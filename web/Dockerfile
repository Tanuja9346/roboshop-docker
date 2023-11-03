# FROM nginx
# # remove default index.html i.e content
# RUN rm -rf usr/share/nginx/html/index.html
# # copying configuration.
# COPY roboshop.conf /etc/nginx/default.d/roboshop.conf 
# # i want to copy the code also from static 
# ADD static usr/share/nginx/html/

FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY roboshop.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html
