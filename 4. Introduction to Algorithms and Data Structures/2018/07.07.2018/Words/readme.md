﻿# 6.3. Думи
Подадена ви е поредица от латински букви. Напишете програма, която намира броя на всички думи, несъдържащи две последователни еднакви букви, които могат да бъдат съставени чрез пренареждане на дадените букви. Генерираните думи трябва да съдържат всички подадени букви. Ако подадена дума отговаря на изискванията, тя трябва да бъде включена в броя.

### Вход
- Входните данни трябва да се прочетат от конзолата.
- На единствения ред с входни данни ще има само една дума, съдържаща всички букви, които трябва да използвате за съставяне на думите.
- Входните данни винаги ще са валидни и в описания формат. Не е необходимо да бъдат изрично проверявани.

### Изход
- Изходните данни трябва да бъдат отпечатани на конзолата.
- На единствения изведен ред напишете броя намерени думи.

## Ограничения
- Броят на подадените букви ще бъде межди 1 и 10 включително.
- Всички подадени букви ще бъдат малки латински букви ('a' – 'z')
- Допустимо време за работа на вашата програма: 0.35 секунди. Допустима памет: 32 MB.

| Вход       | Изход   | Коментари                                    |
| ---------- | ------- | -------------------------------------------- |
| xy         | 2       | Две възможни думи: "xy" и "yx"               |
| xxxy       | 0       | Невъзможно е да се състави дума с тези букви |
| aahhhaa    | 1       | Единствената възможна дума е "ahahaha"       |
| nopqrstuvw | 3628800 | Има 3628800 възможни думи                    |