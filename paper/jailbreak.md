## 1. Jailbreaker: Automated Jailbreak Across Multiple Large Language Model Chatbots [link](https://arxiv.org/abs/2307.08715)

## 2. Universal and Transferable Adversarial Attacks on Aligned Language Models [link](https://llm-attacks.org/)

An interesting LLM jailbreak attack via gradient-based optimization. Two major contributions are: (1) proposing a gradient-based 
oprimization method for discret data. (2) defining the optimization problem of LLM jailbreak. Specifically, the method defines the 
optimization problem as maximizing the probability that the model will start answering "Of course, here it is", which is consistent 
with the conclusions of manual jailbreak attempts.

## 3. OPEN SESAME! UNIVERSAL BLACK BOX JAILBREAKING OF LARGE LANGUAGE MODELS [link](https://arxiv.org/pdf/2309.01446.pdf)

Though using GA to solve discret prombem is less interesting compared with the previous paper, the analysis of jailbreak in this paper is interesting. Since the optimization methods for jailbreak and adversarial example generation are the same, we may wonder the differences between LLM jailbreak with adversarial attacks. Here are the differences: (1) jailbreak requires a sophisticated contextual understanding to keep the output semantic-meamingful and related to the original prompt. (2) No certified explicit rules for jailbreak. Therefore, the major challenge of achieving optimization-based LLM jailbreak is to properly define the optimization problem.
