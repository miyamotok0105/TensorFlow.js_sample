
# Tensorflow.jsをインストール

参考にさせていただきました。    
https://qiita.com/shisama/items/33d34b0b1774f69f8a96    

```
npm install @tensorflow/tfjs
or
yarn add @tensorflow/tfjs
```

# Parcelをインストール

```
npm install -g parcel-bundler
```

```
yarn global add parcel-bundler
```

# 動かしてみる


```
cd 001
touch main.js
touch index.html
parcel build index.html --public-url ./
```

# node js

ビルド


```
parcel build main.js -d dist_node
node dist_node/main.js
parcel build core-concepts.js -d dist_node
node dist_node/core-concepts.js
```




