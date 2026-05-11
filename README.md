# Using Delta Chat under Russian internet whitelists
# Используем Delta Chat в условиях российских белых списков интернета

---

<details open>
<summary><strong>🇷🇺 Читать на русском</strong></summary>

## Зачем это нужно

Delta Chat — мессенджер, который работает поверх обычной электронной почты. Никакого отдельного сервера, никаких заблокированных доменов — сообщения летят как письма. Яндекс.Почта при этом работает без VPN и находится в российском белом списке. Это значит, что общаться можно даже там, где всё остальное заблокировано.

---

## Шаг 1 — Скачать Delta Chat

| Платформа | Ссылка |
|-----------|--------|
| Android | [v2.49.0 → GitHub Releases](https://github.com/deltachat/deltachat-android/releases/tag/v2.49.0) |
| Windows / macOS / Linux | [v2.49.1 → GitHub Releases](https://github.com/deltachat/deltachat-desktop/releases/tag/v2.49.1) |
| iOS (App Store) | [App Store](https://apps.apple.com/us/app/delta-chat/id1459523234) |

---

## Шаг 2 — Зарегистрировать Яндекс.Почту

Идём на [mail.yandex.ru](https://mail.yandex.ru) и создаём новый аккаунт, если его ещё нет.

---

## Шаг 3 — Настройка Яндекс.Почты

### 3.1 Включить IMAP

1. Заходим в **Настройки** → **Почтовые программы**
2. Ставим галочку: **С сервера `imap.yandex.ru` по протоколу IMAP**
3. Сохраняем

### 3.2 Создать пароль приложения

1. Заходим в **Настройки** → **Безопасность**
2. Нажимаем синюю кнопку **[Пароли приложений](https://passport.yandex.ru/security/app-passwords)**
3. Создаём новый пароль для почты
4. **Сохраните пароль** — он понадобится при входе в Delta Chat

### 3.3 Настроить правило обработки писем

Это нужно для того, чтобы письма от друзей не попадали в спам.

1. Переходим в **Правила обработки писем** → создаём новое правило
2. Настраиваем так:
   - **От кого:** вписываете email вашего друга
   - **Применять:** ко всем письмам, включая спам, с вложениями и без
   - **Действие:** положить в папку «Входящие»
   - **Дополнительно:** пометить как прочитанное
   - **Применить ко всем существующим письмам:** ✅
3. Сохраняем

> В дальнейшем можно редактировать это правило и добавлять туда почты других друзей. Ваши друзья должны сделать зеркальное правило и вписать туда ваш адрес.

---

## Шаг 4 — Подключить аккаунт в Delta Chat

1. Открываем Delta Chat
2. Нажимаем **Добавить аккаунт** → **Use other server** → **Use classic email as relay**
3. Вводим вашу Яндекс.Почту и пароль приложения из шага 3.2
4. Готово 🎉

---

## Что дальше

**Добавить еще одно устройство к аккаунту – откройте настройки -> добавить второе устройство -> далее выстветится qr-code, который надо будет отсканировать на втором устройстве в приложении DeltaChat
**Поделиться профилем** — нажмите на иконку QR-кода сверху и дайте другу отсканировать.

**Автоудаление сообщений** — зайдите в **Настройки чатов** и установите таймер удаления сообщений с сервера и с устройства.

**Звонки и каналы** — зайдите в **Настройки** → **Дополнительно** и включите нужные функции.

---

## Что должны сделать ваши друзья

1. Установить Delta Chat (шаг 1)
2. Завести Яндекс.Почту (шаг 2)
3. Включить IMAP и создать пароль приложения (шаг 3.1 и 3.2)
4. Создать правило обработки входящих писем и **добавить туда ваш email** (шаг 3.3)
5. Войти в Delta Chat (шаг 4)

</details>

---

<details>
<summary><strong>🇬🇧 Read in English</strong></summary>

## Why this works

Delta Chat is a messenger that runs on top of regular email. No separate servers, no blocked domains — messages travel as plain emails. Yandex Mail is whitelisted in Russia and works without a VPN, which means you can chat even where everything else is blocked.

---

## Step 1 — Download Delta Chat

| Platform | Link |
|----------|------|
| Android | [v2.49.0 → GitHub Releases](https://github.com/deltachat/deltachat-android/releases/tag/v2.49.0) |
| Windows / macOS / Linux | [v2.49.1 → GitHub Releases](https://github.com/deltachat/deltachat-desktop/releases/tag/v2.49.1) |
| iOS (App Store) | [App Store](https://apps.apple.com/us/app/delta-chat/id1459523234) |

---

## Step 2 — Register a Yandex Mail account

Go to [mail.yandex.ru](https://mail.yandex.ru) and create an account if you don't have one yet.

---

## Step 3 — Configure Yandex Mail

### 3.1 Enable IMAP

1. Go to **Settings** → **Email clients**
2. Check the box: **From server `imap.yandex.ru` via IMAP**
3. Save

### 3.2 Create an app password

1. Go to **Settings** → **Security**
2. Click the blue button **[App passwords](https://passport.yandex.ru/security/app-passwords)**
3. Create a new password for mail
4. **Save this password** — you'll need it to log into Delta Chat

### 3.3 Set up a mail processing rule

This prevents your friends' messages from landing in spam.

1. Go to **Mail rules** → create a new rule
2. Configure it like this:
   - **From:** enter your friend's email address
   - **Apply to:** all messages including spam, with and without attachments
   - **Action:** move to Inbox
   - **Also:** mark as read
   - **Apply to all existing messages:** ✅
3. Save

> You can edit this rule later to add more friends' addresses. Your friends need to create a matching rule and add your email address to it.

---

## Step 4 — Connect your account in Delta Chat

1. Open Delta Chat
2. Tap **Add account** → **Use other server** → **Use classic email as relay**
3. Enter your Yandex email and the app password from step 3.2
4. Done 🎉

---

## What's next

**Share your profile** — tap the QR code icon at the top and let your friend scan it.

**Auto-delete messages** — go to **Chat settings** and set a timer to delete messages from the server and your device.

**Calls and channels** — go to **Settings** → **Advanced** and enable the features you want.

---

## What your friends need to do

1. Install Delta Chat (step 1)
2. Create a Yandex Mail account (step 2)
3. Enable IMAP and create an app password (steps 3.1 and 3.2)
4. Create a mail rule and **add your email address to it** (step 3.3)
5. Log into Delta Chat (step 4)

</details>

---

> Delta Chat не хранит ваши сообщения на своих серверах — всё идёт через вашу почту. / Delta Chat stores nothing on its own servers — everything goes through your email.
