# storytelling-loop · 스토리텔링 루프

> 이야기는 정보 글과 다르게 돈다. 기준점은 사실 목록이 아니라 로그라인 한 줄이다.

드라마·시나리오·극·웹드라마·숏폼·영상 시리즈 구성안·실화 각색을 **로그라인 중심**으로 개발하는 상위 스킬이다. 작법 지식과 단계표는 [jtydhr88/screenwriting-skills](https://github.com/jtydhr88/screenwriting-skills)의 `sw-workflow`를 그대로 쓰고, 이 스킬은 그 위에 **로그라인 대조 · 대항 리뷰 · 실화/공공 게이트 · 되돌리기 · 다른 스킬로 넘기기**를 얹는다. 짝이 되는 정보·설득 글 루프는 [writing-loop](https://github.com/goodmorninghope-khs/writing-loop)다.

```
⓪ 접수 → ① 로그라인 공방 → ② 뼈대 → ③ 인물 → ④ 장면·회차 설계 → ⑤ 초고 → ⑥ 점검 → ⑦ 판정 ─ 통과 → ⑧ 넘기기·기록
              ▲  (북극성)        ▲        ▲            ▲                ▲                │
              └──────────────────┴────────┴────────────┴────────────────┴──── 되돌리기 ──┘
              모든 단계 끝에서 "로그라인 대조": 이 단계의 결과가 그 한 줄을 지키는가?
```

## writing-loop와 다른 점

| | writing-loop | storytelling-loop |
|-|-|-|
| 기준점 | 근거 목록(원문 사실) | 로그라인(관객과의 한 줄 약속) |
| 단위 | 문단·절 | 비트·장면·회차 |
| 판정 | 문체 5축 점수 40/50 | 🔴🟠🟡 지뢰 + 작가 반박 + 단계 통과 기준 |
| 윤문 | 한국어 AI 티 제거 필수 | 대사에는 쓰지 않는다(말투는 인물의 것). 지문·기획서만 가볍게 |
| 되돌리기 | 최대 3바퀴 | 원인 단계로. 로그라인이 흔들리면 처음으로. 로그라인 변경은 작가 결정 |
| 상태 | 회차 점검표 | story-bible.md(세션을 넘어 이어 쓰기) |
| 누가 쓰나 | 에이전트 초안 | 공동집필 / 코치(원고는 작가가) / 점검만 |

## 단계와 담당 스킬

| 단계 | 담당 | 원본 |
|-|-|-|
| ①~⑤ 작법·단계표·story-bible | screenwriting (22모듈) | [jtydhr88/screenwriting-skills](https://github.com/jtydhr88/screenwriting-skills) (MIT) |
| ⑥ 대항 리뷰(7층 37개 기준, 작가 반박) | screenplay-review-checklist | [zhlmi/screenplay-review-checklist](https://github.com/zhlmi/screenplay-review-checklist) (MIT, 원저 인용 별도 권리) |
| ⑥ 실화·공공 게이트 | policy-media-desk 기준 | [goodmorninghope-khs/policy-media-desk](https://github.com/goodmorninghope-khs/policy-media-desk) |
| ⑧ 기획의도·시놉시스·홍보 문장 | writing-loop | [goodmorninghope-khs/writing-loop](https://github.com/goodmorninghope-khs/writing-loop) |
| ⑧ 쇼츠·홍보 클립 | marketingskills social·video | [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) (MIT) |
| 지문·기획서 윤문(대사 제외) | humanize-korean | [epoko77-ai/im-not-ai](https://github.com/epoko77-ai/im-not-ai) (MIT) |

## 구성

| 경로 | 내용 |
|-|-|
| `SKILL.md` | 루프 9단계, writing-loop와 다른 점, 판정·되돌리기 표, 판단 경계, 변경 이력 |
| `references/forms.md` | 형식 10가지(장편, 시리즈, 한정 시리즈, 단편, 숏폼, 무대극, 다큐·정책 영상 구성안, 쇼츠, 실화·평전, 소설)별 경로와 게이트 |
| `references/logline-card.md` | 로그라인 카드, 후보 5개 만들기, 테스트 10가지, 로그라인 대조 형식 |
| `references/gates.md` | 점검 다섯 칸(L 로그라인 대조 · W 단계 통과 기준 · R 대항 리뷰 · F 실화·공공 · A 관객 시뮬레이션) |
| `references/lessons.md` | 루프를 돌며 쌓는 노하우 |

## 더 붙일 수 있는 고리 (추천, 미설치)

- [danjdewhurst/story-skills](https://github.com/danjdewhurst/story-skills) (MIT): 장편 소설·연재의 연속성 검사(죽은 인물 재등장, 복선 회수 순서). Node CLI가 필요하다.
- [Calliope-Editor/writing-skills](https://github.com/Calliope-Editor/writing-skills) (MIT): 원고를 대신 쓰지 않는 편집자·합평·연습 스킬. 코치 모드의 본보기.
- [XucroYuri/how-to-make-script](https://github.com/XucroYuri/how-to-make-script) (MIT): 로그라인·비트시트 평가 기준(rubric)이 많은 각본 지식 저장소.

## 연계 (밸류체인)

| 고리 | 받는 것 | 넘기는 것 | 상태 |
|-|-|-|-|
| ② 제작 | policy-media-desk의 문체·선거법 기준 → 실화·공공 게이트 | 영상 시리즈 구성안·쇼츠 대본·실화 서사 | 제안 |
| ② 제작 | writing-loop에서 이야기 글로 판정된 요청 | 기획의도·시놉시스·공모전 문서·홍보 문장 → writing-loop | 연계 |
| ⑤ 확산 | - | 구성안·대본 → motion-studio·showreel(포크, 영상 제작) | 제안 |
| ⑥ 기록 | - | 루프 노하우(lessons.md), story-bible 결정 로그 | 연계 |

## 원칙

- 코치 모드에서는 작가의 문장을 고쳐 쓰지 않는다.
- 실존 인물을 다루는 이야기는 동의와 사실 확인 전에 공개용 원고로 넘기지 않는다. 각색이면 각색이라고 밝힌다.
- 작법 원저 인용문과 리뷰 기준의 원저 전문은 이 저장소에 넣지 않는다(각 원본 저장소의 NOTICE·README 참조).
- 실제 내부 기획·주민 정보·작업 ID는 이 저장소에 넣지 않는다.
