# 📊 CSV 데이터 분석기

웹에서 pandas의 `info()`, `describe()`, 결측치 분석 및 처리를 할 수 있는 도구입니다.

## 🌐 **실행 방법**

1. **GitHub Pages**: [https://[사용자명].github.io/[저장소명]](https://github.com)
2. **로컬 실행**: `index.html` 파일을 브라우저에서 열기

## ✨ **주요 기능**

### 📈 **데이터 정보 (pandas info)**
- 컬럼별 데이터 타입 확인
- 메모리 사용량 계산
- Non-Null 값 개수 표시

### 📊 **통계 분석 (pandas describe)**
- count, mean, std, min, 25%, 50%, 75%, max
- 숫자형 컬럼 자동 감지
- 특정 열 선택 분석

### 🔍 **결측치 분석**
- 각 컬럼별 결측치 개수와 비율
- 시각적 색상 구분 (10% 이상 빨간색)
- 전체 결측치 요약

### 🧹 **결측치 처리**
- **결측치 삭제**: 결측치가 있는 행 제거
- **평균값 대체**: 숫자형 데이터의 평균값으로 대체
- **최빈값 대체**: 가장 자주 나타나는 값으로 대체

## 🚀 **사용 방법**

1. **CSV 파일 업로드**
   - 드래그 앤 드롭 또는 클릭하여 파일 선택
   - 50MB 이하 파일 지원

2. **데이터 분석**
   - 자동으로 info, 결측치 분석, describe 결과 표시
   - 특정 열만 선택하여 분석 가능

3. **결측치 처리**
   - 처리할 열 선택 (전체 또는 특정 열)
   - 처리 방법 선택 (삭제/평균/최빈값)
   - 처리 후 결과 자동 갱신

## ⚠️ **주의사항**

- **엑셀 파일 사용 시**: "다른 이름으로 저장" → "파일 형식: CSV UTF-8"로 저장
- **한글 깨짐 방지**: UTF-8 인코딩 권장
- **대용량 파일**: 100MB 이상은 처리 시간이 오래 걸릴 수 있음

## 🛠️ **기술 스택**

- **HTML5**: 구조 및 레이아웃
- **CSS3**: 스타일링 및 반응형 디자인
- **JavaScript**: 데이터 처리 및 분석
- **Papa Parse**: CSV 파싱 라이브러리
- **Font Awesome**: 아이콘

## 📱 **반응형 디자인**

- 데스크톱, 태블릿, 모바일 지원
- 가로 스크롤로 많은 컬럼 확인 가능
- 터치 친화적 인터페이스

## 🔧 **성능 최적화**

- 샘플링 기반 데이터 타입 감지 (처음 100개 행)
- 캐싱으로 반복 계산 방지
- 메모리 사용량 제한 (50MB)

## 📄 **라이선스**

MIT License

## 🤝 **기여하기**

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 **문의**

문제가 있거나 개선사항이 있으시면 Issue를 생성해주세요.

---

⭐ 이 프로젝트가 도움이 되었다면 Star를 눌러주세요! 