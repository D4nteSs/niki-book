# niki-book
Files of project bookstack on my global server "niki-book.ru"

To fast restore dump bstack.sql.gz :

`mysql -uroot -e "CREATE DATABASE bookstack;" | gunzip < bstack.sql.gz | mysql -u root bookstack`
