# sanup-ready
# 정보처리산업기사 과정평가 공개문제(실기) 실습과정 (사전준비)
## 오라클 설치, jdk 설치 및 환경변수 설정, 이클립스 설치, 톰캣 설치
![이클립스 설ㅠㅣ,](https://user-images.githubusercontent.com/104752580/170621817-7d16c8b9-0c7a-4880-b05d-16771faa62d0.JPG)
이클립스 사이트에 들어가서 이클립스 설치 후 C:\학번으로 workspace를 만듭니다.
![Inked이클립스 작업_LI](https://user-images.githubusercontent.com/104752580/170622734-52855e8e-a41b-490d-b68b-152fc3d870b6.jpg)
이클립스에 들어간 후에는 표시 되어있는 박스 안에 windows-preferences-html,css,jsp,spelling,workspace 다 들어가서 encoding UTF-8를 적용시킵니다.
적용 시킨 후에는 new-Dynamic Web project 생성하고 Dynamic Web project-src-main-WEB-INF-lib 파일에 ojdbc6.jar파일을 import 시킵니다.
![오라클](https://user-images.githubusercontent.com/104752580/170633412-ff1b009d-c8bd-48c4-9159-ade760873122.JPG)
오라클 설치는 오라클 사이트에 들어간 후 다운로드를 찾고 사진에 있는 오라클 64비트짜리를 설치합니다. 
![오라클 연결](https://user-images.githubusercontent.com/104752580/170633863-c9945af8-cfb3-4f3a-bf59-5cd4787d3ec9.JPG)
오라클 설치 후에 오라클을 이클립스에 연결하려면 이클립스를 들어간 후에 네모에 있는 파일에 new를 누른후 oracle-new driver definition-oracle thindriver oracle 11 
선택 후 jar list에 들어가  ojdbc14.jar 삭제 후  ojdbc6.jar 추가합니다. 피니쉬 후에 service Name:xe - host:127.0.0.1 - user name:system - password:1234 입력하고
피니쉬를 누르면 오라클 연결이 완료됩니다.
![캡처](https://user-images.githubusercontent.com/104752580/170634734-44d97d6c-6993-4e71-a085-bd4e5fccbc1c.JPG)
![wwww](https://user-images.githubusercontent.com/104752580/170634740-831fcfcd-15a1-41a6-9e30-6b2aef81c0f8.JPG)
톰캣 설치는 톰캣 사이트에 들어간 후에 다운로드를 들어가 톰캣 8.5 이상에 톰캣을 다운로드를 받습니다.(컴퓨터 64비트, 32비트 자기 컴퓨터에 맞는 것 설치해주세요)
톰캣 설치 후 이클립스 연결은 http port : 8005, 톰캣 port : 8090 권장하고, 안되면 1000~9999까지 맞는 포트번호를 찾으시면 톰캣연결이 완료됩니다.
![jdk](https://user-images.githubusercontent.com/104752580/170635561-3d48087a-379f-4e93-a678-d94da3d3446f.JPG)
jdk 1.8 설치는 오라클 사이트에 java 설치를 들어가 설치합니다.(컴퓨터 64비트, 32비트 자기 컴퓨터에 맞는 것 설치해주세요)
![Inked환변_LI](https://user-images.githubusercontent.com/104752580/170636118-18ea016b-d85a-4546-925a-6c6dab74e4fe.jpg)
jdk 설치 후 환경변수 설정을 해주셔야 하는데 환경변수 설정을 하기위해서 제어판에서 환결편수를 검색하시고 환경 변수 편집에 들어갑니다.
환경변수 편집은 시스템변수는 새로 만들기를 이용해 변수 이름은 JAVA_HOME 변수값은 JDK 설치디렉토리 \ BIN을 해주시면 됩니다.
그리고 user에 대한 사용자 변수는 PATH를 클릭 후에 편집에 들어가서 변수 값을 %JAVA_HOME%로 바꿔주시면 환경변수가 적용됩니다.
jdk 1.8 확인은 cmd 창에서 javac를 겁색하시면 확인하실 수 있습니다. 이러면 모든 사전준비가 끝난 것 입니다.
