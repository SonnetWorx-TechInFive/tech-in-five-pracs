FROM nginx:latest

COPY index.html /usr/share/nginx/html
COPY logo-white.png /usr/share/nginx/html
COPY logo-black.png /usr/share/nginx

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]