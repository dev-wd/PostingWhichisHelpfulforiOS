# iOS개발에 도움이 되는 포스팅 모음
더 좋은 앱을 만들어 가기 위한 스터디를 하는 도중 꾸준히 보는 글들을 박-제-합니다👩🏻‍💻
__`주니어 개발자의 학습목록`__

## Clean Arthitecture for iOS
### [iOS-Clean-Architecture-MVVM](https://github.com/kudoleh/iOS-Clean-Architecture-MVVM)
- MVVM Templete Repository
- Domain, Data, Presentation Layer에 대한 자세한 그림 및 프로젝트 제공
## RxSwift
### [Networking with RxSwift](https://www.netguru.com/codestories/networking-with-rxswift)
- Networking 할 때 RxSwift를 적용하는 방법
- ViewModel & ViewController에서만 RxSwift를 적용할 것인가? 
- Networking Layer러 부터 RxSwift를 적용하는 것이 더 좋은가? 에 대한 고민을 할 때! 참고!

### [힐페TV - ViewModel을 무조건 믿을 수 있는 방법이 있다???(삐슝빠슝)](https://blog.gangnamunni.com/post/HealingPaperTV-ViewModel-Test)
- 힐링페이퍼 블로그
- MVVM + RxSwift를 적용한 간단한 앱 구현
- Input, Output을 명확하게 명시하여 구분
- Data 최적화를 Transform 로직을 이용하여 구현
- Test Code 작성, RxNimple 활용
- VieModel뿐 아니라 Network Layer도 'Moya/RxSwift'를 활용항 개발함

## Test Code 
### [UnitTest for Xcode](https://velog.io/@wimes/UnitTest-for-Xcode)
- 한국어 리소스
- Unit Test에 대한 기본적인 설명이 국내 자료는 내용을 많이 생략하고 방법만 적은 것이 많은데, 인과적으로 근거를 두고 잘 설명하고 있음
- 
### [iOS Unit Testing and UI Testing Tutorial](https://www.raywenderlich.com/960290-ios-unit-testing-and-ui-testing-tutorial)
- Raywenderlich의 Unit Test 예제
- given, when, then의 순서를 지킴
- Fake Object 구현 (Mock, Stub)
- 퍼포먼스 테스트 구현
- 네트워크 테스트
- 장점: 프로젝트 단위로 어떻게 테스트 코드를 작성하는지 참고가 가능

### [Testing Your RxSwift Code](https://www.raywenderlich.com/7408-testing-your-rxswift-code)
- 프로젝트에서 RxTest, RxBlocking을 어떻게 적용하는지 학습
- 다양한 환경에서 RxTest, RxBlocking 중 어느것을 사용하는 것이 적합한지 학습
- 프로젝트 Test번들 처음 Add할 때 엉뚱하게 많이 해매는데 이를 말끔하게 해결해준 포스팅

## Managing enterprise-app
### [Enterprise 규모 앱 환경 구성 - 1](http://minsone.github.io/ios/mac/ios-enterprise-app-configuration-1)
### [Enterprise 규모 앱 환경 구성 - 2](http://minsone.github.io/ios/mac/ios-enterprise-app-configuration-2)
- 민소네님 포스팅
- 기업규모 앱의 Layer 나누기
- 라이브러리 의존성 제거, 불필요한 프로토콜 제거, 빌드 타임 감소

### [디버깅 시작해버깅](https://speakerdeck.com/gaeun/dibeoging-sijaghaebeoging)
- 가은님, Let us go 발표자료
- 빌드 타임이 오래 걸리느 프로젝트엣 불필요한 build를 줄이기 위한 디버깅
- LLDB와 친해지기

## Fastlane

## SwiftUI, and Combine
### [SwiftUI+MVVM](https://github.com/kitasuke/SwiftUI-MVVM)
- SwiftUI+Combine으로 MVVM 아키텍쳐 구성
- 일본분이 만드신 리포지토리, 스타가 350개 넘음
- UI 및 Unit Test 또한 작성되어 있다.

## Network 
### [Swift, Moya가 무엇인지, 어떻게 사용하는지 알아봅니다](https://devmjun.github.io/archive/Moya-Tutorial)
- Moya Library에 대한 이해
-  Alamofire와의 관계
-  사용방법 및 장점
