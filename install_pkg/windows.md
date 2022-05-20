# RStanのインストール for Windows

このガイドは，2022年5月20日に作成されました．
Windows11で確認しています．

# インストール前の確認

次のリンク先にある，「インストール前の確認」をよく読み，問題ないことを確認してください．
誤ったユーザ名やアカウントを使った場合，RStanのインストールに失敗します．

- [for Windows10](https://github.com/yyamnk/DataAnalysis/blob/master/install/windows10.md#%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E5%89%8D%E3%81%AE%E7%A2%BA%E8%AA%8D): 
- [for Windows11](https://github.com/yyamnk/DataAnalysis/blob/master/install/windows11.md#%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E5%89%8D%E3%81%AE%E7%A2%BA%E8%AA%8D) 


# Rstanのインストール

1. RStudioの右下にあるPackagesタブ
2. Install
    ![](./win_step1.png?raw=true)
3. Install to Libraryを確認
    - `Install to Library`の表示が，`C:/Users/ユーザ名/Documents/R/win-library/バージョン番号`となっていることを確認する．
    - ユーザ名とバージョン番号は各自で異なるので，適宜読み替えること
    ![](./win_step2.png?raw=true)
4. Packagesに「rstan」と入力し，Install
5. 次のような警告（Rtoolsが必要だが，インストールされていない）が出た場合，Rtoolsをインストールする．
    - 使用しているRのバージョンを確認して，適切なRtoolsのインストーラを入手する．
    ![](./win_step3.png?raw=true)
    - インストーラは次のリンクからダウンロードする．ダウンロードしたインストーラを起動し，全てデフォルト（変更せずにNextを押す）で進める．
    - [Rtoolsのインストーラ](https://cran.r-project.org/bin/windows/Rtools/)
    ![](./win_step4.png?raw=true)
    - Rtoolsがインストーラできたら，再び手順4を行う．
6. Consoleに`library('rstan')`と打ち，Packagesタブのrstanにチェックが入ればインストールできている．
    ![](./win_step5.png?raw=true)


# Rstanのインストール動画 (Rtoolsのインストールは含まれていない）

[Youtube: パッケージのインストール](https://youtu.be/JyKWeQMp5F4)
[![](https://img.youtube.com/vi/JyKWeQMp5F4/0.jpg)](https://www.youtube.com/watch?v=JyKWeQMp5F4)

