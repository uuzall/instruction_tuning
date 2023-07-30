# Instruction-Tuning Pythia

According to a [paper] (https://arxiv.org/pdf/2306.04751.pdf) by Allen Institute for AI, they found out that fine-tuning a model on the ShareGPT data from [Hugging Face] (https://huggingface.co/datasets/anon8231489123/ShareGPT_Vicuna_unfiltered) performed better than GPT-3 Davinci more than 50% of the time according to humans. I wanted to test that myself and hence, this repo was born. 

I fine-tuned the Pythia 1b model on the ShareGPT model like they did, but I had to cap the max length to 512. I have to say that I am pleasantly surprised. I played around with the models after training it and it actually works quite well. Some outputs are stored in 'sample_out.txt.' I found out that it does not work that well in answering questions that are rooted in truth, it is way better at generating things that are open-ended. 