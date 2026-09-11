# Klair — Releases

Klair 데스크톱 앱의 **배포 전용 저장소**입니다. 소스 코드는 포함되어 있지 않습니다.

## 다운로드

[**최신 버전 받기**](https://github.com/camelcaramel/klair-releases/releases/latest)

Windows 10/11 x64를 지원합니다. 두 가지 설치 파일 중 하나를 받으세요.

| 파일 | 설명 |
| --- | --- |
| `Klair_*_x64-setup.exe` | 권장 (NSIS 설치 관리자) |
| `Klair_*_x64_en-US.msi` | 조직 배포용 (MSI) |

## 자동 업데이트

설치된 앱은 이 저장소의 `latest.json`을 확인해 새 버전을 알려줍니다.
모든 업데이트 패키지는 minisign 키로 서명되며, 서명이 검증되지 않으면 설치되지 않습니다.

## 설치 시 경고가 뜨는 경우

현재 빌드에는 Windows 코드 서명 인증서가 적용되어 있지 않습니다.
SmartScreen 경고가 표시되면 **추가 정보 → 실행**을 선택하세요.

## 안내

- CoolMessenger 데이터는 **읽기 전용**으로 열립니다. 원본 문서는 덮어쓰지 않습니다.
- 버그 제보 및 문의: [Issues](https://github.com/camelcaramel/klair-releases/issues)
