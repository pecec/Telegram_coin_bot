# Telegram_coin_bot
![Бот для добывания криптовалюты, выполняя задания ботов dogeclick
](cfce13b13a2a.png)

Бот для добывания криптовалюты, выполняя задания ботов dogeclick

План действий
1. Вносим в скрит SozdanieBD.py данные Telegram аккаунта и запускаем его. Тем самым мы создаем базу аккаунтов и добавляем в нее запись с ботом. Повторяем этот пункт столько раз, сколько аккаунтов у нас есть.
2. Запускаем скрипт Sozdanie_Clienta.py тем самым генерируем фаил-клиент для всех наших Telegram ботов
3. Для старта главной программы запускаем скрипт go.py они будут работать до тех пор пока мы их не остановим. Если в процессе возникнет ошибка цикл перезапустится и все равно продолжит работу начиная с первого бота
4. Если мы хотим узнать сколько заработал каждый бот. Останавливаем пункт 3 и запускаем скрипт Balans.py и ждем завершения, скрипт выведет сколько заработал каждый бот и итоговую ссумму
