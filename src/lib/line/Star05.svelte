<script>
	/** @type {number} */
	export let size = 24;
	/** @type {string} */
	export let color = "currentColor";
	/** @type {number} */
	export let strokeWidth = 2;
</script>

<svg
	{...$$restProps}
	xmlns="http://www.w3.org/2000/svg"
	width={size}
	height={size}
	fill="none"
	viewBox="0 0 24 24"
>
	<path
		stroke={color}
		stroke-linecap="round"
		stroke-linejoin="round"
		stroke-width={strokeWidth}
		d="m12 2-1.302 5.206c-.254 1.016-.38 1.524-.645 1.937a3 3 0 0 1-.91.91c-.413.265-.921.391-1.937.645L2 12l5.206 1.302c1.016.254 1.524.38 1.937.645a3 3 0 0 1 .91.91c.265.413.391.921.645 1.937L12 22l1.302-5.206c.254-1.016.38-1.524.645-1.937.234-.366.544-.676.91-.91.413-.265.921-.391 1.937-.645L22 12l-5.206-1.302c-1.016-.254-1.524-.38-1.937-.645a3 3 0 0 1-.91-.91c-.265-.413-.391-.921-.645-1.937z"
	/>
</svg>
