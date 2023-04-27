# REDROCK移动部门Android方向 2023年中期考核

## 聚餐

> 移动历届考核的传统，没有正当理由不许请假

- 时间： 2023年5月14日 18：00

## 面试

> 面试就是简单了解一下

- 时间：2023年5月7日 14.00-18.00

## 考核题目(二选一)

### 1.**TODO**App

任务清单类APP，UI可参考各大任务清单App

API：（该题目可以不进行网络请求）

如果要实现网络请求可参考wanandroid API https://www.wanandroid.com/blog/show/2 https://www.wanandroid.com/blog/show/2442

#### 核心功能：

必须实现Kotlin语言进行开发

必须完成本地存储功能

#### 基础功能：

- 实现登陆注册功能
- 显示已创建任务
- 实现对任务的增删查改
- 任务能够实现访QQ的侧滑删除和置顶功能

#### 加分功能：

- 每一个任务可以拥有子任务，能依靠多级列表显示（可以参考 ExpandableListView ）
- 对任务的编辑（如删除功能）用自定义View提示
- 根据积分 API（无网络请求可自己设定积分，通过完成任务添加积分）仿掌邮实现积分商城页面（Hard - 上方嵌套滑动）



### 2.知乎日报App

仿写知乎日报，UI可参考知乎日报，知乎日报可前往各大应用商店下载。

API：[RQ527/ZHIHUAPI: 知乎日报API (github.com)](https://github.com/RQ527/ZHIHUAPI)（登录注册点赞等由于接口原因不要求实现）

#### 核心功能：

实现Kotlin语言进行开发

必须完成网络请求功能

#### 基础功能：

- 顶部Banner（不允许使用三方库）与日期

- 上拉加载下拉刷新

- 点击查看新闻详情，左右滑动切换下一篇（上一篇）新闻

- 查看评论与分享功能

  

#### 加分功能：

- 实现夜间功能
- 协调者布局实现Toolbar和Rv联动
- 点击日期查看日历功能（不依靠系统API 用自定义View实现）

## 基本要求

**1.不要熬夜，不要熬夜，不要熬夜！！！**

2.除常见第三方库如`Glide`,`okhttp||retrofit`,`gson`,`jetpack`以外不使用其他第三方库，不建议使用Jetpack Compose，具体其它常见第三方库可以询问自己的导师

3.本次考核因时间原因不要求全部做完,请不要追求做完而去粗制滥造，而是让做出来的页面质量高。

4.在Github仓库中编写详细的README.md文档

至少应该包含：

- APP的简要介绍(APP的功能，主要功能的实现思路，不同页面实现的思路)
- APP功能的展示(GIF)
- 技术亮点或者说你认为写得不错的地方
- 心得体会
- 待提升的地方

5.可以部分CV代码，但要求必须CV的代码是自己能看懂的，禁止大面积CV代码！！！

6.Github 的 commit 记录不得超过一天，请尽量在完成一个新功能后提交commit

7.App中的**核心功能**一定要完成，否则视为未完成，**基础功能**请尽量按照要求完成，否则影响考核评价，**加分功能**不强制要求，请在确保**基础功能**完成后进行尝试。

### 依赖要求

- **禁止**使用除以下库外的其他库，可使用的库如下：
  - 所有 `google` 库
  - 所有 `android` 以及 `androidx` 库
  - 所有 `jetbrains` 库（协程包含在这里面）
  - 部分第三方库
    - [`ARouter`](https://github.com/alibaba/ARouter)（如果不熟练多模块开发，就不要尝试）
    - [`Glide`](https://github.com/bumptech/glide)
    - [`Lottie`](https://lottiefiles.com/blog/working-with-lottie/getting-started-with-lottie-animations-in-android-app)
    - [`Retrofit`](https://github.com/square/retrofit)
    - [`Okhttp`](https://github.com/square/okhttp)
    - [`Gson`](https://github.com/google/gson)
    - [`Rxjava`](https://github.com/ReactiveX/RxJava)
    - [`RxPermissions`](https://github.com/tbruyelle/RxPermissions)：一个权限申请库
    - [`PhotoView`](https://github.com/Baseflow/PhotoView)：一个专门查看图片的库
    - 如果你做的项目需要使用到视频播放的功能，允许使用播放视频的第三方库（因为官方库有坑）
    - 如果对依赖有特殊要求，请在大群里提问
    - 如果使用自己的依赖库，有如下要求
      - 不能是 fork 来的
      - 绝大部分代码是自己所写
- 由于本次考核需要衡量你们接手掌邮的能力，所以**强烈不推荐**使用 `compose`，掌邮目前明确禁止使用 `compose`
- `Banner`（轮播图）请自己实现

## 考核加分项

1. 使用MVVM架构

2. 精美的界面，丰富的动画效果，自定义View

3. 变量命名规范，项目结构合理

4. 完成加分功能


## 考核提交

- 截止日期：2023年5月3日12:00
- 提交方式：发送邮件到：mobile@redrock.team
  - 邮件标题：2023中期考核-学号-姓名。如：2023中期考核-2022214xxx-李戬
  - 邮件正文：Github仓库地址
  - 邮件附件：正式版APK（需要数字签名）
- 未按时提交考核的视为放弃
