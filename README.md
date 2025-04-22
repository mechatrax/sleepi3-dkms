# sleepi3-dkms
slee-Pi 3 を動作させるためのカーネルモジュールを Dynamic Kernel Module Support (DKMS) を利用して提供します。  

## 提供ファイル
次のファイルがパッケージに含まれています。

### /usr/share/doc/sleepi3-dkms/changelog.gz
パッケージの変更履歴を記録したファイルです。

### /usr/share/doc/sleepi3-dkms/copyright
著作権とライセンスを記載したファイルです。

### /usr/src/sleepi3-\*/Makefile
カーネルモジュールのコンパイルに必要な Makefile です。

### /usr/src/sleepi3-\*/dkms.conf
dkms の設定ファイルです。

### /usr/src/sleepi3-\*/rtc-ds1307-legacy.c
カーネルモジュールのソースファイルです。

## 設定

### /etc/modprobe.d/sleepi3-dkms.conf
sleepi3-dkms の提供するカーネルモジュールの設定ファイルです。  
