# RL_notes_02

# Accelerating Reinforcement Learning for Autonomous Driving using Task-Agnostic and Ego-Centric Motion Skills

![title](../pictures/notes_02/title.png)

**{2022}, {Zhou Tong}, {Arixv: https://arxiv.org/pdf/2209.12072.pdf}**

## 0\. Summary

[写完笔记之后最后填，概述文章的内容，以后查阅笔记的时候先看这一段。注：写文章summary切记需要通过自己的思考，用自己的语言描述。忌讳直接Ctrl + c原文]

## 1\. Research Objective(s)

[ 作者的研究目标是什么？]

## 2\. Background

### 2.1 RL in autonomous driving

+ learning efficiency will quickly decay due to un-informed exploration and the sparse and delayed rewards

### 2.2 Pre-training policy & IL (expert demonstrations)

+ **unavailable** are expensive and labor-intense to collect and annotate if unavailable

+ **suboptimal** unbalanced in distribution and hardly optimal-guaranteed

+ **generalization** struggling to transfer to new tasks as the demonstrations are environment-conditioned or task-specific

### 2.2 RL Limitations: 

+ rarely reflect driving intentions

For example: 

![](../pictures/notes_02/tmp180C.png)

+ If offline training agent, it is hard to guarantee all essential skills

+ If task-specific, skill design limits the flexibility and expressiveness of motions. Hard to apply in dense traffic scenario.

## 3\. Method(s)

    TaEc-RL (RL with Task-agnostic and Ego-centric motion skills)

### 3.1 Overview

![](../pictures/notes_02/tmp190C.png)

+ design a task-agnostic and ego-centric (TaEc) motion skill library

+ distill these motion skills into a lowdimensional latent skill space

+ solve diverse, complex tasks like driving in multi-agent settings

### 3.2 

## 4\. Evaluation

[作者如何评估自己的方法？实验的setup是什么样的？感兴趣实验数据和结果有哪些？有没有问题或者可以借鉴的地方？]

## 5\. Conclusion

[作者给出了哪些结论？哪些是strong conclusions, 哪些又是weak的conclusions（即作者并没有通过实验提供evidence，只在discussion中提到；或实验的数据并没有给出充分的evidence]

## 6\. Notes

[不在以上列表中，但需要特别记录的笔记]

## 7\. References

[列出相关性高的文献，以便之后可以继续track下去]