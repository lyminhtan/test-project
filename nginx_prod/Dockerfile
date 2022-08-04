FROM nginx:1.21.6

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d
COPY officience.com.crt /etc/nginx/certs/officience.com.crt
COPY officience.com.key /etc/nginx/certs/officience.com.key
