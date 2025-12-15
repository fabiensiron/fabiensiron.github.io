---
title: 'Curriculum'

type: landing

sections:
  - block: experience
    content:
      title: 'Work Experience'
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Engineer at the Software Safety Laboratory (LSL)
          company: Alternative Energy and Atomic Energy Commission (CEA)
          company_logo: cea
          location: Palaiseau
          date_start: '2025-09-01'
          date_end: ''
          description: |2-
            Contributing to the "synchrone" **Frama-C** plugin dedicated to the
            analysis of synchronous programs written in C and in Lustre. The
            plugin itself is written in **OCaml** and mix techniques based on
            **abstract interpretation**, **weakest preconditions** and **model-checking**.
            While it will be distributed as an external plugin, it is developed
            along the main Frama-C distribution.
  
        - title: Adjunct Lecturer at the Embedded & Real-Time Speciality
          company: EPITA School of Engineering and Computer Science
          company_logo: epita
          location: Le Kremlin-Bicetre
          date_start: '2022-06-01'
          date_end: ''
          description: |2-
            Teaching (and created) a lecture on software **testing and validation** for
            EPITA’s embedded and real-time specialization, involving around 40
            M1/M2 students for a total of around 20h/year.

        - title: R&D Software Engineer
          company: Asterios Technologies (formerly Krono-Safe, now in Safran)
          company_logo: ks
          location: Massy
          date_start: '2019-09-01'
          date_end: '2025-08-31'
          description: |2-
            * Involved in the development of Asterios Technologies’
              main product (*Core Team*), consisting of a **compiler** for the PsyC language
              (written in **C++**) and a **real-time operating system** (written in **C**)
              by implementing various functionalities such as the fault and error
              management service.

            * Designed a **formal verification** methodology
              (as part of my CIFRE PhD supervised by
              **Inria**) as well as a prototype formal verification tool
              (written in **OCaml**) for the PsyC language based on state-of-the-art
              symbolic **model-checking** along with an optimization procedure to
              speed-up verification time by up to 95% compared to a naive approach.

            * Previously involved in the development of a tool (written in
              **Python**) that performs the **validation of compilations** performed
              by the Asterios compiler (*Checker Team*) by implementing the
              tool’s frontend (parser and graph
              analysis), in a context of avionics certification (**DO-178**)

            * Contributed to a technical audit by analyzing Asterios features
              using **HAZOP risk and failure
              analysis** methodology.

            * (Co-)Supervised 3 trainees over the years on topics such as **Lingua
              Franca** to **PsyC** translation and **random PsyC code generation**,
              which led to the discovery of 9 bugs in the Asterios toolchain.

        - title: Internship
          company: Asterios Technologies (formerly Krono-Safe, now in Safran)
          company_logo: ks
          location: Massy
          date_start: '2019-02-01'
          date_end: '2019-08-01'
          description: |2-
            Designed and developed a methodology of incremental code generation based
            on model driven design approaches during my initial 6-month internship.
        - title: Internship
          company: Thales Research & Technologies
          company_logo: thales
          location: Palaiseau
          date_start: '2017-09-01'
          date_end: '2017-12-31'
          description: |2-
            Designed a **mixed-criticality** platform based on **virtualization**, enabling
            spatial and temporal isolation between vision and telecom applications.
        - title: Teaching Assistant
          company: EPITA School of Engineering and Computer Science
          company_logo: epita
          location: Le Kremlin-Bicetre
          date_start: '2016-09-01'
          date_end: '2017-03-01'
          description: |2-
            Supervised and corrected practical sessions on programming
            for students in the *cycle préparatoire* of EPITA.
        - title: Internship at the Security & System Laboratory (LSE)
          company: EPITA School of Engineering and Computer Science
          company_logo: epita
          location: Le Kremlin-Bicetre
          date_start: '2016-06-01'
          date_end: '2016-08-30'
          description: |2-
            Contributed to the initial development of the Netlink subsystem in
            the **Linux** system tracer - **strace** - via the Google Summer of
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
