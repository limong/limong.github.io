---
title: "개발자, PO, 데이터사이언스 삼자대면 - 래빗톡"
metadate: "hide"
categories: ['행사, 밋업']
image: "/assets/img/post/2024-02-17-seminar_3PM_dev_po_data/all.jpg"
---


#### 래빗톡 삼자대면: 개발, PO, 데이터 과학자의 원칙

2024년 2월 15일 래빗톡에서 열린 삼자대면에서는 개발자, 프로덕트 매니저(PO), 데이터 과학자 세 직무의 시니어분들이 각 직무별 원칙과 협업에 대한 이야기를 나누었습니다.

<br />

##### 개발 원칙: 제어 가능한 요소에 집중하라
![래빗톡 QnA 사진](/assets/img/post/2024-02-17-seminar_3PM_dev_po_data/dev.jpg)
이동욱 님은 `"제어할 수 없는 것에 의존하지 않기"`라는 개발 원칙을 강조했습니다. 주민등록번호를 primary key로 사용하거나 시니어 개발자 채용에 의존하는 것처럼 제어 불능한 요소에 의존하는 것은 문제를 야기할 수 있습니다.

1. 주민등록번호 사용의 문제점
   - 과거 시스템에서 주민등록번호를 회원키로 많이 사용했으나, 2014년 개인정보 보호법 개정으로 인해 법적으로 저장 불가능하게 됨.
   - 모든 시스템에서 주민등록번호를 다른 값으로 변경하는 작업이 필요했음.
주민등록번호는 개발자가 제어할 수 없는 요소이며, 이에 의존하는 것은 문제를 야기할 수 있음.

2. 시니어 개발자 채용의 어려움
   - 훌륭한 시니어 개발자를 채용하여 프로젝트를 진행하려는 것은 좋은 생각이지만, 실제로 채용하는 것은 매우 어려움.
시니어 개발자 채용은 개발자가 직접 제어할 수 없는 요소임.

3. 제어 가능한 요소에 집중하는 해결책
   - 내부 고유값 생성: 주민등록번호 대신 내부에서 관리할 수 있는 고유값을 사용하여 회원 식별 문제 해결.
   - 내부 개발자 성장 및 프로세스 개선:
     - 외부 시니어 개발자 초빙 강연
     - 소나큐브, 테스트 코드 작성, ESLINT 도입 등 내부 시스템 강화
     - 팀원 역량 개발을 통한 프로젝트 성공 가능성 높이기

핵심은 내가 제어 가능한 요소에 집중하여 문제를 해결하는 것입니다. 예를 들어, 내부 고유값을 사용하거나 내부 개발자 성장과 프로세스 개선에 투자하는 것이 바람직합니다.


> 나의 생각.
이동욱님은 개발자가 20명 정도일 때 인프런에 조인하였고 조직을 성장시키면서 했었던 고민을 들을 수 있었습니다. 개발자 채용에 고민은 많은 나에게도 다른 시각의 고민거리를 가져다 주었습니다. 
반면에, 현장의 질문에 대답에 대한 답변은 저는 조금 아쉬웠습니다. 현재 CTO로써의 고민을 답해주신것으로 생각이 드는데 선배 개발자로써의 답변을 주셨으면 더 좋지 않았을까? 라는 생각이 들었습니다.


<br />

##### 프로덕  원칙: 서비스를 뜯어보며 성장하라
![래빗톡 QnA 사진](/assets/img/post/2024-02-17-seminar_3PM_dev_po_data/po.jpg)
이미림 님은 `"서비스를 뜯어보며 성장하자"`라는 PO 원칙을 제시했습니다. 경쟁사를 포함한 다른 서비스를 벤치마킹하여 문제점을 파악하고 개선하는 것이 중요합니다.

6가지 단계를 통해 서비스를 뜯어볼 수 있습니다.

1. 현황 파악: 주문서 이탈률이 높다는 문제를 파악합니다.
2. 호기심: 경쟁사의 주문서를 살펴보고 궁금한 점을 파악합니다.
3. 목적: 주문서 이탈 요소를 예측하고 개선 목표를 설정합니다.
4. 방법: 모바일 주문서 UI/UX 정보를 분석합니다.
5. 정리: 주요 경쟁사의 주문서 이탈 방지 장치를 파악합니다.
6. 적용: 이탈 사유에 대한 가설을 세우고 개선 방안을 적용합니다.

 
> 나의 생각.
PO로써 개발자와의 협업이나 갈등의 문제점은 목표가 얼라인 되지 않아서 발생하는 것이고 PO로써 컨센서스를 더욱 잘 맞춰야 한다고 이야기 해준것이 기억에 남습니다. 

<br />

##### 데이터 과학자의 원칙: 비판적 사고 스킬로 문제를 해결하라
(사진을 못 찍었네요..ㅜ)
이진형 님은 `"비판적 사고 스킬로 문제를 해결한다"`라는 데이터 과학 원칙을 강조했습니다. 직관에 의존하지 않고 7가지 단계를 통해 문제를 정의하고 해결해야 합니다. 

1. 문제 식별: 어떤 문제가 있는지 명확하게 정의합니다.
2. 조사: 다른 앱, 모범 사례, 고객 선호도 등을 조사합니다.
3. 데이터 관련성 확인: 데이터로 검증 가능한 지표를 확인합니다.
4. 질문: 가정이나 가설에 대한 질문을 던지고 놓치고 있는 부분을 파악합니다.
5. 최선의 해결책 식별: 여러 해결책 중 최선을 선택하거나 A/B 테스트를 통해 최적의 방안을 찾습니다.
6. 해결책 제시: 5단계에서 도출된 해결책을 적용합니다.
7. 결과 분석: 결과를 분석하고 개선점을 찾습니다.


> 나의 생각.
문제 해결 방법에 대해서 다시 생각해 볼 수 있었고, 실무에 활용해보고 싶었습니다.


![래빗톡 종료](/assets/img/post/2024-02-17-seminar_3PM_dev_po_data/end.jpg)*래빗톡이 끝나고 저자분들과 밍글 시간도 있었습니다*

개발, PO, 데이터 과학자의 원칙을 들을 수 있는 시간이였습니다. QnA 시간에서 진행자분께서 직무별 싸움을 붙일만한 주제에 대해서 질문을 주셨는데 생각보다 평온해서 조금 아쉬웠습니다ㅋㅋㅋ 다음에는 개발자 원칙 책의 모든 저자들과 래빗톡도 계획이 있다고 하는데 시간이 되면 꼭 참석해야겠습니다.

<br />

##### Appendix
- [래빗톡삼자대면](https://goldenrabbit.co.kr/event/%EB%9E%98%EB%B9%97%ED%86%A12-%EC%9B%90%EC%B9%99%EC%9E%90%EB%93%A4-%EC%82%BC%EC%9E%90%EB%8C%80%EB%A9%B4-%EC%8B%A0%EC%B2%AD%ED%95%98%EA%B8%B0/)