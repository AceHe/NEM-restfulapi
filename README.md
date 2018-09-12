# NEM-restfulapi
> Nodejs+Express+MongoDB快速搭建restful风格的api

### 使用到的模块
- **express**: nodejs框架
- **mongoose**: 用来方便的和mongodb交互
- **body-parser**: 方便我们从post请求中解析参数
- **morgan**: 把请求信息打印在控
- **jsonwebtoken**: 用来生成和确认token数据制台

### 项目目录
```
app/
 |————models/                //模块
        |————blog.js
        |————category.js
        |————user.js
 |————routes/                //路由
        |————blog.js
        |————category.js
        |————comment.js
        |————setup.js
        |————user.js
node_modules/              //依赖环境安装后生成
config.js                  //一些配置
package.json               //项目依赖环境(初始化后自动生成)
server.js                  //项目启动文件
```

### 使用说明
1. 首先克隆项目到本地;
2. 进入项目根目录,，安装所需依赖;
```
    npm install
```
3. 最后根据自己的需要修改接口模板;
4. 启动本地MondoDB，再运行本项目;
```
    node server.js
```