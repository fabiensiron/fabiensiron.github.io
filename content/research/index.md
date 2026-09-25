---
title: 'Research'

type: landing

sections:
  - block: markdown
    content:
      title: Research Interests
      text: |2-
        My research focuses on the formal verification of reactive and real-time
        software, at the intersection of programming languages, synchronous
        models, program analysis, and automated verification.

        One of the primary goals of my work is to bridge the gap between
        **implementation-level software** and models used for verification.
        I am particularly interested in approaches that combine
        several verification techniques rather than relying on a single formalism.

        #### Languages, semantics, and execution models for reactive systems

        I work on programming languages and execution models based on
        **logical time**, particularly **Synchronous-Reactive** and
        **Logical Execution Time (LET)** approaches.

        My doctoral work focused on the **PsyC** real-time language and led to
        the definition of the **Synchronous Logical Execution Time (sLET)**
        framework, connecting LET-based execution models with traditional
        synchronous languages such as **Lustre** and **Esterel**.

        More generally, I am interested in language semantics and execution
        models that make the temporal behavior of reactive systems explicit
        while remaining suitable for efficient implementation on real-time
        platforms.

        #### Verification from reactive systems

        A second research direction concerns the verification of reactive
        software directly from its implementation.

        At **CEA List**, I contribute to
        [**Frama-C/Synchrone**](https://frama-c.com/fc-plugins/synchrone.html),
        which extracts synchronous **Lustre** models from reactive C programs.
        The extraction combines symbolic program analysis, deductive reasoning,
        and abstract interpretation in order to construct models suitable for
        verification with synchronous model checkers.

        This work investigates how implementation-level reasoning and
        model-based verification can be combined while preserving a precise
        semantic relation between the original program and the extracted model.

        #### Verification algorithms and proof strategies

        I am also interested in verification algorithms for reactive systems
        and in the broader question of how complex verification tasks should be
        organized.

        My work has involved symbolic **model checking** based on SAT and BDDs,
        deductive verification, abstract interpretation, constraint-based
        verification, and more recently **Statistical Model Checking**.

        A particular research interest is the development of **modular
        verification strategies** combining complementary techniques. Complex
        safety properties often require intermediate invariants, decomposition,
        auxiliary lemmas, or specialized reasoning procedures rather than a
        single monolithic model-checking query. I am therefore interested both
        in verification algorithms themselves and in the strategies used to
        orchestrate them.

    design:
      columns: '2'
  - block: markdown
    content:
      title: Current Research
      text: |2-
        My current work develops these themes along several complementary
        directions.

        #### Verification of reactive C programs
        
        I work on the extraction of synchronous models from C programs within
        **Frama-C/Synchrone**, combining Frama-C analyses with synchronous
        model checking. This includes questions related to symbolic model
        extraction, modularity, memory abstraction, and the verification of
        multi-cycle reactive behavior.

        #### Modular verification and proof strategies
        
        I investigate combinations of **deductive verification**, static
        analysis, and **model checking** for reactive systems. The objective is
        to move toward verification methodologies in which different parts of
        a system, or different proof obligations, can be handled using the most
        appropriate reasoning technique.

        #### Verification algorithms
        
        I am interested in alternative approaches to exhaustive symbolic model
        checking, including constraint-based techniques and statistical model
        checking, and in their integration with SMT-based verification
        frameworks.

        #### Reactive and real-time execution models
        
        Finally, I continue to investigate the relationship between synchronous
        execution, logical-time abstractions, and real-time implementation,
        including multi-rate and multi-task execution models.

    design:
      columns: '2'

  - block: markdown
    content:
      title: PhD Thesis
      text: |2-
        ### Formal Verification of Real-Time Programs Based on Logical Time

        I received my PhD in Computer Science from **Université Côte d'Azur**
        in December 2023. The thesis was conducted within the
        **Inria KAIROS** team as a CIFRE collaboration with
        **Krono-Safe/Asterios Technologies**.

        **Thesis title:**
        *Methodology for the Formal Verification of Temporal Properties for
        Safety-Critical Real-Time Applications Based on Logical Time*

        - **Academic supervisors**: Dumitru Potop-Butucaru and Robert De Simone from *Centre Inria d'Université Côte d'Azur*.
        - **Industrial supervisors**: Damien Chabrol and Amira Methni from *Krono-Safe* (now called *Asterios Technologies*).
        - **Reviewers**: Reinhard Von Hanxleden from *Kiel University* and Pierre-Loïc Garoche from *École Nationale de l’Aviation Civile*.
        - **Examiner**: Timothy Bourke from *Centre Inria de Paris*.

        The thesis investigated the relationship between two major logical-time
        paradigms used for real-time and reactive systems:

        * the **Synchronous-Reactive** model, in which computation evolves
          according to discrete logical instants;
        * **Logical Execution Time (LET)**, in which logical time additionally
          captures the duration assigned to computations.

        The main contributions include:

        * the **Synchronous Logical Execution Time (sLET)** framework,
          combining synchronous-reactive and LET concepts;
        * two formal semantics for the industrial **PsyC** language:
          a native big-step semantics preserving logical durations and a
          synchronous small-step semantics;
        * a proof of equivalence between these semantic descriptions;
        * a formal verification methodology for PsyC based on translation to
          synchronous models and symbolic model checking;
        * temporal abstraction techniques for reducing verification cost;
        * the specification of high-level timing requirements using **CCSL**
          and their translation into synchronous observers.

        **[PhD defense slides](../uploads/slides_thesis.pdf)**

        > The thesis manuscript and associated publications are available in
        > the publication list below.

    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Selected Publications
      count: 6
      filters:
        folders:
          - publication
        featured_only: true
      sort_by: Date
      sort_ascending: false
      archive:
        enable: true
        text: All publications
        link: /publication/
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
---
  <!-- - block: markdown -->
  <!--   content: -->
  <!--     title: Main publications -->
  <!--     text: > -->
  <!--         <iframe -->
  <!--           frameborder="0" style="border:0" -->
  <!--           width="100%" -->
  <!--           height="570" -->
  <!--           id="Publis" -->
  <!--           src="https://haltools.inria.fr/Public/afficheRequetePubli.php?auteur_exp=Fabien+Siron&CB_auteur=oui&CB_titre=oui&CB_article=oui&CB_DOI=oui&CB_typdoc=oui&CB_vignette=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/styles_publicationsHAL.css" -->
  <!--           allowfullscreen> -->
  <!--         </iframe> -->
  <!--   design: -->
  <!--     columns: '2' -->


