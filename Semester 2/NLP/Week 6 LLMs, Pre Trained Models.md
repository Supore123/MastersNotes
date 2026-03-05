--> LLMs and Transformers 
-- Need to pick her modules, review the required slides

What comes after Transformers?
- LLMS! 
- Word level tokens are not enough -- we need subwords a.k.a Tokens.
- We need to go through subwords
- If we are choosing subword tokenization -- how do we determine between character levels vs Word levels
- We determine these subwords by the frequency of the words or not. 

Byte Pair Encoding (BPE)
- This is a method of subdivision, used in LLMs today, its just how we pair frequent symbols and chars to numbers until a vocab size is met.

Why do we pre-train? -- We are effecitvely teaching the LLM to learn english -- then training occurs on specific terms.

So pre-train is just learning how to predict the next set of tokens.
Pretraining operates on the encoder, decoder, or encoder-decoder models setup, This is how the allowance operates

Parameter -efficient fine tuning (PEFT) --> This is a method of how we determine our adapting and handling of the training

