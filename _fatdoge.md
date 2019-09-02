##2019/8/29
- [ ] 调研Jenkins/BlueOcean
- [ ] 调研[代码审核](https://www.jianshu.com/p/bbfda1e21f50)
- 备用：[React拖拽作业组件](https://zhuanlan.zhihu.com/p/30104151)
- 备用：[使用Jenkins持续集成前端项目并自动化部署到Nginx服务器](https://cloud.tencent.com/developer/article/1356668)
1. 配置超长时间的本地缓存 —— 节省带宽，提高性能
2. 采用内容摘要作为缓存更新依据 —— 精确的缓存控制
3. 静态资源CDN部署 —— 优化网络请求
4. 资源发布路径实现非覆盖式发布 —— 平滑升级
## 2019/8/28
- 私有npm解决方案 https://github.com/verdaccio/verdaccio
- 代码部署平台 https://github.com/meolu/walle-web
```
graph LR
a(开发服务器)--apply-->c(NPM服务器)
c(NPM服务器)--apply-->b((私有npm源))
b--uplink-->d((公共npm源))
d--proxy-->c
b--download-->c
c--download-->a
```
## 2019/8/1
- [写给前端工程师的Docker入门](https://savokiss.com/tech/docker-for-frontend-developers.html)
- [JS函数式编程指南](https://llh911001.gitbooks.io/mostly-adequate-guide-chinese/content/)
- [在你身边你左右 --函数式编程别烦恼](https://juejin.im/post/5b26a8b66fb9a00e925bcf30)



