### 0.1.1, 15 March 2014

- Added extra doctests
- Resolved issues:
    - Issue #5: Running sequtil.property_ctd on sequence with length 1 results
                in float division by zero
    - Issue #4: Autocorrelation functions result in error if len(seq) == lag
    - Issue #3: Pseudo-amino-acid-composition calculation results in error if
                sequences contains ambiguous amino acids
    - Issue #2: Incorrect pseudo amino acid composition type 1 and 2 if
                len(seq) < lambda
    - Issue #1: Cannot calculate di-letter counts if seq contains letters that
                are not in alph.

### 0.1.0, 3 Octobre 2013 -- Initial release.
