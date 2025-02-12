# Novel_AI_Tag

一个 Novel Ai 的 ai 绘画魔导书

## 链接

-   [Novel_AI_Tag 原始网站链接](https://thereisnospon.github.io/NovelAiTag/)
-   [Novel_AI_Tag 原始 repo](https://github.com/Thereisnospon/NovelAiTag/)
-   [原作者 B 站链接](https://space.bilibili.com/6537379)
-   [本 repo 建设中的重构网站](https://novel-delta.vercel.app/#/)

## 原网站使用帮助

> 0. 删除本地存储可以解决大部分 bug，但是意味着分组顺序以及添加 tag 会被清空
> 1. TAG 点击左边是减少权重，中间是打开关闭 TAG ，右边是增加权重，没有打开 TAG 只增减权重不会添加 TAG。
> 2. 分组管理用法：在文本框调节分组顺序，或者新增删除分组. 比如是 [头,脚] 改成 [m1 头] 相当于 头 分类的顺序调节到最后,并且删掉了 脚分组，而且增加了一个 m1 分组 新增的分组必须以 m 开头，分组之间用英文逗号,分割

## 需求

1. [ ] 实现 tag 搜索功能
2. [ ] 迁移数据存储方式
3. [x] vue 框架迁移 (暂定使用 Vue3 + Vite + Element_Plus)

## 进度

1. [x] 基本样式
2. [x] 基本的 tag 添加操作完成
3. [ ] 负面 tag 设置
4. [ ] 独立形式显示已经选择的 tag
5. [ ] localStorage 数据存储
6. ......

## 技术栈

-   Vue3
-   Vite
-   Element_Plus
-   Unocss
-   Pinia

## 部署操作

```bash
# 安装 pnpm ( npm 和 yarn 大概也可以, 推荐使用 pnpm )
# git clone 本项目之后, cd 进入文件夹
pnpm install # 安装依赖
pnpm dev # 本地调试
pnpm build # 本地打包

```
