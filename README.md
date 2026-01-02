<div align="center">

# 👨‍💻 신민서 포트폴리오
신민서 | 개발자
</div>


### 🎯 핵심 역량

- **머신러닝**: 분류, 회귀, 앙상블 모델 (RandomForest, XGBoost, LogisticRegression)
- **데이터 분석**: EDA, 전처리, 특성 공학 (Feature Engineering)
- **웹 서비스**: Streamlit 기반 ML 애플리케이션 배포
- **프로그래밍**: Python, SQL, Git/GitHub
- **통계학**: 가설 검정, 불균형 데이터 처리, F1-Score 최적화

---

## 📂 주요 프로젝트

### 1. 🚗 전국 휴게소 맛집 및 여정 정보 큐레이션 시스템
Flask 기반 웹 개발 프로젝트

| 항목 | 내용 |
|------|------|
| **역할** | 기술 아키텍처(PL), 기술 방향성 설정, 시스템 아키텍처 설계, 핵심 백엔드 로직 개발 리드 |
| **팀 구성** | 5명 (Frontend 3명, Backend 2명) |
|**개발 기간**| 2025년 12월 (약 2주)
| **기술 스택** | Backend: Flask, Python, MariaDB / Frontend: Vanilla JS, HTML5, CSS3(Tailwind)                                                                       / API: Kakao Maps, Kakao Local, Google Gemini / DevOps: Gunicorn, Cloudtype, GitHub |
| **주요 기능** | 경로 검색(Kakao Mobility), 휴게소 자동 탐색, AI 기반 메뉴 추천, 편의시설 필터링, 실시간 자동완성 검색 |



**🎯 핵심 기술 성과**
- ⚡ **Backend 아키텍처**: Flask + MariaDB 다층 구조 설계
- 🔌 **외부 API 통합**: Kakao Maps/Local, Google Gemini API 3개 동시 연동
- 🚀 **성능 최적화**: 전체 휴게소 데이터(5,513개) 효율적 관리
- 🌐 **클라우드 배포**: Cloudtype 기반 자동 배포



**💡 주요 기술 경험**
- Kakao Mobility API 좌표 변환 및 경로 계산
- MariaDB 쿼리 최적화 (컬럼 선택, 인덱싱)
- Vanilla JS와 Kakao Maps SDK 통합
- REST API 설계 및 에러 처리



**📚 배운 점**
- RESTful API 설계의 중요성
- 데이터베이스 인덱싱으로 쿼리 성능 개선 방법
- 프론트엔드-백엔드 협업 최적화 전략


**[👉 프로젝트 상세 보기](https://github.com/minseo3280-coder/Flask_project)**

---


### 2. 🎯 청년 고립·은둔 위험군 예측 및 의사결정 지원 웹 서비스

**"데이터 기반으로 사회 문제를 조기에 발굴하고 정책 현장에 즉시 활용하는 ML 프로젝트"**

| 항목 | 내용 |
|------|------|
| **개발 기간** | 2025.01 |
| **역할** | 풀스택 (데이터 분석, ML 모델링, 웹 서비스 구현) |
| **데이터** | 서울시 청년 5,513명 (원본 21개 변수 → 44개 특성) |
| **기술 스택** | Python, scikit-learn, Streamlit, joblib |
| **핵심 기능** | 개인 위험도 진단, 핵심 요인 분석, 모델 비교, 웹 대시보드 |



**🎯 핵심 성과**
- 🤖 **최고 성능 모델**: Random Forest (ROC-AUC 0.873, F1 0.523)
- 🔍 **고위험군 탐지율**: 59.8% (재현율 기준) - 실제 위험군 6명 중 3.6명 정확히 진단
- 💡 **주요 인사이트**: 교류 빈도, 경제 수준, 노동 여부 3가지 요인이 전체 위험의 42% 설명
- ⚡ **실무 적용**: Streamlit 대시보드로 정책 담당자·상담사 누구나 1초 안에 위험도 진단



**💡 주요 기술 경험**
- **불균형 데이터 처리 전문성**: class_weight 조정, F1-Score 최적화로 소수 클래스 정확 탐지
- **특성 엔지니어링**: 명목형/서수형 변수 분류 및 원-핫 인코딩으로 순서 왜곡 방지
- **모델 비교 분석**: 해석성(Logistic Regression) vs 성능(Random Forest) 트레이드오프 관리
- **하이퍼파라미터 튜닝**: GridSearchCV + 5-Fold 교차검증으로 n_estimators 150, max_depth 20 최적화
- **웹 서비스 구현**: Streamlit으로 슬라이더/드롭다운 기반 입출력 UI, joblib 모델 캐싱



**📚 배운 점**
- ✅ 높은 정확도보다 **도메인 요구사항에 맞는 지표 선택** (Accuracy 74% → F1-Score 52%로 전환)
- ✅ **해석 가능성의 가치**: 모델 성능만큼 "왜 이렇게 예측했는가"가 정책 현장에서 중요
- ✅ 클래스 불균형 데이터에서 **Precision-Recall 균형**을 맞추는 실무 스킬
- ✅ 기술 완성도만큼 **현장의 실제 요구사항을 이해하고 반영**하는 것의 중요성



**[👉 프로젝트 상세 보기](https://github.com/minseo3280-coder/BigData_project/blob/main/README.md)** 



---

### 3️⃣ [프로젝트명 - 간단한 설명]

| 항목 | 내용 |
|------|------|
| **개발 기간** | 2024.07 ~ 2024.09 (개인 프로젝트) |
| **역할** | 풀스택 개발 |
| **기술 스택** | Vue.js 3, TypeScript, Spring Boot, MySQL |
| **주요 기능** | 실시간 협업, 채팅, 파일 공유 |

**🎯 핵심 성과**
- 👥 현재 100+ 활성 사용자
- ⭐ GitHub 50+ Stars 획득
- 🏆 기술 커뮤니티 추천 프로젝트

**💡 주요 기술 경험**
- WebSocket을 이용한 실시간 통신
- Vue.js 3 Composition API 숙달
- 트랜잭션 관리 및 데이터 일관성 유지

**📚 배운 점**
- 사용자 피드백을 통한 반복적 개선
- 오픈소스 기여의 즐거움
- 커뮤니티와의 협업 방법

**🔗 [Repository 보기](https://github.com/yourname/project3) **

---

## 🛠 Tech Stack

<table>
  <tr>
    <th>분류</th>
    <th>기술</th>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
      <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white" />
      <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>Database</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/MongoDB-13AA52?style=flat-square&logo=mongodb&logoColor=white" />
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>DevOps</b></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white" />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" />
    </td>
  </tr>
</table>

---

## 📊 GitHub Stats

<div align="center">
  
  [![GitHub stats](https://github-readme-stats.vercel.app/api?username=kimphysicsman&show_icons=true&theme=tokyonight&hide_border=true)](https://github.com/kimphysicsman)
  
  [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kimphysicsman&layout=compact&theme=tokyonight&hide_border=true)](https://github.com/kimphysicsman)

</div>

---

## 📚 Experience & Education

### 👨‍💻 Work Experience
- **Software Engineer** | 회사명 | 2023.06 ~ Present
  - 사용자 20만+ 규모의 웹 서비스 개발 및 운영
  - 레거시 코드 리팩토링으로 유지보수성 50% 개선
  - 팀 리뷰 문화 정착 및 코드 품질 개선 주도

### 🎓 학력
- **경상국립대학교** | 정보통계학과 | 졸업

---

## 🎖 Certifications & Awards

- 🥇 **2024 해커톤** - 최우수상 (스타트업 트랙)
- 📜 **AWS Certified** - Solutions Architect Associate (2024)

---


협업 기회, 코드 리뷰, 기술 논의 등 언제든 환영합니다!

<div align="center">

📧 **Email**: minseo3280@gmail.com  

---

*마지막 업데이트: 2026년 1월*

</div>
