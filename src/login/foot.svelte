<script>
	import bgVid from '../vid/backVid.mp4';
	import Wlogo from '../img/WhiteLogo.png';

	import Digital from '../img/Digibd.png';
	import logo from '../img/logo.png';
	import Ict from '../img/ICTDiv.png';
	import bgDes from '../img/bgDes.jpg';
</script>

<div class="h-full">
	<footer
		class="bg-white  text-white w-full h-full flex items-center justify-center p-5"
		style="background-image:url({bgDes}); ;"
	>
		<div class="">
			<img src={logo} alt="" class=" w-36" />
		</div>

		<div class="ml-20 text-slate-500">
			<h1 class="text-xl">Team Encrypted Cops</h1>
			<h1 class="text-sm">
				United City, Madani Avenue, <br />
				Badda, Dhaka - 1212, Bangladesh.
			</h1>

			<h1 class="flex mt-5 text-xs">
				<a href="">Terms & Conditions | </a>
				<a href="">About Us |</a>
				<a href=""> Leagal Documents</a>
			</h1>
		</div>
		<div class="ml-20 flex space-x-5">

			<img src={Digital} alt="" class=" w-16 h-16" />
			<img src={Ict} alt="" class=" aspect-videon h-16" />
		</div>
	</footer>
</div>
