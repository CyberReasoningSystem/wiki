- [Generic Research](#generic-research)
- [Generic Binary Analysis](#generic-binary-analysis)
  - [Papers](#papers)
  - [Tools](#tools)
- [Cyber Reasoning Systems](#cyber-reasoning-systems)
  - [Papers](#papers-1)
  - [Tools](#tools-1)
- [Vulnerable Programs](#vulnerable-programs)
  - [Datasets](#datasets)
- [Enumerations](#enumerations)
  - [Tools](#tools-2)
- [Attack Surface Approximation](#attack-surface-approximation)
  - [Papers](#papers-2)
- [Fuzzing](#fuzzing)
  - [Tools](#tools-3)
  - [Workshops](#workshops)
  - [Videos](#videos)
- [Symbolic Execution](#symbolic-execution)
  - [Tools](#tools-4)
- [Emulation](#emulation)
  - [Tools](#tools-5)
- [Observations](#observations)

---

# Generic Research

- [Sci-Hub](https://sci-hub.se/) for searching papers
- [Connected Papers](https://www.connectedpapers.com/) for searching related papers
- [IEEE Computer Society](https://www.computer.org/) for papers

# Generic Binary Analysis

## Papers

- (State of) The Art of War: Offensive Techniques in Binary Analysis
- Practical Binary Analysis

## Tools

- [LIEF](https://lief-project.github.io/doc/latest/index.html), a Python 3 library capable of processing, modifying, and abstracting executable file 
- [Angr](https://angr.io/) and [angr-management](https://github.com/angr/angr-management), a Python 3 libray for static and dynamic binary analysis

# Cyber Reasoning Systems

## Papers

- The Mayhem Cyber Reasoning System
- Xandra: An Autonomous Cyber Battle System for the Cyber Grand Challenge
- Rise of the HaCRS
- A Honeybug for Automated Cyber Reasoning Systems
- Survey of Automated Vulnerability Detection and Exploit Generation Techniques in Cyber Reasoning Systems

## Tools

- [HaCRS](https://github.com/ucsb-seclab/hacrs), the repository of HaCRS
- [Mechanical Phish](https://github.com/mechaphish), the organization of Mechanical Phish

# Vulnerable Programs

## Datasets

- [DARPA](https://github.com/orgs/CyberGrandChallenge/repositories), a repository with the samples used in DARPA's Cyber Grand Challenge, on DECREE OS
- [`cb-multios`](https://github.com/trailofbits/cb-multios), a repository with the samples used in DARPA's Cyber Grand Challenge, migrated to multiple operating systems (Windows, Linux, macOS)
- [NIST's Juliet 1.3 Test Suite](https://github.com/arichardson/juliet-test-suite-c), a repository containing the samples of Juliet 1.3
- [NIST's C Test Suite](https://github.com/CyberReasoningSystem/nist_c_test_suite), a repository containing the samples of C Test Suite
- [PDF.js](https://github.com/mozilla/pdf.js/tree/master/test/pdfs), a repository containing PDFs used to test the Mozilla's in-browser reader

# Enumerations

## Tools

- [CWE Enumeration](https://cwe.mitre.org/data/definitions/699.html) for weaknesses enumeration

# Attack Surface Approximation

## Papers

- Approximating Attack Surfaces with Stack Traces

# Fuzzing

## Tools

- [Peach](https://github.com/MozillaSecurity/peach), a generational fuzzer
- [AFL](https://github.com/google/AFL), a (now unmaintained) mutational fuzzer
- [AFL++](https://aflplus.plus/), a fuzzer continuing AFL with additional features
- [River](https://github.com/unibuc-cs/river), a fuzzer using AI
- [boofuzz](https://github.com/jtpereyda/boofuzz), a network fuzzer based on specifications
- [AFLNet](https://github.com/aflnet/aflnet), a greybox network fuzzer, based on AFL

## Workshops

- [The Fuzzing Book](https://www.fuzzingbook.org/)

## Videos

- [FUZZING FOR BEGINNERS (KUGG teaches STÖK American fuzzy lop)](https://www.youtube.com/watch?v=O3hb6HV1ZQo) for finding a 0-day in nginx with AFL
- [Life of an Exploit: Fuzzing PDFCrack with AFL for 0days](https://www.youtube.com/watch?v=8VLNPIIgKbQ) for finding a 0-day in PDFCrack with AFL
- [afl-unicorn: Fuzzing Arbitrary Binary Code](https://medium.com/hackernoon/afl-unicorn-fuzzing-arbitrary-binary-code-563ca28936bf) for Unicorn support in AFL, namely `afl-unicorn`
- [afl-unicorn: Part 2 — Fuzzing the ‘Unfuzzable’](https://hackernoon.com/afl-unicorn-part-2-fuzzing-the-unfuzzable-bea8de3540a5) for using `afl-unicorn` to discover a bug into a function, bypassing limitations imposed by input verifications
- [Fuzzing101 with LibAFL - Part V: Fuzzing LibXML2](https://epi052.gitlab.io/notes-to-self/blog/2022-01-17-fuzzing-101-with-libafl-part-5/) for using `libafl`'s Python 3 binding to fuzz LibXML2
- [Blackbox Fuzzing #1: Start Binary-Only Fuzzing using AFL++ QEMU mode](https://www.youtube.com/watch?v=sjLFf9q2NRc) for fuzzing `pdfinfo` utility with AFL++ in QEMU, binary-only mode

# Symbolic Execution

## Tools

- [Manticore](https://github.com/trailofbits/manticore), a tool for symbolic execution

# Emulation

## Tools

- [Qiling Framework](https://github.com/qilingframework/qiling), a cross platform and multi arch lightweight emulator

---

# Observations

- The first heading level is for purpose, the next one is for resource category.
- All the papers mentioned above are in the `bibliography` folder.