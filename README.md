# Автотесты на Python + Selenium

## О проекте
Автотесты для интернет-магазина (дипломный проект, Академия ТОП).

## Что тестируется
- Навигация по меню
- Добавление товара в корзину
- Изменение количества товара
- Удаление товара из корзины
- Валидация формы регистрации

## Технологии
- Python 3.x
- pytest
- Selenium WebDriver
- Allure (отчёты)

## Запуск тестов

1. Установи зависимости:
```bash
pip install pytest selenium allure-pytest

2.Запусти тесты:

bash
pytest test_br_004_allure_final.py --alluredir=allure-results

3.Сгенерируй отчёт Allure:

bash
allure generate ./allure-results -o ./allure-report --clean
allure serve ./allure-results

Автор
Скрипай Татьяна, группа QA416, Академия ТОП, 2026
