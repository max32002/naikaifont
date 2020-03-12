「內海字體」是基於[瀨戶字體](http://setofont.osdn.jp/)的開放原始碼中文字型，目前字型內文字和符號字數在：31,840個。

## 字體特色

### 彌補繁體中文常用字缺字缺憾

補齊台灣教育部列出的 4,808 個常用字，在原本的瀨戶字體架構下，內海字體增加65字如下：螃螎螞蟈蟑諉賅賒賬贗趟趴跺踩踫踱蹝蹦蹺躂躉躲躺逛遴鄉醣鈉鈣鈽鈾鉻銬銳銻銼鋁鋅錳錶鎂鎊鎢鎳鏍鐮閡閱闆阱陴霉靶頹颳餵餿饞馱鬍鱖鵪鷥麂鼴齜

### 5種字重(Style)

* Light
* Regular
* Medium
* SemiBold
* Bold

原本的瀨戶字體放在Medium 字重裡，透過程式自動產生Light、Regular、SemiBold、Bold 新的字重。Regular字重是把原本的setofont微微調細一點點。在Light的字重裡，可能會因為筆劃太細造成某些筆畫消失。在SemiBold和Bold的字重裡，可能會因為筆劃太粗造成某些筆畫重疊難以識別，有粗體字的需求，可以先挑戰使用Bold字重看看，如果發現效果不如預期，再改用SemiBold字重。

不能確定自動產生出來的字重裡每一個都是完整的字，畢盡程式會誤判是常有的事情，所以不是在Medium字重裡的筆劃可能會消失。

![內海字體](https://github.com/max32002/naikaifont/raw/master/preview/preview.png)

### 清除 setofont 裡空白的文字

瀨戶字體setofont 裡有很多空白的字， 會造成無法讓系統自動用預設字體來補字，已清除空白的文字。

### 調整標點符號位置

瀨戶字體的全形標點符號針對日本做設計，調整為台灣常見的置中用法。半形的 backslash，調整為非日本地區用法。

### 增加「臺灣閩南語推薦用字700字表」裡出現的中文字

在原本的瀨戶字體架構下，內海字體增加47字如下：㧒㧳㪗㾪䆀䉔䘼䩉䫀䫌螿蟧蟮蟳蠩覕譀趒趖跍跔跤踅踮蹛軁迌遢邋鐤雺頦骿魩鰇𠕇𠢕𠲿𢓜𣍐𤆬𤏸𤺪𥰔𥴊𨑨𡳞

![臺灣閩南語推薦用字700字表](https://github.com/max32002/naikaifont/raw/master/preview/preview_taiwaness.png)

### 增加部份的粵語字

感謝網友scott luke的貢獻，在內海字體增加40字如下：㓤㖡㖭㖿㗎㗾㧬㨘㩒㬹㷫㹴䁪䢂䱽螆蠄裇覅趷踎踭蹾躀躝軚輋酶醖鈈鈪鎅鐧閪餸骾髧鮋鯭鰂

![部份的粵語字](https://github.com/max32002/naikaifont/raw/master/preview/preview_hongkong.png)

### 合併原作者瀨戶的擴充字

原作者原本另外放的擴充字型檔在合併後，在內海字體增加303字如下：𠀋𠂉𠂢𠂤𠆢𠈓𠌫𠍱𠎁𠏹𠑊𠔉𠗖𠘨𠝏𠠇𠠺𠢹𠥼𠦝𠫓𠬝𠮟𠵅𠷡𠹤𠹭𠺕𠽟𡈁𡈽𡉕𡉴𡉻𡋗𡋤𡋽𡌛𡌶𡍄𡏄𡑭𡑮𡗗𡙇𡚴𡜆𡝂𡢽𡧃𡱖𡴭𡵅𡵢𡵸𡶒𡶜𡶡𡶷𡷠𡸳𡸴𡼞𡽶𡿺𢅻𢈘𢌞𢎭𢛳𢡛𢢫𢦏𢪸𢭆𢭏𢭐𢮦𢰝𢰤𢷡𣆶𣇃𣇄𣇵𣍲𣏐𣏒𣏓𣏕𣏚𣏟𣏤𣑊𣑋𣑑𣑥𣓤𣕚𣖔𣗄𣘸𣘹𣘺𣙇𣜌𣜜𣜿𣝣𣝤𣟧𣟿𣠤𣠽𣪘𣱿𣳾𣴀𣴎𣵀𣷓𣷹𣷺𣽾𤂖𤄃𤇆𤇾𤎼𤘩𤚥𤟱𤢖𤩍𤭖𤭯𤰖𤴔𤸎𤸷𤹪𤺋𥁊𥁕𥄢𥆩𥇍𥇥𥈞𥉌𥐮𥒎𥓙𥔎𥖧𥝱𥞩𥞴𥧄𥧔𥫣𥫤𥫱𥮲𥱋𥱤𥶡𥸮𥹖𥹢𥹥𥻂𥻘𥻨𥼣𥽜𥿔𥿠𥿻𦀌𦀗𦁠𦃭𦉰𦊆𦍌𦐂𦙾𦚰𦜝𦣝𦣪𦥑𦥯𦧝𦨞𦩘𦪌𦪷𦫿𦰩𦱳𦳝𦹀𦹥𦾔𦿶𦿷𦿸𧃴𧄍𧄹𧏚𧏛𧏾𧐐𧑉𧘔𧘕𧘱𧚄𧚓𧜎𧜣𧝒𧦅𧪄𧮳𧮾𧯇𧲸𧶠𧸐𧾷𨂊𨂻𨉷𨊂𨋳𨏍𨐌𨑕𨕫𨗈𨗉𨛗𨛺𨥆𨥉𨥫𨦇𨦈𨦺𨦻𨨞𨨩𨩃𨩱𨪙𨫍𨫝𨫤𨯁𨯯𨴐𨵱𨷻𨸟𨸶𨺉𨻫𨼲𨿸𩊠𩊱𩒐𩗏𩙿𩛰𩜙𩝐𩣆𩩲𩷛𩸕𩸽𩹉𩺊𩻄𩻛𩻩𩿎𪀚𪀯𪂂𪃹𪆐𪎌𪐷𪗱𪘂𪘚𪚲

![原作者瀨戶的擴充字](https://github.com/max32002/naikaifont/raw/master/preview/preview_setofont_ex.png)

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」，或點進想下載的ttf字型檔案，再點「Download」的按鈕進行下載。

## 附註

* 補的缺字，由於缺乏設計美感，所以效果差強人意，但是聊勝於無。
* 目前是Beta公測版本，歡迎提供測試反饋，請直接反饋在GitHub的Issues中。
* 「豬」、「箸」日文漢字中的「者」有多一點，保留setofont的寫法，目前沒有刪掉多的點。
* 「偏」字上面沿用日文寫法「戸」，沒有改成台灣用法「戶」。
* 只要是 setofont 中有的，都不會被刻意移除，除了空白的字。
* 歡迎一起來補字，如果您也有自己造字並且想更新到內海字體裡，請把您的ttf字型檔或是把您增加的字匯出成svg檔，透過email(weng.32002@gmail.com)給我，謝謝。

## 著作權與授權

* 本字型是基於 SIL Open Font License 1.1 改造かにさわ(twinklem_seto)所開發、發表的「[瀨戶字體](http://setofont.osdn.jp/)」字型。
* 本字型亦基於 SIL Open Font License 1.1 授權條款免費公開，關於授權合約的內容、免責事項等細節，請詳讀 License 文件。
    * 本字型可自由使用在印刷、影像、網路或任何媒體上，不限個人或商業使用。
    * 您可基於 SIL Open Font License 1.1 的規定再散佈或改造本字型。
    
    
## 相關文章

* 內海字體 (NaikaiFont) 
https://max-everyday.com/2020/03/naikaifont/
* 莫大毛筆字體 (Bakudai)
https://max-everyday.com/2020/03/bakudaifont/
* 清松手寫體 (JasonHandWriting)
https://jasonfonts.max-everyday.com/

## 相關影片

* [MaxCodeReview] FontForge 補缺字：㧳 (內海字體)
https://youtu.be/ugrR1Oh0LSw
* [MaxCodeReview] FontForge 補缺字：鷥 (內海字體)
https://youtu.be/9ho81gUPKjc
* [MaxCodeReview] FontForge 補缺字：麂 (內海字體)
https://youtu.be/Izft1O-e22g
* [MaxCodeReview] FontForge 補缺字：鼴 (內海字體)
https://youtu.be/N4hCLq-Db9A
* [MaxCodeReview] FontForge 補缺字：齜 (內海字體)
https://youtu.be/X4X-m-vthw8
* [MaxCodeReview] FontForge 補缺字：霉 (內海字體)
https://youtu.be/QjZNT8uBwMg
