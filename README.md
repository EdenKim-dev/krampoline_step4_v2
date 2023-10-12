# krampoline-step4

## 소개

`krampoline-step4`는 krampoline으로 여러가지 앱들을 하나의 구성으로 배포하는 시나리오를 담고 있습니다.
이 저장소에서는 아주 간단한 mariaDB 이미지 생성과 여러가지 쿠버네티스 설정들을 담고 있습니다.

프론트엔드(React) 저장소와 백엔드(Spring) 저장소를 등록하여 도커 이미지를 만듭니다.
그리고 nginx 이미지를 가지고 와서 프론트엔드와 백엔드를 위한 프록시 서버 역활을 합니다.

현재 저장소에서는 nginx와 데이터베이스의 초기 데이터를 위한 config 파일이 있습니다.
쿠버네티스를 통해서 해당 설정들을 어떻게 하는지를 확인할 수 있습니다.


![image](https://github.com/MonoKim01/krampoline-step4/assets/85483855/1421cd44-8c34-4b6d-ab5e-222c9a63e4d7)
