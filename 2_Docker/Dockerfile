FROM ubuntu
# равноценна docker run -it ubuntu bash


RUN apt-get update && apt-get install -y cowsay && ln -s /usr/games/cowsay /usr/bin/cowsay
# -y  автоматически определяет запрос на  все согласия

ENTRYPOINT [ "cowsay" ]
# позволяет при написании "docker run seabassc/cowsay"  не писать команду cowsay после seabassc/cowsay
