<div style="margin: 2% 5%">

<br/>

### Argular , React , Vue 프레임워크 특징, 차이점
# 


```
안녕하세요, 한국에서 5년차 생황중인 주니오 프론트엔드 개발자입니다.

오늘 프론트엔드 개발자로써 채용 지원, 면접 준비 과정과 면접 후기를 정리해 기록해봤습니다.

```
<br/>

<div style="text-align : center">
  <img 
  style="width: 75%; border-radius: 10px;"
  src ="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Ftg094%2FbtrZLRWT7TY%2FOAgHwf5WeuPHFQ6ldbbHk0%2Fimg.jpg"> 
</div>

<br/><br/>

### ☆ Argular.js

```
Angular은 강력한 명령행 도구와 잘 정돈된 폴더 구조, 프로젝트 생성과 동시에 각종 
환경이 한 번에 갖춰지는 등 필요한 기능을 모두 내장한 프레임워크입니다. 특징은 
컴포넌트의 형태로 사용자 인터페이스를 정의하고, 자바스크립트 파일뿐 아니라템플릿 
역할을 할 HTML 파일이나 스타일시트가 담긴 CSS 파일도 컴포넌트에 포함한다는 
것입니다. 이 파일들은 컴포넌트마다 자동으로 생성됩니다. 

```
```
개인적으로 새용해보지 않았지만 Google이 개발한 Angular는 'decorator'를 많이
활용하는 선언적 코딩 스타일을 사용한다고 합니다. 태그명, 템플릿 파일, CSS 파일에 
대한 정보를 decorator 문법으로 전달하고 있습니다.
```

# 

###  ☆ React.js

```
React는사용자의 조작에 따라 사용자 인터페이스가 동적으로 변화하는 웹 
애플리케이션을 개발할 수 있게 해 주는 프론트엔드 라이브러리입니다. React 역시 
컴포넌트 기반이고 React는 XML 포맷의 템플릿을 직접 자바스크립트에 내장시키는 
형태로 JSX 기술을 주력으로 사용하는 것을 권장하고 있습니다. 그렇기 때문에 
다른 프레임워크에 비하여 더 자바스크립트에 집중된 형태의 컴포넌트가 나타나게 
됩니다.한마드로 Argular, Vue보다 React를 사용하려면 자바스크립트 보다 많은 
쓰인다는 점 느꼈습니다.
```

```
React만의 특징이 바로 데이터 바인딩 방법입니다. 알고 보니까 데이터 바인딩은 모델-뷰
(Model-View) 업데이트 처리 방식으로 차이 나는 기본적으로 단방향과 양방향이라는 두 가지 
구현방식이 있다고 합니다. 양방향 데이터 바인딩은 뷰가 변경되면 모델도 변경되며 모델이 
변경되면 뷰도 변경되는 처리방식입니다. 양방향 데이터 바인딩은 뷰가 변경되면 모델도 변경되며 
모델이 변경되면 뷰도 변경되는 처리방식입니다. React는 단방향 데이터 바인딩을 사용합니다. 
단방향 데이터 바인딩은 일반적으로 예측 가능성이 높기 때문에 코드가 더 안정적이지만, 
양방향 바인딩에 비해서 코드 작성시간이 더 필요합니다. 참고로 Angular와 Vue.js는 단방향 
데이터 바인딩과 양방향 데이터 바인딩 모두 지원합니다.
```
# 

###  ☆  Vue.js

```
Vue.js도 React처럼 컴포넌트 기반 개발을 중심으로 합니다. Vue.js만의 특징은 컴포넌트의 
자바스크립트 집중도가 낮다고 합니다. 컴포넌트 구조와 구성요소를 작성할 때 HTML 마크업 
기반의 템플릿 문법을 사용합니다. 다른 프레임워크들과 마찬가지로 Vue.js도 CLI 
( A command-line interface ) 툴을 제공합니다. 

```

```
그리고 애플리케이션 개발에 필요한 다른 모듈을 React처럼 사용자에게 책임을 맡기지 않고 
가이드 문서를 통해 특정모듈을 권장하고 있습니다. Angular처럼 내장모듈로 정해진 것은 
아니지만 React처럼 방임에 가깝게 두지도 않고 둘 사이를 절충한다고 볼 수 있습니다.
```

<br/>

<div style="text-align : center">
  <img 
  style="width: 80%; border-radius: 10px;"
  src ="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fbm7l03%2FbtrZK1rV5O9%2FDkn1k4azQTSiUWA4ptKQN1%2Fimg.png"> 
</div>

<br/>

# 

<br/>

###  ☆  NEXT.js 이란 ? 사용하는 이유 설명해보세요~

```
Next.js는 React 라이브러리의 프레임워크입니다. 아 그래도 복잡한 리엑트는 왜 Next를 
사용할까 궁금해서 알아보니까 Next.js를 사용하는 가장 큰 이유로 SEO (Search Engine Optimization)를 
위한 Server-Side Rendering(SSR)을 가능하게 하기 때문에 사용한다고 합니다. 알고 보니 
기본적으로 React는 Client Side Rendering(CSR)으로 실행하고 웹사이트를 요청했을 때 빈 html을 가져와
script를 로딩하기 때문에, 첫 로딩 시간도 오래걸리고 Search Engine Optimization(SEO)에
취약하다는 단점이 있으며 next.js는 pre-reloading을 통해 미리 데이터가 렌더링된 페이지를 
가져올수 있게 해주므로 사용자에게 더 좋은 경험을 주고, 검색 엔진에 잘 노출 될 수 있도록 
해주는 SEO에서도 장점을 얻을 수 있습니다. 

```

<br/>

<div style="text-align : center">
  <img 
  style="width: 80%; border-radius: 10px;"
  src ="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FDd7Zx%2FbtrZILp4Eb2%2FoMC0ObSVZ8DF1s1vJwtYV0%2Fimg.jpg"> 
</div>

<br/>


```
Next.js는 pre-rendering 뿐만 아니라 페이지 기반 라우팅 시스템도 제공하고 프로젝트의 가장 
바깥 폴더인 /pages 폴더에서 컴포넌트를 export하면 폴더명이 페이지 route가 되고 dynamic 
route도 지원한다고 나옵니다. 추가적으로 NEXT < Link /> 컴포넌트를 통해 페이지간의 빠르고 
매끄러운 이동을 가능하고 일반 HTML의 a 태그와 달리 페이지를 리로딩하지 않고도 페이지간 
이동이 가능하고, link 컴포넌트가 뷰포트에 보였을 때 관련 페이지를 백그라운드에서 미리 가져다 
놓기 때문에 사용자가 링크를 클릭했을 때 매우 빠르게 해당 페이지로 이동할 수 있게 해줍니다.

```

```
개인적으로 Next를 사용하지 못했지만 앞으로 리액트 기반으로 프로젝트 운영하게 되면 꼭 
같이 사용해보고 싶은 느낌이 들었습니다. 대부분의 사용자들은 웹페이지가 3초 이상 로딩될 
시 이를느리다 판단해서 NEXT 코드를 분할해 처음에 가장 필요한 부분만 전송해 주는
어플리케이션 로드 타임을 줄여주는 기능이 핵심이라고 볼 수 있습니다.

```


# 

<br/>

###  ☆  프레임워크 ( Framework )에 대해 설명해주세요.

```
프레임워크는 뼈대나 기반구조를 뜻하고, 제어의 역전 개념이 적용된 대표적인 기술입니다.
소프트웨어에서의 프레임워크는 '소프트웨어의 특정 문제를 해결하기 위해서 상호 협력하는 
클래스와 인터페이스의 집합' 이라 할 수 있으며, 완성된 어플리케이션이 아닌 프로그래머가 
완성시키는 작업을 해야합니다. 앱/서버 등의 구동, 메모리 관리, 이벤트 루프 등의 공통된 
부분은 프레임워크가 알아서 관리하며, 개발자는 서비스별로 다른 부분만 "프레임워크가 정해준
방식대로" 클래스, 메서드 등에 구현해두면 된니다.

```

<br/>

<div style="text-align : center">
  <img 
  style="width: 80%; border-radius: 10px;"
  src ="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbqU81f%2FbtrZNv0qXs3%2FAkLGFW7KAKyPJzNVE8USS1%2Fimg.png"> 
</div>

<br/>


```
프레임워크의 특징
1) 특정 개념들의 추상화를 제공하는 여러 클래스나 컴포넌트로 구성되어 있습니다.
2) 추상적인 개념들이 문제를 해결하기 위해 같이 작업하는 방법을 정의합니다.
3) 컴포넌트들은 재사용이 가능합니다.
4) 높은 수준에서 패턴들을 조작화 할 수 있습니다.

```

```
유명한 프레임워크로 몇가지 정리하면
1) Java 서버 개발에 사용되는 Spring
2) Python 서버 개발에 사용되는 Django, Flask
3) 안드로이드 앱 개발에 사용되는 Android
4) 아이폰 앱 개발에 사용되는 Cocoa Touch
5) 웹 개발에 사용되는 Angular, Vue.js 등

```
<br/>
<div style = "background-color: #000; text-align : start;  color: #fff; border-radius : 5px;"> 
<p style="padding : 10px; font-weight: bold; "><span style="color:#B9E9FC"> IsReact</span> ? Library : Framework </p>
</div>

<br/>

```

여기서 재미있는 내용은 "98% of Developers Use React as a Framework, Not a Library" React는
라이브러리긴 하지만, 98% 프레임워크처럼 사용합다고 나옵니다. 리액트공식 홈페이지로 들어가보면
"React , A JavaScript library for building user interfaces" 프레임워크 아니라 라이브러리라고
하지만 다양한 블로그나 글 검색해보면 "The React. js framework is an open-source JavaScript
framework and library developed by Facebook." 이란 내용을 볼수 있습니다.

```

<br/>

# 

<br/>


###  ☆  라이브러리( Library ) 대해 설명해주세요.

```
라이브러리(Library)는 간단히 설명하면 단순 활용가능한 도구들의 집합을 말합니다.
즉, 개발자가 만든 클래스에서 호출하여 사용, 클래스들의 나열로 필요한 클래스를 불러서 사용하는
방식을 취하고 있습니다.

```

```
사전적 의미로는 "소프트웨어를 개발할 때 컴퓨터 프로그램이 사용하는 비휘발성 자원의 모임이다."
정의되어 있습니다. 라이브러리 = 도서관이라는 개념과 같이 소프트웨어를 개발할 때 반복적인 코드
묶음이 있다거나 자주 생성하여 사용되어야 하는 메서드, 변수 등등을 '비휘발성'으로 만들어 간단한
호출을 통해 사용하는 것으로 정의될 수 있다.

```

<br/>

# 

<br/>



###  ☆  프레임워크와 라이브러리의 차이점 

```
쉽게 설명드리면 라이브러리는 톱, 망치, 삽같은 연장입니다. 사람이 들고 썰고, 바꿔들고 내려치고,
다시 바꿔들고 땅을 파는 겁니다. 도구를 쓸 때, 급하면 썰어야 할 곳에 망치를 쳐도 됩니다. 땅 파야할
때 톱으로 땅을 긁어내도 됩니다. 사람은 도구를 선택하는 입장이기 때문에, 어떤 도구를 사용하든
원하는 것을 만들어낼 수 만 있으면 됩니다.

```

```
프레임워크는 차, 비행기, 배같은 탈 것입니다. 사람이 타서 엔진 켜고, 기어 넣고, 핸들 돌리고,
운전하거나, 조종하거나 해야합니다. 반면에, 탈것은 정해진 곳으로만 다녀야 합니다. 차를 타고 하늘을
날거나, 배를 타고 땅으로 갈 수는 없습니다. 그 목적에 맞게 만들어져 있기 때문에 그저 정해진 규칙에
맞춰서 엔진, 기어, 핸들만 잘 돌리면 되는 것입니다.


```

<br/>

# 

<br/>



### List

* Item 1
* Item 2
* Item 2a
* Item 2b


### ☆ 바로 이동 | Links

You may be using [Markdown Live Preview](https://markdownlivepreview.com/).



</div>

