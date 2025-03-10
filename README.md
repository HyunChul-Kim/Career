# Career
# 김현철
안녕하세요, 사용자 입장에서 생각하고 안정성과 완성도 높은 앱을 만들기 위해 노력하는 안드로이드 개발자 김현철입니다.
UI/UX 개선을 위해 기획,디자이너와 자주 소통하고 비지니스 로직 해결을 위해 서버, iOS 개발자들과도 소통하여 문제 해결을 위해 노력합니다.
- [링크드인](https://www.linkedin.com/in/%ED%98%84%EC%B2%A0-%EA%B9%80-05a540262/)

![kotlin](https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white)![java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)![androidstudio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)![android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)![git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

# 경력
## 🚀차후
> OpenLayers를 이용한 건축 도면 관리 서비스 제공

> 시스템개발팀/선임연구원

> 2024.09 - 재직중

✅ **코드 리팩토링을 통한 유지보수성 개선**
 - 기존 Java 기반 프로젝트를 Kotlin으로 전환, MVVM 패턴 및 Clean Architecture 적용
 - Repository Pattern과 ViewModel을 활용하여 비즈니스 로직과 UI 분리
 - 기존 API 호출 방식 개선 → Coroutine & Flow 적용하여 비동기 처리 최적화

✅ 오프라인 모드 구현
 - 서버 데이터를 Room DB에 저장하여 오프라인 환경에서도 사용 가능하도록 개선
 - Zip 파일 다운로드 및 해제 기능을 개발하여 건축 도면 이미지 및 데이터 관리

✅ 업로드 및 내부 로그 기능 개선
 - 파일 업로드 진행도 및 갯수 표시 기능 추가
 - 오프라인 환경에서도 이벤트 로그 저장 → 네트워크 연결 시 자동 업로드

✅ 미디어 선택기 및 카메라 구현
 - OS에서 제공하는 Photo Picker와 CameraX를 이용하여 커스텀 선택기 및 카메라 구현
 - 동영상 촬영 및 선택, 다중 선택 기능 등으로 사용자 편의성 증대

## 🚀컬쳐히어로
> 우리의 식탁이라는 음식 레시피 및 커머스 서비스 제공

> 앱개발셀/스탭

> 2022.04 - 2024.04

<img src="https://github.com/HyunChul-Kim/Career/blob/main/images/wtable/wtable_image1.jpg" width="100" height="200"/><img src="https://github.com/HyunChul-Kim/Career/blob/main/images/wtable/wtable_image2.jpg" width="100" height="200"/><img src="https://github.com/HyunChul-Kim/Career/blob/main/images/wtable/wtable_image3.jpg" width="100" height="200"/><img src="https://github.com/HyunChul-Kim/Career/blob/main/images/wtable/wtable_image4.jpg" width="100" height="200"/><img src="https://github.com/HyunChul-Kim/Career/blob/main/images/wtable/wtable_image5.jpg" width="100" height="200"/><img src="https://github.com/HyunChul-Kim/Career/blob/main/images/wtable/wtable_image6.jpg" width="100" height="200"/>

✅ 본인인증 화면 개발
 - 화면에서 입력된 인증정보를 WebView로 전달하여 인증
 - 본인인증 및 성인인증 기능을 통해 주류 상품 판매 기능 추가
✅ EventLogger 개발
 - Firebase Analytics, Branch, Braze, Amplitude를 사용하여 사용자 이벤트를 로깅하고 있었는데 필요한 위치에서 매번 중복되는 코드들을 작성하고 각 라이브러리마다 코드를 작성해서 코드가 길어지고 복잡해짐
 - 이를 개선하고자 EventLogger class를 만들어 단일 함수로 logging 할 수 있게 개발
 - 이후 기존 코드들이 간결하게 변경됐고 하나의 로직으로 여러 platform에 logging 할 수 있게되어 유지보수성 향상
✅ 검색 화면 리뉴얼
 - 검색어 입력 화면에서 추천검색어, 검색어 히스토리, 연관 검색어 등의 기능 개발
 - 검색 결과 화면 UI 변경 등의 리뉴얼
✅ 게시물 해시태그
 - 게시물 작성할 때 #입력 후 타이핑하면 연관 해시태그가 보여지고 입력 된 해시태그가 볼드로 표시되게 개발
 - 사용자에게 해시태그가 더 잘 보여지고 작성 할 때 연관 해시태그를 노출하여 편의성 제공
✅ Image Picker 개발
 - Custom Image Picker에 대한 기획쪽 니즈가 있어 앨범 리스트, 화면 상세 보기 등의 기능을 제공하는 ImagePicker 개발
✅ AI Recipe 개발
 - 검색어를 입력하면 서버쪽과 연결하여 해당 검색어를 이용한 레시피를 제공하는 기능 개발
 - xml tag 방식을 적용하여 서버에서 전달 되는 data에 tag정보를 포함시키고 이를 파싱하여 bold, color, size 등의 UI를 제공할 수 있게 개발
 - 로딩화면 애니메이션 개발
✅ JWT 인증 로직 개발
 - OkHttp Interceptor를 이용한 JWT 인증 로직 구현
 - Header Interceptor에 Access Token 정보 추가
✅ EventBus Flow 개발
 - Flow를 사용하여 다양한 Event를 방출하고 이를 구독하여 Event 처리할 수 있는 기능 개발
✅ Branch Quick Link 적용
✅ 채널톡 SDK 추가
 - 채널톡 SDK를 이용하여 문의 환경 개발
 - 채널톡 SDK 버그 이슈 제보하여 이슈 수정
✅ 레거시 코드 개선
 - deprecated ButterKnife 제거하고 ViewBinding으로 변경
 - Jcenter 사용중인 Library를 maven으로 전환

## 🚀Qoo10(큐텐테크놀로지)
> 글로벌 오픈마켓 서비스를 제공

> 모바일그룹/대리

> 2017.06 - 2022.04

<img src="https://github.com/HyunChul-Kim/Career/blob/24ca7354056d9ea65a2e5db5b9b8375430b30618/images/qoo10/qoo10_image1.jpeg" width="100" height="200"/><img src="https://github.com/HyunChul-Kim/Career/blob/24ca7354056d9ea65a2e5db5b9b8375430b30618/images/qoo10/qoo10_image2.jpeg" width="100" height="200"/><img src="https://github.com/HyunChul-Kim/Career/blob/24ca7354056d9ea65a2e5db5b9b8375430b30618/images/qoo10/qoo10_image3.jpeg" width="100" height="200"/><img src="https://github.com/HyunChul-Kim/Career/blob/24ca7354056d9ea65a2e5db5b9b8375430b30618/images/qoo10/qoo10_image4.jpeg" width="100" height="200"/><img src="https://github.com/HyunChul-Kim/Career/blob/24ca7354056d9ea65a2e5db5b9b8375430b30618/images/qoo10/qoo10_image5.jpeg" width="100" height="200"/><img src="https://github.com/HyunChul-Kim/Career/blob/24ca7354056d9ea65a2e5db5b9b8375430b30618/images/qoo10/qoo10_image6.jpeg" width="100" height="200"/><img src="https://github.com/HyunChul-Kim/Career/blob/24ca7354056d9ea65a2e5db5b9b8375430b30618/images/qoo10/qoo10_image7.jpeg" width="100" height="200"/>

✅ 상,하단 툴바 컨트롤러 개발
 - 사용자가 더 넓은 정보를 볼 수 있도록 스크롤 화면 및 WebView에서 상,하단 툴바 show, hide 기능 개발
✅ 생체 인증을 이용한 사용자 정보 저장
 - FingerPrintManager를 이용한 생체 인증 컨트롤러 개발
 - 이를 사용하여 사용자 정보를 암복호화
✅ Kotlin 전환
✅ Localization
✅ Expandable RecyclerView Adapter
 - 데이터 타입에 상관없이 열리고 접히는 UI 기능을 제공하여 생산성 향상
✅ MVC, MVP, MVVM 환경에서 개발
 - 오래된 프로젝트라 MVC, MVP가 혼용되고 있어서 해당 환경에서 개발
 - 신규 작업에서는 MVVM 패턴 적용
✅ WebView를 통한 하이브리드 앱 개발
✅ 동영상 컨트롤러
 - 일반 영상, 유튜브 영상에 따라 ExoPlayer, YoutubePlayer로 재생하는 Player 개발
 - 리스트 화면에서 특정 위치에 있는 아이템이 동영상일 경우 해당 영상 재생하는 컨트롤러 개발
✅ RxJava를 이용한 API 호출 개선
✅ Git Branch 전략을 이용한 버전관리
