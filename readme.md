This is the THU version compiler of [piVC](https://cs.stanford.edu/people/jasonaue/pivc/), an education purposed verification language.

## Usage

## To-Do

A lot of work needs to do, include the followings and something other.

### Level I: You have to do

- [x] The grammar is not totally correct and sufficiently tested.
- [x] The design and implementation of CFG.
- [ ] The framework of verification algorithm and a baseline implementation.
  - [ ] SMT solver abstraction
  - [ ] substitution
- [ ] printer
  - [ ] control flow graph
    - [ ] more beautiful printer to avoid too long line
  - [ ] basic path
  - [ ] verification condition
  - [ ] counter model
- [ ] The documentation for code, task and environments.
- [ ] The testcases and judging system.

### Level II: Make things better

- [ ] label of annotation: now I just omit it for simplicity
- [ ] Target code (assembly) generator
- [ ] Find a student to test

### Level III: Bonus for fun

- [ ] VS Code syntax highlighter
