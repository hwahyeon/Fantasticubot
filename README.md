# Fantasticubot

부천시에 위치한 독립영화전용관 **'판타스틱 큐브'**
의 상영시간표와 상영 중인 영화 포스터 등을 제공하는 텔레그램 봇입니다.

(현재 봇 서비스 일시중지)

## 파일

* exe.py

  텔레그램봇 서비스 운용 파일입니다. crawler.py에서 저장해놓은 데이터를 사용자에게 전달합니다.


* crawler.py

  인디앤아트시네마에서 제공하는 판타스틱큐브의 시간표와 영화 포스터 url 주소를 각각 txt파일과 pickle파일로 만들어 로컬에 저장합니다.
  영화 시간표는 70분, 영화 포스터 주소는 12시간마다 데이터를 갱신합니다.


## 기능 일람

* /start

* /help

* 상영표

  현재 관람 가능한 영화를 보여줍니다. 

* 주소

* 연락처

* 포스터

  상영 중인 영화의 포스터를 보여줍니다. 영화의 일부분만 입력해도 포스터를 볼 수 있습니다.
