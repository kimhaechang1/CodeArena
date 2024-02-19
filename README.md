# 🖥 SSAFY 2학기 공통 프로젝트 - CodeArena

## 🎥 시연영상

### >> https://codearena.shop/ <<

## 🪪 개요

### 코딩이 선택이 아닌 필수가 되어가는 단계에서

### 프로그래머로서 취업하기 위한 첫 발판인 코딩테스트를 즐겁게!

코딩테스트가 대부분의 프로그래머에게 가장 신경쓰이고 힘든 요소 중 하나입니다.

이런 코딩테스트 학습의 경우, 혼자서 충분한 시간을 갖고 공부하는것도 중요하지만

"내가 이제 어느정도 실력일까?" 혹은 "혼자 하니까 따분해" 라는 생각이 들 수 있습니다.

코드아레나는 기본적인 다른 온라인 저지 사이트에서의 장점들을 모으고

코드아레나만의 특색인 레이팅 매칭 시스템을 추가함으로서 재미있는 학습을 할 수 있도록 장려합니다.

## 🚩 개발기간

|           |     [프로젝트 일정]     |
| :-------: | :---------------------: |
| 진행 기간 | 2024.01.03 - 2024.02.16 |
|   인원    |           6명           |

## 🤓 팀원 구성 🤓

<table>
 <tr>
    <td align="center"><a href="https://github.com/kimhaechang1"><img src="https://avatars.githubusercontent.com/kimhaechang1" width="130px;" alt=""></a></td>
    <td align="center"><a href="https://github.com/Be-HinD"><img src="https://avatars.githubusercontent.com/Be-HinD" width="130px;" alt=""></a></td>
    <td align="center"><a href="https://github.com/Agwii"><img src="https://avatars.githubusercontent.com/Agwii" width="130px;" alt=""></a></td>
    <td align="center"><a href="https://github.com/wkdtpwjd19"><img src="https://avatars.githubusercontent.com/wkdtpwjd19" width="130px;" alt=""></a></td>
   <td align="center"><a href="https://github.com/timber3"><img src="https://avatars.githubusercontent.com/timber3" width="130px;" alt=""></a></td>
   <td align="center"><a href="https://github.com/YangGeoun"><img src="https://avatars.githubusercontent.com/YangGeoun" width="130px;" alt=""></a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Be-kimhaechang1"><b>김회창</b></a><p><b>팀장</b><p><b>Back-end</b></p><p>매칭서버 개발</p><p>Problem Solving API 개발</p><p>인프라 구축</p></p></td>
    <td align="center"><a href="https://github.com/Be-HinD"><b>김정현</b></a><p><b>팀원</b></p><p><b>Back-end</b></p><p>아레나 게임서버 개발</p><p>알림 & 게시판 API 개발</p><p>화면공유 시스템 관리</p></p></td>
    <td align="center"><a href="https://github.com/Agwii"><b>이귀현</b></a><p><b>팀원</b></p><p><b>Front-end</b></p><p>아레나 컴포넌트 개발</p></td>
    <td align="center"><a href="https://github.com/wkdtpwjd19"><b>장세정</b></a><p><b>팀원</b></p><p><b>Front-end</b></p><p>알림 & 게시판 컴포넌트 개발</p><p>회원 컴포넌트 개발</p></td>
    <td align="center"><a href="https://github.com/timber3"><b>오승현</b></a><p><b>팀원</b></p><p><b>Back-end</b></p><p>채점서버 개발</p><p>회원관리 API 개발</p></p></td>
    <td align="center"><a href="https://github.com/YangGeoun"><b>양건우</b></a><p><b>팀원</b></p><p><b>Front-end</b></p><p>Problem Solving 컴포넌트 개발</p><p>화면 공유 컴포넌트 개발</p></p></td>
  </tr>
</table>

<br/>

## 📌 커밋 컨벤션

```
[Feat]     : 기능 개발
[Modify]   : 코드 수정
[fix]      : 긴급 수정
[Docs]     : 문서 작업
[Test]     : 테스트 코드
[Design]   : CSS, UI 수정
[Remove]   : 파일 삭제
[Refactor] : 리팩토링
```

## 📌 코드 컨벤션

```
Back-End
- 함수명을 작성할 때는 동사+명사 형태로 구성
- 함수명은 Camel-Case로 작성
- Package Depth == 3Depth
- servlet.context-path는 해당 WAS를 나타낼 수 있도록 작성
- Endpoint는 해당 리소스를 나타낼 수 있도록 작성
- 한줄 주석은 //, 여러 줄 주석은 /** */으로 작성
```

## 📃 개발 환경

### ⚒️ Back-End

- Springboot 3.2.2
- InteliJ
- JDK 17
- AWS EC2
- AWS S3
- MySQL
- Redis
- WebSocket&STOMP
- Nginx
- OpenVidu

### ⚒️ Front-End

- React
- Visual Studio
- TailwindCSS
- OpenVidu

### ⚒️ CI/CD

- Jenkins

### ⚒️ 협업 툴

- Gerrit
- GitLab

## 📝 API 명세서

### 노션 링크 첨부 🔗

https://efficient-liver-208.notion.site/API-a1db160026a44efa971c6dc31fa2a88a

## ⚙️ ERD 다이어그램

### ERD Cloud 사이트로 제작 및 링크 첨부 🔗

https://www.erdcloud.com/d/nrfqSDdChRWJpanzz

## 📌 브랜치 전략

### Git-Flow 전략 및 Github-Flow을 기반으로 한 커스텀 전략 채택

- 사용 브랜치

  - feature : 기능개발
  - fix : 긴급 수정
  - develop : CI/CD Hook 브랜치

- Gerrit 사용 전략

  - feature 브랜치에서 기능구현이 완료되면 원격 EC2 Gerrit으로 HEAD:refs/for/[브랜치명]으로 Commit&Push로 리뷰 Open
  - 1차적으로 마니또 리뷰어가 코드리뷰 진행 및 Submit
  - 마니또의 일정이 바쁘다면 같은 포지션 동료가 코드리뷰 진행
  - 리뷰 승인 이후 develop으로 merge 후 CI/CD 배포

- 브랜치 명명 규칙
  - feature/기능 명시-{BE or FE}
    - FE Example : feature/login-FE
    - BE Example : fix/login-BE

## ⚙ 서비스 아키텍쳐

![Architecture](/asset/img/Architecture.png)

## 🎬 Figma Design

### Main

![Main](/asset/img/figma-main.png)
<br>
<br>
<br>
<br>

### Login

![Main](/asset/img/Figma-Login.png)

<br>
<br>
<br>
<br>

### Community

![Main](/asset/img/figma-community.png)

<br>
<br>
<br>
<br>

### Problem Solving

![Main](/asset/img/figma-ps1.png)

<br>
<br>
<br>

![Main](/asset/img/figma-ps2.png)

<br>
<br>
<br>

![Main](/asset/img/figma-ps3.png)

<br>
<br>
<br>
<br>

### Arena Main

![Main](/asset/img/figma-arena.png)

<br>
<br>
<br>
<br>

### MyPage

![Main](/asset/img/figma-profile.png)

<br>
<br>
<br>
<br>

### Matching

![Main](/asset/img/figma-matching.png)

<br>
<br>
<br>
<br>

### INGAME

![Main](/asset/img/figma-arena-ingame-1.png)

<br>
<br>
<br>
<br>

### SPECTATORS

![Main](/asset/img/figma-arena-spec.png)

<br>
<br>
<br>
<br>

### RESULT

![Main](/asset/img/figma-game-result.png)

<br>
<br>
<br>
<br>

## 주요 기능

### 메인 화면

![Main](/asset/gif/Main.gif)

### 문제 풀이

![Main](/asset/gif/ps.gif)

### 마이 페이지

![Main](/asset/gif/Mypage.gif)

### 아레나 통계

![Main](/asset/gif/arena_main.gif)    

### 매칭 진행



### 스피드전 진행, 화면공유 그리고 결과

### 효율전 진행, 중간 채점현황

### 관전자 배팅 및 채팅
