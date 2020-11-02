FROM node:12.19.0

WORKDIR /myapp/nuxt-project

RUN apt-get update && npm install -g npm && npm install -g @vue/cli && npm install -g create-nuxt-app

ENV HOST 0.0.0.0
EXPOSE 8080
