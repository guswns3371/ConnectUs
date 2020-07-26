# 재난 극복을 위한 소상공인 기부 및 소비 촉진 플랫폼

### AdobeXD Link: https://xd.adobe.com/view/6432b457-48a0-4cff-ba17-ef24a8c24c92-3161/
격자보기 누르시면  한눈에 볼 수 있습니다
꼭 필요할 것 같은 페이지만 대략적으로 만들었습니다.

## 질문 리스트

1. react, redux를 사용할 때 갖추어야할 디렉토리 구조 및 사용법에 대해서 확실히 짚고 가고싶습니다. 하지만 어떤것을 참고해야할지 저희끼리 판단할 수 없어 질문 드립니다.
-  아마도 아래 사이트를 검색하셨을 것 같은데요. 2~3번째 링크를 참고해서 진행하는건 어떠세요? 
-  https://medium.com/better-programming/my-awesome-react-redux-structure-6044e5007e22
-  https://github.com/codica2/react-app-best-practice
-  https://dev.to/chrisachard/tips-for-organizing-react-projects-191

2. front 제작시 파트 분담을 어떤식으로 해야될 지 궁금합니다 (header, footer, body 이런식으로 나누는지, 페이지 별로 나누는지)
- 공통 적인 부분 header footer는 재사용하고 body 부분을 담당자 별로 구분하여 개발하는게 좋을 것 같습니다. 

3. 코드를 만들고 올릴때(프론트, 백 둘다) 각자 맡은 기능에 대한 레포지토리를 따로 만들어서 관리하는것과
    한 레포지토리에 각자 맡은 기능을 브랜치로 따서 관리하는것 중 어떤 방법이 더 나을지 질문드립니다.
- 프론트와 백은 별도 서버로 관리되는게 좋습니다. 즉 레파지토리를 따로 만들어서 관리하기가 용이합니다. 
- 하나에 리파지토리를 사용한다면 백에서 프론트를 빌드하고 백 디플로이 폴더에 저장되는 구조가 일반적이기 때문에 빌드/배포 시간도 오래 걸리고 유지관리 관점에서는 나누는게 좋을 것 같습니다. 

 
4. 네이버페이 관련 질문입니다. 네이버페이 클라이언트 ID를 받기 위해서 네이버페이센터 회원가입이 필요합니다. <br>
   (1) 개인 또는 법인사업자 등록증사본, (2) 통신판매업신고증 사본, (3) 통장사본, (4) 매매보호서비스 가입 증명서 등이 필요할 것으로 보입니다.(실제 서비스 등록 요구서류) <br>
   저희는 실제로 판매하는 서비스가 아닌 학습용으로 사용할 방법이 있는지 네이버페이 측 전화상담이 어려워 질문 드립니다.(그 외 상담도 회원가입 필요; 챗봇 및 FAQ에서 원하는 질문을 찾지 못했습니다.)
- 카카오 페이를 확인해봤는데요. 제휴 없이 카카오 페이 API는 모의(Mockup) 용도의 API로 테스트가 가능합니다. 카카오페이 API로 학습 및 연동해보시겠어요? 
- https://developers.kakao.com/docs/latest/ko/kakaopay/common