---Start DB:
sudo docker-compose up

Start and disconnect:
sudo docker-compose up -d
sudo docker-compose start

Stop and destroy:
sudo docker-compose stop
sudo docker-compose rm



---Connect:
mysql --host=127.0.0.1 --user=root --password=root test




----------------

---For import of data:

mysql -u root -p -h 127.0.0.1 test < mysqlsampledatabase.sql


---For viewing imported data:
mysql --host=127.0.0.1 --user=root --password=root classicmodels
