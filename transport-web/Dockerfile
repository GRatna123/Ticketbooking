FROM nginx:alpine
COPY index.html /usr/share/nginx/html/index.html
COPY bus/index.html /usr/share/nginx/bus/index.html
COPY movie/index.html /usr/share/nginx/movie/index.html
COPY train/index.html /usr/share/nginx/train/index.html
COPY nginx/nginx.conf /etc/nginx/conf.d/default.conf
EXPOSE 80
