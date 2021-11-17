# 使用方式

## 首次发布
```bash
npx standard-version --first-release
```

## 迭代版本
* 一般是以`minor`的版本号递增形式，比如`1.1.0` ===> `1.1.1`
```bash
npx standard-version
```

## 预发布版本
1. 版本号变成`1.0.1-0`
```bash
npx standard-version --prerelease
```

2. `1.0.1-alpha.0`
```bash
npx standard-version --prerelease alpha
```

## 提交过程中避免pre-commit钩子的校验
```bash
npx standard-version --no-verify
```
