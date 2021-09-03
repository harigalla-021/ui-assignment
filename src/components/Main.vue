<template>
  <div>
    <header>
      <div id="logo">MADE UP</div>
      <div id="links">
        <a href="/" class="selected-button">For Me</a>
        <a href="/" class="link-button">Jeans</a>
        <a href="/" class="link-button">Shirts</a>
        <a href="/" class="link-button">T-Shirts</a>
        <a href="/" class="link-button">Trousers</a>
        <a href="/" class="link-button">Joggers</a>
        <a href="/" class="link-button">Shorts</a>
      </div>
      <div id="actions">
        <img
          src="~@/assets/Path16.svg"
          alt="search-icon"
          class="action-icons"
        />
        <img
          src="~@/assets/Path19.svg"
          alt="shopping-icon"
          class="action-icons"
        />
        <img
          src="~@/assets/Path35.svg"
          alt="favorite-icon"
          class="action-icons"
        />
        <img
          src="~@/assets/Path41.svg"
          alt="contact-icon"
          class="action-icons"
        />
      </div>
    </header>
    <div class="profile-route">
      Home / My Profile
    </div>
    <nav>
      <div id="profile-info">
        <img src="~@/assets/image1.png" alt="profile-image" />
        <div id="profile-text">
          <div id="profile-name">Grishk</div>
          <div id="profile-email">griiskaim@gmail.com</div>
        </div>
      </div>
      <div id="nav-items">
        <div class="nav-item">
          <div style="float: left;">
            <div class="nav-item-title">My Profile</div>
            <div class="nav-item-text">Notifications, password</div>
          </div>
          <img
            src="~@/assets/Vector.svg"
            alt="accordian-right"
            class="nav-item-icon"
          />
        </div>
        <div class="nav-item">
          <div style="float: left;">
            <div class="nav-item-title">My orders</div>
            <div class="nav-item-text">Already have 12 orders</div>
          </div>
          <img
            src="~@/assets/Vector.svg"
            alt="accordian-right"
            class="nav-item-icon"
          />
        </div>
        <!-- <div>
          <hr />
        </div> -->
        <div class="nav-item">
          <div style="float: left;">
            <div class="nav-item-title">Shipping addresses</div>
            <div class="nav-item-text">3 addresses</div>
          </div>
          <img
            src="~@/assets/Vector.svg"
            alt="accordian-right"
            class="nav-item-icon"
          />
        </div>
      </div>
    </nav>
    <main>
      <section>
        <h1 class="section-heading">My Orders</h1>
        <article class="order-details">
          <img
            src="~@/assets/Rectangle6.png"
            alt="order-image"
            class="order-image"
          />
          <div class="order-info">
            <p class="order-text">Order #12345678</p>
            <p class="order-heading">
              Madeup White Cotton Blend Checkered Slim Fit Shirt
            </p>
            <p class="order-text">Express Delivery by Sat, Aug 30</p>
          </div>
          <div class="order-payment-details">
            <p class="order-text">Credit Card Payment</p>
            <p class="order-amount">Rs 1,899</p>
            <img
              src="~@/assets/Vector2.svg"
              alt="accordian-down"
              class="accordian-down"
            />
          </div>
        </article>
        <hr class="orders-divider" />
        <article class="order-details">
          <img
            src="~@/assets/Rectangle6.png"
            alt="order-image"
            class="order-image"
          />
          <div class="order-info">
            <p class="order-text">Order #12345678</p>
            <p class="order-heading">
              Madeup White Cotton Blend Checkered Slim Fit Shirt
            </p>
            <p class="order-text">Express Delivery by Sun, Aug 31</p>
          </div>
          <div class="order-payment-details">
            <p class="order-text">Credit Card Payment</p>
            <p class="order-amount">Rs 1,899</p>
            <img
              src="~@/assets/Vector2.svg"
              alt="accordian-down"
              class="accordian-down"
            />
          </div>
        </article>
        <hr class="orders-divider" />
        <article class="order-details">
          <img
            src="~@/assets/Rectangle6.png"
            alt="order-image"
            class="order-image"
          />
          <div class="order-info">
            <p class="order-text">Order #12345678</p>
            <p class="order-heading">
              Madeup White Cotton Blend Checkered Slim Fit Shirt
            </p>
            <p class="order-text">Express Delivery by Sun, Aug 16</p>
          </div>
          <div class="order-payment-details">
            <p class="order-text">Credit Card Payment</p>
            <p class="order-amount">Rs 1,899</p>
            <img
              src="~@/assets/Vector2.svg"
              alt="accordian-down"
              class="accordian-down"
            />
          </div>
        </article>
        <hr class="orders-divider" />
        <article class="order-details">
          <img
            src="~@/assets/Rectangle6.png"
            alt="order-image"
            class="order-image"
          />
          <div class="order-info">
            <p class="order-text">Order #12345678</p>
            <p class="order-heading">
              Madeup White Cotton Blend Checkered Slim Fit Shirt
            </p>
            <p class="order-text">Express Delivery by Sat, Aug 15</p>
          </div>
          <div class="order-payment-details">
            <p class="order-text">Credit Card Payment</p>
            <p class="order-amount">Rs 1,899</p>
            <img
              src="~@/assets/Vector2.svg"
              alt="accordian-down"
              class="accordian-down"
            />
          </div>
        </article>
        <hr class="orders-divider" />
      </section>
    </main>
    <footer></footer>
  </div>
</template>

<script>
export default {
  name: 'Main',
}
</script>

<style scoped>
body {
  margin: 0;
}

header {
  width: 100%;
  height: 70px;
  border-bottom: 1px solid #dddddd;
  display: flex;
  align-items: center;
  font-family: 'Jost', sans-serif !important;
}

#logo {
  width: 98px;
  height: 100%;
  background: #e10000;
  font-size: 20px;
  margin-left: 40px;
  padding-top: 14px;
  text-align: center;
  color: #ffffff;
  display: inline-block;
  font-family: 'Scada', sans-serif;
}

#links {
  margin-left: 30px;
  display: inline-block;
}

.link-button {
  text-decoration: none;
  color: #444444;
  padding-left: 76px;
  font-size: 14px;
  line-height: 20.23px;
  font-weight: 400;
  padding-bottom: 2px;
  opacity: 0.9;
}

.selected-button {
  text-decoration: none;
  color: #e10000;
  padding-left: 76px;
  font-size: 14px;
  line-height: 20.23px;
  font-weight: 400;
  padding-bottom: 2px;
  opacity: 0.9;
}

#actions {
  margin-left: 70px;
  display: flex;
  justify-content: flex-end;
}

.action-icons {
  width: 20px;
  height: 20px;
  margin-left: 34px;
}

.profile-route {
  font-size: 12px;
  line-height: 17px;
  color: #777777;
  margin-top: 35px;
  margin-left: 60px;
  font-family: 'Jost', sans-serif !important;
}

nav {
  font-family: 'Jost', sans-serif !important;
  float: left;
}

#profile-info {
  margin-top: 60px;
  margin-left: 67px;
  width: 230px;
}

#profile-text {
  float: right;
  padding-top: 12px;
}

#profile-name {
  color: #333333;
  font-size: 16px;
  line-height: 20px;
}

#profile-email {
  color: #9b9b9b;
  font-size: 14px;
  font-weight: 500;
  line-height: 20px;
}

.nav-item {
  padding-top: 60px;
  margin-left: 67px;
  width: 170px;
  cursor: pointer;
}

.nav-item-title {
  font-size: 16px;
  line-height: 23px;
  font-weight: 600;
  color: #222222;
}

.nav-item-text {
  font-weight: 500;
  font-size: 11px;
  line-height: 16px;
  color: #9b9b9b;
}

.nav-item-icon {
  float: right;
  margin-top: 8px;
}

main {
  float: right;
  margin-right: 20%;
  width: 784px;
  height: 757px;
  border: 1px solid;
  border: 1px solid #333333;
  font-family: 'Jost', sans-serif !important;
  padding-bottom: 45px;
}

.section-heading {
  color: #777777;
  margin-left: 35px;
}

.order-details {
  display: flex;
}

.order-image {
  width: 100px;
  height: 100px;
  padding: 10px;
  background-color: #dddddd;
  margin-left: 30px;
  float: left;
}

.order-heading {
  font-weight: 600;
  font-size: 16px;
  line-height: 23px;
  color: #333333;
}

.order-info {
  margin-left: 20px;
}

.order-text {
  font-size: 14px;
  line-height: 20px;
  color: #777777;
}

.orders-divider {
  width: 90%;
  border: 0;
  border-top: 1px solid #dddddd;
  margin: 25px auto;
}

.order-payment-details {
  margin-left: auto;
  margin-right: 40px;
}

.order-amount {
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 29px;
  color: #333333;
  padding-left: 45px;
}

.accordian-down {
  padding-left: 108px;
}
</style>
