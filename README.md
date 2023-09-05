# iosdowntest

# manifest.plist : software-package 에 다운로드 파일 이름 수정

# xcode 버전업
- 프젝트 - 타겟 - Marketing Version 변경 : 1.0.0

# 아이폰 업그레이드
- 업데이터 버전 변경 : Project - TARGETS - Build Settings - Versioning - Marketing Version - 1.0.0 변경 
- Product - Archive 만들기 
  manifest.plist : 파일의 ipa 업데이터 파일 이름 확인
  ssgdx-mdm-dev.ipa  --> ssgdx-mdm-dev-1.0.0.ipa 이름 변경

  # 앱이름 변경 : Project - TARGETS - Build Settings - Info.plist values --> Bundle Display Name
  # 앱 아이콘 디자인 요청 ??? IOS, AOS 아이콘 크기 확인 


  ??? 바이오 인증 확인
  - 초기화 디바이스에서 테스트 : 메시지 확인 필요
  에러 코드 : 11 - 등록된 지문이 없습니다.  --> 지문 등록 유도
- 


: AOS - 보안 - 지문등록

# IOS 사내배포 시 참조 ㅎㅎㅎ
https://www.blueswt.com/176



# 기업 배포 인증서 생성하기 ('In-House and Ad Hoc' 로 생성)
https://developer.apple.com/kr/help/account/create-certificates/create-enterprise-distribution-certificates/


??? 이부분은 엔트프라이즈 계정 나요면 해보자 ( 되도록 손대지말고 진행 ㅎㅎㅎ)
// 애플 사이트 프로파일 생성 -- 이게 필요한가 확인 필요 ??? xcode에서 선택하여 진행함
// in house 를 만들어봄 -- 그리고 XCDOE 에서 프로파일 연결해서 테스트 ( 이게 필요한지 확인, 프로그램 별로 필요한지 확인 ???)
https://velog.io/@mingbee611/RN-iOS-App-Store-%EB%B0%B0%ED%8F%AC-%EC%A4%80%EB%B9%84-%EC%9E%91%EC%97%85%EA%B3%84%EC%A0%95-CSR-Provisioning-Profile-Device-Identifiers-%EB%93%B1
https://es1015.tistory.com/318


https://learn.microsoft.com/ko-kr/dotnet/maui/ios/deployment/publish-in-house?tabs=vs

이 부분이 필요한가 ? Register a New Provisioning Profile 생성 : inHouse


