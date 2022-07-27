# M1 Macは、platform指定がないとエラー
FROM --platform=linux/x86_64 mysql:5.7.38

COPY ./conf.d/my.cnf /etc/mysql/conf.d/
COPY ./initdb.d/* /docker-entrypoint-initdb.d/