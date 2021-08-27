# FreedTV

同步[原項目](https://github.com/FreeDTV/FreeD)，增加自訂資源。<br>

File | Descriptions 
-- | -- 
public.json | 公共介面，會有些公共參數配置暫時用不到
searchUrl.json | 資源站/定制導航/搜索介面位址 對接蘋果CMS10介面
sourceNavigation.json | 資源專題介面
webPlugNavigation.json | 雲外掛程式介面

<br>

- 在備份基礎上添加了自訂功能，自訂內容會自動添加到核心介面檔中（僅 TV） <br>

File | Descriptions 
-- | -- 
custom/searchUrl.json | 自訂資源站介面
custom/webPlugNavigation.json | 自訂雲外掛程式介面

<br>

- 增加了收集功能，收集一些互聯網上的介面檔，以便挑選後加入自訂 <br>

File | Descriptions 
-- | -- 
custom/exterior/list.txt | 收集地址清單，格式:url 重命名
custom/exterior/files/ | 收集到的檔

<br>

# Usage

[下載](https://wwi.lanzous.com/b025mpw7e) <br>
選擇自建介面，輸入 
- 默認：https://github.com/RomualdoWu/FreeDTV/tree/main/tv
- 大陸：https://cdn.jsdelivr.net/gh/RomualdoWu/FreeDTV@main/tv/

<br>

也可以 fork 本專案，然後自己在自訂檔中修改自己喜歡的介面。（別忘了點 star）

<br>

# FreeD

- https://github.com/FreeDTV/FreeD
- https://gitee.com/freedTV/freed

---

## Logs

20210328 <br>
原項目在GitHub建立了項目，觀察幾天後發現作者已經把這邊作為主要更新地 <br>
本專案修改拉取目標為GitHub

20210222 <br>
因為原項目只有gitee建立，所以在GitHub做了一個定時拉取的備份 <br>
在備份基礎上增加了自訂資源+原項目資源合併的功能

### Custom For FongMi
https://github.com/FongMi/FreeDTV/raw/main/tv/

### Source
https://cdn.jsdelivr.net/gh/FreeDTV/FreeD@master/tv/
