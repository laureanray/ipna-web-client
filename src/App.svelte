<script>
	export let name;
</script>

<main>
	<h1> Hello svelte! </h1>
	<table class="table-auto border">
		<thead>
		<tr>
			<th>Title</th>
			<th>Author</th>
			<th>Views</th>
		</tr>
		</thead>
		<tbody>
		<tr>
			<td>Intro to CSS</td>
			<td>Adam</td>
			<td>858</td>
		</tr>
		<tr class="bg-emerald-200">
			<td>A Long and Winding Tour of the History of UI Frameworks and Tools and the Impact on Design</td>
			<td>Adam</td>
			<td>112</td>
		</tr>
		<tr>
			<td>Intro to JavaScript</td>
			<td>Chris</td>
			<td>1,280</td>
		</tr>
		</tbody>
	</table>
</main>


<style global lang="postcss">

	/* only apply purgecss on utilities, per Tailwind docs */
	/* purgecss start ignore */
	@tailwind base;
	@tailwind components;
	/* purgecss end ignore */
	@tailwind utilities;

	@layer base {
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