<script>
	let seeMobileWarning = $state(true);
</script>

<div class="min-h-screen w-full overflow-hidden bg-[#FFCC90] text-center font-[Urbanist]">
	{#if seeMobileWarning}
		<div
			id="mobile-warning"
			class="absolute inline-flex p-8 md:hidden top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 text-white text-xl z-50 bg-black rounded-lg w-auto h-[50%]"
		>
			<div class="flex flex-col items-center justify-center">
				<p>Hey! Mobile view is kinda cooked rn sorry (T_T)</p>
				<a
					class="border-white border-2 rounded-lg my-8"
					href="#"
					onclick={(e) => {
						e.preventDefault();
						seeMobileWarning = false;
					}}>ok bro</a
				>
			</div>
		</div>
	{/if}

	<div
		style="background-image: url(https://cdn.hackclub.com/019efa09-e174-7ccc-a085-dab6a52b5205/new_tailorgradient.png)"
		class="relative inset-0 flex h-screen w-screen flex-col items-center justify-center bg-cover bg-center"
	>
		<div
			class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 inline-flex m-auto z-0 object-cover flex-col items-center justify-center"
		>
			<div id="window-container" class="inline-flex relative">
				<img
					class=""
					src="https://cdn.hackclub.com/019efa32-9720-777c-8292-313e258bb2ef/tailor_window.png"
					alt=""
				/>

				<img
					src="https://cdn.hackclub.com/019ef80a-a0fc-7fe0-ac3a-fbaaaf6700b0/tailor_title.png"
					alt="Tailor YSWS"
					class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 scroll-title my-4 max-h-[30vh] w-auto md:block z-10 scale-80"
				/>
			</div>
			<p class="z-20 black text-lg md:text-2xl bg-[#FEF7F9] w-full p-2 border-3 border-black">
				you ship a dress up game: we ship sewing materials + steam grants!
			</p>
		</div>
	</div>

	<a href="https://hackclub.com/"
		><img
			src="https://cdn.hackclub.com/019ef82a-1631-740e-9947-d1c2a2d6cd5a/tailortag.png"
			alt="Hack Club flag that links to Hack Club website"
			class="fixed top-0 left-0 w-auto max-h-[20%] md:max-h-[30%]"
		/></a
	>
</div>
