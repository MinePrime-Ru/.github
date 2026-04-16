# Структура анкеты онбординга (Яндекс.Форма)

Этот документ описывает поля, которые необходимо настроить в Яндекс.Форме для регистрации новых разработчиков.

## Основные настройки формы
- **Название:** Регистрация участника проекта MinePrime
- **Доступ:** По ссылке
- **Ограничения:** Рекомендуется ограничить "Один ответ на пользователя" (требуется авторизация в Яндексе).

## Поля формы

### 1. Личные данные
- **Вопрос:** Фамилия, Имя, Отчество
- **Тип:** Короткий текст (строка)
- **Обязательно:** Да
- **Описание:** Укажите ФИО полностью (согласно паспорту) для юридической идентификации.

### 2. Контактный Email
- **Вопрос:** Электронная почта
- **Тип:** Электронная почта
- **Обязательно:** Да
- **Описание:** Для связи и отправки официальных уведомлений.

### 3. Аккаунты
- **Вопрос:** Ваш GitHub Username
- **Тип:** Короткий текст (строка)
- **Обязательно:** Да
- **Описание:** Например, @AveCard1nal.

- **Вопрос:** Ваш Discord Username / Ник в игре
- **Тип:** Короткий текст (строка)
- **Обязательно:** Да

### 4. Роль в проекте
- **Вопрос:** На какую роль вы претендуете?
- **Тип:** Один вариант (Выпадающий список)
- **Обязательно:** Да
- **Варианты:**
  - Разработчик (Java / Web / Scripts)
  - Технический администратор / DevOps
  - Администратор / Модератор сервера
  - Дизайнер / Художник / Builder
  - Иная роль

### 5. Согласие с условиями (Юридический блок)
- **Вопрос:** Подтверждение согласия
- **Тип:** Несколько вариантов (Чекбоксы)
- **Обязательно:** Да
- **Варианты:**
  1. [ ] Я ознакомился(-ась) и полностью принимаю условия **[Соглашения об участии](https://github.com/MinePrime-Ru/.github/blob/main/PARTICIPANT_AGREEMENT.md)** версии 2026-04-16.
  2. [ ] Я подтверждаю, что указанные аккаунты находятся под моим полным контролем.
  3. [ ] Я даю согласие на обработку моих персональных данных (ФИО и Email) на территории РФ в целях исполнения соглашения (согласно ФЗ-152).
  4. [ ] Я понимаю, что все мои будущие вклады (код, ассеты, конфиги) будут регулироваться данным соглашением и права на них переходят к Оператору.
  5. [ ] (Для Staff) Я обязуюсь соблюдать правила для Администрации и не злоупотреблять полномочиями.

### 6. Дата
- **Вопрос:** Дата заполнения
- **Тип:** Дата
- **Обязательно:** Да

---

# Onboarding Form Structure (Yandex.Forms)

This document describes the fields to be configured in Yandex.Forms for participant registration (Developers, Staff, Admins).

## Form Fields

1. **Full Name** (Short text, Required) — For legal identification.
2. **Email** (Email type, Required) — For contact and official notifications.
3. **Accounts**:
   - **GitHub Username** (Short text, Required) — e.g., @AveCard1nal.
   - **Discord Username / In-game Nickname** (Short text, Required).
4. **Project Role** (Dropdown, Required):
   - Developer (Java / Web / Scripts)
   - Technical Admin / DevOps
   - Server Admin / Moderator
   - Designer / Artist / Builder
   - Other
5. **Agreement Confirmation** (Checkboxes, Required):
   - [ ] I have read and fully accept the **[Project Participation Agreement](https://github.com/MinePrime-Ru/.github/blob/main/PARTICIPANT_AGREEMENT.md)** version 2026-04-16.
   - [ ] I confirm that the specified accounts and email are under my full control.
   - [ ] I consent to the processing of my personal data (Full Name and Email) within the RF for the purpose of the agreement (FZ-152).
   - [ ] I understand that all my future contributions (code, assets, configs) will be governed by this agreement and rights to them are transferred to the Operator.
   - [ ] (For Staff) I undertake to comply with the rules for Administration and not to abuse my powers.
6. **Date** (Date, Required).
