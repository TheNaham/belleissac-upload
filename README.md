// belleissac-upload
Belle IssaC 파트너사 자료 업로드 포털 - https://upload.belleissac.cloud
index.html : 업로드 페이지 (CSS/JS/로고 전부 내장된 단일 파일)
백엔드 : Google Apps Script 웹앱 (index.html 안의 ENDPOINT 상수)
저장소 : Google Drive 업체자료_UPLOAD 폴더 + Google Sheets DATA 탭
배포 : main 브랜치에 push하면 Cloudflare Pages가 자동 배포 (빌드 명령 없음, 출력 디렉터리 /)
주의 : ENDPOINT 상수와 폼의 data-cat 속성(card/logo/product/doc)은 절대 변경하지 말 것
