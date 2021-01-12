<!--

 * @Author: Letmeouted

 * @Email: 1002726239@qq.com

 * @Date: 2021-01-12 13:56:35

 * @LastEditTime: 2021-01-12 14:37:51

 * @FilePath: \vite\README.md
    -->
## Vite

一个基于浏览器原生 ES imports 的开发服务器。利用浏览器去解析 imports，在服务器端按需编译返回，完全跳过了打包这个概念，服务器随起随用。同时不仅有 Vue 文件支持，还搞定了热更新，而且热更新的速度不会随着模块增多而变慢。针对生产环境则可以把同一份代码用 rollup 打。虽然现在还比较粗糙，但这个方向我觉得是有潜力的，做得好可以彻底解决改一行代码等半天热更新的问题。

### 快速上手

1. Vite 官方目前提供了一个比较简单的脚手架: create-vite-app ,用户可以通过该脚手架快速构建一个使用Vite构建的Vue.js 应用

   ```
   yarn add -g create-vite-app
   yarn create vite-app <project-name>
   cd <project-name>
   yarn
   ```

2. 执行完上述命令，便可以初始化一个 Vite 项目(模板为vue.3x),项目目录如下图所示。

   ![image](https://cdn.jsdelivr.net/gh/Letmeouted/PicGO/Pic/Snipaste_2021-01-12_14-11-30.png)

3. 最后再执行下行命令便可以访问 Vite 项目网页内容。

   ```
   yarn dev
   ```

   


