20180331
之前安装的unity3D的版本太低了，导致打开一些工程的时候直接闪退。所以要重新安装。
但是由于当时是通过deb文件直接安装的，所以发现在 Ubuntu软件 里面找不到它所以也没法卸载。
方法如下：
1.  dpkg -l //看看系统里面那个软件到底叫什么名字，这里他叫 unity-editor
2.  sudo dpkg -r unity-editor
3. sudo dpkg -P unity-editor
