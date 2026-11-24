# LowSky-UAV-Papers
A curated reading list for low-altitude UAV control, recognition, navigation, localization, and multimodal information processing.

## 开放词汇-无人机-导航/航迹预测/航迹规划
### 2026：
### [1] 1Rao P, Zhang W, Balestriero R, et al. Skyjepa: Learning long-horizon world models for zero-shot sim-to-real control of quadrotors[J]. arXiv preprint arXiv:2606.23444, 2026.（GB/T引用格式）
SkyJEPA：面向四旋翼无人机零样本 sim-to-real 控制的长时程世界模型学习
<details>
<summary>摘要</summary>
精确的动力学模型对于机器人系统的知情决策至关重要，特别是对于在不确定条件下运行的敏捷飞行器而言。神经网络动力学模型对于捕获复杂的非线性效应具有吸引力，但现有的预测方法难以进行长时预测，因为它们的自回归滚动机制放大了误差随时间的变化。联合嵌入预测结构( Joint Embedding Predictive Architectures，JEPA )通过在潜在空间中建模动态提供了一种令人信服的替代方案，但先前JEPA风格的机器人导航方法主要是针对运动学级规划进行研究的，在高频控制方面的研究有限。在这项工作中，我们介绍了用于实时四旋翼控制的JEPA风格模型。 该方法将潜在动力学模型与一种新颖的物理启发探测器相结合，将冻结的潜在状态映射到可解释的状态，从而实现基于物理的长视距预测。此外，我们将学习到的模型与基于采样的最优控制解决方案相结合，以利用其在嵌入式硬件上实时控制的预测能力。最后，为了减少对昂贵和不安全的真实世界数据收集的依赖，我们开发了用于自动生成数据集的结构化管道。大量的开环和室外闭环实验证明了准确的预测，鲁棒的零样本实时传输，以及在不同操作条件下的强泛化能力。
<img width="1761" height="510" alt="image" src="https://github.com/user-attachments/assets/a4aa11e3-9604-4bbc-85f9-b45ced7e27d6" />
对提出的框架进行概述:我们学习了一个JEPA风格的潜在动力学模型，并通过一个物理启发的探测器将抽象的嵌入映射到物理上有意义的状态，从而实现了稳定的长视距四旋翼飞行器预测。该模型完全基于领域随机化的仿真数据进行训练，并部署在基于采样的控制器中，在室外飞行实验中得到了验证，实现了实时执行和鲁棒的零样本近真实传输。
</details>

### 



## 开放词汇-低空-感知/识别/检测/定位


## 低空-多模态信息处理


## VLA


## 多模态hash检索


## 多模态信息融合



## 锂电池分类


