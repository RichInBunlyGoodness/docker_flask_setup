FROM nginx:1.13.8-alpine
RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/
RUN rm /etc/nginx/conf.d/default.conf
COPY my_flask_app.conf /etc/nginx/conf.d/
