# JD_Spider_python是一个python抓取京东商城的爬虫，没有使用框架，主要使用了requests,BeautifulSoup,threading,time,mysql数据库存储

# Usage

## requirements

```
pip install requests
pip install MySQL-python
pip install beautifulsoup4
```

## db schema
```
CREATE DATABASE `jd_crawler` /*!40100 DEFAULT CHARACTER SET latin1 */;
CREATE TABLE `JD` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `img_url` varchar(1024) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=142 DEFAULT CHARSET=latin1;
```