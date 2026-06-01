<style>
.bd-site {
  font-family: Georgia, 'Times New Roman', serif;
  color: #3b1f1f;
  background: #fffaf2;
}

.bd-hero {
  background: linear-gradient(rgba(90, 18, 22, .88), rgba(60, 20, 15, .9)),
              url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c');
  background-size: cover;
  background-position: center;
  color: white;
  padding: 95px 25px;
  text-align: center;
  border: 6px solid #c9a24a;
  border-radius: 12px;
}

.bd-tag {
  color: #f4d06f;
  font-weight: bold;
  letter-spacing: 1px;
  text-transform: uppercase;
}

.bd-hero h1 {
  font-size: 64px;
  margin: 10px 0;
  color: #f4d06f;
  text-shadow: 2px 2px #4b1115;
}

.bd-sub {
  max-width: 850px;
  margin: 0 auto 30px;
  font-size: 20px;
  line-height: 1.6;
}

.bd-btn {
  display: inline-block;
  background: #8b1e24;
  color: #fff !important;
  border: 2px solid #f4d06f;
  padding: 14px 30px;
  border-radius: 4px;
  text-decoration: none !important;
  font-weight: bold;
}

.bd-section {
  padding: 60px 20px;
  text-align: center;
}

.bd-section h2 {
  font-size: 38px;
  color: #8b1e24;
  margin-bottom: 25px;
}

.bd-section p {
  max-width: 850px;
  margin: auto;
  font-size: 18px;
  line-height: 1.7;
}

.bd-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
  gap: 16px;
  max-width: 1050px;
  margin: auto;
}

.bd-grid a {
  display: block;
  background: #ffffff;
  padding: 22px;
  border-radius: 8px;
  color: #5a1216 !important;
  text-decoration: none !important;
  font-weight: bold;
  border: 2px solid #c9a24a;
  box-shadow: 0 4px 10px rgba(91, 35, 20, .12);
  transition: .2s ease;
}

.bd-grid a:hover {
  background: #8b1e24;
  color: #fff !important;
  transform: translateY(-3px);
}

.bd-reviews {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 20px;
  max-width: 1100px;
  margin: auto;
}

.bd-review {
  background: #fff;
  border: 2px solid #c9a24a;
  padding: 24px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(91, 35, 20, .12);
  line-height: 1.6;
}

.bd-review strong {
  color: #8b1e24;
}

.bd-cta {
  background: #8b1e24;
  color: #fff;
  padding: 70px 25px;
  text-align: center;
  border: 5px solid #c9a24a;
  border-radius: 12px;
}

.bd-cta h2 {
  font-size: 38px;
  color: #f4d06f;
}

@media (max-width: 600px) {
  .bd-hero h1 {
    font-size: 42px;
  }

  .bd-sub {
    font-size: 17px;
  }
}
</style>

<div class="bd-site">

  <section class="bd-hero">
    <p class="bd-tag">Great Deals Every Day</p>
    <h1>Bargain Depot</h1>
    <p class="bd-sub">
      Furniture, clothing, shoes, jewelry, housewares, kitchen items, mattresses, food, drinks, Middle Eastern specialties, and much more.
    </p>
    <a href="#categories" class="bd-btn">Shop Categories</a>
  </section>

  <section id="categories" class="bd-section">
    <h2>What You'll Find</h2>

    <div class="bd-grid">
      <a href="/furniture/">🛋 Furniture</a>
      <a href="/mens-clothing/">👕 Men's Clothing</a>
      <a href="/womens-clothing/">👗 Women's Clothing</a>
      <a href="/kids-clothing/">🧒 Kids' Clothing</a>
      <a href="/shoes/">👟 Shoes</a>
      <a href="/jewelry/">💍 Jewelry</a>
      <a href="/accessories/">👜 Accessories</a>
      <a href="/housewares/">🏠 Housewares</a>
      <a href="/kitchen-items/">🍳 Kitchen Items</a>
      <a href="/beds-mattresses/">🛏 Beds & Mattresses</a>
      <a href="/tables/">🪑 Tables</a>
      <a href="/bakery/">🥐 Bakery Items</a>
      <a href="/food/">🍽 Breakfast, Lunch & Dinner</a>
      <a href="/drinks/">🥤 Drinks</a>
      <a href="/middle-eastern-food/">🥙 Middle Eastern Food</a>
    </div>
  </section>

  <section class="bd-section">
    <h2>About Bargain Depot</h2>
    <p>
      Bargain Depot is your local destination for great bargains, quality finds, and new items arriving regularly. From furniture and clothing to household goods and fresh food, we offer something for the whole family at affordable prices.
    </p>
  </section>

  <section id="reviews" class="bd-section">
    <h2>What Our Customers Say</h2>

    <div class="bd-reviews">
      <div class="bd-review">“Best services provided by Sameer. He is very friendly and helpful. Best bargains in everything.”<br><strong>— Mercy</strong></div>
      <div class="bd-review">“Always find great bargains there for name brand items. I check them out once a week!”<br><strong>— Paulette McGuinness</strong></div>
      <div class="bd-review">“Great place to find great furniture with a good price.”<br><strong>— Nabila Idbelaid</strong></div>
      <div class="bd-review">“Nice staff and great deals.”<br><strong>— Mariam Mohamed</strong></div>
      <div class="bd-review">“Good things with very good prices!”<br><strong>— Dani Evan</strong></div>
      <div class="bd-review">“Getting some great new items.”<br><strong>— Michaelle Louis-Charles</strong></div>
    </div>
  </section>

  <section class="bd-cta">
    <h2>Visit Bargain Depot Today</h2>
    <p>Find amazing bargains on furniture, clothing, food, and more.</p>
    <br>
    <a href="#categories" class="bd-btn">Browse Categories</a>
  </section>

</div>
