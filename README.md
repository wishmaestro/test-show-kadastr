# test-show-kadastr
Отображение на карте полигона объекта, полученного по кадастровому номеру

#скачиваем библиотеку
git clone https://github.com/rendrom/rosreestr2coord 
# переходим в нее
cd ./rosreestr2coord
# создание виртуального окружения
python -m venv ./.env
# активация виртуального окружения Linux and MacOS
. ./.env/bin/activate
# установка зависимостей
pip install -r requirements.txt

# запуск приложения
python ./main.py