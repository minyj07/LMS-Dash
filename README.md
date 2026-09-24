# LMS Dash — 순천향대 e-class 비공식 대시보드

순천향대 e-class(Canvas LMS + LearningX)의 **마감 임박 과제, 봐야 할 강의 동영상, 공지**를 한눈에 보여주는 앱입니다.
**Windows** 와 **Android** 앱이 있습니다. LearningX 앱이 불편해서 만든 개인 프로젝트이며, 학교 공식 앱이 아닙니다.

<p>
<img src="screenshots/desktop-dashboard.png" width="560" alt="Windows 대시보드">
<img src="screenshots/mobile-home.png" width="200" alt="Android 홈">
</p>

## 다운로드

**[최신 버전 받기 (Releases)](https://github.com/minyj07/LMS-Dash/releases)** — 설치 파일만 있으면 되고, 다른 프로그램은 필요 없습니다.

| 기기 | 파일 | 설명 |
| --- | --- | --- |
| Windows | `LMSDash-Setup-<버전>.exe` | 설치판 (권장). 알림·자동 실행·자동 업데이트가 가장 잘 동작 |
| Windows | `LMSDash-<버전>-portable.exe` | 설치 없이 바로 실행 |
| Android | `LMSDash-<버전>.apk` | `android-v` 로 시작하는 릴리스에 있습니다 |

- **Windows**: 코드 서명이 없어서 처음 실행할 때 "Windows의 PC 보호" 창이 뜰 수 있습니다 → **추가 정보 → 실행**
- **Android**: 휴대폰에서 APK 를 받아 열고, "출처를 알 수 없는 앱 설치"를 허용한 뒤 설치합니다.
- 설치한 뒤에는 앱이 새 버전을 확인합니다 (Windows 는 자동으로 받아 설치, Android 는 설정 → 업데이트).
- 릴리스 페이지의 "Source code" 파일은 GitHub 이 자동으로 붙이는 것으로, 이 안내 문서만 들어 있습니다.

## 주요 기능

- **앱 자체 로그인** (학번·비밀번호, 자동 로그인) — 비밀번호는 기기에만 암호화해 저장
  - 다른 Canvas LMS 학교도 사용 가능 (학교 로그인 페이지에서 직접 로그인)
- **대시보드**: 24시간 내 마감, 이번 주 마감, 봐야 할 동영상, 미제출 과제를 한눈에
- **할 일**: 오늘 / 내일 / 이번 주 / 다음 주로 묶은 목록, 필터와 검색, 지각 제출 가능 항목 표시
- **동영상 출석 현황**: 출석 인정 기간, 진도율, 출석/지각/결석 상태. 아직 열리지 않은 주차는 "○월 ○일 열림"으로 표시
- **공지사항을 앱 안에서 읽기** (LMS 에도 읽음 표시), 첨부파일 받기
- **강의자료 모아보기**와 받기 (Windows 는 "모두 다운받기")
- **마감 알림**: 아직 안 한 항목의 마감 하루 전·3시간 전 (시간 선택 가능)
- 동영상 시청·과제 제출은 앱 안의 LMS 화면에서 로그인된 상태로 (출석 정상 기록)
- 주간 캘린더, 과목별 화면, 완료 표시·숨기기, 라이트/다크 테마

<p>
<img src="screenshots/mobile-todo.png" width="200" alt="Android 할 일">
<img src="screenshots/mobile-notices.png" width="200" alt="Android 공지">
<img src="screenshots/mobile-resources.png" width="200" alt="Android 강의자료">
</p>

## 개인정보

앱에는 개발자가 운영하는 서버가 없습니다. 학번·비밀번호와 LMS 정보는 **사용자의 기기와 학교 서버 사이에서만** 오가고, 개발자에게 전송되지 않습니다.
사용 통계·광고·추적 기능도 없습니다. 자세한 내용은 **[개인정보 처리방침](PRIVACY.md)** 을 보세요.

## 이용 약관

무료로 설치해 쓸 수 있는 비공개 소스 소프트웨어입니다. 수정·재배포·판매는 할 수 없습니다. → **[이용 약관 (라이선스)](LICENSE.md)**

과제 마감·출석 정보가 항상 정확하다는 보장은 없으니, 중요한 일정은 학교 LMS 에서도 꼭 확인하세요.

## 문의

버그 제보, 건의, 개인정보 관련 문의: **[minyj07@sch.ac.kr](mailto:minyj07@sch.ac.kr)**
