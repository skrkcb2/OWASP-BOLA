# OWASP-BOLA(Broken Obejct Level Authorization)
### 특징: 사용자가 자신의 권한을 초과하여 다른 사용자 또는 객체에 접근할 수 있는 취약점 이다.  
- ## 공격 유형:
  - ### BOLA 취약 코드:
    ![BOLA](https://github.com/user-attachments/assets/46eeac18-1fbb-40b1-a856-458b66d9429f)
  - ### 공격 예시
    ##### leeinho 유저의 세션 발급 후 타 유저의 아이디로 호출
    ![bola](https://github.com/user-attachments/assets/90ef0868-00e7-4dc4-84a6-5e3c3bbb7755)
- ## 보안 유형:
  - ### BOLA 시큐어 코드:
    ![bola-sec](https://github.com/user-attachments/assets/bb9cf8c3-4712-43fe-b655-5ccbf5a6e866)
  - ### 방어 예시
    ##### 위 공격 예시와 같이 똑같은 흐름으로 진행
    ![bola-sec](https://github.com/user-attachments/assets/229c332d-f101-435c-8aa6-206c070b7421)
    ##### BOLA의 경우 공격자가 자신 권한을 넘지 못하도록 세션 혹은 토큰에 정보를 남겨 비교 하는 방법으로 막을수 있다.




