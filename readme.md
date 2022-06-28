# github 提交  
- 把我们的项目交给github托管 ， 可以直接访问    
    1. 这项服务的名字叫 github  pages   
    2. 免费的二级域名   
        纯静态页面   

- 相对地址有问题  
    工程化vite配置 将index.html 与 assets 的关系配置成 ./   
    在vite.config.js里 添加配置    
    base:'./'
    github 中可能有好多个项目   
    / 根路径   

    git init      
    git add .  
    git commit -m '' 
    git remote add origin 地址  
    git push origin master