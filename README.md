# AI Agent releases

Windows installers and cloud update packages for the shared Adobe After Effects
and Premiere Pro AI Agent panel.

Download **AI Agent Setup.exe** from the [latest release](https://github.com/Vsdream/ai-agent-releases/releases/latest).
Close Adobe for initial installation, then open Window > Extensions > AI Agent and
enter your API key. Cursor IDE and separate Node.js installation are not required.

**0.5.6:** fixes updates blocked by a running bundled node.exe. The compatibility
package omits unchanged native files so older updaters can install the fix; future
updates stop owned runtime processes and check locks before replacement.
If 0.5.5 failed with a node.exe lock, check for updates again and install 0.5.6.
Users on **0.5.2 or later** can use Check for updates > Update without restarting
Adobe. Users on **0.5.0/0.5.1** must download the new installer manually once
to repair the old updater; do not use their old Update button. Save your project
and close both Adobe applications before running Setup. User data is preserved.

**0.5.6:** исправлено обновление при занятом node.exe. Совместимый пакет не заменяет
неизменившиеся бинарники, поэтому старый обновлятор может получить исправление.
Если 0.5.5 завершилась ошибкой node.exe, снова проверьте обновления и установите 0.5.6.
С версии **0.5.2** обновляйтесь кнопкой Update без перезапуска Adobe. С версий
**0.5.0/0.5.1** один раз скачайте новый Setup вручную, чтобы исправить обновлятор;
старую кнопку Update не используйте. Перед Setup сохраните проект и закройте
After Effects и Premiere Pro. Ключи, задачи и пресеты сохраняются.

Starting with 0.0.34, the panel checks this repository for updates. Ordinary
updates reload the panel without restarting Adobe. Releases changing CEP startup
configuration show a restart notice.

This repository distributes release files only, without personal API keys,
settings or chat history.
