# Туториал по работе с Git

## Начало работы

Для начала работы, необходимо инициализировать сам Git

Для его инициализации введите команду 

```
  git init
```

## Добавление файла

Для добавления файла в Git необходимо воспользоваться командой 

```
git add название файла
```

## Команда git push и её особенности

Этой командой можно отправить изменения в удаленный репозиторий.

```
git push
```

Особенности:
1. git должен знать адрес удаленного репозитория; 
2. git должен быть "авторизован" на внесение изменений в удаленном репозитории.

## Команда git pull

Этой команд позволяет «стянуть/выкачать» все изменения из удаленного репозитория на свой компьютер.

```
git pull
```