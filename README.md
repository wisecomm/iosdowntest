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



: AOS - 보안 - 지문등록
