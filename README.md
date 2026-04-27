# 🎓 가전졸업의 성지

이사·입주·웨딩가전 종합 매장 사이트

---

## 📋 사이트 정보

- **고객용 사이트**: [https://gajeon-master.github.io/store/](https://gajeon-master.github.io/store/)
- **관리자 페이지**: [https://gajeon-master.github.io/store/admin.html](https://gajeon-master.github.io/store/admin.html)

---

## 🛠️ 기능 소개

### 고객용 (index.html)
- 🎁 **BEST 패키지** 선택 — 사장님이 등록한 풀패키지 견적
- 📦 **개별 상품 선택** — 카테고리별 아코디언 UI
- 💳 **제휴카드 캐시백** 자동 적용 (700만~2000만원 구간별)
- 📡 **IPTV 제휴 할인** (최대 84만원)
- 🔥 **다품목 할인** 자동 계산 (LG 품목당 / 삼성 총액)
- 🎉 **오픈혜택 10%** 자동 적용
- 💍 **신축아파트 / 웨딩 추가할인**
- 📋 **상담 신청** 기능

### 관리자용 (admin.html)
- 🔐 비밀번호 보호
- 📊 신청 내역 대시보드
- 📋 신청 상세 확인 + 상태 변경
- 📥 CSV 엑셀 다운로드
- 📖 사용 가이드

---

## 📂 폴더 구조

```
store/
├── index.html              # 고객 메인 페이지
├── admin.html              # 관리자 페이지
├── README.md               # 이 파일
└── images/
    └── products/           # 제품 이미지 폴더
        ├── [모델명1].jpg
        ├── [모델명2].jpg
        └── ...
```

---

## 🔄 데이터 관리

모든 상품/할인/신청 데이터는 **Google Sheets**에서 관리합니다.

### 시트 구조
- `상품` — 판매 상품 목록
- `할인` — 카드/IPTV/캐시백/특별 할인
- `다품목할인` — 브랜드별 다품목 할인 정책
- `월별행사` — 매월 변경되는 행사 모델
- `패키지` — BEST 패키지 정보
- `신청` — 고객 상담 신청 내역 (자동 저장)

---

## ⚙️ 기술 스택

- **Frontend**: Vanilla HTML / CSS / JavaScript
- **Backend**: Google Apps Script
- **Database**: Google Sheets
- **Hosting**: GitHub Pages

---

## 📷 제품 이미지 추가 방법

1. 시트에서 모델명 확인 (예: `RM80F91K1X`)
2. 제품 사진 준비 (1:1 비율, 500x500 권장)
3. 파일명을 모델명과 동일하게 저장 (예: `RM80F91K1X.jpg`)
4. `images/products/` 폴더에 업로드
5. 사이트 새로고침 — 자동 반영! ✨

지원 확장자: `.jpg`, `.jfif`, `.png`, `.webp`

---

## 🎨 디자인

- 화이트 톤 미니멀 디자인
- 빨간색(`#DC2626`) 강조 컬러
- 학사모 일러스트 BI

---

## 📝 라이선스

© 2026 가전졸업의 성지 | All rights reserved
