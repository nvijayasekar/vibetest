FROM nginx
#COPY index.html /usr/share/nginx/html


# Copy source code
COPY index.html /usr/share/nginx/html
COPY nginx.conf /etc/nginx/conf.d


## add permissions
RUN chown -R nginx:nginx /usr/share/nginx/html && chmod -R 755 /usr/share/nginx/html && \
        chown -R nginx:nginx /var/cache/nginx && \
        chown -R nginx:nginx /var/log/nginx && \
        chown -R nginx:nginx /etc/nginx/conf.d
#RUN touch /var/run/nginx.pid && \
     #   chown -R nginx:nginx /var/run/nginx.pid




