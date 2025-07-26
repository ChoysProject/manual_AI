
AI 사내 매뉴얼 챗봇 서비스
-------------------------


1. frontend 설치

    frontend/에서
    npx create-next-app@latest frontend --typescript
    설치옵션 Y Y Y Y Y N -> 코드검사 기능.. css 자동 라이브러리.. 터보엔진.. 등

backend 설치

    backend/에서
    pip install fastapi uvicorn langchain langchain-openai pypdf chromadb python-multipart
        : pip 미설치시 설치
        : 하기 라이브러리 설치 포함
    주요 라이브러리:
    문서 파싱: pypdf, python-docx, unstructured
    임베딩/LLM: langchain, langchain-openai, sentence-transformers
    벡터DB: chromadb
    파일 업로드: FastAPI의 UploadFile
    일반DB: sqlalchemy, sqlite3
