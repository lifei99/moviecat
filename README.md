# 豆瓣电影项目 - 项目计划

## 项目描述
- 电影网站，用于分类展示电影简要信息，亦可查询查看详细信息
- 数据来源：豆瓣电影API

## 项目定位
- SPA、PC端

## 技术栈
- AngularJS
- Git
- Gulp 自动构建工具

## 项目结构

```
.
├── app
│   ├── index.html
│   ├── app.js
│   ├── assets
│   │   ├── css
│   │   ├── img
│   │   └── js
│   ├── common
│   │   ├── directives
│   │   └── services
│   ├── home
│   │   └── module.js
│   │   └── view.html
│   └── movie_detail
│   │   └── module.js
│   │   └── view.html
│   └── movie_list
│       └── module.js
│       └── view.html
├── node_modules
├── .gitignore
├── gulpfile.js
├── package.json
└── README.md

```

## 参考资料
- [.editorconfig说明](http://www.alloyteam.com/2014/12/editor-config/)



## 目录结构的说明
- app 开发目录
- dist 是最终的项目代码目录（自动生成的）
- node_modules 依赖的包文件
- .gitignore git忽略文件
- gulpfile.js gulp的文件
- package.json npm自动生成的一个文件