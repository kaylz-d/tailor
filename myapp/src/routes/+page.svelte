<script>
	let seeMobileWarning = $state(true);
</script>

<div class="p-8 md:p-0 min-h-screen w-full overflow-hidden bg-[#ffcbdc] text-center font-[Urbanist]">
	<div class="md:grid md:grid-cols-[60%_40%] w-full h-auto">
		<!-- left column -->
        <div>
			<div>

				<div
					style="background-image: url(https://cdn.hackclub.com/019efa09-e174-7ccc-a085-dab6a52b5205/new_tailorgradient.png)"
					class="relative inset-0 flex h-screen w-full flex-col items-center justify-center bg-cover bg-center"
				>
					<div
						class="absolute top-1/2 left-1/2 w-full max-w-[80vh] -translate-x-1/2 -translate-y-1/2 inline-flex m-auto z-0 object-cover flex-col items-center justify-center"
					>
						<div id="window-container" class="inline-flex relative">
							<!-- window pic -->
                            <img
								class=""
								src="https://cdn.hackclub.com/019efa32-9720-777c-8292-313e258bb2ef/tailor_window.png"
								alt=""
							/>

							<img
								src="https://cdn.hackclub.com/019ef80a-a0fc-7fe0-ac3a-fbaaaf6700b0/tailor_title.png"
								alt="Tailor YSWS"
								class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 scroll-title my-4 h-[60%] w-auto object-contain md:block z-10 scale-80"
							/>
						</div>
						<p class="z-20 black text-lg bg-[#FEF7F9] w-full p-2 border-3 border-black">
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
		</div>
		<!-- right side -->
        <div class="bg-[#474243] text-white flex flex-col justify-center items-center gap-12">
			<a href="#" class="text-9xl hover:text-[#F3CCE4] hover:underline hover:decoration-dotted hover:decoration-8">submit here idk</a>
            <div>
                <p class="font-bold">GUIDELINES HELLO<span class="text-[#ffa5dd]">?</span></p>
                <p>haiii lol</p>
            </div>
            <div>
                <p class="font-bold">PRIZES<span class="text-[#ffa5dd]">!</span></p>
                <!-- <p>8 hours • sewing kit and then 20 hours: steam grant</p> -->
                 <p>budget budget budget</p>
            </div>
            <img class="px-12 max-w-full h-auto object-contain" src="https://cdn.hackclub.com/019efa6b-4eea-7acd-bc8c-8b09834ce8f8/Made%20With%20Love_texture_text.png" alt="frosty-textured text that reads Made With Love">
		</div>
	</div>
</div>
