# Determino a imagem que servirá como base para a imagem que irei criar
FROM ubuntu:21.04

# Roda o comando instruido
# É uma boa prática instalar os pacotes junto com o apt-get update, para evitarmos cachear o apt-get update, que pode levar à erros como baixar um pacote desatualizado.
RUN apt-get update -y && \
  apt-get install curl -y