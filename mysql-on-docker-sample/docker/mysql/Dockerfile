# M1 Macは、platform指定がないとエラー
FROM --platform=linux/x86_64 mysql:5.7.38

# DBのglobalな設定値を投入
COPY ./conf.d/my.cnf /etc/mysql/conf.d/
# 初期値としてのtableやcolumnを投入
COPY ./initdb.d/* /docker-entrypoint-initdb.d/