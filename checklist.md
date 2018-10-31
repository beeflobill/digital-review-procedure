# Digital Review Procedure

https://github.com/beeflobill/digital-review-procedure



1. Show and talk about the block list.
  The block list has all major blocks and briefly describes the function of each.
   
2. Read each block spec:
   * Signal inputs and outputs (not necessarily all the inputs and outputs, just signals)
   * Maximum and minimum input frequencies
   * Principle of operation (an algorithm, a process, a standard that’s conformed to)?
      - What does the block do?
   * List of the ways the block can fail and what will the consequences be for those failures?
   * What can go wrong on the inputs
   * What can go wrong with the outputs
   * Bypasses and enables
      - How is the block disabled?
      - How is the block bypassed?
      - What happens if the block is bypassed or disabled?  What will the outputs do?
   * Register list.  Which registers have a direct impact on this block?
   * Neighboring blocks
      - Upstream blocks, which ones feed the inputs?
      - Downstream blocks, what ones feed the outputs?
   * Clocks and resets
      - What clocks feed this block?
      - What domain crossings are there?
      - What resets feed the block?
      - Are there any special clock or reset behaviors?
