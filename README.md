# 🚀 Trendify - 대한민국 트렌드 & 밈(Meme) 대시보드

Trendify는 지금 이 순간 가장 핫한 인터넷 유행어와 밈(Meme)을 한눈에 파악하고, 사용자가 직접 참여하여 트렌드의 흐름을 즐길 수 있는 웹 플랫폼 프로토타입입니다.

## 🌐 바로가기
**배포 주소:** [https://kth4778.github.io/Trendify/](https://kth4778.github.io/Trendify/)

---

## ✨ 핵심 기능

### 1. 🔥 실시간 급상승 트렌드 (Index)
- 현재 온라인에서 가장 화제가 되고 있는 키워드를 실시간 티커와 차트로 제공합니다.
- Canvas API를 활용한 역동적인 밈 주식 변동 그래프를 확인할 수 있습니다.

### 2. 📖 유행어 사전 (Dictionary)
- 신조어부터 유행하는 밈까지, 의미와 유래를 완벽하게 정리한 사전입니다.
- 실시간 검색 및 카테고리(SNS, 커뮤니티, 신조어 등) 필터링 기능을 지원합니다.

### 3. 📈 밈 주식 거래소 (Meme Stock)
- 트렌드의 인기를 주식 지표처럼 시각화하여 재미를 더했습니다.
- MEME-X 지수, 화제 언급량 추이 등 데이터 기반의 트렌드 분석 대시보드를 제공합니다.

### 4. 🗳️ 트렌드 투표 (Vote)
- "마라탕 vs 탕후루"와 같이 화제가 되는 주제로 실시간 투표 배틀을 진행합니다.
- 참여 즉시 결과를 확인할 수 있는 인터랙티브한 UI가 구현되어 있습니다.

### 5. 📤 밈 제보 및 업로드 (Upload)
- 사용자가 새로운 밈을 직접 제보하고, 검수 상태(대기, 승인, 반려)를 확인할 수 있습니다.

---

## 🛠 기술 스택

- **Frontend:** HTML5, Vanilla JavaScript, Tailwind CSS (CDN)
- **Visualization:** HTML5 Canvas API (커스텀 차트 드로잉)
- **Design:** Pretendard Font, Glassmorphism UI 스타일
- **Deployment:** GitHub Pages

---

## 🏃 로컬에서 실행하기

이 프로젝트는 정적 웹사이트이므로 별도의 설치 없이 브라우저에서 바로 확인하거나, 간단한 로컬 서버를 통해 실행할 수 있습니다.

**Python을 사용하는 경우:**
```bash
python -m http.server 8000
```
접속 주소: `http://localhost:8000`

**Node.js (serve)를 사용하는 경우:**
```bash
npx serve .
```

---

## 📸 프로젝트 스크린샷

*기본 제공되는 `index.html`, `dictionary.html`, `meme-stock.html` 등을 통해 현대적이고 깔끔한 UI를 경험할 수 있습니다.*

---

## 📄 라이선스
© 2024 Trendify. All rights reserved.
