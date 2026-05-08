---
name: Remain
description: A Korean life-archiving service for someone who will remember me. Built on the Eastern philosophy of 會者定離·去者必返 — those who meet must part, and those who part shall meet again. The interface is a quiet vessel for memory, rendered in warm paper tones and sepia browns rather than the cold blacks of typical modern UI. The whole product should feel like opening an old keepsake box, not opening an app.

colors:
  warm-cream: "#FAF6F0"     # primary background — paper warmth, not white
  warm-beige: "#F0E8D8"     # surface — capsule cards, secondary blocks
  warm-sand: "#E0CDB0"      # avatars, decorative rings, soft fills
  warm-brown: "#8B6F47"     # primary CTA, brand brown, key actions
  deep-brown: "#4A3520"     # headings — warm dark, never pure black
  text-main: "#3A2E22"      # body text — warm dark brown
  text-sub: "#7A6655"       # secondary text, navigation, metadata
  text-light: "#A89080"     # captions, timestamps, labels
  muted-gold: "#C8A96E"     # slogans, hanja accents, time markers — used sparingly
  soft-rose: "#D4A89A"      # private content accent — gentle dusty pink
  dusty-rose: "#B07A70"     # secondary rose accent
  border-soft: "#E0D0B8"    # card borders, dividers
  shadow-warm: "rgba(139,111,71,0.12)"  # all shadows are warm-toned, never neutral gray
  private-bg: "#F5EFE8"     # private/locked content backgrounds — slightly warmer surface

typography:
  display:
    fontFamily: "Noto Serif KR, serif"
    fontSize: "3rem"
    fontWeight: 600
    lineHeight: 1.2
  hero-name:
    fontFamily: "Noto Serif KR, serif"
    fontSize: "2.6rem"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  h1:
    fontFamily: "Noto Serif KR, serif"
    fontSize: "2rem"
    fontWeight: 600
    lineHeight: 1.3
  h2:
    fontFamily: "Noto Serif KR, serif"
    fontSize: "1.5rem"
    fontWeight: 600
    lineHeight: 1.4
  h3:
    fontFamily: "Noto Serif KR, serif"
    fontSize: "1.3rem"
    fontWeight: 600
    lineHeight: 1.45
  body-lg:
    fontFamily: "Noto Sans KR, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.8
  body-md:
    fontFamily: "Noto Sans KR, sans-serif"
    fontSize: "0.95rem"
    fontWeight: 400
    lineHeight: 1.8
  body-sm:
    fontFamily: "Noto Sans KR, sans-serif"
    fontSize: "0.85rem"
    fontWeight: 400
    lineHeight: 1.7
  caption:
    fontFamily: "Noto Sans KR, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 400
    letterSpacing: "0.06em"
  hanja-slogan:
    fontFamily: "Noto Serif KR, serif"
    fontSize: "0.85rem"
    fontWeight: 500
    letterSpacing: "0.12em"

spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 80px
  section: 120px

rounded:
  sm: 4px
  md: 8px
  lg: 12px
  xl: 16px
  pill: 20px
  pill-lg: 24px
  pill-xl: 30px
  full: 9999px

shadows:
  sm: "0 2px 8px rgba(139,111,71,0.12)"
  md: "0 2px 16px rgba(139,111,71,0.12)"
  lg: "0 8px 32px rgba(139,111,71,0.12)"
  dramatic: "0 20px 60px rgba(74,53,32,0.28)"
  ring-gold: "0 0 0 2px #C8A96E"
  ring-rose: "0 0 0 2px #D4A89A"

components:
  card-capsule:
    background: "warm-beige"
    border: "1px solid border-soft"
    borderRadius: "xl"
    shadow: "md"
    padding: "xl"
  
  button-primary:
    background: "warm-brown"
    color: "warm-cream"
    borderRadius: "full"
    padding: "md lg"
    transition: "all 0.3s ease"
---

## Overview

Remain은 **"나를 기억할 누군가를 위해"** 라는 슬로건의 라이프 아카이빙 서비스다. 사용자는 자신의 시간을 타임라인·이야기·회고록·하루 한 줄·타임캡슐·방명록의 형태로 남기고, 종래에는 인쇄된 회고록으로 이어진다.

브런치가 독자를 위한 퍼블리싱이라면, Remain은 **나와 나를 사랑하는 사람을 위한 기록**이다. 그래서 톤은 콘텐츠 플랫폼이 아니라 **오래된 보석함을 여는 감각**이다.

비주얼 무드는 **한지 위에 세피아 잉크로 쓴 글, 그 위에 시간의 금빛이 스민 듯**한 정서를 따른다. 모든 텍스트는 차가운 검정이 아니라 따뜻한 짙은 갈색으로 처리해 종이 질감과 통일된 톤을 유지한다. 화려하지 않고, 차갑지 않다. 잡지보다 일기에 가깝고, 일기보다 편지에 가깝다.

## Colors

팔레트는 **종이 톤의 따뜻한 뉴트럴**이 절대 다수를 차지하고, 강조색은 **머티드 골드**와 **소프트 로즈** 두 가지뿐이다.

- **`warm-cream` (#FAF6F0)** — 기본 배경. 흰색이 아닌 한지 톤의 아이보리. 모든 페이지의 베이스.
- **`warm-beige` (#F0E8D8)** — 카드, 타임캡슐 타일. `warm-cream`보다 한 톤 깊게.
- **`warm-sand` (#E0CDB0)** — 아바타 배경, 데코레이티브 링.
- **`warm-brown` (#8B6F47)** — 프라이머리 CTA, 브랜드 브라운. "기록하기", "저장하기" 같은 핵심 액션.
- **`deep-brown` (#4A3520)** — 헤딩 전용. 순수한 검정이 아니라 **세월이 묻은 책표지의 색**.
- **`text-main` (#3A2E22)** — 본문 텍스트. 따뜻한 짙은 갈색. **절대 #000이나 #1A1A1A 같은 차가운 검정으로 대체하지 않는다**. 이것이 Remain 톤의 핵심.
- **`text-sub` (#7A6655)** — 보조 텍스트, 네비게이션, 메타데이터.
- **`text-light` (#A89080)** — 캡션, 타임스탬프, 라벨.
- **`muted-gold` (#C8A96E)** — 매우 절제. 한자 슬로건(會者定離), 통계 숫자, 시간이 깃든 강조에만. **한 화면에 3곳 이상 등장하지 않는다**.
- **`soft-rose` (#D4A89A)** — 비공개 콘텐츠의 액센트. 자물쇠 인디케이터, 프라이빗 카드 보더.
- **`dusty-rose` (#B07A70)** — 좀 더 진한 로즈 액센트. 선택 사용.
- **`border-soft` (#E0D0B8)** — 카드 보더, 디바이더.
- **`shadow-warm`** — 모든 그림자는 **따뜻한 톤**. `rgba(0,0,0,0.x)` 같은 중성 검정 그림자는 절대 사용 금지.

## Typography

- **헤딩·이름·슬로건은 Noto Serif KR (명조)** — 회고록의 무게를 전달.
- **본문·UI·메타데이터는 Noto Sans KR** — 가독성과 현대성.
- **본문 행간은 1.8** — 한국어 본문은 행간을 넉넉히. 1.5 이하로 좁히지 않는다.
- **한자 슬로건(會者定離 등)은 명조 + muted-gold + letter-spacing 0.12em** — 도장 찍힌 듯한 무게.
- 폰트 굵기는 400(본문), 500(슬로건/라벨), 600(헤딩) 세 단계.

## Spacing

8px 그리드 기반. 글이 주인공이므로 **여백을 인색하게 쓰지 않는다**.

- 카드 내부 패딩: `lg`(24px) 이상
- 섹션 간 간격: `section`(120px) — 모바일에서도 `2xl`(48px) 이하로 좁히지 않는다
- 본문 좌우 여백: `xl`(32px) 이상, 본문 최대폭은 약 720px

여백은 비어 있는 게 아니라 **숨 쉬는 공간**이다.

## Rounded

- 카드: `lg`(12px) 또는 `xl`(16px)
- 버튼: `md`(8px) 또는 `pill`(20px)
- 프라이머리 CTA: `pill-lg`(24px)
- 뱃지·캡슐 태그: `pill-xl`(30px)
- 아바타·인디케이터 점: `full`

너무 각진(0~4px)·너무 둥근(50%+) 디자인은 회고록 정서와 맞지 않는다. **중간 정도의 둥글기**가 핵심.

## Shadows

그림자는 **거의 보이지 않을 정도로** 미세하게. `sm`과 `md`를 주로 쓰고, `dramatic`은 모달과 인쇄 미리보기 같은 강조 상황에만. 모든 그림자는 따뜻한 갈색 톤(`rgba(139,111,71,...)` 또는 `rgba(74,53,32,...)`).

## Voice & Tone

- **한국어 우선.** 모든 UI 라벨, 네비게이션, 헤딩, 본문은 한국어로. 영문은 섹션 부가 라벨("Timeline", "My Story") 또는 국제 인용에만 허용.
- **재촉하지 않는다.** "오늘도 쓰셔야 합니다" 대신 "오늘은 어떤 문장이 남으셨나요". 청유형 권유.
- **편지 톤.** 마케팅 워딩 대신 편지 같은 워딩. 마침표를 아끼고, 느낌표는 거의 쓰지 않는다.
- **한자 슬로건 활용.** 會者定離(회자정리), 去者必返(거자필반), 殘香(잔향) 같은 한자 표현을 절제해서. 한자 자체가 시각 언어.
- **계절감.** 벚꽃, 매미, 단풍, 첫눈 같은 계절 신호를 카피와 이미지에 활용.

## Imagery

- 사진은 **세피아·필름톤**으로 통일. 채도 낮고 노출은 약간 따뜻하게.
- **사물·풍경·정물 우선.** 인물 클로즈업은 사용자가 직접 올린 것에 한정.
- 모든 이미지는 `border-soft` 1px 라인 또는 `lg`(12px) rounded 적용.
- 일러스트는 **선화 + 한지 텍스처** 정도로 절제. 컬러풀한 스폿 일러스트는 지양.

## Persona Diversity

이 서비스 사용자 페르소나를 **단일 인물에 종속시키지 않는다**.

- 다양한 연령대(20대~70대)의 기록을 함께 보여준다.
- 성별, 가족 구성(독신, 부부, 부모, 손자녀)을 다양하게.
- 직업·취미는 사진가뿐 아니라 교사, 농부, 회사원, 학생 등.
- 어떤 한 사람의 생애가 아닌 **여러 사람의 시간이 모인 아카이브** 같은 인상.

## Components

### Navigation (Top Bar)
- `position: fixed`, height 60px
- 배경 `rgba(250,246,240,0.92)` + `backdrop-filter: blur(12px)`
- 하단에 `border-soft` 1px
- 로고는 명조 + `letter-spacing: 0.08em`, 한 글자만 muted-gold로 강조
- 메뉴 링크는 작게(`0.85rem`), `text-sub` 색, hover 시 warm-brown
- 로그인 버튼은 `pill`(20px), warm-brown 배경

### Hero / Profile
- `min-height: 100vh`, 그라디언트 배경 `linear-gradient(160deg, #f7f0e4, #ede0cc, #e8d5bc)`
- 배경 중앙에 거대한 한자 워터마크(會者定離) — `18vw` 사이즈, opacity 0.04, 명조
- 아바타 180px 원형, warm-sand 배경, 흰 4px 보더, dashed 링 스핀 애니메이션
- 슬로건은 hanja-slogan 스타일
- 통계 숫자는 명조 1.5rem warm-brown
- 사쿠라 페탈 떨어지는 애니메이션 (배경 디테일)

### Timeline (시대별)
- 상단에 시대 필터 칩(전체/유년기/청소년기/청년기/장년기) — 활성 칩은 warm-brown 배경 + 흰 텍스트, 비활성은 투명 배경 + text-sub
- 카드 그리드 형태
- 각 카드: 이미지 상단(rounded `xl` 16px), 연도 + 시대 라벨 + 공개여부 뱃지, 제목(h3 명조), 본문 미리보기
- **잠긴 엔트리**: `private-bg` 배경, `soft-rose` 보더, 자물쇠 아이콘 + "비공개 기억" 텍스트만. 제목·본문은 가린다.
- "+ 새 기억 추가하기" CTA는 점선 보더 카드

### 나의 이야기 (Story Cards)
- 카테고리 라벨(CHILDHOOD·유년 / YOUTH·청년 / JOURNEY·여행 / CREATION·창작 / NOW·현재) — caption 스타일
- 이미지 + 카테고리 라벨 + 제목 + 본문 미리보기 + 하단 메타(연월 + 좋아요 ♥ N)
- 좋아요 아이콘은 muted-gold

### 회고록 (Memoir)
- 가운데 정렬 헤딩(h1 명조)
- "예시 회고록" 라벨이 붙은 샘플 + "새 회고록 쓰기" CTA
- 각 회고록 카드: 시기 라벨 → 제목(h3) → 짧은 디바이더(48px golden line) → 본문 → 하단 액션
- 본문은 quote 스타일에 가깝게 italic + 명조 가능

### 오늘 한 줄 (Daily)
- 큰 입력창 한 줄(`body-lg` 사이즈), 플레이스홀더는 text-light "오늘 하루를 한 줄로 남겨보세요"
- 우측 "기록하기" CTA(warm-brown, pill)
- 아래에 과거 한 줄들이 카드 리스트 — 날짜(caption + text-light) + 한 줄(body-md)
- 카드 사이 `lg`(24px), 카드 자체는 그림자 없이 `border-soft` 하단선만

### 타임캡슐 (Time Capsule)
- 카드 좌측 큰 이모지(📦 💌 💑 등) — 60-80px
- "Open · 2030년 1월 1일" 같은 오픈 일자가 caption + muted-gold
- 제목(h3) + 본문 미리보기 + 하단 "🔒 봉인 중" 상태
- 봉인 중 카드는 약간 어둡게, 오픈 가능 카드는 밝게
- "+ 새 타임캡슐 만들기" CTA

### 방명록 (Guestbook)
- 상단 입력 영역: 이모지 선택 + 메시지 입력 + 비공개 토글
- 방문자 카드: 이모지 → 이름 → 관계(text-sub) → 날짜 → 메시지 → ♥ 좋아요 수
- 비공개 메시지는 모자이크 + 자물쇠 아이콘

### Buttons
- **Primary** (`btn-primary`): warm-brown 배경, 흰 텍스트, `pill-lg`(24px), hover 시 deep-brown
- **Ghost** (`btn-ghost`): 투명 배경, warm-brown 텍스트, `border-soft` 1.5px 보더, hover 시 warm-brown 보더 + warm-beige 배경
- **Diary** (`diary-btn`): 투명 배경, 명조 폰트, `pill-lg`(24px), 아이콘 좌측 — "오늘 한 줄" 같은 시그니처 액션
- **Service** (`service-btn`): 아이콘 + 라벨/이름 두 줄 — 회고록 인쇄, 동영상 서비스 같은 보조 서비스

### Privacy Indicators
- 공개: warm-brown 점
- 친구공개: muted-gold 점
- 비공개: soft-rose 점 + 자물쇠
- 비공개 카드 전체에는 `private-bg` + `soft-rose` 보더

## Accessibility

- `text-main` (#3A2E22) on `warm-cream` (#FAF6F0): 약 11:1 — WCAG AAA 통과
- `warm-brown` (#8B6F47) on `warm-cream`: 약 4.7:1 — WCAG AA 통과
- `muted-gold` (#C8A96E) on `warm-cream`: 약 2.3:1 — **본문 사용 금지**, 장식·강조에만
- `text-sub` (#7A6655) on `warm-cream`: 약 5.6:1 — 보조 텍스트로 안전
- 모든 인터랙티브 요소 최소 14px, 터치 타겟 44px 이상
- 본문 행간 1.8 유지

## Cultural Anchors

- 한자 표현(會者定離·去者必返·殘香 등)은 디자인의 정체성. 제거하거나 영문으로 대체 금지.
- 한국 계절감(벚꽃·매미·단풍·첫눈)을 카피와 이미지에 자연스럽게 녹인다.
- 한국 지명(서울 마포구·제주·교토·홍대)을 활용해 구체적 공간 기억.

## Don'ts

- ❌ 차가운 검정 텍스트(#000, #1A1A1A) 사용 금지 — 항상 warm 갈색 톤
- ❌ 채도 높은 컬러(파랑·빨강·녹색) 사용 금지 — 액센트는 muted-gold와 soft-rose만
- ❌ 순수한 흰색 배경 금지 — 항상 warm-cream 또는 그 변형
- ❌ 신경질적인 그림자(검정 톤, 강한 대비) 금지 — 그림자는 항상 warm-shadow
- ❌ 영문 우선 라벨 금지 — 한국어가 우선
- ❌ 한자를 모두 한글로 풀어쓰기 금지 — 한자 자체가 시각 언어
