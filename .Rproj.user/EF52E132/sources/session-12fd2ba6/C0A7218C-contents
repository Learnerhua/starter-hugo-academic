# install.packages("blogdown") #安装blogdown包
library(blogdown) #加载blogdown包
#blogdown::install_hugo()#安装hugo软件
hugo_version()#检测hugo是否运行正常

#在hugo主页中挑选合适的主题新建站点 https://themes.gohugo.io/
blogdown::new_site(theme = 'wowchemy/starter-hugo-academic')
#新建博客 .Rmd文件
blogdown::new_post()
#启动本地服务，一遍写文档，网页渲染效果随时可见，在线重建
blogdown::serve_site()
#停止本地服务
blogdown::stop_server()
#将.Rmd文件渲染为html等站点文件，结果在public文件夹中
blogdown::build_site()
