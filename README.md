Dialogue Summarization with Generative AI and Fine-Tuning
Overview
This project focuses on fine-tuning a generative AI model to enhance dialogue summarization capabilities. It involves exploring prompt engineering techniques, comparing inference methods (zero-shot, one-shot, few-shot), and fine-tuning the FLAN-T5 model using Proximal Policy Optimization (PPO) to reduce toxicity and improve summarization. The project also demonstrates Parameter Efficient Fine-Tuning (PEFT) to balance performance and resource efficiency.

Objectives
Dialogue Summarization

Explore how input prompts influence model outputs.
Compare zero-shot, one-shot, and few-shot inferences for prompt engineering.
Use FLAN-T5, a high-quality instruction-tuned model, to summarize dialogue effectively.
Toxicity Reduction

Fine-tune the model using Meta AI's hate speech reward model to generate less toxic content.
Implement Proximal Policy Optimization (PPO) to refine the model's predictions.
Fine-Tuning Approaches

Perform full fine-tuning of the FLAN-T5 model and evaluate results using ROUGE metrics.
Explore Parameter Efficient Fine-Tuning (PEFT) to optimize resource usage while maintaining acceptable performance.
Methodology
1. Prompt Engineering
Zero-Shot Inference: Generate summaries without any example prompts.
One-Shot Inference: Provide one example prompt for better results.
Few-Shot Inference: Use multiple example prompts to guide the model towards desired outputs.
2. Model Fine-Tuning
Base Model: FLAN-T5, a pre-trained model designed for instruction-based tasks.
Toxicity Reduction: Utilize Meta AI's hate speech reward model, a binary classifier that predicts "not hate" or "hate" labels, to reward less toxic outputs.
Optimization: Apply PPO to align the model's outputs with reduced toxicity objectives.
3. Evaluation
ROUGE Metrics: Measure the quality of generated summaries against ground truth data.
PEFT: Assess the trade-offs between resource efficiency and model performance during fine-tuning.
