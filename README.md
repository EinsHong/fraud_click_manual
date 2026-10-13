# 부정클릭 모니터링 메뉴얼 (MkDocs)

## 배포 (GitHub Pages)
1. 새 저장소를 만들고(Public) 이 폴더의 **내용물**을 올립니다. `.github/workflows/deploy.yml` 경로가 정확해야 합니다.
2. Settings > Pages > Source를 **GitHub Actions**로 지정합니다.
3. Actions 탭이 초록색이면 배포 완료입니다.

## 수정
- 본문: `docs/*.md`, 이미지: `docs/assets/img/`, 메뉴: `mkdocs.yml`의 `nav`

## 공개 범위
Public 저장소의 Pages는 주소를 아는 누구나 볼 수 있습니다. noindex는 검색 노출만 줄일 뿐 접근 제한이 아닙니다.
