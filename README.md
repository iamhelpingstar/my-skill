# useful skills

- https://github.com/android/skills
- https://github.com/skydoves/android-skills-mcp


# Prompt

## implementation

```
설계 확정 프로토콜 (Design Confirmation Protocol)
1. 추측 금지: 요구사항 중 조금이라도 모호하거나 논리적 공백이 느껴지는 부분은 임의로 결정하지 마세요.
2. 자체 조사 우선: 질문하기 전에, 프로젝트 내 코드베이스·설정 파일·기존 컨벤션 등 스스로 확인할 수 있는 정보는 먼저 파악하세요. 자체 조사로 해소된 사항은 질문 대신 "확인한 내용"으로 간략히 공유해 주세요.
3. 질문 루프 수행: 자체 조사 후에도 모호하거나 판단이 필요한 사항은 번호를 매겨 질문해 주세요. 내 답변 이후에도 추가로 모호한 점이 발견된다면, 다시 질문하여 이 과정을 반복하세요.
4. 단계별 진행: 질문이 모두 해소되어 제가 '최종 승인'을 내리기 전까지는 실제 코드를 작성하지 마세요.
5. 대안 제시 + 추천: 질문할 때 단순히 모른다고 하기보다, 당신이 생각하는 설계 방향을 선택지(Option A, B 등)로 함께 제시하세요. 각 선택지에는 장단점을 간략히 명시하고, 당신이 추천하는 방향과 그 이유를 명확히 밝혀 의사결정을 도와주세요.
"위 프로토콜에 따라, 먼저 자체 조사를 수행한 뒤 확인이 필요한 질문을 시작해 주세요."
```

## commit

```
Review the current git diff, identify the changes made so far, and split them into logical work-unit commits. Do not modify any code. Do not include Co-authored-by in commit messages. Write each commit message in English as a single line.
```

## 기획 (초기)
```
기획 수정 프로토콜 (Design Confirmation Protocol)
1. 추측 금지: 요구사항 중 조금이라도 모호하거나 논리적 공백이 느껴지는 부분은 임의로 결정하지 마세요.
2. 질문 루프 수행: 자체 조사 후에도 모호하거나 판단이 필요한 사항은 번호를 매겨 질문해 주세요. 내 답변 이후에도 추가로 모호한 점이 발견된다면, 다시 질문하여 이 과정을 반복하세요.
3. 대안 제시 + 추천: 질문할 때 단순히 모른다고 하기보다, 당신이 생각하는 설계 방향을 선택지(Option A, B 등)로 함께 제시하세요. 각 선택지에는 장단점을 간략히 명시하고, 당신이 추천하는 선택지과 그 이유를 명확히 명시하여 의사결정을 도와주세요.
4. 단계별 진행: 질문이 모두 해소되어 제가 '최종 승인'을 내리기 전까지는 기획 과정을 완료하지 마세요
"위 프로토콜에 따라, 먼저 자체 조사를 수행한 뒤 확인이 필요한 질문을 시작해 주세요."
```


## Figma

```
Implement this Figma design as an Android UI using Jetpack Compose.
Requirements:
* Match the Figma layout, spacing, hierarchy, and interactions as accurately as possible.
* Do not hardcode color or typography values.
* Use the existing Design System / Theme tokens for color and typography.
* If a required color, typography style, spacing value, or token is unavailable or unclear, ask a question instead of guessing.
* Split the UI into reusable composable functions.
* State should be provided from a ViewModel or from a parent composable.
* Write an @Preview.
* The preview component must be wrapped with PilsaTheme, like this: PilsaTheme { YourComposable() }.
* Include mock state/data needed for the preview.
```

## Translation

```
위 내용을 한국어로 번역해주세요.
아래 용어들은 번역하지 말고 영어 그대로 유지해주세요: [manifest, callback, parent activity, child activity, type-safe, recomposition, scope, semantic label, view, boiler plate, response, codegen, navigation, Domain Layer, UI Layer, Data Layer, source of truth, exponential backoff, intent, Activity, intent-filter, filter, use case, annotation, flavor, feature, module, annotation, side-effect, back pressure, ViewModel, context, concurrently, concurrent, source of truth, component, string, persistent storage, override, initialize, stable, unstable, state, mutable, immutable, idempotence, idempotent, imperative, declarative, skip, input, output, property, parameter, control, controlled, mutability, in place, extend, configuration, modifier, suspending, suspension, function, R8 optimization, optional, higher-order function, named parameter, lifecycle, composition, composable, request, deserialize, serialize, color scheme, lifecycle-aware]
반드시 아래 규칙을 지켜주세요.
1. 원문의 모든 내용을 빠짐없이 번역하세요.
2. 내용을 요약하거나 축약하지 마세요.
3. 문장, 문단, bullet, numbering, heading, code block, table, Markdown 구조를 가능한 한 원문과 동일하게 유지하세요.
4. 원문에 있는 예시, 괄호 안 설명, 주석, 경고, 단서 조항도 생략하지 마세요.
5. 의미를 바꾸거나 임의로 내용을 추가하지 마세요.
6. 원문의 정보량과 논리 구조를 보존하세요.
7. 번역하지 말라고 지정한 용어는 대소문자와 철자를 그대로 유지하세요.
8. 코드, 파일명, 클래스명, 함수명, 변수명, package명, URL, 명령어는 번역하지 말고 그대로 유지하세요.
9. 원문에 없는 설명이나 요약을 마지막에 덧붙이지 마세요.
10. 최종 답변에는 번역문만 출력하세요.
11. Kotlin 코드는 반드시 ```kotlin으로 시작하고 ```으로 끝나는 Markdown code block으로 감싸세요.
12. 원문에서 Kotlin 코드가 inline code, 일반 텍스트, 잘못된 code block, 또는 언어가 지정되지 않은 code block으로 제공되더라도, 출력할 때는 올바른 kotlin code block으로 변환하세요.
13. data class, class, object, interface, fun, val, var, @Serializable, @Composable, suspend fun, Kotlin annotation, Kotlin property, Kotlin function 등이 포함된 코드는 Kotlin 코드로 간주하세요.
14. Kotlin 코드 내부의 주석은 번역해도 되지만, 코드의 식별자, string literal, package명, import문, annotation, class명, function명, property명은 임의로 변경하지 마세요.
15. Kotlin 코드가 아닌 일반 설명 문단은 code block으로 감싸지 마세요.
번역을 마치기 전에 원문과 번역문을 대조하여 누락된 문장, 항목, 코드가 없는지 자체 점검한 뒤 출력하세요.
```
