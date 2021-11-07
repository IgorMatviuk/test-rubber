<template>
  <div>
    <div class="container">
      <div class="main-slider">
        <VueSlickCarousel :arrows="false" :dots="true">
          <div class="main-slider__block">
            <div class="main-slider__block__img">
              <img src="../assets/img/slider/slide1.png" alt="logo">
            </div>
            <div class="main-slider__block__content">
                <p>Крем-брюле и пломбир с малиновым джемом</p>
                <button>Давайте оба!</button>
            </div>
          </div>
          <div class="main-slider__block">
            <div class="main-slider__block__img">
              <img src="../assets/img/slider/slide2.png" alt="logo">
            </div>
            <div class="main-slider__block__content">
                <p>Крем-брюле и пломбир с малиновым джемом</p>
                <button>Давайте оба!</button>
            </div>
          </div>
          <div class="main-slider__block">
            <div class="main-slider__block__img">
              <img src="../assets/img/slider/slide3.png" alt="logo">
            </div>
            <div class="main-slider__block__content">
                <p>Крем-брюле и пломбир с малиновым джемом</p>
                <button>Давайте оба!</button>
            </div>
          </div>
        </VueSlickCarousel>
      </div>
      <div class="action-blocks">
        <div class="action-blocks__block">
          <div class="action-blocks__block__container">
            <div class="action-blocks__block__container__title">
              <p>Малинка даром!</p>
            </div>
            <div class="action-blocks__block__container__text">
              <p>При покупке 2 кг любого фруктового мороженого, добавим в ваш заказ банку малинового варенья бесплатно.</p>
            </div>
            <div class="action-blocks__block__container__button">
              <button>Хочу варенье!</button>
            </div>
          </div>
        </div>
        <div class="action-blocks__block-cho">
          <div class="action-blocks__block__container">
            <div class="action-blocks__block__container__title">
              <p>Шоколадки даром!</p>
            </div>
            <div class="action-blocks__block__container__text">
              <p>При покупке 2 кг пломбира, добавим в ваш заказ упаковку вкуснейшей шоколадной присыпки совершенно бесплатно.</p>
            </div>
            <div class="action-blocks__block__container__button">
              <button>Хочу шоколадки!</button>
            </div>
          </div>
        </div>
      </div>
      <div class="products-list">
        <div class="product-card">
          <div class="product-card__img">
            <img src="../assets/img/main/product1.png" alt="logo">
          </div>
          <div class="product-card__hit">
            <img src="../assets/img/main/hit.svg" alt="logo">
          </div>
          <div class="product-card__price">
            <p>310 ₽<strong>/кг</strong></p>
          </div>
          <div class="product-card__title">
            <p>Сливочное с апельсиновым джемом и цитрусовой стружкой</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-card__img">
            <img src="../assets/img/main/product2.png" alt="logo">
          </div>
          <div class="product-card__hit">
            <img src="../assets/img/main/hit.svg" alt="logo">
          </div>
          <div class="product-card__price">
            <p>380 ₽<strong>/кг</strong></p>
          </div>
          <div class="product-card__title">
            <p>Сливочно-кофейное с кусочками шоколада</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-card__img">
            <img src="../assets/img/main/product3.png" alt="logo">
          </div>
          <div class="product-card__hit">
            <img src="../assets/img/main/hit.svg" alt="logo">
          </div>
          <div class="product-card__price">
            <p>355 ₽<strong>/кг</strong></p>
          </div>
          <div class="product-card__title">
            <p>Сливочно-клубничное с присыпкой из белого шоколада</p>
          </div>
        </div>
        <div class="product-card">
          <div class="product-card__img">
            <img src="../assets/img/main/product4.png" alt="logo">
          </div>
          <div class="product-card__hit">
            <img src="../assets/img/main/hit.svg" alt="logo">
          </div>
          <div class="product-card__price">
            <p>415 ₽<strong>/кг</strong></p>
          </div>
          <div class="product-card__title">
            <p>Сливочное крем-брюле с карамельной подливкой </p>
          </div>
        </div>
      </div>
      <div class="main-description">
        <div class="main-description__container">
          <div class="main-description__title">
            <p>Магазин Глэйси – это онлайн и офлайн-магазин по продаже мороженого собственного производства на развес</p>
          </div>
          <div class="main-description__container__blocks">
            <div class="main-description__container__blocks__block">
              <img src="../assets/img/main/d1.svg">
              <p>Все наше мороженое изготавливается на собственном производстве, с использованием современного оборудования и проверенных временем технологий.</p>
            </div>
            <div class="main-description__container__blocks__block">
              <img src="../assets/img/main/d2.svg">
              <p>Закупка ингредиентов производится только у проверенных фермерских хозяйств и компаний, с которыми нас связывает долговременное сотрудничество.</p>
            </div>
            <div class="main-description__container__blocks__block">
              <img src="../assets/img/main/d3.svg">
              <p>Для приготовления мороженого используются настоящие сливки и молоко высочайшего качества. Все дополнительные ингредиенты и добавки произведены из натурального, экологически чистого сырья.</p>
            </div>
            <div class="main-description__container__blocks__block">
              <img src="../assets/img/main/d4.svg">
              <p>Доставка нашего мороженого до заказчиков осуществляется в специальном термопаке, который не дает мороженому растаять в пути и позволяет сохранить превосходный вкус.</p>
            </div>
          </div>
        </div>
      </div>
      <div class="main-forum-and-subscription">
        <div class="main-forum-and-subscription__forum">
          <div class="main-forum-and-subscription__forum__container">
            <div class="main-forum-and-subscription__forum__container__sub-title">
              <p>Новое в нашем блоге</p>
            </div>
            <div class="main-forum-and-subscription__forum__container__title">
              <p>10 способов сервировки фруктовых щербетов к столу</p>
            </div>
          </div>
        </div>
        <div class="main-forum-and-subscription_subs">
          <div class="main-forum-and-subscription_subs__block">
            <div class="main-forum-and-subscription_subs__block__title">
              <p>Подпишитесь на нашу сладкую рассылку и будьте всегда в курсе всего самого вкусного, что у нас происходит. Обещаем не спамить и не слать всякой ненужной ерунды. Честно =)</p>
            </div>
            <div class="main-forum-and-subscription_subs__block__form">
              <div class="main-forum-and-subscription_subs__block__form__input">
                <input type="text">
              </div>
              <div class="main-forum-and-subscription_subs__block__form__button">
                <button>Отправить</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="main-map">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1998.6160238160664!2d30.324506913144162!3d59.93851344856849!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4696310fca145cc1%3A0x42b32648d8238007!2z0JHQvtC70YzRiNCw0Y8g0JrQvtC90Y7RiNC10L3QvdCw0Y8g0YPQuy4sIDE5LzgsINCh0LDQvdC60YIt0J_QtdGC0LXRgNCx0YPRgNCzLCDQoNC-0YHRgdC40Y8sIDE5MTE4Ng!5e0!3m2!1sru!2sua!4v1636318314518!5m2!1sru!2sua" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>
  </div>  
</template>

<script>

  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'

export default {
      components: { VueSlickCarousel },
}
</script>

<style lang="scss">
</style>