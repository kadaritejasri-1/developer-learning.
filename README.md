# Developer Learning Journey

## Current Focus
- Python programming
- Data Structures and Algorithms
- Generative AI and LLMs
- Retrieval-Augmented Generation (RAG)
- REST APIs
- Open-source contributions
- Git and GitHub

## Current Open-Source Investigation
**Project:** OpenRAG

**Issue:** #1460

**Topic:** Incorrect source citation detection caused by regex matching.

## Goals
- Build practical projects.
- Understand real-world codebases.
- Fix open-source issues.
- Improve software development skills.


## New Development – Pull Request #1483

Another contributor has opened PR #1483 to address Issue #1460.

### Proposed Solution

- Modified the regex in `source_filtering.py`.
- Added a negative lookbehind to prevent matching `source` or `sources` inside longer words.
- Added test cases to verify the behaviour.

### Current Status

The fix has been proposed through PR #1483. It still needs to be reviewed and merged before the issue can be considered officially resolved.

### My Learning and Next Steps

1. Understand the original bug.
2. Study the proposed regex modification.
3. Understand the pytest test cases.
4. Investigate possible edge cases.
5. Find another issue for an independent contribution.

### Learning Outcome

Learned how regular expressions are used in Python source filtering and how open-source contributors investigate bugs, propose fixes and write tests.
