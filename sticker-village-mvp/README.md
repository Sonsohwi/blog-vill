# My Sticker Village MVP

개인 콘텐츠를 스티커 캔버스로 시각화하는 정적 웹앱입니다.

## 기능
- 스티커 캔버스, 클릭/탭해서 포스트 모음 보기
- 편집 모드에서 스티커 드래그 배치
- 직접 스티커 추가
- Markdown, HTML, TXT, JSON 파일 가져오기
- Notion Markdown/HTML ZIP 내보내기 파일 가져오기
- localStorage에 기록과 배치 저장
- 모바일 터치 및 하단 패널 대응

## Notion
Notion에서 페이지/워크스페이스를 Markdown & CSV 또는 HTML로 내보낸 뒤 ZIP 파일을 가져오세요. ZIP 안의 Markdown, HTML, TXT를 읽습니다. 현재 이미지 파일은 자동으로 첨부하지 않습니다. Notion 계정에 직접 연결하거나 자동 동기화하지 않습니다.

## GitHub Pages 배포
1. 압축을 풀고 파일 전체를 GitHub 저장소 루트에 업로드합니다.
2. 저장소 Settings → Pages에서 Source를 GitHub Actions로 선택합니다.
3. main 브랜치에 push하면 포함된 workflow가 Pages에 배포합니다.
4. Actions에서 배포 완료 후 Pages URL로 접속합니다.

## 참고
- ZIP 가져오기는 JSZip CDN을 사용하므로 인터넷 연결이 필요합니다.
- 파일 내용은 서버로 전송하지 않고 현재 브라우저에서 처리합니다.
- 브라우저 데이터를 삭제하면 가져온 기록/배치가 사라질 수 있습니다. 원본 파일을 보관하세요.
