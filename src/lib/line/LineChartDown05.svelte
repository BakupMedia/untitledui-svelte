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
		d="m6 10 3.434 3.434c.198.198.297.297.411.334.1.033.21.033.31 0 .114-.037.213-.136.41-.334l2.87-2.868c.197-.198.296-.297.41-.334a.5.5 0 0 1 .31 0c.114.037.213.136.41.334L18 14m4-2c0 5.523-4.477 10-10 10S2 17.523 2 12 6.477 2 12 2s10 4.477 10 10"
	/>
</svg>
