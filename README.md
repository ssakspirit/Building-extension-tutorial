# Building Extension Tutorial

Building Extension 사용법을 배우는 단계별 튜토리얼입니다.

## 📚 튜토리얼 내용

- ✅ 직각 건물 만들기 (ㅁ형, ㄱ형, ㄷ형)
- ✅ 원형 건물 만들기
- ✅ 건물 속성 설정 (크기, 재료, 창문)
- ✅ 건물 지우기

## 🎮 튜토리얼 시작 방법

### 방법 1: 웹 브라우저에서 시작

브라우저에서 다음 링크를 열어주세요:
```
https://minecraft.makecode.com/#tutorial:github:ssakspirit/Building-extension-tutorial/tutorial
```

### 방법 2: education.json 파일 사용 (권장)

월드가 시작될 때 자동으로 Code Builder에서 튜토리얼을 열도록 설정할 수 있습니다.

1. 마인크래프트 Education Edition 월드 폴더로 이동:
   ```
   설치 파일로 설치한 경우
   C:\Users\사용자이름\AppData\Roaming\Minecraft Education Edition\games\com.mojang\minecraftWorlds
   스토어 경유해서 설치한 경우
   C:\Users\username\AppData\Local\Packages\Microsoft.MinecraftEducationEdition_8wekyb3d8bbwe\LocalState\games\com.mojang\minecraftWorlds
   ```

2. 월드 폴더 안에 `education.json` 파일을 생성하거나 수정:
   ```json
   {
       "codebuilder": {
           "canResize": true,
           "defaulturi": "https://minecraft.makecode.com/#tutorial:github:ssakspirit/Building-extension-tutorial/tutorial"
       },
       "commands": {
           "hiddenFromPlayer": [""]
       }
   }
   ```

3. 월드에 접속하면 자동으로 튜토리얼이 열립니다!

### 방법 3: 커맨드 블록 사용

1. 크리에이티브 모드에서 커맨드 블록을 설치합니다
2. 커맨드 블록에 다음 명령어를 입력:
   ```
   codebuilder navigate @p false https://minecraft.makecode.com/#tutorial:github:ssakspirit/Building-extension-tutorial/tutorial
   ```
3. 커맨드 블록을 활성화하면 가장 가까운 플레이어에게 튜토리얼이 열립니다

**팁:** 버튼과 연결하여 플레이어가 버튼을 누르면 튜토리얼이 열리도록 만들 수 있습니다.

### 방법 4: NPC 사용

1. 교육용 NPC를 배치합니다
2. NPC 설정에서 "고급설정" 
3. "다음 명령어 입력:
   ```
   codebuilder navigate @initiator false https://minecraft.makecode.com/#tutorial:github:ssakspirit/Building-extension-tutorial/tutorial
   ```
4. NPC와 상호작용하면 튜토리얼이 열립니다

**참고:** `@initiator`는 NPC와 상호작용한 플레이어를 의미합니다.

이 튜토리얼은 [Building Extension](https://github.com/ssakspirit/Building-extension)을 사용합니다.

Building Extension의 모든 기능:
- 직각 건물: ㅁ형, ㄱ형, ㄷ형
- 원형 건물
- 다양한 지붕 형태: 평면, 삼각형, 피라미드형, 돔형
- 창문 자동 생성
- 다층 건물 지원

## 🔧 문제 해결

### 튜토리얼이 열리지 않는 경우
- 인터넷 연결을 확인하세요
- 브라우저에서 먼저 테스트해보세요
- URL이 정확한지 확인하세요

### Building 블록이 보이지 않는 경우
- 튜토리얼을 완전히 닫고 다시 열어보세요
- 브라우저 캐시를 지우고 다시 시도하세요

### 커맨드 블록이 작동하지 않는 경우
- 커맨드 블록이 활성화되어 있는지 확인하세요
- 레드스톤 신호가 제대로 전달되는지 확인하세요

## 🤝 기여

이슈나 개선 사항이 있다면 GitHub에 이슈를 등록해주세요!

이 확장과 튜토리얼은 스티브코딩이 제작 및 배포합니다. 
