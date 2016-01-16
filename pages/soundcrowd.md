status: hidden
title: SoundCrowd

This is a demo page, built to showcase – or better to hear-case – a possible audio questionary.

Technically, the ingredients are here:

-   Preloading sound files, so there is no waiting during the questionary
-   Play sound on the mouse down event (because that allows more precise timing that a normal "click" which waits till the button is release)
-   Measuring the elapsed time from the click on a "Play sound x" button till one of the answer Buttons.

We could also do reaction/timing tests. Something along the lines: After pressing start, we use a random delay until we play a sound (or show a visual marker) and ask the users to "Press as quickly as possible when you hear a sound".


<div class="jumbotron">
	<audio id="soundcheck1" src="/__downloads/test.wav" preload="auto"></audio>
	<audio id="soundcheck2" src="/__downloads/test-44100-le-1ch-4bytes.wav" preload="auto"></audio>
	<audio id="soundcheck3" src="/__downloads/ds_china.wav" preload="auto"></audio>
	
	<h3>Press "Play sound" then, answer A or B.</h3>
	
	<div class="btn-group btn-group-lg" role="group" aria-label="...">
	  <button type="button" class="btn btn-default" onmousedown="play_sound1();">Play sound 1</button>
	  <button type="button" class="btn btn-default" onmousedown="play_sound2();">Play sound 2</button>
	  <button type="button" class="btn btn-default" onmousedown="play_sound3();">Play sound 3</button>
	</div>
	
	<script type="text/javascript">
		var time_start = new Date().getTime();
	
		function play_sound1() {
			time_start = new Date().getTime();
			document.getElementById('soundcheck1').play();
		}
		function play_sound2() {
			time_start = new Date().getTime();
			document.getElementById('soundcheck2').play();
		}
		function play_sound3() {
			time_start = new Date().getTime();
			document.getElementById('soundcheck3').play();
		}
	</script>

	<p></p>

	<div id="time_display" class="alert alert-success" role="alert">...waiting for answer A or B. </div>

	<div class="btn-group btn-group-lg" role="group" aria-label="...">
	  <button type="button" class="btn btn-default btn-primary" onmousedown="stop_timer('A');">  A  </button>
	  <button type="button" class="btn btn-default btn-primary" onmousedown="stop_timer('B');">  B  </button>
	</div>
	<script type="text/javascript">
	
		function stop_timer(ans) {
			var now = new Date().getTime();
			var time_delta = now - time_start;
			document.getElementById("time_display").innerHTML = "You answerd " +ans+ " in "+time_delta.toString() + " ms" ;
		}
		
		function checkKey(e) {
		    e = e || window.event;
    		    if (e.keyCode == 37) {stop_timer('A')};
    		    if (e.keyCode == 39) {stop_timer('B')};
		}

		document.onkeydown = checkKey;
		
	</script>


</div>

