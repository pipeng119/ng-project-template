1. `npm i husky -D`
2. 在`package.json`中添加`script`命令:
   ```json
    ...

    "scripts": {
      "ng": "ng",
      "start": "ng serve --port 4230",
      "build": "ng build",
      "watch": "ng build --watch --configuration development",
      "test": "ng test",
      "prepare": "husky install"
    }
   ```
3. 执行命令: `npm run prepare`
4. 
