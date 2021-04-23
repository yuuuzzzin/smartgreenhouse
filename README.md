:pencil: 한국컴퓨터정보학회(KSCI) 논문지 Vol.25 No.11 [2020] 에 'IoT 기반 스마트 온실' 논문 등재

# SmartGreenHouse
박유진, 김경연, 강재연, 노정민

### 🌱 프로젝트명
#### IoT 기술을 활용한 스마트 온실 프로젝트

### :mag_right: 프로젝트 소개
--------------------------------------
- 온실에 부착된 센서를 통해 온실 상태를 실시간으로 측정
- 최적의 생육 환경 조성을 위해 자동으로 장치를 제어
- 온실에 부착된 카메라를 통해 언제 어디서나 반려 식물들의 상태를 확인 및 관리

### :mag_right: 개발배경 및 필요성
--------------------------------------
- '반려식물’ 이라는 새로운 트렌드 등장
- 반려식물을 제대로 관리하지 못해 죽는 상황 방지
- 장기간 여행 및 출장 시 식물 관리의 어려움 해소

### :mag_right: 주요 기능
--------------------------------------
#### S/W
- **원격 제어**
    - 사용자가 온실내 장치(워터펌프, LED, 쿨링팬)를 원격으로 제어
    - 시간을 설정해 장치 작동 예약이 가능
    - Volley API를 사용해 웹서버와 HTTP 통신
- **실시간 온실 상태 확인**
    - 어플리케이션에서 온실의 상태(온도, 습도, 토양습도, 물 양, 조도)를 확인
    - Volley API를 사용해 웹서버와 HTTP 통신
- **OpenAPI를 이용한 식물 생장 정보 확인**
    - 농업기술포털 '농사로'의 openAPI를 이용해 어플리케이션에서 식물 생장 정보를 확인하고, 이를 토대로 온실 환경을 설정
    - 다양한 식물 정보 조회 가능
- **실시간 온실 영상 스트리밍**
    - 온실에 부착된 카메라를 이용해 온실 촬영 영상 스트리밍
- **데이터 시각화**
    - 센서로 부터 수신한 값을 가공해 주간 및 월간 라인 차트로 데이터 시각화
### H/W
- **장치 작동 기능**
    - 워터펌프, LED, 쿨링팬을 설정에 따라 작동
- **센서 값 측정**
    - 온습도, 토양습도, 조도센서 등의 장치를 통해 온실의 상태 값을 수신
### :mag_right: 개발환경
--------------------------------------
![20210423_141718](https://user-images.githubusercontent.com/57751515/115823061-9f281b00-a440-11eb-8224-312746bbb636.png)
### :mag_right: 작품 구성도
--------------------------------------
#### 시스템 구성도
![20210423_144040](https://user-images.githubusercontent.com/57751515/115824105-68530480-a442-11eb-969a-9987b1afc717.png)
#### H/W 구성도
![20210423_144405](https://user-images.githubusercontent.com/57751515/115824134-756ff380-a442-11eb-9aac-aeae8548d3e8.png)
#### 시스템 수행 시나리오
![20210423_144139](https://user-images.githubusercontent.com/57751515/115824278-a8b28280-a442-11eb-9a60-0d17207ff7a3.png)
#### 서비스 흐름도
![20210423_144818](https://user-images.githubusercontent.com/57751515/115825783-e31d1f00-a444-11eb-9a91-b4b3c02368ba.png)
    - 사용자 식물 종류 설정<br>
        1. 사용자가 식물 목록과 정보 확인<br>
        2. 온실에서 기르고자 하는 식물을 선택<br>
        3. Application 메인화면에서 현재 선택한 식물 목록 확인<br>
     - 사용자 온실 환경 설정<br>
        1. 사용자가 온실 환경 자동제어 선택<br>
        2. 자동제어를 선택한 경우, 온실 상태에 따라 자동으로 장치가 작동<br>
        3. 수동제어를 선택한 경우, 사용자의 설정에 따라 장치가 작동<br>
### :mag_right: 결과물
--------------------------------------
#### 온실 제작 모형
#### Application
#### Arduino, Ras
