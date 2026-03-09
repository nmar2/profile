---
layout: default
/* title: Certifications */
---

## Certifications

<style>
.cert-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.cert-card {
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 20px;
  background: #fafafa;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.cert-card h3 {
  margin: 0 0 6px 0;
  font-size: 1em;
}

.cert-card .issuer {
  color: #666;
  font-size: 0.85em;
  margin-bottom: 4px;
}

.cert-card .year {
  color: #999;
  font-size: 0.8em;
  margin-bottom: 14px;
}

.cert-links {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}

.cert-links a {
  font-size: 0.85em;
  padding: 5px 12px;
  border-radius: 4px;
  text-decoration: none;
  border: 1px solid currentColor;
}

.cert-links a.pdf {
  color: #c0392b;
}

.cert-links a.link {
  color: #2980b9;
}
</style>

<div class="cert-grid">

  <div class="cert-card">
    <div>
      <h3>IIBA® – Agile Analysis Certification (AAC)</h3>
      <div class="issuer">International Institute of Business Analysis (IIBA)</div>
      <div class="year">2023</div>
    </div>
    <div class="cert-links">
      <a class="link" href="https://badges.iiba.org/3e32f259-a2b7-4817-8d8a-1f4f2dc9835d#acc.3SiDEQ95" target="_blank">🔗 Verify</a>
    </div>
  </div>

  <div class="cert-card">
    <div>
      <h3>Project Management Professional (PMP)</h3>
      <div class="issuer">Project Management Institute (PMI)</div>
      <div class="year">Add year</div>
    </div>
    <div class="cert-links">
      <a class="link" href="https://www.credly.com/users/YOUR-USERNAME" target="_blank">🔗 Credly</a>
      <!-- <a class="pdf" href="certifications/pmp.pdf" target="_blank">📄 PDF</a> -->
    </div>
  </div>

  <div class="cert-card">
    <div>
      <h3>Add Certification Title</h3>
      <div class="issuer">Issuing Organisation</div>
      <div class="year">Year</div>
    </div>
    <div class="cert-links">
      <a class="pdf" href="certifications/filename.pdf" target="_blank">📄 PDF</a>
      <a class="link" href="https://verify-link.com" target="_blank">🔗 Verify</a>
    </div>
  </div>

</div>

---

> **To add a new certification:** copy one of the `<div class="cert-card">` blocks above,
> fill in the title, issuer, year, and update the links.
> For PDF files, place them in a `/certifications/` folder in your repository and update the `href` path.
