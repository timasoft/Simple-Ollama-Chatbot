# Simple Ollama Chatbot

## [EN]

A simple Ollama chatbot that is easy to install and use.

### Install instructions
1. Install and setup Ollama.
1. Copy the file ```simple_chatbot_EN.html``` to your disk.
1. Open the file ```simple_chatbot_EN.html``` in a web browser.
- If you want to set specific model on page load write it in URL. For example ```Folder/with_file/simple_chatbot_EN.html?model=qwen3:14b```
- If you want to use this in Firefox AI sidebar, you can set ```browser.ml.chat.provider``` to ```Folder/with_file/simple_chatbot_EN```

#### Ollama setup instruction
1. Install Ollama: [ollama.com/download](https://ollama.com/download).
1. Install your favorite model. For example, you can use the following command to install the qwen3 model: ```ollama pull qwen3```.
1. Set environment variable ```OLLAMA_ORIGINS=*```. On windows, you can set it simply by running this powershell command: ```[Environment]::SetEnvironmentVariable("OLLAMA_ORIGINS","*","User")```.
1. Make sure Ollama is running. Either by doing ```ollama serve``` in a terminal or by opening ollama.exe.

If you want to modify the chatbot, you can edit the file ```simple_chatbot_EN.html``` in a text editor. The chatbot is written in HTML and JavaScript, so you can easily change the code to suit your needs.
Also, you can copy the code in the chatbot interface and ask your favorite ai model to make it better! In fact, the entire code was created by an AI.

### Support
Support the following features:
- Markdown
- Mathjax
- Code bloc synthax highlighting
- Attaching files (including pdf)
- Attaching images
- Scrape URL content found in the user input and send it to the model
- Dark and light mode toggle
- Firefox AI sidebar support
- Remember chat history when reopening the file. Chat history can be erased by clicking the ```Reset Chat``` button.


## [RU]

Простой чат-бот Ollama, который легко установить и использовать.

### Инструкции по установке
1. Установите и настройте Ollama.
1. Скопируйте файл ```simple_chatbot_RU.html``` на свой диск.
1. Откройте файл ```simple_chatbot_RU.html``` в веб-браузере.
- Если вы хотите поставить определённую модель во время загрузки страницы, укажите её в URL. Для примера ```Папка/с_файлом/simple_chatbot_RU.html?model=qwen3:14b```
- Если вы хотите использовать это в ИИ боковой панели Firefox, вы можете установить ```browser.ml.chat.provider``` на ```Папка/с_файлом/simple_chatbot_RU```

### Инструкция по настройке Ollama
1. Установите Ollama: [ollama.com/download](https://ollama.com/download).
1. Установите свою любимую модель. Например, вы можете использовать следующую команду для установки модели qwen3: ```ollama pull qwen3```.
1. Установите переменную окружения ```OLLAMA_ORIGINS=*```. В Windows вы можете сделать это, просто запустив эту команду PowerShell: ```[Environment]::SetEnvironmentVariable("OLLAMA_ORIGINS","*","User")```.
1. Убедитесь, что Ollama работает. Либо выполнив ```ollama serve``` в терминале, либо открыв ollama.exe.

Если вы хотите модифицировать чат-бота, вы можете отредактировать файл ```simple_chatbot_RU.html``` в текстовом редакторе. Чат-бот написан на HTML и JavaScript, поэтому вы можете легко изменить код в соответствии со своими потребностями.
Также, вы можете скопировать код в интерфейсе чат-бота и попросить свою любимую ИИ модель сделать его лучше! На самом деле, весь код был создан ИИ.

### Поддерживаемые функции:
- Markdown
- Mathjax
- Подсветка синтаксиса для блоков кода
- Прикрепление файлов (включая PDF)
- Прикрепление изображений
- Извлечение содержимого URL, найденного во вводе пользователя, и отправка его модели
- Переключение между темной и светлой темами
- Поддержка ИИ боковой панели Firefox
- Сохранение истории чата при повторном открытии файла. История чата может быть удалена нажатием кнопки ```Очистить чат```.
