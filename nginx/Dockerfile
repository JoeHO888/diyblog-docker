FROM nginx
COPY mysite_nginx.conf /etc/nginx/sites-available/
COPY nginx.conf /etc/nginx/nginx.conf
RUN mkdir /etc/nginx/sites-enabled/
RUN ln -s /etc/nginx/sites-available/mysite_nginx.conf /etc/nginx/sites-enabled/
CMD ["nginx", "-g", "daemon off;"]
