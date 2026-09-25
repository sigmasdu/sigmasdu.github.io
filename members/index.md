---
layout: article
title: 
key: page-members
---

<style>
.members-page {
  --members-rule: rgba(127, 127, 127, 0.28);
  --members-gap: clamp(1.25rem, 4vw, 2.75rem);
  letter-spacing: 0;
}

.members-page h2 {
  margin: 2.25rem 0 0.9rem;
  padding-bottom: 0.4rem;
  border-bottom: 1px solid var(--members-rule);
}

.members-page h2:first-child {
  margin-top: 0;
}

.members-page a {
  text-underline-offset: 0.16em;
}

.members-page .member-grid,
.members-page .advisor-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
}

.members-page .member-grid {
  gap: 0.35rem var(--members-gap);
}

.members-page ul.member-grid,
.members-page .plain-list,
.members-page .advisor-column ul {
  margin: 0;
  padding-left: 1.2rem;
}

.members-page .faculty-grid {
  margin-top: 0;
  padding-left: 0;
  list-style: none;
}

.members-page .faculty-grid li {
  margin: 0;
}

.members-page .faculty-grid a {
  display: inline-block;
  padding: 0.35rem 0;
  font-weight: 600;
}

.members-page .advisor-grid {
  align-items: start;
  gap: 0;
}

.members-page .member-grid > *,
.members-page .advisor-column {
  min-width: 0;
}

.members-page .advisor-column:first-child {
  padding-right: clamp(0.6rem, 2vw, 1.3rem);
}

.members-page .advisor-column + .advisor-column {
  padding-left: clamp(0.6rem, 2vw, 1.3rem);
  border-left: 1px solid var(--members-rule);
}

.members-page .advisor-column h3 {
  margin: 0 0 0.65rem;
  padding-bottom: 0.35rem;
  border-bottom: 1px solid var(--members-rule);
  font-size: 1.05rem;
  line-height: 1.4;
}

.members-page li {
  margin: 0.38rem 0;
  line-height: 1.6;
  overflow-wrap: break-word;
  word-break: normal;
  text-wrap: pretty;
}

.members-page .member-main,
.members-page .member-note {
  display: block;
  max-width: 100%;
}

.members-page .member-note {
  margin-top: 0.05rem;
  font-size: 0.93em;
  opacity: 0.75;
}

@media (max-width: 640px) {
  .members-page ul.member-grid:not(.faculty-grid) {
    grid-template-columns: 1fr;
  }

  .members-page .advisor-grid {
    font-size: 0.9rem;
  }

  .members-page .advisor-column:first-child {
    padding-right: 0.55rem;
  }

  .members-page .advisor-column + .advisor-column {
    padding-left: 0.55rem;
  }

  .members-page .advisor-column ul {
    padding-left: 1.05rem;
  }
}
</style>

<div class="members-page" markdown="1">

## Faculty Members

<ul class="member-grid faculty-grid">
  <li><a href="https://faculty.sdu.edu.cn/lizengpeng/zh_CN/index.htm">李增鹏</a></li>
  <li><a href="https://faculty.sdu.edu.cn/wangmei12345/zh_CN/index.htm">王梅</a></li>
</ul>

## Guest Faculty

<ul class="plain-list">
  <li><a href="https://riki8686.github.io/#about">Riccardo Spolar</a></li>
</ul>

## Ph.D. Students

<ul class="member-grid">
  <li>2026级 迟曼（直博，通用技术研究院委培）</li>
  <li>2026级 刘凯中（直博，电科委培）</li>
  <li>2025级 邓旭东</li>
  <li>2025级 唐博</li>
  <li>2024级 朱豪（2022硕博连读, 中交委培）</li>
  <li>2023级 陈梦佳（直博, 中交委培）</li>
</ul>

## Ph.D. Students (Part-Time)

<ul class="member-grid">
  <li>2026级 满翔宇（空天委培，合作导师：张化祥）</li>
  <li>2026级 李宸宇（中交委培，合作导师：查雅行）</li>
  <li>2024级 霍朝宾（中电委培，合作导师：阮强）</li>
  <li>2024级 史俊（中电委培，合作导师：李蕾）</li>
  <li>2023级 程向军（中交委培，合作导师：侯芸）</li>
</ul>

## Ph.D. Visitors and Co-supervision

<ul class="plain-list">
  <li>2020级 廖光宇</li>
</ul>

## Master's students

<div class="advisor-grid">
  <section class="advisor-column">
    <ul>
      <li>2026级 王紫璇（苏州大学）</li>
      <li>2026级 任航（苏州大学）</li>
      <li>2026级 张喆雨（曲阜师范）</li>
      <li>2026级 曹云（长江大学）</li>
      <li>2025级 陶瑞琦（山东大学）</li>
      <li>2025级 黄廷宸伊（山东大学）</li>
      <li>2025级 胡灏然（华北电力）</li>
      <li>2025级 曹海健（齐鲁工业）</li>
      <li>2025级 赵英伟（江苏大学）</li>
      <li>
        <span class="member-main">2024级 崔浩宇（山东大学）</span>
        <span class="member-note">隐私RAG</span>
      </li>
      <li>
        <span class="member-main">2024级 王浩（中国石油）</span>
        <span class="member-note">远程可信证明</span>
      </li>
      <li>
        <span class="member-main">2024级 孙洋（中国石油）</span>
        <span class="member-note">Oblivious Retrieval</span>
      </li>
    </ul>
  </section>
  <section class="advisor-column">
    <ul>
      <li>2026级 姚逸超（南京邮电）</li>
      <li>2026级 王男（山东科技）</li>
      <li>
        <span class="member-main">2024级 刘芮洁（中国石油大学）</span>
        <span class="member-note">远程可信证明</span>
      </li>
      <li>
        <span class="member-main">2024级 逯笑扬（山东大学）</span>
        <span class="member-note">OPRF+AKE</span>
      </li>
      <li>
        <span class="member-main">2024级 柏骄阳（齐鲁工业大学）</span>
        <span class="member-note">隐私推理</span>
      </li>
      <li>
        <span class="member-main">2024级 魏东方（重庆科技大学，退役）</span>
        <span class="member-note">可验证凭证</span>
      </li>
    </ul>
  </section>
</div>

## Master's students (Part-Time)

<div class="advisor-grid">
  <section class="advisor-column">
    <ul>
      <li>2027级 熊芷萱（山东大学，中电委培）</li>
      <li>2026级 张海洋（山东大学，电科委培）</li>
      <li>2026级 刁文（山东大学，电科委培）</li>
      <li>2025级 李永琪（山东大学，中交委培）</li>
      <li>2024级 陈晓宇（山东师范，中交委培）</li>
      <li>2024级 李路岩（山东大学，中电委培）</li>
      <li>2024级 周婷婷（山东大学，NTU联培）</li>
    </ul>
  </section>
  <section class="advisor-column">
    <ul>
      <li>2026级 赵一泽（山东大学，电科委培）</li>
      <li>2024级 李沛然（哈尔滨工程大学，中交委培）</li>
      <li>2024级 王珂（郑州大学，中电委培）</li>
    </ul>
  </section>
</div>

## Alumnus & Visitors

<div class="advisor-grid">
  <section class="advisor-column">
    <h3>李增鹏</h3>
    <ul>
      <li>
        <span class="member-main">2023-2026，王思旸（山东大学，中交委培）</span>
        <span class="member-note">武大读博</span>
      </li>
      <li>
        <span class="member-main">2023-2026，吕英杰（山东大学，校优秀毕业生）</span>
        <span class="member-note">读博</span>
      </li>
      <li>
        <span class="member-main">2023-2026，王书超（西电）</span>
        <span class="member-note">电网</span>
      </li>
      <li>
        <span class="member-main">2023-2026，匡金明（中国矿业）</span>
        <span class="member-note">传音</span>
      </li>
      <li>
        <span class="member-main">2023-2025，耿春秋（中国地质）</span>
        <span class="member-note">山大读博</span>
      </li>
      <li>
        <span class="member-main">2022-2025，赵子硕（山东大学）</span>
        <span class="member-note">电网</span>
      </li>
      <li>
        <span class="member-main">2022-2025，丁江（山东大学）</span>
        <span class="member-note">南瑞</span>
      </li>
      <li>
        <span class="member-main">2022-2025，李蔚（山东大学）</span>
        <span class="member-note">选调</span>
      </li>
      <li>
        <span class="member-main">2019-2022，魏令涛（青岛大学）</span>
        <span class="member-note">电网</span>
      </li>
      <li>
        <span class="member-main">2019-2022，高菲（青岛大学）</span>
        <span class="member-note">三未信安</span>
      </li>
      <li>
        <span class="member-main">2019-2022，肖帅（青岛大学）</span>
        <span class="member-note">镇长</span>
      </li>
      <li>
        <span class="member-main">2019-2022，邓旭东（青岛大学）</span>
        <span class="member-note">山大读博</span>
      </li>
    </ul>
  </section>
  <section class="advisor-column">
    <h3>王梅</h3>
    <ul>
      <li>
        <span class="member-main">2023-2026，葛菲（山东大学）</span>
        <span class="member-note">阿里</span>
      </li>
      <li>
        <span class="member-main">2023-2026，李宣仪（山东大学）</span>
        <span class="member-note">航旅纵横</span>
      </li>
      <li>
        <span class="member-main">2023-2026，杨潇然（新疆大学）</span>
        <span class="member-note">省联社</span>
      </li>
      <li>
        <span class="member-main">2023-2026，李文文（山东大学，中电委培）</span>
        <span class="member-note">CETC</span>
      </li>
    </ul>
  </section>
</div>

</div>

## [Undergraduate Alumnus](/members/undergraduate)

