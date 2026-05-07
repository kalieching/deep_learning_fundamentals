
#### 05-01-2026

I am beginning a daily journey to improve my deep learning, robotics, and general engineering skills. This will serve as a journal to record my progress over time.

The main concepts I will cover:
- Fundamentals (MNIST)
- Transformers
- Action Chunking Transformers
- Diffusion Policy
- Reinforcement Learning (SAC, Q-Learning, etc.)

#### 05-03-2026 - Transformers

I read this chapter: https://d2l.ai/chapter_attention-mechanisms-and-transformers/queries-keys-values.html

Key notes:
- Keys and values are the pairings that exist in a database, while queries are requests to that database.

#### 05-04-2026 - Transformers

I read this chapter: https://d2l.ai/chapter_attention-mechanisms-and-transformers/attention-scoring-functions.html 

Key notes:
- Why use dot product?
    - It's a very intuitive method to capture the "distance" between two vectors Q and K to compute a similarity score.
    - When you have two vectors, 


#### 05-05-2026 - Transformers

Given a sequence of tokens, attention lets each token determine which tokens it should pay attention to.
- Q: What am I looking for?
- K: What do I tell about myself?
- V: What do I contribute if my associated key is selected?

The key equation is Attention(Q, K, V) = softmax(QK^T / sqrt(d_k)) * V.


#### 05-06-2026 - Whole-Body Control Using RL for Humanoids

I have been working on a side project to bring up a whole-body control RL policy, train using sim, and deploy on a simulated humanoid robot. So far, I completed the full IsaacSim and IsaacLab setup and got comfortable with the tools.