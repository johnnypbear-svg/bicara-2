# Bicara 印尼语词库 - 安卓版

## 生成 APK（用电脑，约 5 分钟）
1. 安装 Android Studio（官网下载，安装时选默认选项）。
2. 打开 Android Studio，选择 **Open**，选中本文件夹 `BicaraApp`。
3. 等待右下角 Gradle 同步完成（第一次需要下载，较慢，耐心等）。
4. 菜单 **Build → Build Bundle(s) / APK(s) → Build APK(s)**。
5. 完成后点右下角 **locate**，找到文件：
   `app/build/outputs/apk/debug/app-debug.apk`

## 安装到手机
1. 把 `app-debug.apk` 传到手机（数据线、微信文件传输或网盘）。
2. 在手机上打开文件，允许“安装未知来源应用”，点安装。
3. 桌面出现 “Bicara 印尼语” 图标即可使用。

## 说明
- 完全离线运行，不需要网络。
- 发音使用手机自带的印尼语语音。如果没有声音，请到手机 **设置 → 语言和输入 → 文字转语音** 中安装印尼语语音包。
- 所有词库、查询记录、掌握度都保存在手机本地（应用内存储），关闭应用后不会丢失。卸载应用时会一起删除，所以卸载前请先导出备份（后续版本会加导出功能）。
- 更新词库：修改 `app/src/main/assets/index.html`，重新生成 APK 即可。
