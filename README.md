# JDF
#### C++项目目录组织结构

参考：https://cloud.tencent.com/developer/article/1606950

```
├── 3rdparty          三方库
├── benchmark         基准测试代码目录
├── doc               文档
├── dist              打包此目录即可完成项目分发
├── build             各种编译的临时文件和最终的目标文件皆存于此，分为debug/和release/子目录 
├── platforms         平台适配相关    
├── modules			  功能模块相关
├── scripts           相关脚本存放目录，包括持续集成和部署相关
├── shared			  用于存放应用程序的一些共享文件              
├── etc               配置文件目录
├── examples          示例代码目录
├── res               资源目录，比如程序的icon等
├── src               源码目录
├── tests             测试代码目录
├── tools             工具目录，比如存放一些辅助脚本
├── .clang-format     使用clang-format对代码格式化的配置文件
├── .clang-tidy       使用clang-tidy对代码静态检查的配置文件
├── .gitignore        git忽略项配置文件
├── .gitmessage       git提交模板文件
├── CHANGELOG.md      更新日志
├── CMakeLists.txt    cmake项目工程文件
├── LICENSE           license文件
```



#### 持续集成和发布参考

https://zhulj.net/Basic-tutorial-build-a-github-cpp-project.zh.html
