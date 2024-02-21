<script>
	export let text;
</script>

<div class="content">
	<div class="text">
		<p>{text}</p>
	</div>
</div>

<style>
	.content {
		box-sizing: border-box;
		width: 220px;
		padding: 8%;
		color: #000;
		transition: .3s;
	}

	.content:hover {
		background-color: #1b1b1b;
		border-radius: 5px;
	}

	.text {
		font-size: 7px;
		height: 280px;
		background-color: #fff;
		padding: 4%;
	}
</style>