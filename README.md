# yyl-npm-practice

> A Vue.js project

## Build Setup

``` bash
# How to use
//切换NPM源到私有仓库
npm config set registry http://xx.xxx.xxx.../
//切换NPM源到淘宝镜像源
npm config set registry http://registry.npm.taobao.org

npm i zwzh-video
npm i axios
npm i vue-axios

//In main.js
import Main from 'zwzh-video'
import axios from 'axios'
import VueAxios from 'vue-axios'
Vue.use(Main)
Vue.use(VueAxios,axios)

//In html
<zwzh-video :videoUrl='videoUrl'></zwzh-video>

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).
