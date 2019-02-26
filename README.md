# Pandas 数据分析实战练习

当今最热的职业是数据科学，数据科学领域应用最广泛的编程语言是python，python这么火的原因就是其有一个功能强大的数据科学库：pandas。

厌倦了大量的教程，但始终没有简单的方法来练习pandas。我创建了这样一个专注于实战练习来学会pandas的仓库教程。学习就是要做，因此，除非你亲手练习，否则你永远都无法学会。

仓库里将有三种不同类型的文件：

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. 练习说明

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. 无代码的解决方案

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. 带代码和注释的解决方案
 
我的建议是你在教程或视频中学习一个主题然后做练习。
再学习一个主题再做练习。 
如果您的答案有误，请多思考而不是直接使用代码解决方案。


建议和合作非常受欢迎。欢迎打开issue或提PR :)

## Lessons
|时间|主题|学习内容|对应数据集|练习数据集|
|:-------------:|:-------------:|:-----------:|:-------------:|:-------------:|
|D1|[开始了解你的数据](#getting-and-knowing)      | 探索Chipotle快餐数据|chipotle.tsv|Occupation、World Food Facts
|D2|[数据过滤与排序](#getting-and-knowing) | 探索2012欧洲杯数据|Euro2012_stats.csv|Chipotle、Fictional Army
|D3|[数据分组](#getting-and-knowing)      | 探索酒类消费数据|drinks.csv|Occupation、Regiment
|D4|[Apply函数](#getting-and-knowing)      | 探索1960 - 2014 美国犯罪数据|US_Crime_Rates_1960_2014.csv|students_alcohol_consumption
|D5|[数据合并](#getting-and-knowing)      | 探索虚拟姓名数据|练习中手动内置的数据|auto_mp、housing market
|D6|[数据统计](#getting-and-knowing)      | 探索风速数据|wind.data|us_baby_names
|D7|[数据可视化](#getting-and-knowing)      | 探索泰坦尼克灾难数据|train.csv|chipotle、online_retail、scores、tips
|D8|[创建Series和DataFrames](#getting-and-knowing)      | 探索Pokemon数据|练习中手动内置的数据|pokemon
|D9|[时间序列](#getting-and-knowing)      | 探索Apple公司股价数据|Apple_stock.csv|financial_data、investor
|D10|[数据删除](#getting-and-knowing)      | 探索Iris纸鸢花数据|iris.csv|Wine

## 这套教程适合谁

这套教程包含从初级到进阶的内容，适合初学者和希望进阶建立知识体系的数据科学从业者、竞赛爱好者。请关注公众号AI圈终身学习(ID:AIHomie)组队学习活动。

--- 

# Pandas Exercises

Fed up with a ton of tutorials but no easy way to find exercises I decided to create a repo just with exercises to practice pandas.
Don't get me wrong, tutorials are great resources, but to learn is to do. So unless you practice you won't learn.

There will be three different types of files:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Exercise instructions  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Solutions without code  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. Solutions with code and comments

My suggestion is that you learn a topic in a tutorial or video and then do exercises.
Learn one more topic and do exercises. If you got the answer wrong, don't go directly to the solution with code.

Suggestions and collaborations are more than welcome. Please open an issue or make a PR. :)

## Lessons

|				                                  |				                                   |                   |
|:-----------------------------------------------:|:----------------------------------------------:|:-----------------:|
|[Getting and knowing](#getting-and-knowing)      | [Merge](#merge)                                |[Time Series](#time-series)|
|[Filtering and Sorting](#filtering-and-sorting)  | [Stats](#stats)                                |[Deleting](#deleting)       |
|[Grouping](#grouping)							  | [Visualization](#visualization)                |Indexing           |
|[Apply](#apply)							      | [Creating Series and DataFrames](#creating-series-and-dataframes) 		            |Exporting|

### [Getting and knowing](https://github.com/guipsamora/pandas_exercises/tree/master/01_Getting_%26_Knowing_Your_Data)  
[Chipotle](https://github.com/guipsamora/pandas_exercises/tree/master/01_Getting_%26_Knowing_Your_Data/Chipotle)  
[Occupation](https://github.com/guipsamora/pandas_exercises/tree/master/01_Getting_%26_Knowing_Your_Data/Occupation)  
[World Food Facts](https://github.com/guipsamora/pandas_exercises/tree/master/01_Getting_%26_Knowing_Your_Data/World%20Food%20Facts)

### [Filtering and Sorting](https://github.com/guipsamora/pandas_exercises/tree/master/02_Filtering_%26_Sorting)
[Chipotle](https://github.com/guipsamora/pandas_exercises/tree/master/02_Filtering_%26_Sorting/Chipotle)  
[Euro12](https://github.com/guipsamora/pandas_exercises/tree/master/02_Filtering_%26_Sorting/Euro12)  
[Fictional Army](https://github.com/guipsamora/pandas_exercises/tree/master/02_Filtering_%26_Sorting/Fictional%20Army)

### [Grouping](https://github.com/guipsamora/pandas_exercises/tree/master/03_Grouping)
[Alcohol Consumption](https://github.com/guipsamora/pandas_exercises/tree/master/03_Grouping/Alcohol_Consumption)  
[Occupation](https://github.com/guipsamora/pandas_exercises/tree/master/03_Grouping/Occupation)  
[Regiment](https://github.com/guipsamora/pandas_exercises/tree/master/03_Grouping/Regiment)

### [Apply](https://github.com/guipsamora/pandas_exercises/tree/master/04_Apply)
[Students Alcohol Consumption](https://github.com/guipsamora/pandas_exercises/tree/master/04_Apply/Students_Alcohol_Consumption)  
[US_Crime_Rates](https://github.com/guipsamora/pandas_exercises/tree/master/04_Apply/US_Crime_Rates)     

### [Merge](https://github.com/guipsamora/pandas_exercises/tree/master/05_Merge)
[Auto_MPG](https://github.com/guipsamora/pandas_exercises/tree/master/05_Merge/Auto_MPG)  
[Fictitious Names](https://github.com/guipsamora/pandas_exercises/tree/master/05_Merge/Fictitous%20Names)  
[House Market](https://github.com/guipsamora/pandas_exercises/tree/master/05_Merge/Housing%20Market)  

### [Stats](https://github.com/guipsamora/pandas_exercises/tree/master/06_Stats)
[US_Baby_Names](https://github.com/guipsamora/pandas_exercises/tree/master/06_Stats/US_Baby_Names)  
[Wind_Stats](https://github.com/guipsamora/pandas_exercises/tree/master/06_Stats/Wind_Stats)

### [Visualization](https://github.com/guipsamora/pandas_exercises/tree/master/07_Visualization)
[Chipotle](https://github.com/guipsamora/pandas_exercises/tree/master/07_Visualization/Chipotle)  
[Titanic Disaster](https://github.com/guipsamora/pandas_exercises/tree/master/07_Visualization/Titanic_Desaster)  
[Scores](https://github.com/guipsamora/pandas_exercises/tree/master/07_Visualization/Scores)  
[Online Retail](https://github.com/guipsamora/pandas_exercises/tree/master/07_Visualization/Online_Retail)  
[Tips](https://github.com/guipsamora/pandas_exercises/tree/master/07_Visualization/Tips)  

### [Creating Series and DataFrames](https://github.com/guipsamora/pandas_exercises/tree/master/08_Creating_Series_and_DataFrames)  
[Pokemon](https://github.com/guipsamora/pandas_exercises/tree/master/08_Creating_Series_and_DataFrames/Pokemon)  

### [Time Series](https://github.com/guipsamora/pandas_exercises/tree/master/09_Time_Series)  
[Apple_Stock](https://github.com/guipsamora/pandas_exercises/tree/master/09_Time_Series/Apple_Stock)  
[Getting_Financial_Data](https://github.com/guipsamora/pandas_exercises/tree/master/09_Time_Series/Getting_Financial_Data)  
[Investor_Flow_of_Funds_US](https://github.com/guipsamora/pandas_exercises/tree/master/09_Time_Series/Getting_Financial_Data)  

### [Deleting](https://github.com/guipsamora/pandas_exercises/tree/master/10_Deleting)  
[Iris](https://github.com/guipsamora/pandas_exercises/tree/master/10_Deleting/Iris)  
[Wine](https://github.com/guipsamora/pandas_exercises/tree/master/10_Deleting/Wine)  



