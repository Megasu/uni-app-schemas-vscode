# 改动日志

## Unreleased

- `manifest.json` 中 `versionCode` 调整为 `number` 类型

## 0.8.7

- 补充部分字段
- 调整部分字段说明

## 0.8.6

- 修复插件功能

## 0.8.5

- 切换到 [uni-helper](https://github.com/uni-helper) 组织下

## 0.8.4

- 修复 `subNVues` 类型

## 0.8.3

- 为颜色属性增加 `"format": "color"`
- 修复 `pages.json` 中 `titleNView.tags.textStyles.color` 错误设置 `enum` 的问题

## 0.8.2

- 发布流程改进
- 更新链接

## 0.8.1

- 补充插件外使用的说明

## 0.8.0

- 大量字段更新

## 0.7.2

- 发布流程改进

## 0.7.1

- 更新 `manifest.json`，移除多余的 `uniStatistics.version` 和 `uniStatistics.debug`

## 0.7.0

- 更新 `manifest.json`，增加 `uniStatistics.version` 和 `uniStatistics.debug`

## 0.6.1

- 更新 `androidPrivacy.json`，增加参考链接
- 更新 `manifest.json`，增加 `locale`

## 0.6.0

- 更新 `androidPrivacy.json`，增加 `disagreeMode`
- 更新 `manifest.json`
  - 增加 `${platform}.scopedSlotsCompiler`、`app-plus.screenOrientation`
  - 移除 `${platform}.usingComponents`，`screenOrientation`
  - 增加 `mp-lark` 和 `mp-kuaishou`

## 0.5.0

- 校验 uni-app `androidPrivacy.json` 格式
- 移除了所有的 `default`，避免不必要的误导
- 增加 `manifest.json` 配置项 `app-plus.splashscreen.useOriginalMsgbox`

## 0.4.0

- 增加配置项 `vueVersion`

## 0.3.2

- 修复 README 链接

## 0.3.1

- 使用脚本生成 README

## 0.3.0

- 增加配置项 `screenOrientation`
- 增加部分平台专属字段
- 更新部分字段的 `enum`

## 0.2.0

- 增加支付宝小程序配置项 `enableAppxNg`

## 0.1.5

- 使用 `node` 生成 README.md

## 0.1.4

- 修复无法校验的问题

## 0.1.3

- 更新文档说明

## 0.1.2

- 更新文档说明

## 0.1.1

- 更新文档说明

## 0.1.0

- 校验 uni-app `pages.json` 和 `manifest.json` 格式
