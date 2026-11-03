# 拧螺丝解压工坊 (Screw Puzzle Workshop) - Android 原生工程

本项目是由《拧螺丝解压工坊》自动生成的完整 Android 原生工程包，内置 **GitHub Actions 云端自动编译 APK 工作流**。

## 🚀 方法一：使用 GitHub 仓库免费自动编译 APK（无需本地配置环境）

1. 在 GitHub 上新建一个仓库（公开或私有均可）。
2. 将本压缩包解压后的所有文件（注意包含隐藏文件夹 `.github/workflows/build-apk.yml`）上传并推送 (Push) 到 GitHub 仓库的 `main` 或 `master` 分支。
3. 打开 GitHub 仓库顶部的 **Actions** 选项卡，会自动触发 `Build Android APK` 构建任务。
4. 等待约 1~2 分钟构建变绿完成后，点进该次运行记录底部的 **Artifacts** 区域，即可直接下载：
   - `ScrewPuzzle-debug-apk`（内含可直接安装的 `app-debug.apk`）
   - `ScrewPuzzle-release-apk`（内含已签名的 `app-release.apk`）

## 💻 方法二：使用本地 Android Studio 编译

1. 打开 **Android Studio**（建议使用 Hedgehog / Iguana 或更新版本，JDK 17）。
2. 选择 **Open**，打开解压后的工程根目录。
3. 等待 Gradle 同步完成后，点击顶部菜单 **Build -> Build Bundle(s) / APK(s) -> Build APK(s)** 即可生成 APK。
