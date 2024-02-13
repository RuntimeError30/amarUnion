<script>
	import bgVid from '../vid/backVid.mp4';
	import logo from '../img/logo.png';
</script>

<div class="flex items-center justify-center h-full overflow-hidden">
	<div class="bg-white/30 text-white p-5 rounded-xl mt-60 backdrop-blur-sm w-1/4 shadow-2xl">
		<div class="z-50 w-full h-fit text-right flex justify-between">
			<div class="w-full">
				<img src={logo} alt="" class="   w-32 mr-20" />
			</div>
			<div class="w-full">
				<h1 class="text-5xl font-bold">লগ-ইন</h1>
				<h1 class="text-xs font-thin">আপনার এন আইডি নাম্বার এবং পাসওয়ার্ড দিয়ে লগ-ইন করুন</h1>
			</div>
		</div>

		<div class="">
			<form action="/userdashboard" class="space-y-8 w-full">
				<input
					type="text"
					class="bg-transparent outline-none placeholder:text-white focus:border-orange-500 border-b w-full"
					placeholder=" মোবাইল নাম্বার"
				/>

				<input
					type="password"
					class="bg-transparent outline-none placeholder:text-white focus:border-orange-500 border-b w-full"
					placeholder="পাসওয়ার্ড"
				/>
				<a href=""><h1 class="mt-4">পাসওয়ার্ড ভুলে গেছেন?</h1></a>

				<button
					class="border border-orange-500 w-full rounded-xl hover:bg-orange-500 transition-all hover:text-lg ease-in focus:bg-orange-500 p-5"
					>লগইন</button
				>

				<a href="/SignUpUser">নতুন একাউন্ট নিবন্ধন</a>
			</form>
		</div>
	</div>

	<div class="h-screen w-full absolute inset-0 -z-50">
		<video src={bgVid} muted autoplay loop class="h-full w-full object-cover" />
		<div class="absolute inset-0 bg-black opacity-50 h-full w-full" />
	</div>
</div>
