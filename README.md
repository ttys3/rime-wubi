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

### Mac RIME 用户配置目录

```
~/Library/Rime/
```

@see https://github.com/rime/home/wiki/RimeWithSchemata#rime-%E4%B8%AD%E7%9A%84%E6%95%B8%E6%93%9A%E6%96%87%E4%BB%B6%E5%88%86%E4%BD%88%E5%8F%8A%E4%BD%9C%E7%94%A8


## Installation with ibus

### fedora
```bash
sudo dnf install -y ibus-rime ibus-table-chinese-stroke5 ibus-table-chinese-wubi-jidian
```
using `ibus-setup` and add `Chinese - Rime` and `English - English` Input Method

go to Gnome `Region & Language` remove all under `Input Sources` and just add `Chinese(Rime)`


## MISC

拼音反查、五筆拼音混合輸入依賴於

  - [袖珍简化字拼音](https://github.com/rime/rime-pinyin-simp) ℞ **`pinyin-simp`**

[東風破](https://github.com/rime/plum) 安裝口令： `bash rime-install wubi pinyin-simp`

授權條款：見 [LICENSE](LICENSE)
