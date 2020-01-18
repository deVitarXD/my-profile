<template>
	<div class="profile-container">
		<nav class="nav-bar">
			<div class="container">
				<h2>
					<i class="nes-icon coin"></i>
					Paramas
				</h2>
			</div>
		</nav>
		<div class="container mr-b-25">
			<div class="row">
				<div class="col">
					<i class="nes-bcrikko"></i>
				</div>
				<div class="col-sm-9 col-xs-12">
					<div class="nes-balloon from-left">
						<p>
							I'm Paramas. This is everything about me.
							<i class="nes-icon heart is-small"></i>
						</p>
					</div>
				</div>
			</div>
		</div>
		<div class="container">
			<div class="row">
				<div class="col-md-4 col-sm-12 col-xs-12">
					<div class="nes-container with-title mr-t-25">
						<h3 class="title">Things I do</h3>
						<div class="item">
							<ul class="nes-list is-disc">
								<li>Web Developer</li>
								<li>Dev OPS</li>
							</ul>
						</div>
					</div>
					<div class="nes-container is-dark with-title mr-t-25">
						<h3 class="title">My Socials</h3>
						<div class="item">
							<div class="icon-list">
								<a href="#"><i class="nes-icon facebook is-medium"></i></a>
								<a href="#"><i class="nes-icon instagram is-medium"></i></a>
								<a href="#"><i class="nes-icon github is-medium"></i></a>
							</div>
						</div>
					</div>
				</div>
				<div class="col-md-4 col-sm-12 col-xs-12">Right</div>
			</div>
		</div>
	</div>
</template>

<script>
	import {
		NesInputText,
		NesOctocat
	} from 'vuenes.css'
	
	export default {
		name: "Profile"
	};
</script>
<style>
	.nav-bar {
		padding: 20px;
		border-bottom: 3px solid #ccc;
		margin-bottom: 60px;
	}

	.mr-b-55 {
		margin-bottom: 55px;
	}

	.mr-b-25 {
		margin-bottom: 25px !important;
	}

	.mr-t-25 {
		margin-top: 25px !important;
	}

	.nes-progress {
		height: 25px;
	}
</style>