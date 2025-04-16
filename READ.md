# DAY6 팬 페이지 저장소

이 저장소는 **DAY6** 팬들을 위한 앨범 소개, 설문조사 폼, 응원 메시지 기능 등을 포함한 웹 페이지 프로젝트입니다. 각 앨범 정보와 미디어, 팬 설문 조사가 포함되어 있습니다.


## 📁 폴더 및 파일 구조

📁 root/
├── 📁 media/                # 공용 이미지, 앨범 커버 이미지 등 저장
├── 📁 pages/                # 각 앨범 상세 페이지 폴더
│   ├── 📁 media/            # 앨범 상세 페이지에 사용되는 이미지
│   ├── album1.html
│   ├── album2.html
│   ├── album3.html
│   ├── album4.html
│   ├── album5.html
│   ├── album6.html
│   ├── album7.html
│   ├── album8.html
│   ├── album9.html
│   ├── album10.html
│   ├── album11.html
│   ├── album12.html
│   ├── album13.html
│   └── album14.html
├── form.html               # 팬 정보 설문조사 폼 페이지
├── index.html              # 메인 페이지 (앨범 리스트 및 소개)
└── style.css               # 전체 웹 페이지 스타일 시트


---

## 📄 주요 파일 설명

- `index.html`:  
  DAY6 밴드를 소개하고, SNS 링크와 앨범 목록을 제공하는 메인 웹페이지입니다.

- `form.html`:  
  팬 설문조사 및 응원 메시지를 입력할 수 있는 페이지로, Google Apps Script와 연동되어 정보를 전송합니다.

- `style.css`:  
  모든 페이지에 공통 적용되는 디자인 스타일을 지정한 파일입니다. (폰트, 배경, 테이블, 링크, 이미지 효과 등 포함)

- `media/`:  
  앨범 커버 이미지, 뮤직비디오 썸네일 등 공용 미디어 리소스를 저장하는 폴더입니다.

- `pages/`:  
  각 앨범별 상세 정보를 담은 HTML 페이지들이 포함되어 있습니다.  
  예: `album1.html` → `The Day` 앨범 상세 페이지

---

## 🛠️ 기술

- HTML5
- CSS3
- JavaScript (폼 제출 처리)
- Google Apps Script (설문 데이터 수집용 백엔드)

---

