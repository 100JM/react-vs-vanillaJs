# react-vs-vanillaJs
참고자료 : 노마드코더 https://nomadcoders.co/react-for-beginners

## react가 좋은점
노드정보가 바뀔때마다 노드트리를 처음부터 다시 생성하는 vanilla javascript와 달리 가상돔을 사용하여 수정이 필요한 부분만 수정하여 보여주고 모든 수정이 끝나면 일괄로 합쳐 실제 돔에 전달해준다.

## JSX 란?
javascript의 확장 문법

## babel 이란?
react로 개발을 할때 상당 부분을 JSX로 코드를 작성한다.
허나 JSX는 공식적인 JS문법이 아니기 때문에 브라우저는 이를 이해하지 못한다.
때문에 babel은 이러한 부분을 해결하기위해 브라우저가 인식할 수 있도록 JS로 변환시켜준다.
