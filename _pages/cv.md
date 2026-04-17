---
layout: page  # ★ cv 대신 page로 변경하여 테마 기본 레이아웃을 피합니다.
permalink: /cv/
title: CV
nav: true
nav_order: 4
---

<div class="post">
  <article>
    <div class="cv">
      <div class="card mt-3 p-3">
        <object data="{{ '/assets/pdf/CV.pdf' | relative_url }}" type="application/pdf" width="100%" height="1000px">
          <p>이 브라우저는 PDF 뷰어를 지원하지 않습니다. <a href="{{ '/assets/pdf/Sihyeong_Yeom_CV.pdf' | relative_url }}">여기에서 PDF를 다운로드하세요.</a></p>
        </object>
      </div>
    </div>
  </article>
</div>
