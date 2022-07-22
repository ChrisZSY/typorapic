## Typora使用网络图片（PicGo+GitHub+Typora搭建图床使用）

​         

### PicGo+[GitHub](https://so.csdn.net/so/search?q=GitHub&spm=1001.2101.3001.7020)+Typora搭建图床使用

#### 如何使用 Github 作为自己的免费[图床](https://so.csdn.net/so/search?q=图床&spm=1001.2101.3001.7020)

##### 前言

现在很多markdown编辑器或者图床管理工具可以使用同性交友网站Github 来作为图床使用。
 例子：
 [外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传

![img](https://img-blog.csdnimg.cn/img_convert/593791368bb563842246460769507b8b.png)

### 教程

我现在以 PicGo 为例，其他的产品其实都差不多

#### 1、分析所需资料

回顾上面那张图片，我们至少需要四样东西（带有星号的）

- Github 账号（必备）
- 仓库名
- 分支名
- token（中文：私人令牌）

#### 2、注册账号

首先注册一个 github 账号（网址：[https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home](https://github.com/join?ref_cta=Sign up&ref_loc=header logged out&ref_page=/&source=header-home)
 短网址：http://cn.hk.uy/qV8）

![img](https://img-blog.csdnimg.cn/img_convert/c1aff2aad8f60c4572fcb4ab3db29f72.png)

#### 3、创建仓库

来到首页（网址：https://github.com）

点击右上角的‘+’号

![[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-q5R38O50-1597746096044)(https://raw.githubusercontent.com/pky2006/photo/master/20200818164008.png)]](https://img-blog.csdnimg.cn/img_convert/14720be3d5a31310dadeeaa50211d4bf.png)

点击‘New repository’（中文：新仓库）

![img](https://img-blog.csdnimg.cn/img_convert/79bf57b16e792667dec4a2ae5b0b7a16.png)

填写资料

![[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-DRUOALP7-1597746096074)(https://raw.githubusercontent.com/pky2006/photo/master/20200818164953.png)]](https://img-blog.csdnimg.cn/img_convert/d38a0d492be2e172c3c9afbd4c0a5046.png)

依上图，主要填写仓库名（Repository name），其他的默认就可以了，最后只需点击创建仓库（Create repository）

创建后，应该会跳转到这样一个页面

![在这里插入图片描述](https://img-blog.csdnimg.cn/img_convert/20d59352611ccecb197646972ad22685.png)

#### 4、 创建token

点击自己的头像，找到‘Settings’，点击进入

![在这里插入图片描述](https://img-blog.csdnimg.cn/img_convert/a15b35c41777511fa252ceb1d626434b.png)

滚动到下面，直到你看见‘Developer settings’

![在这里插入图片描述](https://img-blog.csdnimg.cn/img_convert/eba17f1a9b5b8720d26002bb092ddec1.png)

选择‘Personal access tokens’

![img](https://img-blog.csdnimg.cn/img_convert/0b19754735cd7c831132cbd059540228.png)

点击‘Generate new token’

![在这里插入图片描述](https://img-blog.csdnimg.cn/img_convert/ff6afda1702dad1d82477853b059174b.png)

填写名字（note），勾选‘repo’

![[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-N3vdf8cG-1597746096127)(https://raw.githubusercontent.com/pky2006/photo/master/20200818170736.png)]](https://img-blog.csdnimg.cn/img_convert/c744b3a698e27162cb577578eb1f87a1.png)

最后选择‘Generate token’（中文：生成令牌）

![img](https://img-blog.csdnimg.cn/img_convert/9ec89868054a55887ec3b07cfa33693a.png)

复制并保存你的token

![img](https://img-blog.csdnimg.cn/img_convert/065326d5b82a213e02ea4895eac6f6c8.png)

**PS：这个token只会出现一次，务必保存妥当（虽然可以再次新建，但新建会导致以前的token失效）**

#### 5、打开PicGo，填写 github设置资料

填写仓库名（**记得填写 github.com/ 后面那串字符（通常格式为： 用户名/仓库名）**）、分支名（默认是master）、token值

![在这里插入图片描述](https://img-blog.csdnimg.cn/img_convert/15fb246241e0e349a796876cc0e225e9.png)

设置自定义域名（不设置可能会导致图片上传失败）：

> https://cdn.jsdelivr.net/gh/用户名/仓库名

#### 6、PicGo设置 `时间戳重命名`

> 如果你上传过一张image1.jpg的图片，再上传名称一样的图片就会失败。
>
> 设置`时间戳重命名`可以避免图片存在导致的上传失败。

![image-20210512205908688](https://img-blog.csdnimg.cn/img_convert/4d69fe3927074491ffb111ca1d52e3e9.png)

#### 7、[Typora](https://so.csdn.net/so/search?q=Typora&spm=1001.2101.3001.7020)配置

![在这里插入图片描述](https://img-blog.csdnimg.cn/img_convert/e4a7b8872e8026bf4c4fdeca3ac95e34.png)

