---
layout: page
title: IT 전문가를 위한 프로젝트 매니지먼트
importance: 5
category: 실무 과정

# keep summary short for list page usage
summary:
  교육시간: 3일 21시간, 09:30~17:30
  교육장소: 한국생산성본부(서울 종로구 경복궁역 3번 출구)

schedule:
  - 2026.01.21(수) ~ 01.23(금) (서울)
  - 2026.03.11(수) ~ 03.13(금) (서울) - 근로자주도
  - 2026.05.20(수) ~ 05.22(금) (서울) - 근로자주도
  - 2026.06.17(수) ~ 06.19(금) (대전)
  - 2026.09.16(수) ~ 09.18(금) (서울) - 근로자주도
  - 2026.11.25(수) ~ 11.27(금) (서울) - 근로자주도

features:
  - "**PDU 제공**: PMI 자격 보유자(PMP 등)는 본 과정 참여 시 자격유지를 위한 21 PDUs를 제공받을 수 있습니다(Ways of Working 8 / Power Skills 5 / Business Acumen 8)."
  - "**PMBOK 기반 학습**: 전산(IT) 조직이 프로젝트를 자체 수행하거나 외부와 협업해 수행할 때 필요한 프로젝트 관리 요소를 학습하며, 과정의 기본 바탕은 PMBOK 기반으로 구성되어 있습니다."

targets:
  - "IT 관련 프로젝트를 수행(예정)하는 프로젝트 팀원 및 관리자"
  - "IT 프로젝트 발주/수주 등 전방위 핵심 이해관계자"
  - "IT 프로젝트 특성을 이해하고 관련 역량 향상을 원하는 프로젝트 실무 담당자"

content_summary:
  - "1일차: IT 프로젝트관리 이해(프로젝트 특성/성공·실패 요인/제약조건) + IT 프로젝트 Life Cycle(워터폴/애자일) + 범위관리(요구사항 관리, WBS 작성)"
  - "2일차: 일정 수립(네트워크 다이어그램, Critical Path, 일정 단축, Critical Chain) + IT 프로젝트 품질관리(품질계획, 검사, 관리도 등)"
  - "3일차: 위험관리(계획수립, 정성·정량 분석, 대응계획, 통제/보고) + 프로젝트 팀 구성 및 관리 방법"
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
