<section>
	<div class="sign">
		<span>GIRL,</span>
		<span>its just</span>
	</div>
	<div class="scrolling-text-container">
		<div class="scrolling-text">
			<span class="scrolling-text-1">
				wwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwww
			</span>
			<span class="scrolling-text-2">
				wwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwwww
			</span>
		</div>
	</div>
	<a href="https://www.youtube.com/watch?v=xM93w4mN2ws" target="_blank" rel="noopener noreferrer"
		>Credit to Drawfee</a
	>
</section>

<style>
	section {
		position: relative;
		display: grid;
		place-content: center;
		height: 100vh;
	}

	a {
		position: absolute;
		bottom: 0;
		left: 0;
		right: 0;
		text-align: center;
		color: #fff;
	}

	.scrolling-text-container {
		display: flex;
		overflow: hidden;
		width: 100%;
		position: relative;
	}

	.scrolling-text {
		display: inline-flex;
		font-size: 10rem;
		line-height: 1;
		background-color: #59d2c0;
		margin: 0;
		margin-top: 1rem;
		padding: 0;
	}

	.scrolling-text-1 {
		animation-delay: 0s;
		animation: scroll 500s linear infinite;
	}
	.scrolling-text-2 {
		animation-delay: 500s;
		animation: scroll 500s linear infinite;
	}

	@keyframes scroll {
		0% {
			transform: translateX(0);
		}
		100% {
			transform: translateX(-100%);
		}
	}

	/*-- Sign Styles --*/
	.sign {
		min-height: 100%;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
	.sign span {
		font-size: 5.6rem;
		text-align: center;
		line-height: 1;
		color: #fff;
		animation: neon 0.08s ease-in-out infinite alternate;
	}
	/*-- Animation Keyframes --*/
	@keyframes neon {
		from {
			text-shadow: 0 0 6px rgba(228, 202, 215, 0.92), 0 0 30px rgba(228, 202, 226, 0.34),
				0 0 12px rgba(242, 30, 185, 0.52), 0 0 21px rgba(242, 30, 185, 0.92),
				0 0 34px rgba(242, 30, 185, 0.78), 0 0 54px rgba(242, 30, 185, 0.92);
		}
		to {
			text-shadow: 0 0 6px rgba(228, 202, 215, 0.92), 0 0 30px rgba(228, 202, 226, 0.34),
				0 0 12px rgba(242, 30, 185, 0.58), 0 0 22px rgba(242, 30, 185, 0.84),
				0 0 38px rgba(242, 30, 185, 0.88), 0 0 60px rgba(242, 30, 185, 1);
		}
	}
</style>
