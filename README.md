# 📘 РУКОВОДСТВО ПО ИСПОЛЬЗОВАНИЮ NLOADER / NLOADER USER GUIDE
========================================================================

## 🇷🇺 РУ

> 🤖 **NLoader** — это мой лоадер для серверов Unturned. На данный момент проект запущен в тестовом режиме. Если лоадер покажет себя хорошо и понравится аудитории, я буду полноценно и стабильно поддерживать его в дальнейшем. Сейчас всё находится на стадии активного тестирования, поэтому при обнаружении любых багов или ошибок обязательно пишите в ветку ниже!

---

### ⚙️ Инструкция по установке:

`Шаг 1` **Скачивание файлов**
Загрузите актуальную версию лоадера `NLoader.dll`, а также все необходимые системные библиотеки по ссылке в конце этой инструкции. 
> ⚠️ *Важно: если на вашем сервере не будет установлена вся необходимая база библиотек, плагины могут работать некорректно или не запуститься вовсе. Все зависимости доступны по той же ссылке.*

`Шаг 2` **Загрузка на сервер**
Поместите файл `NLoader.dll` в директорию плагинов вашего сервера:
📂 `Rocket/Plugins/`

`Шаг 3` **Первый запуск и активация**
Запустите сервер в первый раз для автоматической генерации файла конфигурации. После генерации откройте конфиг и установите значение `true` для тех плагинов, которые вы хотите активировать:
📂 `NLoader.configuration.xml`

`Шаг 4` **Перезапуск лоадера**
Для применения изменений напишите в консоль сервера команду `nl reload` или полностью перезапустите сервер.

`Шаг 5` **Настройка плагинов**
Измените конфигурационный файл нужного вам плагина, после чего перезапустите его отдельно с помощью консольной команды:
💬 `nl reload [имя_плагина]`

---

### 💻 Все доступные команды:
> **Синтаксис:** `/nloader <list|reload|load|unload> [имя_плагина]`
> *(Сокращенная версия: `/nl`)*

* 📊 `list` — показать список загруженных плагинов.
* 🔄 `reload [plugin]` — перезагрузить указанный плагин (или лоадер целиком).
* 📥 `load [plugin]` — загрузить выбранный плагин.
* 📤 `unload [plugin]` — выгрузить выбранный плагин.

---

### ⚠️ Обратите внимание:
* Никогда не меняйте название файла `NLoader.dll`.

---

💾 **Скачать NLoader и библиотеки плагинов:**
👉 [ Ссылка на скачивание ](https://github.com/null00000007/Nloader/raw/refs/heads/main/NLoader.dll)
👉 [ Ссылка на репозиторий (библиотеки) ](https://github.com/null00000007/Nloader/tree/main/Libs)

========================================================================

## 🇬🇧 EN

> 🤖 **NLoader** is my loader for Unturned servers. The project is currently in beta. If the loader performs well and is well-received by the community, I will continue to provide full and consistent support for it in the future. Everything is currently undergoing active testing, so if you find any bugs or issues, please be sure to post them in the thread below!

---

### ⚙️ Installation Guide:

`Step 1` **Downloading Files**
Download the latest version of `NLoader.dll` and all required system libraries using the link at the end of this guide.
> ⚠️ *Important: if your server is missing the required library base, the plugins may not function correctly or fail to load. All dependencies are available at the same link.*

`Step 2` **Uploading to Server**
Place the `NLoader.dll` file into your server's plugins directory:
📂 `Rocket/Plugins/`

`Step 3` **First Launch & Activation**
Start the server for the first time to automatically generate the configuration file. Once generated, open the config and set the value to `true` for the plugins you wish to activate:
📂 `NLoader.configuration.xml`

`Step 4` **Reloading the Loader**
To apply the changes, type the `nl reload` command in the server console, or fully restart the server.

`Step 5` **Configuring Plugins**
Modify the configuration file of the desired plugin, then restart it individually using the following console command:
💬 `nl reload [plugin_name]`

---

### 💻 All Available Commands:
> **Syntax:** `/nloader <list|reload|load|unload> [plugin_name]`
> *(Abbreviated version: `/nl`)*

* 📊 `list` — show the list of loaded plugins.
* 🔄 `reload [plugin]` — reload the specified plugin (or the entire loader).
* 📥 `load [plugin]` — load the selected plugin.
* 📤 `unload [plugin]` — unload the selected plugin.

---

### ⚠️ Please Note:
* Never change the filename of `NLoader.dll`.

---

💾 **Download NLoader and Plugin Libraries:**
👉 [ Download Link ](https://github.com/null00000007/Nloader/raw/refs/heads/main/NLoader.dll)
👉 [ Repo Link Libs ](https://github.com/null00000007/Nloader/tree/main/Libs)
