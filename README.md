# Magento-E-commerce
Simple E-commerce Site Using Magento ver. 2.4.3-p1

Requirements
-------------------
    1. Composer 2.x
    2. Elasticsearch 7.10
	3. php 7.4+
	4. Mysql 8.0
    5. Apache 2.4

Setup development
-------------------

	1. From /var/www/html folder Run git clone https://github.com/Muniyaraja98/Magento-E-commerce.git
	2. Enter git username and password when prompted
	3. Run cd magento
	4. Run git checkout master
	5. Run git pull origin master
	6. Run php init
	7. Run composer install
	8. Run composer update
    9. Create an empty database   
    10. Add DB Connection
    11. cd magento 
    12. bin/magento setup:install --base-url=http://localhost/magento2.4.3 --db-host= --db-name= --db-user= --db-password= --admin-firstname=admin --admin-lastname=admin --admin-email=admin@admin.com --admin-user=admin --admin-password=admin123 --language=en_US --currency=USD --timezone=America/Chicago --use-rewrites=1 --search-engine=elasticsearch7 --elasticsearch-host= --elasticsearch-port=
    13. sudo chmod -R 777 .
    14. bin/magento setup:upgrade
    15. bin/magento setup:di:compile
    16. bin/magento setup:static-content:deploy -f
    17. sudo chmod -R 777 .
    18. bin/magento indexer:reindex
    19. Backend Url  : http://localhost/magento/pub/admin_en12rq/
	    Frontend Url : http://localhost/magento/pub/
       
3rd-Party Extension
-------------------
    1. Pixtron – Magento 2 Theme
    
    




