# 2024-paris-olympic
2024 파리 올림픽 관련 데이터입니다. [위키피디아](https://en.wikipedia.org/wiki/List_of_2024_Summer_Olympics_medal_winners#) 및 [나무위키](https://namu.wiki/w/2024%20%ED%8C%8C%EB%A6%AC%20%EC%98%AC%EB%A6%BC%ED%94%BD#s-7.2)를 참고하여 제작하였습니다. 

## 데이터 스키마

### [countries.csv](https://github.com/EDA-study/2024-paris-olympic/blob/main/data/countries.csv)
  - 국가: 국가명
  - 대륙: 해당 국가가 속한 대륙
  - 인원 수: 해당 국가에서 2024 파리 올림픽에 참가하는 선수의 수
  - 국기: 해당 국가의 국기 이미지 URL
 
### [medals.csv](https://github.com/EDA-study/2024-paris-olympic/blob/main/data/medals.csv)
  - 국가: 국가명
  - 종목: 해당 국가가 메달을 획득한 종목명
  - 금: 해당 국가가 해당 종목에서 획득한 금메달 수
  - 은: 해당 국가가 해당 종목에서 획득한 은메달 수
  - 동: 해당 국가가 해당 종목에서 획득한 동메달 수
  - 합계: 해당 국가가 해당 종목에서 획득한 총 메달 수

### [sports.csv](https://github.com/EDA-study/2024-paris-olympic/blob/main/data/sports.csv)
  - 종목: 종목명
  - 한 국가의 최대 메달 수: 해당 종목에서 가장 많은 메달을 획득한 국가의 메달 수
