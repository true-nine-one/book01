# 如何將gitbook組織的內容 同步到github
#### how to sync gitbook Organizations content with github
###### #
* 基本內容
 * gitbook組織的內容 要用github組織來同步
 
###### #

1.

登入gitbook(建議用github帳號登入)

在個人gitbook設定中連結github帳號(Install integration on this account)

連結成功後 Integration 跟 Account 旁邊都會有綠色勾勾

![Imgur](http://i.imgur.com/K5iXjuw.jpg)


2.

新建github組織(Organizations)

建立完成後

到

https://github.com/settings/applications

點gitbook

底下有 Organization access

選取你新建的github組織 

點(grant access)

組織名稱旁邊的紅叉叉會變成綠勾勾 就表示成功

![Imgur](http://i.imgur.com/LNt4qEQ.jpg)


3.

新建gitbook組織 (Organizations)

建立完成後

到

新書的設定中>github分頁裡>integration項目>選取github組織>安裝integration

點(Install integration on this account)

![Imgur](http://i.imgur.com/nsHYQJV.jpg)


4.

在github組織中新建一個新repo

在gitbook組織中新建一本書

在新書設定中的github分頁>選擇github組織的新repo

點(sync)同步

若出現的是紅叉叉就點左邊的(force sync using gitbook content) 

之後gitbook新書的內容會複製到github新repo裡

![Imgur](http://i.imgur.com/vtj3xlZ.jpg)



###### #結束


