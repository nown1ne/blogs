
<div><slot></slot></div>

<style>
	div {
		background: orange;
		border: 23px solid orangered;
		padding: 0 15px;
		width: 400px;
		text-align: center;
		transform: translateX(-200px);
		animation: 2s slide infinite alternate ease-in-out;
  }

	@keyframes slide {
		from {
			transform: translateX(-200px)
		}
		to {
			transform: translateX(200px)
		}
	}
</style>
