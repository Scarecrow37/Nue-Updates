# Nue-Updates

누에(Nue) 테스트 빌드의 **새 버전 알림**용 파일만 두는 저장소입니다.
앱은 `nue-version.json`의 버전 번호를 확인해, 새 버전이 나오면 트레이 알림으로 알려 줍니다.
실행 파일은 여기에 없으며 itch.io에서만 받을 수 있습니다.

```json
{ "version": "0.1.1", "message": "한 줄 소개", "page": "https://dosuha.itch.io/nue" }
```

이 파일은 배포 스크립트(`Deploy/publish.ps1 -Push`)가 자동으로 갱신합니다.
