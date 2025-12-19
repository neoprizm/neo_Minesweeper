# neo_Minesweeper (Web Mini Apps Collection)

이 리포지토리는 브라우저에서 바로 실행 가능한 **여러 개의 독립 HTML 웹 프로그램**을 모아둔 컬렉션입니다.  
리포지토리명은 `neo_Minesweeper`이지만, 실제로는 지뢰찾기 외에도 다양한 실험/데모/미니게임이 함께 포함되어 있습니다.

- **Entry(허브):** `index.html`  

> 참고: 각 프로그램은 단일 HTML 파일 형태로 동작하는 구성이며, 일부는 이미지 리소스를 사용합니다.

---

## 빠른 시작(실행 방법)

### 1) 가장 쉬운 방법
1. 리포지토리를 다운로드/클론합니다.
2. `index.html`을 브라우저로 열어 프로그램 목록을 확인합니다.

### 2) 로컬 서버 권장(일부 브라우저 제한 회피)
브라우저 보안 정책 때문에 `file://` 실행 시 일부 기능이 제한될 수 있습니다(예: fetch, 오디오, 일부 리소스 로딩 등).  
이 경우 간단한 로컬 서버(VS Code Live Server 등)로 실행하는 것을 권장합니다.

---

## 포함된 프로그램(루트 기준)

> 아래는 파일 단위 프로그램 목록입니다. 자세한 내용은 `index.html` 및 각 HTML 내부 설명을 참고하세요.

- `mine.html` : Minesweeper (neo 스타일)
- `sudoku.html` : Sudoku
- `space-shooter.html` / `space-shooter_v2.html` : Space Shooter (버전별 변형)
- `cosmos.html` / `cosmos2.html` / `cosmos3.html` / `cosmos4.html` : Cosmos 시뮬레이션/데모 (버전별 변형)
- `multi_effect.html` : 이펙트 모음/데모
- `chart.html` : 차트/시각화 데모
- `chat.html` : 채팅 UI/데모
- `ball.html` : 볼/물리 데모
- `ps.html`, `uni.html`, `x2.html`, `100M.html`, `100M2.html` : 실험/프로토타입(파일명 기준, 상세는 각 파일 참고)

---

## 디렉토리 구조

- `pm/` : 서브 프로젝트 폴더
- `sc/` : 서브 프로젝트 폴더
- `rocket.png`, `enermy.png` : 일부 프로그램에서 사용하는 이미지 리소스

---

## 보안(Security)

보안 관련 안내는 `SECURITY.md`를 참고하세요.

---

## 라이선스(License)

LICENSE 파일을 참고하세요.
