# 憲法及其下位法工程

為了保證中國大陸在中共垮臺後迅速走上正軌，我們現在就應當着手準備新的中國的
法律體系。本倉庫就是為此而存在的。全套的法律體系是一個大工程，但是至少應當
在中共倒臺前應該有一部甚至幾部憲法可供選擇，歡迎各路英才出謀劃策，更歡迎每一位
（不管是來自哪個國家）貢獻自己的憲法或下位法草案，或者參與修改以有的草案。
本倉庫還接受對其他人的看法或者法律草案進行評論。

## 本倉庫的文件系統結構

* [README.md](README.md)， 就是本文件。
* [Makefile](Makefile) 是一個 GNU make 腳本，用於維護本倉庫。
* [refs/](refs) 是一個目錄，內含世界各國歷史上曾經出現過的值得借鑑的
  法律文本，包括目前仍然在實行的法律文本。各法律文本儘可能以其官方公布的版本
  為准，同時還可以附帶中文譯本。每一個國號（包括已經不存在的國號）對應着該目錄
  下的一個子目錄，在該子目錄下收集該國號頒布過的法律文本。
    * [README.md](refs/README.md) 該子目錄下的 README 文件。
    * [ROC/](refs/ROC) 中收錄中華民國在各個歷史時期頒布或施行的法律文本。
    * [HongKong-UK/](refs/HongKong-UK) 中存放港英時期頒布和施行的法律文本。1997
    年之後在香港施行的法律文本不再收錄。
    * [USA/](refs/USA) 中收錄美國自獨立後頒布或施行的法律文本。
    * [UK/](refs/UK) 中收錄英國自憲政以來的法律文本。
    * [Japan/](refs/Japan) 收錄日本自 1945 年之後頒布和施行的法律文本。
    * [ml-CN/](refs/ml-CN) 收錄大陸和海外民主人士獨立於本項目制定的憲法草案等。
    * [UN](refs/UN) 收錄聯合國的相關憲章、宣言、條約等。
* [R4C/](R4C) 是一個目錄，目錄名為 **request for comments** 的縮寫，內含為後中共
  時期的中國制訂的法律文本草案，
  以供中共倒臺後新中國建國時選擇。在該目錄下，每一個子目錄內是一套相對獨立和
  完整的法律文本草案，擁有相對固定的一個或一組作者（作者有多人的，需要從中
  自行推舉一位維護人），其中應當有
    * `README.md`，用於說明該子目錄中的其他文件，必備；
    * 憲法草案（或相當於憲法的草案），必備；
    * 與該憲法草案相配套的下位法，可選；
    * 以及作者的立法哲學、原理等方面的說明，可選；
    * 還可以包括作者收納的其他人的評論和建議，可選。
* [comments/](comments) 是一個目錄，存放不能收入 [refs/](refs) 或 [R4C/](R4C)
  中的各類評論、建議等。
    * [README.md](README.md)，用於說明該目錄下的其他文件；
    * 打算長期供稿的作者，可以考慮在該目錄下建立自己專屬的子目錄，將自己主筆的
      文章置於其中並自行維護。
* [support/](support) 是一個目錄，用於存放參與本工程的規則以及技術支持等方面的
  文章，以及相關的建議。

**本倉庫中的所有目錄都對參與者開放。**
只要是具有建設性的文章或草案，而且符合建立民主、法治和自由社會這個大方向，措辭
中肯、邏輯性強，而不是歪攪胡纏、攻擊謾罵，則不管文章的觀點如何，都可以收錄。
例如，基於聯邦制主張、各地區獨立建國主張的觀點和憲法草案都可以收納，但是基於
專制主義的憲法草案就不予收納。

**有關本倉庫的鏈接**

* 參與者正式網址 (暗網網址): <http://git.idk.i2p/rebuild-roc/legal-sys>
* 上述網址的洋蔥暗網網址: <https://47ggr2fa3vnwfyhvgskzdmr3i32eijwymxohtxsls45dulmriwxszjad.onion/rebuild-roc/legal-sys>
* 面向公衆的開放網址: <https://github.com/rebuild-roc/legal-sys>
* 面向公衆的開放網址: <https://gitlab.com/rebuild-roc/legal-sys>
