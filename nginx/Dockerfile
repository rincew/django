FROM nginx
 
RUN mkdir /sock
 
ADD uwsgi_params /etc/nginx/
ADD django.conf /etc/nginx/conf.d/default.conf
