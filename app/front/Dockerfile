FROM nginx:latest

WORKDIR /usr/share/nginx/html

COPY entrypoint.sh /

COPY index.html .

RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]

CMD ["nginx", "-g", "daemon off;"]

