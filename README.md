#xyz-cloud

本库是Pelican的一个示例站点，查看效果请移步https://xyz-cloud.github.io。

该站点使用了Pelican自带的notmyidea主题，并对主题/templates目录下的部分文件进行了修改，将在网页上显示的英文替换为了中文。

通过以下参数，指定生成页面的目录：
ARTICLE_URL ='posts'
ARTICLE_SAVE_AS = 'posts/{date:%Y}/{slug}.html'