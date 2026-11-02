# 김지성 · Jisung Kim

**서사와 아이디어를 구조화하고, AI와 함께 구현하며, 근거로 검토합니다.**  
**Narrative thinking · AI-assisted prototyping · Evidence-based evaluation**

의공학을 공부하며 소설·게임 기획, 연구 도구, 데이터 분석을 탐구합니다. 이 GitHub에서는 공개 가능한 코드와 분석 결과를 통해 문제 정의, 평가 기준, 검토 과정과 한계를 보여드립니다.

I study biomedical engineering and explore fiction, game concepts, research tools and data analysis. This profile brings together public work that makes the problem, evaluation criteria, review process and limitations inspectable.

## 창작과 기획 / Narrative & creative practice

- **장편소설 기획·개고:** 인물과 장면의 기능, 전체 구조, 설정의 일관성을 검토하고 시놉시스·작품 소개 등 투고 준비 자료를 구성합니다. AI 보조 초안·검토와 사람의 선택·개고를 구분하며, 출판·계약·외부 감수 완료 실적으로 소개하지 않습니다.
- **게임 콘셉트·세계관 설계:** 플레이 경험과 서사 규칙을 연결하는 기획을 탐구합니다. 기획 문서와 구현·정식 출시를 구분합니다.

I work on long-form fiction planning and revision, narrative consistency, and submission materials, alongside game concepts and worldbuilding. AI-assisted drafting and review are distinct from human decisions and revision. These are works in progress, not claims of publication, completed external review or released games. Unpublished manuscripts remain private.

## 공개 프로젝트 / Selected public work

### [SECOM Quality Analysis](https://github.com/nickname529/secom-quality-analysis)

**분석 완료 · 공개 v1 결과 Frozen / Analysis complete · public v1 frozen**

공개 UCI SECOM 데이터의 불균형 분류를 분석하고, 정확도보다 불량 누락과 오탐의 관계를 살폈습니다. 잠금 테스트에서 FAIL **21건 중 17건**을 찾는 설정은 정상 표본 **145건을 오탐**했습니다. 시간순 민감도에서는 결과가 약화됐습니다.

A reproducible study of imbalanced classification on public manufacturing data. The recall-focused setting captured **17 of 21 failures with 145 false positives**; temporal sensitivity exposed weaker generalization. This is a portfolio experiment, not a deployed manufacturing system or a causal finding.

[결과표 / Results](https://github.com/nickname529/secom-quality-analysis/blob/main/results/tables/test_metrics.csv) · [Notebook](https://github.com/nickname529/secom-quality-analysis/blob/main/notebooks/secom_quality_analysis.ipynb) · [AI 사용 기록 / AI usage](https://github.com/nickname529/secom-quality-analysis/blob/main/docs/AI_USAGE.md)

### [Semiconductor Quality Decision Lab](https://github.com/nickname529/semiconductor-quality-decision-lab)

**분석 파이프라인 검증 기록 있음 · 해석 Draft / Pipeline validation documented · interpretation Draft**

검토 용량이 제한될 때 무엇을 먼저 확인하고 무엇을 놓치는지 평가했습니다. 시간순 테스트 314건에서 상위 20%인 **62건을 검토해 FAIL 17건 중 3건**을 포착했습니다. 동일 용량 무작위 검토 기대값 **3.36건**보다 낮아 실무 우위를 입증하지 못했습니다.

A chronological evaluation of limited review capacity. Reviewing the top **62 of 314 samples captured 3 of 17 failures**, below the equal-capacity random expectation of **3.36**. The value is in a transparent evaluation and its limits; operational benefit has not been established.

[결과표 / Results](https://github.com/nickname529/semiconductor-quality-decision-lab/blob/main/results/baseline/decision_metrics.csv) · [분석 규칙 / Protocol](https://github.com/nickname529/semiconductor-quality-decision-lab/blob/main/docs/ANALYSIS_PROTOCOL.md) · [AI 사용 기록 / AI usage](https://github.com/nickname529/semiconductor-quality-decision-lab/blob/main/docs/AI_USAGE.md)

## 연구와 개발 / Research & development

학부연구에 참여하며 연구 소프트웨어와 시각화를 탐구합니다. **RATRO**는 움직임을 살펴보는 AI 보조 연구 도구 프로토타입입니다. 참조 동작 시각화와 과학적 검증을 구분하며, 검증된 해부학·물리 디지털 트윈이라고 주장하지 않습니다. 연구 저장소와 자료는 비공개로 유지합니다.

Through undergraduate research, I explore research software and visualization. **RATRO** is an AI-assisted prototype for exploring movement. Reference-motion visualization is distinct from scientific validation; it is not presented as a validated anatomical or physical digital twin. Research repositories and materials remain private.

## 작업 방식 / How I work

- 문제와 검토 기준을 먼저 정하고, 결과와 해석을 구분합니다.
- AI가 보조한 구현·문서화 범위를 공개하고, 실패 사례와 미검증 사항을 함께 기록합니다.
- 공개 코드의 존재를 독립적인 전체 구현 능력, 출시 실적 또는 사업 성과와 동일시하지 않습니다.

I define the question and review criteria, separate results from interpretation, disclose AI assistance, and document failures and unresolved checks. Public code is not a claim that every line was independently authored or that a product has launched.

*Updated 2026-11-02 · 공개 가능한 근거 중심으로 구성 / Based on evidence suitable for public disclosure.*
