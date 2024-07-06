![](NO_MILKTEA.jpg)

<p align="left"> <a href="README.md">简体中文</a> | <b>繁體中文</b> </p>

# 字幕計劃

所有製作過或正在進行的字幕計劃及連結請查看 [項目表](https://github.com/orgs/Nekomoekissaten-SUB/projects/1)。如若發現錯誤歡迎通過 [Issues](https://github.com/Nekomoekissaten-SUB/Nekomoekissaten-Subs/issues) 或 [Google 表單](https://forms.gle/PQVM8p8SxvgKUco48) 進行回報。

## 注意事項

1. 與其他字幕組合作的作品會進行標註。在此對合作字幕組表示感謝
2. 本組字幕一般為簡繁中文字幕，中日雙語字幕會另行標註
	- Repo 内包含的單日文字幕的來源一般是放送或配信的日文文本字幕，未做其他源的調軸適配且不保證其日文內容、字幕樣式的準確性
3. 未打包的字幕可以使用 [DownGit](https://downgit.github.io/) 等打包下載
4. 本組製作的字幕以 [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) 為基礎進行授權
	- 可以自由轉載，但轉載字幕時不得修改原始字幕內容及需要註明來源，聯合發布需要徵求本組同意
	- 發布修改版字幕（包括但不限於時間軸調整、譯法調整）一定要註明來源和附帶原始字幕
		- 如果發現錯字、錯譯、錯軸等推薦通過 GitHub 等方式回報
	- 禁止用於商業目的
	- 發布同為文本字幕的修改版字幕演繹遵循上述第二點
	- 禁止發布一切未經同意的不可逆的文本轉圖像修改版字幕（包括但不限於外掛結構、加流重灌）
	- 本組所有字幕（除直接轉載的官方日文字幕）無特殊聲明外均遵循上述協議進行許可，如有疑問請聯絡本組
5. 通過 [Issues](https://github.com/Nekomoekissaten-SUB/Nekomoekissaten-Subs/issues) 回報錯誤前，建議先檢查列表內其他 Issues 是否已有相同內容的回報，避免出現重複

## 項目表說明

1. `Type`
	- 6 位純數字的是 TV 動畫，前 4 位為播出年份，後 2 位為播出季度（冬 1 月、春 4 月、夏 7 月、秋 10 月）
	- `TV-Old` 為 2017 年冬季之前開播的動畫
	- `Mov` 為劇場版 / 映畫
	- `OVA-O` 為原創類 OVA
	- `OVA-TV` 一般為 TV 動畫衍生、漫畫 / 小說 / 遊戲附贈的 OVA，其中也有一部分在 TV 動畫目錄下，此處收錄的一般是本組未製作 TV 動畫所衍生的 OVA / ONA
	- `Other` 為非日本動畫的內容
2. `ExtraInfo`
	- `JPCH` 表示為中日雙語
3. `Co-authors` 表示為與其他字幕組的合作作品，不同標籤為不同的合作字幕組 Tag
4. `Status`

	| Status        | 狀態             | 附錄              |
	| ------------- | ---------------- | ----------------- |
	| ToDo          | 計劃製作         |
	| Maybe         | 也許製作         |
	| Sync Update   | 同步更新         |
	| In Production | 製作中           |
	| Update Done   | 更新完成但未合集 |
	| Web ver. Done | 已完成 Web 合集  | 也可能是 TV 合集  |
	| BD ver. Done  | 已完成 BD 合集   | 也可能是 DVD 合集 |
	| Maybe Dead    | 也許不會再製作   |
	| Dead          | 不會繼續製作     |

5. `Subs Link` 為外掛字幕的 GitHub 頁面

## 字幕儲存說明

公開的字幕均上傳至 [Nekomoekissaten-Storage](https://github.com/Nekomoekissaten-SUB/Nekomoekissaten-Storage)，並打包上傳至 [Subtitles Packages](https://github.com/Nekomoekissaten-SUB/Nekomoekissaten-Storage/releases/tag/subtitle_pkg)，推薦從項目表訪問至相應的目錄，各目錄中的 README 會提供下載的連結。

1. 一般將合併特效後的成品打包至 tag [subtitle_pkg](https://github.com/Nekomoekissaten-SUB/Nekomoekissaten-Storage/releases/tag/subtitle_pkg) 下，特效等大文本文件上傳至 [subtitle_effect](https://github.com/Nekomoekissaten-SUB/Nekomoekissaten-Storage/releases/tag/subtitle_effect)，單語字幕的日文字幕可能上傳至 [subtitle_jpn](https://github.com/Nekomoekissaten-SUB/Nekomoekissaten-Storage/releases/tag/subtitle_jpn)
2. 打包的命名是按以下順序排列，使用 `_` 連接
	1. 資料夾名稱。如果資料夾內有多個同系列或多季度作品，可能會使用片名縮寫或增加季度縮寫
	2. 根據字幕時間軸的匹配使用 `Web` 或 `BD`（實際可能匹配的是 WebRip 或 BDRip）
	3. 簡繁中文為 `zho`，簡繁日雙語為 `JPCH`，單簡體為 `chs` / `CHS`
	4. 如果後續更改可能會添加打包時的 commit 或者修改日期（`YYYYMMDD`）
3. 如果字幕本身偏大，不適合 git 管理，可能不會上傳至 repo 內而是直接打包至 [subtitle_pkg](https://github.com/Nekomoekissaten-SUB/Nekomoekissaten-Storage/releases/tag/subtitle_pkg)。一般改動會在 README 中記錄 changelog
4. 如果字幕本身只有 1-4 個，可能不會打包上傳至 [subtitle_pkg](https://github.com/Nekomoekissaten-SUB/Nekomoekissaten-Storage/releases/tag/subtitle_pkg)，可以直接從 git repo 下載（目前在減少這種現象）
