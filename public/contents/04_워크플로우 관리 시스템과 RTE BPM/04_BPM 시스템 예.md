# BPM 시스템 예
이 절에서는 현재 널리 사용되고 있는 국산 및 외산 제품을 하나씩 소개하고자 한다. 우선 외산 제품으로 Filenet P8 Business Process manager는 <그림 3-3> 과 같이 그 구성 요소로서, 1) 프로세스 자동화를 위한 프로세스 설계 도구 및 2) 프로세스 엔진, 3) 모델링 시 사전 분석 도구인 프로세스 시뮬레이터와, 4) 실행 시 발생한 데이터를 이용하여 성과를 측정하고 리포팅하는 프로세스 분석기를 기본으로 하고 있으며, 5) 타 시스템과의 통합을 위해 정형/비정형 정보를 관리하는 컨텐츠 엔진과, 6) SAP나 IBM websphere server등과의 통합을 위한 EAI (Enterprise Application Integration) 미들웨어와, 7) 자바 오브젝트나 웹 서비스와 직접 호출하기 위한 컴포넌트통합기와 8) ILOG jRule과 같은 규칙 엔진과의 연계 기능을 갖추고 있다.



3-3
그림 3-3) Filenet P8 Business Process Manager 구조
![](/contents/04_워크플로우%20관리%20시스템과%20RTE%20BPM/04/img1.png)


3-4
그림 3-4) BizFlow BPM 구조
![](/contents/04_워크플로우%20관리%20시스템과%20RTE%20BPM/04/img2.png)




국내에서 개발된 핸디 소프트의 BIzFlow BPM은 <그림 3-4> 에서와 같이 그 구성 요소로 1) 프로세스 설계, 단위 업무 설계, 어플리케이션 설계 등 설계 모듈과 2) 프로세스 운영/모니터링 모듈, 3) 프로세스 결과 분석 모듈 및 4) 데이터 및 응용 시스템 통합 모듈로 구성되어 있다.



3-5
그림 3-5) BizFlow BPM 프로세스 디자이너
![](/contents/04_워크플로우%20관리%20시스템과%20RTE%20BPM/04/img3.png)




<그림 3-5> 는 BIzFlow BPM에서 프로세스 디자이너를 이용하여 전체적인 프로세스를 정의하는 방법과 프로세스 내의 단위 활동의 속성을 상세히 입력하는 것을 나타내고 있다. 즉, 단위 활동 속성인 활동 이름, 참여자, 입력, 출력 및 종료 기한 등을 입력한다.



3-6
그림 3-6) BizFlow BPM 단위 활동 유형
![](/contents/04_워크플로우%20관리%20시스템과%20RTE%20BPM/04/img4.png)




<그림 3-6> 은 BIzFlow BPM에서 프로세스 정의에 사용되는 다양한 단위 활동 유형을 나타내고 있다. 활동의 특성에 따라 일반 업무나 에이전트 소프트웨어에 이한 자동 업무, 메일 발송 및 데이터베이스 갱신 등의 업무로 구분된다.

프로세스 실행 단계에서는 <그림 3-7> 과 같이 프로세스를 개시하고 해당작업자는 자신의 작업 목록에서 작업 항목을 선택하여 작업을 처리하고, 관리자나 작업자는 해당 프로세스의 현재 상태를 모니터링 하여 작업을 수행및통제해 나가는 과정을 거치게 된다.



3-7
그림 3-7) BizFlow BPM 프로세스 실행
![](/contents/04_워크플로우%20관리%20시스템과%20RTE%20BPM/04/img5.png)




참고문헌
(1) 안승해, 백창현, Workflow, 시사정보기술, 2000.
(2) 핸디소프트, Handy BPM, www.handysoft.co.kr, 2007.
(3) Janowski W. Management Update: The Real-Time Enterprise at the Customer Front Line, Inside Gartner: Note Number IGG-05282003-01. 2003.
(4) IBM, IBM FileNet Business Process Manager, www.ibm.com, 2007.
(5) Smith H. and Fingar P., Business Process Management- The Third Wave, Meghan-Kiffer Press, Tampa, FL,2003.
(6) Workflow management Coalition, Workflow management coalition terminology & glossary (Document number WFMC-TC-1011), www.wfmc.org, 1999.
(7) Workflow Management Coalition, Workflow Reference Model (Document Number TC00-1003), http://www.wfmc.org, 1998.