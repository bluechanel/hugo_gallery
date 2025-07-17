# Hugo Theme

## 开发方式

1. 克隆该项目
2. 开发运行
    - 窗口1 执行 tailwindcss的 实时编译 
    ``` shell
    npm install 

    npx @tailwindcss/cli -i input.css -o assets/css/main.css --watch
    ```
    - 窗口2 执行 hugo命令 
    `hugo server -p 2323 -c exampleContent -D`
3. 浏览器访问 http://localhost:2323

## 说明
exampleContent 为示例post内容