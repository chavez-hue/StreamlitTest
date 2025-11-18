# Streamlit Dashboard Project (Cloud Computing Final)

본 프로젝트는 Streamlit을 활용하여 데이터 표시, UI 컴포넌트, 시각화, 필터링, 파일 업로드, 레이아웃 구성 등  
총 7가지 기능을 구현하는 **종합 대시보드 제작** 프로젝트입니다.

---

## 👥 팀 구성

| 학번 | 이름 | 담당 Task |
|------|------|-----------|
| 20213221 | 박세윤 | **Task 1, Task 2** |
| 20215252 | 차병주 | **Task 3, Task 4** |
| 20215277 | 홍예린 | **Task 5, Task 6** |
| 20215186 | 오민희 | **Task 7** |

---

## 📁 프로젝트 구조

StreamlitTest/
├── app.py
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore


---

# 📌 프로젝트 개요

이 프로젝트는 Streamlit을 기반으로  
데이터 시각화 및 상호작용 기능을 단계별로 구현하는 것을 목적으로 합니다.

총 **7단계(Task)** 로 구성되어 있으며, 마지막에는 **종합 대시보드를 제작**합니다.

---

# ✅ **Task별 상세 설명**

---

## **✔ Task 1: 기본 UI 컴포넌트**  
(담당: 20213221 박세윤)

- 텍스트 입력  
- 슬라이더  
- 선택박스(selectbox)  
- 체크박스  
- 버튼  
- Streamlit 기본 위젯 기능 익히기  

---

## **✔ Task 2: 데이터 표시하기 (DataFrame, 통계)**  
(담당: 20213221 박세윤)

- pandas DataFrame 표시 (`st.dataframe`)  
- 데이터 요약 통계 (`df.describe()`)  
- 테이블 기반 정보 제공  

---

## **✔ Task 3: 차트 그리기 (Line / Bar / Area Chart)**  
(담당: 20215252 차병주)

- 선 그래프  
- 막대 그래프  
- 영역 차트  
- Streamlit 내장 chart 기능 활용  
  (`st.line_chart`, `st.bar_chart`, `st.area_chart`)

---

## **✔ Task 4: 인터랙티브 필터 (데이터 필터링)**  
(담당: 20215252 차병주)

- sidebar에 사용자 입력 기반 필터 생성  
- 조건에 따른 DataFrame 필터링  
- 필터링된 데이터 테이블 출력  
- 필터링된 데이터 기반 그래프 표시  

---

## **✔ Task 5: 파일 업로드 (penguins.csv 분석)**  
(담당: 20215277 홍예린)

- CSV 파일 업로드 (`st.file_uploader`)  
- 데이터 미리보기  
- penguins 데이터셋 분석  
- 통계, 시각화 제공  

---

## **✔ Task 6: 레이아웃 구성 (columns, tabs, expander)**  
(담당: 20215277 홍예린)

- 컬럼(column)으로 레이아웃 분리  
- 탭(tabs)으로 페이지 기능 분리  
- expander로 접을 수 있는 UI 구성  

---

## **✔ Task 7: 종합 대시보드 (전체 기능 통합)**  
(담당: 20215186 오민희)

- Task 1~6 전체 기능 통합  
- UI/UX 최적화  
- 최종 발표용 대시보드 완성  

---

# ▶ 실행 방법

필요한 패키지 설치:

```bash
pip install -r requirements.txt

