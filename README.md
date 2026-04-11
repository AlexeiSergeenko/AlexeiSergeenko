<div align="center">

# Привет, я Алексей 👋

### Senior AQA · Lead QA Engineer · 6 лет опыт в автоматизации тестирования

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

На проектах я закрывал `API`, `web` и `mobile` автоматизацию, но ключевой фокус у меня обычно был на backend, интеграциях и критичных для бизнеса сценариях. Если говорить про мобильное направление, умею работать и с `Appium`, и с реальными устройствами, и с `device farm`, выстраивать покрытие как для `UI`-сценариев, так и для `API` и интеграционного слоя. Для меня мобильное качество - это не только интерфейс, но и вся цепочка: клиент, backend, данные, очереди, логи и устойчивость релиза.

---

## Подход и стратегия тестирования продукта

По процессу я всегда иду от риска для бизнеса. В первую очередь покрываю то, где максимальная цена ошибки: платежи, пополнения, заказы, отмены, расчеты, все сценарии, связанные с деньгами и ключевыми пользовательскими потоками. Дальше уже расширяю покрытие на `P1` и `P2`. В автоматизации обычно выстраиваю ступенчатый подход: короткий дымовой прогон на самые критичные сценарии, затем более широкий регресс и ночные полные прогоны. Все это встраиваю в `GitLab CI`, `Jenkins` или другой контур поставки, с отчетностью в `Allure`, чтобы и команда разработки, и QA, и менеджмент видели понятную картину по качеству и могли принимать решения на данных.

Отдельно для меня важен `shift-left` подход. Я стараюсь заходить в задачи как можно раньше: обсуждать их с аналитиками и разработкой на этапе требований, помогать с критериями приемки, приоритизацией и пониманием того, что действительно важно покрыть в текущем спринте, а что можно осознанно отложить. Это позволяет не догонять качество в конце, а строить его с самого начала.

---

## Стек и инструменты

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,requests,selenium,fastapi,docker,postgres,git,github,vscode,linux&perline=10" alt="Python, Pytest, Selenium, FastAPI, Docker, PostgreSQL, Git, GitHub, VS Code, Linux" />
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

[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/@Alexius808)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alexeisergeenko/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:spam.vending430@passinbox.com)

<div align="center">

[![GitHub followers](https://img.shields.io/github/followers/YOUR_USERNAME?label=GitHub&style=social)](https://github.com/YOUR_USERNAME)

*Открыт к профессиональному общению и обмену опытом по AQA и Python*

</div>
