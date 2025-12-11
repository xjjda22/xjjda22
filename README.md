<div align="center">
	<img id="random-goku" src="" width="500">
</div>

<script>
	const images = ['goku-90-anim.gif', 'goku-neon-anim.gif','goku-neon-ascii.jpg'];
	const randomImage = images[Math.floor(Math.random() * images.length)];
	document.getElementById('random-goku').src = randomImage;
</script>
