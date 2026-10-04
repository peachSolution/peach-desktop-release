# Peach Studio 배포

Peach Studio 데스크톱 설치 파일을 배포하는 공개 저장소입니다. 앱 소스와 서버 설정은 포함하지 않습니다.

## 지원 범위

- Windows x64: NSIS 설치 파일과 앱 내 자동 업데이트.
- Mac: DMG/ZIP 설치 파일과 수동 업데이트.

설치 파일은 [릴리스 목록](https://github.com/peachSolution/peach-studio-releases/releases)에 게시됩니다.
초기 릴리스 게시 전에는 다운로드할 설치 파일이 없습니다.

## Windows 배포 파일

각 정식 릴리스에는 같은 빌드에서 생성된 다음 파일을 함께 첨부합니다.

- `PeachStudio-<버전>-win-x64-setup.exe`
- `PeachStudio-<버전>-win-x64-setup.exe.blockmap`
- `latest.yml`

업데이트는 새 버전 확인 → 다운로드 선택 → 작업 저장 → 재시작 및 설치 순서로 진행합니다.
이 저장소에 문서를 커밋·푸시하는 것만으로 설치 파일이 게시되지는 않습니다.

## Mac 배포 파일

`PeachStudio-<버전>-mac-universal.dmg`와 `.zip`을 릴리스에 첨부합니다.
Mac에서는 새 설치 파일을 내려받아 앱을 업데이트합니다.
