**JUNCTIONxSEOUL 2019 HACKATHON**<br>
**Date: 2019.05.10 ~ 12 (3days)**<br>
## 이 서비스는 창업을 할 수 있다는 가정하에 기획되었습니다. 만약 우리의 서비스모델에 관심이 있다면 연락주세요!<br><br>This service was designed with the assumption that you can start a business. If you are interested in our service model, please contact us!<br>_stopdragon@sharpzerosix.com_<br><br><br>

![1](https://raw.githubusercontent.com/cadit/JUNCTIONxSEOUL-Design/master/preview/summary.png)
<br><br><br>
![2](https://raw.githubusercontent.com/cadit/JUNCTIONxSEOUL-Design/master/preview/summary_none_logo_blur.png)

## INFORMATION

**Team Name: idiot-brothers**

**our service name : CADIT (캐딧)**

**Track: API HACK**

![Team Members](https://raw.githubusercontent.com/cadit/JUNCTIONxSEOUL-Design/master/preview/TEAM%20Members.jpg)

[[Go to Github]](https://github.com/cadit)

[[Try XD prototype]](https://xd.adobe.com/view/9e2297c0-5629-4993-70f3-aac812ec2d60-e813/?fullscreen&hints=off)
<br><br><br>
## Because the translator is used, the word order and the grammar may be wrong. If you do not understand anything or something, I will try my best to explain it and undertanding you.<br><br>翻訳機を使用したため、語順や語法が間違っていることがあります。理解していない部分は質問していただければ最善を尽くして説明しましょう。
<br><br><br>
## Survice introduction

![intro1](https://raw.githubusercontent.com/cadit/JUNCTIONxSEOUL-Design/master/preview/Expla_1.jpg)

캐딧은 사용자가 일상생활에 소비하는 금액의 일정 퍼센트를 자동으로 저축해주는 서비스입니다.<br>
‘CADIT’ is a service that automatically saves a percentage of the amount you spend on your daily life.<br>

![intro2](https://raw.githubusercontent.com/cadit/JUNCTIONxSEOUL-Design/master/preview/Expla_2.jpg)

사용자가 결제한 금액의 일정금액을 은행 계좌에서 자동으로 출금합니다. 출금된 금액은 캐딧 회사명의 개인 가상계좌로 입금됩니다.(은행권 공동 API 사용)<br>
You can save a certain amount of money you've made from your bank account, We will automatically withdraw funds. 
The amount withdrawn is the name of the CADIT company.(using the KFTC-API)<br>

![intro3](https://raw.githubusercontent.com/cadit/JUNCTIONxSEOUL-Design/master/preview/Expla_3.jpg)

목표 금액을 달성하면 사용자는 원금과 그에 대한 이자를 추가로 얻을 수 있습니다.<br>
When you achieve the goal, you can get principal and additional interest.(interest can be change because of _Reserve Requirement System_)<br>

## Service Process

![sp](https://raw.githubusercontent.com/cadit/JUNCTIONxSEOUL-Design/master/preview/Expla_4.jpg)<br><br>

1. Users make purchases as usual. <br>
사용자는 평소와 같이 구매를 합니다. <br>
ユーザーはいつものように購入をします。<br>

2. Use KFTC-API to import users purchases into CADIT.<br>
KFTC API를 이용하여 사용자의 구매내역을 CADIT으로 불러옵니다.<br>
KFTC APIを利用して、ユーザーの購入履歴をCADITにロードします。<br>

3. A certain percentage of the purchase amount is withdrawn from the user's account. (The amount withdrawn is temporarily owned by CADIT.)<br>
구매 금액의 일정 퍼센트를 이용자의 통장에서 출금합니다. (출금한 금액은 CADIT이 임시소유합니다.)<br>
購入金額の一定割合を、利用者の通帳から引き出します。 （出金した金額は、CADITが一時的所有します。）<br>

4. Provide additional incentives to users for a certain amount of revenue earned from savings deposits.<br>
저축된 예금으로 벌어들인 수익의 일정금액을 사용자에게 추가 인센티브로 줍니다.<br>
貯蓄預金で稼いだ収入の一定量をユーザーに追加インセンティブとしてします。<br>

5. User can not Withdraw until reach the Goal amount.<br>
사용자는 Goal금액에 도달 할 때까지 Withdraw할 수 없습니다.<br>
目標額に達するまで撤回することはできません。<br>

## Conditions for Service Maintenance and FUTRE PLAN/REVENUE MODEL

1. CADIT is a service that can help users achieve your goals and evolve into a big new financial platform rather than a simple savings service.<br>
CADIT은 사용자의 목표 달성을 이룰 수 있게 도와주고 단순 저축 서비스가 아닌 거대 신금융 플렛폼으로 발전할 수 있는 서비스입니다.<br>
CADITは、単純な貯蓄サービスではなく、あなたの目標を達成し、大きな新しい金融プラットフォームへと進化させるのに役立つサービスです。<br>

2. To obtain maximum revenue, _interest calculations_ are calculated using breakeven points. (The _prototype version service_ interest must be floating, because there is no mathematics major in our team, it is calculated as a fixed value.)<br>
최대 수익을 얻기 위해 이자 계산은 손익분기점을 이용하여 계산합니다. (원래 이자는 유동적이여야하지만 수학전공자가 없기때문에 고정값으로 계산하였습니다.)<br>
最大の利益を得るために利子の計算は、損益分岐点を利用して計算します。 （元の利子は流動的でなければですが、数学専攻がないため、固定値で計算しました。）<br>

3. The CADIT service has a profit structure that can hold a lot of cash. So you do not have to do anything to earn interest income. If you want to make more money, you can also use your deposits to make an investment.<br>
CADIT 서비스는 현금을 많이 보유할 수 있는 수익구조를 가지고 있습니다. 따라서 아무것도 하지 않아도 이자수익이 생깁니다. 더 많은 수익을 원한다면 사용자들의 예금을 이용하여 투자를 해볼 수도 있습니다.<br>
CADITサービスは現金の多くを保持することができる収益構造を持っています。したがって、何もしなくても利子収益が生じます。より多くのお金が必要な場合、ユーザーの預金を利用して投資をみることができます。<br>

4. If we take advantage of CADIT's high cash reserves and _Reserve Requirement System_, which is commonly used all over the world, you can expect much more profit from your loan service.<br>
현금보유액이 많다는 CADIT의 장점과 전세계에서 공통으로 사용하는 지급준비제도를 활용한다면 대출서비스를 통해 훨씬 많은 수익을 기대할 수 있습니다.<br>
現金保有額が多いCADITの利点と、世界で共通に使用される支払準備制度を活用すれば融資サービスを介して、はるかに多くの利益を期待することができます。<br>
[What is "Reserve Requirement System"?](https://ko.wikipedia.org/wiki/%EC%A7%80%EA%B8%89%EC%A4%80%EB%B9%84%EC%A0%9C%EB%8F%84)<br>
[You can watch about "Reserve Requirement System"Documentary](https://youtu.be/0LYMTsj_eqc?t=1390)<br>

5. In the future, we will find the bank APIs of each country and develop it as a service that can be used all over the world.<br>
추후 각국의 은행 API를 찾아 전세계에서도 이용할 수 있는 서비스로 발전시킬것입니다.<br>
今後、各国の銀行のAPIを探して世界中で利用できるサービスとして発展させることです。<br>

![RM](https://raw.githubusercontent.com/cadit/JUNCTIONxSEOUL-Design/master/preview/Expla_5.jpg)

<br>

![FP](https://raw.githubusercontent.com/cadit/JUNCTIONxSEOUL-Design/master/preview/Expla_6.jpg)

## Which API Used?

![Used API](https://raw.githubusercontent.com/cadit/JUNCTIONxSEOUL-Design/master/preview/Expla_7.jpg)
**개발 상황에 따라서 변경된 내용이 있을 수도 있습니다. 이미지는 참고용으로 사용하세요.**<br>
**There may be changes in development status. Please use the image for reference.**<br>
**開発状況が変わる可能性があります。参考のために画像を使用してください。**<br>
<br>
## The Rakuten API was used as follows:
- [Nexmo SMS Messaging](https://english.api.rakuten.net/nexmo/api/nexmo-sms-messaging)
    - Register Phone Number `Verify` Message.
- [Web Search](https://english.api.rakuten.net/contextualwebsearch/api/web-search)
    - Entering a title in my goal setting will automatically match the `image`.
- [HTML To PDF](https://english.api.rakuten.net/restpack/api/html-to-pdf-conversionf)
    - Prints out the items that you purchased from the Dashboard to `PDF`.
- [Noodlio Pay - Smooth Payments with Stripe](https://english.api.rakuten.net/noodlio/api/noodlio-pay-smooth-payments-with-stripe)
    - `Validation` is carried out when the user registers the card.

## Other API:
- Korea Finacial Telecommuniations & Clearings Insitute API
    - Account real name check
    - Transaction details check
    - Deposit / Withdrawal transfer

## Server Architecture
- AWS EC2 (production)

## Server Stack
- Laravel (PHP Framework)
- MySQL

## Swagger API Documentation
![3](https://raw.githubusercontent.com/cadit/laravel-cadit/master/swagger.png)

## Criteria
- Inventiveness
    - Clear problem statement/how well the product/solution fit the problem.
    - How unique is your product/solution compared to existing competitors?

- Functionality
    - Does it work technically? 
    - Is the code well written? 
    - Bonus points for design and aesthetics. 

- API Power 
    - Did you use at least 3 APIs from Rakuten RapidAPI?
    - How did you leverage APIs in your application?
    - How well did you apply APIs to:
        - Access data
        - Provision functionality
        - Leverage innovative technologies

- Viability
    - Does your code scale in the real world?
    - Does your product/solution provide value for users?

- Submissions
    - Submissions should be in the form of a functional application, ideally website or web app. 
    - Each submission must use at least 3 APIs from Rakuten RapidAPI.

