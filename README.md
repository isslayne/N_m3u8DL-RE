# N_m3u8DL-RE
跨平台的DASH/HLS/MSS下载工具。支持点播、直播(DASH/HLS)。
-------


> 本fork为该工具添加了若干我会用到的功能，并向随缘pr到源仓库
>
> 你有需求也可以提出来，我会尽量实现

相比于[原仓库](https://github.com/nilaoda/N_m3u8DL-RE)

+ 添加 `--force-ansi-console` 以在非ansi环境显示进度信息 & 用于移除ANSI颜色的 `--noansi` （用于其他进程调用）
+ 添加 `--live-pipe-options`用于自定义ffmpeg管道混流参数（原仓库那边如果混流到ffmpeg稳定了大概会删）
+ 不删除整个临时文件夹而是只删除新建的子文件夹
+ 一些奇奇怪怪的重试



