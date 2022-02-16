# 我的笔记
## 1、基本运行
```
 npm install
 npm start
```
## 2、react改为react@16.9.0
+ 文件夹改名
+ webpack.config.js改动
```
        // 'react': path.resolve(__dirname, '../src/react@16.9.0/packages/react'),
        // 'react-dom': path.resolve(__dirname, '../src/react@16.9.0/packages/react-dom'),
        // 'legacy-events': path.resolve(__dirname, '../src/react@16.9.0/packages/legacy-events'),
        // 'shared': path.resolve(__dirname, '../src/react@16.9.0/packages/shared'),
        // 'react-reconciler': path.resolve(__dirname, '../src/react@16.9.0/packages/react-reconciler'),
```

## 3、添加最新版react/react-16.9.0(都失败)
```
git clone https://github.com/robin2017/react.git
```
+ 将文件夹改名为react@17.0.3
+ 去掉内部.git文件夹

### 3.1、修改配置