# The Bits Between the Bits by Matt Godbolt

https://github.com/CppCon/CppCon2018/blob/master/Presentations/the_bits_between_the_bits/the_bits_between_the_bits__matt_godbolt__cppcon_2018.pdf

https://youtu.be/dOfucXtyEsU

## 3/10/2019

The page 26: "WHERE DO THESE FUNCTIONS COME FROM?" is the first obstacle I need resolve.

Bird view:
 1. The example in page 16 is the clue, leading us to the question: how is `numFoos` initialized
 2. Page 24: mystery functions
 3. Page 34/35: `__init_array_start` & `__init_array_end`
 4. Linker is the anwser
 5. Conclusion
