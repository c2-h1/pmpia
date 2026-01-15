---
layout: page
title: 프로젝트 품질관리 전문가
importance: 7
category: 실무 과정

# keep summary short for list page usage
summary:
  교육시간: 2일 14시간, 09:30~17:30
  교육장소: 한국생산성본부(서울 종로구 경복궁역 3번 출구)

schedule:
  - 2026.05.18(월) ~ 05.19(화) (서울) - 근로자주도
  - 2026.09.07(월) ~ 09.08(화) (서울) - 근로자주도
  - 2026.12.07(월) ~ 12.08(화) (서울) - 근로자주도

features:
  - "**PDU 제공**: PMI 자격 보유자는 본 과정 참여 시 자격유지를 위한 14 PDUs를 취득할 수 있습니다(Ways of Working 7 / Power Skills 0 / Business Acumen 7)."
  - "**품질관리 역할 구체화**: 프로젝트 품질관리의 의미와 현업 적용 방법을 학습하고, 프로젝트 라이프사이클 단계별로 QAO 역할을 구체화합니다."
  - "**품질관리 실전 적용**: 업무범위 관리·리스크 관리·개발방법론을 모듈로 이해하고, 효율적/효과적 품질관리를 위한 위험·일정관리 방법을 다룹니다."

targets:
  - "기업체 프로젝트 관리를 담당하는 PM/PL 및 팀원"
  - "프로젝트에서 품질을 관리·분석하는 실무 담당자"
  - "프로젝트 관리자 또는 프로젝트 이해관계자"

content_summary:
  - "1일차: 프로젝트관리 개요(Project Life Cycle) → 프로젝트 품질과 업무범위(범위관리, WBS, PMO & 방법론) → 품질 개요(품질 정의/품질관리, CMMI) → 프로젝트 품질관리(Quality Planning/Control/Assurance)"
  - "2일차: QAO의 책임과 역할(단계별 수행체계, 품질보증계획서) → 프로젝트 품질과 리스크(식별, 정성적 분석 등) → 프로젝트 품질과 일정(일정 수립, CPM)"
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
