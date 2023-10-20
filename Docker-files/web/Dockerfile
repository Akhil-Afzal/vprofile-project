FROM nginx
LABEL "project"="vprofile"
LABEL "author"="Afzal"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY ngivproapp.conf /etc/nginx/conf.d/vproapp.conf
