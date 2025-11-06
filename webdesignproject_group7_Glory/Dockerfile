FROM nginx:alpine
RUN rm -rf /usr/share/nginx/html/* /usr/share/nginx/html/.* 2>/dev/null || true
COPY html/ /usr/share/nginx/html/
COPY css/ /usr/share/nginx/html/css/
COPY assets/ /usr/share/nginx/html/assets/
EXPOSE 80