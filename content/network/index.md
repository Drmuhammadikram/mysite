---
title: 'Collaboration network'
summary: 'Co-authorship network across 74 publications, showing recurring collaborators and the research clusters they form.'
type: landing
sections:
  - block: markdown
    content:
      title: 'Collaboration network'
      subtitle: ''
      text: |-
        {{< coauthors >}}
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'How to read it'
      subtitle: ''
      text: |-
        The clusters are not assigned; they emerge from the structure. Two co-authors are connected when they appear on the same paper, and the algorithm groups authors who connect to each other more than to the rest of the network.

        What that produces is a picture of research communities rather than a list of names. The largest cluster reflects sustained work on corporate sustainability and environmental management. Smaller clusters correspond to distinct strands — energy economics, and more recent collaborations in Morocco.

        I am absent from the network by design. Every collaborator connects to me, so including myself would pull the entire graph into a single hub and destroy the cluster structure that makes it informative.

        Collaborators with a single shared paper are also omitted. They represent roughly two-thirds of the total, and including them would produce a halo of disconnected points around the meaningful structure.
    design:
      columns: '1'
---
