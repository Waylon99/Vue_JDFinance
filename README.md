# Vue_JDFinance
Vue_JDFinance V1

##  组件化思维与技巧之京东金融实战

本项目使用的是Vue(2.5.9)实现的组件化课程，侧重思维与方法的训练。在模块化方面不仅涉及常规的JS还有CSS，CSS的模块化使用Sass组织代码，将模块化设计做到极致。在构建部分采用webpack（3.10.0） 和 npm scripts独立完成，不依赖任何第三方的脚手架。

###  安装

```
git clone https://github.com/cucygh/JDFinance.git
cd JDFinance
npm install
```

###  切换分支

项目里使用git分支来管理不同章节的代码，根据自己的情况选择不同的分支进行开发。

1. 如何查看所有的分支？

   ```
   git branch
   ```

   | 分支名           | 章节                                                 |
   | ---------------- | ---------------------------------------------------- |
   | master           | 默认和setup一致                                      |
   | setup            | 最基础的构建部分                                     |
   | setup-edit       | 完整的构建部分，可以在这个基础上进行开发             |
   | router           | 增加了vue-router部分，只想看单页面的同学选择这个分支 |
   | chapter-home     | 首页                                                 |
   | chapter-money    | 理财                                                 |
   | chapter-ious     | 白条                                                 |
   | chapter-raise    | 众筹                                                 |
   | chapter-download | 活动页                                               |
   | chapter-online   | 上线指导                                             |

2. ```
   git checkout 分支名
   ```