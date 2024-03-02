![](没有奶茶.jpg)

# 字幕计划

所有制作过或正在进行的字幕计划及链接请查看 [项目表](https://github.com/orgs/Nekomoekissaten-SUB/projects/1)，如若发现错误欢迎通过 issue 进行回报。

## 注意事项

1. 与其他字幕组合作的作品会进行标注。在此对合作字幕组表示感谢。
2. 本组字幕一般为简繁中文字幕，中日双语字幕会另行标注。
	- 仓库中包含的单日文字幕的来源一般是放送或配信的日文文本字幕，未做其他源的调轴适配且不保证其日文内容、字幕样式的准确性。
3. 未打包的字幕可以使用 [DownGit](https://downgit.github.io/) 等打包下载。
4. 本组制作的字幕以 [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) 为基础进行授权：
	- 可以自由转载，但转载字幕时不得修改原始字幕内容及需要注明来源，联合发布需要征求本组同意；
	- 发布修改版字幕（包括但不限于时间轴调整、译法调整）一定要注明来源和附带原始字幕；
		- 如果发现错字、错译、错轴等推荐通过 GitHub 等方式反馈；
	- 禁止用于商业目的；
	- 发布同为文本字幕的修改版字幕演绎遵循上述第二点；
	- 禁止发布一切未经同意的不可逆的文本转图像修改版字幕（包括但不限于外挂结构、加流重灌）；
	- 本组所有字幕（除直接转载的官方日文字幕）无特殊声明外均遵循上述协议进行许可，如有疑问请联系本组。

## 项目表说明

1. `Type`
	- 6 位纯数字的是 TV 动画，前 4 位为播出年份，后 2 位为播出季度（冬 1 月、春 4 月、夏 7 月、秋 10 月）
	- `TV-Old` 为 2017 年冬季之前开播的动画
	- `Mov` 为剧场版 / 映画
	- `OVA-O` 为原创类 OVA
	- `OVA-TV` 一般为 TV 动画衍生、漫画 / 小说 / 游戏附赠的 OVA，其中也有一部分在 TV 动画目录下，此处收录的一般是本组未制作 TV 动画所衍生的 OVA / ONA
	- `Other` 为非日本动画的内容

2. `ExtraInfo`
	- `JPCH` 表示为中日双语

3. `Co-authors` 表示为与其他字幕组的合作作品，不同标签为不同的合作字幕组 Tag

4. `Status`

	Status | 状态     | 附录
	---    | -------- | ---
	ToDo   | 计划制作
	Maybe  | 也许制作
	Sync Update | 同步更新
	In Production | 制作中
	Update Done | 更新完成但未合集
	Web ver. Done | 已完成 Web 合集 | 也可能是 TV 合集
	BD ver. Done | 已完成 BD 合集 | 也可能是 DVD 合集
	Maybe Dead | 也许不会再制作
	Dead | 不会继续制作

5. `Subs Link` 为外挂字幕的 GitHub 页面

## 字幕存储说明

公开的字幕均上传至 [Nekomoekissaten-Storage](https://github.com/Nekomoekissaten-SUB/Nekomoekissaten-Storage)，并打包上传至 [Subtitles Packages](https://github.com/Nekomoekissaten-SUB/Nekomoekissaten-Storage/releases/tag/subtitle_pkg)，推荐从项目表访问至相应的目录，各目录中的 README 会提供下载的链接。

1. 一般将合并特效后的成品打包至 tag subtitle_pkg 下，特效等大文本文件上传至 subtitle_effect，单语字幕的日文字幕可能上传到 subtitle_jpn
2. 打包的命名是按以下顺序排列，使用 `_` 连接
	1. 文件夹名称。如果文件夹内有多个同系列或多季度作品，可能会使用片名缩写或增加季度缩写
	2. 根据字幕时间轴的匹配使用 Web 或 BD（实际可能匹配的是 WebRip 或 BDRip）
	3. 简繁中文为 zho，简繁日双语为 JPCH，单简体为 chs / CHS
	4. 如果后续更改可能会添加打包时的 commit 或者修改日期（YYYYMMDD）
3. 如果字幕本身偏大，不适合 git 管理，可能不会上传到 repo 内而是直接打包到 subtitle_pkg。一般改动会在 readme 中记录 changelog
4. 如果字幕本身只有 1-4 个，可能不会打包上传至 subtitle_pkg，可以直接从 git repo 下载。（目前在减少这种现象）
