# 🦷 Дент-Лайф — стоматологічна клініка

**Сайт стоматологічної клініки «Дент-Лайф»** — сучасний, легкий і SEO-оптимізований сайт, створений на **Vue 3** з використанням новітніх технологій фронтенду.  
Сайт призначений для презентації послуг, цін, відгуків та контактної інформації клініки.

🌐 **Сторінка стоматології «Дент-Лайф»:** [https://dent-life.kiev.ua](https://dent-life.kiev.ua)

**Сторінки послуг що надаються клінікою:**

🦷 **Гігієна ротової порожнини** [https://dent-life.kiev.ua/service/oral-hygiene](https://dent-life.kiev.ua/service/oral-hygiene)

🦷 **Лікування зубів** [https://dent-life.kiev.ua/service/treatment](https://dent-life.kiev.ua/service/treatment)

🦷 **Протезування зубів** [https://dent-life.kiev.ua/service/prosthetics](https://dent-life.kiev.ua/service/prosthetics)

🦷 **Імплантація зубів** [https://dent-life.kiev.ua/service/implantation](https://dent-life.kiev.ua/service/implantation)

🦷 **Рентген діагностика** [https://dent-life.kiev.ua/service/x-ray-diagnostics](https://dent-life.kiev.ua/service/x-ray-diagnostics)

🦷 **Дитяча стоматологія** [https://dent-life.kiev.ua/service/pediatric-dentistry](https://dent-life.kiev.ua/service/pediatric-dentistry)

---

## ✨ Ключові особливості

- 🧭 **Роутинг (Vue Router)** з окремими SEO-сторінками
- 🦷 **6 сторінок напрямів лікування / послуг**
- 📰 **SEO-friendly статті** з правильною HTML-ієрархією
- 🌍 **Мультимовність**:
  - 🇺🇦 Українська — за замовчуванням
  - 🇬🇧 Англійська
  - 🇷🇺 Російська
- 🔗 Повна інтеграція **schema.org (JSON-LD)**:
  - `MedicalBusiness / LocalBusiness`
  - `Service`
  - `BreadcrumbList`
  - `FAQPage`
- ✅ Схеми пройшли валідацію:
  - https://search.google.com/test/rich-results
  - https://validator.schema.org/
- 📍 **Google Maps API**
- 💬 **Google Reviews**
- 💰 Ціни з **Google Таблиці**
- 💾 Кешування цін у `localStorage`
- ⚡ Оптимізація запитів (`useThrottleFn`)
- 🦴 Skeleton loaders та empty states
- 📱 Повністю адаптивний дизайн
- 🔍 Розширене SEO:
  - meta / og / twitter теги
  - canonical
  - hreflang
  - JSON-LD через `@unhead/vue`

---

## 🧩 Архітектура

Проєкт побудований за підходом **SSG (Static Site Generation)**:

- 🔧 Збірка виконується за допомогою **vite-ssg**
- 📄 HTML-сторінки генеруються на етапі білду
- 🤖 Пошукові системи отримують готовий контент без JS-рендерингу
- ⚡ Максимальна швидкість першого завантаження

---

## 🛠️ Технологічний стек

| Область | Технології |
|------|------------|
| Framework | [Vue 3](https://vuejs.org/) |
| SSG | [vite-ssg](https://github.com/antfu/vite-ssg) |
| Build tool | [Vite](https://vitejs.dev/) |
| Routing | [Vue Router](https://router.vuejs.org/) |
| State | [Pinia](https://pinia.vuejs.org/) |
| UI | [Vuetify 3](https://vuetifyjs.com/) |
| SEO / Head | [@unhead/vue](https://unhead.unjs.io/) |
| Sliders | [Swiper](https://swiperjs.com/) |
| Maps | [vue3-google-map](https://github.com/Dafrok/vue-google-map) |
| Language | TypeScript |
| Backend utils | Node.js |

---

## 🌍 Локалізація та SEO

Для кожної мови налаштовано:

- окремі meta-дані
- локалізовані тексти
- інтерактивні елементи / меню

Це забезпечує правильну індексацію кожної мовної версії.

---

## ⚙️ CI / CD та деплой

Проєкт автоматично деплоїться на **GitHub Pages**:

- 🔄 **GitHub Actions**
- 📦 Збірка через `vite-ssg`
- 🚀 Публікація у `gh-pages` гілку
- ❌ Без ручного втручання

> Кожен push у відповідну гілку запускає білд та деплой сайту.
