---
title: 'Curriculum'

type: landing

sections:
  - block: experience
    content:
      title: 'Academic & Professional Experience'
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Engineer - Software Safety & Security Laboratory (LSL)
          company: Alternative Energy and Atomic Energy Commission (CEA)
          company_logo: cea
          location: Palaiseau
          date_start: '2025-09-01'
          date_end: ''
          description: |2-
            Research on the **formal verification of reactive and real-time software**,
            with a particular focus on combining program analysis, deductive techniques, and
            synchronous model checking.
            
            I contribute to the development of [**Frama-C/Synchrone**](https://frama-c.com/fc-plugins/synchrone.html),
            a Frama-C plug-in that extracts synchronous **Lustre** models from
            reactive C programs for subsequent formal verification. My work involves
            symbolic program analysis, abstract interpretation, deductive verification techniques,
            and **model checking**.
            
            This work led to the paper [*Modular Extraction of Lustre Models from C Reactive Programs using Frama-C*](https://esweek.org/full-program/), published  in EMSOFT 2026 and the IEEE TCAD journal (to appear).

        - title: Adjunct Lecturer at the Embedded & Real-Time Speciality
          company: EPITA School of Engineering and Computer Science
          company_logo: epita
          location: Le Kremlin-Bicetre
          date_start: '2022-06-01'
          date_end: ''
          description: |2-
            Designed and teach a course on **software testing and validation** for
            approximately 50 students in EPITA's Embedded & Real-Time Systems specialization,
            at M1/M2 level for a total of around 25h/year.
            
            The course covers functional and structural testing, fuzzing, static analysis,
            and formal verification, with an emphasis on the verification and validation
            of **safety-critical software**.
            
            I also participate in student assessment and internship juries.

        - title: Doctoral Research Engineer (CIFRE)
          company: Université Côte d'Azur / Inria / Asterios Technologies
          company_logo: ks
          location: Massy
          date_start: '2021-01-01'
          date_end: '2024-01-01'
          description: |2-
            PhD research on the **formal verification of temporal properties for safety-critical
            real-time applications based on logical time**, conducted as a CIFRE collaboration
            between **Université Côte d'Azur**, the **Inria KAIROS** team,
            and **Krono-Safe/Asterios Technologies**.
            
            The work established formal semantics for the industrial **PsyC** language by
            combining the **Synchronous-Reactive** and **Logical Execution Time** models into
            the *Synchronous Logical Execution Time* framework.
            
            I developed a verification methodology based on translation to synchronous models
            (both **Esterel** and **Lustre**), and symbolic **model checking**, together with
            temporal abstractions reducing verification cost.

        - title: R&D Software Engineer
          company: Asterios Technologies (formerly Krono-Safe, now in Safran)
          company_logo: ks
          location: Massy
          date_start: '2019-09-01'
          date_end: '2025-08-31'
          description: |2-
            Worked on the development and verification of the Asterios real-time
            software toolchain, for safety-critical applications.

            * Contributed to the **PsyC compiler** written in **C++** and to the
              associated **real-time kernel** written in **C**, including fault and error
              management, and the support of non time-critical tasks.

            * Designed and implemented formal verification techniques and an **OCaml**
              verification prototype for **PsyC**, using synchronous models and
              symbolic model checking.

            * Contributed to a compiler validation toolchain written in **Python**,
              including parsing, graph analyses, and validation of generated
              implementation artifacts in an avionics certification context.

            * Participated in **HAZOP** safety analyses of software features.

            * Co-supervised 3 interns on topics including **Lingua Franca** to
              **PsyC** translation and **randomized PsyC code generation**,
              which led to the discovery of 9 defects in the Asterios toolchain.

        - title: Internship
          company: Asterios Technologies (formerly Krono-Safe, now in Safran)
          company_logo: ks
          location: Massy
          date_start: '2019-02-01'
          date_end: '2019-08-01'
          description: |2-
            Designed and implemented an **incremental code generation** methodology
            based on model driven engineering techniques.
        - title: Internship
          company: Thales Research & Technologies
          company_logo: thales
          location: Palaiseau
          date_start: '2017-09-01'
          date_end: '2017-12-31'
          description: |2-
            Designed a **mixed-criticality** execution platform based on **virtualization**,
            providing spatial and temporal isolation between computer-vision and telecom applications.
        - title: Teaching Assistant
          company: EPITA School of Engineering and Computer Science
          company_logo: epita
          location: Le Kremlin-Bicetre
          date_start: '2016-09-01'
          date_end: '2017-03-01'
          description: |2-
            Supervised programming laboratory sessions and assessed student work
            in the *cycle préparatoire* of EPITA.
        - title: Internship at the Security & System Laboratory (LSE)
          company: EPITA School of Engineering and Computer Science
          company_logo: epita
          location: Le Kremlin-Bicetre
          date_start: '2016-06-01'
          date_end: '2016-08-30'
          description: |2-
            Contributed to the initial development of the Netlink subsystem in
            the **Linux** system tracer - **strace** - as part of the Google Summer of
            Code program.
    design:
      columns: '2'
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Certificates'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/WLYNZM7X4YRH
          date_end: ''
          date_start: '2024-07-01'
          description: 'Deep Learning, Sequence Models and Convolutional Neural Networks'
          icon: coursera
          organization: DeepLearning.AI
          organization_url: https://www.coursera.org
          title: Deep Learning Specialization
          url: ''
        - certificate_url: 'https://www.coursera.org/account/accomplishments/specialization/7PMER3WDEKYZ'
          date_end: ''
          date_start: '2023-06-01'
          description: 'Supervised learning (regression, classification), Unsupervised, Recommenders, Reinforcement Learning'
          icon: coursera
          organization: DeepLearning.AI
          organization_url: https://www.coursera.org
          title: Machine Learning Specialization
          url: ''

  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         icon: edx
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         icon: datacamp
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
    design:
      columns: '2'
---
            <!-- ;* Involved in the development of Asterios Technologies’ -->
            <!-- ;  main product (*Core Team*), consisting of a **compiler** for the PsyC language -->
            <!-- ;  (written in **C++**) and a **real-time operating system** (written in **C**) -->
            <!-- ;  by implementing various functionalities such as the fault and error -->
            <!-- ;  management service. -->
            <!-- ;* Designed a **formal verification** methodology -->
            <!-- ;  (as part of my CIFRE PhD supervised by -->
            <!-- ;  **Inria**) as well as a prototype formal verification tool -->
            <!-- ;  (written in **OCaml**) for the PsyC language based on state-of-the-art -->
            <!-- ;  symbolic **model-checking** along with an optimization procedure to -->
            <!-- ;  speed-up verification time by up to 95% compared to a naive approach. -->
            <!-- ;* Previously involved in the development of a tool (written in -->
            <!-- ;  **Python**) that performs the **validation of compilations** performed -->
            <!-- ;  by the Asterios compiler (*Checker Team*) by implementing the -->
            <!-- ;  tool’s frontend (parser and graph -->
            <!-- ;  analysis), in a context of avionics certification (**DO-178**) -->
            <!-- ;* Contributed to a technical audit by analyzing Asterios features -->
            <!-- ;  using **HAZOP risk and failure -->
            <!-- ;  analysis** methodology. -->
