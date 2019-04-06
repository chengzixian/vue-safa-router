# vue-safa-router
支持滑动返回的vue-router扩展 , 为PWA应用和webview提供转场效果和手势返回的功能

## 下载安装
```
    npm install vue-safa-router -S
```

## 使用方法
### 1. main.js
```
    import Vue from 'vue'
    import router from './router'

    import VueAppRouter from './vue-app-router'
    VueAppRouter.use(router)
```

### 2. App.vue
```
    <style>
        *{margin:0;  padding:0;  box-sizing:border-box;  }
        .Page{min-height:100vh;  }
    </style>

    <template>
        <div id="app">
            <!-- <router-view/> -->
            <AppRouterView />
        </div>
    </template>
```

### 3. 其他的view页面
```
    <template>
        <Page class="home">        
            <HelloWorld msg="Welcome to Your Vue.js App"/>
        </Page>
    </template>

```

