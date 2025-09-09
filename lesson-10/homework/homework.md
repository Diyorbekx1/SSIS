1. On what Purpose we use Fuzzy LookUp in SSIS?  --Fuzzy Lookup is used for data cleansing and matching.
2.   What does "Similarity Threshold" indicate?  --It’s a numeric value (0–1) that defines how similar two strings must be to be considered a match.
3. Can we connect to other types of connections in Fuzzy LookUp? -- No.
4. What does Fuzzy LookUp return as output when it can't find any rows? -- It still returns the input row, but lookup columns will be NULL.
5.  Can we use Fuzzy Lookup columns for further transformations? Downsides? -- Yes, you can pass matched values to the destination.
6.  What happens when we put "Similarity Threshold" to 1? -- Only exact matches are returned
7.   What are Parent and Child Packages and why do we use them? --A Parent Package is the main controller. A Child Package is called by the parent.
We use them for modularity, reuse, and maintainability.
8. Can we Pass values from Parent to Child? -- Yes.
9.  Can we get values from Child back to Parent? -- Yes.
10.  


     
