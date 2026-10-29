# DDing-Ho-Archive · Organization 문서

이 저장소는 Organization의 공개 소개와 저장소 분류 기준을 관리합니다. [profile/README.md](profile/README.md)는 [Organization 첫 화면](https://github.com/DDing-Ho-Archive)에 표시됩니다.

## 분류 체계

저장소의 프로젝트·교육 과정 분류는 Custom property **`collection`** 하나로 관리합니다.

| 값 | 대상 |
| --- | --- |
| `jungle-gtl03` | Krafton Jungle · Game Tech Lab 3기 주차별 원본 |
| `organization-meta` | Organization 소개·목차·관리 문서 |

새 프로젝트의 저장소를 들일 때 필요한 컬렉션 값을 추가합니다. 아직 저장소가 없는 분류를 목차에 미리 나열하지 않습니다.

기술은 **Topics**로 표시합니다. 예: `cpp`, `directx11`, `game-engine`, `rendering`, `asset-pipeline`. 실제 코드·문서에서 확인되는 기술만 붙입니다. 주차별 순서와 개인 기여는 [KraftonJungle_GameTechLab03](https://github.com/DDing-Ho/KraftonJungle_GameTechLab03)에서 관리합니다.

## 저장소 등록 기준

1. 저장소의 목적에 맞는 `collection` 값을 지정합니다. 새 컬렉션이 필요하면 Organization 설정의 Custom properties에서 선택지를 추가합니다.
2. 저장소 Description에 교육 과정·주차·목적을 한 줄로 적고, Topics에 핵심 기술을 추가합니다.
3. [Organization 목차](profile/README.md)에 분류별 링크를 추가하고, 관련 상세 목차가 있으면 함께 연결합니다.
4. 비공개 저장소의 접근 범위와 팀 공동 결과물·개인 기여 구분을 유지합니다.

저장소 이름과 공개 범위는 분류만을 위해 변경하지 않습니다. 읽기 전용 Archive 처리는 적용하지 않습니다.

## 분류로 검색하기

- [Organization의 Repositories](https://github.com/orgs/DDing-Ho-Archive/repositories)에서 `prop`를 입력하고 `collection`과 원하는 값을 선택합니다.
- [개인 저장소 대시보드](https://github.com/repos)에서는 `organization:DDing-Ho-Archive props.collection:jungle-gtl03`으로 검색할 수 있습니다.

설정 방법은 [Custom properties 공식 문서](https://docs.github.com/en/organizations/managing-organization-settings/managing-custom-properties-for-repositories-in-your-organization)와 [저장소 대시보드 공식 문서](https://docs.github.com/en/repositories/creating-and-managing-repositories/viewing-all-your-repositories)를 참고합니다.
