# github pages

## 初回build

```
docker-compose build
docker exec -it {コンテナ名} bash
yarn create vue
```

## 開発

### コンテナ立ち上げ

```
docker-compose up -d
docker exec -it {コンテナ名} bash
```

### webサーバー起動

```
yarn dev
```

### build

```
yarn build
```