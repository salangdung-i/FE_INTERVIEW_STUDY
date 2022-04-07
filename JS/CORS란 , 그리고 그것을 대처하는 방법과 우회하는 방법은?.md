# CORS란 , 그리고 그것을 대처하는 방법과 우회하는 방법은?

## 결론

**교차 출처 리소스 공유**(Cross-Origin Resource Sharing, [CORS](https://developer.mozilla.org/ko/docs/Glossary/CORS))는 추가 [HTTP](https://developer.mozilla.org/ko/docs/Glossary/HTTP) 헤더를 사용하여, 한 [출처](https://developer.mozilla.org/ko/docs/Glossary/Origin)에서 실행 중인 웹 애플리케이션이 다른 출처의 선택한 자원에 접근할 수 있는 권한을 부여하도록 브라우저에 알려주는 체제입니다. 

## 요약

CORS는 크로스 오리진 리소스 쉐어링의 줄임말로, 동일한 도메인이 리소스를 요청할때 서로 다른 오리진에 대해 http요청이 가능하게 해주는 표준입니다.

대처하는방법으론 액세스-컨트롤 -얼로우- 오리진을 통해 헤더의 접근권한을 "*"로 설정하게 되는 방법도있지만 보안적인 이슈가 있어 좋지가 않습니다. 

그렇기에 외부출처를 일일히 적용하는것입니다.

외부출처 추가는 '액세스-컨트롤-얼로우-오리진'에 헤더를 적용하여 주면됩니다.

그외에 프록시 설정방법이 있습니다 프록시서버는 브라우저 규약에 영향받지않는것으로 알고있습니다. 

## 예상 꼬리질문

1. [GET, POST의 차이는 무엇입니까 ?](./GET, POST의 차이는 무엇입니까 ?.md)

2. Origin이란 무엇입니까 ?

   Origin이란 출처를 말하며, Protocol + Host + Port 를 합친 것을 의미합니다

3. [HTTP와 HTTPS의 차이점에 대해 설명해주세요.](./HTTP와 HTTPS의 차이점에 대해 설명해주세요.md)

​		



