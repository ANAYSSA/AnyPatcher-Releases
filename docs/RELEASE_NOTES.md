# AnyPatcher 0.2.4 — исправление инструментов ChatGPT

- Исправлена ошибка «отсутствует codex-code-mode-host»: необходимый компонент теперь входит в DMG рядом с Codex.
- AnyPatcher проверяет комплектность встроенного Codex до отправки запроса к модели.
- Сборка проверяет настоящий вызов инструмента исследования через Code Mode на локальном тестовом сервере, без расходования лимитов аккаунта.
- Начиная с этой версии DMG выпускается только для Apple Silicon (M1 и новее).

Замените приложение из версии 0.2.3 на `AnyPatcher_0.2.4_macOS_arm64.dmg`. Проекты, вход в ChatGPT и сохранённые способы декодирования находятся отдельно от приложения и сохраняются.

macOS 13+. Preview подписан ad-hoc, без нотарификации Apple.

[Руководство](https://github.com/ANAYSSA/AnyPatcher-Releases/blob/main/docs/GUIDE_RU.md) · [Подключение ИИ](https://github.com/ANAYSSA/AnyPatcher-Releases/blob/main/docs/INTEGRATIONS.md)
