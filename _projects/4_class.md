---
layout: page
title: 슬기로운 PM 생활 (프로젝트를 성공으로 이끄는 지혜)
importance: 4
category: 실무 과정

# keep summary short for list page usage
summary:
  교육시간: 2일 14시간, 09:30~17:30
  교육장소: 한국생산성본부(서울 종로구 경복궁역 3번 출구)

schedule:
  - 2026.03.19(목) ~ 03.20(금)
  - 2026.06.18(목) ~ 06.19(금)
  - 2026.09.14(월) ~ 09.15(화)
  - 2026.12.17(목) ~ 12.18(금)

features:
  - "**PDU 제공**: PMI 자격 보유자(PMP 등)는 본 과정 참여 시 14 PDUs를 제공받을 수 있습니다(Ways of Working 6 / Power Skills 6 / Business Acumen 2)."
  - "**프로젝트 관리의 지혜**: 프로젝트 수행에 필요한 지식뿐 아니라, 시행착오를 줄이기 위한 프로젝트 관리의 ‘지혜’를 중심으로 학습합니다."
  - "**실전 대응 전략**: 좋은/나쁜 프로젝트를 구분하고, 낭비를 줄이며, 요구사항·이해관계자·리스크·종료까지 실전 관점의 대응 전략을 다룹니다."

targets:
  - "프로젝트 관리 방법론에 대한 기본 지식을 학습한 분(권장)"
  - "실전에 적용 가능한 프로젝트 관리 방법이 궁금한 프로젝트 관리자 또는 상품관리자"
  - "프로젝트 관리 애로사항과 대응방법을 학습하고 싶은 프로젝트 관리자/이해관계자"

content_summary:
  - "1일차: 좋은/나쁜 프로젝트 구분 → 낭비를 줄이는 PM → 제약조건 기반 계획 수립(범위·일정·예산 트레이드오프) → 추정 불확실성 관리 → 실행력을 높이는 팀 관리"
  - "2일차: 요구사항 관리 핵심(변경 원인/예방/통제) → 이해관계자 협력을 이끄는 소통 → 프로젝트 위험관리 실전(성과지표/일정지연 대응/복구) → 프로젝트 종료를 위한 사전 준비"
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
