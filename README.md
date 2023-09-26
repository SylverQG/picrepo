# picrepo

- 获取token
  - 个人设置页面->开发者设置
  - 选择Personal access tokens，选择生成新token，添加描述,并添加选项repo
  - 迅速保存获得的token
- vscode picgo设置
  - 记得下载
  - 打开设置, 过滤出picgo
  - 设置如下:

![picgo_settingthin](https://cdn.jsdelivr.net/gh/SylverQG/picrepo@main/ChromeBook_Pic/picgo_settingthin.png)


1. current设置为GitHub
2. Branch选择仓库的分支，默认为master(新建仓库默认main)
3. custom url 图片上传链接
  - 原版:https://raw.githubusercontent.com/[用户名]/[仓库名]/[分支名]
  - cdn加速:https://cdn.jsdelivr.net/gh/[用户名]/[仓库名]@[分支名]
    - 注`cdn.jsdelivr.net`在中国大陆已被DNS污染和SNI阻断
    - 如果想用可以尝试将替换，建议原版:)
      - CloudFlare可以用：test1.jsdelivr.net、testingcf.jsdelivr.net
      - Fastly可以用：fastly.jsdelivr.net
      - GCORE可以用：gcore.jsdelivr.net
4. path是图片存储在仓库中的路径
5. 图床似乎1G，记得要省吃俭用
- 快捷键使用方法

|OS|	Uploading an image from clipboard	|Uploading images from explorer	|Uploading an image from input box|
|----|----|----|----|
|Windows/Unix	|Ctrl + Alt + U	|Ctrl + Alt + E	|Ctrl + Alt + O|
|OsX	|Cmd + Opt + U	|Cmd + Opt + E	|Cmd + Opt + O|
