# Blog Template — v7 (no toggle, smaller type, proper nav, router)

## 변경 사항
1) **다크/라이트 토글 완전 제거** (UI/JS 삭제)
2) **본문 타이포 기본 축소** (`.prose` 폰트/헤딩 스케일 다운)
3) **포스트 페이지 상단바에 카테고리 노출** (site.json 기반)
4) **메인에서 about/archive 숨김** → 상단바 클릭 시에만 해당 섹션 표시 (hash 라우팅)

## 수동 적용 지침(이미 운영 중일 때)
- `index.html`과 `post.html`만 위 버전으로 교체하면 됩니다.
- 라우팅: `/#about`, `/#archive`, 카테고리 필터는 `/?cat=카테고리`

