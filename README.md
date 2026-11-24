# 제 선택은 형이죠

브라우저에서 바로 실행되는 짧은 비주얼 노벨이에요. 빌드 과정 없이 `index.html`과 이미지·음원 파일만으로 돌아가요.

## 실행

- 내 컴퓨터: 폴더째 받아서 `index.html`을 브라우저로 열면 돼요. 음원이 안 나오면 로컬 서버로 여세요. (예: `python3 -m http.server` 후 `http://localhost:8000`)
- GitHub Pages: 저장소 **Settings → Pages**에서 브랜치를 `main`, 폴더를 `/ (root)`로 지정하면 `https://<아이디>.github.io/<저장소이름>/` 주소로 열려요.

## 파일

| 파일 | 내용 |
|---|---|
| `index.html` | 게임 전체 (화면, 스토리, 스크립트) |
| `q_*.jpg`, `p_cry.jpg` | 배경·장면 이미지 |
| `bgm.mp3` | 배경음악 |
| `ring.mp3` | 전화 연결음 |
| `v_a.mp3` ~ `v_k.mp3` | 음성 |
