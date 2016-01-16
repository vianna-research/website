status: hidden
title: SoundCrowd

This is a demo page, built to showcase – or better to hear-case – a possible audio questionary.


<div>
<audio id="soundcheck1" src="/__downloads/test.wav" preload="auto"></audio>
<audio id="soundcheck2" src="/__downloads/test-44100-le-1ch-4bytes" preload="auto"></audio>
<audio id="soundcheck3" src="/__downloads/ds_china.wav" preload="auto"></audio>


<div class="btn-group btn-group-lg" role="group" aria-label="...">
  <button type="button" class="btn btn-default" onmousedown="play_sound1();">Sound 1</button>
  <button type="button" class="btn btn-default" onmousedown="play_sound2();">Sound 2</button>
  <button type="button" class="btn btn-default" onmousedown="play_sound3();">Sound 3</button>
</div>

<script type="text/javascript">
	function play_sound1() {
		document.getElementById('soundcheck1').play();
	}
	function play_sound2() {
		document.getElementById('soundcheck2').play();
	}
	function play_sound3() {
		document.getElementById('soundcheck3').play();
	}
</script>




</div>


<div id="s1">

</div>
