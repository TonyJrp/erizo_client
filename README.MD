## Change into the directory  
cd erizo_client  
  
## Install dependencies  
npm install  
or   
npm i  
  
## Compile the sources  
npm run build   
  
## 备注  
一、如果执行npm install遇到错误：Error: Timeout trying to fetch resolutions from npm  
请切换至华为源后再试：npm config set registry=https://mirrors.huaweicloud.com/repository/npm/  
  
二、编译成功后,erizo.js会出现在 dist/debug/erizo目录和 dist/production/erizo 目录下  
1. debug 下的是未压缩的，建议联调阶段使用  
2. production 下是压缩后的，建议在正式环境使用  
