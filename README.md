# Описание:
Скрипт собирает и выдает список Https proxies с сайта https://free-proxy-list.net
Актуальная версия скрипта: get_ssl_proxies_v2.py

# Формат выдачи результата:
Данные записываются в двух форматах:
- ssl_proxies.txt – список в формате {ip}:{port}. Сепаратор – знак переноса строки '\n'.
- ssl_proxies.json – список словарей в формате:
{
        "proxy": "ip:port"
    }

