# 本项目简单使用 Git


Git 使用(仅限于个人使用本项目)，以及如何 开启 GitHub Pages

## Git 操作命令

1、一般的开始操作
初始化，创建本地连接远程仓库(ssh 方式)
git init
git remote add origin git@github.com:yinSpark/awesome-yinspark.git
查看远程仓库
git remote
上传到远程仓库(本地仓库 远程仓库)
git push -u origin master

2、修改项目后上传远程仓库
git status
git add .
git commit -m "描述你的修改"
git push origin master

3、拉取远程仓库
git pull origin master

## 开启 GitHub Pages

详情请看 <https://www.cnblogs.com/lfri/p/12075338.html>
点击 Settings，往下滚动, 找到 Github Pages 选项, 将 Source 改为 master branch, 最后点击 Save 按钮。
如果为 master branch显示为灰色而无法点击，你需要先给该仓库随便添加一个文件。

完成后，你就可以这样访问你的项目
<https://yinspark.github.io/awesome-yinspark/images/Alipay.jpg>
我的 GitHub Pages 绑定了域名
<https://yinspark.github.io/> 会跳转到 <http://www.yinspark.xyz/>


























