
# HI there！

Zhou Yiqun ｜ z-yq@live[.]cn  ｜

College of Computer Science and Technology, Zhejiang University

[github](https://github.com/Roswellii)

[BiliBili](https://space.bilibili.com/53309716)

wx：180_72926_017 （去掉下划线


## 🎓 教育背景

### [浙江大学](https://www.zju.edu.cn) (985 211 双一流) Zhejiang University

*2023 至今 /直博 / 计算机学院 | 计算机科学与技术专业 | 浙江大学智能汽车研究中心*

导师：潘之杰、杨国青

- 在博士阶段，我带领实验室团队支持了一款无人扫地车的落地运行，组织团队承接国家重大项目，并以这些工作为基础开展深入研究；

### [重庆大学](https://www.cqu.edu.cn) (985 211 双一流) Chongqing University

*2019 -- 2023 | 本科 | 计算机学院 |计算机科学与技术（卓越）专业 | 教育部卓越工程师培养计划*

- 在本科阶段，我带领团队参与了大量竞赛项目，掌握了无人车、ai、大数据、嵌入式等方向的基础技术，为我在博士阶段以无人车为核心的研究工作打下了基础。

---

## 🔧掌握技能
在算法与智能系统方向，具备多模态感知、点云语义分割、强化学习与视觉语言模型微调能力，熟悉 PyTorch、OpenMMLab 与 HuggingFace 框架，能独立设计并实现面向真实场景的模型改进与数据增强方案。

在机器人与无人系统方向，掌握 SLAM、路径规划、RTK 定位与视觉导航技术，熟悉 ROS/ROS2、Gazebo 与 carla、beamNG 仿真系统，具备多传感器融合与端到端部署经验。

在系统与工程实现方向，掌握 C++、Python 与嵌入式开发，掌握Docker、Redis、MySQL 与多线程通信架构，具备软硬件协同开发与项目落地能力。

## 🏆 校园活动

- 浙江大学优秀学生 (2024)
- 浙江大学计算机学院博士生会学术部部长（2024）
- 华为智能基座课程实验设计：基于ascend310的无人车（2023）
- 重庆大学十佳优秀共青团员 (2021)
- 教育部 - 华为智能基座 “未来之星” （华为智能基座奖学金，2022）
- 全国大学生嵌入式芯片设计竞赛三等奖（2022）
- 华为ICT大赛创新赛全国三等奖（基于ascend310的养老巡视车，2022）
- 国家级大学生创新训练计划优秀结题 （2022）
- 重庆大学华为智能基座社团技术部部长（2022）
- 重庆大学优秀共青团员 (2020, 2021, 2022)
- 重庆大学优秀学生 (2021)
- 重庆大学综合奖学金 (2020, 2021)



## 浙江大学期间
在浙江大学直博期间，我的研究与工程实践主要围绕导师公司 Techinao 低成本无人扫地车 项目展开 https://www.techinao.com

入学初期，我与公司团队共同梳理了无人清洁车的系统架构，推动系统达到量产标准，并将整体方案成功迁移至更低成本的 x86 工控平台。随后，我长期负责 SLAM、路径规划与通信系统的维护与场景适配，面向大规模业务需求牵头完成了 RTK 高精度定位导航、Fast-LIO 建图系统、大场景可视化性能优化 及 任务组合模块开发，支撑了系统在多种基础场景下的稳定运行。

目前，随着应用场景从封闭园区扩展至开放道路，我的工作重心从工程落地转向 urban micromobility（城市微型移动机器人）的具体研究，聚焦于在复杂、动态、非结构化的大规模城市环境中实现可靠的长程任务执行。主要研究方向包括：无地图自车定位与导航、狭窄空间运动规划以及社会化导航（social navigation），旨在提升微型城市机器人的自主感知、规划与交互能力。

## 正在进行的研究与项目
<img width="807" height="435" alt="image" src="https://github.com/user-attachments/assets/34f57166-6159-4bc2-8e7d-4d7c9e631168" />

1. MAPSV3： 基于 PointTransformerV3 主干网络，融合高精度地图与语义先验信息，提升稀疏点云在复杂场景下的空间感知精度与跨传感器泛化能力。
2. VLM 微调： 面向智慧工厂场景，通过遮挡和手写数字识别任务对视觉语言模型进行微调。采用基于 GRPO 的强化学习方法，引入针对退化 OCR 的奖励函数，使模型在处理模糊或不完整字符时能够保持视觉一致性并避免幻觉，从而提升其在退化视觉输入下的鲁棒性与多模态理解能力。
3. VLN： 将地图信息引入视觉语言导航（VLN）框架，实现基于地理语义与环境约束的路径推理与自主导航能力提升。
4. 强化学习窄路控制： 基于强化学习设计高安全性无人车控制算法，使车辆在狭窄道路与动态障碍环境中具备决策优化与风险自适应能力。
   
## 前期项目


### 科技部“新能源汽车”重点专项项目“汽车电控单元关键工具链开发”项目
2025年10月结项


<img width="400" height="733" alt="image" src="https://github.com/user-attachments/assets/dd881d75-100e-44c6-8d9d-907d4d44f610" />



作为子课题参与单位，我主要牵头完成ECU智能检测工具的开发与合并，完成了HIL机柜的线下调试。在北航现场期间，我负责完成子课题展示与答辩。最后阶段，我与项目组青年教师团队一起参与了全项目演示汇报的“难题-思路-解法-效果-指标”闭环逻辑梳理，完成了整个项目PPT最终冲刺优化。


### [CurbMapping: Reducing Blind Spots for Low-cost Autonomous Sweepers](https://www.bilibili.com/video/BV1erLuzgEYv/)

2025年10月 CAA2025（中国自动化大会）

<img width="443" height="169" alt="image" src="https://github.com/user-attachments/assets/3327853d-0e23-429f-8043-216f3e1ed264" />


CurbMapping 是一种面向低成本清扫车的 SLAM 方法，通过利用历史数据重建盲区、过滤动态物体、保留静态路缘用于规划，并结合方差动态加权里程计提升运动估计精度。实验证明该方法在有限传感器和计算资源下显著提升了地形感知和导航安全性。

### Dedicated Lanes for Intelligent and Connected Vehicles in Mixed Traffic

2025年8月 CIVS2025（第三届CCF智能汽车学术年会）

<img width="342" height="226" alt="image" src="https://github.com/user-attachments/assets/649a475d-a08e-46f4-b25f-3013724b0ce3" />


提出一种 车–路–云–人（VRCH）一体化架构，用于在混合交通环境下分阶段部署智能网联汽车（ICV）系统。该架构通过分布式基础设施和云端重新分配决策任务，以减轻车载负担，同时保证安全、效率和信任。论文提出了 专用自动驾驶车道（DALs）分阶段部署路线图，包含数字凭证接入与行驶中模式切换机制，并强调人在环的人机交互。未来工作包括试点区域部署、基础设施协同设计和场景化验证。

这篇文章主要描述了算法研究的场景：通过控制场景，给出更多信息，辅助端侧感知。

### 扫地车视觉贴边

*2025年3月 -- 至今*

在西安辅道与西湖白堤运行时，我们遇到了大场景slam不稳定的问题。因此启动了结构化路面下的视觉贴边研究。目前已经完成了moge2+seg算法的验证。接下去，正在朝速度优化和端到端控制方向推进。

[扫地车单目视觉测试](https://www.bilibili.com/video/BV1iJb7zeELX/)

<img width="557" height="211" alt="image" src="https://github.com/user-attachments/assets/20c6c838-231e-40d6-934a-cae463fc9390" />
<img width="497" height="413" alt="image" src="https://github.com/user-attachments/assets/3c80a9bf-1f5f-43fd-a203-0fc4527d6593" />



### 天门山99道弯竞速挑战赛
*2025年3月 -- 至今*

[收集数据中···](https://www.xiaohongshu.com/discovery/item/68a9033a000000001b01d6e8?source=webshare&xhsshare=pc_web&xsec_token=ABJPESFPZpxIgYImuGPLlRJYTpq5nestCiSuy52Hrj2Ro=&xsec_source=pc_share)

我们计划使用纯视觉技术，实现PIX底盘无人车在天门山99道弯山路的安全运行。目前完成了二轮lgsvl下的仿真赛，并在天门山现场收集了实地数据。我们将于10月开始线下比赛。


### 印染工厂视觉的布车定位系统
杭州天富德泰信息技术有限公司  
*2025年6月 -- 至今*

<img width="830" height="445" alt="image" src="https://github.com/user-attachments/assets/6e7d9e16-eb2a-4109-b107-7c1d369b89a2" />


针对印染工厂布车数量大、编号涂写乱而导致的运输管理难题，提出了工厂现有的大量RTSP摄像头实现布车编号识别与定位的方案，基于深度学习、多模态大模型技术，将编号定位接入ERP平台。已经交付。


### 印染工厂载人巡检移动平台
杭州天富德泰信息技术有限公司  
*2025年3月 -- 2025年5月*

<img width="712" height="481" alt="image" src="https://github.com/user-attachments/assets/70eee830-ed51-4350-9f3e-ffe99a0ce5e7" />

<img width="249" height="299" alt="image" src="https://github.com/user-attachments/assets/896dbbbd-be9d-4a5f-add7-24b5890d52fe" />


使用线控底盘，选配激光雷达、工控机，组成一套基于ROS的移动平台。在此基础上，开发了建图、定位、导航系统，连接公司的ERP平台、实现生产管理调度，实现了工厂车间的定点载人巡检功能。项目已完成交付。


### MAPS（Map-Assisted Point cloud Segmentation）*（进行中)*

*2025年3月 -- 至今*

<img width="260" height="258" alt="image" src="https://github.com/user-attachments/assets/4cae4ece-7d5b-46d1-866a-c3a9be71740c" />


基于序列化点云，将道路拓扑结构融合到激光雷达语义分割任务中，使得稀疏、远距离下的点云分类更加准确。目前在nusc上已有性能提升，尚在进一步优化。未来还将引入丰富的先验信息，比如其他车辆、施工区域等。


### SmartKit: User-Friendly Robot with Multiple Operating Systems

2024年3月 IROS2024 二作

<img width="449" height="338" alt="image" src="https://github.com/user-attachments/assets/215cb2a1-0303-4e55-b5ad-bef3586ca5f3" />


一种面向移动机器人的混合关键性系统（MCS）。通过虚拟化技术实现高效的硬件利用，SmartKit 能够在保障安全的前提下同时执行不同关键性的任务。我主要负责实验环节。

### TECHINAO 无人扫地车*（进行中)*

*2022年7月 -- 至今*

2022年-2023年我将无人扫地车从 DEMO 发展到实地全功能运行。在此期间，我完成了建图定位、感知、规划控制、通讯等模块的开发。2024年至今，在实验室同学的支持下，我的工作主要涉及分解场景需求，设计技术方案，组织日常开发，推进现场部署。我们目前已经在多个场景部署，并完成了多个车型的迭代。

### 覆盖汽车全场景安全的电控单元软件自动化测试验证工具

*2023年11月 -- 2025年5月 | 负责人（国家重点研发项目）*

<img width="422" height="329" alt="image" src="https://github.com/user-attachments/assets/03f1d721-9134-422f-aedd-1bcf08f5b05c" />


开发汽车 ECU 智能检测软件平台，开发了 ASAM 协议下的检测系统，与研华、NI 等厂家的 HIL 设备对接。此外，负责项目文档撰写、结题答辩等工作。



## 重庆大学期间
在本科阶段，我的主要兴趣在无人车和硬件设备上，参与了不少有趣的竞赛，并将一些成果转化成国创项目与学院的课程实验。
这一阶段的无人车工作主要都是基于ROS+SLAM+经典规划控制的项目。这一阶段的硬件工作则主要涉及FPGA开发，构建流水线的CPU。我也参与了几个算法研究，涉及多智能体系统和软件工程。


- Understanding the Implementation Issues When Using Deep Learning Frameworks（2024年1月）
- Privacy-Preserving Dynamic Average Consensus via Random Number Perturbation（2022年7月）


### 基于 ROS 的居家养老看护小车

*2021年6月 -- 2022年6月 | 团队负责人 / 无人车系统开发 / 3D 外壳建模*

国家级大学生创新训练计划优秀结题

团队开发了一台看护小车来降低独居老人生活风险。具体来说，我们基于 ROS 搭建了无人车定位与控制系统，基于 Pytorch 开发了人体检测的功能，并搭建了微信小程序支持远程操作，还设计并打印了 3D 外壳。该系统还部署在国产 AI 平台华为昇腾 200DK 上，并在竞争激烈的 2021 华为中国大学生 ICT 大赛进入决赛，获全国三等奖。

### 五级流水线 MIPS 架构

*2021年7月 -- 2021年8月 | 团队负责人 / AXI 开发*

龙芯杯优胜奖

团队基于 Verilog 语言设计实现了 MIPS 架构 CPU，支持基础操作、异常中断等全面功能，顺利通过龙芯中科全部 84 个功能测试点以及系统级测试。基于伪 LRU 算法实现 4KB Cache，并将系统进一步改写成双发射架构后通过基础操作测试。

### [基于 FPGA 的自行车传感器系统](https://www.bilibili.com/video/BV1ep4y167TJ/)

*2020年9月 -- 2020年11月 | 团队负责人 / FPGA 开发 / 视频剪辑*

全国大学生嵌入式芯片设计竞赛三等奖

由于我们常常找不到自己的自行车，团队在 Basys3 FPGA 开发板上实现了蓝牙、电子车锁、超声波的驱动，实现手机遥控开锁、后车靠近报警功能。参加全国大学生嵌入式芯片设计竞赛，获全国三等奖；作为重庆大学计算机学院优秀学生项目参与 2021 年重庆大学科技节。





