# 🚗 경주 맞춤형 관광지 코스 추천 서비스 - Front

[![Contributors](https://img.shields.io/badge/contributors-4-brightgreen)](#-기여자-contributors)  

<img width="1285" alt="스크린샷 2024-11-15 20 55 06" src="https://github.com/user-attachments/assets/54bb6ca3-677c-4873-96bd-4e7763733d83">

이 프로젝트는 경주 지역의 관광지를 개인의 선호에 맞게 추천해주는 웹 서비스입니다. 사용자에게 경주의 다양한 명소를 기반으로 맞춤형 여행 코스를 제공합니다.  

---

## 🧑‍💻 기여자  
| 이름      | Github 프로필     | 역할            |  
|-----------|-----------------|-----------------|  
| 권민지     | [mjgwon24](https://github.com/mjgwon24) | frontend & backend & design |
| 김이현     | [lh7721004](https://github.com/lh7721004) | frontend & backend |  
| 전상은 | [wowddok99](https://github.com/wowddok99) | frontend & backend | 
| 전형주     | [kavu-multi](https://github.com/kavu-multi) | AI/ML Engineer  | 

---

## 👩‍💻 주요 기능  
- **맞춤형 관광지 추천**: 사용자의 취향에 따라 관광 코스를 추천합니다.  
- **관광지 정보 제공**: 주요 관광지의 상세 정보와 리뷰를 제공합니다.  
- **UI/UX 설계**: 직관적인 사용자 인터페이스와 매력적인 디자인으로 사용 편의성을 극대화했습니다.  

---

## 🛠️ 기술 스택  
- **Frontend Framework**: Next.js  
- **CSS Framework**: Tailwind CSS  
- **Fonts**: 커스텀 폰트 적용  

---

## 📁 프로젝트 구조  
```
tour-recommend-front
├── pages/ # 주요 페이지 컴포넌트 폴더
│ ├── allCourses/ # 모든 추천 코스 목록 페이지
│ ├── analysisComplete/ # 관광지 분석 완료 화면
│ ├── analyzing/ # 관광지 분석 진행 중 화면
│ ├── discountCoupon/ # 할인 쿠폰 관련 페이지
│ ├── event/ # 이벤트 정보 페이지
│ ├── footingPost/ # 관광 후기 게시판 메인 페이지
│ ├── footingPostDetail/ # 관광 후기 게시판 상세 페이지
│ ├── home/ # 홈 화면
│ ├── kioskMain/ # 키오스크 메인 화면
│ ├── review/ # 리뷰 목록 페이지
│ ├── reviewDetail/ # 리뷰 상세 페이지
│ ├── reviewWrite/ # 리뷰 작성 페이지
│ ├── survey1/ # 설문조사 1단계 페이지
│ ├── survey2/ # 설문조사 2단계 페이지
│ ├── survey3/ # 설문조사 3단계 페이지
│ ├── survey4/ # 설문조사 4단계 페이지
│ └── survey5/ # 설문조사 5단계 페이지
├── public/fonts/ # 커스텀 폰트 파일
├── styles/ # 스타일시트 파일
├── .gitignore # Git 무시 파일
├── README.md # 프로젝트 설명 파일
├── jsconfig.json # JavaScript 설정 파일
├── next.config.mjs # Next.js 설정 파일
├── package-lock.json # 패키지 잠금 파일
├── package.json # 패키지 매니저 파일
├── postcss.config.mjs # PostCSS 설정 파일
└── tailwind.config.js # Tailwind CSS 설정 파일
```  
---

## 📝 설치 및 실행  
1. 저장소 클론  
   ```bash  
   git clone https://github.com/mjgwon24/tour-recommend-front.git  
   cd tour-recommend-front  
   ```  

2. 의존성 설치  
   ```bash  
   npm install  
   ```  

3. 개발 서버 실행  
   ```bash  
   npm run dev  
   ```  

4. 브라우저에서 [http://localhost:3000](http://localhost:3000)으로 접속  

---

## 📬 문의

프로젝트 관련 문의는 GitHub Issues 또는 아래 연락처로 보내주세요.

- **Github:** [mjgwon24](https://github.com/mjgwon24)
- **이메일:** alswlchlrh8@naver.com
  
