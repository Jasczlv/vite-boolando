<script>
export default {};
</script>

<template>
  <div id="app">
    <header class="header-container margin-bottom100">
      <div class="container">
        <div class="row">
          <div class="col-4">A</div>
          <div class="col-4">
            <ul>
              <li class="inline">a</li>
              <li class="inline">a</li>
              <li class="inline">a</li>
            </ul>
          </div>
          <div class="col-4">B</div>
        </div>
      </div>
    </header>

    <main class="container">
      <div class="row margin-bottom100 space-between">
        <div class="card col-4 relative">
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
          <span class="block Marca">Levi's</span>
          <span class="block Nome-item">INCREDIBILES</span>
          <span class="block prezzo"
            >14,99&euro; <s class="presconto">29,99&euro</s>
          </span>
        </div>
        <div class="card col-4 relative">
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
          <span class="block Marca">Levi's</span>
          <span class="block Nome-item">INCREDIBILES</span>
          <span class="block prezzo"
            >14,99&euro; <s class="presconto">29,99&euro</s>
          </span>
        </div>
        <div class="card col-4 relative">
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
          <span class="block Marca">Levi's</span>
          <span class="block Nome-item">INCREDIBILES</span>
          <span class="block prezzo"
            >14,99&euro; <s class="presconto">29,99&euro</s>
          </span>
        </div>
        <div class="card col-4 relative">
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
          <span class="block Marca">Levi's</span>
          <span class="block Nome-item">INCREDIBILES</span>
          <span class="block prezzo"
            >14,99&euro; <s class="presconto">29,99&euro</s>
          </span>
        </div>
        <div class="card col-4 relative">
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
          <span class="block Marca">Levi's</span>
          <span class="block Nome-item">INCREDIBILES</span>
          <span class="block prezzo"
            >14,99&euro; <s class="presconto">29,99&euro</s>
          </span>
        </div>
        <div class="card col-4 relative">
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
          <span class="block Marca">Levi's</span>
          <span class="block Nome-item">INCREDIBILES</span>
          <span class="block prezzo"
            >14,99&euro; <s class="presconto">29,99&euro</s>
          </span>
        </div>
      </div>
    </main>

    <footer class="footer-container">
      <div class="container">
        <div class="row">
          <div>
            Boolando s.r.l
            <ul>
              <li class="inline"><a href="">Info uno</a></li>
              <li class="inline"><a href="">Info due</a></li>
              <li class="inline"><a href="">Info tre</a></li>
            </ul>
          </div>

          <div>
            Trovaci anche su
            <ul>
              <li class="inline"><a href="">twitter</a></li>
              <li class="inline"><a href="">whatsapp</a></li>
              <li class="inline"><a href="">instagram</a></li>
              <li class="inline"><a href="">facebook</a></li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<style>
/* RESET */

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

img {
  max-width: 100%;
}

a {
  text-decoration: none;
  color: currentColor;
}

menu,
ul,
ol {
  list-style: none;
}

/* utility */

.block {
  display: block;
}

.inblock {
  display: inline-block;
}

.inline {
  display: inline;
}

.relative {
  position: relative;
}

.column {
  flex-direction: column;
}

.absolute {
  position: absolute;
}

.col-4 {
  max-width: calc(4 * 100% / 12);
}

.row {
  flex-direction: row;
  display: flex;
  flex-wrap: wrap;
}

.space-between {
  justify-content: space-between;
}

.container {
  max-width: 60%;
  margin: 0 auto;
}

.margin-bottom100 {
  margin-bottom: 100px;
}

/* header */

.header-container {
  background-color: orange;
  max-height: 20px;
  padding: 15px;
}

.header-container .container {
  max-height: 100%;
}

.footer-container {
  max-width: 100%;
  background-color: black;
  color: white;
  height: 100px;
}

.footer-container .row {
  height: 100px;
  justify-content: center;
  justify-content: space-between;
  align-items: center;
}

header .row div {
  text-align: center;
  line-height: 1px;
}

header .row {
  justify-content: space-between;
}

.presconto {
  color: black;
}

.sost {
  font-size: 20px;
  background-color: Green;
  color: white;
}

.sconto {
  font-size: 20px;
  background-color: red;
  color: white;
}

.preferiti {
  font-size: 30px;
  top: 15px;
  right: 0px;
  color: red;
  background-color: white;
  width: 40px;
  text-align: center;
}

.img-smile {
  height: 400px;
  width: 300px;
  margin-bottom: 10px;
}

.img-cursed {
  position: absolute;
  height: 400px;
  width: 300px;
  margin-bottom: 10px;
  top: 0;
  left: 0;
  z-index: -1;
}

.prezzo {
  font-size: 14px;
  color: red;
}

.Marca {
  font-size: 12px;
}

.Nome-item {
  font-size: 20px;
}

.lable-position {
  bottom: 50px;
  left: 10px;
}

.card {
  padding: 5px;
}

.card img.img-smile:hover {
  opacity: 0;
  transition: 1500ms;
}

/* utility */
</style>
