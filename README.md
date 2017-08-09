# Main-BFF-Service

Smart Meeting Assistant 어플리케이션의 Single Page Application 기반의 Backend For Frontend 서비스


### 사용 프레임워크(런타임 및 버전 상세 필요)
* Node.js
* React.js
* Express

### 프로젝트 구조
Express기반의 서버에 React.js로 구현한 프론트엔드 어플리케이션을 PaaS상에 배포

### 로컬 리액트 앱 구동
main-bff-service 디렉토리에서 다음 명령어 실행
<pre><code>
$ npm install
$ npm start
</code></pre>

이후 http://localhost:8001 에서 어플리케이션 테스트

### 서버 빌드
main-bff-service 디렉토리에서 다음 명령어 실행

<pre><code>
$ npm install
$ npm run build
</code></pre>

main-bff-service/build에 빌드 파일 생성

main-bff-service/server 디렉토리에서 다음 명령어 실행

<pre><code>
$ npm install
$ npm run build
</code></pre>

main-bff-service/server/build에 빌드 파일 생성

다음 명령어로 서버 실행
<pre><code>
$ npm start
</code></pre>

http://localhost:8000에서 서버구동

### 기능
> 메인(디폴트 서비스 소개 페이지)

>> 로그인 → 로그인 페이지(폼 제공)

>>> 성공 → 메인 리다이렉트

>>> 실패 → 페이지 유지(실패 사유 반환)

>> 회원가입 → 회원가입 페이지(폼 제공)

>>> 성공 → 메인 리다이렉트

>>> 실패 → 페이지 유지(실패 사유 반환)

>> 유저정보 → 유저정보 페이지

>>> 유저정보 수정 → 유저정보 수정 페이지(폼)

>>>> 성공

>>>> 실패

>> 서비스 소개 → 서비스 소개 페이지

>> 회의 리스트 → 회원 리스트 페이지
