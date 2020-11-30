# WEB 开发基础知识

## git 基础
- git clone
- git fetch
- git pull
- git add
- git commit
- git push

参考: [git 工作流图示](https://www.git-tower.com/blog/workflow-of-git/)

### Git 基础扩展
- git branch
- git merge
- git rebase
- Pull Requests

## React 基础
- create-react-app with TypeScript <br /> 
参考：https://create-react-app.dev/docs/adding-typescript/#installation
- 启动开发环境

    ```
    $ yarn start 
    # or
    $ npm run start
    ```

- 修改 App.jsx 输出 **Hello World**。
- 使用 props 从 index.jsx 传入 **Hello World**。
- 使用 props 从 index.jsx 传入<*名字*>，只跟 *Alice* 或者 *Bob* 打招呼。如：**Hello Alice**。
- 使用 props 输入一个自然数n，App.jsx 输出从 1 到这个自然数累计之和(1+2+3+...+n)
- 从文本框(input)接受这个自然数n，App.jsx 输出从 1 到这个自然数的累计之和。
- 从文本框(input)接受这个自然数n，App.jsx 提供两个按钮，分别输出
    - 从 1 到这个自然数的累计之和；
    - 从 1 到这个自然数的累计乘积。
- 写一个“猜数字”的小游戏。随机生成一个自然数；玩家输入猜想的数字；页面回应“大了点”或者“小了点”；直到玩家猜出数字。
    - 玩家每次猜的数字需要打印在页面上。同一个数字不分开打印。
    - 玩家猜的次数需要打印在页面上。
- 输出接下来的20个闰年的年份。
