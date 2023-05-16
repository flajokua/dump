# Установка Windows
[Скачиваем python 3.xx](https://www.python.org/downloads/release/python-3110/)
При установке добавляем галочку - Add python.exe to PATH
[Скачиваем zip архив](https://github.com/ivanbrods/dump/archive/refs/heads/main.zip)
Разархивируем архив
В архиве запускаем файл (install module.bat) - только при первой установке python 3.xx в дальнейшем этот файл не нужен
Для использования запускаем файл - start.bat
# Установка Linux
```bash
sudo apt-get update && upgrade --y
```
```bash
sudo apt-get install python3 -y
```
```bash
sudo apt-get install git
```
```bash
git clone https://github.com/ivanbrods/dump
```
```bash
cd dump
```
```bash
pip3 install --upgrade pip3
```
```bash
pip3 install -r requirements.txt
```
Все вышеуказаные команды выполняються только 1 раз во время установки, в последующие разы выполнять их не нужно
```bash
python3 dump.py
```


## Для скачивания списка друзей из вк используем: 
##https://e965.github.io/vk-friends-saver
