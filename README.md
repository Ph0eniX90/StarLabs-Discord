#  StarLabs - Discord 


![Logo](https://i.postimg.cc/J7HndpLX/1.jpg)

## [SEE ENGLISH VERSION BELOW ](https://github.com/0xStarLabs/StarLabs-Discord#english-version)👇

## 🔗 Links
[![Telegram channel](https://img.shields.io/endpoint?url=https://runkit.io/damiankrawczyk/telegram-badge/branches/master?url=https://t.me/StarLabsTech)](https://t.me/StarLabsTech)
[![Telegram chat](https://img.shields.io/endpoint?url=https://runkit.io/damiankrawczyk/telegram-badge/branches/master?url=https://t.me/StarLabsChat)](https://t.me/StarLabsChat)

🔔 CHANNEL: https://t.me/StarLabsTech

💬 CHAT: https://t.me/StarLabsChat

💰 DONATION EVM ADDRESS: 0x620ea8b01607efdf3c74994391f86523acf6f9e1

📖 FULL TUTORIAL: https://teletype.in/@izanumi/star_labs_discord


## 🤖 | Функционал:

🟢 Вход на сервер 

🟢 Прожатие кнопок и реакций

🟢 Прохождений ботов защиты (Pandez, Sledgehammer, Captcha Bot...)

🟢 Отправка сообщений в чат

🟢 Смена имена, юзернейма, аватарки

🟢 Поддержка ретраев, прокси, пауз, потоков

🟢 Проверка токена на работоспособность

🟢 Выход из сервера

🟢 Получить все серверы в которые зашел токен

## 🚀 Installation
```
# для работы необходимо установить NodeJS!
# https://nodejs.org/en/download/current

git clone https://github.com/0xStarLabs/StarLabs-Discord.git

cd StarLabs-Discord

pip install -r requirements.txt

# Перед началом работы настройте необходимые модули в файлах config.ini и /data

python main.py
```

## ⚙️ Config

| Name | Description |
| --- | --- |
| max_invite_retries | Количество попыток входа на сервер |
| max_tasks_retries | Максимальное количество попыток при выполнении задания |
| pause_between_tasks | Пауза между каждым действием |
| pause_between_accounts | Пауза между аккаунтами |
| capmonster_api_key | Ключ от https://capmonster.cloud/Dashboard |
| 2captcha_api_key | Ключ от https://2captcha.com/. |
| hcoptcha_api_key | Ключ от https://hcoptcha.online/ |
| capsolver_api_key | Ключ от https://www.capsolver.com/ |
| anticaptcha_api_key | Ключ от https://anti-captcha.com/ |
| captcha_service_to_use | какой сервис для прохождения капчи использовать. (capmonster, hcoptcha, capsolver, anticaptcha) |
| mobile_proxy | Мобильные прокси |
| change_ip_pause | Пауза после смены айпи мобильных прокси |
| endless_loop | Отправлять сообщения в чат бесконечно |
| random_message | Брать сообщения для отправки в чат рандомно или нет | 
| pause_between_messages | Пауза между сообщения при отправке в чат |


## 🗂️ Data

Данные в папке data:

| Name | Description |
| --- | --- |
| discord_tokens.txt | Содержит дискорд токены |
| failed_tokens.txt | Содержит аккаунты которые не были выполнены |
| new_names.txt | Содержит имена для функции смены имен |
| new_passwords.txt | Содержит новые пароли для функции смены паролей |
| new_usernames.txt | Содержит новые юзернеймы для функции смены юзернеймов |
| passwords.txt | Содержит текущие пароли аккаунтов |
| proxies.txt | Содержит прокси в формате user:pass@ip:port |
| profile_pictures | Папка содержит картинки для смены в профилях |
| locked_tokens.txt | Файл содержит токены, которые заблокированы или ограничены | 
| messages_to_send.txt | Файл содержит сообщения, которые будет отправлять бот в чат (случайно) |
| ip_change_links.txt | Содержит ссылки для смены айпи мобильных прокси |


## Дисклеймер
Автоматизация учетных записей пользователей Discord, также известных как самостоятельные боты, является нарушением Условий обслуживания и правил сообщества Discord и приведет к закрытию вашей учетной записи (аккаунтов). Рекомендуется осмотрительность. Я не буду нести ответственность за ваши действия. Прочтите об Условиях обслуживания Discord и Правилах сообщества.

Это программное обеспечение было написано как доказательство концепции того, что учетные записи Discord могут быть автоматизированы и могут выполнять действия, выходящие за рамки обычных пользователей Discord, чтобы Discord мог вносить изменения. Авторы  освобождаются от любой ответственности, которую может повлечь за собой ваше использование.

## ENGLISH VERSION:

## 🤖 | Features :

🟢 Invite joiner

🟢 Pressing buttons and reactions

🟢 Bypass of protection bots (Pandez, Sledgehammer, Captcha Bot...)

🟢 Sending messages to chat

🟢 Change names, usernames, avatars

🟢 Retries, Proxies, Pauses, Threads

🟢 Checking the token for operability

🟢 Log out of the server

🟢 Get all servers to which the token is logged in

## 🚀 Installation
```
# You need to install NodeJS!
# https://nodejs.org/en/download/current

git clone https://github.com/0xStarLabs/StarLabs-Discord.git

cd StarLabs-Discord

pip install -r requirements.txt

# Before starting the tool make sure to configure it in config.ini and add information to data folder

python main.py
```

## ⚙️ Config

| Name | Description |
| --- | --- |
| max_invite_retries | Number of attempts to log in to the server |
| max_tasks_retries | Maximum number of attempts to complete a task |
| pause_between_tasks | Pause between each action |
| pause_between_accounts | Pause between accounts |
| capmonster_api_key | Key to https://capmonster.cloud |
| 2captcha_api_key | Key to https://2captcha.com |
| hcoptcha_api_key | Key to https://hcoptcha.online |
| capsolver_api_key | Key from https://www.capsolver.com |
| anticaptcha_api_key | Key for https://anti-captcha.com |
| captcha_service_to_use | Which service to use to pass captcha. (capmonster, hcoptcha, capsolver, anticaptcha) |
| mobile_proxy | Mobile proxies yes/no |
| change_ip_pause | Pause after changing the ip of mobile proxies |
| endless_loop | Send messages to chat endlessly |
| random_message | Take messages to send to chat randomly or not | 
| pause_between_messages | Pause between messages to be sent to chat |


## 🗂️ Data

The data is in the data folder:

| Name | Description |
| --- | --- |
| discord_tokens.txt | DISCORD account tokens |
| failed_tokens.txt | Failed tokens |
| new_names.txt | Contains names for the name change function |
| new_passwords.txt | Contains new passwords for the password change feature |
| new_usernames.txt | Contains new usernames for the username change function |
| passwords.txt | Contains current account passwords |
| proxies.txt | Contains a proxy in the format user:pass@ip:port |
| profile_pictures | The folder contains pictures to change in profiles |
| locked_tokens.txt | File contains tokens that are locked or restricted | 
| messages_to_send.txt | File contains messages that the bot will send to chat (randomly) |
| ip_change_links.txt | Contains links to change mobile proxy IPs |

## Disclaimer

The automation of User Discord accounts also known as self-bots is a violation of Discord Terms of Service & Community guidelines and will result in your account(s) being terminated. Discretion is adviced. I will not be responsible for your actions. Read about Discord Terms Of service and Community Guidelines

Discord StarLabs was written as a proof of concept that Discord accounts can be automated and can perform actions beyond the scope of regular Discord Users like sending Embeds so that Discord can make changes. The Discord StarLabs authors are released of any liabilities which your usage may entail.


