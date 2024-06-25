# Multibeam Forward-looking Sonar Video Object Tracking using Truncated L1-L2 Sparsity and Aberrances Repression Regularization
## Results on MFLS datasets
![image](https://github.com/KellySui/L1-L2ARDCF/blob/main/results/OR_new.png)
![image](https://github.com/KellySui/L1-L2ARDCF/blob/main/results/CLE_new.png)
## Videos of L1-L2ARDCF_HC tracking results on the datasets
### Results on Qingxian
https://github.com/KellySui/L1-L2ARDCF/assets/106424240/84ea66f1-4064-4e33-994f-ea1d8f818c19

The challenges included in this video are: occlusion, random ray interference and ambiguous targets. L1-L2ARDCF is consistently more accurate in localising AUV.
### Results on Yellow Sea
https://github.com/KellySui/L1-L2ARDCF/assets/106424240/604eede1-0fe1-4529-b794-343da1d943de

The main challenge contained in this video is: background clutter, where the background noise in the sequence is highly influential, resulting in the AUV features not being visible.
### Results on Enshi1
https://github.com/KellySui/L1-L2ARDCF/assets/106424240/01faa036-18b5-4021-a800-f7938a47e8df

The challenges included in this video are: scale variation, fake target and tugboat wake. The main reasons for the scale variation is the different angles of the AUV's motion to the sonar, which affects its appearance, fake targets, which is also a common challenge in underwater environments, and tugboat wake, which are a special challenge unique to the characteristics of our experimental conditions.
### Results on Enshi2
https://github.com/KellySui/L1-L2ARDCF/assets/106424240/d79e9b6b-c250-44ce-8ee6-9633bf2ec519

The challenges included in this video are: large-scale variation, disturbances with more similar characteristics to the target, and tugboat wake. And the movement of the target has more maneuverability compared to the previous three videos.
### Results on Enshi3
https://github.com/KellySui/L1-L2ARDCF/assets/106424240/23473204-a9c0-4f9c-a232-7094e775f76c

The challenges included in this video are: The target has a weak feature when it first enters the sonar's field of view, followed by a large variation, and is also interference by random rays during its motion。 When close to the sonar, as the platform is dynamic, it is also affected by the wake of the tugboat. The overall features are variable and unclear.

## Publication
Please cite the above publication if you use the code or compare with the L1-L2ARDCF tracker in your work. Bibtex entry:
@ARTICLE{Sui2024,  
  author={Sui, Xueqiong and Pan, Han and Jing, Zhongliang and Leung, Henry},  
  journal={IEEE Robotics and Automation Letters},   
  title={Multibeam Forward-Looking Sonar Video Object Tracking Using Truncated L1-L2 Sparsity and Aberrances Repression Regularization},   
  year={2024},  
  volume={9},  
  number={2},  
  pages={1122-1129},  
  doi={10.1109/LRA.2023.3342669}}
