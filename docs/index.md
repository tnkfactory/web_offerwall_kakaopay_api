## 카카오페이 혜택플러스 (모바일 웹 충전소) 연동 가이드 

## 개요
본 문서는 카카오페이 혜택플러스(포인트 충전소) 연동을 하기 위한 방법을 설명하고 있습니다.  

## 1. 회원가입
티앤케이팩토리([https://www.tnkfactory.com](https://www.tnkfactory.com))사이트에 접속 하여 회원가입 및 계정등록을 합니다.

![img](https://cdn4.tnkfactory.com/tnk/shop/12341.jpg)

## 2. 앱등록 및 매체등록
가입한 아이디로 로그인을 합니다. 로그인 후 퍼블리셔 > Incentive를 선택합니다.  

![img](https://cdn4.tnkfactory.com/tnk/shop/12342.jpg)


좌측 메뉴 중 앱관리를 선택하고 앱추가 버튼을 누르고 앱을 등록합니다.  
앱 등록시 플랫폼은 Web으로 선택하고, 카테고리 우측의 선택 화면에서 KakaoPay(Pub)를 선택합니다.  

![img](https://cdn4.tnkfactory.com/tnk/shop/12340.jpg)

앱 등록이 끝나면 매체등록 버튼을 누릅니다.  
이때 포인트 전환비율만 설정하고 저장을 누릅니다. (다른 설정값은 기본 값으로 두시면 됩니다.)  

![img](https://cdn4.tnkfactory.com/tnk/shop/12344.jpg)

이후 저희 담당자에게 연락하면 귀사 사이트를 카카오페이측에 확인 요청을 합니다.   
카카오페이측에서 승인이 되면 이후 저희 담당자가 별도 연락을 드릴 것입니다.  

## 3. 배너 설정
카카오페이측에서 승인이 된 이후에는 귀사 사이트에 배너를 게제하고 연결 URL은 다음과 같이 설정합니다.  

- 혜택플러스 모바일 웹 충전소 접속 URL
```
https://api2.tnkfactory.com/tnk/cpp.weboff.main?app_id={app_id}&web_yn=Y
```

| **매크로** | **설명** | **최대 길이** | **비고** |
| --- | --- | --- | --- |
| {app_id} | 매체 APP ID | string(32) | 매체별로 고정값(상수) 이다. (TNK 대시보드에서 확인 - App ID) |

배너이미지
- 627x627  
  <img src="https://cdn4.tnkfactory.com/tnk/shop/12354.png" >
  <img src="https://cdn4.tnkfactory.com/tnk/shop/12355.png" >
- 640x100  
  <img src="https://cdn4.tnkfactory.com/tnk/shop/12356.png" >
  <img src="https://cdn4.tnkfactory.com/tnk/shop/12357.png" >
- 640x200  
  <img src="https://cdn4.tnkfactory.com/tnk/shop/12358.png" >
  <img src="https://cdn4.tnkfactory.com/tnk/shop/12359.png" >
- 640x1320    
  <img src="https://cdn4.tnkfactory.com/tnk/shop/12360.png" >
  <img src="https://cdn4.tnkfactory.com/tnk/shop/12361.png" >
- 960x640  
  <img src="https://cdn4.tnkfactory.com/tnk/shop/12362.png" >
  <img src="https://cdn4.tnkfactory.com/tnk/shop/12363.png" >
- 1200x627   
  <img src="https://cdn4.tnkfactory.com/tnk/shop/12364.png" >
  <img src="https://cdn4.tnkfactory.com/tnk/shop/12365.png" >
    
## 4. 테스트
배너 게제 전 위의 URL을 통해 광고에 참여하고, 카카오페이 포인트가 정상적으로 적립되는지 확인합니다.  


## 5. 기술지원
[tech@tnkfactory.com](mailto:tech@tnkfactory.com) 또는 [support@tnkfactory.com](mailto:support@tnkfactory.com) 으로 연락주시면 신속히 지원해드리겠습니다. 


