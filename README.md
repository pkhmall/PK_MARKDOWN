# PK_MARKDOWN
pk_MARKDOWN

## 이미지 넣기  


## 강조  
굵게 표시 : **오늘은 즐거운 금요일 이야호**      
굵게 표시 : __오늘은 즐거운 금요일 이야호__  

## 하이퍼링크  
[pcwk](https://cafe.daum.net/pcwk "PCWK CAFE")

## 가로선  
---  
***  


## 코드블록
```
   MockMvcRequestBuilders.post("/user/add.do")
				.param("uId",       user01.getuId())
				.param("name",      user01.getName())
				.param("passwd",    user01.getPasswd())
				.param("intLevel",  user01.getIntLevel()+"")
				.param("login",     user01.getLogin()+"")
				.param("recommend", user01.getRecommend()+"")
				.param("email",     user01.getEmail()); 
```

## 순서가 있는 목록  
1. 아이템
3. 아이템2  
    9. 1단 하위 아이템    
          3. 2단 하위 아이템
 9. 아이템3

- 아이템1  
+ 아이템2  
  - 1단의 하위 아이템  
  * 2단계 하위 아이템

## 목록 : 기본적인 리스트 작성 방법(아래 세가지 중 어느것을 사용해도 된다.)  
* 목록이름  
- 목록이름  
+ 목록이름  

## 인용상자 : > 내용 형식으로 인용 상자를 작성할 수 있다.
> 여기에 인용할 내용을 채워 넣으면 됩니다.  
빈 줄이 없으면 자동으로 인용상자에 포함됩니다.

## 문단구분을 위한 강제 개행: 줄에 마지막 [Space bar] 두번 이상 눌러 띄어쓰기를 하면 된다.
가나
## 헤더 : #헤더 이름 식으로 작성
# 헤더1
## 헤더2
### 헤더3
#### 헤더4
##### 헤더5
