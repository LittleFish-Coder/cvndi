# CV NDI Package for NCKU 中正堂

可以參考官方的範例：
https://github.com/buresu/ndi-python

## 官方gui tool連結(支援Windows,macOS)
- [NDI Tools for Windows](https://downloads.ndi.tv/Tools/NDI%205%20Tools.exe)
- [NDI Tools for MacOS](https://downloads.ndi.tv/Tools/NDIToolsInstaller.pkg)

## 安裝環境
注意！安裝環境有特別限制，請不要安裝python 3.10以上的版本！
- Windows x64 Python(3.7-3.10)
- macOS x64(>=10.12),arm64(>=11.0) Python(3.7-3.10)
- Linux x64,aarch64 Python(3.7-3.10)

## 安裝套件
記得install以下套件
```
pip install opencv-python
pip install ndi-python
pip install numpy
```
### Linux環境注意事項
如果你是用Ubuntu Linux的話，還要安裝以下套件
```
sudo apt install avahi-daemon
sudo systemctl enable --now avahi-daemon
```