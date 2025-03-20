# Dataset Usage  

This repository utilizes data from [Anthropic's HH-RLHF dataset](https://github.com/anthropics/hh-rlhf), which includes human preference data and red teaming interactions aimed at improving language model alignment.  

## Dataset Overview  

### 1. Human Preference Data on Helpfulness and Harmlessness  
- Consists of text pairs labeled as **"chosen"** or **"rejected"** based on human feedback.  
- Used for training models via **Reinforcement Learning from Human Feedback (RLHF)**.  
- Data includes training and test splits across different model iterations.  
- **Reference Paper**:  
  - *[Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback*.](https://arxiv.org/abs/2204.05862)  

### 2. Red Teaming Data  
- Contains adversarial interactions between human red teamers and an AI assistant.  
- Includes metadata such as **harmlessness scores, model parameters, and red team attack strategies**.  
- **Reference Paper**:  
  - *[Red Teaming Language Models to Reduce Harms: Methods, Scaling Behaviors, and Lessons Learned](https://arxiv.org/abs/2209.07858)*.  

For more details, refer to the original dataset repository: [Anthropic HH-RLHF](https://github.com/anthropics/hh-rlhf).  