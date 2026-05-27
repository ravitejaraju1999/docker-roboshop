from nginx
run rm -rf /usr/share/nginx/html/* && \
    rm -rf /etc/nginx/conf.d/default.conf && \
    rm -rf /etc/nginx/nginx.conf
copy nginx.conf /etc/nginx/conf.d/default.conf
copy static/ /usr/share/nginx/html/