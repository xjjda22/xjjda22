<div align="center">
	<img id="random-goku" src="" width="500" alt="Goku">
</div>

<script>
	(function() {
		const images = ['goku-90-anim.gif', 'goku-neon-anim.gif', 'goku-neon-ascii.jpg'];
		
		function setRandomImage() {
			const imgElement = document.getElementById('random-goku');
			if (imgElement) {
				const randomImage = images[Math.floor(Math.random() * images.length)];
				imgElement.src = randomImage;
			}
		}
		
		// Run when DOM is ready
		if (document.readyState === 'loading') {
			document.addEventListener('DOMContentLoaded', setRandomImage);
		} else {
			setRandomImage();
		}
	})();
</script>
