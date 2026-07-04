# nojaky.github.io

로스터현 웹 도구와 카페 운영 블로그형 홈페이지입니다.

## 구성
- index.html: 메인, 웹 도구 목록, 블로그 미리보기
- blog/: 카테고리형 블로그 목록과 샘플 글
- about.html / contact.html / terms.html / privacy-policy.html
- robots.txt / sitemap.xml / ads.txt

네이버 블로그 글을 옮길 때는 `blog/` 안의 샘플 글 파일을 복사해 제목, 설명, 본문, 카테고리만 교체하면 됩니다.

## 블로그 글쓰기 도구

`/admin/write.html`은 로컬/브라우저에서 블로그 글 HTML 파일을 생성하는 관리자용 도구입니다.

사용 순서:
1. `admin/write.html`을 브라우저에서 엽니다.
2. 제목, 파일명, 카테고리, 요약, 본문을 작성합니다.
3. `글 HTML 저장` 버튼으로 글 파일을 내려받습니다.
4. 생성된 `.html` 파일을 GitHub 저장소의 `/blog/` 폴더에 업로드합니다.
5. `목록 카드 코드 저장` 버튼으로 받은 코드를 `blog/index.html`의 글 목록 영역에 추가합니다.

`/admin/` 경로는 `robots.txt`에서 검색 제외 처리되어 있습니다.
