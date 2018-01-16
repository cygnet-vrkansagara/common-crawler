Common Crawler Index
=====================

Common Crawler library based on `PHP` using `Zend Framework`

#### How to run from web !

``` <<project url>>/commoncrawler```

#### How to run from console !

```  php public/index.php commooncrawler```


### Download / Install
~~~
 composer require vrkansagara/common-crawl
~~~

#### [ TODO ]

-[] Implement client https://github.com/ikreymer/cc-index-client


#### [ Feature - Console]

-[x] Insert index list

-[x] Remove all index

-[x] Active /Inactive  all

-[x] Active /Inactive



#### [ Feature - Web]

-[x] Insert index list

-[x] Remove all index

-[] Active /Inactive  all

-[] Active /Inactive


#### [ Multiple Database Support]

-[x] Mysql

-[x] Sqlite

-[] MongoDB

-[] ElasticSearch


###SQL

~~~sql
CREATE TABLE `common_index` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `index` varchar(25) NOT NULL,
  `name` varchar(20) NOT NULL,
  `timegate` varchar(50) NOT NULL,
  `cdx_api` varchar(55) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=124 DEFAULT CHARSET=utf8
~~~

###SQLite
~~~sqlite
CREATE TABLE common_index
(
    id INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,
    "index" VARCHAR(25) NOT NULL,
    name VARCHAR(20) NOT NULL,
    timegate VARCHAR(50) NOT NULL,
    cdx_api VARCHAR(55) NOT NULL
);
~~~


To follow the path 
look to the master 
follow the master 
walk with the master 
see through the master 
become the master.