<script>
	let seeMobileWarning = $state(true);
</script>

<style>
    .custom-cursor {
        cursor: url('https://cdn.hackclub.com/019efb24-f90a-73d6-9c25-73f74ea1b908/tailor_cursor_1idk.png'), auto;
    }

</style>

<div class="custom-cursor p-8 md:p-0 min-h-screen w-full overflow-hidden bg-[#ffcbdc] text-center font-[Urbanist]">
	<div class="md:grid md:grid-cols-[60%_40%] w-full h-auto">
		<!-- left column -->
        <div>
			<div>

				<div
					style="background-image: url(https://cdn.hackclub.com/019efa09-e174-7ccc-a085-dab6a52b5205/new_tailorgradient.png)"
					class="relative inset-0 flex h-screen w-full flex-col items-center justify-center bg-cover bg-center"
				>
					<div
						class="absolute top-1/2 left-1/2 w-full max-w-[90vh] -translate-x-1/2 -translate-y-1/2 inline-flex m-auto z-0 object-cover flex-col items-center justify-center"
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
								id="tailor-title"
                                class="hover:animate-[focus_0.2s_ease-in-out] absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 scroll-title my-4 h-[60%] w-auto object-contain md:block z-10 scale-80"
							/>
						</div>
						<p class="z-20 black text-lg bg-[#FEF7F9] w-full p-2 border-3 border-black">
							you ship a dress up game, we ship you a sewing machine to make the fits irl!
						</p>
					</div>
				</div>

				<a href="https://hackclub.com/"
					><img
						src="https://cdn.hackclub.com/019ef82a-1631-740e-9947-d1c2a2d6cd5a/tailortag.png"
						alt="Hack Club tag that links to Hack Club website"
						id="hc-tag"
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
			<a href="https://forms.hackclub.com/t/bg2eBwEGuvus" class="text-8xl hover:text-[#F3CCE4] hover:underline hover:decoration-dotted hover:decoration-8">submit here<span class="text-4xl align-middle">↗</span></a>
            
            <p>ENDS JULY 8</p>
            
            <div>
                <p class="font-bold">GUIDELINES HELLO<span class="text-[#ffa5dd]">?</span></p>
                <p>track coding hours with <a class="text-[#ffa5dd] hover:underline hover:decoration-dotted" href="https://hackatime.hackclub.com/">Hackatime</a></p>
                <p></p>
                <p>track art hours with <a class="text-[#ffa5dd] hover:underline hover:decoration-dotted" href="https://lapse.hackclub.com/">Lapse</a> • art up to 30% of total hours</p>
                <p><span class="text-[#F3CCE4]">NO AI ART</span> • up to 30% of code can be AI-generated.</p>
                <p>must have <a class="text-[#ffa5dd] hover:underline hover:decoration-dotted" href="https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories/">GitHub repository</a> with readme + <a class="text-[#ffa5dd] hover:underline hover:decoration-dotted" href="https://itch.io/docs/creators/getting-started">itch.io</a> demo link</p>
                <p>only for teens 13-18</p>
            </div>
            <div>
                <p class="font-bold">PRIZES<span class="text-[#ffa5dd]">!</span></p>
                <!-- <p>8 hours • sewing kit and then 20 hours: steam grant</p> -->
                 <p><span class="text-[#F3CCE4]">3 hours</span> = limited edition stickerpack!</p>
                 <p>★ <span class="text-[#F3CCE4]">8 hours (11 total hours after stickers)</span> = sewing kit</p>
                 <p>★ 40 hours = <a class="text-[#ffa5dd] hover:underline hover:decoration-dotted" href="https://www.amazon.com/Brother-XR3774-Full-Featured-Quilting-Instructional/dp/B00MNS60AQ?th=1">sewing machine</a> OR game console grant</p>
                 <p><span class="text-[#F3CCE4]">$2.5 USD/hour</span> = stackable grant to buy fabrics, charms, and buttons!</p>
            </div>
            <div>
                <p>Questions? Ask kaylee@hackclub.com or in <a class="text-[#ffa5dd] hover:underline hover:decoration-dotted" href="https://hackclub.enterprise.slack.com/archives/C0BCDN149RD">#tailor-ysws</a></p>
            </div>
            <img class="px-12 max-w-full h-auto object-contain" src="https://cdn.hackclub.com/019efa6b-4eea-7acd-bc8c-8b09834ce8f8/Made%20With%20Love_texture_text.png" alt="frosty-textured text that reads Made With Love">
		</div>
	</div>
</div>
