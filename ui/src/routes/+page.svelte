<div class="container max-w-5xl mx-auto py-5">
	<h1 class="text-white text-7xl font-extrabold">ASK MY DOCS</h1>
	<div class="my-4">
		<div class="container max-w-md">
			<h2 class="text-white text-3xl font-semibold">UPLOAD FILES</h2>
			<div class="my-4 drop-shadow-sm">
				<div class="flex items-center justify-center w-full">
					<label
						for="dropzone-file"
						class="flex flex-col items-center justify-center w-full h-64 cursor-pointer rounded-md bg-white hover:bg-gray-300"
					>
						<div class="flex flex-col items-center justify-center pt-5 pb-6">
							<svg
								aria-hidden="true"
								class="w-10 h-10 mb-3 text-gray-400"
								fill="none"
								stroke="currentColor"
								viewBox="0 0 24 24"
								xmlns="http://www.w3.org/2000/svg"
								><path
									stroke-linecap="round"
									stroke-linejoin="round"
									stroke-width="2"
									d="M7 16a4 4 0 01-.88-7.903A5 5 0 1115.9 6L16 6a5 5 0 011 9.9M15 13l-3-3m0 0l-3 3m3-3v12"
								/></svg
							>
							<p class="mb-2 text-sm text-black">
								<span class="font-semibold">Click to upload</span> or drag and drop
							</p>
							<p class="text-xs text-black">DOCX, PDF (MAX 5 Documents)</p>
						</div>
						<input id="dropzone-file" type="file" class="hidden" />
					</label>
				</div>
			</div>
		</div>
		<div class="container max-w-md">
			<h2 class="text-white text-3xl font-semibold">ASK QUESTIONS</h2>
			<div class="bg-white min-h-full my-4 rounded-md" />
			<div class="my-4 flex justify-start">
				<input
					placeholder="Ask me!"
					class="w-full rounded-md pl-2 text-lg caret-slate-800 border-0 mr-2"
				/>
				<button
					class="bg-gradient-to-r rounded-md w-12 h-10 text-center text-lg text-white font-extrabold from-purple-600 to-blue-500"
				>
					?
				</button>
			</div>
		</div>
	</div>
</div>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.black);
	}
</style>
