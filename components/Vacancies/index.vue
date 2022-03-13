<template>
  <div class="container">
    <div class="row">
      <h2>Vacancies</h2>
    </div>
    <div id="accordionExample" class="accordion">
      <div class="accordion-item">
        <h2 id="headingOne" class="accordion-header">
          <button
            class="accordion-button"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#collapseOne"
            aria-expanded="true"
            aria-controls="collapseOne"
          >
            WordPress developer
          </button>
        </h2>
        <div
          id="collapseOne"
          class="accordion-collapse collapse show"
          aria-labelledby="headingOne"
          data-bs-parent="#accordionExample"
        >
          <div class="accordion-body">
            <div class="accordion-body__title">Требования:</div>
            <div class="accordion-body__text">
              <ul>
                <li>Опыт разработки PHP 2+ лет;</li>
                <li>
                  Опыт работы с WordPress более 1 года (создание
                  пользовательских тем, разработка пользовательских плагинов);
                </li>
                <li>Хорошее знание HTML, CSS, JavaScript/JQuery, PHP;</li>
                <li>Знание SQL и опыт MySQL.</li>
              </ul>
            </div>
            <div class="accordion-body__title">Условия работы:</div>
            <div class="accordion-body__text">
              <ul>
                <li>Офис в центре города, 2 минуты от м. Ботанический сад;</li>
                <li>
                  Работа в комфортном, просторном лимонном офисе с панорамным
                  видом на город;
                </li>
                <li>На время карантина возможен режим удаленной работы;</li>
                <li>
                  Рабочий график 5 дней (пн-пт) с 9:00 до 18:00 или с 10:00 до
                  19:00 (1 час обед);
                </li>
                <li>Чай, кофе и вкусняшки;</li>
                <li>Молодая адекватная команда;</li>
                <li>Оплачиваемый отпуск;</li>
                <li>Официальное трудоустройство;</li>
                <li>PS4, настольный теннис, футбольная команда;</li>
                <li>Еженедельные тусовки и корпоративы.</li>
              </ul>
              <p>
                Если ты всегда находишь яркие решения для каждого проекта — ждем
                твое резюме!
              </p>
              <div>
                <p>
                  <strong> Email: </strong>
                  <a href="mailto:info@zubi-solutions.de"
                    >info@zubi-solutions.de</a
                  >
                  или в <strong> Telegram: </strong
                  ><a href="https://t.me/zubi-solutions.de"
                    >https://t.me/zubi-solutions.de</a
                  >
                </p>
              </div>
            </div>
            <button class="btn btn-primary accordion-body__button">
              Send resume
            </button>
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 id="headingTwo" class="accordion-header">
          <button
            class="accordion-button collapsed"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#collapseTwo"
            aria-expanded="false"
            aria-controls="collapseTwo"
          >
            QA engineer
          </button>
        </h2>
        <div
          id="collapseTwo"
          class="accordion-collapse collapse"
          aria-labelledby="headingTwo"
          data-bs-parent="#accordionExample"
        >
          <div class="accordion-body">
            <div class="accordion-body__title">Требования:</div>
            <div class="accordion-body__text">
              <ul>
                <li>Опыт разработки PHP 2+ лет;</li>
                <li>
                  Опыт работы с WordPress более 1 года (создание
                  пользовательских тем, разработка пользовательских плагинов);
                </li>
                <li>Хорошее знание HTML, CSS, JavaScript/JQuery, PHP;</li>
                <li>Знание SQL и опыт MySQL.</li>
              </ul>
            </div>
            <div class="accordion-body__title">Условия работы:</div>
            <div class="accordion-body__text">
              <ul>
                <li>Офис в центре города, 2 минуты от м. Ботанический сад;</li>
                <li>
                  Работа в комфортном, просторном лимонном офисе с панорамным
                  видом на город;
                </li>
                <li>На время карантина возможен режим удаленной работы;</li>
                <li>
                  Рабочий график 5 дней (пн-пт) с 9:00 до 18:00 или с 10:00 до
                  19:00 (1 час обед);
                </li>
                <li>Чай, кофе и вкусняшки;</li>
                <li>Молодая адекватная команда;</li>
                <li>Оплачиваемый отпуск;</li>
                <li>Официальное трудоустройство;</li>
                <li>PS4, настольный теннис, футбольная команда;</li>
                <li>Еженедельные тусовки и корпоративы.</li>
              </ul>
              <p>
                Если ты всегда находишь яркие решения для каждого проекта — ждем
                твое резюме!
              </p>
              <div>
                <p>
                  <strong> Email: </strong>
                  <a href="mailto:info@zubi-solutions.de"
                    >info@zubi-solutions.de</a
                  >
                  или в <strong> Telegram: </strong
                  ><a href="https://t.me/zubi-solutions.de"
                    >https://t.me/zubi-solutions.de</a
                  >
                </p>
              </div>
            </div>
            <button class="btn btn-primary accordion-body__button">
              Send resume
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'VacanciesBlock',
  data() {
    return {
      header: 'Welcome to Zubi-Solutions !',
      description:
        'Looking for Right job that you deserve? We are here to help you!',
      buttonLabel: 'Send a resume',
    }
  },
})
</script>

<style scoped>
</style>
