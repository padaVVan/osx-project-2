# Генератор паролей

## Проблема
По работе мне очень часто приходится регистрировать аккаунты на различных сервисах и сайтах. Как правило логины есть, а вот пароли выдумывать не хочется.

## Аудитория
Данная программа поможет всем кому нужно быстро сгенерировать уникальный устойчивый к подбору пароль.

## Пример
Допустим, нужно мне зарегистрировать 5 почтовых ящиков для новых сотрудников компании, тут то я и беру приложение и генерирую пароли, все легко и просто.

## Описание
Приложение генерирует пароли по критериям - длина, наборы символов (цифры, нижний и верхний регистр)
![окно приложения](http://d3j5vwomefv46c.cloudfront.net/photos/large/698564513.png?key=321391&Expires=1354903156&Key-Pair-Id=APKAIYVGSUJFNRFZBBTA&Signature=oioZ320jHXithPdeKfO2jJfrznYcWVG0FT6EDkIWKaop2mNT-UFQrzT0NHYj-zuKSW-Q2fOb0U552d3OHvQ~0~PGWKh6-IyUGcrkyyh7bfvMN-plEk4-shzTYs3Na~PdD0dYVX7Ang44m-X25GV0nFt~RHVPJ4GNkl5sSdcfy70_)

В окне приложения можно выбрать длину пароля, для этого можно исполльзовать элемент Stepper.
Включая Check Box можно добавлять наборы символов в пароль. _(По умолчанию включены)_

При нажатии кнопки "Генерировать" в поле появится новый сгенерированный пароль.
При нажатии на кнопку "✓" пароль скопируется в буфер.
