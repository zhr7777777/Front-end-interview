### 酷家乐【杭州】
面试流程：
 1. 自我介绍
 2. 项目经历
 3. 技术提升和学习方法
 4. 两道简单算法题
 5. 公司业务了解
 6. 公司技术栈

面试题相关：
  1. 请简单说下什么是闭包？列举下闭包具体使用的场景～
  ```
  这就是闭包
  ```
  2. 请简单描述下作用域， 作用域链，闭包，垃圾回收，和闭包有什么联系？
  ```
  这就是闭包和xxx之间的联系
  ```
  3. 项目中做过的性能优化有哪些？
  ```
  性能优化的方式：资源压缩，缓存策略，减少请求，懒加载，ssr
  ```
  4. 埋点监控的指标有哪些，怎么获取和上报，埋点sdk的基本架构？
  ```
  监控指标：白屏时间，首屏时间，可操作时间
  指标计算：根据performance中的timing参数进行计算获取上报
  sdk设计：监听页面加载完成上报指标，设计缓存队列，定期轮训上报
  ```
  5. 请问有没有处理过运行时的性能优化？
  ```
  举个例子：页面滚动卡顿问题
  ```
  55. 事件监听中涉及到的闭包在哪里，请解释下？
  ```
   window.addEveneListener('load', callback);
 ```
  6. 发布第三方npm包的开发及发布流程，具体什么时候发布大，中，小版本？
  ```
  发布npm包说明
  ```
  7. 算法题：给出一个二叉树数据，中序遍历打印出所有的数字？
  ```
  中序遍历二叉树
  ```
  8. 算法题：怎么遍历获得链表的中间元素？
  ```
  快慢指针
  ```
  ### LeetCode【上海】
  【算法题】：请打印出1000个5位随机数的验证码列表，要求1000个不能重复，且每个验证码相邻的两个数字不相同。
  ```
  代码块
  ```
### 涂鸦智能【杭州】
  1. 项目经历和自我介绍
  ```
  图像围栏/AI中台
  ```
  2. 基础组件是否会写单元测试
  3. 防抖和节流
  4. 项目使用的react使用版本，16x版本的变化详细说明
  ```
  生命周期的变化
  ```
  5. 16.8版本上的`react`版本上了`react hooks`, 简单说明下`react hooks`的特性
  ```
  react hooks
  ```
  6. `react hooks`类比于之前的生命周期
  ```
  react hooks
  ```
  7. `useEffect`和`componentDidMount`是否效果一样？
  ```
  useEffect:
  componentDidMount: 
  ```
  8. `useEffect`和`useLayoutEffect`的用法和区别？
  ```
  useEffect: 
  useLayoutEffect:
  ```
  9. `react hooks`使用规则，注意事项，踩过的坑？
  ```
  hooks的使用规则
  嵌套函数中使用hooks可以吗？
  ```
  10. react源码看过哪些？setState的理解？setState是同步还是异步的？
  ```
  setState:
  ```
  11. `React fiber`是否了解，简单介绍下？
  ```
  ```
  12. react的虚拟dom是什么，简单介绍下用法？更新的diff算法？
  ```
  ```
  13. 状态管理redux, 工作流程是怎样的？
  ```
  ````
  14. `dispatch`一个`action`的时候，怎么找到对应的reudcer的？
  ```
  ```
  15. 解决跨域的几种方案？
  ```
  ```
  16. cors有了解过吗？具体说下跨域资源怎么共享的
  ```
  ```
  17. http的缓存策略, 简单介绍下
  ```
  ```
  18. 简单介绍下闭包，以及应用场景？
  ```
  ```
  19. 简单描述下防抖和节流
  ```
  ```
  20. promise.all和promise.race怎么用的，有什么区别？