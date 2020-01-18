
|插件|作用|
|---|---|
|babel-plugin-import|antDesign按需加载|
|Redux|专门管理状态的库|
|react-redux|react和redux连接的桥梁|
|react-router-dom|页面跳转路由|
|redux-thunk|redux 异步处理工具|
|cookie-parser| 异步处理工具|
|transform-decorators-legacy | Redux支持装饰者模式|
| @babel/plugin-proposal-decorators | 配合legacy使用|
|axios | 网络请求|


###Redux
- Redux专注于状态管理,和React解耦
- 单一状态,单向数据流
- 核心概念：store,state,action,reducer

React-redux
- Provider组件在应用的最外层,传入store即可,只用一次
- Connect 负责从外部获取组件需要的参数


