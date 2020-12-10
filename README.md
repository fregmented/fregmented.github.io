## About Me
애플리케이션 개발자입니다.

Kotlin을 주로 안드로이드 개발에 사용하고 Flutter로 크로스플랫폼 개발을 합니다.

그리고 서버사이즈 API를 파이썬으로 개발하고, ESP32와 STM32, AVR을 타겟으로 임베디드 애플리케이션을 개발합니다.

## My experience

### Languages
- C(🌟🌟🌟⭐⭐): 상용 수준의 임베디드 애플리케이션을 개발할 수 있습니다.
- C++(🌟🌟⭐⭐⭐): 임베디드 애플리케이션을 개발할때 C++도 같이 사용하며, 템플릿과 Boost에 대한 경험은 없습니다.
- Java(🌟🌟🌟⭐⭐),Kotlin(🌟🌟🌟⭐⭐) : 엔드유저 및 서버사이드 애플리케이션을 프로토타이핑 할 수 있으며, 상용 수준의 안드로이드 애플리케이션을 개발할 수 있습니다.
- Python(🌟🌟⭐⭐⭐): 서버 애플리케이션 및 오토메이션 스크립트, 유틸리티를 작성할 수 있습니다.
- Go(🌟⭐⭐⭐⭐): 취미와 프로토타입 수준의 애플리케이션을 개발할 수 있습니다.
- Dart(🌟🌟⭐⭐⭐): MVP수준에서 복잡한 애플리케이션과 상용수준에서 간단한 애플리케이션을 개발할 수 있습니다.

### Frameworks & Libraries
- Android(🌟🌟🌟⭐⭐): 간단한 커스텀뷰와 커스텀 다이얼로그, 서비스 및 논-블로킹 작업을 개발할 수 있습니다.
- RxAndroid(🌟🌟⭐⭐⭐): Observable을 만들고 예외처리 등을 할 수 있습니다.
- Flutter(🌟🌟⭐⭐⭐): 커스텀위젯과 iOS 및 Android를 위한 Flutter plugin을 개발할 수 있습니다.
- Flask(🌟🌟⭐⭐⭐): 서버사이드 렌더링 및 RESTful API 서버를 개발할 수 있습니다.
- SQLAlchemy(🌟🌟⭐⭐⭐): DB를 모델링할 수 있으며, 복잡한 쿼리를 SQLAlchemy로 구현할 수 있습니다.
- Terraform(🌟⭐⭐⭐⭐): 인프라스트럭쳐를 모델링하고 배포를 자동화 할 수 있습니다.

### Stacks
- Communications
  - Bluetooth
  - TCP/IP
  - HTTP/RESTful
  - gRPC

## My Projects

### 개인 프로젝트

#### Car Account [Link](https://github.com/fregmented/CarAccount)
##### 2020. 12 ~ WIP
개인적으로 차계부를 작성하기 위해 개발하고 있는 애플리케이션입니다.

Android X를 적극적으로 이용하여, Constraint Layout, DataBinding, Room, Navigation 등을 이용하여 개발하였으며, 

유가정보를 얻기 위해 오피넷의 API를 이용하기 위해 RxJava + Retrofit2를 이용한 RestAPI client를 작성하였습니다.

유료 API가 아닌 관계로 특정 주유소의 가격정보를 얻어오지는 못하지만, 현재 위치의 시도/시군구별 평균유가를 현시하고 비교할 수 있도록 구성하였습니다.

기본적으로 주유기록, 정비기록, 용품구매기록, 법정비용, 보험료를 저장하며, 각 항목별 및 합간 월/연도별 평균 비용을 확인할 수 있고, 최근 주유기록을 통해 연비를 계산할 수 있는 기능을 포함하고 있습니다.

#### Lotto [Link](https://github.com/fregmented/2019PortfolioAndroid)
##### 2019. 07 ~ 2019. 07
기술 시연용으로 개발한 앱으로, 기존 로또 번호를 조회하고 새로운 로또 번호를 만들어 기 회차의 로또 번호와 비교하는 앱으로 대략 3일의 시간동안 구현한 것입니다.

로또 번호를 조회하기 위해 okhttp3와 retrofit을 이용하였고, RxJAVA를 사용하려 했으나 RESTful한 API가 아닌 관계로 커스텀 이벤트버스를 구현하여 RxJAVA를 활용하였습니다.

또한 GSON을 이용한 DTO를 구현하여 native Kotlin data class를 이용할 수 있도록 하였습니다.

로또번호를 저장하기 위해 Realm 데이터베이스를 이용하였습니다.

UI면에서는 DataBinding과 RecyclerView를 이용하여 코드의 간략화를 꾀하였고, 본인이 이해한 MVVM 아키텍처를 최대한 구현하기 위해 노력하였습니다.

UX적인 면에서는 Navigation 라이브러리를 사용하여 자연스러운 화면 이동을 꽤하면서 Fragment 관리의 어려움을 최소하하였습니다.

### 컬처캠프(프리랜서 개발자) 2020. 01 ~ 현재

#### Feet Guider 기능 추가 개발 [Play Store](https://play.google.com/store/apps/details?id=com.feetguider)
##### 2020. 06 ~ 2020. 06
이전에 참여하였던 웨어러블 헬스케어 장비의 안드로이드/iOS 애플리케이션 기능 추가 및 호환성 개선작업

레거시 Social login SDK 를 Firebase Auth로 마이그레이션

Nordic DFU 라이브러리 마이그레이션

Nordic DFU 에러 수정

Android support 라이브러리 AndroidX로 마이그레이션

기타 버전 호환성 개선

발주처 - (주)비엠시스

#### 공기청정기 AWS IoT Core 라이브러리 개발
##### 2020. 06 ~ 2020. 06
![No Image available](/images/no_images.png)


ESP-IDF 환경에서 공통적으로 활용할 수 있는 통신 라이브러리 개발.

WiFi provisioning 관리

AWS IoT core 접속 및 데이터 송수신

Protobuf를 이용한 데이터 모델링

발주처 - (주)벤투스솔루션

#### 공기청정기 관리 애플리케이션 개발
##### 2020. 04 ~ 2020.06
![No Image available](/images/no_images.png)


공기청정기 관리를 위한 애플리케이션 개발

Flutter를 이용한 멀티플랫폼 구현

Firebase를 이용한 푸쉬메세지 핸들링
 
발주처 - (주)벤투스솔루션

#### 공기청정기 관리 서버 개발
##### 2020. 02 ~ 2020. 04
![No Image available](/images/no_images.png)


공기청정기 관리 및 모니터링을 위한 서버 및 인프라 구축

AWS(Lambda, IoT Core, RDS, SQS)를 이용한 서버리스 서비스 구축

Python(Flask, SQL-Alchemy)를 이용한 REST API 서버 개발

Zappa를 이용한 리소스 매니지먼트

Vue를 이용한 SPA 프론트엔드 개발

발주처 - (주)벤투스솔루션

#### 철도장비 모바일 모니터링 앱 개발
##### 2020. 01 ~ 2020. 02
![No Image available](/images/no_images.png)


철도장비 모니터링을 위한 블루투스 SPP 통신을 하는 안드로이드 애플리케이션 개발.

Kotlin으로 개발

SPP 통신에 Rx적용

Android Databinding 적용

MPAndroidChart를 이용한 바그래프 플로팅

realm을 이용한 데이터 저장

발주처 - 유진기공산업 (주)

### 피앤씨테크놀로지주식회사(개발자) 2019. 08 ~ 2019. 12

#### 파프리카 API서버 리뉴얼
##### 2019. 10 ~ 2019. 12
![No Image available](/images/no_images.png)

Flask와 zappa를 이용하여 REST API server 개발.

SQLAlchemy를 이용하여 Django orm으로 작성된 레거시 DB ORM을 재구현.

zappa를 이용하여 aws lambda에 서버 배포

#### 주차타워 관리자용 태블릿 애플리케이션 개발
##### 2019. 10 ~ 2019. 12
![No Image available](/images/no_images.png)


주차타워 관리자를 위한 안드로이드 태블릿 애플리케이션 개발

OKHTTP + Retrofit을 이용해 REST API client interface 구현

RxKotlin+RxAndroid를 이용한 Reactive REST API client 사용

Android DataBinding을 이용한 MVVM 디자인패턴 사용

### 참솔루션(프리랜서 개발자) 2018. 08 ~ 2019. 07

#### 가스 센서 컨트롤 보드 펌웨어 개발
##### 2019. 04~ 2019. 06
![No Image available](/images/no_images.png)


STM32F0(CortexM0/4kByte SRAM)을 이용하여 고객사 자체 개발 센서 제어 보드 펌웨어 개발

I2C 가스센서 제어 및 데이터 취득 펌웨어 개발.

캐릭터 LCD에 센서 값(실시간, 저장값) 표시 및 EEPROM에 저장.

UART통신을 이용하여 센서 제어 데이터 및 센서 검출 값 송수신.

발주처 - (주) 와이즈산전

#### 화학약품 제어 센서 컨트롤 보드 펌웨어 개발
##### 2018. 12 ~ 2019. 01
![No Image available](/images/no_images.png)


nuvoton NANO100(CortexM0/8kByte SRAM)을 이용하여 고객사 자체 개발 센서 제어 보드 펌웨어 개발

DAC, ADC 및 PWM을 이용한 센서 컨트롤보드 펌웨어 개발.

I2C, UART Peripheral 모드 디바이스

발주처 - (주) 와이즈산전

#### AirFeel 펌웨어 개발
##### 2018. 08 ~ 2018. 12
ESP32를 이용하여 먼지, 온/습도, TVOCs/eCO2, CO2 센서 드라이버 개발.

PMSx003 먼지센서, 온/습도 센서, TVOCs센서 및 CO2센서 사용.

128*64 Mono OLED 및 320*240 Color LCD를 이용하여 화면 표시(LittlevGL 사용)

현재 LG전자 및 영등포구 시설물에서 운용중

발주처 - (주)시대의영웅

### 주식회사고퀄(애플리케이션 개발자) 2017. 02 ~ 2018. 08

#### GOQUAL IoT Platform SDK 개발(Dropped)
##### 2018. 04 ~ 2018. 08
![No Image available](/images/no_images.png)


Kotlin을 이용하여 IoT Platform 커넥션을 위한 SDK 개발
RSA 암호화를 이용한 보안강화 및 HTTP request를 위한 다이나믹 result model 작성

#### GLS시리즈 Zigbee 스위치 펌웨어 개발
##### 2017. 04 ~ 2017. 11
NXP JN516x 환경에서 Zigbee Pro HA1.2 스택을 이용한 스마트 조명 스위치 개발

코맥스 및 Hejhome 브랜드로 출시 및 판매중

#### 10k 안드로이드 애플리케이션 개발
##### 2017. 02 ~ 2017. 04
![No Image available](/images/no_images.png)


기 개발제품 제어 애플리케이션 리팩토링

WebSocket과 MQTT, TCP Socket을 이용하여 스마트 스위치 제어

DataBinding과 Rx를 이용한 동적인 UI 로딩 구현 

### (주) 에스씨웍스(프리랜서 개발자) 2015. 05 ~ 2016. 10

#### Iot 디바이스와 연동한 실시간 위치추적 솔루션(Dropped)
##### 2015. 11 ~ 2016. 10
![No Image available](/images/no_images.png)


Flask를 이용한 웹서버 및 웹 프론트엔드 개발

IoT디바이스에서 보내는 TCP 패킷을 파싱하여 RESTful API 포워드 하는 TCP Socket 서버 제작

Google Firebase Cloud Messaging을 이용하여 사용자에게 이벤트 Notify

Highchart를 이용한 이벤트 및 사용 현황 현시
 
발주처 - (주)씨엔테크

#### Feet Guider 안드로이드 앱 개발 [Play Store](https://play.google.com/store/apps/details?id=com.feetguider)
##### 2015. 07 ~ 2015. 11
![FeetGuider 1](/images/FeetGuider_1.jpeg)
![FeetGuider 2](/images/FeetGuider_2.jpeg)
![FeetGuider 3](/images/FeetGuider_3.jpeg)

Realm을 이용하여 걸음 및 이동거리, 운동 현황 등을 저장

aChartEngine을 이용해 주간, 연간 운동 현황 현시
 
서버에 데이터를 업로드 하여 경쟁기능 구현

Google+및 Facebook 공유기능 구현

발주처 - (주)비엠시스

#### 중소기업 지원정보 애플리케이션 개발
##### 2015. 05 ~ 2015. 06
![FeetGuider 1](/images/SUGARAIN_1.jpeg)
![FeetGuider 2](/images/SUGARAIN_2.jpeg)
![FeetGuider 3](/images/SUGARAIN_3.jpeg)


XMLRPC를 이용하여 서버와 동기화

Realm을 이용하여 데이터 저장 및 현시

실시간으로 타겟 서버에서 HTML을 받아와 파싱하여 앱에 표시

발주처 - (주)플랜아이

### 에스씨웍스(개발자) 2014. 10 ~ 2015. 04

#### 주파수 도약을 이용한 음원 저작권 보호 시스템
##### 2015. 02 ~ 2015. 04
![No Image available](/images/no_images.png)


특허등록(10-1636948-0000)

음원 분석 및 데이터 밀도 측정 DSP 개발

포렌식 마커 생성 및 처리 인터페이스 제작

포렌식 마커 삽입 및 복원 DSP 개발

#### 음원 스트리밍 서비스 개발(Dropped)
##### 2014. 12 ~ 2015. 04
![No Image available](/images/no_images.png)


서버에서 음원을 스트리밍 받는 안드로이드 MediaPlayer wrapper 개발

네트워크 상황에 따라 적응하여 트랜스코딩하는 스트리밍 서버 개발

음원 보호 시스템 개발 및 적용

#### 대여관리 시스템 개발
##### 2014. 10 ~ 2014. 12
![No Image available](/images/no_images.png)


바코드를 이용해 대여 및 반납 관리 안드로이드 앱/서버 제작

위치정보를 이용하여 사용자 맞춤형 광고 알고리즘 개발

## Patents
- 주파수 도약을 이용한 음원 저작권 보호 시스템(10-1636948-0000)