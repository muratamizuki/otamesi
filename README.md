軽い説明を
front React native Expo
back fastAPI
React nativeはreactでネイティブを開発できるフレームワーク
ExpoはXcode,Androidstudo使わなくても手元のデバイスでデバックできたりするから使ってみたくて入れた（~~Xcodeの環境構築めんどくさいし~~）

## 環境構築

以下の手順に従って開発環境をセットアップしてください。

0. **Expo Goのアプリをダンロード**:
    App Storeだったり各自適当な場所で

1. **Dockerコンテナを構築**:
    ```zsh
    docker-compose build

1分ちょいで終わる

2. **Dockerコンテナを起動**
    ```zsh
    docker-compose up 
3. **ブラウザでアクセス**:  
    front
    docker起動後に出てくるQRコードを読み込み
    back
    `http://localhost:8000/`
---
