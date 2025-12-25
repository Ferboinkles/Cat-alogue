<script>
	import { goto } from "$app/navigation";
</script>

<div>
	<h4 class="text-center text-5xl text-white">
		Welcome to the Cat-alogue!
	</h4>
	<h3 class="text-left text-white text-3xl m-7">
		The Pusheen Family
	</h3>
	<!--Pusheen button-->
	<button
		class="text-left m-4"
		onclick={goto("/pusheen")}
		><img
			alt="pusheen"
			src="/images/pusheen.webp"
		/>
	</button>
	<!--Pip button-->
	<button class="m-4" onclick={goto("/pusheen")}
		><img alt="pusheen" src="/images/pip.webp" />
	</button>
	<!--Stormy button-->
	<button class="m-4" onclick={goto("/pusheen")}
		><img
			alt="pusheen"
			src="/images/stormy.webp"
			hh
		/>
	</button>
</div>
