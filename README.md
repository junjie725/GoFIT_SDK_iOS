[![GOLiFE Logo](http://www.goyourlife.com/images/common/logo.png)](http://www.goyourlife.com)

# GoFIT SDK for iOS — [GOLiFE 手環](http://www.goyourlife.com/zh-TW/productlist/#health) App 介接 SDK

此為 [GOLiFE](http://www.goyourlife.com) 釋出之官方 iOS App SDK (`Community Edition`).

讓任何人都可以藉由本 SDK，直接拿 [GOLiFE 市售手環](http://www.goyourlife.com/zh-TW/productlist/#health) 就可以連接、取資料。


## What's This?
- iOS App 的開發人員，可藉由本 SDK 的整合，便可輕輕鬆鬆快速完成開發。
- 並且，即刻就可直接與市面上 [GOLiFE](http://www.goyourlife.com) 出品銷售之 GOLiFE [Care 系列手環](http://www.goyourlife.com/zh-TW/productlist/#health) 裝置連接。達成包括連線、配對、同步、設定等等各項功能。
- 使用範例 : 官方版 GOLiFE's [GoFIT App (Apple's App Store 下載)](https://itunes.apple.com/tw/app/golife-fit/id834110307?l=zh).


## 從哪開始??
1. 請到 [Release 區](/../../releases) 下載 : 包括 Demo App 的 source code (壓縮檔) 與 SDK libraray (.a)

2. 再請到 [GoFIT SDK 申請表](https://docs.google.com/forms/d/1WutpWDV6VlGUhq2RZs2takjcGKHctG2GYfNQr81CA-0/) 申請試用憑證
    - 請不用擔心，僅是請您留個聯絡方式，只需填寫 email 或電話大名等等，然後選擇您要搭配使用的裝置即可。我們收到後便會馬上回覆 30 天的試用憑證給您~
    - 非常歡迎 **為學術研究用途提供更長免費效期** -- 請您只需在申請表上註明，我們都非常樂意為您提供
    - 或是您有意用於 **商業用途或是客製合作**，也是請您在申請表上註明，或是歡迎您來信 [聯繫我們](http://www.goyourlife.com/zh-TW/feedback/)

3. 將收到的憑證，整合進您的 App 內 &rArr; 請參考我們的 Wiki : [Demo App (SDK 的安裝與 compile)](/../../wiki/Demo-App-(SDK-%E7%9A%84%E5%AE%89%E8%A3%9D%E8%88%87-compile))

4. Then you are good to go!!! :grin: 就是這麼簡單~
    - (當然囉，您手邊必須要先有一台我們的裝置 :stuck_out_tongue_closed_eyes: — [GOLiFE 手環](http://www.goyourlife.com/zh-TW/productlist/#health))
    - 還有，首次啟動，會對您收到的憑證做驗證，並下載授權 &rArr; 所以，首次啟動請要連網喔!!!~

**商業用途或是客製合作**，都非常歡迎您來信 [聯繫我們](http://www.goyourlife.com/zh-TW/feedback/)


## Demo App
請參考我們的 [Wiki](/../../wiki) : [Demo App (SDK 的安裝與 compile)](/../../wiki/Demo-App-(SDK-%E7%9A%84%E5%AE%89%E8%A3%9D%E8%88%87-compile))

※ 請注意，repostitory 內附為使用 Xcode v9.3 或以上。如果您不想升級 Xcode 而想使用較低版本，可以試著將 .xcodeproj 裡面的 `compatibilityVersion`, `objectVersion` 修改如下 : 

 ```
 compatibilityVersion = "Xcode 8.0"
 objectVersion = 48
 ```

## API SPEC
請參考我們的 [Wiki](/../../wiki) : [API SPEC](/../../wiki/GoFIT-SDK-iOS-Application-Programming-Interface-Specifications)


## Copyright and License
此為 `Community Edition`.

智慧財產權為 [GOLiFE](http://www.goyourlife.com) 所有。

&copy; 2018 GOYOURLIFE INC. 

http://www.goyourlife.com
