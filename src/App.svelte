<script>
	export let name;
	import Cart from './Cart.svelte';
	import ImageOverlay from './ImageOverlay.svelte';
</script>

<main>
	<div class="product-display">

		<img src="../images/image-product-1.jpg" alt="">
  
		<div class="display-row">
		  <img src="../images/image-product-1-thumbnail.jpg" alt="">
		  <img src="../images/image-product-2-thumbnail.jpg" alt="">
		  <img src="../images/image-product-3-thumbnail.jpg" alt="">
		  <img src="../images/image-product-4-thumbnail.jpg" alt="">
		</div>
  
	  </div>
  
	  <div class="product-info">
  
		<h3>Sneaker Company</h3>
		
		<h1>Fall Limited Edition Sneakers</h1>
		
		<p>
		  These low-profile sneakers are your perfect casual wear companion. Featuring a 
		  durable rubber outer sole, they’ll withstand everything the weather can offer.
		</p>
		  
		<span>
		  $125.00
		</span>
		<span class="discount">
		  50%
		</span>
		<span class="og-price">
		  $250.00
		</span>
		
		<div class="cart-info">
		  <span class="amount">
			0
		  </span>
		  <button>
			Add to cart
		  </button>
		</div>
	  
	  </div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>