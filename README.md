<p align="middle" >
  <img width="100%" alt="네일리안 메인 배너" src="https://github.com/user-attachments/assets/7cff8c7d-949c-46c4-94a3-51ddd493cab3" />
</p>
<h1 align="middle">Nailian (네일리안)</h1>
<h3 align="middle">내 손에 직접 입혀보고 찾는 나만의 네일</h3>

<br/>

## 📝 작품소개
**네일리안**은 네일 아트 시안 탐색의 번거로움을 해결하고, 자신의 손에 어울리는 디자인을 미리 체험해볼 수 있는 **AI 기반 네일 큐레이션 플랫폼**입니다. 기존 플랫폼에서 겪는 과도한 광고나 실제 시술 가능 여부 확인의 어려움을 해결하고자 하며, AI를 활용한 맞춤형 추천과 실시간 AR 체험 기능을 제공합니다.

<br/>

## 🌁 프로젝트 배경
20대 여성 104명을 대상으로 조사한 결과, 약 **82%의 사용자**가 원하는 네일 시안을 찾는 데 **1시간 이상**을 소요하고 있었습니다. 인스타그램과 같은 기존 플랫폼은 광고가 너무 많고 필터링 기능이 제한적이며, 핀터레스트는 마음에 드는 시안을 시술할 수 있는 샵을 찾기 어렵다는 문제점이 있었습니다.

<p align="middle">
  <img width="100%" alt="설문조사 결과" src="https://github.com/user-attachments/assets/fc7d15e3-fbcf-4467-a40e-22b065b12980" />
</p>

| 서비스명 | 플랫폼 유형 | 특징 | 단점 |
|---|---|---|---|
| **인스타그램** | SNS | 다양한 시안 탐색 가능 | 과도한 광고 및 필터링 부족 |
| **핀터레스트** | 이미지 검색 | 취향 기반 추천 | 시술 가능 샵 확인 불가 |
| **네일리안** | **큐레이션 앱** | **AI 기반 개인화 및 AR 체험** | - |

<br/>

## 🎞 Demo
- **iOS 출시 완료**: 2025년 4월 25일 정식 배포되었습니다.
- 실시간 손톱 스캔 및 AR 디자인 합성 기능을 지원합니다.

<p align="middle">
  <img width="100%" alt="앱 시연 이미지" src="https://github.com/user-attachments/assets/834b3a37-8292-4b6e-955f-1665da1bc7b6" />
</p>

<br/>

## ⭐ 주요 기능
- **취향 기반 추천**: 사용자가 선택한 취향(러블리, 심플, 키치 등)에 맞는 AI 생성 네일 시안을 제안합니다.
- **AR 가상 체험**: iOS용 hand landmark detection 모델과 결합하여 자신의 손 위에 네일 시안을 정교하게 매핑하여 미리 볼 수 있습니다.
- **퍼스널네일 셀프 측정**: 손가락의 두께, 길이, 피부톤 등을 입력하면 7개 유형 중 본인에게 맞는 결과를 도출하고 어울리는 아트를 추천합니다.
- **나만의 아트 생성**: 마음에 드는 시안을 조합하여 새로운 아트를 만들고 네일 보관함에 저장할 수 있습니다.
- **AI 시안 자동 생성**: Stable Diffusion을 활용하여 무드, 색상, 패턴 등 키워드에 최적화된 네일 디자인을 직접 생성합니다.

<p align="middle">
  <img width="100%" alt="AI 생성 기능" src="https://github.com/user-attachments/assets/f9c5553c-daff-4441-ac7b-295654748ec7" />
</p>
<p align="middle">
  <img width="100%" alt="AR 체험 UI" src="https://github.com/user-attachments/assets/56e62bca-20de-4db8-a5d6-37e8605003e2" />
</p>
<p align="middle">
  <img width="100%" alt="퍼스널네일 측정 1" src="https://github.com/user-attachments/assets/bcff2787-596a-4ba5-97ec-c7b2f0a69bcb" />
</p>
<p align="middle">
  <img width="100%" alt="퍼스널네일 측정 2" src="https://github.com/user-attachments/assets/f9d8e233-fc4e-43bf-ac79-708adf91e505" />
</p>

<br/>

## 🔨 프로젝트 구조
- **비동기 로직 서버**: Spring WebFlux를 기반으로 리소스 활용을 최적화하고 응답성을 높였습니다.
- **무중단 운영**: Kubernetes와 Terraform(IaC)을 활용하여 자동화된 인프라 관리 환경을 구축했습니다.
- **AI 파이프라인**: SOTA Segmentation 및 Detection 모델을 통해 사용자 손톱 영역과 관절 정보를 인식합니다.

<p align="middle">
  <img width="100%" alt="프로젝트 아키텍처" src="https://github.com/user-attachments/assets/020b5a1b-e995-4336-8e5b-bb728d6b6808" />
</p>

<br/>

## 🔧 Stack
- **Frontend**: JavaScript, TypeScript, React Native
- **Backend**: Java, Spring Boot, Spring WebFlux
- **AI**: Stable Diffusion, Hand Landmark Detection, Segmentation Models
- **Infrastructure**: Kubernetes, Terraform, AWS (IaC)
- **Design**: Figma

<br/>

## 💡 기대효과
- **탐색 시간 단축**: 기존 1시간 이상 걸리던 시안 탐색 시간을 약 **3.2분 이내**로 획기적으로 단축합니다.
- **선택의 불확실성 해소**: AR 체험을 통해 시술 전 자신에게 어울리는지 미리 확인하여 사용자 만족도를 높입니다.
- **개인화된 뷰티 경험**: 사용자 입력값 기반의 알고리즘을 통해 최적화된 개별 스타일을 추천합니다.

<br/>

## 👍 활용분야
- **네일 마케팅**: 퍼스널컬러 및 손 유형별 추천 콘텐츠를 통해 신규 타겟 유입을 유도합니다.
- **현업 연계**: 실제 네일샵 사장님들의 피드백을 반영하여 수요에 맞춘 콘텐츠 기획 및 홍보 전략으로 활용합니다.

<br/>

## 🙋‍♂️ Developer

| 분야 | 이름 |
| :--- | :--- |
| **Designer** | 유원희, 함윤정 |
| **Marketer** | 오세연 |
| **FE Developer** | 이우창 |
| **Admin** | 정원제, 김우연 |
| **BE Developer** | 성원호, 이은학 |
| **AI Researcher** | 박주환 |
