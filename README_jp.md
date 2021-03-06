# DXGI-desktop-duplication-Network
Desktop Duplication API によって取得したデスクトップ画像をネットワーク経由で送信します。
Unity側で受信してテクスチャとして使用することでバーチャルデスクトップのようなものが作成できます。

## 使用方法
1. Unity側でデスクトップ画像を表示したいオブジェクトに`DesktopReceiver.cs`をアタッチする。
2. Senderの`StreamingManager.cpp`で送信先のアドレスを指定して起動する。

## ライセンス
MSDNのサンプル（
https://code.msdn.microsoft.com/windowsdesktop/Desktop-Duplication-Sample-da4c696a
）をベースに作成しているのでMS-LPLライセンスに準拠します。

## 参考資料
* [ネットワーク - TCP - boostjp](https://boostjp.github.io/tips/network/tcp.html)
* [DirectXTex · Microsoft/DirectXTex Wiki](https://github.com/Microsoft/DirectXTex/wiki/DirectXTex)
