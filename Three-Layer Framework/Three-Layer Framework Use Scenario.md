# Three-Layer Framework and Use Scenarios 

<p align="center">
  <img src="Three-Layer Framework.png" alt="View Three-Layer Framework" width="500"/>
</p>

<p align="center">
  <em>Figure 1. A Conceptual Three-Layer Framework for Human-Centered AI-Integrated Computing Education.</em>  
  <br/>
  <a href="Three-Layer Framework.pdf">Download full PDF</a>
</p>

# Three-Layer Framework and Illustrative Application

This document accompanies the paper and presents the framework's hypothetical AI-assisted debugging scenario. It illustrates intended uses of the framework rather than reporting an implemented or evaluated intervention.

[View or download the framework diagram (PDF)](THREE-LAYERS.pdf)

## Framework Overview

The framework connects three layers:

- **Layer 1: AI-Integrated Task Pipeline** structures individual tasks through six stages: **Identify, Engage, Evaluate, Refine, Deliver, and Reflect**. Earlier stages may be revisited, and human participants retain responsibility for evaluating and accepting AI-assisted outputs.
- **Layer 2: Professional Development Loop** connects tasks within role-specific activities, allowing experience and feedback from one activity to inform others.
- **Layer 3: Computing Education Ecosystem** connects students, educators, and professional developers through pedagogical scaffolding, education–practice alignment, and professional transition.

The scenario below follows the layers from ecosystem alignment to role-specific development and individual tasks. Feedback from practice also informs subsequent development and alignment.

## Illustrative Application: AI-Assisted Debugging

The survey identified debugging as a common use of GenAI among students and professional developers, alongside shared concerns about verifying AI-generated outputs. To illustrate the framework, we construct a hypothetical scenario in which government policy permits GenAI use in university computing programs. The scenario follows how universities, industry, and students coordinate their expectations under this policy setting (Layer 3), how these expectations shape connected development activities within each role (Layer 2), and how they are enacted through individual tasks (Layer 1). These tasks comprise a student debugging assignment, educators' AI-assisted assignment design, and developers' AI-assisted bug fixing.

### Layer 3: Ecosystem Alignment

The hypothetical policy decision affects all groups, whose responses shape one another. Universities must decide how students learn and are assessed when AI can produce part of their work. Educators must teach with tools they are still learning themselves. Employers' expectations of graduates change as AI enters their own workflows. Students sit at the center of these changes and encounter expectations from each group.

Representatives of universities, industry, and students therefore discuss what AI literacy means for computing graduates and how it can be assessed. Their discussion establishes a shared direction rather than a fixed specification: AI literacy includes verifying AI-generated outputs and taking responsibility for the resulting decisions, and assessment examines how students develop their solutions, not only the final artifact.

This direction connects the groups through:

- **Pedagogical scaffolding:** how students progress toward responsible AI use.
- **Education–practice alignment:** connecting educational goals with workplace expectations.
- **Professional transition:** how graduates carry their preparation into employment.

As practices change, feedback from each group informs revisions to this shared direction.

### Layer 2: Role Development

The shared direction reaches each group through changes to its everyday activities. These activities inform one another and support the development of capabilities needed to put the direction into practice.

**Students.** Debugging exercises in programming courses require students to check AI suggestions rather than accept them uncritically. They apply these verification strategies in collaborative projects, where they explain their own AI-assisted changes and review those of their peers. Ethical reflection addresses responsibility for these decisions. Assessments completed without AI identify gaps that inform subsequent learning activities. These connected experiences are intended to develop verification and judgment for professional practice.

**Educators.** The direction shapes curriculum design: verification becomes a learning objective, and assignments ask students to show how they reached their solutions. Marking this evidence reveals whether the assignments elicit the intended reasoning, informing revisions to scaffolding and rubrics. Professional development and discussion with colleagues support these revisions, while difficulties encountered in teaching identify further professional learning needs. Educators thus develop their own practice of teaching with AI while putting the shared direction into effect.

**Developers.** The direction shapes workplace training, code review, and graduate mentoring. Reviewing AI-assisted changes puts verification and responsibility into practice. A boundary case overlooked in a repair and identified during review becomes an example in team training and a check in subsequent reviews. Mentoring builds on what graduates bring from their programs and identifies where further support is needed. Developers adapt their practices accordingly, and their observations return to Layer 3 as feedback on graduate preparation.

### Layer 1: Task Pipeline

Within these activities, the pipeline structures how the shared direction is enacted in an individual task. Each task below requires verification and evidence supporting the resulting decisions, while retaining human responsibility for accepting AI-assisted outputs. The following tables present a student debugging assignment, guidelines for educators' AI-assisted assignment design, and an operational guide for developers' AI-assisted bug fixing.

#### Students: AI-Assisted Debugging Assignment Using the Task Pipeline

**Task:** Debug the provided program using GenAI. Document your work across the six stages, revisiting earlier stages as needed.

| Stage | Assignment Instructions |
|---|---|
| **Identify** | Run the program before using AI. Describe its observed and expected behavior. What might be causing the difference? |
| **Engage** | Use a GenAI tool to investigate the problem. Record your prompts and its responses. What help are you seeking from the tool? |
| **Evaluate** | Inspect the suggested changes and test them. Does the AI's suggestion address the problem? Explain your judgment using evidence from the code and tests. |
| **Refine** | Revise the solution based on your evaluation and test it again. What did you retain, modify, or reject from the AI's suggestion, and why? |
| **Deliver** | Submit your corrected code and test results. Explain how your changes resolve the problem. Are there any remaining limitations? |
| **Reflect** | Write a brief reflection on your debugging process. How did AI help or hinder your work? What did you learn, and what would you do differently next time? |

The assignment makes students' AI-assisted problem-solving process visible. Assessment can consider their diagnosis, verification, justification, and reflection alongside the correctness of the final code. Although this assignment requires AI use, instructors can vary its permitted role according to learning objectives and include independent debugging tasks to assess students' understanding without AI assistance.

#### Educators: Design Guidelines for AI-Assisted Assignment Design Using the Task Pipeline

**Context:** Educators design and review a debugging assignment with GenAI support, including student instructions, faulty code, reference materials, and assessment criteria.

| Stage | Design Guidelines |
|---|---|
| **Identify** | Establish the learning objectives and prerequisite knowledge. Determine what evidence would demonstrate students' debugging understanding beyond producing correct code with AI. |
| **Engage** | Provide GenAI with the objectives, student level, and teaching constraints. Use it to explore suitable faults, task instructions, tests, or rubric descriptors. |
| **Evaluate** | Work through the proposed assignment and execute its code and tests. Check technical correctness, workload, and difficulty. Examine whether the requested submissions and rubric make the intended learning assessable. |
| **Refine** | Resolve ambiguous instructions and revise unsuitable faults, incomplete tests, or rubric criteria. Adjust scaffolding and AI-use boundaries where students could bypass the intended reasoning. |
| **Deliver** | Prepare the assignment brief, checked reference solution, tests, and rubric. Make permitted AI use and expectations for verification and independent explanation clear to students and teaching staff. |
| **Reflect** | Review the design decisions and anticipated difficulties. After classroom use, revisit these judgments using student work, questions, and marking difficulties to inform subsequent teaching. |

These guidelines support pedagogical judgment rather than prescribe a fixed teaching procedure. Evidence from classroom use can inform subsequent design and assessment activities within Layer 2.

#### Developers: An Operational Guide to AI-Assisted Bug Fixing Using the Task Pipeline

**Context:** Developers investigate and repair a project defect with GenAI support, alongside existing development and review procedures.

| Stage | Operational Guidance |
|---|---|
| **Identify** | Reproduce the failure and establish expected behavior. Check the issue report, relevant requirements, and affected components before selecting a repair approach. |
| **Engage** | Use an approved GenAI tool to explore possible causes, repairs, or missing tests. Supply sufficient technical context while respecting restrictions on confidential code and data. |
| **Evaluate** | Inspect the proposed diff and verify its behavior against the requirements. Run relevant tests and check boundary cases, regressions, and potential compatibility or security implications. |
| **Refine** | Revise or discard unsupported changes. Add tests for the reported failure and newly identified risks, and rerun the relevant checks. Keep the patch focused on the intended repair. |
| **Deliver** | Submit the patch through the normal review process, with the cause, repair rationale, test evidence, and known limitations. Disclose AI assistance where required by project policy. |
| **Reflect** | Use review feedback and any subsequent failures to identify missed assumptions or verification gaps. Feed relevant lessons into regression tests, review checklists, or team guidance for future AI-assisted work. |

The resulting evidence supports patch-review decisions, while review outcomes can inform subsequent implementation, testing, and team learning within Layer 2.
