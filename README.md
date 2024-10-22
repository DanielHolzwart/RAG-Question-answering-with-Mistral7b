# RAG-Question-answering-with-Mistral7b

Large language model have billions of paramters and are often trainied on publically available data. Having all this knowledge available, they sometimes struggle to give precise answers and reasoning to questions.
Moreover, the model's knowledge is static in the sense that, quite often, it does not have access to real-time data. 

To have better results on predetermined tasks, fine-tuning is often an appropiate choice. However, in this workbook we will look at retrival augmented generation (=RAG). This is a powerfull application to query text passages
and give the model the direction to extract the answer from. In this way, the output of the model is much more dynamic and does not involve the costly fine-tuning process.

The model we will be looking at the Mistral7b which has already been fine-tuned on instruction tasks https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2. We will see how RAG works within the llamaindex framework and make some simply tests.
