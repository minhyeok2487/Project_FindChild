# 아이찾기

* Skills: Android, FireBase, GoogleAPI, Java
* 진행 기간: 2022/04/07 → 2022/04/20
* 팀 구성: Android 개발자 4
* 한 줄 소개: 피보호자를 보호하기 위한 위치알림앱

### 🔗 Link

**Source**

[https://github.com/minhyeok2487/Project_FindChild.git](https://github.com/minhyeok2487/Project_FindChild.git)

**Video**

[https://www.youtube.com/watch?v=9RIpWmiq5Fs](https://www.youtube.com/watch?v=9RIpWmiq5Fs)

## ✍️ 요약
![Untitled](https://user-images.githubusercontent.com/76654360/170811115-dfe3262b-c7ed-4ac5-9953-1e0c859857a1.png)


- 피보호자(미성년자 또는 심신미약자)를 돌보고 있는 보호자들을 위한 앱
- 회원가입 후 권한요청과 허용으로 피보호자와 보호자가 연동됨
- 피보호자가 위치전송 START버튼을 누르면 보호자가 위치를 확인할 수 있음

## 🛠 사용 기술 및 라이브러리

- Java, Android
- FireBase
- Google maps, location API

## 🖥 담당한 기능 (Server, Android)

- 앱과 서버와의 데이터 통신을 담당. 서버는 FireBase를 사용함
- 회원가입은 인증서비스, 회원정보 저장은 파이어 스토어, 권한요청과 실시간 위치(위도, 경도)데이터 전송은 리얼타임 데이터베이스 서비스를 사용함
- 사용용도에 맞게 서비스끼리 데이터가 분리되어있어 서버내에서 서비스끼리 정보를 주고받음

![Untitled 1](https://user-images.githubusercontent.com/76654360/170811144-a46bd7bb-5fd2-4100-9b83-4d293fc5fe64.png)

## 💡 성장한 부분

- Firebase 서비스 중 인증, 파이어 스토어, 리얼타임 데이터베이스 간에 데이터 연동을 할 수있다.
- 권한 요청과 권한을 부여, 권한이 있는 상태에서만 사용할 수 있는 기능을 구현 할 수있다.
- JSON형식의 데이터를 다룰 수 있다.

## ☑️ 아쉬운 부분

- 구글 아이디와 페이스북 아이디와 연동가입 구현 중 로그아웃, 탈퇴, 재가입부분에서 버그가 발생했고 프로젝트 끝날 때까지 잡지못하였다.
- 피보호자쪽에서 백그라운드 위치전송은 되지만, 보호자쪽 백그라운드에서 따로 알림을 받는 기능을 구현을 못하였다.
