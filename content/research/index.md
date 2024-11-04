---
title: 'My Research'

type: landing

sections:
  - block: markdown
    content:
      title: Research Interests
      text: |2-
        Models and Languages for real-time systems
        : I'm interested in languages and models based on the logical
        time concept and on synchronous-reactive approaches. I've worked
        on the PsyC language, the CCSL specification language and more traditional
        synchronous languages such as Lustre and Esterel. In my thesis, I
        proposed two levels of equivalent semantics descriptions
        for PsyC, which allowed me to define
        a framework combining Synchronous-Reactive and Logical
        Execution Time called **Synchronous Logical Execution
        Time (or synchronous LET)**.

        Formal verification for real-time systems
        : I'm interested in adapting formal verification techniques to
        reactive systems, particularly technics based on **Model-Checking**.
        I'm working on intermediate techniques between timed automata approaches,
        and more traditional symbolic approaches such as SAT and BDD. In my thesis,
        I proposed
        temporal optimization techniques for PsyC in order to use SAT and
        BDD approaches.

        Implementation of real-time systems
        : Finally, I'm also interested in the implementation of these systems,
        whether in terms of compilation or scheduling analysis. I was able to
        participate in the design of a **validation tool** (in the context of
        **Krono-Safe**), verifying implementation artifacts such as the
        scheduling plan, or the sizing of communications.

        **university application** (*qualification* CNU): : [link](../uploads/cnu.pdf)
    design:
      columns: '2'
  - block: markdown
    content:
      title: PhD thesis
      text: |2-
        ## Subject and Jury
        - **Subject**: Methodology for the formal verification of temporal properties for real-time safety-critical applications based on logical time.
        - **Academic supervisers**: Dumitru Potop-Butucaru and Robert De Simone from *Centre Inria d'Université Côte d'Azur*.
        - **Industrial supervisers**: Damien Chabrol and Amira Methni from *Krono-Safe* (now called *Asterios Technologies*).
        - **Reviewers**: Reinhard Von Hanxleden from *Kiel University* and Pierre-Loïc Garoche from *École Nationale de l’Aviation Civile*.
        - **Examiners**: Timothy Bourke from *Centre Inria de Paris*.
        - **Slides**: [link](../uploads/slides_thesis.pdf)
        ## Abstract
        Safety-critical real-time systems have to respect strict timing
        constraints. Thus, timing constraints must be considered throughout the software
        development cycle. As exact computation execution time are generally not known
        during design, logical time provides a way to abstract time constraints and
        execution from platform-dependent physical time.

        In this thesis, we focus on two main formalisms based on logical time:
        - The Synchronous-Reactive
        approach totally abstracts physical time by discrete time bases on which
        computations are triggered.
        - The Logical Execution Time approach uses logical time
        bases to represent not only triggering instants but also the durations of
        elementary computations.

        We start by unifying Synchronous-Reactive
        and Logical Execution Time approaches. This provides the natural formal framework
        for defining the semantics of PSYC, an expressive industrial real-time language.
        We define two formal semantics for PsyC:
        1. a native big-step semantics preserving
        the logical durations of time intervals defined by structural operational rules
        and;
        2. a synchronous small-step semantics defined by translation to a
        Synchronous-Reactive language expanding time interval durations to a succession
        of atomic transitions.

        We show that the two semantics definitions are equivalent.
        This formalization of the PsyC semantics enables us to define a formal verification
        methodology for PSYC based on symbolic model-checking. To reduce
        the state space during model-checking, we also define an optimization technique
        inspired by timed automata model-checking. Finally, we show how to encode
        high-level timing requirements into a clock constraint specification
        language — CCSL — which are then translated to synchronous observers.

        > *Link to the thesis is available below in the publication list*
    design:
      columns: '2'
  - block: markdown
    content:
      title: Main publications
      text: >
          <iframe
            frameborder="0" style="border:0"
            width="100%"
            height="570"
            id="Publis"
            src="https://haltools.inria.fr/Public/afficheRequetePubli.php?auteur_exp=Fabien+Siron&CB_auteur=oui&CB_titre=oui&CB_article=oui&CB_DOI=oui&CB_typdoc=oui&CB_vignette=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/styles_publicationsHAL.css"
            allowfullscreen>
          </iframe>
    design:
      columns: '2'
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
