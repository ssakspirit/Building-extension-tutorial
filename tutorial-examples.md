# 건물 예제 모음

## 소개 @unplugged

Building Extension으로 만들 수 있는 다양한 건물 예제를 배워봅시다!

학교, 성, 탑 등 실제로 사용할 수 있는 건물들을 만들어볼 거예요.

## 예제 1: 학교 건물

"학교"라고 채팅하면 ㄷ형 학교 건물을 만들어봅시다.

```blocks
player.onChat("학교", function () {
    building.직각건물속성정하기(
        30,
        25,
        15,
        4,
        0,
        STONE,
        PLANKS_OAK,
        STONE_BRICKS,
        BRICK_BLOCK,
        RED_CONCRETE,
        1,
        true,
        GLASS,
        3,
        2
    )
    building.ㄷ형건물생성()
})
```

## 예제 2: 작은 집

"집"이라고 채팅하면 아늑한 작은 집을 만들어봅시다.

```blocks
player.onChat("집", function () {
    building.직각건물속성정하기(
        12,
        10,
        8,
        4,
        0,
        COBBLESTONE,
        PLANKS_SPRUCE,
        LOG_SPRUCE,
        PLANKS_SPRUCE,
        BRICK_BLOCK,
        2,
        true,
        GLASS,
        2,
        2
    )
    building.ㅁ형건물생성()
})
```

## 예제 3: 성 (Castle)

"성"이라고 채팅하면 거대한 성을 만들어봅시다.

```blocks
player.onChat("성", function () {
    building.직각건물속성정하기(
        40,
        40,
        25,
        5,
        0,
        COBBLESTONE,
        STONE_BRICKS,
        STONE_BRICKS,
        STONE_BRICKS,
        STONE_BRICKS,
        1,
        true,
        GLASS_PANE,
        2,
        3
    )
    building.ㅁ형건물생성()
})
```

## 예제 4: 망루 (Tower)

"망루"라고 채팅하면 원형 망루를 만들어봅시다.

```blocks
player.onChat("망루", function () {
    building.원형건물속성정하기(
        6,
        20,
        4,
        0,
        COBBLESTONE,
        PLANKS_OAK,
        STONE_BRICKS,
        RED_CONCRETE,
        1
    )
    building.원형건물생성()
})
```

## 예제 5: 아파트

"아파트"라고 채팅하면 높은 아파트를 만들어봅시다.

```blocks
player.onChat("아파트", function () {
    building.직각건물속성정하기(
        20,
        15,
        30,
        3,
        0,
        STONE,
        LIGHT_GRAY_CONCRETE,
        IRON_BLOCK,
        WHITE_CONCRETE,
        GRAY_CONCRETE,
        1,
        true,
        GLASS,
        2,
        1
    )
    building.ㅁ형건물생성()
})
```

## 예제 6: L자형 상가

"상가"라고 채팅하면 ㄱ형 상가 건물을 만들어봅시다.

```blocks
player.onChat("상가", function () {
    building.직각건물속성정하기(
        25,
        25,
        12,
        4,
        0,
        COBBLESTONE,
        QUARTZ_BLOCK,
        STONE_BRICKS,
        WHITE_CONCRETE,
        CYAN_CONCRETE,
        1,
        true,
        GLASS,
        3,
        2
    )
    building.ㄱ형건물생성()
})
```

## 예제 7: 교회 (삼각 지붕)

"교회"라고 채팅하면 삼각 지붕이 있는 교회를 만들어봅시다.

```blocks
player.onChat("교회", function () {
    building.직각건물속성정하기(
        18,
        25,
        15,
        0,
        8,
        COBBLESTONE,
        PLANKS_OAK,
        STONE_BRICKS,
        QUARTZ_BLOCK,
        RED_CONCRETE,
        2,
        true,
        STAINED_GLASS,
        2,
        3
    )
    building.ㅁ형건물생성()
})
```

## 예제 8: 원형 신전

"신전"이라고 채팅하면 돔형 지붕의 원형 신전을 만들어봅시다.

```blocks
player.onChat("신전", function () {
    building.원형건물속성정하기(
        12,
        15,
        5,
        0,
        QUARTZ_BLOCK,
        GOLD_BLOCK,
        QUARTZ_BLOCK,
        GOLD_BLOCK,
        3
    )
    building.원형건물생성()
})
```

## 예제 9: 현대식 빌딩

"빌딩"이라고 채팅하면 현대식 유리 빌딩을 만들어봅시다.

```blocks
player.onChat("빌딩", function () {
    building.직각건물속성정하기(
        20,
        20,
        40,
        3,
        0,
        STONE,
        WHITE_CONCRETE,
        IRON_BLOCK,
        LIGHT_BLUE_CONCRETE,
        BLUE_CONCRETE,
        1,
        true,
        GLASS,
        2,
        1
    )
    building.ㅁ형건물생성()
})
```

## 예제 10: 피라미드

"피라미드"라고 채팅하면 피라미드형 건물을 만들어봅시다.

```blocks
player.onChat("피라미드", function () {
    building.직각건물속성정하기(
        30,
        30,
        20,
        0,
        15,
        SANDSTONE,
        SANDSTONE,
        SANDSTONE,
        SANDSTONE,
        GOLD_BLOCK,
        3,
        false,
        GLASS,
        2,
        2
    )
    building.ㅁ형건물생성()
})
```

## 완료! @unplugged

축하합니다! 다양한 건물 예제를 배웠습니다.

**배운 것:**
- 학교, 집, 성 등 실용적인 건물
- 망루, 신전 등 원형 건물
- 아파트, 빌딩 등 높은 건물
- 다양한 지붕 형태 활용

**이제 해볼 것:**
- 재료를 바꿔서 나만의 건물 만들기
- 크기를 조절하여 더 크거나 작은 건물 만들기
- 여러 건물을 조합하여 마을 만들기
- 창문 설정을 바꿔보기
