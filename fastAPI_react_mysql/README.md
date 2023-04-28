### 大変申し訳ございません
とりあえず基礎的なdocker composeはかけるくらいの程度の参考資料になります。
面接でバックエンドとフロントエンドに分けて、用意したほうがいいと伺ったので、それっぽいものを作ろうと思ったのですが、時間がとれませんでした。
結局、react側は環境構築しただけです。

### 構造

```
.
fastAPI_react_mysql/
├── README.md
├── backend
│   ├── Dockerfile
│   ├── app
│   └── requirements.txt
├── docker-compose.yml
└── frontend
    ├── Dockerfile
    ├── README.md
    ├── app
    ├── node_modules
    ├── package-lock.json
    ├── package.json
    ├── public
    ├── src
    └── tsconfig.json
```