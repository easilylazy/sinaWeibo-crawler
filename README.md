# sinaWeibo crawler
本测试项目为爬虫爬取新浪微博并分析数据的实现代码  
使用平台为jupyter notebook   
编程语言为python  


每个文件夹中的文件配合使用，实现功能如下：  
## repostWeibo
博主转发影响力分析  
acquaireData：从微博爬取需要的数据——某博主所有转发的微博相关数据  
analyseData：分析转发量等数值型数据  
analyseTxt：分析转发博文文本，绘制词云图  
总结文章：https://blog.csdn.net/cascara/article/details/104090441
## singleWeibo
博文传播图绘制  
acquaireRepost：获取需要的数据——某条微博的全部转发情况  
analyseLinks：生成传播图像  
总结文章：https://blog.csdn.net/cascara/article/details/104135868
## fansMap
绘制粉丝分布热力图  
acquaireData：从微博爬取需要的数据——某博主的所有粉丝（微博限流，实际只能爬取10页）  
analyseSite：生成地区图像  
总结文章：https://blog.csdn.net/cascara/article/details/104172602
