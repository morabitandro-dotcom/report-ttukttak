# 보고서뚝딱

유튜브 영상이나 내 영상·음성 파일을 **자막 + 요약 보고서(HTML/PDF)** 로 만들어 주는 Windows 앱이에요.
내 Claude 또는 ChatGPT **구독 로그인**으로 요약해요(API 키·추가 결제 없음).

## 내려받기

👉 **[최신 버전 내려받기](https://github.com/morabitandro-dotcom/report-ttukttak/releases/latest)** → `보고서뚝딱_설치_<버전>.exe`

1. 설치 파일을 실행해요. "Windows의 PC 보호" 창이 뜨면 **[추가 정보] → [실행]** (코드 서명이 없어서 처음에 떠요).
2. 관리자 권한 없이 내 계정에만 설치돼요: `%LOCALAPPDATA%\Programs\보고서뚝딱`
3. 처음 켜면 안내(약관 → AI → 저장 폴더 → 형식 → 받아쓰기 → 텔레그램 → 편하게 쓰기)를 따라가면 돼요.

## 필요한 것
- Windows 10/11 64비트, Microsoft Edge(PDF 만들 때 씀, 기본 설치돼 있음)
- AI 하나 이상
  - Claude Pro/Max + Claude Code: 명령 창에서 `claude` 실행 후 `/login`
  - ChatGPT Plus/Pro + Codex: 명령 창에서 `codex login`

## 업데이트
앱이 켤 때 하루 한 번 이 저장소의 새 버전을 확인해요(설정 → 정보 · 업데이트). 새 버전은 `SHA256SUMS.txt`의 확인 값이 맞을 때만, 진행 중인 작업이 끝난 뒤 설치하고 다시 켜져요.

## 지우기
Windows 설정 → 앱 → 보고서뚝딱 → 제거. 만든 보고서(`문서\보고서뚝딱`)와 설정(`%LOCALAPPDATA%\보고서뚝딱`)은 남아요.

## 주의
영상 저장·장면 캡쳐는 본인이 권리를 가진 영상이나 개인 학습 범위에서만 쓰세요. 이 앱은 DRM이나 접근 제한을 우회하지 않아요.
