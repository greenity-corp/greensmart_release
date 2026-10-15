# GreenSmart 공개 안내

GreenSmart는 Cloud·Edge·Controller가 함께 동작하는 플랫폼입니다. 이 저장소는 구성요소별 공개 안내와 승인된 릴리즈를 찾아가는 입구입니다.

## 구성요소와 공개 채널

| 구성요소 | 역할 | 안내 | 릴리즈 목록 |
| --- | --- | --- | --- |
| Cloud | 중앙 관리·데이터 연계 | [Cloud 안내](https://github.com/greenity-corp/green_smart-cloud-releases) | [Cloud Releases](https://github.com/greenity-corp/green_smart-cloud-releases/releases) |
| Edge | 현장 서비스·로컬 제어 | [Edge 안내](https://github.com/greenity-corp/green_smart-edge-releases) | [Edge Releases](https://github.com/greenity-corp/green_smart-edge-releases/releases) |
| Controller | 현장 장치 연결·제어 실행 | [Controller 안내](https://github.com/greenity-corp/green_smart-controller-releases) | [Controller Releases](https://github.com/greenity-corp/green_smart-controller-releases/releases) |

2026-10-15 기준, 위 GitHub 채널에 게시된 Releases는 각각 0개입니다. 이는 이 채널의 게시 현황이며, Cloud 운영 여부나 기존 설치본의 사용 여부를 뜻하지 않습니다. 검증한 공개 버전 조합과 설치 파일은 아직 이 안내에 게시하지 않았습니다.

## 설치·업데이트 안내

기존 고객의 설치 파일 전달 경로는 Cloud의 **설치 및 업데이트** 메뉴를 따릅니다. 이 공개 안내를 추가하는 것으로 고객 다운로드 권한이나 설치·업데이트 절차가 변경되지는 않습니다. 새 설치와 업데이트는 해당 배포의 승인된 안내 및 운영 담당자 확인을 거쳐 진행하세요.

공개 릴리즈를 게시할 때 구성요소별 페이지에서 다음을 확인할 수 있도록 안내합니다.

- 실제 검증한 Cloud·Edge·Controller 버전 조합과 알려진 제한
- 설치 대상과 사전 조건, 적용 순서, 업데이트 중단·복구 절차
- 해당 산출물의 식별자·체크섬·서명 검증 방법과 공개 변경 내역

아직 게시하지 않은 버전이나 조합은 지원한다고 판단하지 마세요. 같은 변경의 개발 시험 성공만으로 기존 설치본과의 호환성이나 실제 장치 출고 검증을 대신하지 않습니다.

## 공개 범위와 출고 기준

이 홈에는 전체 제품 ZIP이나 통합 릴리즈를 게시하지 않습니다. 각 구성요소 채널에 승인된 고객용 안내와 해당 구성요소 산출물만 게시하고, 서로의 버전과 링크로 호환 관계를 연결합니다. 소스 코드·상세 내부 설계·운영 설정·인증정보·고객 데이터는 이 공개 안내의 게시 대상에서 제외합니다.

공개 출고 전에는 구성요소 시험, 앱 간 호환성·회귀 시험, 필요한 실제 장치 설치·업데이트·복구 시험과 공개 내용 검토를 완료하고 출고 승인을 받습니다. 고객 화면에 새 기능이 추가되면 관련 브라우저 E2E 시나리오도 함께 갱신해 검증합니다. 미실행·생략 항목은 통과로 표시하지 않습니다.
