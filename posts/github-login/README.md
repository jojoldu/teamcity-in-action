# Teamcity Github 로그인 연동

Teamcity에는 기본적인 id/password 방식의 로그인 기능이 있지만, 실제 업무에서 해당 기능은 잘 사용되지 않습니다.  
  
Github 혹은 Google 과 같은 OAuth 인증을 사용하게 되는데요.  
이번 시간에는 Teamcity 에서의 Github 로그인을 연동해보겠습니다.  

## 1. 플러그인 설치

Teamcity에서는 공식적으로 Github 로그인을 지원하지 않습니다.  

> Jenkins와 비슷합니다.

다만, 해당 기능을 플러그인으로 지원하고 있습니다.  
  
그래서 가장 먼저 플러그인 설치를 하겠습니다.  
  
먼저 설치된 Teamcity 의 관리자 페이지 (Adminstration) 으로 이동합니다.

![1](./images/1.png)

좌측 사이드바 하단의 PluginsList 를 클릭합니다.

![2](./images/2.png)

검색을 통한 플러그인 설치를 위해 Browse plugins repository 를 선택합니다.

![3](./images/3.png)

IntelliJ와 마찬가지로 플러그인 검색 화면으로 이동됩니다.  
여기서 **github** 으로 검색합니다.

![4](./images/4.png)

그럼 아래와 같이 **teamcity-oauth** 플러그인을 찾을 수 있습니다.

![5](./images/5.png)

플러그인 상세 화면으로 가시면 **Get** 버튼이 있습니다.  
클릭하시면 아래와 같이 **Install to Teamcity주소** 선택하신뒤, Install 버튼을 클릭합니다.  

![6](./images/6.png)

![7](./images/7.png)

![8](./images/8.png)

![9](./images/9.png)

![10](./images/10.png)

![11](./images/11.png)

![12](./images/12.png)

![13](./images/13.png)

![14](./images/14.png)

![15](./images/15.png)

![16](./images/16.png)

![17](./images/17.png)

![18](./images/18.png)

![19](./images/19.png)

![20](./images/20.png)

![21](./images/21.png)

![22](./images/22.png)

![23](./images/23.png)

![24](./images/24.png)