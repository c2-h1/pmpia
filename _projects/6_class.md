---
layout: page
title: 프로젝트 관리자 리더십 향상
importance: 6
category: 실무 과정

# keep summary short for list page usage
summary:
  교육시간: 2일 14시간, 09:30~17:30
  교육장소: 한국생산성본부(서울 종로구 경복궁역 3번 출구)

schedule:
  - 2026.01.19(월) ~ 01.20(화) (서울)
  - 2026.03.09(월) ~ 03.10(화) (서울) - 근로자주도
  - 2026.06.11(목) ~ 06.12(금) (서울) - 근로자주도
  - 2026.09.03(목) ~ 09.04(금) (서울) - 근로자주도
  - 2026.11.19(목) ~ 11.20(금) (서울) - 근로자주도
  - 2026.12.21(월) ~ 12.22(화) (서울) - 근로자주도

features:
  - "**PDU 제공**: PMI 자격 보유자(PMP 등)는 본 과정 참여 시 14 PDUs를 제공받을 수 있습니다(Ways of Working 0 / Power Skills 7 / Business Acumen 7)."
  - "**리더십 모델 이해**: 리더십과 관리를 구분하고 리더십 모델을 이해하여 프로젝트 상황에 적용할 수 있습니다."
  - "**이해당사자/정치 논리 관리**: 프로젝트 이해당사자와 정치 논리를 이해하고 이를 효과적으로 관리할 수 있습니다."
  - "**동기부여/갈등관리**: 동기유발 및 갈등관리 기법을 이해하여 프로젝트 인력관리에 적용할 수 있습니다."

targets:
  - "프로젝트 관리자 또는 조직관리자로서 리더십과 인력관리 역량을 강화하고자 하는 분"
  - "프로젝트의 정치적 관계를 이해하고 이를 조직적으로 관리하고자 하는 분"
  - "프로젝트 팀원을 동기유발하고 이해당사자를 효과적으로 관리하고자 하는 분"

content_summary:
  - "1일차: 프로젝트 관리 개요(프로젝트/제약조건/성공·실패 요인/PM 역량) → 프로젝트 라이프사이클 이해 → 요구사항관리 및 WBS(정의·사례·Lessons Learned)"
  - "2일차: 리더십 개요(리더십 이론 전개, 상황적 리더십, 슈퍼/셀프 리더십, 자가진단, 관리자의 Power) → 프로젝트 조직과 리더십(팀 빌딩/강력한 팀 구성) → 리더십의 법칙(21가지 법칙)"
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
