1. Criar o Dockerfile
2. Criar a imagem docker a partir das definições contidas no Dockerfile: sudo docker build -t linuxlite/conversao-peso:v1 .
3. Executar o container: sudo docker run -it --rm -p 5000:80 linuxlite/conversao-peso:v1
4. Acessar a aplicação: http://localhost:5000/
