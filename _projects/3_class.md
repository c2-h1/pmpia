---
layout: page
title: Agile 프로젝트 관리 실무
importance: 3
category: 실무 과정

# keep summary short for list page usage
summary:
  교육시간: 3일 21시간, 09:30~17:30
  교육장소: 한국생산성본부(서울 종로구 경복궁역 3번 출구)

schedule:
  - 2026.02.02(월) ~ 02.04(수) (서울)
  - 2026.03.30(월) ~ 04.01(수) (서울)
  - 2026.07.27(월) ~ 07.29(수) (서울)
  - 2026.08.31(월) ~ 09.02(수) (서울)
  - 2026.11.09(월) ~ 11.11(수) (서울)

features:
  - "**PDU 제공**: PMI 자격 보유자(PMP 등)는 본 과정 참여 시 21 PDUs를 제공받을 수 있습니다(Ways of Working 11 / Power Skills 5 / Business Acumen 5)."
  - "**애자일 가치 이해**: 애자일이 산업 전반으로 확산된 배경과 프로젝트 관리 관점의 의미를 이해하고, 고객 가치 조기 실현·생산성·품질 관점의 실천방법을 학습합니다."
  - "**주요 실천방안 습득**: 애자일의 철학/가치/원칙을 기반으로 스크럼·XP·칸반 등 주요 실천방안을 익히고, 역할·팀 운영 방식(Self-organizing/Self-management) 관점을 함께 다룹니다."

targets:
  - "프로젝트 관리자, 팀 리더, 스폰서, 비즈니스 분석가, 개발자/설계자/테스터 등 프로젝트 참여 전 구성원"
  - "IT/소프트웨어에 국한하지 않고 애자일 실천방안을 익히고자 하는 전 산업 종사자"

content_summary:
  - "1일차: Agile 개요(전통적 PM의 한계) / Agile 사고방식·가치·원칙(Manifesto) / 수명주기(Lifecycle) / Agile 팀 구성과 역할(PO, PM, 개발자 등)"
  - "2일차: Agile 프로젝트 환경 조성(DoR/DoD) / 프로젝트 계획(비전·목표·로드맵) / 추정(스토리·스토리포인트·플래닝포커) / 수행(백로그·릴리즈·이터레이션·데일리·회고)"
  - "3일차: 측정(번다운/번업, Agile EVM) / 도입(조직 변화관리, CoE, PMO) / 주요 프랙티스(스크럼·칸반·XP, 확장형 모델)"
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
