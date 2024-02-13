<script>
	import bgVid from '../vid/backVid.mp4';
	import logo from '../img/logo.png';
</script>

<div class="flex items-center justify-center h-full overflow-hidden">
	<div class="bg-white/30 text-white p-5 rounded-xl mt-60 backdrop-blur-sm w-1/4 shadow-2xl">
		<div class="z-50 w-full h-fit text-right flex justify-between items-center">
			<div class="w-full">
				<a href="/"><img src={logo} alt="" class="   w-32 mr-20" /></a>
			</div>
			<div class="w-full">
				<h1 class="text-5xl font-bold">সাইন-আপ</h1>
			</div>
		</div>

		<div class="">
			<form action="" class="space-y-8 w-full">
				<input
					type="text"
					class="bg-transparent outline-none placeholder:text-white focus:border-orange-500 border-b w-full"
					placeholder="নাম"
				/>

				<div class="flex w-full space-x-2">
					<input
						type="text"
						class="bg-transparent outline-none placeholder:text-white focus:border-orange-500 border-b w-1/2"
						placeholder="স্থায়ী ঠিকানা"
					/>

					<input
						type="text"
						class="bg-transparent outline-none placeholder:text-white focus:border-orange-500 border-b w-1/2"
						placeholder="বর্তমান ঠিকানা"
					/>
				</div>

				<div class="flex w-full space-x-2">
					<input
						type="text"
						class="bg-transparent outline-none placeholder:text-white focus:border-orange-500 border-b w-1/2"
						placeholder="মোবাইল নাম্বার*"
					/>

					<input
						type="text"
						class="bg-transparent outline-none placeholder:text-white focus:border-orange-500 border-b w-1/2"
						placeholder="NID নাম্বার *"
					/>
				</div>

				<input
					type="password"
					class="bg-transparent outline-none placeholder:text-white focus:border-orange-500 border-b w-full"
					placeholder="নতুন পাসওয়ার্ড"
				/>

				<input
					type="password"
					class="bg-transparent outline-none placeholder:text-white focus:border-orange-500 border-b w-full"
					placeholder="নতুন পাসওয়ার্ড কনফার্ম"
				/>

				<button
					class="border border-orange-500 w-full rounded-xl hover:bg-orange-500 transition-all hover:text-xl ease-in focus:bg-orange-500 p-5"
					>নিবন্ধন</button
				>

				<a href="/SignUpUser">লগ-ইন করুন</a>
			</form>
		</div>
	</div>

	<div class="h-screen w-full absolute inset-0 -z-50">
		<video src={bgVid} muted autoplay loop class="h-full w-full object-cover" />
		<div class="absolute inset-0 bg-black opacity-50 h-full w-full" />
	</div>
</div>
