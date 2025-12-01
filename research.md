<style>
/* ---- 背景：更轻、更柔和 ---- */
body {
  background:
    linear-gradient(rgba(255,255,255,0.65), rgba(255,255,255,0.65)),
    url("car-t-cell-therapy-2x.jpg");
  background-size: cover;
  background-attachment: fixed;
  background-position: center;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", system-ui, sans-serif;
  margin: 0;
  padding: 0;
}

/* ---- 导航栏：保持 GitHub 主题原有颜色 ---- */
.navbar {
  text-align: center;
  font-size: 16px;
  margin: 25px 0 5px 0;
}

/* 不再设置 color，直接使用主题默认链接色（和首页一致） */
.navbar a {
  text-decoration: none;
  margin: 0 10px;
  font-weight: 500;
}

.navbar a:hover {
  text-decoration: underline;
}

/* 去掉导航栏下方的那条线 */
.navbar + hr {
  display: none !important;
}

/* ---- 主体容器 ---- */
.lab-container {
  max-width: 880px;
  margin: 30px auto 60px auto;
  padding: 0 18px;
}

/* ---- Section 卡片样式 ---- */
.lab-section {
  background: rgba(255,255,255,0.88);
  border-radius: 10px;
  padding: 18px 22px;
  margin-bottom: 26px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.06);
  border-left: 4px solid #8c1515; /* Stanford Cardinal */
}

/* ---- Section 标题 ---- */
.lab-section h2 {
  font-size: 21px;
  margin: 0 0 8px 0;
  color: #2c3e50;
  font-weight: 600;
}

/* ---- 正文 ---- */
.lab-section p {
  font-size: 16px;
  line-height: 1.68;
  color: #333;
  margin: 0;
}

</style>

<!-- ---- 导航栏 ---- -->
<div class="navbar">
  <a href="/lab">Home</a> ·
  <a href="/lab/members">Members</a> ·
  <a href="/lab/research">Research</a> ·
  <a href="/lab/publications">Publications</a> ·
  <a href="/lab/contact">Contact</a>
</div>

<hr>

<!-- ---- 内容主体 ---- -->
<div class="lab-container">

  <div class="lab-section">
    <h2>Virus-driven immune remodeling in transplantation and cellular therapies</h2>
    <p>
      We study how CMV, EBV, and other viral exposures reshape immune reconstitution after HSCT, CAR-T therapy, and other advanced cellular treatments. Using longitudinal CyTOF and single-cell sequencing, we map immune trajectories and identify signatures linked to toxicity, relapse, and infection. Computational models integrate viral kinetics with immune dynamics to guide precision monitoring and therapeutic decision-making.
    </p>
  </div>

  <div class="lab-section">
    <h2>Precision immunology and immunotherapy in acute myeloid leukemia</h2>
    <p>
      AML serves as a key disease model to understand therapy-induced immune remodeling. We investigate how induction regimens such as HAV, antigen drift, and the immune microenvironment shape AML outcomes. We also develop and evaluate AML-directed immunotherapies—including CAR-T cells, vaccines, and viral-antigen–driven immunogenic strategies—to enhance antileukemic immunity and improve long-term survival.
    </p>
  </div>

  <div class="lab-section">
    <h2>Integrating HSCT and CAR-T with multimodal immunotherapies</h2>
    <p>
      We integrate HSCT, CAR-T, and additional immune-based approaches to develop multimodal therapeutic strategies aimed at improving long-term disease control in hematologic malignancies.
    </p>
  </div>

</div>
