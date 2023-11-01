<script>
  import News from "../layout/News.svelte";
  import Contact from "../layout/Contact.svelte";
  import Partners from "../layout/pages/Partners.svelte";

  import Carousel01 from "$lib/images/home/carousel-01.jpg";
  import Carousel02 from "$lib/images/home/carousel-02.jpg";
  import Carousel03 from "$lib/images/home/carousel-03.jpg";
  import Carousel04 from "$lib/images/home/carousel-04.jpg";

  import Home from "$lib/images/home/home-bg.jpg";
  import Directions from "$lib/images/home/directions.jpg";
</script>

<section class="carousel">
  <div class="carousel__body">
    <div class="carousel__content">
      <div class="carousel__content-wrapper">
        <div class="carousel__item-wrapper">
          <div class="carousel__item">
            <div class="carousel__item-img">
              <img src={Carousel01} alt="Carousel" />
            </div>
          </div>
          <div class="carousel__item">
            <div class="carousel__item-img">
              <img src={Carousel02} alt="Carousel" />
            </div>
          </div>
          <div class="carousel__item">
            <div class="carousel__item-title">Ваша реклама</div>
          </div>
          <div class="carousel__item">
            <div class="carousel__item-img">
              <img src={Carousel03} alt="Carousel" />
            </div>
          </div>
          <div class="carousel__item">
            <div class="carousel__item-img">
              <img src={Carousel04} alt="Carousel" />
            </div>
          </div>
        </div>
        <div class="carousel__item-wrapper">
          <div class="carousel__item">
            <div class="carousel__item-img">
              <img src={Carousel01} alt="Carousel" />
            </div>
          </div>
          <div class="carousel__item">
            <div class="carousel__item-img">
              <img src={Carousel02} alt="Carousel" />
            </div>
          </div>
          <div class="carousel__item">
            <div class="carousel__item-title">Ваша реклама</div>
          </div>
          <div class="carousel__item">
            <div class="carousel__item-img">
              <img src={Carousel03} alt="Carousel" />
            </div>
          </div>
          <div class="carousel__item">
            <div class="carousel__item-img">
              <img src={Carousel04} alt="Carousel" />
            </div>
          </div>
        </div>
        <div class="carousel__item-wrapper">
          <div class="carousel__item">
            <div class="carousel__item-img">
              <img src={Carousel01} alt="Carousel" />
            </div>
          </div>
          <div class="carousel__item">
            <div class="carousel__item-img">
              <img src={Carousel02} alt="Carousel" />
            </div>
          </div>
          <div class="carousel__item">
            <div class="carousel__item-title">Ваша реклама</div>
          </div>
          <div class="carousel__item">
            <div class="carousel__item-img">
              <img src={Carousel03} alt="Carousel" />
            </div>
          </div>
          <div class="carousel__item">
            <div class="carousel__item-img">
              <img src={Carousel04} alt="Carousel" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="home" id="home">
  <div class="home__container _container">
    <div class="home__body">
      <div class="home__content">
        <div class="home__block-title">
          <div class="home__title">Покровский колледж</div>
          <div class="home__text">
            Государственное бюджетное профессиональное образовательное
            учреждение Республика Саха (Якутия) "Покровский колледж"
          </div>
        </div>
        <div class="home__block">
          <div class="home__btn-wrapper">
            <div class="home__btn">
              <a href="#directions" class="home__arrow _icon-arrow" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="home__img">
    <img src={Home} alt="Home" />
  </div>
</section>

<section class="directions" id="directions">
  <div class="directions__container _container">
    <div class="directions__body">
      <div class="directions__sub sub">Направления</div>
      <div class="directions__content">
        <div class="directions__block">
          <div class="directions__title">Специальности</div>
          <div class="directions__text">
            Осуществляем подготовку специалистов в разных профессиональных
            областях: Информационные системы, программирование, разработка игр,
            разработка виртуальной и дополненной реальности, туризма,
            кибербезопасности...
          </div>
          <div class="directions__img">
            <img src={Directions} alt="Directions" />
          </div>
        </div>
        <div class="directions__block-slide">
          <div class="directions__item-wrapper">
            <div class="directions__item active" id="item-01">
              <p>Программист<i class="directions__item-arrow _icon-arrow" /></p>
            </div>
            <div class="directions__item-block active" id="item-block-01">
              <div class="directions__item-title">
                Информационные системы и программирование — квалификация
                «Программист/ Разработчик веб приложений» - 3 года 10мес. <br
                /><br />
                Выпускники данной специальности владеют навыками разработки, отладки
                и тестирования программных продуктов и модулей для настольных, мобильных
                и платформ. <br />
                <span>Бесплатное обучение</span>
              </div>
              <div class="directions__item-btn">
                Подробнее <div class="directions__item-btn-arrow _icon-arrow" />
              </div>
            </div>
          </div>
          <div class="directions__item-wrapper">
            <div class="directions__item" id="item-02">
              <p>
                Техник по ИЗ<i class="directions__item-arrow _icon-arrow" />
              </p>
            </div>
            <div class="directions__item-block" id="item-block-02">
              <div class="directions__item-title">
                Информационные системы и программирование — квалификация
                «Программист/ Разработчик веб приложений» - 3 года 10мес. <br
                /><br />
                Выпускники данной специальности владеют навыками разработки, отладки
                и тестирования программных продуктов и модулей для настольных, мобильных
                и платформ. <br />
                <span>Бесплатное обучение</span>
              </div>
              <div class="directions__item-btn">
                Подробнее <div class="directions__item-btn-arrow _icon-arrow" />
              </div>
            </div>
          </div>
          <div class="directions__item-wrapper">
            <div class="directions__item" id="item-03">
              <p>
                Специалист по туризму<i
                  class="directions__item-arrow _icon-arrow"
                />
              </p>
            </div>
            <div class="directions__item-block" id="item-block-03">
              <div class="directions__item-title">
                Информационные системы и программирование — квалификация
                «Программист/ Разработчик веб приложений» - 3 года 10мес. <br
                /><br />
                Выпускники данной специальности владеют навыками разработки, отладки
                и тестирования программных продуктов и модулей для настольных, мобильных
                и платформ. <br />
                <span>Бесплатное обучение</span>
              </div>
              <div class="directions__item-btn">
                Подробнее <div class="directions__item-btn-arrow _icon-arrow" />
              </div>
            </div>
          </div>
          <div class="directions__item-wrapper">
            <div class="directions__item" id="item-04">
              <p>
                Специалист по КС<i class="directions__item-arrow _icon-arrow" />
              </p>
            </div>
            <div class="directions__item-block" id="item-block-04">
              <div class="directions__item-title">
                Информационные системы и программирование — квалификация
                «Программист/ Разработчик веб приложений» - 3 года 10мес. <br
                /><br />
                Выпускники данной специальности владеют навыками разработки, отладки
                и тестирования программных продуктов и модулей для настольных, мобильных
                и платформ. <br />
                <span>Бесплатное обучение</span>
              </div>
              <div class="directions__item-btn">
                Подробнее <div class="directions__item-btn-arrow _icon-arrow" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="about">
  <div class="about__container _container">
    <div class="about__body">
      <div class="about__sub">О нас</div>
      <div class="about__title">Наш колледж</div>
      <div class="about__text">
        Учебное заведение, призванное обеспечить студентам всестороннее и
        разностороннее образование. Наши опытные преподаватели и сотрудники
        стремятся создать динамичную и благоприятную учебную среду,
        способствующую академическому совершенству и личностному росту.
      </div>
    </div>
    <div class="about__decore">Покровский колледж Покровский колледж</div>
  </div>
</section>

<News />

<section class="partners">
  <div class="partners__container _container">
    <div class="partners__body">
      <div class="partners__title">Партнеры</div>
      <Partners />
    </div>
  </div>
</section>

<Contact />
