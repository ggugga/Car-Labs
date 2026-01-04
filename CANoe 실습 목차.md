(용어정리)
전장 네트워크란? = 차량 내부 ECU들이 데이터를 주고받는 통신 구조

### 	1.	Vehicle Network Fundamentals → 차량 네트워크 기초
---

###### <span style="color:red">(1~5) 차량 통신 시스템 개요</span>

자동차 ECU 네트워크 구조와 버스 통신의 주요·확장 기능을 이해하고, 차량 SW 설계 표준과 기능 도메인별 네트워크 특성을 학습합니다.

1.	ECU networking in the Automotive Field

→ 자동차 분야에서의 ECU 네트워크 구성

2.	Primary Tasks in Bus Networking

→ 차량 버스 네트워크의 주요 기본 기능

3.	Extended Tasks in Bus Networking

→ 차량 버스 네트워크의 확장 기능

4.	Classification of Tasks in Bus Networking

→ 차량 버스 네트워크 기능의 분류

5.	Automotive Application Domains and Serial Bus Systems

→ 자동차 기능별 도메인과 직렬 버스 시스템






### 02 CAN Protocol → CAN 프로토콜
---

CAN 프로토콜의 주요 기능들을 이해하고, CAN FD와 CAN프로토콜의 차이점을 알아보고 CAN FD의 장점들을 확인합니다.

###### (1~8) CAN Protocol

1.	CAN Protocol Introduction

→ CAN 프로토콜 개요

2.	Physical Layer

→ 물리 계층

3.	Addressing

→ 식별자(ID) 기반 주소 지정 방식

4.	Bus Access

→ 버스 접근 방식(중재 메커니즘)

5.	CAN Framing

→ CAN 프레임 구조

6.	Data Protection

→ 데이터 보호 및 오류 검출

7.	Synchronization

→ 통신 동기화 메커니즘

8.	CAN with Flexible Datarate

→ 가변 데이터 전송률을 지원하는 CAN (CAN FD)






### 03 CAN Database → CAN 데이터베이스
---

네트워크 디스크립션 파일의 개념을 이해하고, CAN Database를 직접 작성해 CANoe에서 활용합니다.

###### (1~2) CAN Database 생성

1.	Introduction and Definitions

→ 네트워크 디스크립션 파일 개요 및 용어 정의

2.	CANdb++ Editor

→ CANdb++ 편집기 실습

##### 메시지·신호를 정의하는 CAN Database를 직접 설계·활용할 수 있습니다.






### 04 CANoe Measurement & Analysis → CANoe 계측 및 분석
---

CANoe 기본 환경 설정과 실시간 데이터 계측, 분석·전송·로깅 기능을 이해하고 활용 방법을 학습합니다.

###### (1~2) CANoe Setup

1.	Hardware Interface and Configuration

→ 하드웨어 인터페이스 연결 및 설정

2.	Main Windows

→ CANoe 메인 윈도우 구성

###### (3. CANoe 통한 CAN 프레임 분석)

3.	Analysis Windows

→ 데이터 분석 창 활용

###### (4. 시그널 분석)

4.	System Variables

→ 시스템 변수 활용

(5. CANoe 통한 CAN 프레임 분석)

5.	Filter

→ 데이터 필터링 기능

###### (6~8 CAN data 로깅)

6.	Data Logging

→ 데이터 로깅(기록) 기능

7.	Import and Export of Data

→ 데이터 가져오기 및 내보내기

8.	Offline Mode

→ 오프라인 분석 모드

(9. CAN 메시지 송신)

9.	Sending

→ 메시지 전송 기능

(10. 패널)

10.	Panels

→ 패널(사용자 인터페이스) 구성

##### CANoe를 활용해 차량 CAN 통신을 분석·재현하고, ECU 동작 검증 및 문제 원인 분석이 가능합니다.






### 05 CANoe Simulation → CANoe 시뮬레이션
---

CANoe 시뮬레이션 환경을 구성하고, 신호 제어와 CAPL 프로그래밍으로 데이터 처리·메시지 전송·분석 방법을 학습합니다.

###### (1~2 CANoe Simulation 소개와 구성)

1.	Use Case

→ CANoe 시뮬레이션 활용 사례

2.	Simulation with CANoe Interaction Layer

→ CANoe 인터랙션 레이어 기반 시뮬레이션

###### (3 시그널 분석)

3.	Signal Access

→ 신호 접근 및 제어 방법

###### (4~10) CAPL 

4.	CAPL Getting Started

→ CAPL 시작하기

5.	CAPL Basics

→ CAPL 기본 문법

6.	Variables in CAPL

→ CAPL 변수 사용법

7.	Signal-Based CAPL

→ 신호 기반 CAPL 프로그래밍

8.	Sending Messages in CAPL

→ CAPL을 이용한 메시지 전송

9.	System Variables in CAPL

→ CAPL 시스템 변수 활용

10.	Analysis using CAPL

→ CAPL을 활용한 데이터 분석

##### CANoe에서 ECU를 시뮬레이션하고 CAPL로 신호·메시지를 제어·분석하여 차량 통신 동작을 자동화·검증할 수 있습니다.
