<svelte:head>
	<title>CSS border-shape</title>
	<meta name="description" content="border-shape is a powerful upcoming CSS primitive that defines a custom shape for an element's border" />
	<meta property="og:url" content="https://border-shape.com/" />
	<meta property="og:type" content="website" />
	<meta name="og:title" content="CSS border-shape" />
	<meta name="og:description" content="border-shape is a powerful upcoming CSS primitive that defines a custom shape for an element's border." />
	<meta name="og:image" content="https://border-shape.com/border-shape.png" />
	<meta name="twitter:card" content="summary_large_image" />
	<meta property="twitter:domain" content="border-shape.com" />
	<meta property="twitter:url" content="https://border-shape.com/" />
	<meta name="twitter:title" content="CSS border-shape" />
	<meta name="twitter:description" content="border-shape is a powerful upcoming CSS primitive that defines a custom shape for an element's border." />
	<meta name="twitter:image" content="https://border-shape.com/border-shape.png" />
</svelte:head>

<h1>border-shape</h1>
<p>border-shape is a powerful upcoming CSS primitive that defines a custom shape for an element's border.</p>
<p>Una Kravets has written and excellent post about it at <a href="https://una.im/border-shape">https://una.im/border-shape</a>.</p>
<p>I have created a demo at <a href="https://codepen.io/ludviglindblom/pen/gbwbdaR">https://codepen.io/ludviglindblom/pen/gbwbdaR</a>.</p>
<p>You can also check out the <a href="https://drafts.csswg.org/css-borders-4/#border-shape">specification</a>.</p>
<p><i>Note that this feature is still experimental and currently only available in Chrome 146+ (Canary and Beta builds) with the experimental web platform features flag turned on.</i></p>

<style>
	:global(body) {
		box-sizing: border-box;
		width: 100%;
		max-width: 60rem;
		margin: 0 auto;
		padding: 1rem;
		font-family:
			system-ui,
			-apple-system,
			BlinkMacSystemFont,
			'Segoe UI',
			Roboto,
			Oxygen,
			Ubuntu,
			Cantarell,
			'Open Sans',
			'Helvetica Neue',
			sans-serif;
	}
	p {
		line-height: 1.3;
	}
</style>
