# 2024 한양대학교 사학과 서양사학사 웹 크롤링 연습
국사편찬위원회의 텍스트를 엑셀파일로 스크래핑해보자.
**본 스크래핑 코드는 서울대학교 국사학과 2024 겨울 파이썬 특강에서 활용된 코드를 수정한 것입니다.**
https://hursoo.github.io/
- 참고 문헌 : 허수, 2021, ｢『개벽』 논조의 사회주의화에 관한 새로운 접근 ― 토픽 연결망 분석을 중심으로｣, 『인문논총』 78(1), 222~262쪽.

## 1. 스크래핑 순서
### 1. 스크래핑 코드 준비
**gb_scraping.ipynb** 파일을 클릭하여 "google colab"으로 열기
### 2. 국사편찬위원회의 메타데이터 다운로드 및 ChatGPT로 자료구성 파악하기
![image](https://github.com/YunhoCha/2024-DH/assets/152939973/9ddb2ebf-d664-4ddb-a8a3-a8c0ef9c047d)
- 개별 자료 직전까지 들어가서 오른쪽 **다운로드**로 자료의 메타데이터 txt 파일 다운로드
- chatGPT(유료)에 업로드하여 어떤 구성으로 이루어진 데이터파일인지 물어보기
![image](https://github.com/YunhoCha/2024-DH/assets/152939973/f6aae3ef-9b86-4ddc-a10e-08c57b44cd7b)
- 필요하면 메타데이터의 구성과 내용을 변경할 수 있음
![image](https://github.com/YunhoCha/2024-DH/assets/152939973/3d3aefdd-86cc-42be-b677-1e03b90183e3)
### 3. 코드에 자료 url 삽입 및 코드 수정(실습)
### 4. 만들어진 데이터 파일(엑셀파일)로 텍스트 전처리(형태소 분석) 및 빈도 분석 해보기.
### 5. TNA의 5단계, 텍스트 마이닝으로 할 수 있는 것.
https://hursoo.github.io/23win-pylec_07/   
군집도 및 중심성 네트워크, 사회주의 단어 빈도, 사회주의 논설 필자의 시기별 빈도

