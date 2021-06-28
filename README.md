##じゃけぇさんのReactステップアップ講座をTailwind CSSでやってみる

# qastclone

## プロジェクト作成


### auto

```
yarn create next-app
```

### manual

```
yarn add next react react-dom
```

## 開発サーバー立ち上げ

```
yarn dev  // localhost:3000 で立ち上がる
```

## 環境構築

### 1.Typescript

### 空の tsconfig.json ファイルを作成

```
touch tsconfig.json
```

### typescript のインストール

```
yarn add --dev typescript @types/react @types/node
```

ファイルを .js から .tsx に変換すると、準備完了！！

### 2.tailwindcss

### tailwindcss 関連ライブラリのインストール

```
yarn add -D tailwindcss@latest postcss@latest autoprefixer@latest
```

### tailwind.config.js,postcss.config.js ファイルの作成

```
yarn run tailwindcss init -p
```

### 3.eslint

```
yarn run eslint --init
```

✔ How would you like to use ESLint? · problems
✔ What type of modules does your project use? · esm
✔ Which framework does your project use? · react
✔ Does your project use TypeScript? · No / Yes
✔ Where does your code run? · browser
✔ What format do you want your config file to be in? · JavaScript
✔ Would you like to install them now with npm? · No


### eslint-plugin-react、 typescript-eslint/eslint-plugin、typescript-eslint/parserのインストール

```
yarn add  eslint-plugin-react@latest @typescript-eslint/eslint-plugin@latest @typescript-eslint/parser@latest
```

### 4.prettier

### prettier のインストール

```
yarn add -D prettier
```

### slint-config-prettier eslint-plugin-prettier のインストール

```
yarn add eslint-config-prettier eslint-plugin-prettier --save-dev
```

### 5.axios

### axios のインストール

```
yarn add axios --save
```

### 6.classcat

### classcat のインストール

```
yarn add classcat
```

### 7.@headlessui/react

### @headlessui/react のインストール

```
yarn add @headlessui/react
```
