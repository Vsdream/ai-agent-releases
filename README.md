# AI Agent releases

Windows installers and cloud update packages for the shared Adobe After Effects
and Premiere Pro AI Agent panel.

Download **AI Agent Setup.exe** from the [latest release](https://github.com/Vsdream/ai-agent-releases/releases/latest).
Close Adobe for initial installation, then open Window > Extensions > AI Agent and
enter your API key. Cursor IDE and separate Node.js installation are not required.

**0.5.8:** speeds up routine edits beyond solids through compact AE instructions,
batched execution and checked completion inside the final tool call. Cursor uses
Low effort where supported; Settings offers other effort levels. Reply detail is
independent. Native tests cover selection edits, text, keys, shape/noise, folders,
multi-step duplication and read-only inspection. Update in the panel from 0.5.2+;
Reload Panel in AE/Premiere. A new Setup is provided for fresh installations.
If AE has not been restarted since upgrading from pre-0.5.7, restart it once.

**0.5.8:** ускорены обычные задачи, помимо солидов: компактные инструкции,
пакетное выполнение и завершение прямо в последней команде после проверки значений.
Cursor использует Low там, где модель его поддерживает; уровень меняется в Settings.
Reply detail отдельно управляет длиной ответа. Проверены выделение, текст, ключи,
шейп с шумом, папки, составная задача и чтение проекта. С 0.5.2+ обновляйтесь в
панели, затем Reload Panel в AE/Premiere. Setup нужен для новой установки.
Если после перехода с версии ниже 0.5.7 ещё не перезапускали AE, сделайте это один раз.

**0.5.7:** adds a validated solid batch tool, prevents replay after lost execution
responses, and shows readable Cursor errors. Three live Grok 4.7 / hidden AE 25.5
runs completed the five-solids task in 19–27 seconds. Those local timings do not
guarantee the same bridge latency on another computer.
After upgrading from an older version, save your project and restart AE once to
retire an HTTP server retained by older panel code. A new Setup is not required
for users on 0.5.2+; install inside the panel, then restart AE.

**0.5.7:** готовый инструмент пакетного создания солидов, защита от повторного
исполнения при потере ответа, понятные ошибки Cursor. Три живых прогона Grok 4.7
в скрытом AE 25.5 выполнили задачу с пятью солидами за 19–27 секунд. Это локальные
замеры; задержка моста на другом компьютере может отличаться.
После обновления со старой версии сохраните проект и один раз перезапустите AE:
старый код мог оставить HTTP-сервер в памяти. С 0.5.2+ новый Setup не нужен —
обновитесь в панели, затем перезапустите AE.

**0.5.6:** fixes updates blocked by a running bundled node.exe. The compatibility
package omits unchanged native files so older updaters can install the fix; future
updates stop owned runtime processes and check locks before replacement.
If 0.5.5 failed with a node.exe lock, check for updates again and install the current release.
Users on **0.5.2 or later** can use Check for updates > Update without restarting
Adobe. Users on **0.5.0/0.5.1** must download the new installer manually once
to repair the old updater; do not use their old Update button. Save your project
and close both Adobe applications before running Setup. User data is preserved.

**0.5.6:** исправлено обновление при занятом node.exe. Совместимый пакет не заменяет
неизменившиеся бинарники, поэтому старый обновлятор может получить исправление.
Если 0.5.5 завершилась ошибкой node.exe, снова проверьте обновления и установите текущую версию.
С версии **0.5.2** обновляйтесь кнопкой Update без перезапуска Adobe. С версий
**0.5.0/0.5.1** один раз скачайте новый Setup вручную, чтобы исправить обновлятор;
старую кнопку Update не используйте. Перед Setup сохраните проект и закройте
After Effects и Premiere Pro. Ключи, задачи и пресеты сохраняются.

Starting with 0.0.34, the panel checks this repository for updates. Ordinary
updates reload the panel without restarting Adobe. Releases changing CEP startup
configuration show a restart notice.

This repository distributes release files only, without personal API keys,
settings or chat history.
