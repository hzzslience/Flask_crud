## Flask_crud

该项目使用Flask作为后端提供api，使用vue构建前端页面

### 依赖

```text
python==3.8.2
Flask==1.1.2
Flask-Cors==3.0.8
```

### 使用方法

1. 安装vue相关：

   ```shell
   $ npm install -g @vue/cli@3.7.0
   $ npm install axios@0.18.0 --save
   $ npm install bootstrap@4.3.1 --save
   $ npm install bootstrap-vue@2.0.0-rc.19 --save
   ```

2. 创建vue app：

   ```shell
   $ npm create vue
   ```

   设置：

   ```shell
   Vue CLI v3.7.0
   ? Please pick a preset: Manually select features
   ? Check the features needed for your project: Babel, Router, Linter
   ? Use history mode for router? Yes
   ? Pick a linter / formatter config: Airbnb
   ? Pick additional lint features: Lint on save
   ? Where do you prefer placing config for Babel, PostCSS, ESLint, etc.? In package.json
   ? Save this as a preset for future projects? (y/N) No
   ```

3. 启动项目：

   ```shell
   $ python app.py  # server目录下
   $ npm run serve  # client目录下
   ```

   前端页面：http://localhost:8080

   后端页面：http://localhost:5000

### 参考

 https://testdriven.io/blog/developing-a-single-page-app-with-flask-and-vuejs/ 