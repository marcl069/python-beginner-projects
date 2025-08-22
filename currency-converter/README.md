# Конвертер валют / Currency Converter

Простая консольная программа на Python для конвертации валют с использованием открытого API [Frankfurter](https://api.frankfurter.app).

A simple Python console application for currency conversion using the free [Frankfurter API](https://api.frankfurter.app).

---

## 🌐 Описание / Description

Этот проект позволяет пользователю ввести сумму в одной валюте и конвертировать её в другую. Программа использует актуальные курсы обмена с API `frankfurter.app`. Поддерживается выбор из нескольких популярных валют или ввод произвольного кода валюты по стандарту ISO 4217.

This project allows the user to enter an amount in one currency and convert it to another. The program uses up-to-date exchange rates from the `frankfurter.app` API. You can choose from several popular currencies or enter a custom currency code according to the ISO 4217 standard.

---

## 🛠️ Функции / Features

- Ввод суммы для конвертации  
  **Amount input for conversion**
- Выбор базовой и целевой валюты из списка или вручную  
  **Select base and target currency from a list or enter manually**
- Поддержка популярных валют: USD, EUR, JPY, GBP, CNY  
  **Supports popular currencies: USD, EUR, JPY, GBP, CNY**
- Использование внешнего API для получения актуальных курсов  
  **Uses external API to get real-time exchange rates**
- Обработка ошибок ввода и ответов API  
  **Input and API response error handling**

---

## 📦 Требования / Requirements

- Python 3.6 или выше
- Библиотека `requests` (устанавливается через pip)

```bash
pip install requests
