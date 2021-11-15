### Запуск Flask примера для Docker
1. Чтобы собрать докер образ: `docker build -t repo_name/image_name:image_tag .`
2. Чтобы его запустить: `docker run -p 5000:5000 -v "$PWD/FlaskExample/data:/root/FlaskExample/data" --rm -i repo_name/image_name`
