---
title: 'Air quality'
summary: 'PM2.5 exposure across 171 countries from 1990 to 2023, measured against the WHO guideline of 5 micrograms per cubic metre.'
type: landing
sections:
  - block: markdown
    content:
      title: 'Air quality worldwide'
      subtitle: ''
      text: |-
        Mean annual exposure to fine particulate matter across 171 countries, from 1990 to 2023.

        {{< airquality >}}

        {{< dl file="air-quality-full.csv" rows="every year 1990–2023" span="1990 to 2023" source="World Bank World Development Indicators" >}}
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'What PM2.5 is, and why it is measured'
      subtitle: ''
      text: |-
        PM2.5 is particulate matter smaller than 2.5 micrometres across — roughly a thirtieth the width of a human hair. That size is what makes it dangerous. Larger particles are trapped in the nose and throat; PM2.5 passes into the deep lung and from there into the bloodstream.

        It is the single environmental risk factor most strongly associated with premature mortality worldwide, implicated in cardiovascular disease, stroke, respiratory illness and lung cancer. The WHO estimates it contributes to several million deaths a year.

        The figures here are population-weighted, meaning they reflect the exposure of where people actually live rather than the average across a country's land area. A country with a clean interior and a polluted capital will show a figure closer to the capital.
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'The guideline, and how far above it most of the world sits'
      subtitle: ''
      text: |-
        The WHO set its current guideline at 5 µg/m³ in 2021, tightened from 10. Below that level, no consistent health harm is detectable.

        Almost no country meets it. The WHO publishes four interim targets — 35, 25, 15 and 10 — precisely because the guideline is unreachable in the near term for most of the world, and staged improvement is more useful than an unattainable standard.

        For scale: Norway sits at around 5.5, close to the guideline. The United States at 7. Morocco at 18.7, nearly four times it. China at 32. India at 54, more than ten times the level at which harm begins.

        The hover panel gives each country's multiple of the guideline, which is a more legible comparison than the raw figure.
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'How to read it'
      subtitle: ''
      text: |-
        **National averages hide the cities.** This is the indicator's main limitation. Delhi, Lahore and Cairo sit far above their national figures, and it is in those cities that most exposure occurs. A country-level map understates the worst of it.

        **The sources differ by region.** In South Asia, road dust, crop burning and solid fuel used indoors dominate. In China, industry and coal. In parts of Africa and the Middle East, natural dust from arid land contributes substantially, which matters for policy — you cannot regulate the Sahara.

        **That last point deserves emphasis.** A high figure does not always indicate a policy failure. Distinguishing anthropogenic from natural sources requires more granular data than a country average provides.

        **Trends are informative.** Use the year buttons. China's figure has fallen substantially since 2013; several South Asian countries have not improved, and some have worsened.
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Read alongside'
      subtitle: ''
      text: |-
        - [Energy mix by source](/data/energy-mix/) — coal combustion is a primary source in several of the worst-affected countries
        - [Coal consumption](/data/coal-consumption/)
        - [Electric vehicles](/data/electric-vehicles/) — transport is a major urban source
        - [Economic indicators](/data/economy/) — the relationship with income is non-linear, rising through industrialisation and falling after
        - [SDG Index](/data/sdg-index/) — Goal 3.9 and Goal 11.6 both address air quality

        Related work:

        - [Cardiovascular disease assessment, prediction and policy implications](/publication/cardiovascular-disease-cvd-assessment-prediction-and-policy/)
        - [Growing green? Sectoral-based prediction of GHG emission in Pakistan](/publication/growing-green-sectoral-based-prediction-of-ghg-emission-in/)
        - [Estimating dynamic interactive linkages among urban agglomeration, economic performance, carbon emissions and health expenditures](/publication/estimating-dynamic-interactive-linkages-among-urban/)

        Data from the World Bank World Development Indicators.

        [← Back to all datasets](/data/)
    design:
      columns: '1'
---
