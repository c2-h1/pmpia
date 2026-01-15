---
layout: page
title: PMBOK기반의 프로젝트관리전문가(PMP)-주말
importance: 9
category: 자격대비 과정

# keep summary short for list page usage
summary:
  교육시간: 5일 40시간, 09:00~18:00
  교육장소: 한국생산성본부(서울 종로구 경복궁역 3번 출구)

schedule:
  - 2026.01.10(토) ~ 02.07(토) (서울)
  - 2026.03.07(토) ~ 04.04(토) (서울)
  - 2026.04.11(토) ~ 05.16(토) (서울)
  - 2026.05.30(토) ~ 07.04(토) (서울)
  - 2026.07.11(토) ~ 08.08(토) (서울)
  - 2026.08.22(토) ~ 09.19(토) (서울)
  - 2026.10.17(토) ~ 11.14(토) (서울)
  - 2026.11.21(토) ~ 12.19(토) (서울)

features:
  - "**PDU 제공**: PMI 자격 보유자(PMP 등)는 본 과정 참여 시 40 PDUs를 제공받을 수 있습니다(Ways of Working 24 / Power Skills 8 / Business Acumen 8)."
  - "**PMBOK 7판 집중 학습**: 프로젝트 관리 글로벌 표준인 PMBOK Guide(7판) 기반으로 프로젝트 관리 체계·프로세스와 시험 합격에 필요한 핵심 노하우를 집중적으로 학습합니다."
  - "**실무 적용 연결**: 자격 취득 목적뿐 아니라, 실제 프로젝트에서의 적용 방법·템플릿·가이드까지 함께 다뤄 실무 활용까지 연결합니다."

targets:
  - "PMP 자격증 취득을 희망하는 분"
  - "프로젝트 관리자/사업 관리자/Program Manager/PMO 등 프로젝트 관리 분야 종사자"
  - "프로젝트 관리 표준·체계·프로세스·기법을 집중적으로 학습하고자 하는 분"
  - "국제 자격을 통해 커리어 경쟁력(해외 프로젝트, 이직 등)을 강화하고자 하는 분"

content_summary:
  - "1일차: [PART 00] PMP 자격 소개(시험 구성, 응시조건, 합격기준, 신청 절차) → [PART 01 PM Standard] Introduction(핵심 용어·개념) / A System for Value Delivery(가치 창출, 거버넌스, 8 PM Functions) / Project Management Principles(12 PM Principles ①)"
  - "2일차: Project Management Principles(12 PM Principles ②) → [PART 02 PMBOK Guide] Introduction(PMBOK Guide 개요)"
  - "3일차: Project Performance Domains: Stakeholder / Team / Development Approach & Lifecycle → Planning / Project Work / Delivery 성과 영역 핵심 정리"
  - "4일차: Tailoring(프로젝트 상황별 적용·조정) → Models, Methods, and Artifacts(PM 모델·방법·산출물 체계)"
  - "5일차: [PART 03 Agile] Introduction(Agile 개요, Manifesto) → Creating Agile Environment(라이프사이클 선택, 팀 구성) → Delivering Agile Environment(주요 Practice, 조직 차원의 애자일 적용 고려사항)"
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
