# DSC180A-Methodology-5

**Name:** Shreya Sudan (ssudan@ucsd.edu)

**Section:** A17

**Mentor:** Barna Saha

---
## Quarter 2 Project Specifications:

**1. What is the most interesting topic covered in your domain this quarter?**

As our domain explores a relatively novel area, most of the topics were intriguing. However, I thought that SemanticSmooth was a particularly elegant technique to protect LLMs from jailbreaking attacks. 

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

Although SemanticSmooth performs well against jailbreaking attempts, while safegaurding utility of the LLM, it's computationally expensive and takes a considerable amount of time to execute. I'd like to optimize this technique to be faster and less expensive. 

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

So far, we simply replicated the PAIR and SemanticSmooth techniques for the Quarter 1 Project. For the second quarter, I'd like to experiment with different LLMs and optimize SemanticSmooth. Moreover, PAIR is not as impressive as it functions counterintuitively. I'd like to investigate its function in greater depth.

**4. What other techniques would you be interested in using in your project?**

To further enhance the robustness and efficiency of SemanticSmooth, I would be interested in exploring the following techniques:
- **Knowledge Distillation:**
  Using a smaller, distilled version of a large LLM to reduce computational costs while retaining high performance.   This could potentially make SemanticSmooth faster and less resource-intensive.

- **Adversarial Training:**
  Incorporating adversarial examples explicitly during the training phase to improve the model's resilience against   jailbreaking attacks.

- **Sparse Representations:**
  Leveraging sparse representations in the LLM's architecture or processing pipeline to reduce computational load     and optimize resource usage during SemanticSmooth execution.

- **Dynamic Pruning:**
  Implementing dynamic pruning techniques to skip less critical computations at runtime, thereby improving           execution speed without significant utility loss.

- **Hybrid Models:**
  Combining rule-based methods with SemanticSmooth to mitigate attack vectors while decreasing dependency on high     computational resources.
