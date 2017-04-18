什么是node.js?

* Node.js 是一个构建于 Chrome V8 引擎之上的 JavaScript 运行时环境
	•	Node.js 使用 事件驱动，非阻塞 I/O 模型，这使得它非常轻量，高效。
	•	Node.js 包管理生态，npm，是世界上最大的开源库生态系统

* 在 V8 引擎基础上套了一层壳，通过编写 JS 代码可以实现后端能做的事情
	•	特点：事件驱动、非阻塞的I/O等特性
	•	优势：轻量、高效
	•	官网：https://nodejs.org/en/
node的安装

3m安装法
* nvm （Node Version Manager）
• 解决多版本共存、切换问题



* curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.0/install.sh | bash
	•	下载nvm, 并将路径配置到 ~/.bashrc 中
	•	注: 如果终端是zsh，则需要配置到~/.zshrc 中(可通过 echo $0 查询)
*                nvm  --version  查看当前版本
	•	nvm ls 查看当前已安装 node 的版本
	•	nvm ls-remote 查看远程 node 的版本
	•	nvm install 4.4.5 安装某版本 node
	•	nvm use 4.4.5 使用某版本 node 
	•	nvm alias default 4.4.5 把某版本 node 设为默认值
*   
• npm  (Node Package Manager) 
• 解决 Node.js 模块安装问题
* 安装完 Node 后自带 npm
	•	npm -v 查询当前npm版本
	•	npm install npm -g 通过 npm 更新 npm
	•	npm install 模块名 
	•	常用 npm 模块一览



• nrm    (NPM Registry Manager)
• 解决 npm 镜像访问慢，提供测试，切换
* npm install -g nrm
	•	nrm test 
	•	nrm ls
	•	nrm use taobao

