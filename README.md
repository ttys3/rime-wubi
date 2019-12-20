# 五筆字型

配方： ℞ **wubi**

[Rime](https://rime.im) 五筆字型輸入方案

五筆字型 86 版

此rep fork自 https://github.com/rime/rime-wubi 并增加两个自定义配置文件：

```
default.custom.yaml
wubi86.custom.yaml
```

## 安裝

将此目录所有 *.yaml 文件复制到 RIME 用户配置目录

### Windows RIME 用户配置目录

```
%AppData%\Rime
```

### Linux ibus-rime 用户配置目录

```
$HOME/.config/ibus/rime
```

## MISC

拼音反查、五筆拼音混合輸入依賴於

  - [袖珍简化字拼音](https://github.com/rime/rime-pinyin-simp) ℞ **`pinyin-simp`**

[東風破](https://github.com/rime/plum) 安裝口令： `bash rime-install wubi pinyin-simp`

授權條款：見 [LICENSE](LICENSE)
