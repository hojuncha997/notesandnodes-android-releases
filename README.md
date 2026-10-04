# Notes and Nodes — 안드로이드 배포 파일

[notesandnodes.com](https://notesandnodes.com)의 안드로이드 앱 APK를 올려 두는 곳이다. **소스 코드는 여기 없다.**

- 앱은 켤 때 `https://api.notesandnodes.com/api/v1/app/android/latest`로 새 버전을 묻고, 여기 최신 릴리스의 APK를 받아 설치 화면을 연다.
- 릴리스마다 APK와 `release.json`(versionCode·버전 이름·바뀐 점·크기·MD5·SHA-256)이 함께 올라간다.
- 모든 APK는 같은 키로 서명돼 있다. 서명 인증서 SHA-256:
  `DA:B3:8C:29:0A:2B:69:A0:DE:1E:FE:F9:EA:AD:4C:91:8B:A6:5A:47:3F:61:33:5B:84:98:93:AA:54:FC:7B:94`
  안드로이드는 처음과 같은 키로 서명한 APK만 업데이트로 설치한다.
