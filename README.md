# gulp_settings
Дополнительно для настроек gulp и VScode:

1. Установить плагин для VScode "Path Autocomplete"
2. В настройках плагина в файле settings.json прописать команду:
            "path-autocomplete.pathMappings": {
            "@img": "${folder}/src/img",
            "@scss": "${folder}/src/scss",
            "@js": "${folder}/src/js",
        }
3. Все пути теперь прописываем так: 
    <img src="@img/img1.jpg" alt="">
    
4. Таким образом редактор будет считывать правильную папку, и на выходе в исходном коде мы получим следующее:
    <img src="img/img1.jpg" alt="">

