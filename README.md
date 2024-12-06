# **Git Commit Message Convention**

Git 커밋 메시지를 작성할 때 통일된 형식을 유지하면 협업과 코드 리뷰를 효율적으로 진행할 수 있습니다. 다음은 커밋 메시지 작성 규칙입니다.

---

## **Commit Message Structure**
 ```
    <type>: <subject>

    <description>

 ```

## Type
| 타입      | 설명                                                                 |
|-----------|----------------------------------------------------------------------|
| `feat`    | 새로운 기능 추가                                                     |
| `fix`     | 버그 수정                                                             |
| `docs`    | 문서 수정 (README, 코드 주석 등)                                       |
| `style`   | 코드 스타일 수정 (세미콜론, 공백, 코드 포맷 등)                       |
| `refactor`| 코드 리팩토링 (기능 변경 없이 코드 구조 개선)                         |
| `test`    | 테스트 코드 추가 또는 수정                                           |
| `chore`   | 기타 작업 (빌드 설정, 패키지 업데이트 등)                             |
| `perf`    | 성능 향상 (기능 수정 없이 성능을 개선하는 변경)                       |
| `ci`      | CI 설정 파일 수정 (Continuous Integration 관련)                      |
| `build`   | 빌드 시스템이나 외부 종속성 변경 (예: Gradle, Webpack 설정)          |
| `revert`  | 이전 커밋 되돌리기                                                    |
| `wip`     | 작업 중 (Work in Progress)                                            |

## Subject
커밋의 핵심 내용. 간결한 설명 작성

## Description (선택)
커밋에 대한 자세한 설명
