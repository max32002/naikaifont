「內海字體」是基於[瀨戶字體](http://setofont.osdn.jp/)的開放原始碼中文字型，目前字型內文字和符號字數在：47,417個。與原作者的版本，主要差異是另外新增中文字和符號，調整為5個字重，調整部件寫法。可以免費商用，歡迎大家自由應用、自由優化、自由改作！

## 字體特色

### 彌補繁體中文常用字缺字缺憾

內海字體已經補齊台灣教育部列出的 4,808 個常用字，增加了65字如下：螃螎螞蟈蟑諉賅賒賬贗趟趴跺踩踫踱蹝蹦蹺躂躉躲躺逛遴鄉醣鈉鈣鈽鈾鉻銬銳銻銼鋁鋅錳錶鎂鎊鎢鎳鏍鐮閡閱闆阱陴霉靶頹颳餵餿饞馱鬍鱖鵪鷥麂鼴齜。後續從其他字型取得了很多中文字，常見的中文字應該不會缺字了。

手動新增的字清，請參考文字檔 [added_glyph.txt](https://github.com/max32002/naikaifont/raw/master/added_glyph.txt)。

附註： 由於是「非原作者」的補字，新加入的字在風格上，雖然盡力求一致，難免會與原作者會有一些不同。有一些字補的「超級醜」的，一般情況應該不會遇到，如果有好心人有重做那些醜到爆的字，請再寄給我，感謝。

### 5種字重(Style)

* ExtraLight
* Light
* Regular
* SemiBold
* Bold

原本的瀨戶字體放在Regular 字重裡，透過程式自動產生ExtraLight、Light、SemiBold、Bold 新的字重。

在ExtraLight和Light字重是把原本的setofont微微調細一點點。在Light的字重裡，可能會因為筆劃太細造成某些筆畫消失。

在SemiBold和Bold的字重裡，可能會因為筆劃太粗造成某些筆畫重疊難以識別，有粗體字的需求，可以先挑戰使用Bold字重看看，如果發現效果不如預期，再改用SemiBold字重。

不能確定自動產生出來的字重裡每一個都是完整的字，畢盡程式會誤判是常有的事情，所以不是在Regular字重裡的筆劃可能會消失。

![內海字體](https://github.com/max32002/naikaifont/raw/master/preview/preview.png)

### 清除 setofont 裡空白的文字

瀨戶字體setofont 裡有很多空白的字， 會造成無法讓系統自動用預設字體來補字，已清除空白的文字。

### 調整標點符號位置

瀨戶字體的全形標點符號針對日本做設計，調整為台灣常見的置中用法。半形的 backslash，調整為非日本地區用法。

### 增加「臺灣閩南語推薦用字700字表」和部份客語的中文字

部份臺灣閩南語例如：㧒㧳㪗㾪䆀䉔䘼䩉䫀䫌螿蟧蟮蟳蠩覕譀趒趖跍跔跤踅踮蹛軁迌遢邋鐤雺頦骿魩鰇𠕇𠢕𠲿𢓜𣍐𤆬𤏸𤺪𥰔𥴊𨑨𡳞

![臺灣閩南語推薦用字700字表](https://github.com/max32002/naikaifont/raw/master/preview/preview_taiwaness.png)

### 增加部份的粵語字

感謝網友Luke Liu的貢獻，在內海字體增加107字如下：㓤㖡㖭㖿㗎㗾㧬㨘㩒㬹㷫㹴䁪䢂䱽螆蠄裇覅趷踎踭蹾躀躝軚輋酶醖鈈鈪鎅鐧閪餸骾髧鮋鯭鰂㋿㬹蟅蟴衪衹褔褟襬觩詗誆誏誒謢譭跩踄踭蹓蹧蹩遛酐酚酮酯醚醛鈦銨鋇鋯鋰錸鍘鍺鎘鎩隡霝頜饈髂魟魠魽鴯鶘鷰𠝹𠱁𠺝𠺢𡃁𢭃𢯊𢱕𢵌𤓓𤷪𥄫𦟌𦧺𨅝𨋢𩶘

![部份的粵語字](https://github.com/max32002/naikaifont/raw/master/preview/preview_hongkong.png)

### 從「小濑字体」取得猫啃新人和[落霞孤鶩lxgw](https://www.weibo.com/u/6624339726)的修正與優化

* 透過[小瀨字體](https://github.com/lxgw/kose-font)更新下面的字：傺动吨哌哨啄嗝埒堵塌填天夭孚察寥屯市帽廣弥戮戳所掐搌摒摔撇撙擢改旅昊曜柃柢桊桴棒植榍榔榻橫檫欤歙殍殛沣沿涤渝港溱潢潲濂濯瀚炖焰煺熠燕燧瑶璜瓴甑甩町画瘳直盹真睬瞥矗祆祓祗祚祛祭禅禇称稃稹稻窖窬筌箐綮置罾羚羝羰翎翮耀耥聃肇肫胝脬腈腠腧腴膈臁臾舀苓菁萏萸蓊蓼薯藤蘧虢蚺蛉蛸蜉蜩蝉蝓蝤蝽螂融螓蟀蠢蠲袢褪褶覃觅諂谄赜赧赭蹈蹊蹋躇边迟遄遘遽郛酹醪鍰鎘锾镉閻阎陷隔隘隧雕零霄鞘韬頓顿飩餡饨馁馅鬲鬻黛鼻𧝒
* 增加 940 簡体中文字。
* 感谢 猫啃网 用户 猫啃新人和[落霞孤鶩lxgw(孤鹜先森)](https://www.weibo.com/u/6624339726)的修正與優化。

### 合併「[cjkFonts 全瀨體](https://www.cjkfonts.io/blog/cjkfonts_allseto)」

* 從 cjkFonts 全瀨體取得 1萬1千個缺字。
* 內海字體收錄的文字＋符號數：47,417個；全瀨體收錄文字＋符號數：42,154個。有些字的品質會是全瀨體優於內海字體，有些則相反。

### 合併「台灣萌體」

* 從台灣萌體取得1947個符號與中文字：𠀉𠁣𠃛𠆧𠎷𠏮𠑘𠕆𠖫𠖲𠗳𠗼𠘆𠚺𠚼𠛎𠛒𠛓𠛪𠜐𠜖𠟄𠟉𠟶𠠁𠠃𠠍𠠹𠡠𠢆𠢠𠧅𠭴𠮾𠯤𠰍𠲛𠲥𠴂𠴼𠹃𠺣𠻹𠼖𠽾𠿝𠿪𡀿𡂏𡅏𡌽𡍤𡎔𡎮𡎺𡖓𡖯𡗭𡚸𡛰𡜵𡜿𡝠𡞞𡞟𡟓𡟧𡟯𡡎𡨞𡪗𡬆𡬘𡱰𡲬𢃓𢇓𢈈𢈊𢎙𢛔𢛟𢜩𢜳𢩰𢪈𢫨𢫫𢫭𢬳𢬵𢬿𢭕𢭪𢯩𢯹𢯽𢰡𢱉𢱋𢱑𢲫𢲲𢲶𢲾𢳀𢳇𢳍𢳚𢴳𢴿𢶉𢶌𢶍𢷓𢷾𢻷𢻹𢽲𢽻𢾖𢿞𣁴𣂁𣂡𣆅𣆯𣌍𣏫𣐞𣖜𣖬𣗖𣗺𣘛𣟵𣢇𣩈𣪟𣫙𣴠𣵷𣶉𣶦𣸍𣸥𣹇𤁢𤂱𤃶𤄜𤄷𤆵𤇺𤉮𤉹𤌣𤎖𤑷𤖯𤗇𤗷𤟟𤢌𤴯𤵉𤶁𤸑𤸫𤸬𤺅𤻤𤿎𤿩𥁠𥂝𥄹𥆌𥆍𥇇𥈅𥉔𥉘𥊰𥍆𥎊𥏘𥒭𥓩𥔳𥕿𥖄𥡃𥭆𥭘𥮕𥱊𥳳𥵝𥷒𥹉𥻵𥼶𥽕𦁧𦃆𦆟𦇎𦈰𦋐𦗀𦘅𦙮𦜍𦜩𦟜𦠖𦢊𦣀𦣇𦣘𦣱𦤟𦧊𦨮𦩫𦪧𦮕𦵩𧈪𧉅𧉒𧋘𧍢𧎹𧑎𧒒𧓎𧘂𧜛𧜞𧢜𧣡𧤠𧧸𧭝𧰵𧸜𧹛𧻙𧻷𧼨𧽤𧾑𧾱𧾵𧿓𨀜𨀞𨁑𨃗𨃟𨄇𨄕𨄮𨅠𨆐𨈜𨉸𨋸𨎩𨒫𨙒𨪌𨫕𨯤𨰠𨴏𨵌𩆚𩇟𩉍𩎉𩏠𩐅𩑝𩑢𩑵𩑷𩔶𩕃𩕗𩛎𩜇𩜘𩞫𩦨𩨑𩩍𩩴𩪢𩴻𩵚𩶅𩷹𩸍𩸞𩽏𪄣𪏮𪏸𪑚𪒴𪓑𪓜𪖶𪗆𪘁𪘧𫝙𫝞𫝾𫞭𫞻𫟊𬑎𬖐󸾯󿕅󿗧
* 雖然匯入的注音符號在風格上不太搭，還是暫時使用一下，等有遇到風格上較相似的版本後再更新掉。

### 合併「拾陆字濑户2.0」

* 從拾陆字濑户取得549個符號與中文字：̸̥̭̰̀́̈́⃝⅐⅑⅒↉␀␁␂␃␄␅␆␇␈␉␊␋␌␍␎␏␐␑␒␓␔␕␖␗␘␙␚␛␜␝␞␟␡⧵⨀⨁⨂⨃⨄⨅⨆⨇⨈⨉⨊⨋⨌⨍⨎⨏⨐⨑⨒⨓⨔⨕⨖⨗⨘⨙⨚⨛⨜⨝⨞⨟⨠⨡⨢⨣⨤⨥⨦⨧⨨⨩⨪⨫⨬⨭⨮⨯⨰⨱⨲⨳⨴⨵⨶⨷⨸⨹⨺⨻⨼⨽⨾⨿⩀⩁⩂⩃⩄⩅⩆⩇⩈⩉⩊⩋⩌⩍⩎⩏⩐⩑⩒⩓⩔⩕⩖⩗⩘⩙⩚⩛⩜⩝⩞⩟⩠⩡⩢⩣⩤⩥⩦⩧⩨⩩⩪⩫⩬⩭⩮⩯⩰⩱⩲⩳⩴⩵⩶⩷⩸⩹⩺⩻⩼⩽⩾⩿⪀⪁⪂⪃⪄⪅⪆⪇⪈⪉⪊⪋⪌⪍⪎⪏⪐⪑⪒⪓⪔⪕⪖⪗⪘⪙⪚⪛⪜⪝⪞⪟⪠⪡⪢⪣⪤⪥⪦⪧⪨⪩⪪⪫⪬⪭⪮⪯⪰⪱⪲⪳⪴⪵⪶⪷⪸⪹⪺⪻⪼⪽⪾⪿⫀⫁⫂⫃⫄⫅⫆⫇⫈⫉⫊⫋⫌⫍⫎⫏⫐⫑⫒⫓⫔⫕⫖⫗⫘⫙⫚⫛⫝̸⫝⫞⫟⫠⫡🄀🄁🄂🄃🄄🄅🄆🄇🄈🄉🄊🄌🄐🄑🄒🄓🄔🄕🄖🄗🄘🄙🄚🄛🄜🄝🄞🄟🄠🄡🄢🄣🄤🄥🄦🄧🄨🄩🄰🄱🄲🄳🄴🄵🄶🄷🄸🄹🄺🄻🄼🄽🄾🄿🅀🅁🅂🅃🅄🅅🅆🅇🅈🅉🈐🈑🈒🈕🈖🈗🈘🈙🈚🈛🈜🈝🈞🈟🈠🈡🈢🈣🈤🈥🈦🈧🈨🈩🈪🈫🈬🈭🈮🈯🈰🈱🈲🈳🈴🈵🈶🈷🈸🈹🈺🉀🉁🉂🉃🉄🉅🉆🉇🉈𠀖𠀗𠀡𠀧𠀨𠀪𠀫𠀲𠀳𠀴𠀾𠁂𠁆𠁨𠁪𠂆𠂇𠂊𠂎𠂔𠂪𠂫𠃊𠃋𠃌𠃍𠃑𠃝𠃣𠄌𠄎𠄘𠄧𠆤𠆩𠆫𠆳𠇁𠤎𠤖𠧧𠨑𠩕𠩤𠫾𠬃𠬉𠬍𠬒𠮏𠮨𠮷𠮿𠯅𠯆𠯇𡈼𡿨𤣩𤣰𤣱𤣲𤣳𤣻𤣿𤤀𤤁𤤌𤤖𤤗𤤯𤤳𤤾𤤿𤥀𤥁𥘑𥘪𥘵𩶝𩶟𩶪𩷆𩷉𩷕𩾰𩾷𩿗𩿘𩿙𩿚𩿞𩿦𩿨𪀄𪀅𪀆𪀎𪀐𪃙𪃵𪃸𪃾𪄳你侻兔再冤冬割勇勺卉卿吆周咢善城姬娧寃将屠屮巽帨弢形彫慈憲懶成拔晉冕杞杓桒栟槪櫛沿浩潮炭爵眞真芳芽䕫蜨裞諭軔輸嶲駾

### 合併原作者瀨戶的擴充字

原作者原本另外放的擴充字型檔在合併後，在內海字體增加303字如下：𠀋𠂉𠂢𠂤𠆢𠈓𠌫𠍱𠎁𠏹𠑊𠔉𠗖𠘨𠝏𠠇𠠺𠢹𠥼𠦝𠫓𠬝𠮟𠵅𠷡𠹤𠹭𠺕𠽟𡈁𡈽𡉕𡉴𡉻𡋗𡋤𡋽𡌛𡌶𡍄𡏄𡑭𡑮𡗗𡙇𡚴𡜆𡝂𡢽𡧃𡱖𡴭𡵅𡵢𡵸𡶒𡶜𡶡𡶷𡷠𡸳𡸴𡼞𡽶𡿺𢅻𢈘𢌞𢎭𢛳𢡛𢢫𢦏𢪸𢭆𢭏𢭐𢮦𢰝𢰤𢷡𣆶𣇃𣇄𣇵𣍲𣏐𣏒𣏓𣏕𣏚𣏟𣏤𣑊𣑋𣑑𣑥𣓤𣕚𣖔𣗄𣘸𣘹𣘺𣙇𣜌𣜜𣜿𣝣𣝤𣟧𣟿𣠤𣠽𣪘𣱿𣳾𣴀𣴎𣵀𣷓𣷹𣷺𣽾𤂖𤄃𤇆𤇾𤎼𤘩𤚥𤟱𤢖𤩍𤭖𤭯𤰖𤴔𤸎𤸷𤹪𤺋𥁊𥁕𥄢𥆩𥇍𥇥𥈞𥉌𥐮𥒎𥓙𥔎𥖧𥝱𥞩𥞴𥧄𥧔𥫣𥫤𥫱𥮲𥱋𥱤𥶡𥸮𥹖𥹢𥹥𥻂𥻘𥻨𥼣𥽜𥿔𥿠𥿻𦀌𦀗𦁠𦃭𦉰𦊆𦍌𦐂𦙾𦚰𦜝𦣝𦣪𦥑𦥯𦧝𦨞𦩘𦪌𦪷𦫿𦰩𦱳𦳝𦹀𦹥𦾔𦿶𦿷𦿸𧃴𧄍𧄹𧏚𧏛𧏾𧐐𧑉𧘔𧘕𧘱𧚄𧚓𧜎𧜣𧝒𧦅𧪄𧮳𧮾𧯇𧲸𧶠𧸐𧾷𨂊𨂻𨉷𨊂𨋳𨏍𨐌𨑕𨕫𨗈𨗉𨛗𨛺𨥆𨥉𨥫𨦇𨦈𨦺𨦻𨨞𨨩𨩃𨩱𨪙𨫍𨫝𨫤𨯁𨯯𨴐𨵱𨷻𨸟𨸶𨺉𨻫𨼲𨿸𩊠𩊱𩒐𩗏𩙿𩛰𩜙𩝐𩣆𩩲𩷛𩸕𩸽𩹉𩺊𩻄𩻛𩻩𩿎𪀚𪀯𪂂𪃹𪆐𪎌𪐷𪗱𪘂𪘚𪚲

![原作者瀨戶的擴充字](https://github.com/max32002/naikaifont/raw/master/preview/preview_setofont_ex.png)

### 修正清單
* 「獼」字補二個點。
* 「拜」字補一橫。
* 更新部分「直」和「真」裡的直寫法。
* 更新部分「臽」的寫法。
* 更新部分「益」的寫法。
* 更新部分「黃」的寫法。
* 更新部分「率」的寫法。
* 更新部分「辶」的寫法。
* 更新部分「令」的寫法。
* 更新部分「青」的寫法。
* 更新部分「屯」的寫法。
* 更新部分「曾」的寫法。
* 更新部分「祭」的寫法。
* 更新部分「鬲」的寫法。
* 更新部分「祭」的寫法。
* 更新部分「肖」、「半」的寫法。
* 更新部分「孚」、「妥」的寫法。
* 更新部分「臽」、「舀」的寫法。
* 更新「示」部寫法為「礻」。
* 更新「食」部寫法為「飠」。
* 修改「包」裡的「己」為「巳」，例如：泡、炮、飽。

## 更新日誌
[點擊此處](https://github.com/max32002/naikaifont/blob/master/naikaifont_history.md) 查看更新記錄。

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」，或點進想下載的ttf字型檔案，再點「Download」的按鈕進行下載。

## 網頁字型(Web Font)服務

網頁字型用於網頁上的字型顯示，訪客不需預先安裝字型檔，一樣能夠看到特殊的字型效果。不只是電腦，在智慧型手機和平板裝置的瀏覽器上也可正常顯示。實現該功能的原理是在瀏覽時才下載字型檔。

WebFont建議使用，繁體中文常用字的內海字體-精簡版(檔案大小：2.1MB)，可以服用下面的css:
```
@font-face {
  font-family: naikaifont;
  src: url(https://cdn.jsdelivr.net/gh/max32002/naikaifont@1.0/webfont/NaikaiFont-Regular-Lite.woff2) format("woff2");
}
```

完整的內海字體(檔案大小約16MB)可以服用下面的css:
```
@font-face {
  font-family: naikaifont;
  src: url(https://cdn.jsdelivr.net/gh/max32002/naikaifont@1.89/webfont/NaikaiFont-Regular.woff2) format("woff2");
}
```

## 附註

* 補的缺字，效果差強人意，聊勝於無。
* 「豬」、「箸」日文漢字中的「者」有多一點，保留setofont的寫法，目前有些字的的點有被修改已刪掉，還有一些沒有刪掉多的點。
* 「戶」部件，大多沿用日文寫法「戸」，沒有改成台灣用法「戶」，相較小濑字体就很厲害，大多部份戶都改成為「點」的版本，而不是「橫」。
* 歡迎一起來補字，如果您也有自己造字並且想更新到內海字體裡，請把您的ttf字型檔透過 email(weng.32002@gmail.com)給我，謝謝。由於Max是新手補字，難免補很略醜，如果您也挑戰修改了同一個字，也歡迎寄給我合併，當然您也可以另外再起一個新的字型名稱。

## 著作權與授權

* 本字型是基於 SIL Open Font License 1.1 改造かにさわ(twinklem_seto)所開發、發表的「[瀨戶字體](http://setofont.osdn.jp/)」字型。
* 本字型亦基於 SIL Open Font License 1.1 授權條款免費公開，關於授權合約的內容、免責事項等細節，請詳讀 License 文件。
    * 可自由商用 不需付費、知會或標明作者，即可自由使用此字型，亦可做商業應用。
    * 可自由傳布 可自由分享檔案、將檔案安裝於任何軟硬體中。
    * 可自由改作為其他字型 將字型檔案修改重製為其他字型檔案，改作後的字型檔案須同樣依 Open Font License 釋出。

字體授權小提示：本字型採用 SIL Open Font License 1.1 授權發表，可以免費商用。在 github 上有附上 SIL Open Font License 1.1 的授權文件，如甲方或公司需要出示授權文件，直接使用此文件即可。
    
## 相關網頁

花園家族：
* B2花園 B2 Hana
https://max-everyday.com/2020/08/b2-hana-font/
* 花園肉丸 Hana Meatball
https://max-everyday.com/2020/08/hana-meatball/

簡體/繁體轉換家族：
* 獅尾簡腿黑體 Swei Jay Leg
https://max-everyday.com/2020/11/swei-jay-leg/
* 獅尾簡中黑體 Swei Jay Sans
https://max-everyday.com/2020/11/swei-jay-sans/
* 獅尾簡中宋體 Swei Jay Serif
https://max-everyday.com/2020/11/swei-jay-serif/
* 獅尾繁腿黑體 Swei Fan Leg
https://max-everyday.com/2020/11/swei-fan-leg/
* 獅尾繁中黑體 Swei Fan Sans
https://max-everyday.com/2020/11/swei-fan-sans/
* 獅尾繁中宋體 Swei Fan Serif
https://max-everyday.com/2020/11/swei-fan-serif/

獅尾黑體家族：
* 獅尾右下腿黑體 Swei Right Bottom Leg
https://max-everyday.com/2021/08/swei-right-bottom-leg/
* 獅尾右下圓黑體 Swei Right Bottom Sans
https://max-everyday.com/2021/08/swei-right-bottom-sans/
* 獅尾飛腿黑體 Swei Dart Leg
https://max-everyday.com/2020/11/swei-dart-leg/
* 獅尾飛鏢黑體 Swei Dart Sans
https://max-everyday.com/2020/11/swei-dart-sans/
* 獅尾火腿黑體 Swei Match Leg
https://max-everyday.com/2020/11/swei-match-leg/
* 獅尾火柴黑體 Swei Match Sans
https://max-everyday.com/2020/11/swei-match-sans/
* 獅尾骨腿黑體 Swei Bone Leg
https://max-everyday.com/2020/11/swei-bone-leg/
* 獅尾骨頭黑體 Swei Bone Sans
https://max-everyday.com/2020/11/swei-bone-sans/
* 獅尾斧腿黑體 Swei Ax Leg
https://max-everyday.com/2020/11/swei-ax-leg/
* 獅尾斧頭黑體 Swei Ax Sans
https://max-everyday.com/2020/11/swei-ax-sans/
* 獅尾喇腿黑體 Swei Bell Leg
https://max-everyday.com/2020/11/swei-bell-leg/
* 獅尾喇叭黑體 Swei Bell Sans
https://max-everyday.com/2020/11/swei-bell-sans/
* 獅尾惡腿黑體 Swei Devil Leg
https://max-everyday.com/2020/11/swei-devil-leg/
* 獅尾惡魔黑體 Swei Devil Sans
https://max-everyday.com/2020/11/swei-devil-sans/
* 獅尾麥腿黑體 Swei Marker Leg
https://max-everyday.com/2020/10/swei-marker-leg/
* 獅尾麥克黑體 Swei Marker Sans
https://max-everyday.com/2020/10/swei-marker-sans/
* 獅尾詠腿黑體 Swei Fist Leg
https://max-everyday.com/2020/10/swei-fist-leg/
* 獅尾詠春黑體 Swei Fist Sans
https://max-everyday.com/2020/10/swei-fist-sans/
* 獅尾鋸腿黑體 Swei Alias Leg
https://max-everyday.com/2020/10/swei-alias-leg/
* 獅尾鋸齒黑體 Swei Alias Sans
https://max-everyday.com/2020/10/swei-alias-sans/
* 獅尾尖腿黑體 Swei Spike Leg
https://max-everyday.com/2020/10/swei-spike-leg/
* 獅尾尖刺黑體 Swei Spike Sans
https://max-everyday.com/2020/10/swei-spike-sans/
* 獅尾快腿黑體 Swei Shear Leg
https://max-everyday.com/2020/09/swei-shear-leg/
* 獅尾快剪黑體 Swei Shear Sans
https://max-everyday.com/2020/09/swei-shear-sans/
* 獅尾福腿黑體 Swei Gospel Leg
https://max-everyday.com/2020/09/swei-gospel-leg/
* 獅尾福音黑體 Swei Gospel Sans
https://max-everyday.com/2020/09/swei-gospel-sans/
* 獅尾D滷腿黑體 Swei Del Luna Leg
https://max-everyday.com/2020/09/swei-del-luna-leg/
* 獅尾德魯納黑體 Swei Del Luna Sans
https://max-everyday.com/2020/09/swei-del-luna-sans/
* 獅尾彎腿黑體 Swei Curve Leg
https://max-everyday.com/2020/09/swei-curve-leg/
* 獅尾彎黑體 Swei Curve Sans
https://max-everyday.com/2020/09/swei-curve-sans/
* 獅尾霓腿黑體 Swei Bow Leg
https://max-everyday.com/2020/09/swei-bow-leg/
* 獅尾霓黑體 Swei Bow Sans
https://max-everyday.com/2020/09/swei-bow-sans/
* 獅尾蝙蝠圓體 Swei Bat Sans
https://max-everyday.com/2020/09/swei-bat-sans/
* 獅尾牙膏圓體 Swei Toothpaste
https://max-everyday.com/2020/09/swei-toothpaste/
* 獅尾三腿黑體 Swei 3T Leg
https://max-everyday.com/2020/09/swei-3t-leg/
* 獅尾三角黑體 Swei 3T Sans
https://max-everyday.com/2020/08/swei-3t-sans/
* 獅尾螺帽腿黑體 Swei Nut Leg
https://max-everyday.com/2020/08/swei-nut-leg/
* 獅尾螺帽黑體 Swei Nut Sans
https://max-everyday.com/2020/08/swei-nut-sans/
* 獅尾B2腿黑體 Swei B2 Leg
https://max-everyday.com/2020/07/swei-b2-leg/
* 獅尾B2黑體 Swei B2 Sans
https://max-everyday.com/2020/07/swei-b2-sans/
* 獅尾腿圓 Swei Gothic Leg
https://max-everyday.com/2020/08/swei-gothic-leg/
* 獅尾彩虹腿 Swei Rainbow Leg
https://max-everyday.com/2020/08/swei-rainbow-leg/
* 獅尾XD珍珠 Swei XD Pearl
https://max-everyday.com/2020/07/swei-xd-pearl/
* 獅尾D露西 Swei D Lucy
https://max-everyday.com/2020/07/swei-d-lucy/
* 獅尾半月字體 Swei Gothic
https://max-everyday.com/2020/04/swei-half-moon/
* 台灣圓體 TaiwanPearl
https://max-everyday.com/2020/06/taiwanpearl/
* 獅尾圓體 Swei Gothic
https://max-everyday.com/2020/04/swei-gothic/
* 獅尾黑體 Swei Sans
https://max-everyday.com/2020/03/swei-sans/

獅尾宋體家族：
* 獅尾B2加糖宋體 Swei B2 Sugar
https://max-everyday.com/2020/11/swei-b2-sugar/
* 獅尾加糖宋體 Swei Sugar
https://max-everyday.com/2020/11/swei-sugar/
* 獅尾B2宋朝 Swei B2 Serif
https://max-everyday.com/2020/07/swei-b2-serif/
* 獅尾肉丸 Swei Meatball
https://max-everyday.com/2020/06/swei-meatball/
* 獅尾四季春字體 Swei Spring
https://max-everyday.com/2020/04/swei-spring/

其他字體：
* 馬路口圓體 Maruko Gothic
https://max-everyday.com/2021/07/maruko-gothic/
* 苦累蛙圓體 Kurewa Gothic
https://max-everyday.com/2021/06/kurewa-gothic/
* 何某手寫體 Nani Font
https://max-everyday.com/2020/09/nanifont/
* 內海字體  Naikai Font
https://max-everyday.com/2020/03/naikaifont/
* 莫大毛筆字體 Bakudai Font
https://max-everyday.com/2020/03/bakudaifont/
* 正風毛筆字體 Masa Font
https://max-everyday.com/2020/05/masafont/
* 假粉圓體 Fake Pearl 
https://max-everyday.com/2020/03/open-huninn-font/
* 俊羽圓體 Yu Pearl 
https://max-everyday.com/2020/03/yupearl/

其他網站：
* 清松手寫體 JasonHandWriting
https://jasonfonts.max-everyday.com/
* Max學習字體相關的筆記
https://codereview.max-everyday.com/font-readme/

## 贊助Max

很高興可以替中華民國美學盡一分心力、讓台灣擁有更好的文字風景，希望能提供另一種美學讓大家選擇。

如果你想支持或打賞Max，贊助方式如下：
https://max-everyday.com/about/#donate
