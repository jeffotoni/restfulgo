# restfulgo
CREATING A SIMPLE API USING GOLANG

# CLONE
<pre>git clone git@github.com:DiegoSantosWS/restfulgo.git</pre>

# CREATING DATA BASE

<pre>
    CREATE A DATA BASE AND LAST EXECUT THE CODE.

    CREATE TABLE `products` (
    `id` int(11) NOT NULL AUTO_INCREMENT,
    `name` varchar(50) DEFAULT NULL,
    `description` longtext,
    `stock` decimal(10,3) DEFAULT NULL,
    `width` decimal(10,3) DEFAULT NULL,
    `height` decimal(10,3) DEFAULT NULL,
    `amount` decimal(10,3) DEFAULT NULL,
    `weight` decimal(10,3) DEFAULT NULL,
    `price` decimal(10,3) DEFAULT NULL,
    `discount` decimal(10,3) DEFAULT NULL,
    `promotion` decimal(10,3) DEFAULT NULL,
    PRIMARY KEY (`id`)
    ) ENGINE=InnoDB DEFAULT CHARSET=utf8;
</pre>