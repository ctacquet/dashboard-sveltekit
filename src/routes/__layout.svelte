<script>
import '../app.css';
import "flowbite/dist/flowbite.css";
import Navbar from "$lib/Navbar.svelte";
import Sidebar from '$lib/Sidebar.svelte';
import Breadcrumb from '$lib/Breadcrumb.svelte';
</script>


<Navbar />
<main class="flex">
	<Sidebar />
	<div class="flex-1">
		<Breadcrumb />
		<div class="p-8">
			<slot />
		</div>
	</div>
</main>
