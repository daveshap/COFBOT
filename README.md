# COFBOT
Simple chatbot based on my Core Objective Functions and Discord

Current COF model is `curie:ft-user-aev4t8pdy0qsyqxayyjuuqut-2021-10-23-13-08-17`

## Tasks

1. Homogenize all COF data (fill in the blanks so that each COF has all the same contexts)
2. Compile input data (see below format)
3. Generate output training data. Probably will just use few-shot examples with the input data. I can manually write a bunch of responses and then generate from there using DAVINCI.

## Data format

Input template

```
CONTEXT:

<<CONTEXT>>

REDUCE SUFFERING:

<<COF1>>

INCREASE PROSPERITY:

<<COF2>>

INCREASE UNDERSTANDING:

<<COF3>>

OUTPUT:
```

Output will just be Raven's chat output.