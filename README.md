# GraphQL-Node-Example
一个GraphQL使用nodejs来做的demo

### 安装node

npm install 


### 运行程序
node server.js

### 测试
在浏览器访问
```
http://localhost:5000/graphql
```
然后在输入框输入如下，测试搜索 director，movie的搜索

```
  {
  director(id: 3){
    name,age
  },
  movie(id:1){
    name
  }
  }
```
如果测试hello
```
{
hello
}
```
