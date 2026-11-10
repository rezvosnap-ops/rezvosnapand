# 拾光截图 · Android

原生 Java Android 应用，奶油白 / 鼠尾草绿 / 橙色视觉。支持系统图片导入、中心正方形裁剪、奶油留白、文字标注、应用内作品历史、保存到相册及系统分享。所有图片本地处理，无网络权限。

`images/googleplay.png` 已复制到 `app/src/main/res/drawable/store_badge.png`，在关于页实际引用。首页灵感卡片使用原生布局绘制。

## 运行

需要 Android Studio、JDK 17、Android SDK 35、Gradle 8.9。Android Studio 打开本目录，同步后运行 app（Android 10+）。本仓库未包含 Gradle Wrapper 二进制；已安装 Gradle 8.9 时可执行 `gradle wrapper --gradle-version 8.9`，随后 `./gradlew assembleDebug`。APK 位于 `app/build/outputs/apk/debug/app-debug.apk`。

保存作品到应用私有目录和 `Pictures/Shiguang`。导入使用系统文件选择器，无需照片库广泛读取权限。文字标注是底部单行题注，裁剪为可逆的中心正方形裁剪。当前不包含手绘、OCR、滚动截屏或屏幕录制。

本次环境缺少 JDK、Android SDK 和 Gradle，未进行编译或设备验证，尚未生成 APK。
