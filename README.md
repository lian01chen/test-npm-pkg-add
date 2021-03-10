---
theme: github
---
# test-npm-pkg-add
> 从零发布一个npm包，新手入门引导
1. 创建要发布的包内容
    - 创建一个github空白仓库
    - 在仓库根目录下执行 npm init 命令，初始化基本内容，如下：
    
        ```js
        {
          "name": "test-npm-pkg-add",
          "version": "1.0.0",
          "description": "a project test npm pkg publish",
          "main": "index.js",
          "scripts": {
            "test": "echo \"Error: no test specified\" && exit 1"
          },
          "repository": {
            "type": "git",
            "url": ""
          },
          "keywords": [
            "npm"
          ],
          "author": "***",
          "license": "ISC",
          "bugs": {
            "url": ""
          },
          "homepage": ""
        }
        ```
        
2.   在npm官网 （https://www.npmjs.com/） 创建npm账户，运行npm login 或者npm adduser,登录在npm中注册的账户
       ```js
            test-npm-pkg-add|main⚡ ⇒ npm login
            npm notice Log in on https://registry.npmjs.org/
            Username: ***
            Password:
            Email: (this IS public) 
            Logged in as *** on https://registry.npmjs.org/.
            test-npm-pkg-add|main⚡ ⇒ npm publish
            npm notice
            npm notice 📦  test-npm-pkg-add@1.0.0
            npm notice === Tarball Contents ===
            npm notice 1.1kB LICENSE
            npm notice 131B  README.md
            npm notice 386B  .vscode/launch.json
            npm notice 85B   index.js
            npm notice 590B  package.json
            npm notice 86B   test.js
            npm notice === Tarball Details ===
            npm notice name:          test-npm-pkg-add
            npm notice version:       1.0.0
            npm notice filename:      test-npm-pkg-add-1.0.0.tgz
            npm notice package size:  1.6 kB
            npm notice unpacked size: 2.3 kB
            npm notice shasum:        ef1e48bd51e7c745a23a55615676af5afab758ea
            npm notice integrity:     sha512-EaQADRP8AlSok[...]Xfzi+aTrWuM4g==
            npm notice total files:   6
            npm notice
            + test-npm-pkg-add@1.0.0
        ```
3. npm publish 发布创建的包    





 




