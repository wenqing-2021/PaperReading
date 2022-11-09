# PaperReading
PaperReading Notes concerning Motion Planing &amp; Reinforcement Learning &amp; Robotics &amp; Autonomous Driving

## RL for autonomous driving

|#    | Abstract       |    Link |
|:---:|:---------------|:--------|
| 1   | 本文的研究场景为十字路口，交通参与者包含行人、车辆、自行车等。提出了一种动态排列的状态表征方法，该方法下生成的状态可以表示不同数量、不同类型的交通参与者。在结构化道路场景中，以最小化跟踪误差和约束违犯惩罚之和，构建最优化问题，利用梯度下降的方法进行求解，实现车辆的跟踪控制。实验表明，可以保证车辆通过十字路口的高效性、舒适性、安全性。| [2022_T_ITS_李升波](./RL/RL_notes_01_Self-Learned%20Intelligence%20for%20Integrated%20Decision%20and%20Control%20of%20Automated%20Vehicles%20at%20Signalized%20Intersections.md) |
| 2 | 专家演示中学习有利于探索，但收集成本高且是次优的。人类驾驶员可以适应各种各样的驾驶任务，且是在完整的技能空间中学习。基于以上两点，提出一种能够在完备的行驶技能空间中学习的RL算法。实验表明RL可以handle各类场景且具有高效率高性能| [2022_上海人工智能实验室](./RL/RL_notes_02_Accelerating%20Reinforcement%20Learning%20for%20Autonomous%20Driving%20using%20Task-Agnostic%20and%20Ego-Centric%20Motion%20Skills.md) |