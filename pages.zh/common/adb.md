# adb

> 安卓调试桥：与 Android 模拟器或已连接的 Android 设备通信.

- 检查 adb server 进程的是否在运行，并开启它:

`adb start-server`

- 终止 adb server 进程:

`adb kill-server`

- 在目标模拟器 / 设备实例上开启一个远程 shell:

`adb shell`

- 将 Android 应用程序推送到模拟器 / 设备 :

`adb install -r {{本地 APK 的路径}}`

- 从目标设备上拷贝一个文件 / 目录到本地:

`adb pull {{被拷贝的目标设备上的文件或目录}} {{要保存到本地的文件或目录}}`

- 从本地拷贝一个文件 / 目录到目标设备:

`adb push {{被拷贝的本地文件或目录}} {{要保存到目标设备的文件或目录}}`

- 列出已连接的设备:

`adb devices`
