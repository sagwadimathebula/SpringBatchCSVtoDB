# SpringBatchCSVtoDB

springBatch 
First Springbatch application with Reader, Writer, Processr and JobListener
use CSV File to populate Database
Junit test using Junit4

use msql DB
create database mydb
use mydb
CREATE TABLE `product` (
  `id` int NOT NULL AUTO_INCREMENT,
  `name` varchar(30) DEFAULT NULL,
  `description` varchar(50) DEFAULT NULL,
  `price` int DEFAULT NULL,
  PRIMARY KEY (`id`)
)
