---
layout: page
title: 성공적인 PMO 구축 및 운영 실무
importance: 2
category: 실무 과정

# keep summary short for list page usage
summary:
  교육시간: 2일 14시간, 09:30~17:30
  교육장소: 한국생산성본부(서울 종로구 경복궁역 3번 출구)

schedule:
  - 2026.02.05(목) ~ 02.06(금)
  - 2026.04.02(목) ~ 04.03(금)
  - 2026.07.30(목) ~ 07.31(금)
  - 2026.09.03(목) ~ 09.04(금)
  - 2026.11.12(목) ~ 11.13(금)

features:
  - "**PDU 제공**: PMI 자격 보유자는 본 과정 참여 시 자격유지를 위한 14 PDUs를 취득할 수 있습니다(Ways of Working 7 / Power Skills 0 / Business Acumen 7)."
  - "**최신 동향/실패 원인 분석**: 프로젝트 관리 최신 동향과 주요 실패 원인을 분석하고, PMO의 필요성을 이해합니다."
  - "**PMO 기능·유형 이해**: PMO의 기능·유형을 이해하고, 조직/프로젝트 환경에 맞는 PMO 유형을 판단할 수 있도록 합니다."
  - "**OPM 핵심 개념**: 전사적 프로젝트 관리(OPM) 관점에서 포트폴리오·프로그램·프로젝트 관리 핵심 개념을 이해합니다."
  - "**PMO 성숙도/역량 이해**: PMO 성숙도(발전 과정/성숙도 레벨)와 PMO 전문 인력의 역할·역량을 이해하고, PMO 실패 요인과 극복 방안까지 다룹니다."

targets:
  - "PMO 조직에서 담당업무를 수행하는 전문 인력"
  - "프로젝트/프로그램/포트폴리오 관리 관련 업무 수행 인력"
  - "전사적 관점에서 프로젝트 관리를 수행하는 인력"

content_summary:
  - "1일차: PMO 조직의 이해(최신 동향/필요성, 기능·유형) → PMO 구축 및 운영(성숙도와 발전 방향, PMO 인력 역할·역량, 구축·운영 접근 방법)"
  - "2일차: PMO 조직 관리 기술(PM 핵심 기술: WBS, EVM, Critical Path, Risk Management 등) → 전사적 프로젝트 관리(OPM, 프로젝트·프로그램·포트폴리오 관리, PMO 실패 10가지 이유와 극복 방안, PMO 운영 글로벌 통계)"
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
    <li>{{ line }}</li>
  {% endfor %}
</ul>
