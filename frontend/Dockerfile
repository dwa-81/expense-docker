FROM nginx
RUN rm -rf /etc/nginx/nginx.conf
COPY Code /usr/share/nginx/html
RUN rm -rf /etc/nginx/conf.d/default.conf 
COPY nginx.conf /etc/nginx/nginx.conf 
CMD ["sleep", "300"]
