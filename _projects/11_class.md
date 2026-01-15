---
layout: page
title: Agile 기반의 프로젝트 관리 전문가 (PMI-ACP)
importance: 11
category: 자격대비 과정

# keep summary short for list page usage
summary:
  교육시간: 3일 21시간, 09:30~17:30
  교육장소: 한국생산성본부(서울 종로구 경복궁역 3번 출구)

schedule:
  - 2026.04.06(월) ~ 04.08(수) (서울) - 근로자주도
  - 2026.08.31(월) ~ 09.02(수) (서울) - 근로자주도
  - 2026.12.09(수) ~ 12.11(금) (서울) - 근로자주도

features:
  - "**Agile Mindset 이해**: Agile Life Cycle의 역사 및 사고방식(Mindset)을 이해합니다."
  - "**이해관계자/역할 이해**: Agile 프로젝트 이해관계자별 책임과 역할을 이해하고, 프로젝트 진행 방법 및 고려사항을 학습합니다."
  - "**Practice/Tool 습득**: Agile 접근법의 주요 Practice 및 Tool & Technique를 습득합니다."
  - "**자격취득 지원**: Agile 프로젝트 관리 국제 자격인 PMI-ACP 자격취득 지원을 포함합니다."
  - "**PDU 제공**: PDU 등록을 위한 영문수료증 발행(교육 + 개별 추가 학습 포함 28 PDUs: Ways of Working 10 / Power Skills 10 / Business Acumen 8)."

targets:
  - "Agile 방법론으로 업무를 수행하는 프로젝트 팀원"
  - "Agile 방법론을 업무에 도입하고자 하는 실무진"
  - "PMI-ACP 자격증을 취득하고자 하는 분"

content_summary:
  - "1일차: [Phase 00] PMI-ACP 시험 소개(자격/등록, 교재·학습 방법, ECO 소개) → [Phase 01] Mindset(Agile mindset, 협업 환경, 투명성, 심리적 안전, 피드백 루프, 변화 수용 등)"
  - "2일차: [Phase 02] Leadership(팀 강화, 문제 해결, 지식 공유, 공유 비전, 갈등 관리 등) → [Phase 03] Product(백로그 정제, 증분 관리, 작업 시각화, 가치 제공 관리)"
  - "3일차: [Phase 04] Delivery(조기 피드백, 지표 관리, 장애물/리스크, 낭비 제거, 지속 개선, 고객 참여, 흐름 최적화) → [Phase 05] 과정 정리 및 기출문제 풀이"
---
<div class="cv">
  <div class="card mt-3 p-3">
    <table class="table table-cv table-sm table-borderless table-responsive table-cv-map mb-0">
      {% for item in page.summary %}
        <tr>
          <td class="p-1 pr-2 font-weight-bold cv-key">
            <b>{{ item[0] }}</b>
          </td>
          <td class="p-1 pl-2 font-weight-light text cv-val">
            {{ item[1] }}
          </td>
        </tr>
      {% endfor %}

      <tr>
        <td class="p-1 pr-2 font-weight-bold cv-key"><b>교육일정</b></td>
        <td class="p-1 pl-2 font-weight-light text cv-val">
          <ul class="cv-ul">
            {% for item in page.schedule %}
              <li>{{ item }}</li>
            {% endfor %}
          </ul>
        </td>
      </tr>
    </table>
  </div>
</div>

<hr class="my-4" />

<h3>교육목적/특징</h3>
<ul>
  {% for line in page.features %}
    <li>{{ line | markdownify }}</li>
  {% endfor %}
</ul>

<h3>교육대상</h3>
<ul>
  {% for line in page.targets %}
    <li>{{ line }}</li>
  {% endfor %}
</ul>

<h3>교육내용(요약)</h3>
<ul>
  {% for line in page.content_summary %}
    <li>{{ line | markdownify }}</li>
  {% endfor %}
</ul>
