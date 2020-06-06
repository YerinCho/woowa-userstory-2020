# woowa-userstory-2020

# 곰신네 꽃신가게 (고무신 / 군화 커뮤니티 서비스)


## 서비스 소개

#### 개요

내 남자친구는 왜 군인일까? 
군인인걸로도 화나는데! 요즘에는 휴가도 못나오네!?
나는 잘 기다리고 있는걸까? 이 심정을 누군가와 공유하고 싶다!

나이스 조기진급~ 전역일 계산기에 이걸 **간 단 히** 반영하고 싶은데 어디 좋은 계산기 없나?




이 서비스는 기획자 본인이 타 고무신 커뮤니티를 사용했을 때 불편함을 느껴 더 좋은 커뮤니티를 제공하기 위해 기획하였다.


#### 기존 커뮤니티들의 문제점

 + 국방부에서 제공하는 커뮤니티는 고무신 뿐만 아니라, 군인의 부모님들도 같이 사용해 고무신 본인에게는 불편하다. (부모님과 고무신은 서로를 이해하지 못한다.)
 + 전역일 계산기도 같이 보고 싶은데 네이버 카페는 그런 점에서 불편하다.
 + 위의 두 니즈를 충족하는, 사람들이 가장 많이 사용하는 기존 커뮤니티가 있지만, 그 커뮤니티는 자체 버그가 너무 많다.
 + 그래서 느리다.
 + (네이버 카페가 아닌 커뮤니티는) 게시판인데 글 검색 기능도 제공하지 않는다.
 + 또한, 전역일, 휴가일, 진급일에 변동이 생기면 계산기에 그 점을 반영하는데 사용자에게 너무 많은 일을 시킨다. 변동사항 하나만 입력하고 싶은데 여러가지를 전부 입력해야 한다.




## 페르소나

조예린 (23세 여, 대학생, 곰신 1년차)

니즈

+ 남자친구 진급일이 바뀌었다. ***상병 -> 병장 1개월 조기진급*** 정보만을 가지고 전역일 계산기의 계급별 현황을 수정하고 싶다. 



한형서 (23세 남, 군인 본인, 상병 4호봉)

니즈

+ 여자친구랑 싸웠다. 군대 내 시커먼 남정네들 말고 여자친구와 같은 입장의 사람들에게 이야기를 듣고 싶다.



오렌지 (22세 여, 대학생, 곰신 2주차)

니즈

+ 남자친구가 막 입대했다. 너무 힘들다. 같은 곰신들은 어떤지, 편지는 어떻게 보내는지, 전화는 오긴 하는지, 선물은 무엇이 좋은지 등의 정보들을 알고싶다. 



## 시나리오

```
최근 조예린은 상병 남자친구가 군대 내 창업경진대회에서 상을 받아 1개월 조기진급을 한다는 좋은 소식을 들었다. 
굳이 전역일 계산기 현황을 바꿀 필요는 없지만 남자친구의 진급이 빨라져 계산기의 군 복무 현황 퍼센트가 올라가면 괜히 기분은 좋다. 
그래서 기존 9월진급에서 8월진급으로 바뀌었는데, 사용하던 전역일 계산기에 계급별 진행현황을 변경하고 싶다. 
이병, 일병, 바뀐 상병과 병장의 기간을 모두 입력하지 않고 병장 1개월 조기진급 만의 정보를 가지고 계산기 현황을 바꾼다. 
```

#### 요구사항

| 시나리오                                                     | 요구사항                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 남자친구의 진급이 빨라져 계산기의 군 복무 현황 퍼센트가 올라가면 괜히 기분은 좋다. | - 전역일 계산기에 복무 현황(퍼센트) 표시가 필요하다.<br>- 계급별 현황 표시도 필요하다. |
| 그래서 기존 9월진급에서 8월진급으로 바뀌었는데, 이를 사용하던 전역일 계산기에도 반영하고 싶다. | - 복무 현황이 바뀌면 그에 따라 계산기 현황을 바꿀 수 있어야 한다. |
| 이병, 일병, 상병, 병장의 기간을 모두 입력하지 않고 병장 1개월 조기진급 만의 정보를 가지고 계산기 현황을 바꾼다. | - 변경된 정보만을 가지고 계산기 현황을 바꿀 수 있어야 한다. (사용자에게 최소한의 일만 시켜야 한다.) |






```
군인 한형서는 어제 여자친구와 심하게 다투었다. 여자친구는 당분간 연락을 하지 말라고 하며, 나의 연락을 모조리 받지 않는다. 
여자친구와 헤어지고 싶지 않은 한형서는 생활관 동기, 상담병에게 도움을 요청하지만 이들 모두 여자친구와 같은 고무신이 아니어서 그런지 그럴싸한 대답을 얻지 못한다. 
고무신 친구에게 물어보자니 여자친구와 함께 아는 사람이어서 물어보기 꺼려진다. 그래서 고무신 커뮤니티에 접속한다. 
간단한 가입을 한 후, 여자친구가 혹시 볼 수도 있으니 여자친구가 모를만한 닉네임을 설정하고 글을 남긴다. 여러 고무신들이 댓글을 남긴다. 
답글로 질문을 하며 다양한 도움을 얻는다. 특히 도움이 되는 댓글을 발견한 한형서는 댓글 작성자에게 감사하다는 답글을 남기고 좋아요를 눌러준다.
```

#### 요구사항

| 시나리오                            | 요구사항                             |
| ---------------------- | ----------------------------------------- |
| 간단한 가입을 한 후, 여자친구가 혹시 볼 수도 있으니 여자친구가 모를만한 닉네임을 설정하고 글을 남긴다. | - 가입절차를 간소화한다.<br>- 닉네임을 설정할 수 있어야 한다.<br>- 게시글 작성이 가능해야 한다. |
| 여러 고무신들이 댓글로 다양한 조언을 남긴다.여러 고무신들이 댓글을 남긴다. 답글로 질문을 하며 다양한 도움을 얻는다. | - 게시글에 댓글 작성이 가능해야 한다.<br>- 댓글에 대한 답글을 달 수 있어야 한다. |
| 특히 도움이 되는 댓글을 발견한 한형서는 댓글 작성자에게 감사하다는 답글을 남기고 좋아요를 눌러준다. | - 댓글에 대한 좋아요 표시가 가능하다.                        |





```
고무신을 신은지 얼마 되지 않은 오렌지는 지금 상황이 너무 힘들다. 매일 보던 남자친구는 연락조차 되지 않고 아직 편지 한 통도 오지 않았다. 
오렌지는 남자친구가 훈련소에 있는 사람들과 이야기를 나누며 이 슬픈 감정을 누그러뜨린다. 
다른 훈련소 고무신들과 이야기를 나누다 보니 남자친구에게 손편지를 보내고 싶어졌다.
어떻게 보내는지 잘 모르는 오렌지는 '훈련소 손편지' 라는 키워드로 검색해 추천 수가 가장 많은 게시글을 통해 방법을 알게 된다.
게시글을 더 찾아보다가 군대, 손편지 등과 무관한 광고성 글을 발견한 오렌지는 신고 버튼을 누른다. 
```

#### 요구사항

| 시나리오                                                     | 요구사항                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| 오렌지는 남자친구가 훈련소에 있는 사람들과 이야기를 나누며 이 슬픈 감정을 누그러뜨린다. | - 계급별 등, 상황에 맞는 게시판의 분리가 필요하다.           |
| 어떻게 보내는지 잘 모르는 오렌지는 '훈련소 손편지' 라는 키워드로 검색해 추천 수 기준으로 정렬해 추천 수가 가장 많은 게시글을 통해 방법을 알게 된다. | - 게시글 검색이 가능해야 한다. <br>- 게시글을 추천하는 기능이 필요하다.<br>- 검색한 게시글을 기준에 따라 정렬할 수 있어야 한다. |
|게시글을 더 찾아보다가 군대, 손편지 등과 무관한 광고성 글을 발견한 오렌지는 신고 버튼을 누른다. | - 사용자가 불쾌함을 느끼는 글에 대해 신고를 할 수 있어야 한다.|







### 생각해 보아야 할 사항

+ 모바일 웹의 제공이 필요하다.
+ 모바일 어플리케이션과의 차별점을 둬야 한다. 검색해서 들어올 만큼의 유인 요소가 필요하다.
+ 굳이 본인인증, 가입절차가 필요할까? 가입절차 없이 자유롭게 글을 쓸 수 있는 방식은 어떨까?
+ 광고성 글에 대한 제재가 필요하다.
+ 계산기만 사용하는 유저가 커뮤니티도 사용하게 하려면 어떠한 점을 이용해야 할까?
