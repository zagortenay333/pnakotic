A tiny markup parser and other eldritch horrors.

It's a single-header ISO C99 file (`pnakotic.h`), instructions in the file.

Check out `pnakotic_to_html.c` for a simple usage example.

Here is an interactive semi-formal documentation of the markup
language: http://zagortenay333.github.io/pnakotic  
There's no formal grammar available currently.

---

Do not rely on this lib in security sensitive situations, or do at own risk.

Although it's intended to be used in applications, has some test cases, was
fuzzed somewhat with afl, checked with clang-sanitizer, and can be compiled
with flags like `-Wall -Wextra`, no major effort is made to seriously harden it.
It's a learning project.