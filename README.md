Generating a Text using LLMs(Phi-3 mini)
When you use LLMS two models are : 1. the generative model itself 2. its underlying tokenizer
After doanloading the model next a pipline is created which encapsulates the model, tokenizer, and text generation process into a sinlge function
In this code block: 
return_full_text: by setting this to False, the prompt will not be returned, only the output will return
max_new_tokens: Setting the maximum number of tokens prevents long and unwieldly output
do_sample: By setting this false, the model always selects the next most probable token instead of having a sampling strategy
Next code block is a prompt. IT asks the LLM to tell a joke about chicken and prints the output.
