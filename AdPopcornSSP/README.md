# AdPopcorn SSP SDK
  # 1. Android ChangeLog
  - 3.3.2a
    * SDK 미디에이션 초기화 관련 로직 변경
      
  - 3.3.1a
    * ReactNative 네이티브 크기 조절 지원
    * 하이브리드 내 WebData 스크립트 대응
    * 전면, 비디오 Activity onConfigurationChanged 이벤트 관련 처리 추가
    * 중복 load 요청에 대한 로직 개선
      
  - 3.3.0a
    * 스플래시 광고 타입 추가
    * ReactNative 네이티브 광고 지원
  
  - 3.2.9a
    * NAM 최신 버전 호환 대응
      
  - 3.2.8a
    * NAM 이미지 배너 활용한 전면 광고 연동
    * 전면비디오, 리워드 비디오 활용 시, timeout index 오류 수정
    * 전면, 비디오 showAd 호출 시, main thread 여부 체크.
    * KT 라이브러리 체크 로직 변경
      
  - 3.2.7a
    * 배너-네이티브 템플리 사용 시, 임프레션 100프로 이슈 수정
      
  - 3.2.6a
    * 배너-네이티브 가로 길이 오처리 수정
      
  - 3.2.5a
    * AdaptiveSize Template 추가
    * NAM 6.1.1 대응
    * 비디오 광고 닫기 버튼 영역 조정 및 이미지 교체
    * 하이브리드 스크립트 오류 수정
    * 네이티브 템플릿 적용 시, 가로 크기에 따른 영역 조정 처리
    
  - 3.2.4a
    * AdaptiveSize Template 추가
    * NAM 네이티브 광고 내 외부 DSP 지원
    
  - 3.2.3a
    * 하이브리드 웹뷰 script 오류 수정
    * 배너-네이티브 타이틀, desc 광고 영역 오류 수정
    * Bitmap out of memory 이슈 수정 
    
  - 3.2.2a
    * AppLovin Timeout 이슈 대응
    
  - 3.2.1a
    * 배너-네이티브 신규 사이즈 템플릿 
    
  - 3.2.0a
    * 하이브리드 앱 배너, 네이티브 스크립트 연동 대응
    
  - 3.1.8a
    * AppLovin Max Custom Adatper 관련 로그 추가
    
  - 3.1.7a
    * AppLovin Max Custom Adapter 추가
    * NAM 네이티브 로드 실패 시, 이벤트 전달 오류 수정
    
  - 3.1.6a
    * NAM 전용 신규 배너 사이즈 추가
    
  - 3.1.5a
    * GAM 네이티브 미디에이션 로드 중복 이슈 수정
    
  - 3.1.4a
    * 네이티브 이미지 다운로드 방식 개선
    
  - 3.1.3a
    * Naver Ad Manager 미디에이션 추가
    * TapJoy 인앱 비딩 지원
    
  - 3.1.2a
    * adfit, coupang 최소 지원 버전 체크 로직 추가
    * pangle 최신 버전 호환성 대응(3.6.0.9)
    * 배너-네이티브, 전면-네이티브 지원
    
  - 3.1.1a
    * 벙글 인앱 비딩 리포팅 오류 수정
    
  - 3.1.0a
    * 미디에이션 + 인앱 비딩 Mix 지면 오류 수정
    
  - 3.0.20a
    * 벙글 인앱 비딩 오류 수정
    
  - 3.0.19a
    * pangle 미디에이션 연동 키 오류 수정
    
  - 3.0.18a
    * Adfit BizBoard 연동 추가
    * Vungle 인앱 비딩 추가
    * Cauly 배너 사이즈(320x100, 300x250) 추가
    * Coupang 배너, 전면 신규 연동
    
  - 3.0.17a
    * Appier 웹뷰 랜딩 로직 추가
    * 컴패니언 템플릿 변경 및 추가
    
  - 3.0.16a
    * 컴패니언 광고 추가
    * 메조미디어 배너 타입 지원 사이즈 추가
    
  - 3.0.15a
    * 앱러빈 RV 완료 이벤트 시점 변경
    * AdColony 4.7.1, Vungle 6.10.5 호환성 검증
    
  - 3.0.14a
    * 앱러빈 Max 제거
    
  - 3.0.13a
    * UnityAds 4.1.0 호환성 검증   
    
  - 3.0.11a
    * Mute 기능 추가
    * 비디오 resume 로직 변경
   
  - 3.0.10a
    * 미디에이션 광고 연동 추가(벙글, 앱러빈)
    * 전면 광고 close event delay 이슈 대응
    * 유니티 네이비트 광고 타입 지원
   
  - 3.0.8a
    * Android 12 ADID 권한 옵션 추가 
    * GAM Ui Thread 이슈 대응
    * DeepLink 처리 로직 추가
    * 
  - v3.0.7a
    * UnityAds 미디에이션 콜백 이벤트 처리 로직 변경
    
  - v3.0.6a
    * GAM 미디에이션 일부 class 변경
    * mopub custom network report 기능 변경

  # 2. iOS ChangeLog 
  - 2.5.6
    * 전면 광고 백그라운드 색상 변경 옵션 추가
      
  - 2.5.5
    * ReactNative 네이티브 크기 조절 지원
    * 하이브리드 내 WebData 스크립트 대응
    * 중복 load 요청에 대한 로직 개선

  - 2.5.4
    * 리액트 네이티브 플러그인용 네이티브 지원
    * 스플래시 지원
    * ADOP 지원
    * 웹뷰 내 스크립트 새창 띄우기 오류 수정
    * 네이티브 내, 애드팝콘 SSP 광고일 경우에만 imp 체크 타이머 동작하도록 수정
      
  - 2.5.3
    * 커스텀 광고 내 네이티브 지원 템플릿 정보 오류 수정

  - 2.5.2
    * 커스텀 광고 내 지원 템플릿 정보 추가
    
  - 2.5.1
    * 배너-네이티브 타입내, LoadSuccess 이벤트 발생 안하는 이슈 수정

  - 2.5.0
    * 배너-네이티브 신규 템플릿 타입(23, 24) 추가
    * 앱러빈 다이나믹 비드 지원

  - 2.4.9
    * xcframework 내 미사용 framework 제거(Adservice)
    
  - 2.4.8 
    * 비디오 광고 닫기 버튼 터치 오동작 개선
    * xcframework 전환
      
  - 2.4.7
    * 네이티브 메모리 오류 대응
    * 하이브리드 imp, click 오류 대응
    * 탭조이 인앱 비딩 추가
      
  - 2.4.6
    * 배너-네이티브, 전면-네이티브, 네이티브 템플릿 기능 지원
    * 리워드/전면 비디오 비주기 크래시 이슈 수정
    
  - 2.4.4
    * 배너 360x185 -> Adaptive Size로 변경
    * 하이브리드 앱 배너, 네이티브 스크립트 연동 
    
  - 2.4.3
    * 배너 360x185 사이즈 추가
    * VAST Video imp, click 수집 누락 이슈 대응
    
  - v2.4.2
    * vast player 기능 지원 
    * 전면 광고 close 이벤트 발생 오류 수정
    
  - v2.4.1
    * 네이티브 asset 중 privacy icon 관련 커스터마이징 기능 추가
    
  - v2.4.0
    * 미디에이션 호환성 업데이트(pangle, admob, google ad manager, adfit, applovin, fan, cauly)
    
  - v2.3.9
    * RV CS 컨트롤러 탑바 이슈 수정
  
  - v2.3.8
    * 전면 광고 정렬 이슈 수정
    
  - v2.3.7
    * 배너 광고 리프레시 동작 오류 수정
    
  - v2.3.6
    * 컴패니언 광고 타입 추가
    * 앱러빈 미디에이션 추가
    * 벙글 mute 옵션 추가
    
  - v2.3.4
    * FAN 전면, 전면 비디오, 리워드 비디오 인앱 비딩 적용
    * 전면 광고 최소 노출 시간 설정 옵션 추가
    
  - v2.3.3
    * GAM 미디에이션 업체 추가
    * Pangle, Admob 최신 버전 대응

  - v2.3.2
    * Pangle, FAN 전면 비디오 연동
    
  - v2.3.1
    * RV close 이벤트 발생 시, 비주기 크래시 이슈 수정
    
  - v2.3.0
    * Pangle RV 지원
    
  - v2.2.9
    * 네이티브 미디에이션 광고 요청 시, 스케쥴 오류 수정
    
  - v2.2.8
    * Xcode12(iOS14) 대응 및 최소 지원 버전 9.0으로 변경
