<script>
</script>

<main>
	<div class="md:container md:mx-auto px-4">
		<h1> is project name available? </h1>
		<label for="projectName">Project Name </label>
		<input type="text" id="projectName" placeholder="ipna" class="outline-none">
	</div>
</main>


<style global lang="postcss">

	/* only apply purgecss on utilities, per Tailwind docs */
	/* purgecss start ignore */
	@tailwind base;
	@tailwind components;
	/* purgecss end ignore */
	@tailwind utilities;

	@layer base {
		h1 {
			@apply text-2xl;
			@apply font-bold
		}
		h2 {
			@apply text-xl;
		}
		/* inter-300 - latin */
		@font-face {
			font-family: 'Inter';
			font-style: normal;
			font-weight: 300;
			src: local(''),
			url('assets/fonts/inter-v2-latin-300.woff2') format('woff2'), /* Chrome 26+, Opera 23+, Firefox 39+ */
			url('assets/fonts/inter-v2-latin-300.woff') format('woff'); /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
		}
		/* inter-regular - latin */
		@font-face {
			font-family: 'Inter';
			font-style: normal;
			font-weight: 400;
			src: local(''),
			url('assets/fonts/inter-v2-latin-regular.woff2') format('woff2'), /* Chrome 26+, Opera 23+, Firefox 39+ */
			url('assets/fonts/inter-v2-latin-regular.woff') format('woff'); /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
		}
		/* inter-500 - latin */
		@font-face {
			font-family: 'Inter';
			font-style: normal;
			font-weight: 500;
			src: local(''),
			url('assets/fonts/inter-v2-latin-500.woff2') format('woff2'), /* Chrome 26+, Opera 23+, Firefox 39+ */
			url('assets/fonts/inter-v2-latin-500.woff') format('woff'); /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
		}
		/* inter-600 - latin */
		@font-face {
			font-family: 'Inter';
			font-style: normal;
			font-weight: 600;
			src: local(''),
			url('assets/fonts/inter-v2-latin-600.woff2') format('woff2'), /* Chrome 26+, Opera 23+, Firefox 39+ */
			url('assets/fonts/inter-v2-latin-600.woff') format('woff'); /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
		}
		/* inter-700 - latin */
		@font-face {
			font-family: 'Inter';
			font-style: normal;
			font-weight: 700;
			src: local(''),
			url('assets/fonts/inter-v2-latin-700.woff2') format('woff2'), /* Chrome 26+, Opera 23+, Firefox 39+ */
			url('assets/fonts/inter-v2-latin-700.woff') format('woff'); /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
		}
	}
</style>