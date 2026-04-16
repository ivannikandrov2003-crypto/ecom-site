<template>
  <div v-if="isPrivacyPage" class="page privacy-page">
    <header class="site-header" aria-label="Шапка">
      <div class="container header-row">
        <a class="logo" href="/" aria-label="На главную">
          <span class="logo-dot"></span>
          Артем Никандров
        </a>
        <nav class="nav-links" aria-label="Навигация по документу">
          <a href="/">На главную</a>
        </nav>
      </div>
    </header>

    <main class="privacy-main">
      <section class="section privacy-section" aria-label="Политика обработки персональных данных">
        <div class="container privacy-container">
          <p class="eyebrow">Юридическая информация</p>
          <h1 class="privacy-title">Политика обработки персональных данных</h1>
          <p class="privacy-updated">Дата публикации: 15 апреля 2026 года</p>

          <div class="privacy-content">
            <section>
              <h2>1. Общие положения</h2>
              <p>
                Настоящая Политика определяет порядок обработки персональных данных
                пользователей сайта Артема Никандрова, размещенного в сети Интернет.
              </p>
              <p>
                Оператор персональных данных: индивидуальный предприниматель Никандров
                Артем Олегович, ИНН 352535819890, email:
                <a href="mailto:artnikandrov@gmail.com">artnikandrov@gmail.com</a>.
              </p>
              <p>
                Политика подготовлена с учетом Федерального закона от 27.07.2006
                N 152-ФЗ "О персональных данных" и применяется ко всем данным, которые
                Оператор может получить при использовании сайта и при обращении через
                указанные на сайте контакты.
              </p>
            </section>

            <section>
              <h2>2. Какие данные обрабатываются</h2>
              <p>Оператор может обрабатывать следующие категории данных:</p>
              <ul>
                <li>имя, фамилию, никнейм или иное имя, которое пользователь сообщает при обращении;</li>
                <li>контактные данные: email, аккаунт в мессенджере, телефон, если пользователь сообщает его сам;</li>
                <li>содержание сообщений, запросов и приложенных пользователем материалов;</li>
                <li>технические данные: IP-адрес, сведения о браузере, устройстве, операционной системе, дате и времени посещения;</li>
                <li>данные cookies и похожих технологий, если пользователь согласился на их использование.</li>
              </ul>
            </section>

            <section>
              <h2>3. Цели обработки</h2>
              <p>Персональные данные обрабатываются для следующих целей:</p>
              <ul>
                <li>ответ на обращение пользователя и запись на консультацию;</li>
                <li>подготовка, согласование и оказание консультационных услуг;</li>
                <li>ведение деловой переписки и документооборота;</li>
                <li>обеспечение корректной и безопасной работы сайта;</li>
                <li>анализ посещаемости сайта и улучшение материалов сайта при подключении Яндекс Метрики;</li>
                <li>исполнение обязанностей, предусмотренных законодательством Российской Федерации.</li>
              </ul>
            </section>

            <section>
              <h2>4. Правовые основания обработки</h2>
              <p>
                Обработка персональных данных осуществляется на основании согласия
                пользователя, действий пользователя по направлению обращения Оператору,
                необходимости заключения или исполнения договора, а также требований
                законодательства Российской Федерации.
              </p>
            </section>

            <section>
              <h2>5. Cookies и аналитика</h2>
              <p>
                Сайт использует необходимые технические данные для своей работы. В
                будущем на сайте может быть подключена Яндекс Метрика для анализа
                посещаемости, источников переходов и поведения пользователей на сайте.
              </p>
              <p>
                Аналитические cookies используются только после согласия пользователя.
                Пользователь может ограничить или удалить cookies в настройках браузера.
                При отказе от аналитических cookies сайт продолжит работать, но Оператор
                не будет получать статистику посещений через такие инструменты.
              </p>
            </section>

            <section>
              <h2>6. Передача данных третьим лицам</h2>
              <p>
                Оператор может передавать данные сервисам, которые необходимы для работы
                сайта, связи с пользователем, аналитики и исполнения договоренностей:
                хостинг-провайдеру, почтовым сервисам, мессенджерам, сервисам аналитики
                и иным подрядчикам, если такая передача необходима для указанных в
                Политике целей.
              </p>
              <p>
                Оператор не продает персональные данные пользователей и не передает их
                третьим лицам для самостоятельного маркетинга без отдельного основания.
              </p>
            </section>

            <section>
              <h2>7. Сроки хранения</h2>
              <p>
                Персональные данные хранятся не дольше, чем требуется для целей обработки,
                ответа на обращение, оказания услуг, исполнения договора и соблюдения
                требований закона. Данные переписки могут храниться в течение срока,
                необходимого для подтверждения договоренностей и защиты законных интересов
                Оператора.
              </p>
            </section>

            <section>
              <h2>8. Права пользователя</h2>
              <p>Пользователь вправе:</p>
              <ul>
                <li>получать информацию об обработке своих персональных данных;</li>
                <li>требовать уточнения, блокирования или удаления персональных данных;</li>
                <li>отозвать согласие на обработку персональных данных;</li>
                <li>обжаловать действия или бездействие Оператора в уполномоченный орган или суд.</li>
              </ul>
              <p>
                Для реализации прав пользователь может написать на
                <a href="mailto:artnikandrov@gmail.com">artnikandrov@gmail.com</a>.
              </p>
            </section>

            <section>
              <h2>9. Защита данных</h2>
              <p>
                Оператор принимает необходимые правовые, организационные и технические
                меры для защиты персональных данных от неправомерного доступа,
                уничтожения, изменения, блокирования, копирования, распространения и иных
                неправомерных действий.
              </p>
            </section>

            <section>
              <h2>10. Изменение Политики</h2>
              <p>
                Оператор может обновлять Политику. Новая редакция действует с момента
                публикации на сайте, если иное не указано в тексте новой редакции.
              </p>
            </section>
          </div>
        </div>
      </section>
    </main>

    <footer aria-label="Футер">
      <div class="container footer-row footer-row--legal">
        <div class="footer-legal">
          <div>© {{ year }} ИП Никандров Артем Олегович</div>
          <div>ИНН 352535819890</div>
          <a class="footer-email" href="mailto:artnikandrov@gmail.com">artnikandrov@gmail.com</a>
        </div>
        <div class="footer-links">
          <a href="/">На главную</a>
        </div>
      </div>
    </footer>
  </div>

  <div v-else class="page">
    <div class="scroll-progress" aria-hidden="true">
      <div class="scroll-progress-bar" :style="{ width: scrollProgress + '%' }"></div>
    </div>
    <!-- Ticker -->
    <div class="ticker" aria-label="Новостная лента">
      <div class="ticker-track">
        <div class="ticker-group" aria-hidden="false">
          <span>e-commerce • retail media • стратегия</span>
          <span>e-commerce • retail media • стратегия</span>
          <span>e-commerce • retail media • стратегия</span>
          <span>e-commerce • retail media • стратегия</span>
          <span>e-commerce • retail media • стратегия</span>
          <span>e-commerce • retail media • стратегия</span>
          <span>e-commerce • retail media • стратегия</span>
        </div>
        <div class="ticker-group" aria-hidden="true">
          <span>e-commerce • retail media • стратегия</span>
          <span>e-commerce • retail media • стратегия</span>
          <span>e-commerce • retail media • стратегия</span>
          <span>e-commerce • retail media • стратегия</span>
          <span>e-commerce • retail media • стратегия</span>
          <span>e-commerce • retail media • стратегия</span>
          <span>e-commerce • retail media • стратегия</span>
        </div>
      </div>
    </div>

    <!-- Header -->
    <header class="site-header" aria-label="Шапка">
      <div class="container header-row">
        <div class="logo" aria-label="Логотип">
          <span class="logo-dot"></span>
          Артем Никандров
        </div>
        <nav class="nav-links" aria-label="Главная навигация">
          <a href="#about" @click.prevent="scrollTo('about')">О себе</a>
          <a href="#services" @click.prevent="scrollTo('services')">Услуги</a>
          <a href="#experience" @click.prevent="scrollTo('experience')">Опыт</a>
          <a href="#contacts" @click.prevent="scrollTo('contacts')">Контакты</a>
        </nav>
        <a class="cta small" href="#contacts" @click.prevent="scrollTo('contacts')">
          Записаться
        </a>
      </div>
    </header>

    <!-- Hero -->
    <section class="hero" id="hero" aria-label="Hero">
      <div class="hero-decor" aria-hidden="true">
        <span class="orb orb-1"></span>
        <span class="orb orb-2"></span>
        <span class="orb orb-3"></span>
      </div>
      <div class="container hero-grid">
        <div class="hero-main reveal">
          <div class="eyebrow">e-commerce • retail media • стратегия</div>
          <h1 class="hero-title">
            <span class="hero-title-name">Никандров Артем</span>
            <span class="hero-title-sub">e-commerce маркетолог и стратег</span>
          </h1>
          <p class="hero-subtitle">
            Помогаю брендам выстраивать эффективный маркетинг в e-commerce и
            масштабировать продажи на маркетплейсах и в онлайн-ритейле
          </p>
          <div class="hero-specialties">
            <p class="hero-specialties-title">Специализируюсь на:</p>
            <ul class="hero-specialties-list">
              <li>росте онлайн-продаж в e-commerce</li>
              <li>разработке рекламных стратегий для маркетплейсов</li>
              <li>работе с retail media и performance-инструментами</li>
              <li>интеграции e-commerce в общую маркетинговую стратегию бренда</li>
            </ul>
            <p class="hero-specialties-note quote-card">
              Мои консультации - это независимая экспертная оценка того, как ваш
              бизнес ведет маркетинг в e-commerce: от стратегии до конкретных
              рекламных кампаний.
            </p>
          </div>
          <div class="hero-actions">
            <a class="cta" href="#contacts" @click.prevent="scrollTo('contacts')">
              Записаться на консультацию
            </a>
          </div>
        </div>
        <div class="hero-side">
          <figure class="photo-card reveal" aria-label="Фото автора">
            <div class="photo-frame">
              <img class="photo-img" :src="authorPhoto" alt="Фото автора" />
            </div>
          </figure>
        </div>
      </div>
    </section>

    <!-- About -->
    <section class="section" id="about" aria-label="О себе">
      <div class="container">
        <div class="about-grid">
          <div class="about-copy">
            <h2 class="section-title about-section-title">О себе</h2>
            <ul class="about-list" aria-label="Ключевые факты">
              <li class="reveal">опыт в e-commerce с 2020 года: PepsiCo, RoRe (ex-Publicis Group), АДВ</li>
              <li class="reveal">
                автор Telegram-канала
                <a href="https://t.me/ecom_ads" target="_blank" rel="noreferrer">БАЗАР ТУТ РАЗВЕЛИ</a>
              </li>
              <li class="reveal">
                преподаватель курса
                <a href="https://ecomedu.rore.group/" target="_blank" rel="noreferrer">Ecom-маркетолог</a>
              </li>
              <li class="reveal">член комитета АРИР по E-Retail Media</li>
              <li class="reveal">выпускник НИУ ВШЭ, Факультет мировой экономики и мировой политики</li>
              <li class="reveal">сертифицированный практик дизайн-мышления d.standards</li>
            </ul>
          </div>
          <div class="about-when reveal" id="when" aria-label="Я нужен, когда">
            <h2 class="section-title about-section-title about-when-heading">Я нужен, когда</h2>
            <ul class="about-when-list">
              <li>бренд выходит на маркетплейсы (Ozon, Wildberries, Яндекс Маркет) и нужна стратегия</li>
              <li>рекламный бюджет растёт, но e-commerce продажи не масштабируются</li>
              <li>нет понимания, как эффективно использовать retail media</li>
              <li>команда или агентство не видят точек роста в рекламе</li>
              <li>нужно встроить e-commerce в общий digital и маркетинговый микс</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="approach" aria-label="Подход к работе">
      <div class="container">
        <div class="approach-card reveal">
          <div class="approach-copy">
            <div class="section-head">
              <h2 class="section-title">Подход к работе</h2>
            </div>
            <p class="approach-lead">
              Работаю на стыке стратегии, аналитики и практического опыта в e-commerce
            </p>
            <p class="approach-text">
              Использую методологию дизайн-мышления, ориентированную на поведение и
              потребности конечного пользователя
            </p>
            <p class="approach-text">
              Рассматриваю маркетинг в e-commerce не только как performance (CPM,
              ДРР), но и как систему точек контакта бренда с аудиторией на всех
              этапах CJM
            </p>
          </div>
          <div class="approach-points">
            <div class="approach-points-title">Опыт работы на стороне бренда и агентства позволяет:</div>
            <ul class="approach-list">
              <li>быстро находить слабые места в стратегии</li>
              <li>давать применимые рекомендации</li>
              <li>учитывать реальные ограничения бизнеса</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Services -->
    <section class="section" id="services" aria-label="Мои услуги">
      <div class="container">
        <div class="section-head">
          <h2 class="section-title">Мои услуги</h2>
        </div>
        <div class="services-rail">
          <p
            v-show="!servicesCanScrollPrev && servicesCanScrollNext"
            class="services-mobile-hint"
          >
            Свайпните, чтобы посмотреть все услуги <span aria-hidden="true">→</span>
          </p>
          <div
            class="services-slider"
            :class="{ 'services-slider--has-next': servicesCanScrollNext }"
            aria-live="polite"
          >
            <button
              class="services-arrow services-arrow--prev"
              type="button"
              @click="showPrevService"
              :disabled="!servicesCanScrollPrev"
              aria-label="Предыдущие услуги"
            >
              <span aria-hidden="true">‹</span>
            </button>
            <div class="services-track" ref="servicesTrack">
              <article
                v-for="service in services"
                :key="service.title"
                class="service-card reveal"
              >
                <div class="service-card-top">
                  <div class="service-tag">{{ service.duration }}</div>
                  <div class="service-price-chip">{{ service.price }}</div>
                </div>
                <div class="service-title">{{ service.title }}</div>
                <p class="service-description">{{ service.description }}</p>
                <ul class="service-list">
                  <li v-for="point in service.points" :key="point">{{ point }}</li>
                </ul>
              </article>
            </div>
            <button
              class="services-arrow services-arrow--next"
              type="button"
              @click="showNextService"
              :disabled="!servicesCanScrollNext"
              aria-label="Следующие услуги"
            >
              <span aria-hidden="true">›</span>
            </button>
          </div>
        </div>
      </div>
    </section>

    <!-- Experience -->
    <section class="section" id="experience" aria-label="Опыт">
      <div class="container">
        <div class="section-head">
          <h2 class="section-title">Опыт</h2>
        </div>
        <div class="section-sub">
          <span class="section-chip">Клиенты</span>
        </div>
        <div class="logo-grid" aria-label="Клиенты">
          <div
            v-for="logo in clientLogos"
            :key="logo.name"
            class="logo-item reveal"
            :class="{ 'logo-item--boosted': logo.boosted }"
            :aria-label="logo.name"
            :title="logo.name"
          >
            <img
              class="logo-img"
              :class="{ 'logo-img--boosted': logo.boosted }"
              :src="logo.src"
              :alt="`Логотип ${logo.name}`"
              loading="lazy"
            />
          </div>
        </div>
        <div class="section-sub">
          <span class="section-chip">Площадки</span>
        </div>
        <div class="logo-grid" aria-label="Площадки">
          <div
            v-for="logo in platformLogos"
            :key="logo.name"
            class="logo-item reveal"
            :aria-label="logo.name"
            :title="logo.name"
          >
            <img
              class="logo-img"
              :src="logo.src"
              :alt="`Логотип ${logo.name}`"
              loading="lazy"
            />
          </div>
        </div>
      </div>
    </section>

    <!-- Contacts -->
    <section class="section" id="contacts" aria-label="Контакты">
      <div class="container">
        <div class="section-head">
          <h2 class="section-title">Контакты</h2>
        </div>
        <div class="contact-card reveal">
          <p class="contact-links-title">Записаться через</p>
          <div class="contact-links">
            <a
              class="cta"
              href="https://t.me/artnikandroff"
              target="_blank"
              rel="noreferrer"
              aria-label="Записаться через Telegram"
            >
              Telegram
            </a>
            <a
              class="cta"
              href="https://max.ru/u/f9LHodD0cOKOk3e7pHhYRhaIWWumNPMgaK_WPG-4XbidA4zJc0MUe_FUY-8"
              target="_blank"
              rel="noreferrer"
              aria-label="Записаться через Max"
            >
              MAX
            </a>
          </div>
          <p class="contact-privacy">
            Переходя в мессенджер и отправляя сообщение, вы соглашаетесь с
            обработкой персональных данных согласно
            <a href="/privacy">Политике</a>.
          </p>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer aria-label="Футер">
      <div class="container footer-row">
        <div class="footer-legal">
          <div>© {{ year }} ИП Никандров Артем Олегович</div>
          <div>ИНН 352535819890</div>
          <a class="footer-email" href="mailto:artnikandrov@gmail.com">artnikandrov@gmail.com</a>
        </div>
        <div class="footer-links">
          <a href="#about" @click.prevent="scrollTo('about')">О себе</a>
          <a href="#services" @click.prevent="scrollTo('services')">Услуги</a>
          <a href="#experience" @click.prevent="scrollTo('experience')">Опыт</a>
          <a href="#contacts" @click.prevent="scrollTo('contacts')">Контакты</a>
          <a href="/privacy">Политика</a>
        </div>
      </div>
    </footer>
  </div>

  <aside
    v-if="showCookieBanner"
    class="cookie-banner"
    role="dialog"
    aria-live="polite"
    aria-label="Настройки cookies"
  >
    <div>
      <p class="cookie-title">Cookies</p>
      <p class="cookie-text">
        Сайт использует необходимые cookies. Аналитические cookies для Яндекс
        Метрики будут включаться только после вашего согласия.
        <a href="/privacy">Подробнее</a>
      </p>
    </div>
    <div class="cookie-actions">
      <button class="cookie-button cookie-button--secondary" type="button" @click="rejectAnalyticsCookies">
        Только необходимые
      </button>
      <button class="cookie-button" type="button" @click="acceptAnalyticsCookies">
        Принять
      </button>
    </div>
  </aside>
</template>

<script setup>
import { computed, onBeforeUnmount, onMounted, ref } from "vue";
import authorPhoto from "./assets/author-photo-artem.jpg";

const COOKIE_CONSENT_KEY = "artnikandrov_cookie_consent";
const YANDEX_METRIKA_ID = "";

const clientLogos = [
  { name: "Karcher", src: "/logos/karcher-new.png", boosted: true },
  { name: "Electrolux", src: "/logos/electrolux-new.png", boosted: true },
  { name: "Nestle", src: "/logos/nestle-new.png" },
  { name: "PepsiCo", src: "/logos/PepsiCo-new.png", boosted: true },
  { name: "JDE", src: "/logos/JDE-new.png" },
  { name: "Borjomi", src: "/logos/borjomi-new.png" },
  { name: "Акрихин", src: "/logos/akrihin-new.png", boosted: true },
  { name: "Сотекс", src: "/logos/sotex-new.png", boosted: true },
  { name: "ФрутоНяня", src: "/logos/fruto-nyanya-new.png" },
  { name: "билайн", src: "/logos/beeline-new.png" },
  { name: "Woerwag", src: "/logos/woerwag-new.png" },
  { name: "Аванта", src: "/logos/avanta-new.png", boosted: true },
  { name: "Село Зелёное", src: "/logos/selo-zelenoe-new.png" },
  { name: "X5", src: "/logos/X5-new.png" },
  { name: "Коломенский", src: "/logos/kolomenskiy-new.png", boosted: true },
  { name: "Полисорб", src: "/logos/polisorb-new.png", boosted: true },
];

const platformLogos = [
  { name: "Ozon", src: "/logos/Ozon-new.png" },
  { name: "Wildberries", src: "/logos/WB-new.png" },
  { name: "Яндекс Маркет", src: "/logos/yandex-market-new.png" },
  { name: "Мегамаркет", src: "/logos/mega-market-new.png" },
  { name: "Самокат", src: "/logos/samokat-new.png" },
  { name: "Яндекс Лавка", src: "/logos/yandex-lavka-new.png" },
  { name: "Яндекс Еда", src: "/logos/yandex-eda-new-2.png" },
  { name: "Деливери", src: "/logos/delivery-new.png" },
  { name: "Купер", src: "/logos/kuper-new.png" },
  { name: "Лента", src: "/logos/lenta-new.png" },
  { name: "X5", src: "/logos/X5-new.png" },
  { name: "Ситилинк", src: "/logos/citylink-new.png" },
  { name: "apteka.ru", src: "/logos/apteka-ru-new.png" },
  { name: "Магнит", src: "/logos/magnit-new.png" },
  { name: "Еаптека", src: "/logos/eapteka-new.png" },
  { name: "Ютека", src: "/logos/yuteka-new.png" },
  { name: "Апрель", src: "/logos/aprel-new.png", boosted: true },
  { name: "Яндекс UrbanAds", src: "/logos/yandex-urbanads-new.png" },
];

const services = [
  {
    title: "Консультация по retail media и рекламе в e-commerce",
    duration: "1,5 часа",
    price: "50 000 руб",
    description: "Разбор вашей ситуации и ответы на ключевые вопросы:",
    points: [
      "как распределять бюджет между маркетплейсами",
      "какие рекламные инструменты использовать",
      "как оценивать эффективность (ДРР, TACoS, омниканальные приросты)",
      "как работать с трафиком и конверсией",
      "что улучшить в контенте и креативах",
    ],
  },
  {
    title: "Разработка стратегии маркетинга в e-commerce",
    duration: "Стратегический проект",
    price: "от 250 000 руб",
    description: "Комплексная стратегия работы с маркетплейсами и онлайн-ритейлом:",
    points: [
      "анализ рынка и категории",
      "конкурентный анализ",
      "CJM и точки контакта",
      "мэппинг онлайн-ритейлеров",
      "медиамикс и сплит инструментов",
      "прогноз продаж и эффективности",
    ],
  },
  {
    title: "Адаптация digital-стратегии под e-commerce",
    duration: "Тактический блок",
    price: "от 150 000 руб",
    description: "Перевод общей маркетинговой стратегии в конкретную тактику для e-commerce:",
    points: [
      "медиапланирование",
      "выбор каналов и инструментов",
      "синхронизация с performance и брендовыми задачами",
    ],
  },
  {
    title: "Аудит рекламы в e-commerce",
    duration: "Аудит и рекомендации",
    price: "от 100 000 руб",
    description: "Анализ текущих рекламных кампаний:",
    points: [
      "оценка эффективности размещений",
      "проверка закупочных метрик по рынку",
      "выявление точек роста",
      "рекомендации по оптимизации",
    ],
  },
  {
    title: "Обучение команд e-commerce и retail media",
    duration: "2 часа",
    price: "120 000 руб",
    description: "Практический тренинг под задачи бизнеса:",
    points: [
      "как работает реклама на маркетплейсах",
      "ключевые метрики и аналитика",
      "тренды e-commerce и retail media",
      "разбор кейсов из вашей категории",
    ],
  },
  {
    title: "Карьерная консультация в e-commerce",
    duration: "1 час",
    price: "10 000 руб",
    description: "Для специалистов уровня junior-middle:",
    points: [
      "разбор резюме",
      "рекомендации по карьерному росту",
      "ориентиры по зарплате",
      "развитие личного бренда в e-commerce",
    ],
  },
];

const year = new Date().getFullYear();
const currentPath = ref(typeof window !== "undefined" ? window.location.pathname : "/");
const isPrivacyPage = computed(() => currentPath.value.replace(/\/$/, "") === "/privacy");
const showCookieBanner = ref(false);
const scrollProgress = ref(0);
const servicesTrack = ref(null);
const servicesCanScrollPrev = ref(false);
const servicesCanScrollNext = ref(true);
let rafId = 0;
let revealObserver = null;
let metrikaLoaded = false;

const loadYandexMetrika = () => {
  if (!YANDEX_METRIKA_ID || metrikaLoaded || typeof window === "undefined") return;
  metrikaLoaded = true;

  window.ym =
    window.ym ||
    function (...args) {
      (window.ym.a = window.ym.a || []).push(args);
    };
  window.ym.l = Number(new Date());

  const script = document.createElement("script");
  script.async = true;
  script.src = "https://mc.yandex.ru/metrika/tag.js";
  document.head.appendChild(script);

  window.ym(Number(YANDEX_METRIKA_ID), "init", {
    clickmap: true,
    trackLinks: true,
    accurateTrackBounce: true,
    webvisor: true,
  });
};

const readCookieConsent = () => {
  if (typeof window === "undefined") return null;
  return window.localStorage.getItem(COOKIE_CONSENT_KEY);
};

const saveCookieConsent = (value) => {
  if (typeof window === "undefined") return;
  window.localStorage.setItem(COOKIE_CONSENT_KEY, value);
  showCookieBanner.value = false;
};

const acceptAnalyticsCookies = () => {
  saveCookieConsent("analytics");
  loadYandexMetrika();
};

const rejectAnalyticsCookies = () => {
  saveCookieConsent("necessary");
};

const updateServicesArrows = () => {
  const el = servicesTrack.value;
  if (!el) return;
  const maxScrollLeft = el.scrollWidth - el.clientWidth;
  servicesCanScrollPrev.value = el.scrollLeft > 4;
  servicesCanScrollNext.value = el.scrollLeft < maxScrollLeft - 4;
};

const scrollServicesByPage = (direction) => {
  const el = servicesTrack.value;
  if (!el) return;
  const styles = window.getComputedStyle(el);
  const gap = Number.parseFloat(styles.columnGap || styles.gap || "0") || 0;
  const cardsPerView = window.innerWidth <= 960 ? 1 : 2;
  const cardWidth = (el.clientWidth - gap * (cardsPerView - 1)) / cardsPerView;
  const offset = (cardWidth + gap) * cardsPerView * direction;
  el.scrollBy({ left: offset, behavior: "smooth" });
};

const showPrevService = () => scrollServicesByPage(-1);
const showNextService = () => scrollServicesByPage(1);

const scrollTo = (id) => {
  const target = document.getElementById(id);
  if (target) {
    target.scrollIntoView({ behavior: "smooth", block: "start" });
  }
};

const updateScrollProgress = () => {
  const doc = document.documentElement;
  const scrollTop = window.scrollY || doc.scrollTop || 0;
  const scrollHeight = doc.scrollHeight - doc.clientHeight;
  const progress = scrollHeight > 0 ? (scrollTop / scrollHeight) * 100 : 0;
  scrollProgress.value = Math.min(100, Math.max(0, progress));
  doc.style.setProperty("--parallax", `${scrollTop * 0.12}px`);
  doc.style.setProperty("--parallax-slow", `${scrollTop * 0.06}px`);
};

const handleScroll = () => {
  if (rafId) return;
  rafId = window.requestAnimationFrame(() => {
    updateScrollProgress();
    rafId = 0;
  });
};

onMounted(() => {
  currentPath.value = window.location.pathname;
  const cookieConsent = readCookieConsent();
  showCookieBanner.value = !cookieConsent;
  if (cookieConsent === "analytics") {
    loadYandexMetrika();
  }

  updateScrollProgress();
  updateServicesArrows();

  window.addEventListener("scroll", handleScroll, { passive: true });
  window.addEventListener("resize", updateServicesArrows, { passive: true });

  if (servicesTrack.value) {
    servicesTrack.value.addEventListener("scroll", updateServicesArrows, { passive: true });
  }

  revealObserver = new IntersectionObserver(
    (entries) => {
      entries.forEach((entry) => {
        if (entry.isIntersecting) {
          entry.target.classList.add("is-visible");
          revealObserver?.unobserve(entry.target);
        }
      });
    },
    { threshold: 0.15, rootMargin: "0px 0px -10% 0px" }
  );

  document.querySelectorAll(".reveal").forEach((el) => revealObserver?.observe(el));
});

onBeforeUnmount(() => {
  window.removeEventListener("scroll", handleScroll);
  window.removeEventListener("resize", updateServicesArrows);
  if (servicesTrack.value) {
    servicesTrack.value.removeEventListener("scroll", updateServicesArrows);
  }
  if (rafId) {
    window.cancelAnimationFrame(rafId);
  }
  revealObserver?.disconnect();
});
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;600&family=Space+Grotesk:wght@400;600;700&display=swap");

:root {
  --bg: #141414;
  --bg-soft: #1a1a1a;
  --bg-muted: #262626;
  --ink: #ffffff;
  --ink-strong: #ffffff;
  --ink-soft: #ffffff;
  --ink-muted: #ffffff;
  --accent: #ff5b00;
  --accent-hover: #ff7a33;
  --accent-pressed: #cc4900;
  --accent-ink: #ffffff;
  --card: #1a1a1a;
  --card-alt: #262626;
  --surface-dark: #262626;
  --border: #3a3a3a;
  --border-strong: #ffffff;
  --shadow: 0 18px 40px rgba(0, 0, 0, 0.22);
  --shadow-soft: 0 20px 48px rgba(0, 0, 0, 0.28);
  --shadow-float: 0 24px 60px rgba(0, 0, 0, 0.34);
  --text-shadow: none;
  --container: 1120px;
  --radius: 18px;
  --transition: 180ms ease;
  --parallax: 0px;
  --parallax-slow: 0px;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: "Space Grotesk", system-ui, sans-serif;
  color: var(--ink);
  background: var(--bg);
  line-height: 1.6;
  overflow-x: hidden;
  scrollbar-width: thin;
  scrollbar-color: var(--border-strong) transparent;
}

.page {
  min-height: 100vh;
  background:
    linear-gradient(118deg, transparent 0 10%, rgba(255, 91, 0, 0.52) 10.12%, transparent 10.42%),
    linear-gradient(73deg, transparent 0 24%, rgba(255, 91, 0, 0.44) 24.14%, transparent 24.42%),
    linear-gradient(134deg, transparent 0 47%, rgba(255, 91, 0, 0.38) 47.12%, transparent 47.38%),
    linear-gradient(58deg, transparent 0 66%, rgba(255, 91, 0, 0.34) 66.16%, transparent 66.42%),
    linear-gradient(149deg, transparent 0 82%, rgba(255, 91, 0, 0.3) 82.14%, transparent 82.34%),
    linear-gradient(180deg, #141414 0%, #1a1a1a 100%);
  position: relative;
}

::-webkit-scrollbar {
  width: 10px;
  height: 10px;
}

::-webkit-scrollbar-track {
  background: transparent;
}

::-webkit-scrollbar-thumb {
  background: var(--border-strong);
  border-radius: 999px;
  border: 2px solid var(--bg);
}

.scroll-progress {
  position: fixed;
  top: 0;
  left: 0;
  height: 4px;
  width: 100%;
  background: rgba(255, 255, 255, 0.12);
  z-index: 30;
}

.scroll-progress-bar {
  height: 100%;
  background: linear-gradient(90deg, var(--ink-strong) 0%, var(--accent) 100%);
  width: 0%;
  transition: width 120ms linear;
}

a {
  color: inherit;
  text-decoration: none;
}

.container {
  width: min(92%, var(--container));
  margin: 0 auto;
}

.ticker {
  background: var(--surface-dark);
  color: #ffffff;
  font-family: "IBM Plex Mono", monospace;
  text-transform: uppercase;
  letter-spacing: 0.24em;
  font-size: 12px;
  overflow: hidden;
  border-bottom: 1px solid var(--border-strong);
}

.ticker-track {
  display: flex;
  width: max-content;
  min-width: 100%;
  padding: 12px 0;
  animation: ticker 18s linear infinite;
}

.ticker-group {
  flex: 0 0 100%;
  min-width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: clamp(32px, 7vw, 120px);
}

.ticker-track span {
  flex: 1 1 0;
  text-align: center;
  white-space: nowrap;
}

@keyframes ticker {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-33.333%);
  }
}

.site-header {
  position: sticky;
  top: 0;
  background: rgba(20, 20, 20, 0.92);
  backdrop-filter: blur(12px);
  border-bottom: 1px solid var(--border);
  z-index: 10;
}

.header-row {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 18px 0;
  gap: 18px;
}

.logo {
  display: flex;
  align-items: center;
  gap: 12px;
  font-weight: 700;
  font-size: clamp(14px, 1.7vw, 16px);
  text-transform: uppercase;
  letter-spacing: 0.08em;
}

.logo-dot {
  width: 18px;
  height: 18px;
  border-radius: 50%;
  background: var(--accent);
  border: 1px solid var(--border-strong);
}

.nav-links {
  display: flex;
  gap: 20px;
  font-size: 14px;
  text-transform: uppercase;
  letter-spacing: 0.16em;
  font-family: "IBM Plex Mono", monospace;
}

.nav-links a {
  padding-bottom: 4px;
  border-bottom: 2px solid transparent;
  transition: border-color var(--transition);
}

.nav-links a:hover {
  border-color: var(--accent);
}

.cta {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  background: var(--accent);
  color: var(--accent-ink);
  border: 1px solid var(--accent);
  padding: 14px 26px;
  border-radius: 999px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  box-shadow: var(--shadow);
  transition: transform var(--transition), background var(--transition), border-color var(--transition);
}

.cta:hover {
  background: var(--accent-hover);
  border-color: var(--accent-hover);
  transform: translate(-2px, -2px);
}

.cta:active {
  background: var(--accent-pressed);
  border-color: var(--accent-pressed);
}

.cta.small {
  padding: 10px 18px;
  font-size: 12px;
  box-shadow: none;
}

.hero {
  padding: 80px 0 40px;
  position: relative;
  overflow: hidden;
}

.hero-grid {
  display: grid;
  grid-template-columns: minmax(0, 1.1fr) minmax(0, 0.9fr);
  gap: 36px;
  align-items: start;
}

.hero-main {
  padding: 40px;
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  box-shadow: var(--shadow);
}

.hero-side {
  display: grid;
  gap: 22px;
}

.hero-decor {
  position: absolute;
  inset: -10% 0 0;
  pointer-events: none;
  z-index: 0;
}

.hero-grid {
  position: relative;
  z-index: 1;
}

.orb {
  display: none;
}

.photo-card {
  margin: 0;
  padding: 18px;
  border: 1px solid var(--border);
  border-radius: var(--radius);
  background: var(--card);
  box-shadow: var(--shadow);
  display: grid;
  gap: 14px;
}

.photo-frame {
  border-radius: calc(var(--radius) - 6px);
  border: 1px solid var(--border);
  overflow: hidden;
  background: var(--bg-muted);
  aspect-ratio: 5 / 8.6;
}

.photo-img {
  width: 100%;
  height: 100%;
  min-height: clamp(420px, 58vw, 620px);
  object-fit: cover;
  object-position: center 18%;
  display: block;
  filter: saturate(0.95) contrast(1.05);
}

.photo-caption {
  font-family: "IBM Plex Mono", monospace;
  font-size: 12px;
  text-transform: uppercase;
  letter-spacing: 0.18em;
  color: var(--ink-soft);
}

.eyebrow {
  font-family: "IBM Plex Mono", monospace;
  text-transform: uppercase;
  letter-spacing: 0.32em;
  font-size: 12px;
  margin-bottom: 16px;
}

.hero-title {
  font-size: clamp(36px, 5vw, 64px);
  line-height: 1.05;
  margin-bottom: 18px;
  text-shadow: var(--text-shadow);
}

.hero-title-name {
  display: block;
  color: var(--accent);
}

.hero-title-sub {
  display: block;
  font-size: 0.68em;
  margin-top: 0.1em;
}

.hero-subtitle {
  font-size: 18px;
  color: var(--ink-strong);
  margin-bottom: 28px;
}

.hero-specialties {
  margin-bottom: 28px;
}

.hero-specialties-title {
  font-size: 18px;
  font-weight: 700;
  margin-bottom: 14px;
  color: var(--ink-strong);
}

.hero-specialties-list {
  margin: 0 0 18px;
  padding-left: 22px;
  display: grid;
  gap: 10px;
  color: var(--ink-strong);
}

.hero-specialties-list li {
  line-height: 1.45;
}

.hero-specialties-note {
  margin: 0;
  color: var(--ink-strong);
  line-height: 1.55;
}

.hero-actions {
  display: flex;
  align-items: center;
  gap: 16px;
  flex-wrap: wrap;
}

.hero-note {
  font-family: "IBM Plex Mono", monospace;
  font-size: 12px;
  text-transform: uppercase;
  letter-spacing: 0.2em;
}

.hero-panel {
  border: 1px solid var(--border);
  border-radius: var(--radius);
  background: var(--card-alt);
  padding: 28px;
  box-shadow: var(--shadow);
}

.panel-header {
  font-family: "IBM Plex Mono", monospace;
  text-transform: uppercase;
  letter-spacing: 0.18em;
  font-size: 12px;
  margin-bottom: 16px;
}

.panel-list {
  display: grid;
  gap: 18px;
}

.panel-item {
  display: grid;
  gap: 6px;
}

.panel-item p {
  color: var(--ink-muted);
}

.tag {
  display: inline-flex;
  align-items: center;
  padding: 4px 10px;
  border: 1px solid var(--border);
  border-radius: 999px;
  font-size: 11px;
  text-transform: uppercase;
  letter-spacing: 0.22em;
  font-family: "IBM Plex Mono", monospace;
  color: var(--ink);
  background: var(--card);
  width: fit-content;
}

.section {
  padding: 70px 0;
}

.reveal {
  opacity: 0;
  transform: translateY(26px) scale(0.98);
  transition: opacity 500ms ease, transform 520ms ease;
}

.reveal.is-visible {
  opacity: 1;
  transform: translateY(0) scale(1);
}

.section-head {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  margin-bottom: 24px;
}

.section-title {
  font-size: clamp(26px, 3.4vw, 40px);
  text-transform: uppercase;
  text-shadow: var(--text-shadow);
}

.section-chip {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 8px 18px;
  border-radius: 14px;
  border: 1px solid var(--border);
  font-family: "IBM Plex Mono", monospace;
  text-transform: uppercase;
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 0.14em;
  background: var(--card);
  box-shadow: var(--shadow);
}

.lead {
  font-size: 18px;
  max-width: 720px;
}

.about-list {
  list-style: disc;
  padding-left: 24px;
  margin: 0;
  display: grid;
  gap: 12px;
  font-size: 17px;
  line-height: 1.4;
}

.about-list li {
  padding-left: 4px;
  font-weight: 600;
}

.about-list li:hover {
  transform: none;
  box-shadow: none;
}

.about-list a {
  color: var(--accent);
  font-weight: 700;
  text-decoration: none;
}

.about-list a:hover {
  color: var(--accent-hover);
}

.about-grid {
  display: grid;
  grid-template-columns: minmax(0, 0.92fr) minmax(0, 1.08fr);
  gap: 28px;
  align-items: stretch;
}

.about-copy {
  min-width: 0;
  height: 100%;
  box-sizing: border-box;
  padding: 28px;
  border: 1px solid var(--border);
  border-radius: var(--radius);
  background:
    radial-gradient(circle at top right, rgba(255, 91, 0, 0.1), transparent 32%),
    linear-gradient(180deg, rgba(38, 38, 38, 0.95), rgba(26, 26, 26, 0.98));
  box-shadow: var(--shadow);
}

.about-section-title {
  margin: 0 0 22px;
}

.about-when {
  height: 100%;
  box-sizing: border-box;
  padding: 28px;
  border: 1px solid var(--border);
  border-radius: var(--radius);
  background:
    radial-gradient(circle at top right, rgba(255, 91, 0, 0.14), transparent 34%),
    linear-gradient(180deg, rgba(38, 38, 38, 0.95), rgba(26, 26, 26, 0.98));
  box-shadow: var(--shadow);
}

.about-when-heading {
  margin-bottom: 16px;
}

.about-when-title {
  margin: 0 0 18px;
  font-size: 18px;
  line-height: 1.45;
  color: var(--ink-strong);
}

.about-when-list {
  margin: 0;
  padding-left: 22px;
  display: grid;
  gap: 14px;
  font-size: 17px;
  line-height: 1.5;
}

.about-when-list li::marker {
  color: var(--accent);
}

.approach-card {
  display: grid;
  grid-template-columns: minmax(0, 1.15fr) minmax(320px, 0.85fr);
  gap: 28px;
  padding: 32px;
  border: 1px solid var(--border);
  border-radius: var(--radius);
  background:
    radial-gradient(circle at top left, rgba(255, 91, 0, 0.12), transparent 28%),
    linear-gradient(180deg, rgba(26, 26, 26, 0.98), rgba(20, 20, 20, 1));
  box-shadow: var(--shadow);
}

.approach-copy {
  min-width: 0;
}

.approach-lead {
  margin: 0 0 18px;
  font-size: 18px;
  line-height: 1.6;
  font-weight: 400;
}

.approach-text {
  margin: 0 0 16px;
  font-size: 18px;
  line-height: 1.6;
  color: var(--ink-strong);
  max-width: 70ch;
}

.approach-text:last-child {
  margin-bottom: 0;
}

.approach-points {
  align-self: stretch;
  margin-top: 62px;
  padding: 24px;
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: calc(var(--radius) - 2px);
  background: rgba(255, 255, 255, 0.03);
}

.approach-points-title {
  margin-bottom: 16px;
  font-size: 18px;
  font-weight: 700;
  line-height: 1.45;
}

.approach-list {
  margin: 0;
  padding-left: 22px;
  display: grid;
  gap: 12px;
  font-size: 18px;
  line-height: 1.6;
}

.approach-list li::marker {
  color: var(--accent);
}

.quote-card {
  padding: 24px;
  border: 1px solid var(--border);
  border-radius: var(--radius);
  background: var(--card-alt);
  font-style: italic;
  box-shadow: var(--shadow);
  transition: transform var(--transition), box-shadow var(--transition);
}

.quote-card:hover {
  transform: translate(-2px, -2px);
  box-shadow: var(--shadow-soft);
}

.when-rail {
  padding: 6px;
  border-radius: calc(var(--radius) + 6px);
}

.when-shelf {
  display: grid;
  grid-auto-flow: column;
  grid-auto-columns: minmax(240px, 1fr);
  gap: 18px;
  padding: 14px 12px 22px;
  overflow-x: auto;
  overflow-y: visible;
  scroll-snap-type: x proximity;
  scroll-padding-inline: 18px;
  -webkit-overflow-scrolling: touch;
  scrollbar-color: var(--accent) transparent;
}

.when-card {
  position: relative;
  padding: 24px 22px 24px 58px;
  border-radius: var(--radius);
  border: 1px solid var(--border);
  background: var(--card);
  box-shadow: var(--shadow);
  font-weight: 600;
  min-height: 110px;
  display: flex;
  align-items: center;
  scroll-snap-align: start;
  transition: transform var(--transition), box-shadow var(--transition);
}

.when-card:nth-child(odd) {
  transform: translateY(-6px);
}

.when-card:nth-child(even) {
  transform: translateY(6px);
}

.when-card:hover {
  transform: translateY(-10px);
  box-shadow: var(--shadow-soft);
}

.when-index {
  position: absolute;
  left: 18px;
  top: 18px;
  width: 30px;
  height: 30px;
  border-radius: 999px;
  background: var(--accent);
  color: #ffffff;
  font-size: 12px;
  letter-spacing: 0.08em;
  font-weight: 700;
  display: grid;
  place-items: center;
}

.service-card {
  flex: 0 0 calc((100% - 22px) / 2);
  min-height: 520px;
  box-sizing: border-box;
  padding: 26px;
  border-radius: var(--radius);
  border: 1px solid var(--border);
  background:
    radial-gradient(circle at top right, rgba(255, 91, 0, 0.12), transparent 30%),
    linear-gradient(180deg, rgba(38, 38, 38, 0.96), rgba(26, 26, 26, 0.98));
  box-shadow: var(--shadow);
  display: grid;
  gap: 16px;
  align-content: start;
  scroll-snap-align: start;
  transition: transform var(--transition), box-shadow var(--transition);
}

.service-card:hover {
  transform: translate(-3px, -3px);
  box-shadow: var(--shadow-float);
}

.service-card-top {
  display: flex;
  justify-content: space-between;
  gap: 16px;
  align-items: center;
  flex-wrap: wrap;
}

.service-tag,
.service-price-chip {
  border: 1px solid var(--border);
  border-radius: 999px;
  padding: 10px 14px;
  background: rgba(255, 255, 255, 0.03);
  font-family: "IBM Plex Mono", monospace;
  font-size: 12px;
  text-transform: uppercase;
  letter-spacing: 0.12em;
}

.service-price-chip {
  color: var(--accent);
}

.service-title {
  font-weight: 700;
  font-size: 24px;
  line-height: 1.2;
  text-shadow: var(--text-shadow);
}

.service-description {
  margin: 0;
  color: var(--ink-muted);
  font-size: 18px;
  line-height: 1.6;
}

.service-list {
  margin: 0;
  padding-left: 22px;
  display: grid;
  gap: 14px;
  font-size: 18px;
  line-height: 1.6;
}

.service-list li::marker {
  color: var(--accent);
}

.services-rail {
  padding-top: 10px;
}

.services-slider {
  position: relative;
}

.services-mobile-hint {
  display: none;
  margin: 0 0 14px;
  align-items: center;
  gap: 8px;
  font-family: "IBM Plex Mono", monospace;
  font-size: 12px;
  text-transform: uppercase;
  letter-spacing: 0.14em;
  color: rgba(255, 255, 255, 0.78);
}

.services-track {
  display: flex;
  gap: 22px;
  overflow-x: auto;
  overflow-y: hidden;
  scroll-snap-type: x mandatory;
  scroll-behavior: smooth;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}

.services-track::-webkit-scrollbar {
  display: none;
}

.services-arrow {
  appearance: none;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  width: 54px;
  height: 54px;
  border: 1px solid rgba(255, 255, 255, 0.14);
  border-radius: 999px;
  background: rgba(20, 20, 20, 0.84);
  color: var(--ink-strong);
  backdrop-filter: blur(10px);
  display: inline-flex;
  align-items: center;
  justify-content: center;
  font-size: 34px;
  line-height: 1;
  cursor: pointer;
  opacity: 0;
  pointer-events: none;
  transition: opacity var(--transition), transform var(--transition), border-color var(--transition), color var(--transition);
  z-index: 2;
}

.services-slider:hover .services-arrow:not(:disabled) {
  opacity: 1;
  pointer-events: auto;
}

.services-arrow--prev {
  left: -18px;
}

.services-arrow--next {
  right: -18px;
}

.services-arrow:hover:not(:disabled) {
  transform: translateY(-50%) scale(1.04);
  border-color: var(--accent);
  color: var(--accent);
}

.services-arrow:disabled {
  opacity: 0;
  pointer-events: none;
  cursor: not-allowed;
}

.logo-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 10px;
  margin-top: 14px;
  align-items: center;
}

.logo-item {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  min-height: clamp(118px, 11.5vw, 142px);
  padding: 12px 16px;
  box-sizing: border-box;
  transition: transform var(--transition), box-shadow var(--transition);
}

.logo-item--boosted {
  padding: 8px 12px;
}

.logo-item:hover {
  transform: translate(-2px, -2px);
}

.logo-img {
  width: auto;
  height: auto;
  max-width: 100%;
  max-height: 86px;
  object-fit: contain;
}

.logo-img--boosted {
  max-height: 104px;
}

@media (max-width: 720px) {
  .logo-grid {
    gap: 8px;
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .logo-item {
    min-height: 104px;
    padding: 10px 14px;
  }

  .logo-item--boosted {
    padding: 6px 10px;
  }

  .logo-img {
    max-height: 68px;
  }

  .logo-img--boosted {
    max-height: 82px;
  }
}

.section-sub {
  margin-top: 28px;
  font-family: "IBM Plex Mono", monospace;
  text-transform: uppercase;
  letter-spacing: 0.18em;
  font-size: 12px;
}

.contact-card {
  max-width: 700px;
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 28px;
  background: var(--card);
  box-shadow: var(--shadow);
  display: grid;
  gap: 16px;
  transition: transform var(--transition), box-shadow var(--transition);
}

.contact-card:hover {
  transform: translate(-2px, -2px);
  box-shadow: var(--shadow-soft);
}

.contact-card p {
  color: var(--ink-muted);
}

.contact-links-title {
  margin: 0;
  font-family: "IBM Plex Mono", monospace;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  font-size: 12px;
  color: var(--ink-muted);
}

.contact-links {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

.contact-links .cta {
  width: auto;
  max-width: 100%;
}

.contact-privacy {
  max-width: 560px;
  font-size: 13px;
  line-height: 1.5;
}

.contact-privacy a,
.privacy-content a,
.footer-legal a,
.cookie-text a {
  color: var(--accent-hover);
  border-bottom: 1px solid currentColor;
}

.contact-privacy a:hover,
.privacy-content a:hover,
.footer-legal a:hover,
.cookie-text a:hover {
  color: var(--ink-strong);
}

.chip {
  padding: 8px 14px;
  border-radius: 999px;
  border: 1px solid var(--border);
  font-family: "IBM Plex Mono", monospace;
  font-size: 12px;
  text-transform: uppercase;
}

footer {
  border-top: 1px solid var(--border);
  padding: 24px 0 40px;
  font-family: "IBM Plex Mono", monospace;
  font-size: 12px;
  text-transform: uppercase;
  letter-spacing: 0.14em;
}

.footer-row {
  display: flex;
  justify-content: space-between;
  gap: 18px;
  flex-wrap: wrap;
}

.footer-row--legal {
  align-items: flex-start;
}

.footer-legal {
  display: grid;
  gap: 8px;
  max-width: 520px;
  line-height: 1.5;
}

.footer-legal .footer-email {
  border-bottom: 0;
  text-decoration: none;
}

.footer-links {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
}

.footer-links a:hover {
  color: var(--accent);
}

.privacy-page {
  min-height: 100vh;
}

.privacy-main {
  min-height: calc(100vh - 180px);
}

.privacy-section {
  padding-top: 72px;
}

.privacy-container {
  max-width: 920px;
}

.privacy-title {
  max-width: 820px;
  margin-top: 14px;
  font-size: clamp(36px, 6vw, 70px);
  line-height: 0.95;
  letter-spacing: 0;
  text-transform: uppercase;
}

.privacy-updated {
  margin-top: 18px;
  color: var(--ink-muted);
  font-family: "IBM Plex Mono", monospace;
  font-size: 13px;
  text-transform: uppercase;
  letter-spacing: 0.12em;
}

.privacy-content {
  display: grid;
  gap: 28px;
  margin-top: 44px;
  padding: 32px;
  border: 1px solid var(--border);
  border-radius: var(--radius);
  background: var(--card);
  box-shadow: var(--shadow);
}

.privacy-content section {
  display: grid;
  gap: 12px;
}

.privacy-content h2 {
  font-size: clamp(20px, 3vw, 28px);
  line-height: 1.15;
}

.privacy-content p,
.privacy-content li {
  color: var(--ink-muted);
  font-size: 16px;
}

.privacy-content ul {
  display: grid;
  gap: 8px;
  padding-left: 22px;
}

.cookie-banner {
  position: fixed;
  right: 24px;
  bottom: 24px;
  z-index: 50;
  width: min(560px, calc(100% - 48px));
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 18px;
  align-items: center;
  padding: 18px;
  border: 1px solid var(--border-strong);
  border-radius: 8px;
  background: rgba(26, 26, 26, 0.98);
  box-shadow: var(--shadow-float);
}

.cookie-title {
  margin-bottom: 6px;
  font-family: "IBM Plex Mono", monospace;
  font-size: 12px;
  letter-spacing: 0.16em;
  text-transform: uppercase;
}

.cookie-text {
  color: var(--ink-muted);
  font-size: 14px;
  line-height: 1.45;
}

.cookie-actions {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  justify-content: flex-end;
}

.cookie-button {
  border: 1px solid var(--accent);
  border-radius: 8px;
  background: var(--accent);
  color: var(--accent-ink);
  cursor: pointer;
  padding: 11px 14px;
  font: inherit;
  font-family: "IBM Plex Mono", monospace;
  font-size: 11px;
  font-weight: 600;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  transition: background var(--transition), border-color var(--transition), transform var(--transition);
}

.cookie-button:hover {
  background: var(--accent-hover);
  border-color: var(--accent-hover);
  transform: translateY(-2px);
}

.cookie-button--secondary {
  background: transparent;
  border-color: var(--border-strong);
}

.cookie-button--secondary:hover {
  background: var(--surface-dark);
  border-color: var(--ink-strong);
}

@media (max-width: 960px) {
  .container {
    width: min(calc(100% - 32px), var(--container));
  }

  .hero-grid {
    grid-template-columns: 1fr;
    gap: 24px;
  }

  .about-grid {
    grid-template-columns: 1fr;
  }

  .approach-card {
    grid-template-columns: 1fr;
    padding: 28px;
  }

  .approach-points {
    margin-top: 0;
  }

  .section-head {
    flex-direction: column;
    align-items: flex-start;
  }

  .services-track {
    gap: 16px;
  }

  .services-arrow {
    opacity: 1;
    pointer-events: auto;
  }

  .services-arrow--prev {
    left: 8px;
  }

  .services-arrow--next {
    right: 8px;
  }
}

@media (max-width: 720px) {
  .container {
    width: min(calc(100% - 24px), var(--container));
  }

  .ticker {
    font-size: 10px;
    letter-spacing: 0.16em;
  }

  .ticker-track {
    padding: 10px 0;
  }

  .ticker-group {
    gap: 20px;
  }

  .header-row {
    flex-direction: column;
    align-items: stretch;
    padding: 14px 0;
  }

  .logo {
    justify-content: center;
  }

  .nav-links {
    flex-wrap: wrap;
    gap: 12px 16px;
    justify-content: center;
    font-size: 12px;
    letter-spacing: 0.12em;
  }

  .site-header .cta.small {
    width: 100%;
  }

  .hero {
    padding: 44px 0 24px;
  }

  .hero-main {
    padding: 22px;
  }

  .hero-side {
    order: -1;
  }

  .hero-title {
    font-size: clamp(30px, 10vw, 42px);
  }

  .hero-subtitle,
  .hero-specialties-title {
    font-size: 16px;
  }

  .hero-specialties-list {
    gap: 8px;
    padding-left: 18px;
  }

  .cta {
    width: 100%;
    justify-content: center;
    text-align: center;
  }

  .photo-card {
    padding: 14px;
  }

  .photo-frame {
    aspect-ratio: 4 / 5;
  }

  .photo-img {
    min-height: 0;
  }

  .section {
    padding: 52px 0;
  }

  .section-title {
    font-size: clamp(24px, 8vw, 32px);
  }

  .about-copy,
  .about-when,
  .approach-card,
  .contact-card {
    padding: 22px;
  }

  .about-list,
  .about-when-list,
  .approach-text,
  .approach-list {
    font-size: 16px;
  }

  .approach-lead,
  .approach-points-title {
    font-size: 17px;
  }

  .approach-points,
  .quote-card {
    padding: 18px;
  }

  .service-title {
    font-size: 21px;
  }

  .service-description,
  .service-list {
    font-size: 16px;
  }

  .service-card {
    flex-basis: 80%;
    min-height: auto;
    padding: 20px;
  }

  .service-card-top {
    align-items: flex-start;
    gap: 10px;
  }

  .service-tag,
  .service-price-chip {
    width: 100%;
    justify-content: center;
    text-align: center;
  }

  .when-card {
    min-height: 120px;
  }

  .when-card:nth-child(odd),
  .when-card:nth-child(even) {
    transform: none;
  }

  .when-card:hover {
    transform: translateY(-6px);
  }

  .services-arrow {
    display: none;
  }

  .services-mobile-hint {
    display: inline-flex;
  }

  .services-slider--has-next::after {
    content: "";
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    width: 28px;
    pointer-events: none;
    background: linear-gradient(90deg, rgba(20, 20, 20, 0), rgba(20, 20, 20, 0.96));
    border-radius: 0 var(--radius) var(--radius) 0;
  }

  .contact-links {
    flex-wrap: nowrap;
    align-items: stretch;
  }

  .contact-links .cta {
    width: auto;
    flex: 1 1 0;
    min-width: 0;
  }

  .footer-row,
  .footer-links {
    flex-direction: column;
    align-items: flex-start;
  }

  .privacy-section {
    padding-top: 52px;
  }

  .privacy-content {
    padding: 22px;
  }

  .cookie-banner {
    left: 12px;
    right: 12px;
    bottom: 12px;
    width: auto;
    grid-template-columns: 1fr;
  }

  .cookie-actions {
    justify-content: stretch;
  }

  .cookie-button {
    flex: 1 1 180px;
  }
}

@media (max-width: 480px) {
  .header-row {
    gap: 14px;
  }

  .nav-links {
    width: 100%;
    justify-content: center;
    align-self: center;
  }

  .hero-main,
  .about-copy,
  .about-when,
  .approach-card,
  .contact-card,
  .service-card {
    padding: 18px;
  }

  .service-card {
    flex-basis: 80%;
  }

  .service-title {
    font-size: 19px;
  }

  .service-description,
  .service-list,
  .about-list,
  .about-when-list,
  .approach-text,
  .approach-list {
    font-size: 15px;
  }

  .logo-grid {
    gap: 6px;
    grid-template-columns: repeat(4, minmax(0, 1fr));
  }

  .logo-item {
    min-height: 72px;
    padding: 8px;
  }

  .logo-item--boosted {
    padding: 6px;
  }

  .logo-img {
    max-height: 40px;
  }

  .logo-img--boosted {
    max-height: 48px;
  }
}

@media (max-width: 380px) {
  .logo-grid {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }
}

@media (prefers-reduced-motion: reduce) {
  .ticker-track,
  .reveal,
  .scroll-progress-bar {
    animation: none;
    transition: none;
  }

  .orb-1,
  .orb-2,
  .orb-3 {
    transform: none;
  }
}
</style>
