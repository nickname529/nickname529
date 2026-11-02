# 김지성 · Jisung Kim

**이야기를 기획하고, 도구로 구현하며, 결과를 검토합니다.**  
**Narrative thinking · AI-assisted prototyping · Evidence-based evaluation**

의공학을 전공하며 소설과 게임을 기획하고, AI의 도움을 받아 연구 도구와 데이터 분석 프로젝트를 만들고 있습니다. 이곳에는 어떤 문제를 다뤘고, 무엇을 확인했으며, 아직 해결하지 못한 점은 무엇인지 정리했습니다.

I study biomedical engineering and explore fiction, game concepts, research tools and data analysis. This profile brings together public work that makes the problem, evaluation criteria, review process and limitations inspectable.

[Portfolio / 홈페이지](https://portfolio.webbe-b.com/) · [한국어 홈페이지](https://portfolio.webbe-b.com/?lang=ko) · [Résumé / 이력서](https://portfolio.webbe-b.com/resume.html?lang=ko) · [Contact / 연락](https://portfolio.webbe-b.com/?lang=ko#contact)

**빠르게 살펴보기:** [창작·기획](https://portfolio.webbe-b.com/?lang=ko#creative-practice) → [RATRO 개발 과정](https://portfolio.webbe-b.com/?lang=ko#ratro-development) → 아래 공개 분석의 결과·검증 기록

## 창작과 기획 / Narrative & creative practice

- **장편소설 기획·개고:** 인물과 장면이 전체 흐름에 맞는지, 설정에 모순이 없는지 살피며 원고를 고칩니다. 시놉시스와 작품 소개 등 투고 자료도 준비합니다. AI의 도움을 받은 부분과 제가 직접 선택하고 고친 부분을 구분합니다. 진행 중인 작업이며 출판·계약·외부 감수 완료를 성과로 내세우지 않습니다.
- **게임 콘셉트·세계관 설계:** 플레이 방식과 이야기·세계관이 어우러지도록 기획합니다. 현재 기획 단계의 작업이며, 구현하거나 정식 출시한 게임으로 소개하지 않습니다.

I work on long-form fiction planning and revision, narrative consistency, and submission materials, alongside game concepts and worldbuilding. AI-assisted drafting and review are distinct from human decisions and revision. These are works in progress, not claims of publication, completed external review or released games. Unpublished manuscripts remain private.

## 공개 프로젝트 / Selected public work

### [SECOM Quality Analysis](https://github.com/nickname529/secom-quality-analysis)

**분석 완료 · 공개 v1 결과 Frozen / Analysis complete · public v1 frozen**

공개 UCI SECOM 데이터의 불균형 분류를 분석하고, 정확도보다 불량 누락과 오탐의 관계를 살폈습니다. 잠금 테스트에서 FAIL **21건 중 17건**을 찾는 설정은 정상 표본 **145건을 오탐**했습니다. 시간순으로 데이터를 나눴을 때는 성능이 낮아졌습니다.

A reproducible study of imbalanced classification on public manufacturing data. The recall-focused setting captured **17 of 21 failures with 145 false positives**; temporal sensitivity exposed weaker generalization. This is a portfolio experiment, not a deployed manufacturing system or a causal finding.

[결과표 / Results](https://github.com/nickname529/secom-quality-analysis/blob/main/results/tables/test_metrics.csv) · [Notebook](https://github.com/nickname529/secom-quality-analysis/blob/main/notebooks/secom_quality_analysis.ipynb) · [AI 사용 기록 / AI usage](https://github.com/nickname529/secom-quality-analysis/blob/main/docs/AI_USAGE.md)

### [Semiconductor Quality Decision Lab](https://github.com/nickname529/semiconductor-quality-decision-lab)

**분석 파이프라인 검증 기록 있음 · 해석 Draft / Pipeline validation documented · interpretation Draft**

검토 용량이 제한될 때 무엇을 먼저 확인하고 무엇을 놓치는지 평가했습니다. 시간순 테스트 314건에서 상위 20%인 **62건을 검토해 FAIL 17건 중 3건**을 포착했습니다. 동일 용량 무작위 검토 기대값 **3.36건**보다 낮아 실무 우위를 입증하지 못했습니다.

A chronological evaluation of limited review capacity. Reviewing the top **62 of 314 samples captured 3 of 17 failures**, below the equal-capacity random expectation of **3.36**. The value is in a transparent evaluation and its limits; operational benefit has not been established.

[결과표 / Results](https://github.com/nickname529/semiconductor-quality-decision-lab/blob/main/results/baseline/decision_metrics.csv) · [분석 규칙 / Protocol](https://github.com/nickname529/semiconductor-quality-decision-lab/blob/main/docs/ANALYSIS_PROTOCOL.md) · [AI 사용 기록 / AI usage](https://github.com/nickname529/semiconductor-quality-decision-lab/blob/main/docs/AI_USAGE.md)

## 연구와 개발 / Research & development

학부연구생으로 활동하며 움직임을 관찰하고 분석하는 도구 **RATRO**를 개발하고 있습니다. AI를 활용해 관찰 기록, 3D 보기, 분석 기능을 연결합니다. 공개 데모는 설명용 참조 동작이며, 해부학·물리적 타당성이 검증된 디지털 트윈은 아닙니다. 연구 저장소와 자료는 비공개입니다.

**개발 과정:** 기록·3D 보기·타임라인 기반 구축 → 마커·그래프·결과 저장 및 출처 확인 → 원본 모델 실행 점검 → 근육 관련 수식·경로 계산의 개별 검증. **2026-11-02 확인 기록 기준, 과학적 채택을 위해 개별 기능과 계산 근거를 검증하는 단계입니다.**

[개발 과정과 현재 단계 / Development history](https://portfolio.webbe-b.com/?lang=ko#ratro-development) · [참조 동작 데모 / Reference-motion demo](https://portfolio.webbe-b.com/#ratro)

Development has progressed from records and a 3D viewer to analysis tools, source checks and bounded numerical verification. As of the records reviewed on 2 November 2026, component verification is ongoing and scientific adoption remains pending.

Through undergraduate research, I explore research software and visualization. **RATRO** is an AI-assisted prototype for exploring movement. Reference-motion visualization is distinct from scientific validation; it is not presented as a validated anatomical or physical digital twin. Research repositories and materials remain private.

## 작업 방식 / How I work

- 문제와 검토 기준을 먼저 정하고, 결과와 해석을 구분합니다.
- AI가 보조한 구현·문서화 범위를 공개하고, 실패 사례와 미검증 사항을 함께 기록합니다.
- 제가 맡은 문제 정의와 검토 과정, AI를 활용한 구현 범위를 함께 설명합니다. 실제 출시·운영 성과는 확인된 경우에만 기록합니다.

I define the question and review criteria, separate results from interpretation, disclose AI assistance, and document failures and unresolved checks. Public code is not a claim that every line was independently authored or that a product has launched.

*Updated 2026-11-02 · 공개 가능한 근거 중심으로 구성 / Based on evidence suitable for public disclosure.*
