# Relay Note 78

## 📌 목차

1. 아이디어 브레인스토밍
2. 정해진 주제
3. 조사 내용

---

## 1. 💡 아이디어 브레인스토밍

### ✅ 주요 채택 아이디어

- **메타인지 프롬프트 만들기**
  → 사용자의 누적 데이터를 기반으로 AI가 스스로에 대해 되묻고 자각하는 질문을 생성.
  → 본인의 학습 습관, 사고 방식 등을 더 잘 이해할 수 있음.

- **AI로 간단한 노래 만들기**
  → Slack에 음악을 공유하는 동료들이 많아, 흥미와 몰입도가 높을 것으로 판단.
  → 개성 있는 자작곡을 AI로 제작 가능.

- **AI로 웹툰 만들기**
  → 개발자들의 일상, 해프닝 등을 재밌게 시각화하여 희화화 가능.
  → 스토리텔링을 기반으로 몰입도 높은 결과물이 기대됨.

- **영상 AI 활용하기**
  → 음악 + 영상을 결합하면 뮤직비디오 제작도 가능.
  → 영상은 퀘스트 형태로 선택적으로 진행하면 부담을 줄이면서 퀄리티도 확보 가능.

### 📝 기타 제안 아이디어

- **AI 툴 챌린지 (제한 시간 내 최대 활용)**
  → 해커톤처럼 다양한 AI 툴을 시간 내 최대한 사용해보고 비교 학습.

- **CLI 기반 AI (예: Gemini)**
  → 터미널 환경에서 동작하는 AI를 활용한 프로젝트 제안.

- **여러 AI 툴 결과 비교하기**
  → 같은 작업을 여러 AI에게 시켜보고 결과 비교 → 각 도구의 장단점 이해에 도움.

- **AI 기반 성장 로드맵 생성기**
  → 사용자의 현재 학습 상태를 분석해 앞으로의 학습 경로를 AI가 설계.

- **금융 분석 AI (주식, 코인 등)**
  → 재테크 수요를 반영하여, 과거 데이터를 기반으로 분석 및 전략 수립 도와주는 도구.
  → 현실적인 제약으로 채택은 보류됨.

- **AI로 개발 로그 웹툰화**
  → 개발자의 삽질/버그/성공 로그 등을 스토리 기반 웹툰으로 자동 변환.
  → 학습 회고를 재미있게 만들 수 있음.

- **향후 부스트캠프 과제 예측기**
  → 지금까지 과제 데이터를 기반으로 다음 과제를 예측하는 AI.

---

## 2. 🎯 정해진 주제

> **“본인의 메타인지에 대한 작품을 AI로 만들기”**

- **작품 종류 선택**: 그림, 웹툰, 영상, 노래 중 1개 이상
- **메타인지 확인 방법**: AI에게 스스로를 돌아볼 수 있는 프롬프트 활용
- **형식 예시**:

  - A: 웹툰
  - B: 그림
  - C: 노래
  - D: 영상

- **중복 지양**: 팀원 간 작품 형태가 겹치지 않도록 조율
- **복수 선택 가능**: 하나 이상의 형식을 선택해도 무방함

---

## 3. 🔍 조사 내용

- **메타인지 프롬프트 예시 및 활용법**
- **그림 생성 AI 도구**
- **웹툰 제작 AI 툴**
- **음악 생성 AI (예: Suno, Udio 등)**
- **영상 생성 AI (예: Pika, Runway, Sora 등)**

### 메타인지란 무엇인가

**메타인지(Metacognition)**란 쉽게 말해 "자신의 사고 과정을 인식하고 조절하는 능력"입니다. 즉, 내가 무엇을 알고 있고, 무엇을 모르고 있는지를 아는 것입니다.
이는 학습과 문제 해결, 그리고 자기 주도적인 성장을 위한 핵심 능력입니다.

### 📌 개발자에게 메타인지가 중요한 이유

- 디버깅 어떤 부분에서 실수가 발생했는지를 스스로 인식하고 전략적으로 접근 가능
- 학습 내가 잘 모르는 개념을 인지하고 필요한 리소스를 찾아 학습 가능
- 성장 반복되는 실수나 개선이 필요한 습관을 돌아보고 수정할 수 있음
- 협업 자신의 이해 수준을 파악하여 적절한 질문이나 피드백을 줄 수 있음

## 메타인지를 확인하는 프롬포트

### ✅ (1) 사용자 데이터가 충분히 축적된 경우

```
지금까지 내가 너와 나눈 대화, 작성한 코드, 고민한 문제들을 바탕으로,

1. 내가 잘하는 부분과 강점을 정리해줘.
2. 내가 자주 실수하거나 약점을 보이는 부분을 알려줘.
3. 앞으로 어떤 학습 전략을 세우면 좋을지 조언해줘.
4. 내 사고나 학습 습관에 대해 메타인지 관점에서 요약해줘.
```

### ✅ (2) 사용자 데이터가 없는 경우 (또는 처음인 경우)

```
나는 개발자로서 아래 질문에 따라 내 상태를 되돌아보고 싶어.

1. 최근에 가장 자신 있게 구현한 기능은 무엇이었나? 왜 그렇게 느꼈는가?
2. 최근에 가장 어려웠던 문제는 무엇이었고, 어떻게 해결했는가?
3. 내가 자주 실수하는 영역(예: 상태관리, 성능 최적화, 비동기 처리 등)은 무엇이라고 생각하는가?
4. 현재 학습하고 있는 내용 중, 내가 제대로 이해하지 못하고 있는 부분은 무엇이라고 느끼는가?
5. 나의 학습 방식(예: 문서 읽기, 강의 보기, 프로젝트 기반 학습 등)은 효과적인가?

이 답변을 바탕으로, 내 강점, 약점, 개선 방향을 메타인지 관점에서 정리해줘.
```

## 그림 생성 ai 도구 정리

- chat gpt
- canva
- 플라멜

## 그림 생성을 위한 프롬포트 작성법

---

(_영문 프롬프트와 한글 설명 병기_)

### ✅ 1. 기본 구조

> 영어로 작성하는 것이 대부분의 AI 도구에서 더 높은 퀄리티의 결과를 만듭니다. 아래는 추천 구조입니다.

```
주제(Subject), 매체(Medium), 스타일(Style), 조명(Lighting), 색감(Color Tone), 구도(Perspective), 감정(Emotion)
```

---

### ✅ 2. 구성 요소 예시 (영어 프롬프트 + 한글 설명)

| 요소       | 영어 프롬프트 예시                          | 한글 설명                               |
| ---------- | ------------------------------------------- | --------------------------------------- |
| **주제**   | a developer reflecting on his past mistakes | 자신의 실수를 되돌아보는 개발자         |
| **매체**   | digital painting, 3D render, sketch         | 디지털 페인팅, 3D 렌더, 스케치 등       |
| **스타일** | anime style, cyberpunk, minimalist          | 애니메이션풍, 사이버펑크, 미니멀리즘 등 |
| **조명**   | dramatic shadows, warm lamp light           | 극적인 그림자, 따뜻한 조명 등           |
| **색감**   | muted colors, pastel tones                  | 차분한 색상, 파스텔톤                   |
| **구도**   | isometric view, close-up, top-down          | 등각 뷰, 클로즈업, 탑다운 뷰 등         |
| **감정**   | frustration, growth, enlightenment          | 좌절, 성장, 깨달음 등                   |

---

### ✅ 3. 프롬프트 예시 (영어 + 한글 해석)

#### 예시 1. 메타인지 기반 회고 일러스트

```txt
A digital illustration of a software developer sitting alone at a desk, surrounded by floating error messages and code snippets. The lighting is dim with a warm desk lamp glow. Style is semi-realistic, color tone is muted blue and orange, emotion is introspection and determination.
```

> **한글 해석:**
> 책상에 혼자 앉아 있는 소프트웨어 개발자의 디지털 일러스트. 주변에는 떠다니는 에러 메시지와 코드 조각들이 있음. 따뜻한 전등 아래 어두운 조명. 반사실주의 스타일, 차분한 파란색과 주황색 톤. 감정은 자기 성찰과 결심.

---

#### 예시 2. 버그와 싸우는 희화화된 이미지

```txt
A cartoon-style image of a programmer fighting a huge bug monster with a keyboard as a sword. Bright colors, comic-book style, dynamic perspective. Emotion: frustration mixed with humor.
```

> **한글 해석:**
> 거대한 버그 몬스터와 키보드를 칼 삼아 싸우는 프로그래머의 만화 스타일 이미지. 밝은 색상, 코믹북 스타일, 역동적인 시점. 감정은 좌절과 유쾌함이 혼재됨.

---

#### 예시 3. 성장의 여정과 메타인지 은유

```txt
A surreal painting of a person climbing a staircase made of code, leading to a glowing brain in the sky. Fantasy art style, ambient lighting, pastel colors. Emotion: ambition and self-awareness.
```

> **한글 해석:**
> 코드로 만들어진 계단을 올라 하늘의 빛나는 뇌를 향하는 사람의 초현실적 그림. 판타지 아트 스타일, 몽환적인 조명, 파스텔 색감. 감정은 야망과 자기 인식.

---

### ✅ 4. 프롬프트 작성 팁

- 영어로 작성하되, 미리 한글로 생각을 정리해보는 것이 좋습니다.
- "무엇을 표현하고 싶은가?"에 감정과 맥락을 넣어야 더 풍부한 결과가 나옵니다.
- 여러 스타일을 병렬로 작성하거나, “like”를 이용해 참고 작가를 명시할 수도 있습니다.

  ```txt
  in the style of Hayao Miyazaki, watercolor texture, peaceful mood
  ```

다음은 **웹툰 생성 AI 도구 정리**와 **웹툰 생성을 위한 프롬프트 작성법**입니다.
그림 생성보다는 더 복잡한 구조(캐릭터 연속성, 컷 구성, 대사 흐름 등)를 갖는 웹툰을 위한 자료로, 도구와 작성 방식 모두 실용성 중심으로 구성했습니다.

---

## 🎬 웹툰 생성 AI 도구 정리

| 도구 이름                           | 특징                                                        | 접근 방식                           | 추천 용도                                       |
| ----------------------------------- | ----------------------------------------------------------- | ----------------------------------- | ----------------------------------------------- |
| **Storyboard Hero**                 | 컷 단위 웹툰 구성, 인물 연속성 유지, 자동 배경 삽입         | 영어 프롬프트 입력 → 컷 구성 자동화 | 상황극 기반의 회고, 시나리오 기반 메타인지 묘사 |
| **ToonCrafter (by Tencent ARC)**    | 동일 캐릭터의 연속 동작 이미지 생성, 컷 간 일관성 유지 탁월 | 1장면 → 연속컷 자동 생성            | 짧은 에피소드 표현, 움직임이 있는 장면          |
| **Comipo / MangaMaker**             | 직접 포즈 조절, 말풍선 삽입 등 편집 가능                    | 3D 캐릭터 조립형 UI                 | 연출 제어가 필요한 만화형 회고                  |
| **Leonardo AI** + **Canva** 조합    | 캐릭터 일러스트 생성 → Canva로 컷 구성 및 말풍선 추가       | AI 그림 + 수동 편집                 | 자유도 높은 시각적 회고 (텍스트 중심)           |
| **Storyboard Generator (GPT 기반)** | 텍스트 시나리오 → 컷 설명 자동 생성                         | ChatGPT 연동 프롬프트 사용          | 대사 중심 회고 or 메타인지 과정 설명 웹툰       |

---

## ✏️ 웹툰 생성을 위한 프롬프트 작성법

---

### ✅ 1. 프롬프트 구성 요소

| 요소          | 영어 작성 예시                               | 한글 설명                          |
| ------------- | -------------------------------------------- | ---------------------------------- |
| **장면 배경** | a messy developer's room full of monitors    | 모니터가 가득한 지저분한 개발자 방 |
| **등장인물**  | a young frustrated developer                 | 좌절한 젊은 개발자                 |
| **상황**      | debugging a critical error before a deadline | 마감 전 심각한 오류 디버깅 중      |
| **감정 변화** | from confusion to enlightenment              | 혼란에서 깨달음으로 변하는 감정    |
| **컷 수**     | 4-panel webtoon                              | 4컷 구성                           |
| **톤**        | humorous and relatable                       | 유머 있고 공감 가능한 분위기       |

---

### ✅ 2. 프롬프트 예시 (영어 + 한글 해석)

#### 예시 1. 메타인지 기반 회고 웹툰 (4컷)

```txt
Create a 4-panel webtoon about a junior developer who is trying to fix a bug.
1st panel: He's confused and panicking.
2nd: He searches Stack Overflow but finds nothing.
3rd: He remembers a similar past mistake.
4th: He fixes the bug and smiles confidently.
Background is a desk with dual monitors. Style is simple cartoon. Emotion: growth and reflection.
```

> **한글 해석:**
> 버그를 고치려는 주니어 개발자에 대한 4컷 웹툰을 만들어줘.
>
> - 1컷: 혼란에 빠져 당황하는 모습
> - 2컷: 스택오버플로우를 검색하지만 원하는 답을 찾지 못함
> - 3컷: 과거 비슷한 실수를 떠올림
> - 4컷: 버그를 고치고 자신감 있게 미소 짓는 장면
>   배경은 듀얼 모니터가 있는 책상, 스타일은 단순한 만화풍, 감정은 ‘성장과 회고’

---

#### 예시 2. 메타인지 은유 웹툰

```txt
A 3-panel webtoon where a developer climbs a staircase of errors.
Each step represents a bug he overcame.
At the top, he meets a version of himself giving advice.
Style: pastel tones, soft lighting, emotional tone of reflection.
```

> **한글 해석:**
> 개발자가 ‘버그 계단’을 오르는 3컷 웹툰.
> 각 계단은 그가 해결한 문제 하나씩을 의미하며,
> 마지막 계단 꼭대기에서 과거의 자신이 조언을 주는 장면.
> 파스텔 색감, 부드러운 조명, 회고적인 감성 강조.

---

### ✅ 3. 작성 팁

- **컷 수는 명확히 지정** (`4-panel`, `6-frame webtoon`)
- **시간 흐름**이나 **감정 변화**가 있으면 AI가 연출을 더 풍부하게 표현
- **배경과 상황**을 구체적으로 지정하면 AI 도구에서 컷별 연속성이 좋아짐
- **툴에 따라 나눠서**:

  - 컷 구성 → GPT, Notion 등에서 미리 구상
  - 그림 생성 → Midjourney, DALL·E
  - 배치 및 말풍선 → Canva, Pixton, ComicGen 등

---

## 🎼 노래 생성 AI 도구 정리

| 도구 이름   | 특징                                                 | 접근 방식           | 추천 용도                                    |
| ----------- | ---------------------------------------------------- | ------------------- | -------------------------------------------- |
| **Suno AI** | 프롬프트 기반 전체 노래 생성 (가사+보컬+멜로디) 가능 | 텍스트 or 가사 입력 | 감성 기반 자작곡 제작, 빠른 공유용 음악 생성 |
| **Udio AI** | 감정 표현 중심의 멜로디와 보컬 생성, 퀄리티 우수     | 텍스트 or 가사 입력 | 분위기 중심의 노래, 한국어 가사 표현도 자연  |

---

## 🎼 노래 생성을 위한 프롬프트 작성법

---

### ✅ 1. 프롬프트 구성 요소

| 요소       | 영어 예시                                              | 한글 설명                               |
| ---------- | ------------------------------------------------------ | --------------------------------------- |
| **주제**   | a song about self-discovery and learning from mistakes | 자기 발견과 실수를 통해 성장하는 이야기 |
| **스타일** | soft indie pop, K-pop ballad, lo-fi hiphop             | 인디팝, 발라드, 로파이 등               |
| **감정**   | hopeful, melancholic, reflective                       | 희망, 쓸쓸함, 성찰 등                   |
| **보컬**   | female voice, soft tone                                | 여성 보컬, 부드러운 음색                |

---

### ✅ 2. 프롬프트 예시

#### 예시 1. 영어 노래 프롬프트

```txt
Create a reflective indie-pop song about realizing one's thought patterns. Include soft piano and ambient background. The lyrics should be introspective, touching on self-awareness and quiet determination. Sung in English.
```

#### 예시 2. 한국어 노래 프롬프트

```txt
자기 인식을 주제로 한 감성적인 인디팝 노래를 만들어 주세요. 가사는 내면의 목소리를 듣고, 실수에서 배우는 과정을 담아주세요. 부드러운 피아노와 몽환적인 분위기의 배경이 어울리면 좋겠습니다. 한국어 가사로 불러주세요.
```

---

### ✅ 3. 작성 팁

- “감정 + 장르 + 보컬”을 조합하면 원하는 톤을 정확히 전달할 수 있음
- 영어 프롬프트가 모델의 이해도와 표현력을 더 끌어냄 (단, 한글도 지원)
- 가사를 직접 쓰는 대신 주제만 설명해도 자동 생성 가능

---

## 🎬 영상 생성 AI 도구 정리

| 도구 이름         | 특징                                             | 접근 방식     | 추천 용도                                |
| ----------------- | ------------------------------------------------ | ------------- | ---------------------------------------- |
| **Adobe Express** | 텍스트 기반 영상 생성 (최대 5초, 무료 계정 기준) | 프롬프트 입력 | 짧은 영상 생성 + 자작 노래 영상화 (뮤비) |

---

## 🎬 영상 생성을 위한 프롬프트 작성법

---

### ✅ 1. 프롬프트 구성 요소

| 요소       | 영어 예시                                 | 한글 설명                      |
| ---------- | ----------------------------------------- | ------------------------------ |
| **장면**   | a person walking through shifting seasons | 계절이 바뀌는 길을 걷는 사람   |
| **분위기** | cinematic, dreamlike                      | 영화 같은 느낌, 몽환적         |
| **톤**     | soft lighting, natural colors             | 부드러운 조명, 자연스러운 색감 |
| **길이**   | under 5 seconds                           | 5초 이내 (무료 계정 한계)      |

---

### ✅ 2. 프롬프트 예시

```txt
Create a short cinematic video showing a person walking alone through changing seasons. The final scene ends with a sunrise. Style is soft and reflective. Duration: 5 seconds.
```

---

### ✅ 3. 작성 팁

- Adobe Express는 **프롬프트 한 문장**으로도 생성 가능하지만, 구체적으로 쓸수록 영상 품질이 올라감
- 무료 사용자는 영상 길이 5초까지만 가능 → “1장면 중심”으로 프레이밍 필요
- 배경음악(mp3)은 직접 업로드하여 삽입 가능 → Suno/Udio에서 생성한 음악 활용 가능

---

# 릴레이 과제 수행

[relay_83 링크 ](https://github.com/boostcampwm2025/relay-note83/blob/main/week1.md)

### J091\_노기훈

- ✅ 퀘스트 3. 나의 질문 로그로 부족한 점 파악하기

### J017\_고윤성

- ✅ 퀘스트 2. AI에게 학습 퀴즈 요청하고 직접 풀기
- 

<br/>

---



# 🎯 퀘스트 분담

  - **웹툰: J072_김지원**
  - **그림: J274_최지민**
  - **노래: J066_김재훈**
  - **영상: J242_정승준**
