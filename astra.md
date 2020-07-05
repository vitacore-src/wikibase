<!-- TITLE: Astra Linux -->
<!-- SUBTITLE: Инструкция по установке РМИС "Витакор" (клиентская часть) на Astra Linux SE "Смоленск" -->


## 1. Подготовительные работы

Для корректной работы РМИС "Витакор" на операционную систему должно быть установлено кумулятивное обновление безопасности для ОС СН релиз "Смоленск" в. 1.6 (Update 5) в соответствии с  [инструкцией](https://wiki.astralinux.ru/pages/viewpage.action?pageId=71829652). 

На время установки пользователь, от которого ведется установка, должен обладать высоким уровнем целостнисти и входить в группу "sudo". После установки уровень целостности пользователя можно понизить и исключить из группы "sudo".

## 2. Установка криптопровайдера

В случае необходимости функционала электронной подписи в РМИС необходимо установить криптопровайдер. Для установки КриптоПро CSP 4 нужно распаковать архив с дистрибутивом и запустить скрипт инсталляции.

```sh
tar xvzf CPRO-4R4-Astra-ready-32bit-ver2.tar.gz 
cd CPRO-4R4-Astra-ready-32bit-ver2
./astra-install.sh
```


При возникновении ошибок установки пакетов может потребоваться исправление командой

```sh
sudo apt -f install
```


## 3. Установка wine с поддержкой КриптоПро CSP

РМИС "Витакор" в ОС Linux работает в среде wine. Для установки выполните следующие шаги в каталоге с пакетами wine

```sh
sudo apt -y install ia32-libs
sudo apt -y install binutils
sudo dpkg -i wine-5.0.1-cpro_astra.deb 
sudo dpkg -i libmspack0*.deb
sudo dpkg -i cabextract*.deb
sudo dpkg -i winetricks*.deb
sudo apt -f install
```

# 4. Установка шрифтов и драйвера принтера

Перейдите в домашний каталог и распакуйте архив со шрифтами, необходимыми для работы РМИС

```sh
cd
tar xvzf fonts.tar.gz
```

Удалите системный шрифт Tahoma (в случае если он установлен)

```sh
sudo find /usr -name "tahoma.ttf" -delete
sudo find /usr -name "tahomabd.ttf" -delete
sudo find /opt -name "tahoma.ttf" -delete
sudo find /opt -name "tahomabd.ttf" -delete
```

Для корректной работы предпросмотра печати необходим псевдопринтер pdf (при отсутствии физического принтера)

```sh
sudo dpkg -i printer-driver-cups-pdf_2.6.1-22_amd64.deb
sudo apt -f install
```

## 5. Установка префикса wine

В сессии, из которой запускаем wine нужно определить переменные WINE и WINEARCH. Для постоянного эффекта нужно добывить указанные переменные в файл ~/.bashrc 

```sh
export WINE=/opt/wine-cpro/bin/wine
export WINEARCH=win32

echo "export WINE=/opt/wine-cpro/bin/wine" >> ~/.bashrc
export "WINEARCH=win32" >> ~/.bashrc
```




