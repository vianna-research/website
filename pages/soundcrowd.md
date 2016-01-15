status: hidden
title: SoundCrowd

This is a demo page, built to showcase – or better to hear-case – a possible audio questionary.


<div>

<audio id="soundcheck1" src="/__downloads/test.wav" preload="auto"></audio>
<a href="javascript:play_single_sound();">Click here to play sound</a>
<script type="text/javascript">
	function play_single_sound() {
		document.getElementById('soundcheck1').play();
	}
</script>


</div>
