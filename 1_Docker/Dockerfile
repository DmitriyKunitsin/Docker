#our base image
#Для начала укажем базовый образ. Для этого нужно использовать ключевое слово FROM
FROM python:3-onbuild

#specify the port number the container should expose
#Дальше нам нужно указать порт, который следует открыть.
#Наше приложение работает на порту 5000, поэтому укажем его
EXPOSE 5000

#run the application
#Укажем команду для запуска приложения. Это просто python ./app.py. Для этого используем команду CMD
CMD [ "python", "./app.py" ]

