~~# Assignment1~~
세개의 html파일('index.html', 'aboutme.html', 'photo.html')을 하이퍼링크를 통해 연동하여 자기소개 페이지를 구현해보았습니다.

## index.html
* `div`로 초기 AREA size와 background color를 설정함
* body를 세개의 `div` : `#header, #article, #footer`로 나눔
  * header   
    * `padding, margin`으로 흰색 네모칸을 구현했지만 html상의 오류인지 계속 top쪽 green color가 덮어쓰여짐
    * `table`을 사용하려 했으나 각각의 열사이의 간격을 벌리는게 안됨
    * `li`를 사용하려 했으나 가로방향으로 정렬되게하는 방법이나 list앞에 마크를 지우는 방법을 모름
    * 4개의 `button`들을 class로 묶어서 style(`border`, `box-shadow`)을 표현함
    * `button`의 어느부분을 누르던 간에 하이퍼링크가 작동되게하고 싶었지만 구현이 안됨
    * 링크를 한번 클릭하고 나면 색이 변하고 밑줄이 남음
  * article
    * 마찬가지로 `padding, margin`으로 흰색칸을 구현
    * 2개의 버튼들을 class로 묶어서 style을 표현함
  * footer
    * 마찬가지로 `padding, margin`으로 흰색칸을 구현

## aboutme.html
* index.html과 style은 비슷함

## photo.html
* image에 `float`을 주어서 image와 문단의 상단을 맞춤
* image에 `margin`을 주어 문단을 띄어씀
* 문단은 `text-align : left`정렬함

## 보완해야할 점
* style이 중복된 내용이 많아서 생략이 필요함
* 초기 AREA size를 통일 시키지 못함

## 참고 사이트
1. HTML, CSS 공식 문서   
https://www.w3schools.com/css/css_border.asp
