
1、把当前文件夹（readme_sass安装问题.txt 所在文件夹）的所有文件放在自己配置的服务器上，如：d:/phpStudy/www

2、改变sass的服务器来源
  在命令行执行如下两行命令：
  gem sources --remove https://rubygems.org/

  gem sources -a http://localhost


3、安装sass
   gem install sass