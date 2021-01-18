FROM httpd:2.4
#COPY index.html /usr/local/apache2/htdocs/
COPY index.html /var/www/html
#COPY ./.s2i/bin/ /usr/libexec/s2i
RUN DATE='date "+%b %d, %Y @ %H:%M %p"'
RUN echo '========================================================================================='
RUN echo "---> adding date to info.html"
RUN echo '========================================================================================='
RUN echo "HOLA {$DATE} y adios" >> /var/www/html/info.html
