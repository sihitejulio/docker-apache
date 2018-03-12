
FROM secret06/belajarcodenodejs:v1.0.0

MAINTAINER agung julisman <agung.julisman@yahoo.com>

COPY . /app

CMD pm2 start app.js --no-daemon --watch 

CMD pm2 start app_sec.js --no-daemon --watch 

EXPOSE 9000

EXPOSE 7000








