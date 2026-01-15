---
layout: page
title: PM(Project Manager) 양성
importance: 1
category: 실무 과정

# keep summary short for list page usage
summary:
  교육시간: 4일 28시간, 09:30~17:30
  교육장소: 한국생산성본부 2층 205호

schedule:
  - 2026.01.12(월) ~ 01.15(목)
  - 2026.02.09(월) ~ 02.12(목)
  - 2026.03.16(월) ~ 03.19(목)
  - 2026.04.13(월) ~ 04.16(목)
  - 2026.05.11(월) ~ 05.14(목)
  - 2026.06.15(월) ~ 06.18(목)
  - 2026.07.13(월) ~ 07.16(목)
  - 2026.08.03(월) ~ 08.06(목)
  - 2026.09.07(월) ~ 09.10(목)
  - 2026.10.12(월) ~ 10.15(목)
  - 2026.11.16(월) ~ 11.19(목)
  - 2026.12.07(월) ~ 12.10(목)
  - 2026.12.21(월) ~ 12.24(목)

features:
  - "**PDU 제공**: PMI 자격 보유자(PMP 등)는 본 과정 참여 시 28 PDUs를 제공받을 수 있습니다(Ways of Working 12 / Power Skills 8 / Business Acumen 8)."
  - "**프로젝트 목표 설정**: 조직 전략과 프로젝트의 관계를 이해하고, 명확한 목표를 설정합니다."
  - "**계획 기법 이해/적용**: 한정된 자원·예산·기간 내 결과 창출을 위한 계획 기법을 이해하고 적용합니다."
  - "**리스크/이슈 대응**: 목표 달성에 영향을 주는 잠재 위험·이슈를 식별하고 대응 전략을 수립합니다."
  - "**성과 모니터링/정량 관리**: 프로젝트 성과를 모니터링하고 정량적으로 관리하는 방법을 습득·적용합니다."

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
