# Simple Calculator with Unit Tests

Проект для лабораторной работы:
- есть простое приложение;
- есть unit-тесты;
- код готов к загрузке в git-репозиторий.

## Запуск приложения

```bash
python calculator.py
```

## Запуск тестов

```bash
python -m unittest discover -s tests -v
```

## Инициализация git и загрузка в репозиторий

```bash
git init
git add .
git commit -m "Initial commit: calculator app with unit tests"
git branch -M main
git remote add origin <URL_ВАШЕГО_РЕПОЗИТОРИЯ>
git push -u origin main
```
