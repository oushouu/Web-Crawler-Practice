# Web-Crawler-Practice
this is my first practice of web crawler: getting top 250  movies' information from douban. 这个其实是python小课的一个练习题的延展，原题是让我获取电影的名字然后结合一个事先自制的下片的爬虫脚本返回250个电影的下载地址就可以了（虽然有一部分电影是找不到下载链接的）。为了完整的练习爬虫技能，我把每部电影的所有基本情报都抓取下来并整理成最干净的dataframe格式导出到了excel文档里。
download文件里定义了一个下载电影的函数；
main里调用了download里的那个函数用于打印下载地址，但main的主要作用还是讲电影数据清洗并整理成dataframe，然后导出到excel。