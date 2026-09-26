girok-note 아이콘 교체 파일

GitHub 저장소 루트에서 아래 파일들을 같은 이름으로 덮어쓰세요.
- app-icon-source.png
- apple-touch-icon.png
- favicon-16.png
- favicon-32.png
- icon-192.png
- icon-512.png
- icon-maskable-512.png
- sw.js

추가로 index.html의 기존 data:image/png;base64 형태 favicon 한 줄은
아래 두 줄로 교체하는 것을 권장합니다.

<link rel="icon" type="image/png" sizes="32x32" href="./favicon-32.png?v=25">
<link rel="icon" type="image/png" sizes="16x16" href="./favicon-16.png?v=25">

현재 manifest.webmanifest의 아이콘 경로는 이미 올바릅니다.
새 sw.js 캐시 버전: girok-note-v25-icon-20260926
