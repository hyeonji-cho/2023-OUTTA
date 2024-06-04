### PCA를 활용한 기업 ESG 성과 분석
---
1. ESG 등급 표 스크랩\n
데이터 소스: KRX ESG 포털\n
데이터 수집: 연도별 기업 ESG 등급 표를 스크랩하여 CSV 파일로 저장했다.\n

2. 데이터 전처리\n
결측치 제거: 결측치를 포함한 데이터를 제거하여 분석의 정확성을 높였다.\n
정수 인코딩: 등급 데이터를 분석하기 위해 정수로 인코딩했다.\n

3. 탐색적 데이터 분석 (EDA)\n
등급 분포 확인: 종합등급, 환경, 사회, 지배구조에 따른 연도별 등급 분포를 확인했다.\n

4. 시각화\n
3차원 산점도: 주성분을 3으로 설정하여 데이터의 분포를 3차원 산점도로 시각화했다.\n
2차원 PCA 시각화: PCA를 적용하여 데이터를 2차원으로 축소하고, PC1과 PC2 두 차원을 기준으로 시각화했다.\n

5. 주성분 분석 설명\n
PC1: 데이터 변동성을 크게 설명하며 중요한 역할. 종합등급, 환경, 사회 등의 변수들과 관련성이 있다.\n
PC2: 지배구조와 관련성이 있다.\n

6. 클러스터 특성 파악\n
PC1이 큰 클러스터: 종합등급, 환경, 사회 성과가 높은 경향이 있다.\n
PC2가 큰 클러스터: 지배구조와 관련된 성과가 낮은 경향이 있다.\n
