# yarn_demo
Facebook推出的Yarn：为速度而打造的开源JavaScript包管理器，或取代npm    

依次运行下列命令：  
npm install -g yarn    
yarn init       
yarn add gulp    
yarn add browser-sync --dev    

yarn 与 npm 功能对应表格：

命令 | yarn | npm
--- | --- | ---
初始化 | yarn init | npm init
安装项目所有包(注意) | yarn | npm install
添加 dependencies | yarn add [package-name]  | npm install [package-name] --save
添加 devDependencies | yarn add [package-name] --dev | npm install [package-name] --save-dev
删除 dependencies | yarn remove [package-name]  | npm uninstall [package-name] --save
删除 devDependencies | yarn remove [package-name] --dev | npm uninstall [package-name] --save-dev
全局安装 | yarn global add [package-name] | npm install -g [package-name]
运行 | yarn run | npm run
  
