Dropplets [译]
=========

Dropplets is a minimalist **Markdown** blogging platform focused on delivering just what you need in a blogging solution, but absolutely nothing you don't. When it comes to basic blogging, all you really want to do is write & publish which is where Dropplets excels. It's databaseless, so it installs on any server in just about 30 seconds. 

Dropplets 是一个极简的**Markdown**博客平台致力提供一个只发布你想要的内容的博客解决方案,绝对没有你不需要的发布的内容. 当它成为一个基础博客,你所需要做的只有写和发布,这就是Dropplets的优势. 它不需要数据库,所以在任何一台服务器上安装只要大概30秒.

## What's Markdown?
Markdown is a text formatting syntax inspired on plain text email. It is extremely simple, memorizable and visually lightweight on artifacts so as not to hinder reading.

Markdown是一个文本格式语法受到纯文本邮件的启发. 它非常的简单,容易记和而且对人工阅读不造成障碍.

> The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it's been marked up with tags or formatting instructions.

Markdown格式文件应该被不被改变的上传,就像朴实的文本,不需要看上去像被用标签或者说明来标记.

## Getting Started
- [Installation](#installation)
- [Writing Posts](#writing-posts)
- [Publishing Posts](#publishing-posts)
- [Editing Posts](#editing-posts)
- [Changing Settings](#changing-settings)
- [Changing Templates](#changing-templates)
- [Updating Dropplets](#updating-dropplets)
- [License](#license)

## Installation
Dropplets is compatible with most server configurations and can be typically installed in under a minute using the few step-by-step instructions below:

Dropplets是兼容大多数的服务器设置以及安装小于一分钟作为特色只需要按照以下说明一步步操作:

1. Download the latest **release** and then extract the downloaded zip file.

1. 下载最新的发行版并且解压这个被下载的文件.

2. Upload the entire contents of the extracted zip file to your web server wherever you want Dropplets to be installed. 

2. 上传解压出的所有文件到那个你想要安装Dropplets的web服务器.

3. Pull up your site in any modern web browser (e.g. if you uploaded Dropplets to **yoursite.com**, load **yoursite.com** in your browser to finish the installation), then create and confirm your password.

3. 打开你的web浏览器来查看你的网站(比如:加入你上传了Dropplets到**yoursite.com**,读取**yoursite.com**从你的浏览器中去完成这个安装),然后创建和确认你的密码.


## Writing Posts
With Dropplets, you write your posts offline (using the text or Markdown editor of your choice) in Markdown format. Here's a handy [syntax guide](https://github.com/circa75/dropplets/wiki/Markdown-Syntax-Guide) if you need a little help with your Markdown skills. All posts for Dropplets **MUST** be composed using the following format:

通过Dropplets,你线下写你的Markdown格式的文章(使用文本或者Markdown编辑器). 这是一个就近的[语法向导](https://github.com/circa75/dropplets/wiki/Markdown-Syntax-Guide),如果你需要一点帮助你的markdown技能.所有的文章对Dropplets必须用以下格式组成:

    # Your Post Title 你的文章标题
    - Post Author Name (e.g. "Dropplets") 作者名字
    - Post Author Twitter Handle (e.g. "dropplets") 推特地址
    - Publish Date in YYYY/MM/DD Format (e.g. "2013/04/28") 发布时间
    - Post Category (e.g. "Random Thoughts") 文章分类
    - Post Status (e.g. "published" or "draft") 文章状态

    Your post text starts here. 

    你的文章文本从这里开始.
    
All posts must also be saved with the **.md** file extension. For instance, if your post title is **My First Blog Post**, your post file should look like this:

所有的文章都必须用**.md**的文件拓展保存. 一些实例,如果你的文件题目是**My First Blog Post**,你发布的文件需要像这样:

    my-first-blog-post.md

Some templates include the ability to add a post image or thumbnail along with your post in which should match your post file name like this:

有些模板包括了独立于文章进行增加文章图片或者缩略图的功能,那样的情况你的文件名需要像这样:

    my-first-blog-post.jpg

Post file names are used to structure post permalinks on your blog. So, a post file saved as **my-first-blog-post.md** will result in **yoursite.com/my-first-blog-post** as the post permalink.

发布的文件名是用来组成你博客的固定链接的.所以一个发布文件被保存为**my-first-blog-post.md**将会作为**yoursite.com/my-first-blog-post**的固定连接.

## Publishing Posts
After you've finished writing your post offline, you can then publish your post using the Dropplets toolbar:

等你离线写完了你的文章,你可以发布你的文章用Dropplets工具栏:

1. Login to your Dropplets installation using the password you created during the installation and setup process.

1. 登陆你的Dropplets用你创建的密码进行安装.

2. Click the Dropplet in your toolbar to select, upload and publish your post.

2. 点击Dropplet在你的工具栏去选择,上传和发布你的文章.


## Editing Posts
Re-upload your edited post file using the steps above. Doing this will automatically overwrite the existing post and publish your new edits. To delete a post, change the **Post Status** at the top of your post file to **draft**.

重新上传你修改过的文件和前面的步骤一样. 这样操作会自动覆盖原来的文件并且发布你新的修改. 要删除一个文件, 修改**Post Status**在你文件的顶部成为**draft**.

## Changing Settings
To change your blog settings, click the gear icon in the Dropplets toolbar. This will load the settings panel where you will be able to change all of your blog settings including your password.

修改你博客的设置,点击Dropplets工具栏的齿轮图标. 它会读取设置面板然后你可以修改所有的博客设置包括你的密码.

## Changing Templates
To change your blog template, click the star icon in the Dropplets toolbar. This will load the templates panel where you will be able to browse and change your blog template as well as purchase new premium templates.

修改你的博客模板,点击Dropplets工具栏的星星图标. 它会读取模板面板然后你可以查看和修改你的博客模板和买一个新的高级模板一样.

## Updating Dropplets
Eventually, we will be implementing auto-updates for the Dropplets platform, but until then, just replace everything but your **posts** directory and **config.php** when we release a new version of Dropplets.

最终,我们将会实现自动更新Dropplets平台.不过在此之前当我们用新版本发布时候你需要覆盖所有文件除了post文件夹和config.php.

## License
Copyright (c) 2013 Circa75 Media, LLC

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
