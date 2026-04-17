---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 4
cv_pdf: /assets/pdf/CV_SihyeongYeom.pdf # ★ 업로드하신 실제 파일명으로 수정하세요.
description: 
---

<div class="post">
  <header class="post-header">
    <h1 class="post-title">{{ page.title }}</h1>
    <p class="post-description">{{ page.description }}</p>
  </header>

  <article>
    <div class="cv">
      <div class="card mt-3 p-3">
        <object data="{{ '/assets/pdf/CV.pdf' | relative_url }}" type="application/pdf" width="100%" height="1000px">
          <p>이 브라우저는 PDF 뷰어를 지원하지 않습니다. <a href="{{ '/assets/pdf/CV_SihyeongYeom.pdf' | relative_url }}">여기에서 PDF를 다운로드하세요.</a></p>
        </object>
      </div>
    </div>
  </article>
</div>
