# Story Point Estimation Using the Cynefin Framework

## Overview

**Story Point Estimation Using the Cynefin Framework** is a novel approach that classifies tasks into five domains and applies appropriate estimation methods and point criteria for each. By adding the clear distinction of uncertainty types and risks to traditional relative estimation, this method achieves more accurate story point estimation.

## Background & Motivation

Common challenges teams face in story point estimation:

- **Unclear estimation criteria**: Lack of clarity on "what to base difficulty assessment on"
- **Mixed types of uncertainty**: Technical complexity and requirement ambiguity are not distinguished
- **Inconsistent estimation methods**: Attempting to estimate all tasks using the same process regardless of their nature
- **Insufficient risk reflection**: Urgency and confusion levels are not properly reflected in story points

By utilizing the classification axes of the Cynefin Framework, these challenges can be systematically addressed.

## Story Points Fundamentals

### What are Story Points?

Story Points are units for measuring the "relative effort, complexity, and uncertainty" of work.

**Characteristics**:
- Consider difficulty, risk, and uncertainty rather than time (effort)
- Relative scale ("Task B seems about twice as hard as Task A")
- Function as a common standard within teams
- Often adopt Fibonacci sequence (1, 2, 3, 5, 8, 13...)

### Benefits of Proper Story Point Implementation

- **Improved Sprint Goal Achievement**: Easier understanding of team's achievable scope
- **Unified Recognition**: Common understanding of task difficulty among team members
- **Streamlined Decision Making**: Efficient task division and priority judgment

## Cynefin Framework Overview

The Cynefin Framework classifies situations into five domains for decision-making and problem-solving contexts.

### Five Domains

| Domain | Characteristics | Approach |
|--------|----------------|----------|
| **Obvious** | Clear best practices, can be standardized | Sense → Categorize → Respond |
| **Complicated** | Requires expertise but analyzable and solvable | Sense → Analyze → Respond |
| **Complex** | Unpredictable outcomes, requires trial and error | Probe → Sense → Respond |
| **Chaotic** | Requires immediate action, solutions unclear | Act → Sense → Respond |
| **Confused** | Doesn't fit any domain, complete confusion | First organize situation and classify |

## Story Point Criteria Using Cynefin Framework

### Criteria Table

| Cynefin Domain | Characteristics | Story Point Range | Estimation Method |
|---------------|-----------------|-------------------|-------------------|
| **Obvious** | Clear work, can be standardized | **1-2 points** | Quick estimation based on past similar tasks |
| **Complicated** | Requires analysis/expertise but solution is visible | **3-5 points** | Planning poker with consensus building |
| **Complex** | Unpredictable outcomes, requires trial and error | **8+ points** | Insert spike (investigation task), break down then estimate |
| **Chaotic** | Requires urgent response, many unknown risks | **13+ points** | Prioritize urgent response, estimate after stabilization |
| **Confused** | Complete confusion, unclear where to start | **Cannot estimate** | Must organize tasks and identify domain first |

### Estimation Process

#### Step 1: Domain Classification

Identify domain using these questions:

1. **Can you see the solution immediately?** → Obvious
2. **Can it be solved with analysis or expertise?** → Complicated
3. **Are outcomes unpredictable, requiring trial and error?** → Complex
4. **Is it urgent with many unknown risks?** → Chaotic
5. **Doesn't fit any of the above?** → Confused

#### Step 2: Apply Domain-Appropriate Estimation Method

**For Obvious Tasks**:
- Reference past performance data
- Conduct rapid estimation
- Decide within 1-2 point range

**For Complicated Tasks**:
- Conduct planning poker
- Emphasize opinions from members with expertise
- Build consensus within 3-5 point range

**For Complex Tasks**:
- Execute spike (investigation/validation task) first
- Break down tasks based on investigation results
- Reclassify and estimate broken-down tasks

**For Chaotic Tasks**:
- Prioritize urgent response over story point assignment
- Reclassify and estimate after situation stabilization
- Set minimum 13+ points

**For Confused Tasks**:
- Task content organization needed before estimation
- Identify domain through requirements definition or investigation
- Apply appropriate domain method after identification

## Implementation Guidelines

### Team Adoption Process

1. **Learn Cynefin Framework**
   - Deepen team-wide understanding of the framework
   - Practice classification using past tasks as examples

2. **Adjust Criteria**
   - Fine-tune point criteria to match team characteristics
   - Validate criteria validity with sample tasks

3. **Set Trial Period**
   - Test run for 1-2 sprints
   - Compare and validate against traditional methods

4. **Continuous Improvement**
   - Review criteria and methods in retrospectives
   - Adjust according to team maturity

### Considerations

- **Subjectivity in Domain Classification**: Build consensus through discussion when members disagree
- **Tasks Spanning Multiple Domains**: Classify by dominant element or consider splitting
- **Changes Over Time**: Same tasks may change domains as project progresses

## Comparison with Traditional Methods

| Aspect | Traditional Relative Estimation | Cynefin-Based Method |
|--------|--------------------------------|----------------------|
| **Criteria Clarity** | Ambiguous (comparison with past tasks only) | Clear (based on domain characteristics) |
| **Uncertainty Handling** | Uniformly "estimate large" | Distinguish types of uncertainty |
| **Estimation Method** | Uniform planning poker | Select method based on domain |
| **Risk Reflection** | Depends on experience | Systematically classify and reflect risks |
| **Learning Cost** | Low | Medium (framework understanding required) |
| **Accuracy Improvement** | Gradual improvement | Early improvement effects expected |

## References

- [クネビンフレームワークを活用したストーリーポイントの考え方](https://bmf-tech.com/posts/%e3%82%af%e3%83%8d%e3%83%93%e3%83%b3%e3%83%95%e3%83%ac%e3%83%bc%e3%83%a0%e3%83%af%e3%83%bc%e3%82%af%e3%82%92%e6%b4%bb%e7%94%a8%e3%81%97%e3%81%9f%e3%82%b9%e3%83%88%e3%83%bc%e3%83%aa%e3%83%bc%e3%83%9d%e3%82%a4%e3%83%b3%e3%83%88%e3%81%ae%e8%80%83%e3%81%88%e6%96%b9) - Detailed explanation article of this method (Japanese)
- [Demystifying Story Point Estimation Using the Cynefin Framework](https://example.com) - Prior work on similar approaches
- Cynefin Framework by Dave Snowden - Original framework

---

**Note**: This method is an experimental approach that requires adjustment based on team characteristics and project nature. Continuous improvement and retrospectives are recommended to evolve it into the optimal form for your team.
