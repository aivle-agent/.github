제공해주신 템플릿 양식에 맞춰 **"국민제안 도우미 AGENT 서비스"** (팀명: 프롬프트 중독자들)의 내용을 작성해 드립니다.

이미지 URL, 깃허브 링크 등 `[]`로 표시된 부분만 실제 프로젝트 정보로 교체하시면 바로 사용하실 수 있습니다.

---

# <img src="[프로젝트 로고 이미지 URL]" style="height: 1em; vertical-align: middle;"> National Proposal Assistant Agent (국민제안 도우미)

![메인 배너 이미지]([메인 배너 이미지 URL])


## ⭐ 서비스 소개
<div align="left">
<img src="[서비스 소개용 작은 이미지 URL]" width=200>

> **개발 기간:** 2025. XX ~ 2025. XX
> 
> **팀명:** 프롬프트 중독자들
>
> **배포 주소 :** [배포된 서비스 URL]

<h3><b>"채택률 0.45%의 벽을 넘어, 국민의 목소리를 실제 정책으로"</b></h3>

<p>
<b>"내 제안은 왜 항상 채택되지 않을까요?"</b> <br/>
많은 국민이 지역사회 문제를 해결하기 위해 '국민신문고'에 제안을 올리지만, <b>낮은 채택률(약 0.45%)</b>로 인해 실제 정책 변화로 이어지기 어렵습니다. 제안 내용의 구조적 미흡, 정책 용어의 부재, 기존 법령과의 중복성 등이 그 원인입니다.

**국민제안 도우미 AGENT**는 생성형 AI를 활용하여 일반 국민의 막연한 민원을 **'채택 가능한 수준의 정책 제안서'로 교정**해주고, 법령과 판례를 기반으로 **'예상 행정 답변'**을 미리 제공하는 AI 서비스입니다. 이를 통해 국민의 효능감을 높이고, 행정관의 불필요한 검토 업무를 줄여 실질적인 사회 문제 해결을 돕습니다.

<br/>

**"1. AI 질문 교정 (Question Correction)"** <br/>
비전문적인 국민의 제안을 명확성, 구체성, 사실성 등을 기준으로 분석하고, **RandomForest와 SHAP 알고리즘**을 활용해 행정 용어와 구조를 갖춘 제안서로 재작성(Refining)합니다. <br/>

**"2. RAG 기반 예상 답변 (Expected Answer)"** <br/>
약 7만 건의 법제처 해석례와 행정 데이터를 학습한 RAG(검색 증강 생성) 시스템을 통해, 제안 제출 시 **행정기관이 보낼 것으로 예상되는 답변**과 법적 근거를 미리 확인할 수 있습니다. <br/>

**"3. 업무 효율화 및 채택률 제고"** <br/>
중복되거나 실현 불가능한 제안을 사전에 필터링하여 **행정 담당자의 검토 시간을 단축**하고, 국민에게는 제안의 **질적 향상 가이드라인**을 제공합니다. <br/>


<h3>단순 민원 처리에서 벗어나, 함께 만드는 정책의 시작을 돕습니다.</h3>
</p>
</div>

## 🤝 팀원 소개: 프롬프트 중독자들

### AI & Modeling (핵심 기능 구현)

<table>
  <tr>
    <!-- 팀원 1 -->
    <td align="center"><img src="[팀원1 프로필 이미지 URL]" width="160" height="160"></td>
    <!-- 팀원 2 -->
    <td align="center"><img src="[팀원2 프로필 이미지 URL]" width="160" height="160"></td>
  </tr>
  <tr>
    <td align="center"><a href="[팀원1 깃허브 링크]">[팀원1 이름]</td>
    <td align="center"><a href="[팀원2 깃허브 링크]">[팀원2 이름]</td>
  </tr>
    <tr>
    <td align="center">질문 교정 Agent 모델링<br>(RF & SHAP)</td>
    <td align="center">예상 답변 RAG 구축<br>(Vector DB & Retrieval)</td>
  </tr>
</table>

### Backend & Data Pipeline

<table>
  <tr>
    <td align="center"><img src="[팀원3 프로필 이미지 URL]" width="160"></td>
    <td align="center"><img src="[팀원4 프로필 이미지 URL]" width="160"></td>
  </tr>
  <tr>
    <td align="center"><a href="[팀원3 깃허브 링크]">[팀원3 이름]</td>
    <td align="center"><a href="[팀원4 깃허브 링크]">[팀원4 이름]</td>
  </tr>
    <tr>
    <td align="center">LangGraph 워크플로우 설계</td>
    <td align="center">데이터 전처리 및<br>Bandit 알고리즘 구현</td>
  </tr>
</table>

### Frontend & Project Management

<table>
  <tr>
    <td align="center"><img src="[팀원5 프로필 이미지 URL]" width="160"></td>
    <td align="center"><img src="[팀원6 프로필 이미지 URL]" width="160"></td>
    <!-- 필요시 td 추가 -->
  </tr>
  <tr>
    <td align="center"><a href="[팀원5 깃허브 링크]">[팀원5 이름]</td>
    <td align="center"><a href="[팀원6 깃허브 링크]">[팀원6 이름]</td>
  </tr>
  <tr>
    <td align="center">UI/UX 개발 & 디자인</td>
    <td align="center">기획 & PM</td>
  </tr>
</table>

## 🤖 주요 기능

- **AI 제안서 교정 (Proposal Correction)**  
    - 사용자의 민원 텍스트를 입력받아 명확성, 구체성, 법률적 타당성 점수를 산출합니다.
    - `Qwen2.5-3B-Instruct` 모델을 통해 비구조화된 텍스트를 공공기관 양식에 맞는 구조화된 제안서로 변환합니다.
 
- **예상 답변 및 법령 매칭 (Expected Answer & Legal Matching)**
    - `kanana_nano_2.1b` 임베딩 모델과 Chroma DB를 활용하여 유사한 과거 민원 사례와 법령을 검색합니다.
    - 제안 내용에 대해 관계 법령에 의거한 승인/반려 가능성과 구체적인 사유(예상 답변)를 생성합니다.

- **자가 진단 및 가이드라인 제공 (Self-Diagnosis)**
    - 사용자가 제출 전 중복 제안 여부를 스스로 판단할 수 있도록 돕습니다.
    - 제안이 반려될 가능성이 높을 경우, 보완해야 할 구체적인 가이드라인(키워드, 근거 데이터 등)을 제시합니다.

## 💻 화면

<table align="center" style="border-collapse: collapse; width: 100%; max-width: 1200px; margin: 20px auto;">
    <tr>
        <td align="center" style="width: 50%; padding: 10px;">
            <img src="[화면 이미지 1 URL]" alt="메인 제안 작성 화면" style="width: 100%; max-width: 500px;">
            <p align="center"><strong>1. 제안 내용 작성 및 AI 분석 요청</strong></p>
        </td>
        <td align="center" style="width: 50%; padding: 10px;">
            <img src="[화면 이미지 2 URL]" alt="질문 교정 결과 화면" style="width: 100%; max-width: 500px;">
            <p align="center"><strong>2. AI가 교정한 구조화된 제안서 확인</strong></p>
        </td>
    </tr>
    <tr>
        <td align="center" style="width: 50%; padding: 10px;">
            <img src="[화면 이미지 3 URL]" alt="예상 답변 결과 화면" style="width: 100%; max-width: 500px;">
            <p align="center"><strong>3. 관련 법령 기반 예상 답변 출력</strong></p>
        </td>
        <td align="center" style="width: 50%; padding: 10px;">
            <img src="[화면 이미지 4 URL]" alt="최종 제출 화면" style="width: 100%; max-width: 500px;">
            <p align="center"><strong>4. 처리 기관 선택 및 최종 제출</strong></p>
        </td>
    </tr>
</table>


## ⚙️ 아키텍처 구조
<table align="center" style="border-collapse: collapse; width: 100%; max-width: 1200px; margin: 20px auto;">
    <tr>
        <td colspan="2" align="center" style="padding: 10px;">
            <img src="[전체 아키텍처 이미지 URL]" alt="Service Workflow" style="width: 90%; max-width: 900px;">
        </td>
    </tr>
    <tr>
        <td colspan="2" align="center" style="padding: 10px;">
            <strong>전체 서비스 워크플로우 (LangGraph Workflow)</strong>
        </td>
    </tr>
    <tr>
        <td align="center" style="padding: 10px;">
            <img src="[서브 아키텍처 1 URL]" alt="질문 교정 파이프라인" style="width: 500px; max-width: 500px;">
        </td>
        <td align="center" style="padding: 10px;">
            <img src="[서브 아키텍처 2 URL]" alt="RAG 답변 생성 파이프라인" style="width: 500px; max-width: 500px;">
        </td>
    </tr>
    <tr>
        <td align="center" style="padding: 10px;">
            <strong>질문 교정 파이프라인 (RF + SHAP)</strong><br>
            민원 평가 및 재작성 로직
        </td>
        <td align="center" style="padding: 10px;">
            <strong>예상 답변 생성 파이프라인 (RAG)</strong><br>
            법제처 데이터 기반 검색 및 답변 생성
        </td>
    </tr>
</table>

## 🛠️ 기술 스택

### Frontend (Example)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
<!-- 프론트엔드 스택에 맞게 수정 필요 -->

### Backend & AI Server
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)

### AI Model & Data
![Qwen2.5](https://img.shields.io/badge/Qwen2.5-Model-blue?style=flat)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
<!-- Kanana, RF, SHAP 관련 커스텀 배지 사용 가능 -->

### DB & Infra
![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector_DB-orange?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

### Collaboration Tool
![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat&logo=discord&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
