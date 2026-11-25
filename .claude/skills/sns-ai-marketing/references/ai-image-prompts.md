# AI 이미지 프롬프트 공식

모든 예시 프롬프트는 이 스킬을 위해 새로 작성했다. 사용자가 바꿀 부분은 `(괄호)`로 표시한다.
사용처: ChatGPT 이미지 생성, Google AI Studio/Gemini(나노바나나) 등. 사진을 함께 첨부해야 하는 프롬프트는 그 점을 꼭 안내한다.

---

## 1. 3D 클레이 피규어 디오라마 (내 사진 → 브랜드 박스 속 피규어)

**구조 공식**
1. 스타일: playful 3D clay-style diorama, stylized action figure
2. 인물: inspired by the uploaded photo + 헤어 + 표정 + 분위기
3. 무대: 브랜드 컬러의 **상자(신발 상자, 패키지 박스)를 작은 공방처럼 꾸민 공간**
4. 의상: 상의 / 하의 / 신발
5. 행동: 대표 제품을 보물처럼 들고 있음
6. 주변: 작은 클레이 일꾼들이 사다리와 선반에서 제품을 만들고 포장하는 코믹한 장면
7. 연출: studio lighting, toy photography aesthetic
8. 받침대 문구: 브랜드 슬로건이나 원하는 문구
9. 배경: 인물 성격이나 브랜드를 반영한 테마

**템플릿**
```
A playful 3D clay-style diorama of a cheerful (young woman/man) inspired by the uploaded photo,
keeping (hairstyle) and a (facial expression), sculpted as a stylized action figure.
The figure stands inside an open (brand color) (brand name) packaging box that has been turned
into a tiny, whimsical workshop. Outfit: (top), (bottoms), (shoes).
The figure proudly lifts (signature product) like a treasure, while tiny clay workers climb ladders
and shelves around them, crafting, wrapping and stacking (product) with comic energy.
Studio lighting, toy photography aesthetic, shallow depth of field.
The base has the words "(slogan)" embossed in bold letters.
Background: (background theme).
```

**괄호 번역표**: hairstyle 머리 스타일 · facial expression 표정 · brand color 브랜드 색 · top 상의 · bottoms 하의 · shoes 신발 · signature product 대표 제품 · slogan 받침대 문구 · background theme 배경 테마

**작성 예시 (가상의 동네 빵집 "Morning Crumb")**
```
A playful 3D clay-style diorama of a cheerful young woman inspired by the uploaded photo,
keeping her short bob haircut and a wide, warm smile, sculpted as a stylized action figure.
She stands inside an open cream-and-brown "Morning Crumb" bakery box turned into a tiny,
whimsical workshop. Outfit: a beige linen apron over a white shirt, denim pants, and brown clogs.
She proudly lifts a golden croissant like a treasure, while tiny clay bakers climb ladders and
shelves around her, kneading dough, dusting flour and boxing pastries with comic energy.
Studio lighting, toy photography aesthetic, shallow depth of field.
The base has the words "Fresh Every Morning" embossed in bold letters.
Background: a cozy bakery counter with rows of bread and warm morning sunlight.
```
⚠️ 실존 유명 브랜드 로고는 개인 재미용으로만 쓰도록 하고, 상업 광고에는 **본인 브랜드**를 넣도록 안내한다.
팁: 원하는 이미지가 나올 때까지 "표정만 더 밝게", "박스를 더 크게"처럼 부분 수정을 요청한다. 완성 이미지는 이미지→영상 AI(Kling, Veo, Higgsfield 등)로 움직이게 만들 수 있다.

---

## 2. 구름 글씨 & 구름 캐릭터

**구름 글씨 템플릿** (원하는 글자만 바꾸기)
```
A wide, bright blue sky where soft white clouds naturally drift together to spell the Korean
text "(원하는 글자)" in loose, airy handwriting. Below, (landscape: e.g. green hills and a calm lake)
under clear daylight. Photorealistic yet dreamy, fluffy cloud texture, vivid colors, high detail.
```
팁: 한글이 깨지면 글자 수를 줄이거나(2~4자), 영어로 먼저 시도하거나, 여러 번 다시 생성한다.

**사진 → 구름 캐릭터 템플릿** (본인 사진 첨부)
```
Turn the person in the uploaded photo into a cute, simplified character made entirely of fluffy,
realistic white clouds, floating above (city or landscape, e.g. the Seoul skyline at Han River).
Keep the hairstyle, outfit shape and key features recognizable, but rounded and cartoon-like,
with gentle shading for a sculpted 3D look. Realistic city/landscape below, clear blue sky with only
natural clouds. No emojis, hearts, stars or extra decorations. Dreamy, warm and playful mood.
```
"장식 금지" 문장을 넣어야 AI가 하트나 별을 임의로 추가하지 않는다.

---

## 3. 사진 편집 명령 (나노바나나 / Gemini 이미지 편집)

사진을 올리고 **짧고 명확한 영어 명령 한 문장**을 쓰는 방식이 가장 잘 먹힌다. 여러 장을 올리면 "this model", "the woman on the left"처럼 대상을 지정한다.

| 목적 | 명령 패턴 |
|---|---|
| 여러 장 합성 | `Merge these (N) photos into a single natural scene` |
| 데스크 피규어화 | `Turn this person into a collectible 3D figure standing on a desk` |
| 제품 들기(광고컷) | `Show this model holding the (product) from the second image` |
| 인물 교체 | `Replace the person in the (position) with (description)` |
| 함께 셀카 | `Make these two people look like they are taking a selfie together` |
| 옷 바꾸기 | `Dress this model in a (color) (garment)` / `...in the (garment) shown next to her` |
| 증명사진 | `Turn this into a formal ID photo` → `Change the background to (color)` |
| 표정 | `Change the expression to (happy / surprised / angry / sad)` |
| 스타일 변환 | `Redraw this as (pixel art / a jigsaw puzzle / watercolor / clay)` |
| 글자 효과 | `Make this lettering look like (inflated balloons / knitted yarn / neon glass)` |

순서대로 한 단계씩 수정하면 결과가 안정적이다. 실존 타인의 얼굴을 바꾸거나 합성하는 작업은 동의받은 사진으로만 하도록 안내한다.

---

## 4. ChatGPT × Canva 템플릿 찾기
1. ChatGPT에서 **GPT 탐색 → Canva GPT**(또는 Canva 앱 연결)를 연다.
2. 원하는 느낌을 문장으로 요청한다. 예: "어린이집 학부모 설명회용 동화 같은 발표 템플릿 추천해줘", "커피잔을 단순화한 따뜻한 느낌의 카페 로고 시안 보여줘"
3. 추천된 템플릿 링크를 클릭해 Canva에서 열고, 텍스트와 사진만 바꿔서 완성한다.
