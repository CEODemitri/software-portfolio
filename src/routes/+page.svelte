<article class="text-center">
	<h1 class="text-5xl">Demitri Echols</h1>
	<p>Software Engineer</p>
	<p>Crafting your ideas to the finest precision.</p>
</article>

<ul class="flex gap-6 justify-center mt-16">
	<li>Web</li>
	<li>Software</li>
	<li>Design</li>
</ul>

<a href="/">Resume</a>
<a href="/">Projects</a>

<style>
	li {
		color: lightgray;
		cursor: pointer;
		position: relative;
		display: inline-block;

		&:after {
			content: '';
			position: absolute;
			bottom: 0;
			left: 0;
			width: 0;
			height: 3px;
			background-color: maroon;
		}

		&:hover {
			animation: darken 1500ms ease-in forwards;
		}

		&:hover::after {
			width: 100%;
			animation: underline 1s ease-in forwards;
		}
	}

	@keyframes darken {
		from {
			color: darkgrey;
		}
		to {
			color: #000;
			font-weight: bold;
		}
	}

	@keyframes underline {
		0% {
			width: 0%;
		}
		50% {
			text-decoration: underline;
		}
		100% {
			width: 100%;
		}
	}
</style>
