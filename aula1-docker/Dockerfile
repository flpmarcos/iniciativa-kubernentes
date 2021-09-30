# Criando uma imagem baseado no ubuntu
FROM ubuntu
RUN apt-get update
RUN apt-get install curl --yes
RUN apt-get install vim --yes

# Colocar a instrucao concatenada evita o cache na hora de criar a imagem
# RUN apt-get update && apt-get install curl --yes && apt-get install vim --yes
