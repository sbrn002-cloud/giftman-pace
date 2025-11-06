# 러닝 페이스 계산기 배포 안내

## 1) GitHub Pages로 배포 (무료)
1. GitHub에서 새 저장소 생성 (예: `giftman-pace`)
2. `index.html` 업로드 (이 ZIP에 들어있습니다)
3. Settings → Pages → Deploy from a branch → `main`/`/root` 선택
4. 배포 URL 예: `https://<GitHub아이디>.github.io/giftman-pace/`

## 2) Netlify / Cloudflare Pages (무료)
- 사이트 추가(Add new site) → 프로젝트 없이 업로드(Drag & Drop) → URL 발급

## 3) 네이버 블로그에 임베드
스마트에디터에서 HTML(또는 외부콘텐츠) 모드로 아래 코드 삽입:

<div style="max-width: 360px; margin: 0 auto;">
  <iframe
    src="https://<배포한-URL>"
    width="360"
    height="560"
    style="border:1px solid #e3e7ef; border-radius:12px; box-shadow:0 6px 18px rgba(20,28,55,.06);"
    loading="lazy"
    referrerpolicy="no-referrer"
  ></iframe>
  <div style="text-align:center; font-size:12px; color:#7f8798; margin-top:8px;">
    계산기 새 창으로 열기 ▶ <a href="https://<배포한-URL>" target="_blank" rel="noopener">러닝 페이스 계산기</a>
  </div>
</div>

※ 모바일 스킨에 따라 `iframe`이 제한될 수 있습니다. 이 경우 네이버의 외부콘텐츠 위젯을 이용하세요.

## 4) 블로그 버튼으로 새 창 열기 (대안)
<a href="https://<배포한-URL>" target="_blank" rel="noopener" 
   style="display:inline-block; background:#6ec1ff; color:#fff; padding:10px 14px; border-radius:8px; text-decoration:none;">
  러닝 페이스 계산기 열기
</a>
