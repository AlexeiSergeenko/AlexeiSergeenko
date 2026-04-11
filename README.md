<div align="center">

# UI-автотесты на Python

**Selenium · Pytest · Allure**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)](https://pytest.org/)
[![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)](https://www.selenium.dev/)
[![Allure](https://img.shields.io/badge/Allure_Report-FF6C37?style=for-the-badge&logo=allure&logoColor=white)](https://docs.qameta.io/allure/)

[![License](https://img.shields.io/badge/License-MIT-97ca00?style=flat-square)](LICENSE)
[![Code style](https://img.shields.io/badge/code%20style-black-000000.svg?style=flat-square)](https://github.com/psf/black)

</div>

---

## О проекте

Репозиторий с примерами **UI-автотестов**: сценарии на **Selenium WebDriver**, организация через **pytest**, отчёты и вложения при падениях — **Allure**.

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,pytest,selenium,git,github,vscode&perline=8" alt="Стек: Python, Pytest, Selenium, Git, GitHub, VS Code" />
  </a>
</p>

---

## Возможности

| | |
| :--- | :--- |
| **Фреймворк** | Pytest + фикстуры под браузеры |
| **Отчётность** | Allure: скриншоты и HTML страницы при падении теста |
| **Браузеры** | Примеры под Chrome / Firefox (см. тесты и фикстуры) |

---

## Требования

- **Python** 3.10+ (рекомендуется 3.11)
- Установленный **браузер** и совместимый **WebDriver** / **Selenium Manager** (в зависимости от версии Selenium)

---

## Быстрый старт

```bash
# клонирование
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

# виртуальное окружение
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# зависимости (пример — подставьте свой requirements.txt или pyproject)
pip install -U pip pytest selenium allure-pytest
```

### Запуск тестов

```bash
# все тесты
pytest

# конкретная папка
pytest selenium_tests/ -v

# с результатами для Allure
pytest --alluredir=allure-results
```

### Отчёт Allure

```bash
allure serve allure-results
```

---

## Структура (ориентир)

```
├── selenium_tests/     # UI-сценарии
├── tasks/              # примеры, conftest с вложениями Allure
├── allure-results/     # сырые результаты (генерируется)
└── README.md
```

---

## Полезные ссылки

[![Документация Selenium](https://img.shields.io/badge/docs-Selenium-43B02A?style=flat-square&logo=selenium)](https://www.selenium.dev/documentation/)
[![Pytest](https://img.shields.io/badge/docs-Pytest-0A9EDC?style=flat-square&logo=pytest)](https://docs.pytest.org/)
[![Allure](https://img.shields.io/badge/docs-Allure-FF6C37?style=flat-square)](https://docs.qameta.io/allure-report/)

---

<div align="center">

**Сделано с** · **AQA · Python · Автотесты**

[![GitHub followers](https://img.shields.io/github/followers/YOUR_USERNAME?label=Follow&style=social)](https://github.com/YOUR_USERNAME)

</div>
