---
title: 'Home'
date: 2023-10-24
type: landing

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    id: home
    content:
      username: me
    design:
      show_status: false
      spacing:
        padding: ['1rem', '0', '1rem', '0']
      biography:
        # Customize the style of your biography text
        style: 'font-size: 0.8em; line-height: 1.3;'
      # Avatar customization
      avatar:
        size: small # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: rounded # Options: circle (default), square, rounded
  - block: markdown
    id: education
    content:
      title: "🎓 Education"
      text: |-
        - **PhD in Computer Science**, Inria Paris (ALMAnaCH Team) and Sorbonne Université, 2023-present  
          Industrial PhD conducted in collaboration with Qatent (A Questel Company). Research topic: patent representation learning for innovation generation and technical trend analysis.  
          Supervisors: [Benoît Sagot](https://pauillac.inria.fr/~sagot/), [Éric de La Clergerie](https://moca.inria.fr/people-en.html), and [Kim Gerdes](https://gerdes.fr/).

        - **Master 2 in Artificial Intelligence**, Université Paris-Saclay, 2020-2021  
          GPA: 16.7/20, ranked 1/17. Main coursework included generative models, graphical models, natural language processing, multilingual NLP, and advanced optimisation.

        - **Engineering Diploma**, [ENSIIE - L'École Nationale Supérieure d'Informatique pour l'Industrie et l'Entreprise](https://www.ensiie.fr/), 2018-2021  
          Engineering curriculum in applied mathematics and computer science.

        - **Bachelor in Information and Computing Science**, [Xidian University](https://en.wikipedia.org/wiki/Xidian_University), 2015-2018  
          GPA: 3.60/4.0. Main coursework included mathematical analysis, matrix theory, optimisation, functional analysis, probability theory, and statistics.
    design:
      columns: '1'
  - block: markdown
    id: teaching
    content:
      title: "🧑‍🏫 Teaching"
      text: |-
        - **Part-time Lecturer, Introduction to Natural Language Processing in English**, [Institut national des langues et civilisations orientales (INALCO)](https://www.inalco.fr/), Sep. 2024-May 2025  
          Lecturer for the course *Introduction to Natural Language Processing in English*, a master's-level course for students in the [PluriTAL program](https://plurital.org/).

        - **Teaching Assistant, Introduction to Machine Learning**, [Université Paris-Saclay](https://www.universite-paris-saclay.fr/en), Sep. 2024-Dec. 2024  
          Assisted in teaching and supporting the L3 undergraduate course *Introduction to Machine Learning*, taught by [François Landes](https://perso.lisn.upsaclay.fr/flandes/), including labs, assignments, and student guidance.
    design:
      columns: '1'
  - block: markdown
    id: research-experience
    content:
      title: "🧪 Research Experience"
      text: |-
        - **Research Engineer**, Inria Paris, Oct. 2021-Nov. 2022  
          Worked on fine-grained patent classification in collaboration with [**INPI (French Intellectual Property Office)**](https://www.inpi.fr/), under the supervision of [Kim Gerdes](https://gerdes.fr/), [Benoît Sagot](https://pauillac.inria.fr/~sagot/), and Samir Ghamri Doudane.

        - **Research Internship**, LISN, Mar. 2021-Aug. 2021  
          Worked on technological term recognition and hypernym/hyponym prediction on patent texts, under the supervision of [Kim Gerdes](https://gerdes.fr/).
    design:
      columns: '1'
  - block: markdown
    id: news
    content:
      title: "📰 News"
      text: |-
        - **May 2026:** Our paper *Learning Sparse Representations for Patent Search via Geometric Covering of Embedding Spaces* was accepted for an oral presentation at [CORIA 2026](https://coria-taln-2026.ls2n.fr/).
        - **February 2026:** Released a new preprint on citation-driven multi-view training for patent embeddings.
        - **October 2025:** Released a preprint on self-supervised patent representation learning.
        - **September 2024:** Started teaching *Introduction to Natural Language Processing in English* at INALCO and served as a teaching assistant for *Introduction to Machine Learning* at Université Paris-Saclay.
        - **June 2024:** Published *PatentEval* at **NAACL 2024**.
        - **July 2023:** Attended the **13th Lisbon Machine Learning School (LxMLS 2023)**.
        - **June 2023:** Published work on French patent classification at **TALN 2023**.
        - **March 2023:** Started my PhD at Inria Paris and Sorbonne Université in collaboration with Qatent (A Questel Company).
        - **July 2022:** Served as a student volunteer at **SIGIR 2022**, where I also presented our work on French patent classification at the **PatentSemTech** workshop.
        - **October 2021:** Gave a seminar talk at the ALMAnaCH team, Inria, on *Tech-Taxonomy with a Text to Text Transfer Transformer*, jointly with Kim Gerdes.
    design:
      columns: '1'
  - block: markdown
    id: publications
    content:
      title: "📚 Publications"
      text: |-
        - Younes Djemmal, **You Zuo**, Kim Gerdes, and Kirian Guiller. [Citation-Driven Multi-View Training for Patent Embeddings: QaECTER and Sophia-Bench](https://www.lisn.upsaclay.fr/publications/citation-driven-multi-view-training-for-patent-embeddings-qaecter-and-sophia-bench/). *Preprint*, 2026. <span class="pub-badge pub-badge-preprint">Preprint</span> <span class="pub-links">[HAL](https://www.lisn.upsaclay.fr/publications/citation-driven-multi-view-training-for-patent-embeddings-qaecter-and-sophia-bench/) [PDF](publication/qaecter-sophia-bench/paper.pdf)</span>

        - **You Zuo**, Kim Gerdes, Éric de La Clergerie, and Benoît Sagot. [Patent Representation Learning via Self-supervision](https://hal.science/hal-05333463v2). *Preprint*, 2025. <span class="pub-badge pub-badge-preprint">Preprint</span> <span class="pub-links">[HAL](https://hal.science/hal-05333463v2) [PDF](publication/patent-representation-learning-self-supervision/paper.pdf) [Code](https://github.com/ZoeYou/patentmapv0)</span>

        - **You Zuo**, Kim Gerdes, Éric de La Clergerie, and Benoît Sagot. [PatentEval: Understanding Errors in Patent Generation](https://aclanthology.org/2024.naacl-long.147/). In *Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (NAACL 2024)*. <span class="pub-badge pub-badge-conference">Conference</span> <span class="pub-links">[ACL](https://aclanthology.org/2024.naacl-long.147/) [PDF](publication/patenteval/paper.pdf) [Code](https://github.com/ZoeYou/PatentEval)</span>

        - **You Zuo**, Benoît Sagot, Kim Gerdes, Houda Mouzoun, and Samir Ghamri Doudane. [Exploring Data-Centric Strategies for French Patent Classification: A Baseline and Comparisons](https://aclanthology.org/2023.jeptalnrecital-long.20/). In *Actes de la 30e Conférence sur le Traitement Automatique des Langues Naturelles (TALN 2023)*. <span class="pub-badge pub-badge-conference">Conference</span> <span class="pub-links">[ACL](https://aclanthology.org/2023.jeptalnrecital-long.20/) [PDF](publication/french-patent-classification-data-centric/paper.pdf) [Code](https://github.com/ZoeYou/Patent-Classification-2022)</span>

        - **You Zuo**, Houda Mouzoun, Samir Ghamri Doudane, Kim Gerdes, and Benoît Sagot. [Patent Classification using Extreme Multi-label Learning: A Case Study of French Patents](https://www.lisn.upsaclay.fr/publications/patent-classification-using-extreme-multi-label-learning-a-case-study-of-french-patents/). In *PatentSemTech 2022 Workshop, co-located with the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2022)*. <span class="pub-badge pub-badge-workshop">Workshop</span> <span class="pub-links">[HAL](https://www.lisn.upsaclay.fr/publications/patent-classification-using-extreme-multi-label-learning-a-case-study-of-french-patents/) [PDF](publication/patent-classification-extreme-multi-label/paper.pdf)</span>

        - **You Zuo**, Yixuan Li, Alma Parias Garcia, and Kim Gerdes. [Technological Taxonomies for Hypernym and Hyponym Retrieval in Patent Texts](https://www.lisn.upsaclay.fr/publications/technological-taxonomies-for-hypernym-and-hyponym-retrieval-in-patent-texts/). In *Terminology & Ontology: Theories and Applications (ToTh 2022)*. <span class="pub-badge pub-badge-conference">Conference</span> <span class="pub-links">[HAL](https://www.lisn.upsaclay.fr/publications/technological-taxonomies-for-hypernym-and-hyponym-retrieval-in-patent-texts/) [PDF](publication/technological-taxonomies-patent-texts/paper.pdf) [Code](https://github.com/ZoeYou/AutoTaxo)</span>
    design:
      columns: '1'
---
