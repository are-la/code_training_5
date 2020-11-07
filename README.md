# code_training_5

### 0 前言

相信大家对Vue已经有了初步的认识。不过在实际开发中，我们并不会使用在html里引入vue.js的方法进行vue的开发，而是使用一种叫**脚手架**(CLI)的东西进行项目的构建，脚手架可以把我们的项目模块化，利于大家协作开发与后期的维护。

第五次培训就围绕着Vue的脚手架Vue-CLI展开，带领大家正式接触工程化的Vue开发。

### 1 准备

大家在进行这部分工作时，如果在某处报错或者出现异常，请直接复制报错文字**到搜索引擎中查找原因**，因为工程配置中出的错五花八门，学长学姐们也未必遇到过，所以请优先请教互联网。当一切解决方法都无效时，再来寻求帮助。

1. ##### 下载安装Node.js

   - Vue-CLI需要Node.js的支持，请大家下载并安装Node.js，安装过程中可选项全部默认即可

   - 安装完成后，启动命令行，输入 `node -v` 即可查看node版本

2. ##### 切换npm下载源

   - npm是Node.js的包管理工具，我们使用它管理我们工程中用到的包*（package，模块）*，npm默认的下载源在国外，速度很慢，对于国内用户不友好，所以我们可以通过切换下载源为国内镜像源的方式提升速度，这里我们选择淘宝源

   - 启动命令行，输入 `npm config set registry https://registry.npm.taobao.org` 即可完成切换

   - 切换后可以通过输入 `npm config get registry` 来查看目前的下载源，如果显示为 `https://registry.npm.taobao.org` 则切换成功

3. ##### 安装Vue-CLI

   - 启动命令行，输入`npm install @vue/cli -g`，即可进行Vue-CLI的安装，期间等待其自动完成安装即可

   - 安装完成后会提示 `+ @vue/cli@4.5.8` 字眼

4. ##### 创建第一个Vue-CLI项目

   - 启动命令行，输入 `vue create xxx` 其中xxx是你的项目名称（注意：项目名称**不能包含大写字母**），这个自己取一个名字就好

   - 项目创建过程中Vue-CLI会询问用户一些配置问题，使用**小键盘方向键切换，空格选取，回车确认**
     - 首先会让用户选择preset，`Please pick a preset:` 这里**选择第三个**， `Manually select features`
     - 随后进入选取features，`Check the features needed for your project:` 这里**仅选取Babel**
     - 随后询问如何存放配置文件， `Where do you prefer placing config for Babel, ESLint, etc.?` 这里**选择第一个**， `In dedicated config files`
     - 随后询问是否保存为预设，这里**选否**即可（输入N）

5. ##### 启动Vue-CLI项目

   - 进入到项目文件夹，启动命令行，输入 `npm run serve` 即可启动，当屏幕中显示绿色的DONE时即表示完成
   - 在浏览器中输入带有localhost的网址即可访问项目页面

### 2 需要提前掌握的知识

1. Vue.js语法及概念（官网教程中**基础**部分要全看完）
2. JavaScript语法、ES6语法
   - 对象
   - this指针
   - import / export
   - 箭头函数

### 3 培训内容

培训内容为到时候上课的实际内容，希望大家可以提前预习一下，至少了解要讲什么

- Vue-CLI项目的架构
- vue单文件组件的写法
- 使用npm配置工程中所需要的模块
- Vue-router的概念、配置以及使用
  - 引入Vue-router
  - history模式与hash模式
  - routes数组的写法（动态路由、嵌套路由、命名路由、重定向、路由传参）
  - js中进行路由切换
- Webpack、Babel、Vuex、SCSS的基础概念

### 4 资源导航

1. Node.js中文官网

   http://nodejs.cn/

2. 百度

   https://www.baidu.com/

3. Vue-CLI官网

   https://cli.vuejs.org/zh/

4. Vue.js官方教程

   https://cn.vuejs.org/v2/guide/

5. Vue-router官网

   https://router.vuejs.org/zh/

### 5 写在最后

- Vue-CLI是程序部进行网站开发的首选，因此这节课非常重要（直接与开发接轨）

- 请大家做好作业的同时做好复习的工作，这节课会大量地用到前面所讲的内容，所以一定要将之前的知识理解透彻，有问题请及时在群里提问
- 大家加油！！冲！！

