# ajashop
## 組員介紹
* Archer (阿全)
  * 工作型態與領域
    * 全職工作
    * 領域為 IIoT
  * 興趣
    * 旅遊、研究技術、寫作、教學
* Jacs
  * 工作型態與領域
    * 全職工作
    * 領域待補充
  * 興趣
    * 待補充
* Alvis
  * 工作型態與領域
    * 全職工作
    * 領域 產品設計，機械設計
  * 興趣
    * 電影，料理，瑜珈，maker
  
* ㊟ AJA 代表小組成員三個人的英文名字字首組合而成，故取名為 ajashop

## 為何選做電子商務這個主題？有解決什麼問題？期待這個產品達到什麼目的？
* 為何選做電子商務這個主題？
  * 待補充
* 有解決什麼問題？
  * 待補充
* 期待這個產品達到什麼目的？
  * 待補充

## 開發流程
![](https://oranwind.s3.amazonaws.com/2019/Nov/_____2019_11_19___2_32_28-1574145171619.png)

## 專案管理與流程繪製工具
* Google 試算表
* GitHub Project
  ![](https://oranwind.s3.amazonaws.com/2019/Nov/1_24g7O7hLYotolsIDtR9fuA-1574142315609.png)
* lucidchart
  * https://www.lucidchart.com/documents/edit/8d943dc1-de3f-4c8e-a2bf-d68669fbaa69/YGcM5DNywbTK?shared=true
* Wireframe
  * 待補充 ( 使用的軟體 )
  
## 規格範圍、開發順序與時程規劃
* 產品規格明確範圍與定義
  * https://github.com/ArcherHuang/e-commerce/blob/master/project-intro.md#3-%E5%B0%88%E6%A1%88%E6%9C%80%E7%B5%82%E7%9A%84%E6%A0%B8%E5%BF%83-user-story
* 如何決定產品開發的優先順序？哪個功能要先開發？哪些功能是需要合併開發的？
  * 待補充
* 時程規劃
  * Ref [AJA -  畢業專案簡報 Page 7](https://docs.google.com/presentation/d/1eEFugzsHLU2zndnr_4QGcI4YsZLs-XfPL38dQUcSa2Q/edit?folder=1RGHRIP7m1JHTc-bpsIt2flYp63h0ahQS#slide=id.g78f9a65bac_0_354)
  ![](https://oranwind.s3.amazonaws.com/2019/Nov/_____2019_11_19___3_48_43-1574149747189.png)
  
## 系統亮點 ( 第三方 API 和工具應用 )
* 雲端平台

| 編號 | Cloud Platform |        說明        |
|:----:|:----------:|:------------------:|
|  1  |    AWS S3 / Imgur |  存放產品照片 |
|  2  |   AWS EC2  |  架設 Node-Red |
|  3  |   Heroku  |  部署 ajashop 系統 |

* 第三方工具  

| 編號 | 第三方套件 |        說明        |
|:----:|:----------:|:------------------:|
|  1  |    Redis   |  註冊帳號與忘記密碼連結時效  |
|  2  |   Mailgun  |      寄送 email      |
|  3  |   AddThis  |    Share Facebook Button    |
|  4  |   Swagger  | API 說明與測試環境 |
|  5  |   Node-Red  | Flow-Based Programming (FBP) & Message Queue |
|  6  |   Stripe  | 國外金流 |
|  7  |   藍新金流  | 國內金流 |
|  8  |   Cloudflare  | CDN、DNS 與 https |

* 前端套件
  * Bootstrap
  * animate.css
    https://daneden.github.io/animate.css/
  * owl-carousel
    https://owlcarousel2.github.io/OwlCarousel2/
  * POPPER.JS
    https://popper.js.org/index.html#example10

* 特別功能
  * Cron Job
  
* 補充說明
  * Swagger
    ![](https://oranwind.s3.amazonaws.com/2019/Nov/1_af0sASMU75aaV5AkRmJ9HA-1574142401713.png)
    
  * Redis
    ![](https://oranwind.s3.amazonaws.com/2019/Nov/_____2019_11_19___1_49_01-1574142553916.png)
    
  * Node-Red [( Issue )](https://github.com/ArcherHuang/e-commerce/issues/218)
    ![](https://oranwind.s3.amazonaws.com/2019/Nov/1_RyWCsGqAOXS42RPy6vnMAA-1574142582374.png)
    ![](https://oranwind.s3.amazonaws.com/2019/Nov/_____2019_11_08___1_46_56-1573192035760.png)
    
  * Cloudflare
    ![](https://oranwind.s3.amazonaws.com/2019/Nov/1_FXt0vqd5_kZK7cwfdqwIfw-1574142612645.png)
    
  * AddThis
    ![](https://oranwind.s3.amazonaws.com/2019/Nov/1_ImKeGJHdaAX4CSx6h3ve3A-1574142649095.png)

  * Stripe
    * 待補充

## 系統測試
* 小組成員進行全功能測試
* 非小組成員的外部 PM & RD 人員協助測試
* 小組成員進行隨意測試

## Demo
* 開發者功能
  * [Swagger](https://ajashop.co/api-docs/)
    * Admin 管理者登入 - JSON Web Token ( JWT )
    * 取得產品分類
* 使用者功能
  * ① 忘記密碼
  * ② Stripe
  * 待補充
* 管理者功能
  * ① 選取使用者寄送 Coupon
  * ② Order 管理
  * ③ 查看 Stripe
  
## 使用者回饋
* 待補充

## 開發畢業專案時最享受、挑戰或最值得做的部分
* Archer
  * 最享受的部分
    * 規劃大致上都有照著劇本走
  * 最挑戰的部分
    * 要在最有限的時間內完成所需的功能
  * 最值得做的部分
    * 專案開發初期先選定專案管理工具 ( GitHub Project )、定義開發流程與整併 Swagger 以方便開發人員後續工作
* Jacs
  * 待補充
* Alvis  
  * 最享受的部分
    * 專案從無到有，開發的過程
  * 最挑戰的部分
    * 在被google大神遺棄下，一步一步刻下各個功能。
  * 最值得做的部分
    * 每個步驟，每個過程，每項失敗，都是值得的部分。
  
## 系統的未來發展
* Archer
  * 撰寫自動化測試程式與自動化部署至 Public Cloud Platform ( AWS or Azure )
  * 使用 Public Cloud Platform 的 MQ
  * 前後端分離
  * 寄信功能改用 AWS
  * 產品照片皆傳到 AWS
  * 加強使用者認證功能
* Jacs
  * 待補充
* Alvis  
  * 前期的前後端結合，方便後端測試系統穩定度，再來帶入vue框架，實行前後端分離，完整實現跨平台。
  * 細節修改，更貼近使用者的UI，更吸引消費者的眼光。  
  
---
* Product Objectives
  * 想解決的核心問題究竟是什麼？
  * 期待這個產品達到什麼目的？
* Product Scope
  * 產品規格需要有明確範圍與定義 -- 在不同的階段，清楚說明該做什麼以及不做什麼。
* Product Priority
  * 如何決定產品開發的優先順序？
  * 哪個功能要先開發？
  * 哪些功能是需要合併開發的？
