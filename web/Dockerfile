FROM nginx   
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY roboshop.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/


### use official nginx image and remove default config and nginx.conf and coppy the conf and unzip the folder