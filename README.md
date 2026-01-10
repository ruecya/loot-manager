# 전리품 분배 매니저 v5

## 핵심 규칙(요청 반영)
- 보스 1회(배치)에서 **레인별 1인 1개**
  - 고정템 레인: 사람당 최대 1개
  - 전리템 레인: 사람당 최대 1개
  - 같은 사람이 같은 배치에서 고정 1개 + 전리 1개는 가능

## 토큰
- 전리템 레인에서 **패스 시 토큰 +1 생성**
- 우선권(토큰 1개): 요청자 -1 / 원차례자 +1 (토큰 이동)

## 명단
- 최대 50명
- 대량 붙여넣기 지원
- 레인별 참여자 ON/OFF 분리
- **명단 순서 변경**: 드래그(↕) 또는 ▲/▼

## GitHub roster.txt
- repo에 `roster.txt` 업로드(한 줄에 한 명)
- 명단 탭에서 raw URL 또는 `roster.txt`로 불러오기

## 파일 구성
- index.html : 단일 파일 앱
- roster.txt : (템플릿) 한 줄에 한 명
- loot_items.txt : (템플릿) 한 줄에 하나(전리템 목록)


## 전리품 목록 가져오기(loot_items.txt)
- repo에 `loot_items.txt` 업로드(한 줄에 하나)
- 명단/목록 탭의 '전리템 목록 관리'에서 raw URL 또는 `loot_items.txt`로 불러오기


## URL 팁
- `github.com/<owner>/<repo>/blob/...` 형태로 넣어도 자동으로 raw 주소로 변환합니다.
- 실패하면 raw 주소를 직접 사용하세요: `https://raw.githubusercontent.com/<owner>/<repo>/<branch>/...`
