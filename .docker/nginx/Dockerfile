FROM nginx:1.15.0-alpine

#RUN echo "Arquivo antigo"

#RUN cat /etc/nginx/conf.d/default.conf

RUN rm /etc/nginx/conf.d/default.conf

 COPY ./nginx.conf /etc/nginx/conf.d/

#COPY ./nginx.conf /etc/nginx/conf.d/default.conf
#RUN echo "Arquivo novo"
#RUN cat /etc/nginx/conf.d/default.conf
