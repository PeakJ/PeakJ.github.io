# blog

#### 项目介绍
用于github.io的仓库

# 基于HEXO的博客发布流程
##  安装
1. 安装node 和 git,具体步骤略过
2. 安装hexo的命令行工具
`npm install -g hexo-cli`
3. 安装 Hexo 完成后，请执行下列命令，Hexo 将会在指定文件夹中新建所需要的文件。

```
hexo init <folder>
cd <folder>
npm install
``` 
新建完成后，指定文件夹的目录如下：

```.
├── _config.yml
├── package.json
├── scaffolds
├── source
|   ├── _drafts
|   └── _posts
└── themes
```
4. 新建文章
`hexo new "My New Post"`
5. 生成静态文章
`hexo generate`
6. 启动服务器,本地查看。默认情况下，
`hexo server`
访问网址为： `http://localhost:4000/`。
7. 确认无误后发布博客。（需要先配置_config.yml中的deploy选项）
`hexo deploy`
8. 如果不生效，先执行 `hexo clean`,然后重复5，6，7步

其他操作查看 [hexo官网](https://hexo.io/zh-cn/index.html)