<template>
  <div id="nav-bar">
    <router-link to="/products" id="products-link">
      <h1>Store</h1>
    </router-link>
    <img src="bmw.jpg" alt="BMW" width="70" height="70">
    <router-link to="/cart" id="cart-link">
      <button>Shopping Cart</button>
    </router-link>
  </div>
</template>

<script>
export default {
    name: 'NavBar',
}
</script>

<style scoped>
  #nav-bar {
    border-bottom: 1px solid #ddd;
    height: 75px;
    width: 100%;
  }

  #products-link {
    text-align: center;
    display: block;
    color: #0000A0;
    font-size: 16px;
    left: 100px;
    position: absolute;
    top: 20px;
    text-decoration: none;
  }

  #products-link h1 {
      margin: 0;
  }

  #cart-link {
    position: absolute;
    right: 16px;
    top: 16px;
  }
</style>
