# 📊 데이터 분석 & 시각화 (pandas 기초)

브라우저만으로 **pandas `info()` · `describe()`**, **결측치 분석·처리**, **차트 시각화**를 연습할 수 있는 정적 웹 앱입니다.  
고등학교 **정보·데이터 분석** 수업, 판다스 입문 연수에 활용할 수 있습니다.

## 🌐 바로 실행

| 방법 | 링크 |
|------|------|
| **GitHub Pages** (권장) | https://sweet1203.github.io/pandas/ |
| **로컬** | `index.html`을 브라우저에서 열기 |

GitHub: https://github.com/sweet1203/pandas

## ✨ 주요 기능

### 📈 데이터 분석기 탭

| 기능 | 설명 |
|------|------|
| **info** | 컬럼 타입, Non-Null 개수, 메모리 사용량(추정) |
| **describe** | count, mean, std, min, 25%·50%·75%, max |
| **결측치 분석** | 컬럼별 결측 개수·비율 (비율 10% 이상 강조) |
| **결측치 처리** | 행 삭제, 평균·최빈값·중앙값 대체, 앞/뒤 값 채우기, 사용자 지정 값 |

### 📉 데이터 시각화 탭

- **차트 종류**: 꺾은선, 막대, 가로막대, 원·도넛, 산점도, 히스토그램
- **옵션**: 축·제목, 색상 테마, 격자, 값 표시 등
- **PDF 출력** 지원

### 📂 데이터 불러오기

1. **Seaborn 샘플 데이터셋** (12종, 버튼 한 번에 로드)

   | 데이터셋 | 설명 |
   |----------|------|
   | iris | 붓꽃 분류 |
   | titanic | 생존자 분석 |
   | tips | 식당 팁 |
   | penguins | 펭귄 종류 |
   | diamonds | 다이아몬드 가격 |
   | flights | 항공 승객 |
   | mpg | 자동차 연비 |
   | planets | 외계행성 |
   | taxis | 택시 승하차 |
   | geyser | 간헐천 분출 |
   | healthexp | 의료비 지출 |
   | fmri | 뇌 활동 측정 |

2. **CSV 업로드** — 드래그 앤 드롭 또는 파일 선택 (약 50MB 권장)

## 🚀 사용 순서 (수업용)

1. GitHub Pages 링크 접속 → **데이터 분석기** 탭에서 Seaborn 예시(예: `iris`) 선택  
2. `info` · 결측치 · `describe` 결과 확인  
3. **데이터 시각화** 탭에서 그래프 종류·축 선택 후 차트 생성  
4. (선택) 본인 CSV 업로드 후 같은 절차 반복  

## ⚠️ 주의사항

- **엑셀 → CSV**: 「다른 이름으로 저장」→ **CSV UTF-8(쉼표로 분리)(*.csv)**  
- **한글 깨짐**: UTF-8 인코딩 CSV 사용  
- **대용량**: `diamonds` 등 큰 샘플은 기기 성능에 따라 다소 느릴 수 있음  
- **브라우저 전용**: 서버에 데이터를 보내지 않으며, 분석은 모두 **클라이언트(내 PC)** 에서 처리  

## 🛠️ 기술 스택

- HTML5, CSS3, JavaScript
- [Papa Parse](https://www.papaparse.com/) — CSV 파싱
- [Chart.js](https://www.chartjs.org/) — 차트
- Seaborn 스타일 **내장 샘플 CSV** (GitHub Pages 정적 호스팅)

## 📁 저장소 구성

| 파일 | 설명 |
|------|------|
| `index.html` | 메인 앱 (분석 + 시각화) |
| `csv_analysis.html` | CSV 분석 실험/보조 페이지 |
| `csv_debug.html`, `csv_test.html` | 개발·테스트용 |

## 📄 라이선스

MIT License
