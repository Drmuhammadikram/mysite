---
title: ''
summary: ''
date: 2022-10-24
type: landing
sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <div style="background:rgba(128,128,128,0.06);border-radius:12px;padding:1.5rem 1.75rem;margin:1rem 0;">
          <div style="display:flex;align-items:center;gap:10px;margin-bottom:1.5rem;flex-wrap:wrap;">
            <svg width="18" height="18" viewBox="0 0 512 512" aria-hidden="true" style="flex-shrink:0;">
              <path fill="#4285f4" d="M256 411.12L0 202.667 256 0z"/>
              <path fill="#356ac3" d="M256 411.12l256-208.453L256 0z"/>
              <circle fill="#a0c3ff" cx="256" cy="362.667" r="149.333"/>
              <path fill="#76a7fa" d="M121.037 298.667c23.968-50.453 75.392-85.334 134.963-85.334s110.995 34.881 134.963 85.334H121.037z"/>
            </svg>
            <span style="font-size:0.75rem;letter-spacing:0.06em;text-transform:uppercase;opacity:0.7;">Google Scholar</span>
            <a href="https://scholar.google.com/citations?user=zD2p9JcAAAAJ" style="margin-left:auto;font-size:0.8rem;">View profile →</a>
          </div>
          <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(110px,1fr));gap:1.5rem;">
            <div>
              <div style="font-size:2.5rem;line-height:1;font-weight:600;letter-spacing:-0.02em;font-variant-numeric:tabular-nums;">{{< scholar "citations" >}}</div>
              <div style="font-size:0.72rem;letter-spacing:0.06em;text-transform:uppercase;opacity:0.7;margin-top:0.5rem;">Citations</div>
            </div>
            <div>
              <div style="font-size:2.5rem;line-height:1;font-weight:600;letter-spacing:-0.02em;font-variant-numeric:tabular-nums;">{{< scholar "h_index" >}}</div>
              <div style="font-size:0.72rem;letter-spacing:0.06em;text-transform:uppercase;opacity:0.7;margin-top:0.5rem;">h-index</div>
            </div>
            <div>
              <div style="font-size:2.5rem;line-height:1;font-weight:600;letter-spacing:-0.02em;font-variant-numeric:tabular-nums;">{{< scholar "i10_index" >}}</div>
              <div style="font-size:0.72rem;letter-spacing:0.06em;text-transform:uppercase;opacity:0.7;margin-top:0.5rem;">i10-index</div>
            </div>
          </div>
          <div style="margin-top:1.75rem;padding-top:1.25rem;border-top:1px solid rgba(128,128,128,0.2);">
            <div style="font-size:0.72rem;letter-spacing:0.06em;text-transform:uppercase;opacity:0.7;margin-bottom:0.75rem;">Citations per year</div>
            {{< scholar "chart" >}}
          </div>
          <div style="margin-top:1.25rem;padding-top:1rem;border-top:1px solid rgba(128,128,128,0.2);font-size:0.72rem;opacity:0.55;">
            Updated {{< scholar "updated" >}}
          </div>
        </div>
    design:
      columns: '1'
  - block: markdown
    content:
      title: '📚 Research'
      subtitle: ''
      text: |-
        My research examines how formal environmental management systems — particularly ISO 14001 — translate into measurable carbon and sustainability outcomes, and how organisations in emerging economies navigate the transition to low-carbon operations.

        I work across bibliometric analysis, systematic review, grey systems modelling, and multi-criteria decision analysis, with published work in *Journal of Cleaner Production*, *Business Strategy and the Environment*, *Sustainable Production and Consumption*, and *Corporate Social Responsibility and Environmental Management*.

        I welcome collaboration on environmental management systems, decarbonisation pathways, and corporate sustainability performance.
    design:
      columns: '1'
---
