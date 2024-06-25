# WEB-SCANNER
WEB SCANNER: Python Interactive Deepweb-ориентированный Rapid Intelligent Link Analyzer - это действительно быстрый прототип асинхронного веб-сканера путей, разработанный командой BrightSearch для всех этичных пользователей сети.

Python Interactive Deepweb-oriented Rapid Intelligent Link Analyzer - это действительно быстрый прототип асинхронного веб-сканера, разработанный командой Bright Search для всех этичных нетсталкеров. Написан на python. Сканер имеет большую скорость работы, имеет поддержку proxy. Сканирует структуру сайта, ищет файлы, каталоги, которые могут содержать критическую информацию.

# Опции
Usage: pidrila.py [OPTIONS]

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


