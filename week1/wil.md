웹 : 인터넷 위에서 동작하는 서비스 중 하나
클라이언트 - 서버 모델 클라이언트가 서버로 request(홍익대 메인 페이지 데이터 주세요). 서버가 클라이언트로 response(홍익대 메인 페이지 데이터 여기요) 
URL : 1. host-IP 주소 혹은 도메인 2. Port: 서버의 특정 네트워크 포트 번호 3. path: 서버 내에서 원하는 리소스의 경로 4. query: 서버에 추가적인 정보를 보냄 
http 주요 상태코드 200 ,201, 400, 404, 500 
내가 몰랐던 세계가 있다... 그냥 막 쓰던 홈페이지가 DB와 requset와 response로 나한테 화면을 보여준다니... 
404 not found만 알고 있었는데 그 외에도 많은 상태가 있다는거.... 신기하고 빨리 배우고싶다 ^^

![Whitelabel Error Page가 떴다면 성공](./image/localhost8080-1.png)

상품 정보 등록
HTTP Method : POST
URI : /products

상품 목록 조회
HTTP Method : GET
URI : /products

개별 상품 정보 상세 조회
HTTP Method : GET
URI : /products/{productid}

상품 정보 수정
HTTP Method : PATCH
URI :/products/{productid}

상품 삭제
HTTP Method : DELETE
URI :/products/{productid}

주문 정보 생성
HTTP Method : POST
URI :/order

주문 목록 조회
HTTP Method : GET
URI :/order

개별 주문 정보 상세 조회
HTTP Method : GET
URI :/order/{orderid}

주문 취소
HTTP Method : DELETE
URI :/order/{orderid}