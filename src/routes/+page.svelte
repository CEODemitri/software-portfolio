<article class="text-center">
	<h1 class="text-3xl font-bold">Demitri Echols</h1>
	<p>Software Engineer</p>
	<p>Crafting your ideas to the finest precision.</p>
</article>

<ul class="flex gap-6 justify-center">
	<li>Web</li>
	<li>Software</li>
	<li>Design</li>
</ul>

<nav class="flex flex-col">
	<a href="/">Current Resume</a>
	<a href="/">Examples of my Work</a>
	<a href="/">Let Us Connect</a>
</nav>

<main class="my-8">
	<section>
		<h2>Many ways to crack a Problem. Try me.</h2>
		<p>
			For eons, we as humans looked to nature for inspiration, finding it in least likely places,
			returning with solid gold. As a developer, I am creating new bridges better aligning nature
			with technology. How do we make the most of this temporary home, making it better for those
			after us? Let's go for a dive.
		</p>
		<img
			src="https://images.unsplash.com/photo-1698472505070-6d3b90afb530?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8d2hhbGV8ZW58MHx8MHx8fDA%3D"
			alt="me when I am a whale. img by Chinh Le Duc @ unsplash"
			class="w-1/2 h-1/5"
		/>
	</section>
</main>

<style>
	li {
		color: lightgray;
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
