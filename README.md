
# VaccinateCenterApi
공공데이터활용지원센터_코로나19 예방접종센터 조회서비스
# data 
1)예방접종 센터 정보를 가져오는 api 입니다.
2)예방접종 센터의 주소 , 장소 시,군,구 , zipcode data 를 가져옵니다.
<img width="692" alt="스크린샷 2021-07-22 오전 11 19 01" src="https://user-images.githubusercontent.com/69393030/126582021-a30f52cc-780a-4bb1-915d-daa1e74c8672.png">
# 사용법
<img width="397" alt="스크린샷 2021-07-22 오전 11 20 19" src="https://user-images.githubusercontent.com/69393030/126582081-e4a89ddd-fd92-45a3-8476-2a016f38275e.png">
발급받은 인증키를 queryString 으로 json data 를 가져올것이므로 , 아래 두번째 인증키를 넣는곳에 입력해줍니다.
# 데이터 가공 (dto) 
<img width="397" alt="스크린샷 2021-07-22 오전 11 20 45" src="https://user-images.githubusercontent.com/69393030/126582101-9e0c392c-2b7f-4913-b7d7-0d957f560d7f.png">
# open Api 호출 
<img width="595" alt="스크린샷 2021-07-22 오전 11 21 54" src="https://user-images.githubusercontent.com/69393030/126582152-9667a593-0daa-40f9-aee6-e0492ef66cc6.png">
# success (202) result 
<img width="595" alt="스크린샷 2021-07-22 오전 11 22 24" src="https://user-images.githubusercontent.com/69393030/126582178-94a956a1-87e7-412e-87d3-2963401d76b7.png">

# java code (server)
<img width="1108" alt="스크린샷 2021-07-22 오전 11 22 58" src="https://user-images.githubusercontent.com/69393030/126582207-865f40c5-363d-46e1-933d-49205ba0b160.png">
# vue.js code (front-client)
<img width="731" alt="스크린샷 2021-07-22 오전 11 23 49" src="https://user-images.githubusercontent.com/69393030/126582237-62c0a08f-2e9e-4b03-9f6d-563f33575a5d.png">
# Result 
<img width="1172" alt="스크린샷 2021-07-22 오전 11 24 17" src="https://user-images.githubusercontent.com/69393030/126582260-46fcf9a7-1ceb-43d6-b62b-0aa0e4226b12.png">
데이터를 json format 으로 정상적으로 가져옴.






