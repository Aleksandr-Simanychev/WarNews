# WarNews
## English version
### Backstory
About 03:00 UTC on 24. February Russian President Vladimir Putin announced in a prerecorded television broadcast that he had ordered "a special military operation" in eastern Ukraine; minutes later, missile strikes occurred at dozens of cities across the country, including Ukraine's capital Kyiv. However, the first steps of it were made on 21. February, when Vladimir Putin announced that Russia recognizes the independence of two pro-Russian breakaway regions in eastern Ukraine (DPR and LPR).  
### Description
My focus was the analysis of publications about the war on Ukrainian and Russian Telegram channels. Using Telegram Analytics (https://tgstat.com) I got the 100 biggest news-orienteered telegram channels from Russia and Ukraine in the Russian language. However some of them are private, that is why we have only 84 Russian channels and 89 Ukrainian. Then I built up Telegram Grabber based on this article (https://proglib.io/p/pishem-prostoy-grabber-dlya-telegram-chatov-na-python-2019-11-06). I wanted to get posts, that were published after 2022-02-21, so I took the last 2000 posts and got rid of all that was posted earlier.
### TelPool.csv
It's the file of the most popular news-orienteered telegram channels in format **russian_channels; ukrainian_channels**.
### TelegramGrabber.ipynb
It's the code, that takes a CSV file of channels as input and gives a stack of JSON files with posts of these channels as output.
### RU_JSON/UA_JSON
It's a folder with JSON files with all posts of these channels since 2022-02-21
### RuChange/UaChange
It's the code, that delete all post, that were published before 2022-02-21
### config.ini
There is no config file posted due to confidential information.
## Русская версия
### Предыстория
Около 03:00 UTC 24 февраля президент России Владимир Путин объявил в предварительно записанной телепередаче, что отдал приказ о начале «военной операции» на востоке Украины; Через несколько минут были нанесены ракетные удары по десяткам городов Украины, в том числе по Киеву. Однако первые шаги были сделаны уже 21 февраля, когда Владимир Путин объявил, что Россия признает независимость двух пророссийских сепаратистских регионов на востоке Украины (ДНР и ЛНР).
### Описание
Целью моей работы был анализ постов о «военной операции», опубликованных в украинских и росскийских телеграм каналах. С помощью [Telegram Analytics] (https://tgstat.com) я спарсил 100 крупнейших новостных телеграм каналов России и Украины на русском языке. Однако некоторые из них оказались закрытыми, поэтому по итогу мы получили 84 российских канала и 89 украинских. Затем я собрал Telegram Grabber на основе [данной статьи] (https://proglib.io/p/pishem-prostoy-grabber-dlya-telegram-chatov-na-python-2019-11-06). Я хотел получить только те посты, которые были опубликованы после 21 февраля 2022 года, поэтому было решено взять последние 2000 публикаций каждого канала и избавиться от тех постов, что были опубликованы ранее.
### TelPool.csv
Таблица, содержащая в себе топ самых популярных новостных телеграм каналов в формате **русские_каналы; украинские_каналы**.
### TelegramGrabber.ipynb
Код, принимающий на вход CSV таблицу с телеграм каналами и возвращающий серию JSON файлов с постами в этих каналах.
### RU_JSON/UA_JSON
Папки с JSON файлами со всеми постами опубликованными в новостных каналах, начиная с 2022-02-21.
### RuChange/UaChange
Код, удаляющий все посты, которые были опубликованы раньше 2022-02-21.
### config.ini
Из соображений конфиденциальности данный файл не будет опубликован
