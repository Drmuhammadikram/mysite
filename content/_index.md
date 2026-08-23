---
title: ''
summary: ''
date: 2022-10-24
type: landing
sections:
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <style>
        section:has(#pbnr){position:relative;z-index:60;}
        </style>
        <div style="width:100vw;position:relative;left:50%;margin-left:-50vw;padding:0.75rem 0 0;margin-bottom:-3rem;">
          <img src="/uploads/sdg-poster.png" alt="The 17 UN Sustainable Development Goals" style="display:block;width:100%;max-width:1700px;height:auto;margin:0 auto;border-radius:16px;box-shadow:0 16px 40px rgba(30,41,59,0.14);position:relative;z-index:100;">
        </div>
        <span id="pbnr"></span>
    design:
      columns: '1'
      spacing:
        padding: ['0', '0', '0', '0']
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
      title: 'Estimate your carbon footprint'
      subtitle: ''
      text: |-
        Adjust the inputs to see how household energy, travel, and diet contribute to an annual carbon footprint, and how the total compares against national averages and the per-person budget consistent with 1.5 °C.

        {{< carboncalc >}}
    design:
      columns: '1'
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:16px;margin:1rem 0;align-items:stretch;" id="metrics-pair">
        <div style="background:rgba(128,128,128,0.06);border-radius:12px;padding:1.5rem 1.75rem;">
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
          <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(90px,1fr));gap:1.5rem;">
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
        {{< scopus >}}
        </div>
        <p style="font-size:0.71rem;opacity:0.5;line-height:1.6;margin-top:0.5rem;">
          Scopus indexes a narrower set of journals than Google Scholar, so its citation count is
          consistently lower. Neither figure is wrong; they cover different corpora.
        </p>
        <style>@media(max-width:820px){#metrics-pair{grid-template-columns:1fr!important}}</style>
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Collaboration network'
      subtitle: ''
      text: |-
        Co-authorship across 74 publications. Each node is a recurring collaborator, sized by shared papers; the clusters emerge from who has worked with whom rather than being assigned.

        {{< coauthors >}}
    design:
      columns: '1'
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <a href="https://www.timeshighereducation.com/campus/how-embed-sustainability-your-business-school" style="display:block;text-decoration:none;color:inherit;border:1px solid rgba(128,128,128,0.2);border-radius:14px;padding:1.6rem 1.8rem;transition:border-color .18s ease,transform .18s ease;" onmouseover="this.style.borderColor='rgba(27,175,122,0.5)';this.style.transform='translateY(-2px)'" onmouseout="this.style.borderColor='rgba(128,128,128,0.2)';this.style.transform='none'">
          <div style="display:flex;align-items:center;gap:12px;margin-bottom:1.1rem;flex-wrap:wrap;">
            <img src="/uploads/logos/the-logo.png" alt="Times Higher Education" style="height:76px;width:auto;">
            <span style="font-size:0.66rem;letter-spacing:0.09em;text-transform:uppercase;opacity:0.5;font-weight:600;">Feature article · October 2025</span>
          </div>
          <div style="font-size:1.35rem;font-weight:600;line-height:1.3;margin-bottom:0.6rem;letter-spacing:-0.01em;">How to embed sustainability in your business school</div>
          <div style="font-size:0.9rem;opacity:0.72;line-height:1.6;margin-bottom:1rem;">Vague symbolic gestures and greenwashing are no longer enough. Written for THE Campus on moving business schools from recycling bins and mission statements to sustainability embedded across curriculum, campus operations, research agendas and industry partnerships — with seven practical steps for institutions starting out.</div>
          <div style="font-size:0.8rem;color:#1baf7a;font-weight:500;">Read at Times Higher Education →</div>
        </a>
    design:
      columns: '1'
  - block: markdown
    content:
      title: '📚 Research Statement'
      subtitle: ''
      text: |-
        My research examines how organizations, industries, and public institutions can respond strategically to complex sustainability challenges through responsible management, technological innovation, and data-driven decision-making. Positioned at the intersection of sustainability, strategic management, and decision sciences, my work develops practical frameworks that help decision-makers address environmental uncertainty, resource constraints, institutional complexity, and competing stakeholder priorities.

        A central theme of my research is the development of integrated decision-support systems for sustainable development. I employ advanced quantitative and analytical approaches — including fuzzy multi-criteria decision-making, grey systems theory, data envelopment analysis, structural equation modelling, bibliometric analysis, and composite-index construction — to evaluate sustainability performance, prioritize strategic alternatives, and support policy formulation. Rather than viewing sustainability as a single environmental objective, my research considers its economic, social, technological, institutional, and governance dimensions.

        My current work focuses on several interconnected areas. The first investigates sustainable resource management, particularly water resilience, energy management, food security, and environmental performance in emerging economies. This research explores how technological solutions, policy interventions, and governance mechanisms can be combined to strengthen resilience and improve equitable access to essential resources. The second area examines the strategic adoption of green technologies, circular-economy practices, low-carbon production systems, and digital technologies such as artificial intelligence, Industry 4.0, autonomous systems, and decision intelligence.

        A further stream of my research explores corporate sustainability, responsible management, environmental certification, green marketing, corporate social responsibility, and stakeholder behaviour. Through this work, I seek to explain how organizational capabilities, leadership decisions, consumer perceptions, and institutional pressures influence sustainable business performance. I am particularly interested in how firms can translate environmental and social commitments into measurable competitive advantages while avoiding symbolic or fragmented sustainability practices.

        Geographically, much of my research is situated in Morocco, North Africa, the Middle East, and other emerging-market contexts. These regions face distinctive environmental, institutional, and socioeconomic challenges, yet they remain underrepresented in mainstream management and sustainability research. By incorporating local evidence into globally relevant theoretical and analytical frameworks, my work aims to produce knowledge that is both academically rigorous and contextually meaningful.

        My broader research objective is to bridge the gap between academic analysis and practical implementation. I seek to develop research that informs managers, policymakers, communities, and international organizations while contributing to scholarly debates in sustainability management, strategic decision-making, responsible innovation, and organizational transformation. Through interdisciplinary collaboration, methodological innovation, and engagement with real-world problems, my research supports the transition toward more resilient, inclusive, and environmentally responsible economic systems.
    design:
      columns: '1'
---
