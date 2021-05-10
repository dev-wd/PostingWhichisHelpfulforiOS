# iOS개발에 도움이 되는 포스팅 모음
더 좋은 앱을 만들어 가기 위한 스터디를 하는 도중 국내외 꾸준히 보는 글들을 박-제-합니다👩🏻‍💻
__`주니어 개발자의 학습목록`__


## AutoLayout 
### [Self-Sizing Table View Cells](https://baked-corn.tistory.com/124)
- 이동건님 블로그
- Cell의 높이를 동적으로 지정하는 것에 대한 여러 방법과 차이점이 서술되어 있음

### [(iOS swift) 테이블뷰 - TableView](https://m.blog.naver.com/PostView.nhn?blogId=jdub7138&logNo=220958881556&proxyReferer=https:%2F%2Fwww.google.com%2F)
- 여러가지 상황에서의 테이블뷰를 이용하는 방법을 제시, 한국어 블로그
- 행 삽입, 행 삭제, 행 수정
- 제공해주는 함수로 행 이동하기
- 커스텀하여 행 이동 동작 구현하기

## Clean Arthitecture for iOS
### [iOS-Clean-Architecture-MVVM](https://github.com/kudoleh/iOS-Clean-Architecture-MVVM)
- MVVM Templete Repository
- Domain, Data, Presentation Layer에 대한 자세한 그림 및 프로젝트 제공

### [RxSwift+clean architecture - Tiendeo Tech](https://medium.com/tiendeo-tech/ios-rxswift-clean-architecture-d7e9eaa60ba)
- MVVM + RxSwift (including Domain Layer,  Data Layer)
- MVVM을 Presenter Layer ~ Data Layer를 RxSwift를 활용해 쓰는 예제를 잘 구성하였음

### [devxoul/Drrrible](https://github.com/devxoul/Drrrible)
- 전수열님의 ReactorKit을 활용한 예제 프로젝트
- ReactorKit을 이용한 Clean Architecture을 어떻게 가져가는 것이 좋은지 참고할 수 

### [Builder Pattern In Swift](https://medium.com/@m.delgiudice/builder-pattern-in-swift-ce87b40de597)
- 빌더패턴을 여러가지 방식으로 구현할 수 있지만, 함수형으로 구현할 수 있는 방법이 소개됩니다.
- 파라미터를 동일한 형식으로 직관적으로 가져갈 수 있다는 장점이 있습니다.


### [iOS Dev Course: Repository with Realm](https://medium.com/@vialyx/ios-dev-course-repository-with-realm-983f210c5408)
- Realm 및 Local Data Repository 생성방법 

## UICollectionView and Cells
### [Drag and Drop Tutorial for iOS](https://www.raywenderlich.com/3121851-drag-and-drop-tutorial-for-ios)
- Raywenderlich 예제
- UICollectionView Drag and Drop을 구현하는 예제
- 동일 CollectionView, 다른 CollectionView, 다른 앱 모두가 대응 가능하다.
- IndexPath를 기준으로 끊기 때문에 ViewModel 기준으로 가져가는 경우에 대해서 추가 고민이 필요하다.

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

### [RxAnimated — animated bindings](https://medium.com/flawless-app-stories/rxanimated-animated-bindings-c5daa7f7d591)
- RxCocoa 를 Extention으로 animation을 주는 방법
- RxAnimated 추가 

### [RxSwift and Animations in iOS](https://www.toptal.com/ios/rxswift-animations-ios)
- UIView.animate를 RxSwift에 넣지 않고 반응형으로 구현하는 방법 제시
- Observable을 Create하고 스트림 단계를 연결하여 붙여줌으로써 반응형으로 구현하는 것이 가능하다.
- 복잡하 Animation들의 통합이 필요할 때에 참고하기가 좋음

### [RxFlow Demo App](https://github.com/RxSwiftCommunity/RxFlow/blob/master/RxFlowDemo/RxFlowDemo/Flows/AppFlow.swift)
- RxFlow Demo App 
- 꽤 여러가지 화면을 구성하여서 다양한 상황에 대한 활용을 참고할 수 있다.
- 현재 Demo앱 보다 쉽고 디테일하게 참고할 수 있는 RxFlow 예제는 없다고 판단된다.

## Test Code 
### [UnitTest for Xcode](https://velog.io/@wimes/UnitTest-for-Xcode)
- 한국어 포스팅
- Unit Test에 대한 기본적인 설명이 국내 자료는 내용을 많이 생략하고 방법만 적은 것이 많은데, 인과적으로 근거를 두고 잘 설명하고 있음

### [iOS Unit Testing and UI Testing Tutorial](https://www.raywenderlich.com/960290-ios-unit-testing-and-ui-testing-tutorial)
- Raywenderlich의 Unit Test 예제
- given, when, then의 순서를 지킴
- Fake Object 구현 (Mock, Stub)
- 퍼포먼스 테스트 구현
- 네트워크 테스트
- 장점: 프로젝트 단위로 어떻게 테스트 코드를 작성하는지 참고가 가능

### [How to test deep links with UI Testing](https://masilotti.com/test-deep-links-with-ui-testing/)
- Deeplink 로직을 테스트하는 방법에 대해 기술
- Local Server와 사파리를 

### [Applying Unit Tests to MVVM with Swift](https://medium.com/flawless-app-stories/applying-unit-tests-to-mvvm-with-swift-ba5a79df8a18)
- Q. 단순히 테스트코드를 작성하는 문제를 넘어서서 어떤 범위까지 우선순위로 테스트를 작성할 것인가?
- Q. ViewModel을 테스트하려면 의존되어 있는 Service, Repository를 다 테스트해야하는가?
- Q. Mock, Stub을 우리 프로젝트에서는 어떤식으로 구성할까?
- 위 질문들에 대해서 하나의 좋은 예제가 되었다. 
- 프로젝트에 따라 유연하게 작성되어야 하는 것이 TestCode라 스터디하는데 있어 다양한 예제를 참고해야 한다.

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

### [Framework Part 1 : Static Framework와 Dynamic Framework](http://minsone.github.io/ios/mac/ios-framework-part-1-static-framework-dynamic-framework)
### [Framework Part 2 : 프로젝트, 서브 프로젝트, Dependencies, 그리고 Static, Dynamic Framework](http://minsone.github.io/ios/mac/ios-framework-part-2-project-subproject-dependencies)
### [Framework Part 3 : Storyboard, Xib, Color, Image를 리소스 프레임워크에서 관리](http://minsone.github.io/ios/mac/ios-managing-color-image-storyboard-xib-from-resources-framework)
- 민소네님 포스팅
- Framework를 활용하여 모듈화를 잘 하는 방법을 세세하게 설명한 포스팅
- Library Link, Dependency에 대한 이해를 위해 공부가 필요

### [디버깅 시작해버깅](https://speakerdeck.com/gaeun/dibeoging-sijaghaebeoging)
- 가은님, Let us go 발표자료
- 빌드 타임이 오래 걸리 프로젝트에서 불필요한 빌드를 줄이기 위한 디버깅
- LLDB와 친해지기

### [[Xcode][LLDB]Debugging With Xcode and LLDB](http://minsone.github.io/ios/mac/xcode-lldb-debugging-with-xcode-and-lldb)
- 민소네님 포스팅 
- 위 가은님의 발표자료가 기능에 따라 사용법을 발표를 했었다면, 민소네님은 LLDB 명령어를 중심으로 기술함
- 실제 예제를 통해서 서술이 되어 따라해볼 수 있음

### [iOS 서버별 자동배포 환경 구축 방법](https://magicmon.github.io/2019/01/07/iOS-Automated-Deployment-Environment/)
- Xcode + Jenkins 설정을 통해 각 서버별로 자동배포 가능하도록 구축하는 방법
- 코드 수정 없이 각 서버 및 조건 별로 배포가능 하도록 환경설정 하는 방법

### [Bazel로 LINE의 iOS 앱 빌드 속도를 2배 빠르게!](https://engineering.linecorp.com/ko/blog/improving-build-performance-line-ios-bazel/)
- 라인 기술블로그
- Bazel + XcodeGen을 활용한 빌드 속도 개선 및 라이브러리 의존성 이슈 개선

## Fastlane
### [Fastlane Docs](https://docs.fastlane.tools/getting-started/ios/setup/)
- Fastlane 공식문서

### [Fastlane. tutorial: Getting Started](https://devmjun.github.io/archive/Fastlane)
- 한국어 리소스
- 각각의 lane들의 역할과 이를 응용하여 활용하는 방법을 구체적으로 적어놓았음
- 이를 단순히 코드 하나로 실행하는 것을 넘어서서 다른 툴과 연동해서 사용하는 방법을 고민해야한다.

### [Implementing fastlane from nothing to App Store, Josh Holtz](https://www.youtube.com/watch?v=6Jz-Ywxki0U)
- 해외 유튜버, 처음하는 사람들이 순서대로 잘 따라할 수 있도록 단계별로 동영상으로 설명해줌
- 2020.04.27 내 생일에 올라온 영상..

## GitHub Action
### [Github Actions ) Archive and export](https://zeddios.tistory.com/1033)
- Zedd님 블로그
- Github Action에서 배포를 할 때에 빌드가 선행되어야 함.
- 빌드를 하기 위해서 Github Server에 개발자 인증서가 있어야하는데, 암호화에서 올리고 Action에 넣어주는 방법을 서술함


## SwiftUI, and Combine
### [SwiftUI+MVVM](https://github.com/kitasuke/SwiftUI-MVVM)
- SwiftUI+Combine으로 MVVM 아키텍쳐 구성
- 일본 분이 만드신 리포지토리, 스타가 350개 넘음
- UI 및 Unit Test 또한 작성되어 있다.

## Network 
### [Swift, Moya가 무엇인지, 어떻게 사용하는지 알아봅니다](https://devmjun.github.io/archive/Moya-Tutorial)
- Moya Library에 대한 이해
-  Alamofire와의 관계
-  사용방법 및 장점

### [Better networking with Moya + RxSwift](https://dev.to/mcontin/better-networking-with-moya-rxswift-1mlk)
- Moya+RxSwift Service Layer에서 개인적으로 깔끔하게 구성한 예제라고 생각함
- Network Error, Mapping Error Handling을 한 스트림 내에서 처리가 가능함
- JWT Token Refresh 또한 Retry로 원큐에 해결할 수 있을지 시도해보고 싶은 예제

## Memory Management
### [iOS 메모리 뜯어보기, 메모리 이슈 디버깅하기, 메모리 릭 찾기](https://seizze.github.io/2019/12/20/iOS-메모리-뜯어보기,-메모리-이슈-디버깅하기,-메모리-릭-찾기.html)
- 메모리 뜯어보는 몇가지 방법 소개, 채완님 블로그
- 설명이 디테일함, 해당 글의 레퍼런스를 참조해서 메모리 관리 전략을 짤 예정

### [Practical Dependency Inversion in Swift](https://medium.com/flawless-app-stories/practical-dependency-inversion-in-swift-1c1142161a8)
- 두 객체 사이의 강한 의존성 고리를 끊기 위해서 의존성을 역전하는 방식
- 레츠스위프트 뉴스레터 8호 소개 해외글
- 의존성 제거를 매니징하는 것에 대해 스탠다드가 없는데, 한가지 방법으로 공부하면 좋을것 같다는 생각

### [wkwebview message handler memory leak(쉽게 실수하는 WKWebView 메모리 누수 수정)](http://monibu1548.github.io/2019/11/17/wkwebview-memory-leak/)
- WKWebView 에서 메모리 누수가 발생하는 주요 원인과 해결책
- 꼭 WebView에서의 상황이 아니더라도 'add()' 함수가 strong 일 때에, 트램폴린 패턴을 활용하여 해결할 수 있다.

## Compilier
### [SIL Docs](https://github.com/apple/swift/blob/main/docs/SIL.rst#silgen)
- Swift Intermediate Language  GitHub Swift Documentation.


### [(번역) SIL(Swift Intermediate Language), 일단 시작해보기까지](https://woowabros.github.io/swift/2018/03/18/translation-SIL-for-the-moment-before-entry.html)
- 우아한형제들 기술 블로그
- Swift Lintermediate Language 에 대해서 대략적으로 알아볼 수 있는 포스팅

### [SIL(Swift Intermediate Language)을 통한 Swift debugging](https://woowabros.github.io/swift/2018/03/18/swift-debugging-with-SIL.html)
- 우아한형제들 기술 블로그
- Swift 간단한 코드들을 SIL로 빌드해보는 예제 

## Dependency
### [의존관계역전 (Dependency Inversion Principle) - bearkode](https://github.com/bearkode/SwiftOOP/issues/2)
- 의존성 관리의 필요 이유에 대해 한국어로 가장 잘 설명된 글
- 의존성 역전이 필요한 이유, 그리고 방법을 가장 잘 이해하게 된 계기가 된 글임.

## Opensource Developement
### [Library를 CocoaPods에 배포하는 방법](https://jinnify.tistory.com/61)
- 오픈소스 배포에 괸해 한국어로 간단하고 쉽게 설명해놓은 블로그.
- CocoaPod
