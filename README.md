# 🎓 School Schedule Telegram Bot

> Телеграм-бот для швидкого доступу до шкільного розкладу, дзвоників та зворотного зв’язку з адміністрацією.

![Python](https://img.shields.io/badge/python-3.10+-blue.svg)
![Telegram Bot](https://img.shields.io/badge/telegram%20bot-active-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 📲 Можливості бота

- 📅 Перегляд розкладу по класам та підкласам (наприклад, `6-А`, `7-Б`)
- 🔔 Перевірка дзвоників у школі
- 🛠 Надсилання скарг/повідомлень напряму адміністратору
- 🧭 Зручне меню з кнопками

---

## 🚀 Запуск бота

### 1. Клонування репозиторію

```bash
git clone https://github.com/your-username/school-schedule-telegram-bot.git
cd school-schedule-telegram-bot
```

### 2. Встановлення залежностей

```bash
pip install python-telegram-bot==13.15
```

### 3. Налаштування структури

```bash
.
├── bot.py
├── rozklad/
│   ├── 6-А_class.txt
│   ├── 7-Б_class.txt
│   └── ...
├── dzvonki/
│   └── vsa_sc.txt
```

> ⚠️ У папці `rozklad/` мають бути текстові файли з розкладом для кожного класу (назва у форматі `Клас-Підклас_class.txt`).
> Файл з дзвониками: `dzvonki/vsa_sc.txt`

### 4. Заміни наступні дані в `bot.py`

- `TOKEN = 'your_bot_token'` — твій Telegram API токен
- `ADMIN_CHAT_ID = 'your_chat_id'` — чат ID адміністратора (можна дізнатись через [@userinfobot](https://t.me/userinfobot))

### 5. Запуск

```bash
python bot.py
```

---

## 🧠 Технології

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![python-telegram-bot](https://img.shields.io/badge/python--telegram--bot-v13.15-blue?logo=telegram&logoColor=white)

---

## 📌 Рекомендації

* Не заливайте в публічний доступ свій `bot token` та `chat ID`.
* Для розгортання на сервері — використовуйте `nohup`, `screen` або `Docker`.
* Додайте `.env` файл і зберігайте секрети там для безпечного зберігання.

---

## 💡 Ідеї для майбутнього

* 🔐 Авторизація для адміністратора
* 🗓 Інтеграція з Google Calendar або Excel API
* 📨 Автоматичні сповіщення про зміни в розкладі

---

## 📄 Ліцензія

Цей проєкт розповсюджується за ліцензією [MIT](https://github.com/dnnode/telegram-school-bot/blob/main/!%20LICENSE/LICENSE.md).

---

*Зроблено з ❤️ для учнів та шкіл*

