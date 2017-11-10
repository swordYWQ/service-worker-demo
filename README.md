# service-worker-demo

- 这是一个service-worker的简单demo

- [DEMO地址](https://swordywq.github.io/service-worker-demo/)
- F12 开启Chrome 浏览器调试,切换到NetWork面板,修改offline的状态可模拟离线访问.
发现一个bug，暂时不知道原因，使用chrome插件offline模拟离线时，仍然可以访问到，只有真正把网络断开serviceworker才会跳转到离线缓存的页面
