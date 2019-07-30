# 测试 npm

```sh
# 创建会更新 lockfile
npm install --package-lock-only

# 纯净安装
npm ci

# npm 根据 lockfile 安装，lockfile 应无变化
rm -rf node_modules
npm i
```
