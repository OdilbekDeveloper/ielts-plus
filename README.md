# IELTS PLUS 📝

IELTS mock tests in Telegram and on the web.
Students in Uzbekistan pay with Payme or Click. No foreign card needed.

⏸ Offline right now · 🔒 The code is private

## Features

| Feature | Details |
|---|---|
| ✍️ Writing test | Students submit essays, admins check them and send results |
| 🗣 Speaking test | Speaking tasks inside the bot |
| 💳 Balance + payments | Top up with Payme or Click, and the test price is deducted from the balance |
| 🎁 Referrals | Invite friends and get a bonus |
| 📊 Admin panel | Unchecked essays, candidate filters, stats, broadcast |
| 🌐 Languages | Users pick their language |
| 🔗 One backend | The bot and the website share the same API |

## How it works

```
Telegram bot ─┐
              ├→ Django + DRF API → PostgreSQL
Web app ──────┘         ↕
                   Payme / Click
```

## Stack

Python · pyTelegramBotAPI · Django · DRF · PostgreSQL · APScheduler · Payme · Click · Vercel
