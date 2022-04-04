## prop으로 전달되는 값의 type을 어떻게 강제하나요?  & 또 prop이 필수적으로 전달되게끔 어떻게 강제하요?



### 결론

prop-types 라이브러리 설치를 통해 해결가능하다.


### 설명
prop-types를 사용하여 구성요소에 전달된속성에 의도한 유형을 문서화 할수있다. 해당 정의에 대해 구성요소에 전달된 props를 확인하고 일치하지 않는경우 개발단계에서 경고한다.

### 요약
컴포넌트 props의 type을 확인하기 위해서는 props-types를 이용하여 기대되는 값의 type과 prop이 필수적인지 여부를 선언할수 있습니다. 

### 예상 꼬리질문 
<hr/> 

### 참고 
- [props-types 라이브러리](https://www.npmjs.com/package/prop-types)
- [propTypes , 리액트 공식문서](https://ko.reactjs.org/docs/typechecking-with-proptypes.html)
