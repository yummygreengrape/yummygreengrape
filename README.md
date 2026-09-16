# Hi, I'm Podo 🍇

궁금한 걸 직접 만들어 보고, 재 보고, 틀린 걸 고치면서 배웁니다.
요즘은 자동화와 데이터 파이프라인, AI 인프라 쪽을 보고 있습니다.

*I build things I'm curious about, measure them, and fix what I got wrong — lately around automation, data pipelines, and AI infrastructure.*

## Projects

### Discord Archive

디스코드의 기능 변화와 소식을 흘려보내지 않고 기록으로 남기는 서비스입니다.
커뮤니티 서버에서 시작해 지금은 웹사이트와 봇까지 함께 굴러갑니다.
웹에서는 소식과 분석 글을 읽고 검색할 수 있고, 아래 데이터마이닝 결과도 여기서 봅니다.

→ [dicoarki.com](https://dicoarki.com)

### [Discord Datamining](https://github.com/yummygreengrape/discord-datamining)

Discord Canary 클라이언트를 주기적으로 받아 이전 빌드와 비교합니다.
바뀐 실험, 문자열, API 경로만 골라 JSON으로 남깁니다.

추출과 파싱을 맡은 러너는 비공개고, 공개 저장소에 올라가는 건 게시 전 검사를 통과한
결과 파일뿐입니다. 같은 데이터를 디스코드 봇과 웹이 나눠 씁니다.

→ [dicoarki.com/datamining](https://dicoarki.com/datamining) ([English](https://dicoarki.com/datamining?lang=en))

### [RNGD Workload Sizer](https://github.com/yummygreengrape/rngd-workload-sizer)

FuriosaAI RNGD NPU를 직접 재서 "이 서비스에 몇 장이 필요한가"에 답하는 도구입니다.
카탈로그의 peak TOPS로는 이 질문에 답할 수 없습니다.

재 보니 prefill 비용은 입력 길이에 비례하지 않고 몇 군데서 계단처럼 뜁니다.
동시성을 올릴 때 먼저 걸리는 것도 첫 응답이 아니라 사용자당 생성 속도였습니다.
측정이 틀렸던 일곱 가지도 원인과 함께 적어 뒀습니다. 그중 둘은 아직 미해결입니다.

## Stack

`Python` · `TypeScript`

## Contact

Discord · `@yummygrape`
