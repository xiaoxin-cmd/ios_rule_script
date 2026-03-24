# ios_rule_script

iOS 平台分流规则、复写规则与自动化脚本整理仓库。

## 目录结构

- `rule/`：分流规则
- `rewrite/`：复写规则
- `script/`：自动化脚本
- `source/`：上游来源与整理文件
- `icon/`：图标资源
- `blank/`：占位与空白资源

## 推荐入口

### 分流规则
- [Emby.list](https://raw.githubusercontent.com/xiaoxin-cmd/ios_rule_script/master/rule/Emby.list)
- [rule/Loon/](https://github.com/xiaoxin-cmd/ios_rule_script/tree/master/rule/Loon)
- [rule/Surge/](https://github.com/xiaoxin-cmd/ios_rule_script/tree/master/rule/Surge)
- [rule/QuantumultX/](https://github.com/xiaoxin-cmd/ios_rule_script/tree/master/rule/QuantumultX)
- [rule/Shadowrocket/](https://github.com/xiaoxin-cmd/ios_rule_script/tree/master/rule/Shadowrocket)
- [rule/Clash/](https://github.com/xiaoxin-cmd/ios_rule_script/tree/master/rule/Clash)

### 复写规则
- [rewrite/Loon/](https://github.com/xiaoxin-cmd/ios_rule_script/tree/master/rewrite/Loon)
- [rewrite/Surge/](https://github.com/xiaoxin-cmd/ios_rule_script/tree/master/rewrite/Surge)
- [rewrite/QuantumultX/](https://github.com/xiaoxin-cmd/ios_rule_script/tree/master/rewrite/QuantumultX)

### 自动化脚本
- [script/README.md](https://github.com/xiaoxin-cmd/ios_rule_script/blob/master/script/README.md)
- [gallery.json](https://raw.githubusercontent.com/xiaoxin-cmd/ios_rule_script/master/script/gallery.json)

## 当前重点内容

- 已新增并维护 `rule/Emby.list`
- Emby 规则已完成去重、排序、统计修正
- 可直接用于 Loon 远程规则引用

## 示例

### Loon 远程规则引用
```ini
https://raw.githubusercontent.com/xiaoxin-cmd/ios_rule_script/master/rule/Emby.list, policy=Emby, tag=Emby, enabled=true
```

## 说明

本仓库以个人整理、备份和使用为主；部分内容来自公开项目，请按原作者说明与许可使用。
