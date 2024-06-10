<template>
  <q-page class="flex flex-center">
    <div class="container1 flex items-center q-my-lg">
      <div class="product">
        <img src="https://content-prod-live.cert.starbucks.com/binary/v2/asset/137-92442.jpg" alt="">
      </div>
      <div class="text-container">
        <span class="text-h5 text-weight-bold text-primary q-pa-md">Enjoy half off your first
          drink</span>
        <div class="text-center text-primary text-h6 q-py-lg">
          Download the app for half off a handcrafted drink during your first week.* Plus, tap into mobile ordering,
          exclusive offers and so much more.
        </div>
        <q-btn rounded outline label="Sign up here" no-caps color="primary" class="signUp" />
      </div>
    </div>

    <div class="container2 flex items-center q-my-lg">
      <div class="text-container">
        <span class="text-h3 text-weight-bold text-white text-center">Starbucks® Summer
          Game</span>
        <div class="text-center text-white text-h4 q-py-lg">
          Play for a chance to win a trip for two to Costa Rica and millions of other prizes!**
        </div>
        <q-btn rounded outline label="Sign up here" no-caps color="white" class="signUp" />
      </div>
      <div class="product">
        <img src="https://content-prod-live.cert.starbucks.com/binary/v2/asset/137-92093.png" alt="">
      </div>
    </div>

    <div class="container3 flex items-center q-my-lg">
      <div class="product">
        <img src="https://content-prod-live.cert.starbucks.com/binary/v2/asset/137-92096.jpg" alt="">
      </div>
      <div class="text-container">
        <span class="text-h3 text-weight-bold text-white text-center">Summertime crew</span>
        <div class="text-center text-white text-h4 q-py-lg">
          Super chill flavors, all lined up and ready for fun.
        </div>
        <q-btn rounded outline label="Order now" no-caps color="white" class="signUp" />
      </div>
    </div>

    <div class="container4 flex items-center q-my-lg">
      <div class="text-container">
        <span class="text-h4 text-weight-bold text-dark text-center">The best offers are in the
          app</span>
        <div class="text-center text-dark text-h5 q-py-lg">
          Get the app for refreshing offers this summer. Grab a friend, because we're treating you to special deals on
          your go-to drinks and seasonal favorites.
        </div>
        <q-btn rounded outline label="Get the app" no-caps color="dark" class="signUp" />
      </div>
      <div class="product">
        <img src="https://content-prod-live.cert.starbucks.com/binary/v2/asset/137-92345.jpg" alt="">
      </div>
    </div>

    <div class="container5 flex items-center q-my-lg">
      <div class="product">
        <img src="https://content-prod-live.cert.starbucks.com/binary/v2/asset/137-92264.jpg" alt="">
      </div>
      <div class="text-container">
        <span class="text-h5 text-weight-bold text-primary text-center">Summertime, when the
          sippin’ (and saving) is easy</span>
        <div class="text-center text-primary text-h6 q-py-lg">
          Now through 6/14, you can get 20% off your first Starbucks order with DoorDash (up to $5 off).***
        </div>
        <q-btn rounded outline label="Order now" no-caps color="primary" class="signUp" />
      </div>
    </div>

    <div class="container6 flex items-center q-my-lg">
      <div class="text-container">
        <span class="text-h4 text-weight-bold text-primary text-center">Personal cups for good</span>
        <div class="text-center text-primary text-h5 q-py-lg">
          Your choice is a positive and responsible one—because bringing your clean reusable cup helps our planet.
        </div>
        <q-btn rounded outline label="Learn more" no-caps color="primary" class="signUp" />
      </div>
      <div class="product">
        <img src="https://content-prod-live.cert.starbucks.com/binary/v2/asset/137-92108.jpg" alt="">
      </div>
    </div>

    <div class="column q-pb-xl">
      <div class="textBottom flex flex-center">
        <div class="text-body2 text-weight-medium text-center q-pa-xl text-bottom1" style="max-width: 65%">
          *50% off handcrafted drink valid for 7 days from sign up, at participating stores. Must sign up via promo link
          by June 30, 2024 to be eligible. Limit one per member. Excludes delivery orders, alcohol, ready to drink and
          bottled beverages.
        </div>
      </div>

      <div class="textBottom flex flex-center">
        <div class="text-body2 text-weight-medium text-center q-pa-xl text-bottom1" style="max-width: 65%">
          **NO PURCHASE NECESSARY. Participating stores only. Starbucks Partners (employees) are not eligible to win
          Sweepstakes prizes. Ends 6/17/24. To play and for <a href="#">Official Rules,</a> visit
          <a href="">starbuckssummergame.com.</a>
        </div>
      </div>

      <div class="textBottom flex flex-center">
        <div class="text-body2 text-weight-medium text-center q-pa-xl text-bottom1" style="max-width: 65%">
          ***20% off your first Starbucks order on DoorDash on 6/1/24 - 6/14/24 only. Max discount of $5. Fees and taxes
          still apply. Limit one per customer. Menu limited. See the DoorDash app for availability & restrictions.
        </div>
      </div>
    </div>



  </q-page>
</template>

<script setup>
defineOptions({
  name: 'IndexPage'
});
</script>

<style scoped>
.container1 {
  align-items: center;
  background-color: #c0e8a6;
  max-width: 80%;
}

.container2 {
  display: flex;
  align-items: center;
  background-color: #c300bd;
  max-width: 80%;
}

.container3 {
  display: flex;
  align-items: center;
  background-color: #0021db;
  max-width: 80%;
}

.container4 {
  display: flex;
  align-items: center;
  background-color: #bbf2d1;
  max-width: 80%;
}

.container5 {
  display: flex;
  align-items: center;
  background-color: #98cee3;
  max-width: 80%;
}

.container6 {
  display: flex;
  align-items: center;
  background-color: #97d8b1;
  max-width: 80%;
}

.product {
  flex: 1;
}

.product img {
  display: block;
  max-width: 100%;
  height: auto;
}

.text-container {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.text-container .text-center {
  max-width: 58%;
  margin: 0 auto;
}

.signUp {
  font-size: 16px;
  margin-bottom: 20px;
}

@media (max-width: 768px) {

  .container1,
  .container3,
  .container5 {
    flex-direction: column;
    max-width: 100%;
  }

  .product {
    margin-bottom: 20px;
  }

  .text-container .text-center {
    max-width: 100%;
  }

  .text-bottom1 {
    max-width: 100% !important;
  }

  .container2,
  .container4,
  .container6 {
    flex-direction: column-reverse;
    max-width: 100%;
  }
}
</style>
