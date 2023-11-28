![header](https://capsule-render.vercel.app/api?type=waving&text=Druids&nbsp;Developer&fontSize=40&fontAlign=25&fontColor=FFFFFF&animation=fadeIn&height=170&fontAlignY=35&color=timeGradient)
 
***


<body> 
  <div align=center>

💬 SNS 💬
  
<a href="https://blog.naver.com/catoo_4" target="_blank"><img src="https://img.shields.io/badge/Naver Blog-03C75A?style=for-the-badge&logo=Naver&logoColor=white"></a>

📚 STUDY 📚
    
<img src="https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white"> </a>

💡 ENGINE 💡

<img src="https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white"> </a>

  </div>

</body>

[Github 블로그] 웹 폰트 설정하기 (+폰트 추천)
 Date: 2021.02.20    Updated: 2021.02.20
 카테고리: Blog

 태그: HTML jekyll Liquid minimal-mistake Blog

 목차
1️⃣ 무료 웹 폰트 사이트에서 사용할 폰트를 골라보자
🔥 첫 번째 추천 사이트 : 눈누
🔥 두 번째 추천 사이트 : 구글 폰트
2️⃣ 임포트 하기
1) CSS 에 Import 하는 방법
📜main.scss
2) HTML 에 Import 하는 방법
📜default.html
3️⃣ css 에서 폰트 적용하기 👉 font-family : “폰트 이름”
🔥 폰트 이름 확인 하는 방법
구글 폰트
눈누
🔥 내가 적용한 방법
📜_variable.scss
4️⃣ 마무리
🤔 TMI
1️⃣ 무료 웹 폰트 사이트에서 사용할 폰트를 골라보자Permalink
눈누 https://noonnu.cc/index
구글 폰트 https://fonts.google.com/
내가 아는건 이렇게 두 사이트다. 이 두 사이트에서 예쁜 폰트를 골라보자!

🔥 첫 번째 추천 사이트 : 눈누Permalink
image

image

눈누에서 원하는 폰트를 클릭하면 웹 폰트로 사용 이라는 부분이 있다. 임포트 해야할 코드이니 복사하도록 하자!

@font-face {
    font-family: 'Cafe24Oneprettynight';
    src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_twelve@1.1/Cafe24Oneprettynight.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
@import url('https://cdn.jsdelivr.net/font-iropke-batang/1.2/font-iropke-batang.css');
여담으로 내가 현재 눈누로부터 임포트하여 블로그에 적용시킨 폰트는 아래 2가지이다. 나중에 폰트를 또 바꿀지도 모르지만..!

이롭게 바탕체 https://noonnu.cc/font_page/4
카페24 고운밤 https://noonnu.cc/font_page/342


🔥 두 번째 추천 사이트 : 구글 폰트Permalink
image

image

구글 폰트에서 Language 에서 한국어르 설정하면 한국어를 지원하는 폰트 목록을 볼 수 있다. 구글 폰트에서 원하는 폰트를 찾았다면 위와 같이 오른쪽에 “Select this Style” 을 클릭하자.

image

image

폰트를 선택하고 상단에 있는, 사진 속 체크된 곳을 클릭하면 임포트 코드를 복사할 수 있는 창이 오른쪽에 뜨게 된다.

CSS 에서 Import 할 것이라면 👉 @Import 코드로 복사
HTML 에서 Import 할 것이라면 👉 <link> 코드로 복사
아래에서 위의 2 가지 방법을 다 살펴볼 것이다. 그러나 성능 면에서 좀 더 나은 방법은 <head> 태그 안에 <link>를 사용하여 웹 폰트를 임포트 하는 것이라고 들었다! 웹 지식이 얕은 탓에 왜 그런지에 대한 이유는 잘 모르겠다..😅 아무튼 나는 후자를 선택했다.

<@import url: https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2304-01@1.0/omyu_pretty.woff2') format('woff2')>

배운 코드들 기록들 이것저것 모여있어요!  
아무거나 구경해보셔요><  
나중에 한꺼번에 꾸미고 수정할 예정  
물론 폰트도! sns 스터디 디코 추가 예정 
_1 되어있는 건 모두 공부기록  
</a>

<!--
**SeungYeon04/SeungYeon04** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
폰트 어캐 
-->
