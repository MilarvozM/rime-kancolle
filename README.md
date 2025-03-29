# rime-kancolle
 舰队Collection (Kancolle) 中文补充词库

目前更新至2025春活新船。

基础词库只包含官方称呼，不包含黑话。
外国舰因为用户个人选择会倾向于用外文名或中文名所以拆成两版词库，可以单独加装。
黑话因为其复杂性单独做一个词库。


使用方法（懒人简单版）：
1. 安装[RIME](https://rime.im/download/)
2. 安装[雾凇方案](https://github.com/iDvel/rime-ice)（相当完善的一套方案，像我这样的小白可以无痛开包即食）
3. 挂载kancolle词库：
	以雾凇方案为例：
	1. 找到rime_ice.dict.yaml，这个是雾凇方案挂载词库的地方
	2. 找到以下注释（在相当前面）：
	```
	# 建议把扩展词库放到下面，有重复词条时，最上面的权重生效
	
	# - cn_dicts/mydict
	```
	3. 根据kancolle词库位置添加挂载，比如船名文件被放在了cn_dicts目录下，就会是``` - cn_dicts/kancolle.ships ```，挂载时省略文件名后面的dict.yaml
	4. 按需一条条挂载即可。


更新计划：

- [x] IJN船名（包含舰种分类和具体船名）：种类-型-几号舰
	更新至2025春活动（大泊，榧，杉，岛根丸）

- [ ] 外国船名（包含舰种分类和具体船名）：种类-型-几号舰

- [ ] 装备（包含分类总称，前后缀，具体装备名称）：种类-拼音顺序

- [x] 敌舰（出现顺序）
	更新至2020年版

- [x] 道具（游戏内显示顺序）

- [ ] 游戏专用名词（拼音顺序）

- [x] 镇守府服务器（数字顺序）

- [ ] 相关人员（相关职业-拼音顺序）




感谢前人制作提供的参考：
[2014年版本的既存QQ词库](https://cdict.qq.pinyin.cn/detail?dict_id=s48206)
[2020年版本的RIME词库](https://bbs.nga.cn/read.php?tid=20070795)

排序参考以[wikiwiki.jp](https://wikiwiki.jp/kancolle/)为主，[舰百](https://zh.kcwiki.cn/wiki/)为辅。大部分相同少数冲突时采用日站顺序。如果有特殊排序会写明。

舰娘参考[日版wiki](https://wikiwiki.jp/kancolle/艦娘カード一覧2)[舰百汉化](https://zh.kcwiki.cn/wiki/Template:舰娘导航)
舰船分类主要参考游戏内，舰种会转换的以最主要或者最长时间的使用类别为分组依据（例：朝日是修理舰，熊野铃谷是CAV）。晓响雷电这类单字做注释占位表示。

装备参考[日版wiki](https://wikiwiki.jp/kancolle/装備カード一覧（種類別）)

道具参考[日版wiki](https://wikiwiki.jp/kancolle/アイテム)[舰百汉化](https://zh.kcwiki.cn/wiki/道具)
