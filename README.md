# Claude Code Kit (CCKit)

**Windows에서 [Claude Code](https://claude.ai/code)를 더 편하게 써주는 도구 모음**

트레이에 상주하는 WinForms 컨트롤 패널로, Claude Code 세션을 열고·닫고·관리하고, 폰/웹에서 원격으로 조종할 수 있습니다.

<p align="center">
  <a href="https://github.com/hull-kr/Claude-Code-Kit/releases/latest/download/CCKitSetup.exe">
    <b>⬇️ 다운로드 (CCKitSetup.exe)</b>
  </a>
</p>

---

## ✨ 주요 기능

| 기능 | 설명 |
|---|---|
| 🖼️ **이미지 붙여넣기** | 캡처 후 터미널에서 `Ctrl+Shift+V` → 클립보드 이미지 저장 + 경로 자동 입력 |
| 🗂️ **컨트롤 패널** | 관리/열린/닫힌/모든 세션 탭. 상태 색(작업중·대기), 서브에이전트 표시(🔹N) |
| ➕ **새 세션** | 폴더·이름·원격연결·관리추가 옵션으로 새 Claude 세션 생성 |
| 🌙 **bg 전환** | 실행 중 세션을 백그라운드로 (창 닫히고 계속 실행) |
| 📱 **리모트 컨트롤** | claude.ai/code 또는 모바일 앱에서 이 PC의 세션 조종 |
| 🔄 **리붓 자동 복원** | 로그인 시 리붓 직전 열려 있던 세션 자동 복원 |
| 🌐 **다국어** | 한국어 / English / 日本語 / 中文 |

## 📥 설치

1. 위 **다운로드** 버튼으로 `CCKitSetup.exe` 받기 → 실행
2. ⚠️ **Windows SmartScreen** 경고("Windows의 PC 보호")가 뜨면
   → **추가 정보 → 실행** (무료·무서명 프로그램이라 나오는 정상 경고)
3. 설치 후 트레이 아이콘 더블클릭으로 패널 열기

## 📋 요구사항

- **Windows 10 / 11**
- **Claude Code CLI** — 먼저 설치되어 있어야 함 (`claude --version` 으로 확인)
- **Windows Terminal** — 없으면 설치 시 자동으로 설치/업데이트 (winget)

## 💡 ccd 단축 명령

```
ccd = claude --dangerously-skip-permissions
```
권한 확인을 건너뛰고 바로 실행 (설정에서 끌 수 있음)

---

## 📄 라이선스 / 제작

- **제작:** [hull.kr](https://hull.kr)
- **문의:** kimkap10@gmail.com
- © 2026 hull.kr — Freeware (무료 배포)
