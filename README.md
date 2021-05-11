# :mag:공공데이터 분석 - 건강검진 데이터
[:earth_asia: 공공데이터 포털](https://www.data.go.kr/index.do) 에서 전국 의료기관 상가 정보데이터를 받아와 분석 및 시각화한 프로젝트입니다.
* 공공데이터 로드 후 결측치 파악
* groupby , pivot_table
* 각 컬럼별 여러개 그래프 그리기 (히스토그램)
* seaborn의 다양한 시각화 도구
* 상관계수를 이용한 히트맵 그래프

## 개발환경

```
🔶 Jupyter
    🐼  Pandas
    🧮  Numpy
    📊  matplotlib
    📊  seaborn
📤 건강검진데이터.csv
```

## :page_facing_up:공공데이터 로드 후 결측치 파악
### 공공데이터 로드
34개의 컬럼으로 이루어진 100만개의 엑셀파일을 데이터 프레임으로 로드

![image](https://user-images.githubusercontent.com/74235867/117747762-bdb45180-b249-11eb-970b-a1cc29feb902.png)

### :page_with_curl:데이터 미리보기
![image](https://user-images.githubusercontent.com/74235867/117747790-c9077d00-b249-11eb-8fb1-2dd9e24ca90f.png)

### :no_entry_sign:결측치 파악하기
![image](https://user-images.githubusercontent.com/74235867/117747800-d02e8b00-b249-11eb-826c-2569cf632249.png)

### groupby 와 pivot_table
![image](https://user-images.githubusercontent.com/74235867/117747832-df153d80-b249-11eb-90c2-22d0f2920fb2.png)

### :bar_chart:각 컬럼별 여러개 그래프 그리기 (히스토그램)
![image](https://user-images.githubusercontent.com/74235867/117747857-e89ea580-b249-11eb-8e65-55ba75fca2f0.png)

### :bar_chart:seaborn의 다양한 시각화 도구
![image](https://user-images.githubusercontent.com/74235867/117747880-f522fe00-b249-11eb-8ebb-0d6f2adeefc1.png)
![image](https://user-images.githubusercontent.com/74235867/117747883-f6ecc180-b249-11eb-9b1f-d30af53e3116.png)
![image](https://user-images.githubusercontent.com/74235867/117747890-f9e7b200-b249-11eb-8e40-a7637000d12e.png)

### 히트맵
![image](https://user-images.githubusercontent.com/74235867/117747922-0409b080-b24a-11eb-971b-2da36b062f38.png)



