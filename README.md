# WEB-SCANNER
WEB SCANNER: Python Interactive Deepweb-ориентированный Rapid Intelligent Link Analyzer - это действительно быстрый прототип асинхронного веб-сканера путей, разработанный командой BrightSearch для всех этичных пользователей сети.

Python Interactive Deepweb-oriented Rapid Intelligent Link Analyzer - это действительно быстрый прототип асинхронного веб-сканера, разработанный командой Bright Search для всех этичных нетсталкеров. Написан на python. Сканер имеет большую скорость работы, имеет поддержку proxy. Сканирует структуру сайта, ищет файлы, каталоги, которые могут содержать критическую информацию.
# Установить компоненты
# pip install aiohttp_socks
# pip install python-socks
# pip install tqdm~=4.51.0
# pip install click~=7.1.2
# pip install aiohttp~=3.7.2
 =====================================================================================

# Наша новая группа  SOFT на PYTHON  https://t.me/python_softs  (подписываемся добавляем свои скрипты,скачивай наши)
=====================================================================================
# Опции
Usage: Web scanner.py  [OPTIONS]

# Options:
  -U, --user-agent TEXT           User-Agent
  -t, --timeout INTEGER           Request timeout  [default: 30]
  -A, --auth TEXT                 Basic HTTP auth, i.e. login:password
  -M, --max-connections-per-host INTEGER
                                  How many simultaneous connections should we
                                  open (per each host)  [default: 16]

  -m, --max-connections INTEGER   How many simultaneous connections should we
                                  open  [default: 128]

  -p, --proxy TEXT                Proxy address, like socks5h://127.0.0.1:9050
  -p, --pathlist FILENAME         Path list
  -L, --url-list FILENAME         Target URL list
  -u, --url TEXT                  Target URL, option is mutually exclusive
                                  with url_list  [required]

  -l, --logs DIRECTORY            Destination directory for the logs
  --http-method [head|get]        HTTP method: GET or HEAD  [default: get]
  --help                          Show this message and exit.
# Характеристики
Асинхронный
Может одновременно сканировать неограниченное количество сайтов
Поддержка в режиме реального времени
Поддержка HTTP и SOCKS прокси
Рандомизация пользовательских агентов
# Скриншот
<p align="center">
        <img align="center" src="https://raw.githubusercontent.com/enemy-submarine/pidrila/main/Pidrila.png">
</p>

Примеры использования
Сканировать один сайт clearweb

 python3 ./Web scanner.py -u http://silenthouse.yoba -M 128
Сканирование одного сайта onion

 python3 ./Web scanner.py -u http://zqktlwi4fecvo6ro.onion -m 16 -M 16 --proxy=socks5h://127.0.0.1:9050
Быстрое пакетное сканирование с помощью пользовательского агента пользователя

python3 ./Web scanner.py -m 2048 -L darkweb_sites_list.txt --user-agent "Pantusha/2.0 (4.2BSD)"

Наша новая группа  SOFT на PYTHON  https://t.me/python_softs  (подписываемся добавляем свои скрипты,скачивай наши)
