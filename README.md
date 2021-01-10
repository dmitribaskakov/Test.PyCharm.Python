
Команды для докера:
docker build -t test.pycharm .
docker images
docker ps -a
docker rm $(docker ps -a -q)
docker run --name hello --rm test.pycharm