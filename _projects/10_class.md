---
layout: page
title: "[1Day] KPC PMP 에센셜 핵심정리"
importance: 10
category: 자격대비 과정

# keep summary short for list page usage
summary:
  교육시간: 1일 8시간, 09:00~18:00
  교육장소: 한국생산성본부(서울 종로구 경복궁역 3번 출구)

schedule:
  - 2026.01.16(금)
  - 2026.02.13(금)
  - 2026.03.20(금)
  - 2026.04.17(금)
  - 2026.05.15(금)
  - 2026.06.19(금)
  - 2026.07.03(금)
  - 2026.08.07(금)
  - 2026.09.11(금)
  - 2026.10.16(금)
  - 2026.11.20(금)
  - 2026.12.11(금)

features:
  - "**실전 모의고사 중심**: 출제 예상 문제 기반의 실전 모의고사 + 해설 강의로 구성되어, PMP 시험 응시 대비에 집중합니다."
  - "**프로세스 적용 역량 강화**: PMBOK 프로세스 영역별 지식을 실제 문제 풀이에 적용하는 역량을 강화합니다."
  - "**참고**: 본 과정은 PDU 및 중식 제공이 없습니다."

targets:
  - "PMP 자격시험 응시 예정자"

content_summary:
  - "09:00~12:30: PMP 실전 모의고사"
  - "12:30~13:30: 중식(별도 제공 없음)"
  - "13:30~18:00: 모의고사 180제 해설 풀이(진도에 따라 종료시간 변동 가능)"
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
