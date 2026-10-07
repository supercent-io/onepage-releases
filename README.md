# OnePage 배포본

OnePage 데스크톱 앱(Apple 칩 Mac 전용) 배포 저장소입니다. 소스는 비공개 저장소에 있습니다.

## 처음 설치

1. [최신 Release](https://github.com/supercent-io/onepage-releases/releases/latest)에서 `OnePage.zip`을 받습니다.
2. 압축을 풀고 `OnePage.app`을 **응용 프로그램(Applications)** 폴더로 옮깁니다.
3. 처음 열 때 "손상되었습니다" 또는 "확인할 수 없습니다"가 뜨면 터미널에서 한 번 실행합니다.
   ```bash
   xattr -cr /Applications/OnePage.app
   ```
   또는 시스템 설정 → 개인정보 보호 및 보안 → "그래도 열기".

## 업데이트

설치 후에는 자동입니다. 앱을 켜면 새 버전을 확인해 안내하고, 받은 뒤 **다시 시작하거나 앱을 종료할 때** 교체됩니다. 저장하지 않은 문서가 있으면 종료가 확인을 거치므로 작업이 사라지지 않습니다.
메뉴 **OnePage → 업데이트 확인…**으로 직접 확인할 수도 있습니다.

> 앱이 응용 프로그램 폴더 밖(다운로드 폴더 등)에 있으면 자동 교체가 되지 않습니다. 응용 프로그램 폴더로 옮겨 주세요.

## 파일

- `OnePage.zip` — 앱
- `latest.json` — 앱이 읽는 최신 버전 정보(버전, 다운로드 주소, SHA-256, 변경사항)
