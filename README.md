> 此项目是使用docker-compose 部署抽奖系统的教程
1. 在linux目录下使用 git clone https://www.github.com/xyj1209/docker-compose-lottery
2. 再去[抽奖系统]( https://github.com/xyj1209/lotteryparent)下载打包项目
3. 把打包好的lottery-core-0.0.1-SNAPSHOT.jar、lottery-login-0.0.1-SNAPSHOT.jar、lottery-exposer-0.0.1-SNAPSHOT.jar分别复制到java-core、java-login、java-exposer目录下
4. 在linux下 进入docker-compose-lottery目录下输入docker-compose build | docker-compose up -d启动项目，
> 注，默认数据库是没有初始化的，需要导入[抽奖系统]( https://github.com/xyj1209/lotteryparent)的sql文件
