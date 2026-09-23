# 암살자 파견

<p class="pd-meta"><span class="pd-tag pd-tag--personal">개인 후원</span><span class="pd-tag pd-tag--harm">방해 효과</span><span class="pd-tag pd-tag--off">기본 꺼짐</span><span class="pd-id"><code>bandit_melee</code> <code>bandit_ranged</code></span></p>

무장한 적대 NPC 무리를 소환합니다.

| 종류 | 구성 |
| ---- | ---- |
| `bandit_melee` | 근접무기로 무장한 **4인** |
| `bandit_ranged` | 원거리 화기로 무장한 **2인**. 저격에 능한 개체가 포함됩니다 |

- 소환된 NPC 근처에 "{후원자}의 암살자" 표식이 잠시 표시됩니다.
- 여러 건이 몰리면 순서대로 처리됩니다.

!!! warning "기본값은 꺼져 있습니다"

    두 기능 모두 기본 금액이 **0**이라 사용하지 않는 상태입니다. 대기시간 설정도 **퐁듀 - Dev** 탭에 있습니다. 사용하려면 서버장이 **퐁듀 - 메인** 탭에서 금액을 직접 지정해야 합니다.

NPC의 공통 동작(출혈, 감염, 바리케이드 제거, 대사, 자막 등)은 샌드박스 **히트맨 일반 설정** 탭에서 조정합니다.

- 세이프하우스 안에서도 즉시 발동합니다.
- 대기시간: `Delay_bandit_melee` / `Delay_bandit_ranged` (기본 3초)
