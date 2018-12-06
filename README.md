# PHP-Mysql

> 由于订单数据分析时，select金额使用了format导致金额过大会出现逗号分割，更改为round


* demo1
* demo2

> da
>>da
>

```sql
--mysql--
select round(10000.666, 2); echo 10000.67; select format(10000.666, 2); echo 10,000.67;
```
	