# Ideas for Further Development

## Dataset

- Adding support to [`cb-multios`](https://github.com/trailofbits/cb-multios)
- Creating a better interface for test suites parsers as it is too permissive now 

## Attack Surface Discovery

- Pairwise testing of arguments
- Using a Ghidra container to avoid the local installation step

## Vulnerability Detection

- Static analysis for identifying fuzz-able parameters
- Statistics extraction about the fuzzing session
- Coverage convergence as a stopper for the fuzzing session (see Driller)
- Usage of AFL++'s persistent mode