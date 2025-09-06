# 2025 Fall COMP6211J Presentation Topics

## Category 1.  Architecture and Network for LLM

### Topic 1. AI Chip Design.

```
@inproceedings{coburn2025meta,
  title={Meta's Second Generation AI Chip: Model-Chip Co-Design and Productionization Experiences},
  author={Coburn, Joel and Tang, Chunqiang and Asal, Sameer Abu and Agrawal, Neeraj and Chinta, Raviteja and Dixit, Harish and Dodds, Brian and Dwarakapuram, Saritha and Firoozshahian, Amin and Gao, Cao and others},
  booktitle={Proceedings of the 52nd Annual International Symposium on Computer Architecture},
  pages={1689--1702},
  year={2025}
}

@inproceedings{liu2025sparsity,
  title={The Sparsity-Aware LazyGPU Architecture},
  author={Liu, Changxi and Yu, Miao and Sun, Yifan and Carlson, Trevor E},
  booktitle={Proceedings of the 52nd Annual International Symposium on Computer Architecture},
  pages={1020--1034},
  year={2025}
}

@inproceedings{guo2025transitive,
  title={Transitive Array: An Efficient GEMM Accelerator with Result Reuse},
  author={Guo, Cong and Wei, Chiyue and Tang, Jiaming and Duan, Bowen and Han, Song and Li, Hai and Chen, Yiran},
  booktitle={Proceedings of the 52nd Annual International Symposium on Computer Architecture},
  pages={990--1004},
  year={2025}
}

@inproceedings{feng2025topology,
  title={Topology-Aware Virtualization over Inter-Core Connected Neural Processing Units},
  author={Feng, Dahu and Feng, Erhu and Du, Dong and Xu, Pinjie and Xia, Yubin and Chen, Haibo and Zhao, Rong},
  booktitle={Proceedings of the 52nd Annual International Symposium on Computer Architecture},
  pages={1210--1224},
  year={2025}
}
```

### Topic 2. Heterogeneous Hardware for LLM Services.

```
@inproceedings{song2024powerinfer,
  title={Powerinfer: Fast large language model serving with a consumer-grade gpu},
  author={Song, Yixin and Mi, Zeyu and Xie, Haotong and Chen, Haibo},
  booktitle={Proceedings of the ACM SIGOPS 30th Symposium on Operating Systems Principles},
  pages={590--606},
  year={2024}
}

@inproceedings{li2025h2,
  title={H2-LLM: Hardware-Dataflow Co-Exploration for Heterogeneous Hybrid-Bonding-based Low-Batch LLM Inference},
  author={Li, Cong and Yin, Yihan and Wu, Xintong and Zhu, Jingchen and Gao, Zhutianya and Niu, Dimin and Wu, Qiang and Si, Xin and Xie, Yuan and Zhang, Chen and others},
  booktitle={Proceedings of the 52nd Annual International Symposium on Computer Architecture},
  pages={194--210},
  year={2025}
}

@inproceedings{moon2025hybe,
  title={Hybe: GPU-NPU Hybrid System for Efficient LLM Inference with Million-Token Context Window},
  author={Moon, Seungjae and Cha, Junseo and Park, Hyunjun and Kim, Joo-Young},
  booktitle={Proceedings of the 52nd Annual International Symposium on Computer Architecture},
  pages={808--820},
  year={2025}
}

@inproceedings{kim2025lia,
  title={LIA: A Single-GPU LLM Inference Acceleration with Cooperative AMX-Enabled CPU-GPU Computation and CXL Offloading},
  author={Kim, Hyungyo and Wang, Nachuan and Xia, Qirong and Huang, Jinghan and Yazdanbakhsh, Amir and Kim, Nam Sung},
  booktitle={Proceedings of the 52nd Annual International Symposium on Computer Architecture},
  pages={544--558},
  year={2025}
}
```

### Topic 3.  Communication Optimizations in LLM Serving.

```
@inproceedings{wu2024mccs,
  title={MCCS: A Service-based Approach to Collective Communication for Multi-Tenant Cloud},
  author={Wu, Yongji and Xu, Yechen and Chen, Jingrong and Wang, Zhaodong and Zhang, Ying and Lentz, Matthew and Zhuo, Danyang},
  booktitle={Proceedings of the ACM SIGCOMM 2024 Conference},
  pages={679--690},
  year={2024}
}

@inproceedings{gangidi2024rdma,
  title={Rdma over ethernet for distributed training at meta scale},
  author={Gangidi, Adithya and Miao, Rui and Zheng, Shengbao and Bondu, Sai Jayesh and Goes, Guilherme and Morsy, Hany and Puri, Rohit and Riftadi, Mohammad and Shetty, Ashmitha Jeevaraj and Yang, Jingyi and others},
  booktitle={Proceedings of the ACM SIGCOMM 2024 Conference},
  pages={57--70},
  year={2024}
}

@article{chang2024flux,
  title={Flux: Fast software-based communication overlap on gpus through kernel fusion},
  author={Chang, Li-Wen and Bao, Wenlei and Hou, Qi and Jiang, Chengquan and Zheng, Ningxin and Zhong, Yinmin and Zhang, Xuanrun and Song, Zuquan and Yao, Chengji and Jiang, Ziheng and others},
  journal={arXiv preprint arXiv:2406.06858},
  year={2024}
}

@inproceedings{yan2025atop,
  title={From ATOP to ZCube: Automated Topology Optimization Pipeline and A Highly Cost-Effective Network Topology for Large Model Training},
  author={Yan, Zihan and Li, Dan and Chen, Li and Xiong, Dian and Gao, Kaihui and Zhang, Yiwei and Yan, Rui and Zhang, Menglei and Zhang, Bochun and Jiang, Zhuo and others},
  booktitle={Proceedings of the ACM SIGCOMM 2025 Conference},
  pages={861--881},
  year={2025}
}
```

## Category 2. LLM Training Inference and RL Systems

### Topic 4. Long Context LLM Training.

```
@inproceedings{lidistflashattn,
  title={DISTFLASHATTN: Distributed Memory-efficient Attention for Long-context LLMs Training},
  author={Li, Dacheng and Shao, Rulin and Xie, Anze and Xing, Eric P and Ma, Xuezhe and Stoica, Ion and Gonzalez, Joseph E and Zhang, Hao},
  booktitle={First Conference on Language Modeling}
}

@inproceedings{ge2025bytescale,
  title={ByteScale: Communication-Efficient Scaling of LLM Training with a 2048K Context Length on 16384 GPUs},
  author={Ge, Hao and Feng, Junda and Huang, Qi and Fu, Fangcheng and Nie, Xiaonan and Zuo, Lei and Lin, Haibin and Cui, Bin and Liu, Xin},
  booktitle={Proceedings of the ACM SIGCOMM 2025 Conference},
  pages={963--978},
  year={2025}
}
```

### Topic 5. Mixture of Expert Training.

```
@article{zhang2025comet,
  title={Comet: Fine-grained computation-communication overlapping for mixture-of-experts},
  author={Zhang, Shulai and Zheng, Ningxin and Lin, Haibin and Jiang, Ziheng and Bao, Wenlei and Jiang, Chengquan and Hou, Qi and Cui, Weihao and Zheng, Size and Chang, Li-Wen and others},
  journal={arXiv preprint arXiv:2502.19811},
  year={2025}
}

@article{wu2025hetermoe,
  title={Hetermoe: Efficient training of mixture-of-experts models on heterogeneous gpus},
  author={Wu, Yongji and Liu, Xueshen and Jin, Shuowei and Xu, Ceyu and Qian, Feng and Mao, Z Morley and Lentz, Matthew and Zhuo, Danyang and Stoica, Ion},
  journal={arXiv preprint arXiv:2504.03871},
  year={2025}
}
```

### Topic 6.  Prefill-Decoding Disaggregated Inference.

```
@inproceedings{zhong2024distserve,
  title={$\{$DistServe$\}$: Disaggregating prefill and decoding for goodput-optimized large language model serving},
  author={Zhong, Yinmin and Liu, Shengyu and Chen, Junda and Hu, Jianbo and Zhu, Yibo and Liu, Xuanzhe and Jin, Xin and Zhang, Hao},
  booktitle={18th USENIX Symposium on Operating Systems Design and Implementation (OSDI 24)},
  pages={193--210},
  year={2024}
}

@inproceedings{patel2024splitwise,
  title={Splitwise: Efficient generative llm inference using phase splitting},
  author={Patel, Pratyush and Choukse, Esha and Zhang, Chaojie and Shah, Aashaka and Goiri, {\'I}{\~n}igo and Maleki, Saeed and Bianchini, Ricardo},
  booktitle={2024 ACM/IEEE 51st Annual International Symposium on Computer Architecture (ISCA)},
  pages={118--132},
  year={2024},
  organization={IEEE}
}

@inproceedings{qin2025mooncake,
  title={Mooncake: Trading more storage for less computation—a $\{$KVCache-centric$\}$ architecture for serving $\{$LLM$\}$ chatbot},
  author={Qin, Ruoyu and Li, Zheming and He, Weiran and Cui, Jialei and Ren, Feng and Zhang, Mingxing and Wu, Yongwei and Zheng, Weimin and Xu, Xinran},
  booktitle={23rd USENIX Conference on File and Storage Technologies (FAST 25)},
  pages={155--170},
  year={2025}
}

@article{li2025taming,
  title={Taming the Chaos: Coordinated Autoscaling for Heterogeneous and Disaggregated LLM Inference},
  author={Li, Rongzhi and Du, Ruogu and Chu, Zefang and Zhao, Sida and Han, Chunlei and Shi, Zuocheng and Shao, Yiwen and Han, Huanle and Huang, Long and Liu, Zherui and others},
  journal={arXiv preprint arXiv:2508.19559},
  year={2025}
}
```

### Topic 7. Attention-Fully Connected Layer Disaggregated Inference.

```
@article{chen2024efficient,
  title={Efficient Heterogeneous Large Language Model Decoding with Model-Attention Disaggregation},
  author={Chen, Shaoyuan and Xiao, Wencong and Lin, Yutong and Zhang, Mingxing and Shan, Yingdi and Jiang, Jinlei and Chen, Kang and Wu, Yongwei},
  journal={arXiv preprint arXiv:2405.01814},
  year={2024}
}

@article{wang2025step,
  title={Step-3 is Large yet Affordable: Model-system Co-design for Cost-effective Decoding},
  author={Wang, Bin and Wang, Bojun and Wan, Changyi and Huang, Guanzhe and Hu, Hanpeng and Jia, Haonan and Nie, Hao and Li, Mingliang and Chen, Nuo and Chen, Siyu and others},
  journal={arXiv preprint arXiv:2507.19427},
  year={2025}
}

@inproceedings{zhu2025megascale,
  title={MegaScale-Infer: Efficient Mixture-of-Experts Model Serving with Disaggregated Expert Parallelism},
  author={Zhu, Ruidong and Jiang, Ziheng and Jin, Chao and Wu, Peng and Stuardo, Cesar A and Wang, Dongyang and Zhang, Xinlei and Zhou, Huaping and Wei, Haoran and Cheng, Yang and others},
  booktitle={Proceedings of the ACM SIGCOMM 2025 Conference},
  pages={592--608},
  year={2025}
}

@article{xiao2025xdeepserve,
  title={xDeepServe: Model-as-a-Service on Huawei CloudMatrix384},
  author={Xiao, Ao and He, Bangzheng and Zhang, Baoquan and Huai, Baoxing and Wang, Bingji and Wang, Bo and Xu, Bo and Hou, Boyi and Yang, Chan and Liu, Changhong and others},
  journal={arXiv preprint arXiv:2508.02520},
  year={2025}
}
```

### Topic 8. RL Systems.

```
@inproceedings{sheng2025hybridflow,
  title={Hybridflow: A flexible and efficient rlhf framework},
  author={Sheng, Guangming and Zhang, Chi and Ye, Zilingfeng and Wu, Xibin and Zhang, Wang and Zhang, Ru and Peng, Yanghua and Lin, Haibin and Wu, Chuan},
  booktitle={Proceedings of the Twentieth European Conference on Computer Systems},
  pages={1279--1297},
  year={2025}
}

@article{wang2025reinforcement,
  title={Reinforcement Learning Optimization for Large-Scale Learning: An Efficient and User-Friendly Scaling Library},
  author={Wang, Weixun and Xiong, Shaopan and Chen, Gengru and Gao, Wei and Guo, Sheng and He, Yancheng and Huang, Ju and Liu, Jiaheng and Li, Zhendong and Li, Xiaoyang and others},
  journal={arXiv preprint arXiv:2506.06122},
  year={2025}
}

@article{fu2025areal,
  title={AReaL: A Large-Scale Asynchronous Reinforcement Learning System for Language Reasoning},
  author={Fu, Wei and Gao, Jiaxuan and Shen, Xujie and Zhu, Chen and Mei, Zhiyu and He, Chuyi and Xu, Shusheng and Wei, Guo and Mei, Jun and Wang, Jiashu and others},
  journal={arXiv preprint arXiv:2505.24298},
  year={2025}
}

```

## Category 3. Algorithmic Advances for LLM

### Topic 9. Diffusion Language Model.

```
@article{wu2023ar,
  title={Ar-diffusion: Auto-regressive diffusion model for text generation},
  author={Wu, Tong and Fan, Zhihao and Liu, Xiao and Zheng, Hai-Tao and Gong, Yeyun and Jiao, Jian and Li, Juntao and Guo, Jian and Duan, Nan and Chen, Weizhu and others},
  journal={Advances in Neural Information Processing Systems},
  volume={36},
  pages={39957--39974},
  year={2023}
}

@inproceedings{lou2024discrete,
  title={Discrete Diffusion Modeling by Estimating the Ratios of the Data Distribution},
  author={Lou, Aaron and Meng, Chenlin and Ermon, Stefano},
  booktitle={International Conference on Machine Learning},
  pages={32819--32848},
  year={2024},
  organization={PMLR}
}

@article{nie2025large,
  title={Large language diffusion models},
  author={Nie, Shen and Zhu, Fengqi and You, Zebin and Zhang, Xiaolu and Ou, Jingyang and Hu, Jun and Zhou, Jun and Lin, Yankai and Wen, Ji-Rong and Li, Chongxuan},
  journal={arXiv preprint arXiv:2502.09992},
  year={2025}
}

@article{wu2025fast,
  title={Fast-dllm: Training-free acceleration of diffusion llm by enabling kv cache and parallel decoding},
  author={Wu, Chengyue and Zhang, Hao and Xue, Shuchen and Liu, Zhijian and Diao, Shizhe and Zhu, Ligeng and Luo, Ping and Han, Song and Xie, Enze},
  journal={arXiv preprint arXiv:2505.22618},
  year={2025}
}
```

### Topic 10. LLM Inference Acceleration Algorithms.

```
@article{zhang2024h2o,
  title={H2o: Heavy-hitter oracle for efficient generative inference of large language models},
  author={Zhang, Zhenyu and Sheng, Ying and Zhou, Tianyi and Chen, Tianlong and Zheng, Lianmin and Cai, Ruisi and Song, Zhao and Tian, Yuandong and R{\'e}, Christopher and Barrett, Clark and others},
  journal={Advances in Neural Information Processing Systems},
  volume={36},
  year={2024}
}

@article{zhou2024sirius,
  title={SIRIUS: Contexual sparisty with correction for efficient LLMs},
  author={Zhou, Yang and Chen, Zhuoming and Xu, Zhaozhuo and Lin, Xi V and Chen, Beidi},
  journal={Advances in Neural Information Processing Systems},
  volume={37},
  pages={24046--24080},
  year={2024}
}

@inproceedings{elhoushi2024layerskip,
  title={LayerSkip: Enabling Early Exit Inference and Self-Speculative Decoding},
  author={Elhoushi, Mostafa and Shrivastava, Akshat and Liskovich, Diana and Hosmer, Basil and Wasti, Bram and Lai, Liangzhen and Mahmoud, Anas and Acun, Bilge and Agarwal, Saurabh and Roman, Ahmed and others},
  booktitle={Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  pages={12622--12642},
  year={2024}
}

@article{yuan2025native,
  title={Native sparse attention: Hardware-aligned and natively trainable sparse attention},
  author={Yuan, Jingyang and Gao, Huazuo and Dai, Damai and Luo, Junyu and Zhao, Liang and Zhang, Zhengyan and Xie, Zhenda and Wei, YX and Wang, Lean and Xiao, Zhiping and others},
  journal={arXiv preprint arXiv:2502.11089},
  year={2025}
}
```

### Topic 11. Efficient SFT Algorithms.

```
@inproceedings{zhao2024galore,
  title={GaLore: Memory-Efficient LLM Training by Gradient Low-Rank Projection},
  author={Zhao, Jiawei and Zhang, Zhenyu and Chen, Beidi and Wang, Zhangyang and Anandkumar, Anima and Tian, Yuandong},
  booktitle={International Conference on Machine Learning},
  pages={61121--61143},
  year={2024},
  organization={PMLR}
}

@article{pan2024lisa,
  title={Lisa: Layerwise importance sampling for memory-efficient large language model fine-tuning},
  author={Pan, Rui and Liu, Xiang and Diao, Shizhe and Pi, Renjie and Zhang, Jipeng and Han, Chi and Zhang, Tong},
  journal={Advances in Neural Information Processing Systems},
  volume={37},
  pages={57018--57049},
  year={2024}
}

@inproceedings{hao2024flora,
  title={Flora: Low-Rank Adapters Are Secretly Gradient Compressors},
  author={Hao, Yongchang and Cao, Yanshuai and Mou, Lili},
  booktitle={International Conference on Machine Learning},
  pages={17554--17571},
  year={2024},
  organization={PMLR}
}
```

### Topic 12. RL Algorithms for LLM reasoning.

```
@article{schulman2017proximal,
  title={Proximal policy optimization algorithms},
  author={Schulman, John and Wolski, Filip and Dhariwal, Prafulla and Radford, Alec and Klimov, Oleg},
  journal={arXiv preprint arXiv:1707.06347},
  year={2017}
}

@article{shao2024deepseekmath,
  title={Deepseekmath: Pushing the limits of mathematical reasoning in open language models},
  author={Shao, Zhihong and Wang, Peiyi and Zhu, Qihao and Xu, Runxin and Song, Junxiao and Bi, Xiao and Zhang, Haowei and Zhang, Mingchuan and Li, YK and others},
  journal={arXiv preprint arXiv:2402.03300},
  year={2024}
}

@article{yue2025vapo,
  title={Vapo: Efficient and reliable reinforcement learning for advanced reasoning tasks},
  author={Yue, Yu and Yuan, Yufeng and Yu, Qiying and Zuo, Xiaochen and Zhu, Ruofei and Xu, Wenyuan and Chen, Jiaze and Wang, Chengyi and Fan, TianTian and Du, Zhengyin and others},
  journal={arXiv preprint arXiv:2504.05118},
  year={2025}
}

@article{wang2025kimina,
  title={Kimina-prover preview: Towards large formal reasoning models with reinforcement learning},
  author={Wang, Haiming and Unsal, Mert and Lin, Xiaohan and Baksys, Mantas and Liu, Junqi and Santos, Marco Dos and Sung, Flood and Vinyes, Marina and Ying, Zhenzhe and Zhu, Zekai and others},
  journal={arXiv preprint arXiv:2504.11354},
  year={2025}
}

@article{zheng2025group,
  title={Group sequence policy optimization},
  author={Zheng, Chujie and Liu, Shixuan and Li, Mingze and Chen, Xiong-Hui and Yu, Bowen and Gao, Chang and Dang, Kai and Liu, Yuqiong and Men, Rui and Yang, An and others},
  journal={arXiv preprint arXiv:2507.18071},
  year={2025}
}

```

## Category 4. MultiModal Foundation Model

### Topic 13. Multimodal Information Modeling and Reasoning.

```
@article{bai2025qwen2,
  title={Qwen2. 5-vl technical report},
  author={Bai, Shuai and Chen, Keqin and Liu, Xuejing and Wang, Jialin and Ge, Wenbin and Song, Sibo and Dang, Kai and Wang, Peng and Wang, Shijie and Tang, Jun and others},
  journal={arXiv preprint arXiv:2502.13923},
  year={2025}
}

@article{yang2025mmada,
  title={Mmada: Multimodal large diffusion language models},
  author={Yang, Ling and Tian, Ye and Li, Bowen and Zhang, Xinchen and Shen, Ke and Tong, Yunhai and Wang, Mengdi},
  journal={arXiv preprint arXiv:2505.15809},
  year={2025}
}

@article{kwok2025robomonkey,
  title={RoboMonkey: Scaling Test-Time Sampling and Verification for Vision-Language-Action Models},
  author={Kwok, Jacky and Agia, Christopher and Sinha, Rohan and Foutter, Matt and Li, Shulu and Stoica, Ion and Mirhoseini, Azalia and Pavone, Marco},
  journal={arXiv preprint arXiv:2506.17811},
  year={2025}
}
```

### Topic 14. Image- Video- Generation and Acceleration.

```
@inproceedings{yangcogvideox,
  title={CogVideoX: Text-to-Video Diffusion Models with An Expert Transformer},
  author={Yang, Zhuoyi and Teng, Jiayan and Zheng, Wendi and Ding, Ming and Huang, Shiyu and Xu, Jiazheng and Yang, Yuanming and Hong, Wenyi and Zhang, Xiaohan and Feng, Guanyu and others},
  booktitle={The Thirteenth International Conference on Learning Representations}
}

@article{gao2025seedance,
  title={Seedance 1.0: Exploring the Boundaries of Video Generation Models},
  author={Gao, Yu and Guo, Haoyuan and Hoang, Tuyen and Huang, Weilin and Jiang, Lu and Kong, Fangyuan and Li, Huixia and Li, Jiashi and Li, Liang and Li, Xiaojie and others},
  journal={arXiv preprint arXiv:2506.09113},
  year={2025}
}

@article{li2025radial,
  title={Radial Attention: $ O (n$\backslash$log n) $ Sparse Attention with Energy Decay for Long Video Generation},
  author={Li, Xingyang and Li, Muyang and Cai, Tianle and Xi, Haocheng and Yang, Shuo and Lin, Yujun and Zhang, Lvmin and Yang, Songlin and Hu, Jinbo and Peng, Kelly and others},
  journal={arXiv preprint arXiv:2506.19852},
  year={2025}
}

@article{yang2025sparse,
  title={Sparse VideoGen2: Accelerate Video Generation with Sparse Attention via Semantic-Aware Permutation},
  author={Yang, Shuo and Xi, Haocheng and Zhao, Yilong and Li, Muyang and Zhang, Jintao and Cai, Han and Lin, Yujun and Li, Xiuyu and Xu, Chenfeng and Peng, Kelly and others},
  journal={arXiv preprint arXiv:2505.18875},
  year={2025}
}
```

## Category 5.  LLM Agent, Evaluation and Applications

### Topic 15. LLM for Coding.

```
@article{zhu2024deepseek,
  title={Deepseek-coder-v2: Breaking the barrier of closed-source models in code intelligence},
  author={Zhu, Qihao and Guo, Daya and Shao, Zhihong and Yang, Dejian and Wang, Peiyi and Xu, Runxin and Wu, Y and Li, Yukun and Gao, Huazuo and Ma, Shirong and others},
  journal={arXiv preprint arXiv:2406.11931},
  year={2024}
}

@inproceedings{yang2025qwen2,
  title={Qwen2. 5-xCoder: Multi-Agent Collaboration for Multilingual Code Instruction Tuning},
  author={Yang, Jian and Zhang, Wei and Miao, Yibo and Quan, Shanghaoran and Wu, Zhenhe and Peng, Qiyao and Yang, Liqun and Liu, Tianyu and Cui, Zeyu and Hui, Binyuan and others},
  booktitle={Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
  pages={13121--13131},
  year={2025}
}
```

### Topic 16. LLM for Math.

```
@article{yang2024qwen2,
  title={Qwen2. 5-math technical report: Toward mathematical expert model via self-improvement},
  author={Yang, An and Zhang, Beichen and Hui, Binyuan and Gao, Bofei and Yu, Bowen and Li, Chengpeng and Liu, Dayiheng and Tu, Jianhong and Zhou, Jingren and Lin, Junyang and others},
  journal={arXiv preprint arXiv:2409.12122},
  year={2024}
}

@article{ren2025deepseek,
  title={Deepseek-prover-v2: Advancing formal mathematical reasoning via reinforcement learning for subgoal decomposition},
  author={Ren, ZZ and Shao, Zhihong and Song, Junxiao and Xin, Huajian and Wang, Haocheng and Zhao, Wanjia and Zhang, Liyue and Fu, Zhe and Zhu, Qihao and Yang, Dejian and others},
  journal={arXiv preprint arXiv:2504.21801},
  year={2025}
}

@article{xu2025phi,
  title={Phi-4-mini-reasoning: Exploring the limits of small reasoning language models in math},
  author={Xu, Haoran and Peng, Baolin and Awadalla, Hany and Chen, Dongdong and Chen, Yen-Chun and Gao, Mei and Kim, Young Jin and Li, Yunsheng and Ren, Liliang and Shen, Yelong and others},
  journal={arXiv preprint arXiv:2504.21233},
  year={2025}
}
```

### Topic 17. GUI Agent.

```
@inproceedings{xuagenttrek,
  title={AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials},
  author={Xu, Yiheng and Lu, Dunjie and Shen, Zhennan and Wang, Junli and Wang, Zekun and Mao, Yuchen and Xiong, Caiming and Yu, Tao},
  booktitle={The Thirteenth International Conference on Learning Representations}
}

@article{qin2025ui,
  title={Ui-tars: Pioneering automated gui interaction with native agents},
  author={Qin, Yujia and Ye, Yining and Fang, Junjie and Wang, Haoming and Liang, Shihao and Tian, Shizuo and Zhang, Junda and Li, Jiahao and Li, Yunxin and Huang, Shijue and others},
  journal={arXiv preprint arXiv:2501.12326},
  year={2025}
}

@article{wang2025opencua,
  title={Opencua: Open foundations for computer-use agents},
  author={Wang, Xinyuan and Wang, Bowen and Lu, Dunjie and Yang, Junlin and Xie, Tianbao and Wang, Junli and Deng, Jiaqi and Guo, Xiaole and Xu, Yiheng and Wu, Chen Henry and others},
  journal={arXiv preprint arXiv:2508.09123},
  year={2025}
}
```

### Topic 18. Retrieval Augmented Generation.

```
@article{jiang2024chameleon,
  title={Chameleon: A Heterogeneous and Disaggregated Accelerator System for Retrieval-Augmented Language Models},
  author={Jiang, Wenqi and Zeller, Marco and Waleffe, Roger and Hoefler, Torsten and Alonso, Gustavo},
  journal={Proceedings of the VLDB Endowment},
  volume={18},
  number={1},
  pages={42--52},
  year={2024},
  publisher={VLDB Endowment}
}

@article{shao2025reasonir,
  title={ReasonIR: Training Retrievers for Reasoning Tasks},
  author={Shao, Rulin and Qiao, Rui and Kishore, Varsha and Muennighoff, Niklas and Lin, Xi Victoria and Rus, Daniela and Low, Bryan Kian Hsiang and Min, Sewon and Yih, Wen-tau and Koh, Pang Wei and others},
  journal={arXiv preprint arXiv:2504.20595},
  year={2025}
}

@article{jin2025search,
  title={Search-r1: Training llms to reason and leverage search engines with reinforcement learning},
  author={Jin, Bowen and Zeng, Hansi and Yue, Zhenrui and Yoon, Jinsung and Arik, Sercan and Wang, Dong and Zamani, Hamed and Han, Jiawei},
  journal={arXiv preprint arXiv:2503.09516},
  year={2025}
}
```

### Topic 19. LLM Evaluation and Benchmarks.

```
@inproceedings{patilberkeley,
  title={The Berkeley Function Calling Leaderboard (BFCL): From Tool Use to Agentic Evaluation of Large Language Models},
  author={Patil, Shishir G and Mao, Huanzhi and Yan, Fanjia and Ji, Charlie Cheng-Jie and Suresh, Vishnu and Stoica, Ion and Gonzalez, Joseph E},
  booktitle={Forty-second International Conference on Machine Learning}
}

@article{yin2025decentralized,
  title={Decentralized Arena: Towards Democratic and Scalable Automatic Evaluation of Language Models},
  author={Yin, Yanbin and Zhou, Kun and Wang, Zhen and Zhang, Xiangdong and Shao, Yifei and Hao, Shibo and Gu, Yi and Liu, Jieyuan and Singla, Somanshu and Liu, Tianyang and others},
  journal={arXiv preprint arXiv:2505.12808},
  year={2025}
}

@article{ye2025verina,
  title={VERINA: Benchmarking Verifiable Code Generation},
  author={Ye, Zhe and Yan, Zhengxu and He, Jingxuan and Kasriel, Timothe and Yang, Kaiyu and Song, Dawn},
  journal={arXiv preprint arXiv:2505.23135},
  year={2025}
}

@article{patel2025deepscholar,
  title={DeepScholar-Bench: A Live Benchmark and Automated Evaluation for Generative Research Synthesis},
  author={Patel, Liana and Arabzadeh, Negar and Gupta, Harshit and Sundar, Ankita and Stoica, Ion and Zaharia, Matei and Guestrin, Carlos},
  journal={arXiv preprint arXiv:2508.20033},
  year={2025}
}
```
