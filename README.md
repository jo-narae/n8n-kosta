# n8n KOSTA 실습 자료

KOSTA n8n 교육 과정용 워크플로우 모음입니다. 각 `.json` 파일을 n8n에 임포트하여 사용하세요.

## 커리큘럼

| LO | 주제 |
|---|---|
| LO2 | 데이터 흐름, 표현식, Loop |
| LO3 | 기본 AI 챗봇, Few-shot, 역할 프롬프트 |
| LO4 | RSS / 뉴스 수집 및 검색 |
| LO5 | Agent Tools (Wikipedia, Calculator, SerpAPI, Multi-Tool) |
| LO6 | Memory (없는 챗봇 vs Simple Memory) |
| LO7 | OAuth 연결 (Gmail, Calendar, Drive) |
| LO8 | AI 이메일 분류 / Gmail Trigger |
| LO9 | Discord Webhook, 영어 튜터 봇 |
| LO10 | Google Drive 문서 검색 / 요약 메일 |
| LO11 | 임베딩 저장 (Pinecone), RAG 챗봇 |

## 사용 방법

1. n8n에서 **Workflows → Import from File** 선택
2. 원하는 `.json` 선택
3. 각 노드의 Credentials를 본인 계정으로 재연결 (파일에는 credential ID 참조만 있으며 실제 키는 포함되지 않음)

## 요구 Credentials

- OpenAI API
- Google OAuth2 (Gmail / Calendar / Drive)
- Pinecone API (LO11)
- SerpAPI (LO5)
- Discord Webhook (LO9)
