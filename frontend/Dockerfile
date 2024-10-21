FROM nginx
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf 
COPY Code /usr/share/nginx/html
COPY nginx.conf /etc/nginx/nginx.conf 
CMD ["sleep", "300"]
