# React

<br>

## 1. React란?
> - React는 UI 컴포넌트 라이브러리다. 
> - 다른 템플릿 언어가 아닌 자바스크립트를 이용해서 만듬
> - 여러 컴포넌트로 UI를 구성하는 방식이 React의 핵심 철학!

React 공식 웹 사이트의 설명<br>
```
' 우리가 해결하고자 한 문제는 시간에 따라 변화하는 데이터를 다루는 거대한 애플리케이션 개발이다.'
```

<br>

## 2. React 장점

### 장점

> - 단순한 앱 개발 
>   - React는 순수 자바스크립트로 만든 컴포넌트 기반 아키텍처이다. 
>   - 강력하고 개발자 친화적인 DOM 추상화 제공 
> - 빠른 UI 
>   - 가상 DOM 채택과 DOM의 변경 사항을 비교할 때 사용하는 알고리즘 덕분에 뛰어난 성능을 제공한다.
>- 코드량 감소 

### 간결성 

- 선언형 스타일 채택 : React는 뷰를 자동으로 갱신하는 선언형 스타일 채택 
- 순수한 자바스크립트를 이용한 컴포넌트 기반 아키텍처
- 강력한 추상화 : React는 DOM을 쉽게 다룰 수 있고, 같은 기능이지만 크로스 브라우징을 위해 다르게 구현할 수 밖에 없었던 인터페이스나 이벤트 핸들링을 정규화 했다. 

#### 선언형 스타일 채택 

> React는 명령형 대신 선언형 스타일을 채택했다. <br>
> - 명령형 스타일 : 개발자가 순서대로 무엇을 해야 할지를 작성하는 스타일 
> - 선언형 스타일 : 실행 결과가 어떻게 되어야 할지를 코드로 작성하는 스타일 <br>
>
> 선언형 스타일이 나은 이유? <br>
> - 복잡도를 줄여줄 뿐만 아니라 코드에 대한 이해도와 가독성을 높일 수 있기 때문.<br>
> - 개발자 UI 요소를 선언형 스타일로 작성한 후 뷰에 변경이 발생하는 경우 React가 알아서 갱신한다. <br>
> - React는 내부적으로 가상 DOM을 사용하여 브라우저에 이미 반영된 뷰와 새로운 뷰의 차이점을 찾아낸다.

<br>


