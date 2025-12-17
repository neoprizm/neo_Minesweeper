# Three.js 2D 플랫포머 (스프라이트 기반)

## 포함 파일
- index.html
- background_color_mushrooms.png
- character_green_idle.png
- character_green_walk_a.png
- character_green_walk_b.png
- character_green_jump.png
- character_green_hit.png

## 실행 방법(중요)
브라우저에서 `file://`로 직접 열면 이미지 로딩(CORS) 문제가 날 수 있습니다.
반드시 로컬 웹서버로 실행하세요.

### 추천 (VS Code)
1) VS Code에서 폴더 열기
2) Live Server 확장 설치
3) `index.html` 우클릭 → **Open with Live Server**

### Node.js가 있으면
- 터미널에서 이 폴더로 이동 후:
  - `npx http-server -p 8080`
  - 브라우저에서 `http://localhost:8080` 접속

## 조작
- 이동: A/D 또는 ←/→
- 점프: Space / W / ↑
- 대시: Shift
- 리셋: R
