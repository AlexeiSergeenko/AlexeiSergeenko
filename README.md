<div align="center">

# Привет, я Алексей 👋

### Senior AQA · Python · Автоматизация тестирования

*Не просто писать автотесты, а делать качество предсказуемым через стратегию тестирования,   стратегию автоматизации и понятный релизный процесс.*

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)](https://pytest.org/)
[![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)](https://www.selenium.dev/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Allure](https://img.shields.io/badge/Allure_Report-FF6C37?style=for-the-badge&logo=allure&logoColor=white)](https://docs.qameta.io/allure-report/)

[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Postgres](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

</div>

---

## Обо мне

Инженер по автоматизации тестирования с упором на **Python** и **практику уровня Senior**: от стратегии качества и пирамиды тестов до интеграций в **CI/CD** и работы с распределёнными системами.

Строю и развиваю автотесты там, где важны и **стабильность UI**, и **контракты API**, и понимание того, как сервисы ведут себя под нагрузкой и при сбоях зависимостей.

---

## Опыт и зона ответственности

Работаю в **продуктовой компании** над платформой в модели **White Label**: партнёры продают решение своим клиентам под своим брендом.

В зоне команды **Multichannels** (мультиканальные коммуникации) отвечаю за критичный контур взаимодействия **конечного пользователя и агента**:

- голос, **SMS**, телефонные номера, соцсети и другие каналы;
- баланс между **UI**- и **API**-автоматизацией: тяжёлую бизнес-логику по возможности опускаю ниже по пирамиде;
- взаимодействие с **микросервисной архитектурой**, внутренними сервисами на **FastAPI**, понимание **async**, интеграций, идемпотентности, устойчивости к сбоям.

В автоматизации опираюсь на **осмысленную стратегию тестирования** (риски, критичность для бизнеса), **контрактное** и **интеграционное** тестирование, осознанное использование **Page Object**, работу с **Docker** и при необходимости — с **БД** для проверки побочных эффектов.

---

## Стек и инструменты

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,pytest,selenium,fastapi,docker,postgres,git,github,vscode,linux&perline=10" alt="Python, Pytest, Selenium, FastAPI, Docker, PostgreSQL, Git, GitHub, VS Code, Linux" />
  </a>
</p>

| Направление | Примеры |
| :--- | :--- |
| **Язык и тесты** | Python, pytest, фикстуры, параметризация, async-тесты (`pytest-asyncio`, `httpx`) |
| **UI** | Selenium WebDriver, Page Object, Allure (скриншоты и вложения при падениях) |
| **API** | REST, контракты, интеграционные сценарии |
| **Инфра и качество** | Git, CI/CD, Docker, логи и трассировки при разборе инцидентов |

---

## Этот репозиторий

Здесь — **учебно-практический** материал: примеры **UI**-сценариев на **Selenium**, организация через **pytest**, отчёты **Allure**, вспомогательные задачи и `conftest` с вложениями при ошибках.

<details>
<summary><strong>Быстрый старт (локально)</strong></summary>

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

pip install -U pip pytest selenium allure-pytest
```

```bash
pytest selenium_tests/ -v
pytest --alluredir=allure-results
allure serve allure-results
```

```
├── selenium_tests/     # UI-сценарии
├── tasks/              # примеры, conftest с Allure
├── allure-results/     # генерируется при прогоне
└── README.md
```

</details>

---

## Контакты

Замени плейсхолдеры на свои ссылки:

[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/YOUR_TELEGRAM)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR_PROFILE/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)

<div align="center">

[![GitHub followers](https://img.shields.io/github/followers/YOUR_USERNAME?label=GitHub&style=social)](https://github.com/YOUR_USERNAME)

*Открыт к профессиональному общению и обмену опытом по AQA и Python*

</div>
