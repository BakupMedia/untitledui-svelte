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
		d="M12 9.25H3M12 4H3m18 10.75H3M21 20H3M19.72 2.96l-3.867 2.9c-.29.217-.434.326-.486.459a.5.5 0 0 0 0 .362c.052.133.197.242.486.459l3.867 2.9c.412.309.618.463.79.46a.5.5 0 0 0 .384-.192C21 10.172 21 9.915 21 9.4V3.6c0-.515 0-.773-.106-.908a.5.5 0 0 0-.384-.192c-.172-.004-.378.151-.79.46"
	/>
</svg>
