# freelec-springboot2-webservice

##### src/main/resources/application-oauth.properties 파일이 없어 실행 안됨.
##### 필요하면 아래 코드 참조해 파일 생성


spring.security.oauth2.client.registration.google.client-id= 구글 id 토큰 <br>
spring.security.oauth2.client.registration.google.client-secret= 구글 pw 토큰 <br>
spring.security.oauth2.client.registration.google.scope=profile,email <br>

spring.security.oauth2.client.registration.naver.client-id= 네이버 id 토큰<br>
spring.security.oauth2.client.registration.naver.client-secret= 네이버 pw 토큰<br>
spring.security.oauth2.client.registration.naver.redirect-uri={baseUrl}/{action}/oauth2/code/{registrationId}<br>
spring.security.oauth2.client.registration.naver.authorization-grant-type=authorization_code<br>
spring.security.oauth2.client.registration.naver.scope=name,email,profile_image<br>
spring.security.oauth2.client.registration.naver.client-name=Naver<br>

spring.security.oauth2.client.provider.naver.authorization-uri=https://nid.naver.com/oauth2.0/authorize<br>
spring.security.oauth2.client.provider.naver.token-uri=https://nid.naver.com/oauth2.0/token<br>
spring.security.oauth2.client.provider.naver.user-info-uri=https://openapi.naver.com/v1/nid/me<br>
spring.security.oauth2.client.provider.naver.user-name-attribute=response<br>


