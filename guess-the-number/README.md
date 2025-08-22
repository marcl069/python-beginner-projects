# 🎯 Угадай число / Guess the Number

Простая консольная игра на Python, в которой игрок должен угадать случайно загаданное число от 1 до 100.  
A simple console game in Python where the player must guess a randomly generated number from 1 to 100.

![Python](https://img.shields.io/badge/Python-3.6%2B-blue)  
![Colorama](https://img.shields.io/badge/Dependency-colorama-green)

---

## 📋 Описание / Description

Игрок выбирает один из трёх уровней сложности:  
The player selects one of three difficulty levels:

- **1 — Простой** (10 попыток) / **1 — Easy** (10 attempts)  
- **2 — Средний** (5 попыток) / **2 — Medium** (5 attempts)  
- **3 — Сложный** (3 попытки) / **3 — Hard** (3 attempts)  

После выбора уровня игрок пытается угадать число. Игра даёт подсказки: «больше» или «меньше».  
After selecting the level, the player tries to guess the number. The game gives hints: "higher" or "lower".

Цветной вывод помогает понять статус:  
Colored output helps indicate the game state:
- 🟩 Зелёный — победа / Green — victory  
- 🔴 Красный — поражение / Red — defeat  
- 🟨 Жёлтый — подсказка / Yellow — hint  

---

## 🛠 Требования / Requirements

- Python 3.6 или выше / Python 3.6 or higher  
- Библиотека `colorama` / `colorama` library (for colored console output)

Установите `colorama`, если она ещё не установлена:  
Install `colorama` if not already installed:

```bash
pip install colorama
