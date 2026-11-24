# 班级桌宠（HTML 版）

## 项目说明
- 素材：本班同学照片（放在 `images/pet.jpg`）
- 互动功能：按住头像可拖动，单击头像弹出同学名字
- 运行方式：Windows 系统直接双击 `pet.html`，用浏览器打开即可运行，无需安装任何软件

## 文件结构
```
class-pet/
├─ pet.html        主程序（双击运行）
├─ README.md       项目说明
└─ images/
   └─ pet.jpg      本班同学照片
```

## 如何替换成自己的同学照片
1. 把同学照片复制进 `images` 文件夹；
2. 将照片重命名为 `pet.jpg`（和代码里的名字一致）；
3. 用记事本打开 `pet.html`，找到 `const petName = "小明";`，把“小明”改成同学真实名字，保存。

## 上传 GitHub
1. 浏览器打开 github.com 并登录；
2. 右上角 `+` → `New repository`，仓库名填 `class-pet`，选择 Public，创建；
3. 点 `Add file` → `Upload files`，把 `pet.html`、`README.md`、`images` 文件夹一起上传；
4. 滑到最下面点 `Commit changes` 提交。

## 常见问题
- 打开是空白：确认照片在 `images` 文件夹里且名字为 `pet.jpg`；确认 `pet.html` 后缀确实是 `.html`，不是 `.txt`。
- 看不到文件后缀：在文件夹顶部「查看」里勾选「文件扩展名」。
