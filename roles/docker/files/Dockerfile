FROM nginx:alpine

# RUN apt-get update && \
#     apt-get --yes install python3-flask-sqlalchemy python3-pymysql && \
#     apt-get clean

WORKDIR /love_app

COPY . .

COPY ./nginx.conf /etc/nginx/nginx.conf