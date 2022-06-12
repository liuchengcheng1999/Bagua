# 部署项目
需要运行下列代码，才能请求JavaScript和CSS：
```javaScript
yarn global add parcel@1.9.7
parcel build src/index.html --no-minify --public-url .
```