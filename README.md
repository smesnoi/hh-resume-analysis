# Проект 1. Анализ резюме HeadHunter

## Описание
Подготовка данных для модели предсказания заработной платы соискателей.

## Данные

⚠️ **Файлы данных** слишком большие для GitHub (450 МБ). Скачайте их по ссылкам:

- [dst-3.0_16_1_hh_database.csv (450 МБ)](https://drive.google.com/file/d/1lY0V7rSym76Vw0x4by_J55Kur0PBAasO/view?usp=sharing)
- [ExchangeRates.csv (курсы валют)](https://drive.google.com/file/d/14hG1HMedz6Y4XGmukdieTJjpsDHg5r8c/view?usp=sharing)

**После скачивания** положите файлы в **корень** проекта.

## Структура проекта

## Интерактивные графики (Plotly)

В папке `plotly_charts/` — интерактивный HTML-график:

- [`salary_by_city.html`](salary_by_city.html) — ЗП по городам.

**Как открыть:** скачайте HTML и откройте в браузере.

## Этапы работы

1. **Базовый анализ** — 44 744 резюме, 12 признаков.
2. **Преобразование** — 10 новых признаков.
3. **EDA** — 10 графиков.
4. **Очистка** — 43 302 строки, 22 признака.

## Итог
Готовый датасет для ML-модели.

## Запуск
```bash
pip install -r requirements.txt
jupyter notebook