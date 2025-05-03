FROM node:20

# 環境構築
WORKDIR /app

# 依存ファイルのみコピーして依存関係をインストール
COPY package*.json ./
RUN npm install -g expo-cli @expo/ngrok

# プロジェクトコピー
COPY . .

# ポート開放
EXPOSE 8081 19000 19001 19002

# Expo 開発サーバー起動
CMD ["npx", "expo", "start", "--tunnel"]
