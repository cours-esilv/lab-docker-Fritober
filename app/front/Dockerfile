FROM nginx:latest

WORKDIR /usr/share/nginx/html

COPY . .

RUN chmod +x entrypoint.sh

ENTRYPOINT ["./entrypoint.sh"]

CMD ["nginx", "-g", "daemon off;"]
