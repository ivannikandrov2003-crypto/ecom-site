<template>
  <div class="page">
    <div class="scroll-progress" aria-hidden="true">
      <div class="scroll-progress-bar" :style="{ width: scrollProgress + '%' }"></div>
    </div>
    <!-- Ticker -->
    <div class="ticker" aria-label="Новостная лента">
      <div class="ticker-track">
        <span>Е-COM МАРКЕТИНГ • СТРАТЕГИЯ • РИТЕЙЛ МЕДИА •</span>
        <span>Е-COM МАРКЕТИНГ • СТРАТЕГИЯ • РИТЕЙЛ МЕДИА •</span>
        <span>Е-COM МАРКЕТИНГ • СТРАТЕГИЯ • РИТЕЙЛ МЕДИА •</span>
      </div>
    </div>

    <!-- Header -->
    <header class="site-header" aria-label="Шапка">
      <div class="container header-row">
        <div class="logo" aria-label="Логотип">
          <span class="logo-dot"></span>
          Артём Никандров
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
          <div class="eyebrow">Е-com стратег и преподаватель</div>
          <h1 class="hero-title">Маркетинг, который растит онлайн-продажи.</h1>
          <p class="hero-subtitle">
            Помогаю брендам выстраивать маркетинг в е-коме: растить продажи,
            формировать бренд, запускать рекламные стратегии и встроить e-commerce
            в общую бизнес-логику.
          </p>
          <div class="hero-actions">
            <a class="cta" href="#contacts" @click.prevent="scrollTo('contacts')">
              Записаться на консультацию
            </a>
            <div class="hero-note">Ответ в Telegram в течение дня.</div>
          </div>
        </div>
        <div class="hero-side">
          <figure class="photo-card reveal" aria-label="Фото автора">
            <div class="photo-frame">
              <img class="photo-img" :src="authorPhoto" alt="Фото автора" />
            </div>
            <figcaption class="photo-caption">Автор и ведущий е-com проектов.</figcaption>
          </figure>
          <div class="hero-panel reveal" aria-label="Кратко обо мне">
            <div class="panel-header">Ключевые факты</div>
            <div class="panel-list">
              <div class="panel-item">
                <span class="tag">Образование</span>
                <strong>Выпускник НИУ ВШЭ</strong>
                <p>Преподаватель e-commerce.</p>
              </div>
              <div class="panel-item">
                <span class="tag">Комьюнити</span>
                <strong>Член комитета АРИР по E-Retail Media</strong>
                <p>Работа с PepsiCo, RoRe, АДВ.</p>
              </div>
              <div class="panel-item">
                <span class="tag">Экспертиза</span>
                <strong>Дизайн-мышление и стратегия</strong>
                <p>Автор телеграм-канала «БАЗАР ТУТ РАЗВЕЛИ».</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- About -->
    <section class="section" id="about" aria-label="О себе">
      <div class="container">
        <div class="section-head">
          <h2 class="section-title">О себе</h2>
        </div>
        <div class="about-grid">
          <ul class="about-list" aria-label="Ключевые факты">
            <li class="reveal">Выпускник НИУ ВШЭ.</li>
            <li class="reveal">Член комитета АРИР по E‑Retail Media.</li>
            <li class="reveal">Преподаватель и сертифицированный практик дизайн‑мышления.</li>
            <li class="reveal">Опыт работы с 2020 в PepsiCo, RoRe, АДВ.</li>
          </ul>
          <div class="quote-card reveal">
            «Помогаю брендам выстраивать маркетинг в е-коме: растить онлайн-продажи,
            строить рекламные стратегии, формировать бренд.»
          </div>
        </div>
      </div>
    </section>

    <!-- When -->
    <section class="section" id="when" aria-label="Когда ко мне обращаются">
      <div class="container">
        <div class="section-head">
          <h2 class="section-title">Когда ко мне обращаются</h2>
        </div>
        <div class="when-rail">
          <div class="when-shelf" aria-label="Сценарии обращений">
            <article class="when-card reveal">
              <span class="when-index">01</span>
              Бренд выходит на маркетплейсы.
            </article>
            <article class="when-card reveal">
              <span class="when-index">02</span>
              Рекламный бюджет растёт.
            </article>
            <article class="when-card reveal">
              <span class="when-index">03</span>
              Нужно встроить e-commerce в общую стратегию.
            </article>
            <article class="when-card reveal">
              <span class="when-index">04</span>
              Команда не понимает ритейл медиа.
            </article>
            <article class="when-card reveal">
              <span class="when-index">05</span>
              Агентству нужна экспертиза.
            </article>
          </div>
        </div>
      </div>
    </section>

    <!-- Services -->
    <section class="section" id="services" aria-label="Мои услуги">
      <div class="container">
        <div class="services-hybrid">
          <div class="services-sticky">
            <div class="section-head">
              <h2 class="section-title">Мои услуги</h2>
            </div>
            <p class="services-lead">
              Горизонтальный формат позволяет быстро сравнить форматы работы и
              почувствовать динамику.
            </p>
            <div class="services-progress" aria-hidden="true">
              <div class="services-progress-bar" :style="{ width: servicesProgress + '%' }"></div>
            </div>
            <div class="services-hint">Листайте вправо</div>
          </div>
          <div class="services-rail">
            <div class="service-shelf" ref="serviceShelf" aria-label="Список услуг">
              <article class="service-card reveal">
                <div class="service-title">Консультация по ритейл медиа (1,5 часа)</div>
                <span>Q&A сессия по актуальным темам в е-ком рекламе</span>
              </article>
              <article class="service-card reveal">
                <div class="service-title">Разработка маркетинговой стратегии в е-коме</div>
                <span>Формирование стратегии работы с рекламной на маркетплейсами онлайн-ритейлерах.</span>
              </article>
              <article class="service-card reveal">
                <div class="service-title">Приземление digital стратегии в тактику для е-кома</div>
                <span>Подготовка тактических рекомендаций и медиаплана с учётом действующей digital стратегии для рекламных кампаний в е-коме</span>
              </article>
              <article class="service-card reveal">
                <div class="service-title">Аудит рекламных кампаний</div>
                <span>Анализ текущих размещений в е-коме и поиск точек роста</span>
              </article>
              <article class="service-card reveal">
                <div class="service-title">Обучение команд (2 часа)</div>
                <span>Тренинг по работе с ритейл медиа и маркетингом в е-коме</span>
              </article>
            </div>
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
            class="logo-badge reveal"
            :aria-label="logo.name"
            :title="logo.name"
          >
            <img class="logo-img" :src="logo.src" :alt="`Логотип ${logo.name}`" loading="lazy" />
          </div>
        </div>
        <div class="section-sub">
          <span class="section-chip">Площадки</span>
        </div>
        <div class="logo-grid" aria-label="Площадки">
          <div
            v-for="logo in platformLogos"
            :key="logo.name"
            class="logo-badge reveal"
            :aria-label="logo.name"
            :title="logo.name"
          >
            <img class="logo-img" :src="logo.src" :alt="`Логотип ${logo.name}`" loading="lazy" />
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
          <a class="cta" href="#" aria-label="Записаться через Telegram-бота">
            Записаться через Telegram-бота
          </a>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer aria-label="Футер">
      <div class="container footer-row">
        <div>© {{ year }} Артём Никандров.</div>
        <div class="footer-links">
          <a href="#about" @click.prevent="scrollTo('about')">О себе</a>
          <a href="#services" @click.prevent="scrollTo('services')">Услуги</a>
          <a href="#experience" @click.prevent="scrollTo('experience')">Опыт</a>
          <a href="#contacts" @click.prevent="scrollTo('contacts')">Контакты</a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup>
import { onBeforeUnmount, onMounted, ref } from "vue";
import authorPhoto from "./assets/author-photo.png";

const clientLogos = [
  { name: "Karcher", src: "/logos/karcher.png" },
  { name: "Electrolux", src: "/logos/electrolux.png" },
  { name: "Nestle", src: "/logos/nestle.png" },
  { name: "PepsiCo", src: "/logos/PepsiCo.png" },
  { name: "JDE", src: "/logos/JDE.png" },
  { name: "Borjomi", src: "/logos/borjomi.png" },
  { name: "Акрихин", src: "/logos/Акрихин.png" },
  { name: "Сотекс", src: "/logos/Сотекс.png" },
  { name: "Фрутоняня", src: "/logos/Фрутоняня.png" },
  { name: "Билайн", src: "/logos/Билайн.png" },
  { name: "Woerwag", src: "/logos/Woerwag.png" },
  { name: "Аванта", src: "/logos/Аванта.png" },
  { name: "Село Зелёное", src: "/logos/Село_Зелёное.png" },
  { name: "X5", src: "/logos/X5.png" },
  { name: "Коломенский", src: "/logos/Коломенский.png" },
  { name: "Полисорб", src: "/logos/Полисорб.png" },
];

const platformLogos = [
  { name: "OZON", src: "/logos/OZON.png" },
  { name: "wb", src: "/logos/wb.png" },
  { name: "ЯМаркет", src: "/logos/ЯМаркет.png" },
  { name: "Мегамаркет", src: "/logos/Мегамаркет.png" },
  { name: "Самокат", src: "/logos/Самокат.png" },
  { name: "Яндекс Лавка", src: "/logos/Яндекс Лавка.png" },
  { name: "Яндекс Еда", src: "/logos/Яндекс Еда.png" },
  { name: "Деливери", src: "/logos/Деливери.png" },
  { name: "Купер", src: "/logos/Купер.png" },
  { name: "Лента", src: "/logos/Лента.png" },
  { name: "X5", src: "/logos/X5.png" },
  { name: "Ситилинк", src: "/logos/Ситилинк.png" },
  { name: "apteka.ru", src: "/logos/apteka.ru.png" },
  { name: "Магнит", src: "/logos/Магнит.png" },
  { name: "Еаптека", src: "/logos/Еаптека.png" },
  { name: "Ютека", src: "/logos/Ютека.png" },
  { name: "Апрель", src: "/logos/Апрель.png" },
];

const year = new Date().getFullYear();
const scrollProgress = ref(0);
const servicesProgress = ref(0);
const serviceShelf = ref(null);
let rafId = 0;
let revealObserver = null;

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

const updateServicesProgress = () => {
  const el = serviceShelf.value;
  if (!el) return;
  const max = el.scrollWidth - el.clientWidth;
  const progress = max > 0 ? (el.scrollLeft / max) * 100 : 0;
  servicesProgress.value = Math.min(100, Math.max(0, progress));
};

onMounted(() => {
  updateScrollProgress();
  updateServicesProgress();

  window.addEventListener("scroll", handleScroll, { passive: true });
  window.addEventListener("resize", updateServicesProgress, { passive: true });

  if (serviceShelf.value) {
    serviceShelf.value.addEventListener("scroll", updateServicesProgress, { passive: true });
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
  window.removeEventListener("resize", updateServicesProgress);
  if (serviceShelf.value) {
    serviceShelf.value.removeEventListener("scroll", updateServicesProgress);
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
  --bg: #f2f2f2;
  --ink: #0a0a0a;
  --ink-soft: #2b2b2b;
  --accent: #d6e86a;
  --accent-ink: #0a0a0a;
  --card: #ffffff;
  --border: #0a0a0a;
  --shadow: 6px 6px 0 rgba(0, 0, 0, 0.16);
  --shadow-soft: 10px 14px 28px rgba(10, 10, 10, 0.12);
  --shadow-float: 12px 18px 32px rgba(10, 10, 10, 0.18);
  --text-shadow: 0 1px 0 rgba(10, 10, 10, 0.22);
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
  scrollbar-width: thin;
  scrollbar-color: var(--ink) transparent;
}

.page {
  min-height: 100vh;
  background-image:
    linear-gradient(90deg, rgba(0, 0, 0, 0.05) 1px, transparent 1px),
    linear-gradient(180deg, rgba(0, 0, 0, 0.05) 1px, transparent 1px);
  background-size: 120px 120px;
}

::-webkit-scrollbar {
  width: 10px;
  height: 10px;
}

::-webkit-scrollbar-track {
  background: transparent;
}

::-webkit-scrollbar-thumb {
  background: var(--ink);
  border-radius: 999px;
  border: 2px solid var(--bg);
}

.scroll-progress {
  position: fixed;
  top: 0;
  left: 0;
  height: 4px;
  width: 100%;
  background: rgba(10, 10, 10, 0.08);
  z-index: 30;
}

.scroll-progress-bar {
  height: 100%;
  background: linear-gradient(90deg, #0a0a0a 0%, #d6e86a 100%);
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
  background: var(--ink);
  color: #ffffff;
  font-family: "IBM Plex Mono", monospace;
  text-transform: uppercase;
  letter-spacing: 0.24em;
  font-size: 12px;
  overflow: hidden;
  border-bottom: 2px solid var(--ink);
}

.ticker-track {
  display: flex;
  gap: 48px;
  padding: 12px 0;
  animation: ticker 20s linear infinite;
}

.ticker-track span {
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
  background: rgba(246, 241, 233, 0.9);
  backdrop-filter: blur(12px);
  border-bottom: 2px solid var(--border);
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
  text-transform: uppercase;
  letter-spacing: 0.08em;
}

.logo-dot {
  width: 18px;
  height: 18px;
  border-radius: 50%;
  background: var(--accent);
  border: 2px solid var(--ink);
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
  border-color: var(--ink);
}

.cta {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  background: var(--accent);
  color: var(--accent-ink);
  border: 2px solid var(--ink);
  padding: 14px 26px;
  border-radius: 999px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  box-shadow: var(--shadow);
  transition: transform var(--transition);
}

.cta:hover {
  transform: translate(-2px, -2px);
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
  background: #ffffff;
  border: 2px solid var(--border);
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
  position: absolute;
  border: 2px solid var(--border);
  background: var(--accent);
  opacity: 0.35;
  filter: blur(1px);
  box-shadow: var(--shadow);
}

.orb-1 {
  width: 240px;
  height: 240px;
  border-radius: 32px;
  top: 10%;
  left: 6%;
  transform: translateY(var(--parallax-slow)) rotate(6deg);
}

.orb-2 {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  top: 52%;
  right: 8%;
  transform: translateY(var(--parallax)) rotate(-10deg);
}

.orb-3 {
  width: 140px;
  height: 140px;
  border-radius: 28px;
  bottom: 12%;
  left: 42%;
  transform: translateY(calc(var(--parallax-slow) * 0.8)) rotate(14deg);
}

.photo-card {
  margin: 0;
  padding: 18px;
  border: 2px solid var(--border);
  border-radius: var(--radius);
  background: #ffffff;
  box-shadow: var(--shadow);
  display: grid;
  gap: 14px;
  position: relative;
  overflow: hidden;
}

.photo-card::after {
  content: "";
  position: absolute;
  right: -24px;
  top: -24px;
  width: 120px;
  height: 120px;
  background: var(--accent);
  border: 2px solid var(--border);
  border-radius: 22px;
  transform: rotate(12deg);
  opacity: 0.55;
  pointer-events: none;
}

.photo-frame {
  border-radius: calc(var(--radius) - 6px);
  border: 2px solid var(--border);
  overflow: hidden;
  background: #f7f7f7;
}

.photo-img {
  width: 100%;
  height: clamp(260px, 44vw, 420px);
  object-fit: cover;
  object-position: center top;
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

.hero-subtitle {
  font-size: 18px;
  color: var(--ink-soft);
  margin-bottom: 28px;
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
  border: 2px solid var(--border);
  border-radius: var(--radius);
  background: var(--card);
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
  color: var(--ink-soft);
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
  border: 2px solid var(--border);
  font-family: "IBM Plex Mono", monospace;
  text-transform: uppercase;
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 0.14em;
  background: var(--accent);
  box-shadow: var(--shadow);
}

.lead {
  font-size: 18px;
  max-width: 720px;
}

.about-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: grid;
  gap: 12px;
  font-size: 17px;
  line-height: 1.4;
}

.about-list li {
  padding: 14px 16px;
  border-radius: var(--radius);
  border: 2px solid var(--border);
  background: #ffffff;
  box-shadow: var(--shadow);
  font-weight: 600;
  transition: transform var(--transition), box-shadow var(--transition);
}

.about-list li:hover {
  transform: translate(-2px, -2px);
  box-shadow: var(--shadow-soft);
}

.about-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 28px;
  align-items: start;
}

.quote-card {
  padding: 24px;
  border: 2px solid var(--border);
  border-radius: var(--radius);
  background: #ffffff;
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
  background: #ffffff;
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

.service-shelf {
  display: grid;
  grid-auto-flow: column;
  grid-auto-columns: minmax(320px, 1fr);
  gap: 22px;
  padding-block: 18px;
  padding-inline: 12px 24px;
  overflow-x: auto;
  overflow-y: visible;
  scroll-snap-type: x mandatory;
  scroll-padding-inline: 24px;
  -webkit-overflow-scrolling: touch;
  scrollbar-color: var(--accent) transparent;
}

.service-card {
  padding: 28px;
  border-radius: var(--radius);
  border: 2px solid var(--border);
  background: #ffffff;
  box-shadow: var(--shadow);
  display: grid;
  gap: 14px;
  min-height: 220px;
  scroll-snap-align: start;
  transition: transform var(--transition), box-shadow var(--transition);
}

.service-card:hover {
  transform: translate(-3px, -3px);
  box-shadow: var(--shadow-float);
}

.service-title {
  font-weight: 700;
  font-size: 20px;
  line-height: 1.2;
  text-shadow: var(--text-shadow);
}

.service-card span {
  color: var(--ink-soft);
  font-size: 16px;
  line-height: 1.5;
}

@media (min-width: 900px) {
  .service-shelf {
    grid-auto-columns: minmax(360px, 420px);
  }
}

@media (max-width: 600px) {
  .service-shelf {
    grid-auto-columns: 88vw;
    scroll-padding-inline: 18px;
  }
}

.service-shelf::-webkit-scrollbar {
  height: 8px;
}

.service-shelf::-webkit-scrollbar-thumb {
  background: var(--accent);
  border: 2px solid #ffffff;
}

.services-hybrid {
  display: grid;
  grid-template-columns: minmax(0, 0.8fr) minmax(0, 1.2fr);
  gap: 30px;
  align-items: start;
}

.services-sticky {
  position: sticky;
  top: 120px;
  display: grid;
  gap: 16px;
}

.services-rail {
  padding-block: 26px;
}

.services-lead {
  font-size: 16px;
  color: var(--ink-soft);
  max-width: 320px;
}

.services-progress {
  height: 6px;
  width: 100%;
  background: rgba(10, 10, 10, 0.1);
  border-radius: 999px;
  overflow: hidden;
  border: 1px solid var(--border);
}

.services-progress-bar {
  height: 100%;
  width: 0%;
  background: var(--accent);
  transition: width 120ms ease;
}

.services-hint {
  font-family: "IBM Plex Mono", monospace;
  font-size: 12px;
  text-transform: uppercase;
  letter-spacing: 0.18em;
}

.logo-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
  margin-top: 18px;
}

.logo-badge {
  width: clamp(58px, 6.6vw, 82px);
  height: clamp(58px, 6.6vw, 82px);
  border-radius: 50%;
  border: 2px solid var(--border);
  background: #ffffff;
  display: grid;
  place-items: center;
  overflow: hidden;
  transition: transform var(--transition), box-shadow var(--transition);
}

.logo-badge:hover {
  transform: translate(-2px, -2px);
  box-shadow: var(--shadow-soft);
}

.logo-img {
  width: 70%;
  height: 70%;
  object-fit: contain;
}

@media (max-width: 720px) {
  .logo-grid {
    gap: 10px;
  }

  .logo-badge {
    width: 62px;
    height: 62px;
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
  border: 2px solid var(--border);
  border-radius: var(--radius);
  padding: 28px;
  background: #ffffff;
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
  color: var(--ink-soft);
}

.contact-links {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

.chip {
  padding: 8px 14px;
  border-radius: 999px;
  border: 2px solid var(--border);
  font-family: "IBM Plex Mono", monospace;
  font-size: 12px;
  text-transform: uppercase;
}

footer {
  border-top: 2px solid var(--border);
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

.footer-links {
  display: flex;
  gap: 16px;
  flex-wrap: wrap;
}

@media (max-width: 960px) {
  .hero-grid {
    grid-template-columns: 1fr;
  }

  .about-grid {
    grid-template-columns: 1fr;
  }

  .section-head {
    flex-direction: column;
    align-items: flex-start;
  }

  .services-hybrid {
    grid-template-columns: 1fr;
  }

  .services-sticky {
    position: static;
  }
}

@media (max-width: 720px) {
  .header-row {
    flex-direction: column;
    align-items: flex-start;
  }

  .nav-links {
    flex-wrap: wrap;
  }

  .hero-main {
    padding: 28px;
  }

  .cta {
    width: 100%;
  }

  .photo-card {
    padding: 16px;
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
}

@media (prefers-reduced-motion: reduce) {
  .ticker-track,
  .reveal,
  .scroll-progress-bar,
  .services-progress-bar {
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
