# learn-with-webpack
# WEBPACK

ссылка на youtube
https://youtu.be/o8KMucDpSno

Для установки пакетов используйте команду npm install

## Команды
npm init -y
```
npm install webpack -d
```
npm install webpack-cli webpack-dev-server -d
```


```
в Json прописать скрипты

 "scripts": {
    "start": "webpack serve",
    "build-dev": "webpack",
    "build-prod": "webpack --node-env=production",
    "clear": "rd /s /q dist"
  },
```
### Запуск сервера для разработки
```shell
npm run start
### Сборка проекта без оптимизации
```shell
npm run build-dev
```

### Сборка проекта с оптимизацией
```shell
npm run build-prod
```

### Очистка папки dist
```shell
npm run clear
```
git init
 git add README.md
  git commit -m "first commit"
   git branch -M main
    git remote add origin https://github.com/Alekc/webpack.git
     #запушить
    git push -u origin main


 git branch -M main 
 git push -u origin main

#дополнения git-config
 #Действия после установки git посмотреть настройки 
git config --list 
git config --global user.name “имя” git config --global user.email “почта”

git config --global core.safecrlf warn 
git config --global core.quotepath off git config --global init.defaultBranch main 
# Ветка по умолчанию windows git config --global core.autocrlf true MAC & UNIX git config --global core.autocrlf input Действия при инициализации нового репозитория и при работе с ним инициализация git репозитория git init текущее состояние репозитория git status добавить в трек (отслеживаемые) файл или папку git add index.html добавить все файлы из корня в трек git add . выполнить коммит (сделать слепок) текущего состояния проекта git commit -m "сообщение" git log --oneline посмотреть историю коммитов
