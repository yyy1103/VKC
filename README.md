# VKC
**Improving Knowledge-Based Visual Reasoning with Multi-Image Large Language Models**
-

The full code will be released upon acceptance of the paper.

![image](https://github.com/user-attachments/assets/e8a55419-9d21-4b92-b7dc-ec4abe166cfe)


Intruduction:
-
We revisit knowledge-based visual reasoning (KB-VR) in light of modern advances in multimodal large language models (MLLMs), and make the following contributions: (i) We propose Visual Knowledge Card (VKC) – a novel image that depicts spatial information of the query image and introduces external knowledge related to visual concepts in the image; (ii) We present VKC-based Multi-Image Reasoning (VKC-MIR) – a four-stage pipeline that generates and utilizes VKC to improve KB-VR.

VKC-MIR consists of four stages: 

(1) visual scene perception;

(2) external knowledge generation;

(3) knowledge image editing; 

(4) multi-image reasoning.

Preprocess datasets： 
-
Download OK-VQA and AOK-VQA dataset, following the PICa format （https://github.com/microsoft/PICa）

Large language models and multimodal tools
-
· Prepare Scene graph :
HiKER-SGG:  https://github.com/zhangce01/HiKER-SGGHiKER-SGG 

· Prepare Visualisation tools
graphviz:https://graphviz.org/

· Knowledge Generation:OPT-66B

·Seed-x-edit:https://github.com/AILab-CVC/SEED-X

·Image Object:
GLEE:https://github.com/FoundationVision/GLEE


Results:
-
![image](https://github.com/user-attachments/assets/1a5b61a2-0774-4cc4-8509-e297a1f3e979)

**Qualitative Analysis**
-

![image](https://github.com/user-attachments/assets/8d1a2131-53e1-42b4-a8af-14834b496630)



