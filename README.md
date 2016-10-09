# updateGithub

在github网页上更新fork的代码的方式：
一、
如果自己本地没有更新，那么重新fork一次也可以获取最新的代码

二、
另外还有一种更加简便聪明的方法：只需在github网站上点几个鼠标，不用本地开发环境轻松搞定：

1.打开你的github fork repo;

2.点击Pull request;

3.点击new pull request.默认情况下，github会比较original/your fork，这时应该不会有任何输出，因为你并没有做过任何变更；

4.点击switching the base（或者手动操作进行swich）.这时github将反过来比较yourfork/original，这时你将看到original相对你fork时的所有commit;

5.点击create a pull request for this comparison，这时将会反过来向你的repo提交一个pull request;

6.这时你作为你自己fork的repo的owner，你就可以点击confirm the merge，大笔一挥，所有的改动都被你一网打尽了@！

图解步骤参考 http://blog.csdn.net/huutu/article/details/51018317
