FROM nginx
# remove default index.html i.e content
RUN rm -rf usr/share/nginx/html/index.html
# copying configuration.
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf 
# i want to copy the code also from static 
ADD static usr/share/nginx/html/
