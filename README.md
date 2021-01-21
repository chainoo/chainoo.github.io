
> 列出区块链源码的当前版本 

## Build Setup

```bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

```

## 生成数据

- `scripts/source.json` 记录要搜集版本的开源软件列表
- `static/data/data.json` 存放搜集到的数据

```bash
# 使用脚本生成数据

python3 scripts/check.py
```

## 参与贡献

欢迎任何形式的贡献.
