# ISC Controller
Flutter를 사용하여 진행 중인 ISC 컨트롤러 프로젝트입니다.

## 프로젝트 기획 배경

이 프로젝트는 코딩을 모르는 사람도 보다 쉽게 코딩할 수 있는 플랫폼을 제공하자는 아이디어에서 출발했습니다. 네이버 블로거이자 임베디드 개발자인 니나농 님의 제안으로 시작되었으며, 초기에는 IoT 시스템이나 방탈출 카페처럼 다양한 프로젝트별 기계를 등록하고, 포트에 연결하여 시나리오를 기획하고 제어하는 시스템을 목표로 합니다.

## 사용 기술 스택

### Flutter
Flutter를 선택한 이유는 다음과 같습니다:

- **높은 생산성**  
  프로젝트의 특성상 임베디드 개발자의 조언과 함께 제가 처음으로 풀스택 역할을 맡아야 했습니다. 생산성이 높은 프레임워크가 필요했고, Flutter는 이러한 요구를 충족시켰습니다. 현재는 Windows 프로그램만 지원하지만, 향후 모바일 채널도 지원할 계획이 있어 여러 플랫폼을 동시에 지원하기 용이한 Flutter를 선택했습니다.

- **빠르고 높은 퀄리티의 개발 가능**  
  상용 서비스를 개발하는 데 있어 전문적인 프론트엔드 개발자가 없어도 충분히 만족스러운 결과물을 낼 수 있는 점이 Flutter의 큰 장점으로 작용했습니다. 기존의 HTML+Spring 조합보다 더 적합하다는 의견이 많았습니다.

## 현재 진행 상황

### 프로젝트 관리
- [x] 프로젝트 등록
- [x] 프로젝트 초기화
- [x] 프로젝트 정보 수정
- [x] 장비 등록 및 수정에 따른 프로젝트 정보 갱신

### 장비 설정
- [x] 장비 등록
- [x] 프로젝트 등록 여부에 따른 에러 메시지 표시
- [x] 첫 장비 등록에 대한 안내 메시지
- [x] 장비 추가 및 삭제
- [x] 장비 저장
- [x] 장비 추가 중 다른 화면으로 이동 시 임시 저장
- [x] 기존 장비 정보와 변경 사항이 없을 경우 임시 저장 없이 화면 전환
- [x] 최대 장비 수 초과 시 즉시 에러 메시지 표시
- [x] 장비 주석 최대 길이 초과 시 자동 파싱 및 알림 메시지 표시

### 포트 설정
- [x] 프로젝트 미등록 또는 장비 미등록 시 에러 메시지 안내
- [x] 선택한 장비에 따라 다른 범위의 포트 채널 및 번호 옵션 설정
- [x] 동일한 포트 채널과 번호로 다른 장비 등록 시 사용자 선택에 따라 처리 (중복 에러 메시지, 가장 먼저 선택한 장비만 등록 등)

## 앞으로의 개발 계획

### 장비 설정
- [ ] 포트에서 사용 중인 장비 삭제 시 알림 메시지 표시 및 삭제 방지 기능 추가

### 포트 설정
- [ ] 기존 포트에서 처리한 에러 상황을 추가 포트에서도 적용
- [ ] 장비 등록과 유사한 포트 삭제 기능 구현
- [ ] 최대 100개의 포트 추가 기능 구현

### 시나리오 코딩
- [ ] 시나리오를 기반으로 장비와 포트를 제어하는 로직 구현


  ![장비홈](https://github.com/user-attachments/assets/dc70c85f-75df-4766-a7ee-d07aca38515f)<br>
  ![포트 설정 홈](https://github.com/user-attachments/assets/8837d3aa-a359-4de1-b949-e576886d60dc)

