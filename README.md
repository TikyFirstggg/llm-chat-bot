# llm-chat-bot
Multimodality Pre-trained large models.
Science Question Answering (ScienceQA) is a new benchmark collected from elementary and high school science curricula, containing 21,208 multimodal multiple-choice science questions. It consists of a diverse set of science topics
and annotations of their answers with corresponding lectures and explanations. It further designs language models to learn to generate lectures and explanations as the chain of thought (CoT) to mimic the multi-hop reasoning process
when answering ScienceQA questions.
Dataset URL: https://scienceqa.github.io/#dataset
Dataset paper: https://arxiv.org/pdf/2209.09513
This project uses a combination of image pre-training model and LLM to become a multimodal LLM, which can answer questions that combine images and text. As the development leader, I first read and reproduced the VIT+GPT method in the paper Pan
Lu, Swaroop Mishra, Tony Xia, Liang Qiu, Kai-Wei Chang, Song-Chun Zhu, Oyvind Tafjord, Peter Clark, Ashwin Kalyan The
36th Conference on Neural Information Processing Systems (NeurIPS), 2022. After that, the project team created a BLIP model to replace the relatively backward VIT, generate more detailed text descriptions and transmit them to GPT. The study found that the accuracy rate was greatly improved (3%).
