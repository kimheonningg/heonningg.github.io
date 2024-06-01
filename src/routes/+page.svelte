<script>
	import myphoto_pink from '$lib/images/myphoto/myphoto_pink.jpg';
	import ContactBox from './ContactBox.svelte';
</script>

<svelte:head>
	<title>Heonningg's Blog</title>
	<meta name="description" content="heonningg's personal blog" />
</svelte:head>

<main>
	<h1> Huiwone (Hannah) Kim | 김희원 </h1>
	<div class ="basic-info">
		<img src = {myphoto_pink} alt = "Photo Of Me"/>
		<ContactBox />
	</div>
</main>

<style>
	main {
		text-align: center;
	}
	h1 {
		font-weight: 800;
	}
	
	.basic-info {
		display: flex;
		justify-content: center;
		align-items: center;
	}

	img {
		width: 30%;
		height: 30%;
		margin-right: 5%;
	}
</style>