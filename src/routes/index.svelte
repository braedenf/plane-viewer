<!-- Use it like any other HTML element -->
<model-viewer
	class="w-screen h-screen"
	bounds="tight"
	src="models/bomber.glb"
	ar
	ar-modes="webxr scene-viewer quick-look"
	camera-controls
	shadow-intensity="2.3"
	camera-orbit="-114.8deg 82.46deg auto"
	exposure="0.93"
>
	<button
		slot="ar-button"
		class="absolute top-8 left-1/2 transform -translate-x-1/2 -translate-y-1/2 bg-indigo-500 hover:bg-indigo-600 transition py-2 px-3 rounded-full text-white font-bold"
	>
		<div class="flex gap-2">
			<svg
				xmlns="http://www.w3.org/2000/svg"
				class="h-6 w-6"
				fill="none"
				viewBox="0 0 24 24"
				stroke="currentColor"
			>
				<path
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4"
				/>
			</svg>
			<label for="ar-button">Activate AR</label>
		</div>
	</button>
</model-viewer>
