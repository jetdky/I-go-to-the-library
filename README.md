# Python实现“我去图书馆”明日预约以及实时预约   
本项目使用fiddler手动抓包获得的数据，以及Python的request库，自动化图书馆自习室的明日预约和实时预约操作，目前实测能够在武汉体育体院完美运行。  
操作过程：  
1.提前半个小时使用fiddler抓取登录公众号时的cookies    
2.在代码中填上自己的cookies    
3.在代码中填上自己想预定的自习室和座位号   
4.运行代码    
【注意】    
0.零基础想使用本段代码，先去看Python的基本语法（推荐百度“廖雪峰python教程”），爬虫基础知识以及Python的request库和urllib库的使用（https://cuiqingcai.com/5052.html）     
1.需要手动抓取cookies
2.目前只能在预约开放前几秒，手动多次运行代码抢座
3.实测在一分钟内若多次对服务器发起GET，预约时将会出现验证码。出现验证码后代码将失效，不过这个状态会在大概10分钟后消失
4.预约成功后，代码可能会没有提示   
5.其他学校运行此代码需要更改座位标识号（座位标识号用fiddler抓取即可）     
有问题欢迎私信：  
简书：日兮夜兮酒兮  
知乎：日兮夜兮酒兮  
（随缘在线答疑解惑）  
