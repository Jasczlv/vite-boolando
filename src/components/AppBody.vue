<script>
export default {
  data() {
    return {
      products: [
        {
          "id": 1,
          "frontImage": "1.webp",
          "backImage": "1b.webp",
          "brand": "Levi's",
          "name": "Relaxed Fit",
          "price": 29.99,
          "isInFavorites": true,
          "badges": [
            {
              "type": "tag",
              "value": "Sostenibilità",
            },
            {
              "type": "discount",
              "value": "-50%",
            },
          ],
        },
        {
          "id": 2,
          "frontImage": "2.webp",
          "backImage": "2b.webp",
          "brand": "Guess",
          "name": "Roses Tee",
          "price": 20.99,
          "isInFavorites": true,
          "badges": [
            {
              "type": "discount",
              "value": "-30%",
            },
          ],
        },
        {
          "id": 3,
          "frontImage": "3.webp",
          "backImage": "3b.webp",
          "brand": "Come Zucchero Filato",
          "name": "Voglia di colori pastello",
          "price": 129.99,
          "isInFavorites": false,
          "badges": [
            {
              "type": "discount",
              "value": "-30%",
            },
          ],
        },
        {
          "id": 4,
          "frontImage": "4.webp",
          "backImage": "4b.webp",
          "brand": "Levi's",
          "name": "Tee Unisex",
          "price": 14.99,
          "isInFavorites": false,
          "badges": [
            {
              "type": "tag",
              "value": "Sostenibilità",
            },
            {
              "type": "discount",
              "value": "-50%",
            },
          ],
        },
        {
          "id": 5,
          "frontImage": "5.webp",
          "backImage": "5b.webp",
          "brand": "Maya Deluxe",
          "name": "Stripe Bodice",
          "price": 99.99,
          "isInFavorites": true,
          "badges": [
            {
              "type": "tag",
              "value": "Sostenibilità",
            },
            {
              "type": "discount",
              "value": "-50%",
            },
          ],
        },
        {
          "id": 6,
          "frontImage": "6.webp",
          "backImage": "6b.webp",
          "brand": "Esprit",
          "name": "Maglione - Black",
          "price": 29.99,
          "isInFavorites": true,
          "badges": [
            {
              "type": "tag",
              "value": "Sostenibilità",
            },
          ],
        },
      ],
    };
  },
};
</script>

<template>
  <main class="container">
    <div class="row margin-bottom100 space-between">
      <div v-for="(prodotto, i) in products" class="card col-4 relative">
        <div class="relative">
          <div class="block">
            <img class="img-smile" src="../assets/Phase_1.png" alt="" />
            <img class="img-cursed" src="../assets/Phase_2.jpg" alt="" />
          </div>
          <div class="absolute badge preferiti">&hearts;</div>
          <div class="lable-position absolute">
            <div class="badge inblock sconto">-50%</div>
            <div class="badge inblock sost">Sostenibilità</div>
          </div>
        </div>
        <span class="block Marca">{{ prodotto.brand }}</span>
        <span class="block Nome-item">{{ prodotto.name }}</span>
        <span class="block prezzo"
          >14,99&euro; <s class="presconto">{{ prodotto.price }}</s>
        </span>
      </div>
    </div>
  </main>
</template>
