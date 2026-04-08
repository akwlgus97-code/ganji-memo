# ganji-memo
60-day Ganji memo web app

# 간지 메모 (Ganji Memo)

## 📌 서비스 소개
간단한 메모를 저장하고 관리하는 웹/앱 서비스

## 🎯 기획 의도
- 빠르게 메모 작성
- 직관적인 UI
- 최소한의 기능으로 생산성 강화

## 📂 폴더 구조
Ganji/
├── MyApp.swift          # 앱 진입점 (@main)
└── ContentView.swift    # 전체 UI 및 로직
    ├── GanjiConverter       # 간지 변환 유틸리티
    ├── GanjiEvent           # 데이터 모델 (Codable)
    ├── GanjiDiaryViewModel  # 상태 관리 + 저장/불러오기
    ├── CalendarTabView      # 그래픽 캘린더 탭
    ├── GanjiDayFeedView     # 간지일 누적 피드 탭
    ├── EventDetailView      # 상세 화면
    └── MemoAddView          # 추가/수정 통합 폼

## 🚀 실행 방법
[Swift Playgrounds]

1. 새 앱 프로젝트 생성
2. MyApp.swift, ContentView.swift 내용 교체
3. 실행

[Xcode]

1. 새 프로젝트 생성 (iOS → App → SwiftUI)
2. Storage: None, Testing: None 선택
3. MyApp.swift, ContentView.swift 내용 교체
4. iPhone 연결 후 Run
