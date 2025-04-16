In the labs the following tasks are accomplished:

# Lab 1: Generative AI Use Case: Summarize Dialogue

In the practical lab of the course, I worked on a dialogue summarization task using generative AI. I explored how different input prompts influence model outputs and applied prompt engineering techniques to guide the model effectively. By experimenting with zero-shot, one-shot, and few-shot inference, I gained hands-on insight into how prompt design impacts the performance of large language models.

# Lab 2: Fine-Tune a Generative AI Model for Dialogue Summarization

I fine-tuned a pre-trained LLM (FLAN-T5 from Hugging Face) for improved dialogue summarization. I first applied full fine-tuning to enhance model performance and evaluated results using ROUGE metrics. Then, I implemented Parameter-Efficient Fine-Tuning (PEFT), compared outcomes, and found that PEFT offered significant efficiency gains with only a minor trade-off in performance.

# Lab 3: Fine-Tune FLAN-T5 with Reinforcement Learning (PPO) and PEFT to Generate Less-Toxic Summaries

I fine-tuned a FLAN-T5 model to generate less toxic content using Meta AI's hate speech reward model. The model, a binary classifier, predicts whether text is "hate" or "not hate." I applied Proximal Policy Optimization (PPO) to fine-tune the model, successfully reducing its toxicity and improving content safety.
