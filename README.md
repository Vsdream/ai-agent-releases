# AI Agent releases

Windows installers and cloud update packages for the shared Adobe After Effects
and Premiere Pro AI Agent panel.

Download **AI Agent Setup.exe** from the [latest release](https://github.com/Vsdream/ai-agent-releases/releases/latest).
Close Adobe for initial installation, then open Window > Extensions > AI Agent and
enter your API key. Cursor IDE and separate Node.js installation are not required.

**0.5.2 upgrade:** users on 0.5.0/0.5.1 need to run the new installer once to
repair the cloud updater. Save your project and close both Adobe applications
before installation. Keys, tasks and presets are preserved. This release offers
the full installer instead of attempting the affected hot-update path.

**Обновление до 0.5.2:** с версий 0.5.0/0.5.1 один раз запустите новый установщик,
чтобы исправить обновлятор. Сохраните проект и закройте After Effects и Premiere
Pro перед установкой. Ключи, задачи и пресеты сохраняются.

Starting with 0.0.34, the panel checks this repository for updates. Ordinary
updates reload the panel without restarting Adobe. Releases changing CEP startup
configuration show a restart notice.

This repository distributes release files only, without personal API keys,
settings or chat history.
