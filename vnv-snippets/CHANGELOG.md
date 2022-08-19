# Change Log

All notable changes to the "vnv-snippets" extension will be documented in this file.

<!-- Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file. -->

## [Unreleased]

- TBD 

## [1.0.0] - 2022-08-19
### Added
The rest of the snippets!

- New snippets:
    - vnv-inject-c for INJECTION\_POINT\_C
    - vnv-func for INJECTION\_FUNCTION\_WRAPPER
    - vnv-func-c for INJECTION\_FUNCTION\_WRAPPER\_C
    - vnv-reg-point for Register\_Injection\_Point
    - vnv-iter for INJECTION\_ITERATION
    - vnv-iter-c for INJECTION\_ITERATION\_C
    - vnv-reg-iterator for Register\_Injection\_Iterator
    - vnv-func-plug for INJECTION\_FUNCTION\_PLUG
    - vnv-func-plug-c for INJECTION\_FUNCTION\_PLUG\_C
    - vnv-reg-plug for Register\_Injection\_Plug

### Changed
- vnv-iter for INJECTION\_LOOP\_ITER changed to vnv-loop-iter
  - disambiguates the relation between INJECTION\_ITERATION and INJECTION\_LOOP\_ITER
  - same done for vnv-iter-d

## [0.0.2] - 2022-08-16
### Added
- New snippets:
    - vnv-loop-begin for INJECTION\_LOOP\_BEGIN
    - vnv-loop-begin-c for INJECTION\_LOOP\_BEGIN\_C
    - vnv-loop-end for INJECTION\_LOOP\_END
    - vnv-iter for INJECTION\_LOOP\_ITER
    - vnv-iter-d for INJECTION\_LOOP\_ITER\_D
    - vnv-loop for injection loop block
    - vnv-loop-c for injection loop block with callback
- @title was prepended to each snippet argument for a VnV macro comment's title

### Changed
- text to describe a snippet's argument now better matches the source code of VnV
- snippets are now in alphabetical order in their json
