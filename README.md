# everything-recognition
 
Скрипт для распознавания объектов по загруженным классификаторам.

## Как установить

1. Клонировать репозиторий:

    ```shell
    git clone https://github.com/devmanorg/everything-recognition
    ```

2. Установить зависимости:

    ```shell
    pip install -r requirements.txt
    ```

3. Для запуска скрипта используйте команду:
    
    ```shell
    python run.py
    ```
    
    Для выхода из приложения нажмите `q`.

## Файл config.py

Файл `config.py` содержит настройки распознаваемых объектов в словаре `CASCADES`.
Доступные объекты:
- `Face front`
- `Face profile`
- `Smile`
- `Eyes`
- `Full body`
- `Cat face`

Параметры объектов:
- `path` - путь к классификатору в формате `.xml`
- `color` - цвет рамки в GBR
- `draw` - флаг активности каскада




