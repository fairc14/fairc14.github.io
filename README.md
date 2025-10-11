# fairc14.github.io

<!DOCTYPE html>

<html>
	<head>
		
	</head>
	<body>
		<div>
			<audio id="audio" src="pity.mp3" autostart="false"></audio>
			<button onclick="clickpity();">pity</button>
			<!-- top left button -->
		</div>
		<div>
			<audio id="audio2" src="shut.mp3" autostart="false"></audio>
			<button onclick="clickshut();">shut up</button>
			<!-- bottom right button -->
		</div>
		<div>
			<audio id="audio3" src="talk.mp3" autostart="false"></audio>
			<button onclick="clicktalk();">no backtalk</button>
			<!-- top right button -->
		</div>
		<div>
			<audio id="audio4" src="mad.mp3" autostart="false"></audio>
			<button onclick="clickmad();">don't make me mad</button>
			<!-- middle right button -->
		</div>
		<div>
			<audio id="audio5" src="jibber.mp3" autostart="false"></audio>
			<button onclick="clickjibber();">quit yo jibber jabber</button>
			<!-- middle left button -->
		</div>
		<div>
			<audio id="audio6" src="name.mp3" autostart="false"></audio>
			<button onclick="clickname();">first name</button>
			<!-- bottom left button -->
		</div>
	<script>
		function clickpity(){
			var sound = document.getElementById('audio');
			sound.play()
		}
		function clickshut(){
			var sound = document.getElementById('audio2');
			sound.play()
		}
		function clicktalk(){
			var sound = document.getElementById('audio3');
			sound.play()
		}
		function clickmad(){
			var sound = document.getElementById('audio4');
			sound.play()
		}
		function clickjibber(){
			var sound = document.getElementById('audio5');
			sound.play()
		}
		function clickname(){
			var sound = document.getElementById('audio6');
			sound.play()
		}
	</script>
	</body>

</html>
