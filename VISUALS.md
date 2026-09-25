# 비주얼 제작 기록

내장 image_gen 도구로 제작·편집한 프로젝트용 비주얼입니다. 웹 전송 용량을 줄이기 위해 JPEG로 저장했습니다. 공간 이미지 원본과 대표자 사진 원본은 보존했습니다.

- `assets/nature-path.jpg`: 첫 화면의 숲길 비주얼
- `assets/connection-ripples.jpg`: 몸·마음·관계의 연결을 표현하는 물결 비주얼
- `assets/director-portrait.jpg`: 대표자 원본 캡처의 UI 제거 및 프로필 구도·조명 정리

## 사용 프롬프트

### 숲길

Use case: photorealistic-natural. Asset type: portrait hero photograph for a Korean integrated health counseling website, 1024x1536 portrait composition. Create a refined editorial nature photograph: a gently curving narrow walking path through soft green woodland, warm morning sunlight streaming between graceful trees, delicate leaves catching light, a calm welcoming sense of taking the first step and breathing freely. Natural muted sage greens, warm cream highlights, earthy beige, matching a cream and forest green wellness site. Atmospheric depth, subtle film grain, real organic texture, luminous and hopeful, beautifully composed, not overly dark. No people, no buildings or interiors, no medical symbols, no text, no logo, no watermark. Full bleed photograph only, no border or layout.

### 물결

Use case: photorealistic-natural. Asset type: landscape editorial visual for the body-mind-relationships philosophy section of a Korean counseling website, 1536x1024. Create a tranquil close-up nature photograph of three smooth warm grey river stones partly emerging from shallow clear water, their delicate circular ripples meeting and connecting, a small softly focused green branch at upper edge, warm sunlight reflected on water and sandy riverbed, soft sage green reflections and warm cream light, subtle natural texture, sophisticated editorial wellness photography. Balanced asymmetrical composition with spacious breathing room, gently poetic but realistic, no stacked stones, no spa props, no people, no room or furniture, no text, no logo, no watermark. Full bleed photograph only.

### 대표자 사진

Use case: identity-preserve / precise-object-edit. Edit target: attached local photo is a mobile screenshot of a Korean woman's portrait. Produce a clean professional website portrait photograph with absolutely no phone screenshot UI. Remove all status bar/time/battery icons, back arrow, social app avatar/name/date/text, heart/chat/more buttons, dark bottom navigation bar, and interface gradient overlays. Crop/reframe to a flattering portrait 4:5 composition, head and shoulders with some upper torso, modest headroom. Preserve the EXACT SAME woman's facial identity, age, facial geometry, eyes, nose, smile, hair, earrings, necklace, white blouse and natural friendly expression. Do not beautify into a different person, no age reduction, no face reshaping, retain natural skin texture. Keep original dark warm wooden architectural background but softly defocus it and remove the distracting framed sign/calligraphy; do not invent a clinic or office. Correct exposure and white balance very subtly for natural soft daylight and a warm cream/forest green counseling website palette. Clean, credible editorial portrait, realistic photograph, no text, no watermark, no added objects. The result must look like the original portrait photograph recovered from the screenshot, not a new person.


로고: 사용자 제공 `정인로고.png`를 원본 그대로 `assets/jeongin-logo.png`로 이름 변경했습니다. `jeongin-symbol.svg`는 동일 원본을 내장해 심볼 영역만 표시하는 SVG 뷰포트로, 상단·하단·파비콘에 사용합니다. 이름 소개에는 전체 원본을 표시합니다.
