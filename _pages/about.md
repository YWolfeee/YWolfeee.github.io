---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p id="about">
I am a third-year Ph.D. student at <a href="https://www.cs.stanford.edu/">Stanford CS</a>, co-advised by <a href="https://www.james-zou.com/">James Zou</a> and <a href="https://cs.stanford.edu/~ermon/">Stefano Ermon</a>. I received my B.S. in Math and CS at Yuanpei College, <a href="https://english.pku.edu.cn/">Peking University</a>, co-advised by <a href="http://www.liweiwang-pku.com/">Liwei Wang</a> and <a href="https://dihe-pku.github.io/">Di He</a>. During my undergrad, I was fortunate to work with <a href="https://jsteinhardt.stat.berkeley.edu/">Jacob Steinhardt</a> and <a href="https://simonshaoleidu.com/">Simon S. Du</a> as a visiting researcher. I also collaborated with <a href="https://mingyuliu.net/">Ming-Yu Liu</a> as an intern in <a href="https://www.nvidia.com/en-us/ai/cosmos/">NVIDIA Cosmos</a>, and <a href="https://felixyu.org/">Felix Yu</a> in <a href="https://deepmind.google/">Google Deepmind</a>.</p>

<!-- <h2 id="researchinterests">Research Interest</h2> -->
<!-- <p> -->
My Ph.D. research aims to advance generative AI capabilities for open problems through post-training and inference-time algorithm design. Specifically, for both text and vision generative models:
- How do we continuously improve them via post-training, even at superhuman levels?
- How do we scale test-time compute effectively and efficiently?

I believe in the synergy of scalable engineering and principled algorithm design. This philosophy is grounded in my early research on deep learning foundations and AI for science.
Feel free to reach out if you are interested in my research or simply want to chat.
<!-- </p> -->

<h2 id="news">News</h2>
- (Feb. 2026) [InfoTok](https://arxiv.org/abs/2512.16975) (<font color="#DC143C">Spotlight</font>) and [Scaling Law Discovery](https://linhaowei1.github.io/scaling_law_discovery/) accepted by ICLR 2026. See you in Rio de Janeiro!
- (Jan. 2026) We release an interesting [study](https://linhaowei1.github.io/scaling_law_discovery/) on whether AI can discover its own scaling laws better than humans. Check it out!
- (Jan. 2026) Check out [InfoTok](https://arxiv.org/abs/2512.16975), our adaptive information-theoretic tokenizer that achieves 40% higher compression without information loss and represents videos via coarse-grained to fine-grained sequences.
- (Dec. 2025) We release [DDRL](https://research.nvidia.com/labs/dir/ddrl/), the RL algorithm powering NVIDIA's [Cosmos-Predict2.5](https://research.nvidia.com/labs/dir/cosmos-predict2.5/) video generative models (2B/14B)! An amazing experience scaling the post-training of models on ~2,000 H100 GPUs. Check our [post](https://x.com/haotian_yeee/status/1997138677529825452?s=20) and [models](https://github.com/nvidia-cosmos/cosmos-predict2.5)!
<!-- - (Dec. 2025) [Data Attribution for RL](https://arxiv.org/abs/2505.19281) was accepted by NeurIPS 2025 (<font color="#DC143C">Oral</font>). See you in San Diego! -->
<!-- - (Nov. 2025) We released NVIDIA [Cosmos-Predict2.5](https://research.nvidia.com/labs/dir/cosmos-predict2.5/), the Cosmos World Foundation Models specialized for video generation. I am responsible for designing the RL algorithm and performing large-scale post-training (1K+ GPUs) for the release. -->  
<!-- - (Oct. 2025) [Diffusion Inference-Time Acceleration](https://arxiv.org/abs/2507.15260) was accepted by ICCV 2025. See you in Hawaii!  -->
<!-- - (Apr. 2025) Google intern work [LLM Constrained Decoding](https://arxiv.org/abs/2504.09135) was accepted by AISTATS 2025, and [ICV-Hallucination](https://arxiv.org/abs/2410.15778) by ICLR 2025 (<font color="#DC143C">Spotlight</font>). See you in Singapore and Phuket! ->
<!-- - (Sept. 2024) I started my part-time internship at [NVIDIA Deep Imagination Research](https://research.nvidia.com/labs/dir/). ->
<!-- - (Sept. 2024) Two papers was accepted by NeurIPS 2024, including [training-free guidance](https://arxiv.org/abs/2409.15761) (<font color="#DC143C">Spotlight</font>) and [geometric trajectory models](https://arxiv.org/abs/2410.13027). See you in Vancouver! ->
<!-- - (May 2024) Three papers got accepted by ICML 2024, including [LLM selection](https://arxiv.org/abs/2402.02314), [in-context vectors](https://arxiv.org/abs/2311.06668), and [monitoring AI usage in peer reviews](https://arxiv.org/pdf/2403.07183). See you in Vienna! -->
<!-- - (Feb. 2024) Our [Forward Laplacian paper](https://www.nature.com/articles/s42256-024-00794-x) is accepted by Nature Machine Intelligence! We release [LapJAX](https://github.com/YWolfeee/lapjax), a JAX-based package designed for accelerating general second-order operators (e.g., Laplacian) computation. -->
  <br/>

<h2 id="publications">Selected Publications</h2>

<div class="pub-item">
<div class="pub-left">
<abbr class="badge">In submission</abbr>
<a href="/images/papers/ddrl.gif" target="_blank"><img src="/images/papers/ddrl.gif" alt="DDRL"></a>
</div>
<div class="pub-right">
<div class="pub-title">Data-regularized Reinforcement Learning for Diffusion Models at Scale</div>
<div class="pub-authors">Haotian Ye, Kaiwen Zheng, Jiashu Xu, Puheng Li, Huayu Chen, Jiaqi Han, Sheng Liu, Qinsheng Zhang, Hanzi Mao, Zekun Hao, Prithvijit Chattopadhyay, Dinghao Yang, Liang Feng, Maosheng Liao, Junjie Bai, Ming-Yu Liu, James Zou, Stefano Ermon</div>
<div class="pub-links"><a href="https://www.arxiv.org/abs/2512.04332">[Paper]</a> <a href="https://research.nvidia.com/labs/dir/ddrl/">[Website]</a> <a href="https://github.com/nvidia-cosmos/cosmos-rl/blob/main/examples/ddrl.md">[Code]</a> <a href="https://x.com/haotian_yeee/status/1997138677529825452?s=20">[Twitter]</a></div>
</div>
</div>

<div class="pub-item">
<div class="pub-left">
<abbr class="badge">ICLR 2026 Oral</abbr>
<a href="/images/papers/infotok.png" target="_blank"><img src="/images/papers/infotok.png" alt="InfoTok"></a>
</div>
<div class="pub-right">
<div class="pub-title">InfoTok: Adaptive Discrete Video Tokenizer via Information-Theoretic Compression</div>
<div class="pub-authors">Haotian Ye*, Qiyuan He*, Jiaqi Han, Puheng Li, Jiaojiao Fan, Zekun Hao, Fitsum Reda, Yogesh Balaji, Huayu Chen, Sheng Liu, Angela Yao, James Zou, Stefano Ermon, Haoxiang Wang, Ming-Yu Liu</div>
<div class="pub-links"><a href="https://arxiv.org/abs/2512.16975">[Paper]</a> <a href="https://github.com/YWolfeee/InfoTok">[Code]</a></div>
</div>
</div>

<div class="pub-item">
<div class="pub-left">
<abbr class="badge">ICLR 2026</abbr>
<a href="/images/papers/sld.png" target="_blank"><img src="/images/papers/sld.png" alt="Scaling Laws"></a>
</div>
<div class="pub-right">
<div class="pub-title">Can Language Models Discover Scaling Laws?</div>
<div class="pub-authors">Haowei Lin*, Haotian Ye*, Quzhe Huang, Wenzheng Feng, Yujun Li, Xiangyu Wang, Hubert Lim, Zhengrui Li, Jianzhu Ma, Yitao Liang, James Zou</div>
<div class="pub-links"><a href="https://arxiv.org/abs/2507.21184">[Paper]</a> <a href="https://linhaowei1.github.io/scaling_law_discovery/">[Website]</a> <a href="https://github.com/linhaowei1/SLD">[Code]</a> <a href="https://algorithmicsuperintelligence.ai/blog/openevolve-sldagent/index.html">[Blog]</a></div>
</div>
</div>

<div class="pub-item">
<div class="pub-left">
<abbr class="badge-highlight">NeurIPS 2025 Oral</abbr>
<a href="/images/papers/onlinerl.png" target="_blank"><img src="/images/papers/onlinerl.png" alt="Snapshot"></a>
</div>
<div class="pub-right">
<div class="pub-title">A Snapshot of Influence: A Local Data Attribution Framework for Online Reinforcement Learning</div>
<div class="pub-authors">Yuzheng Hu, Fan Wu, Haotian Ye, David Forsyth, James Zou, Nan Jiang, Jiaqi W. Ma, Han Zhao</div>
<div class="pub-links"><a href="https://arxiv.org/abs/2505.19281">[Paper]</a> <a href="https://github.com/LDAORL/LDA-ORL">[Code]</a></div>
</div>
</div>

<div class="pub-item">
<div class="pub-left">
<abbr class="badge">AISTATS 2025</abbr>
<a href="/images/papers/decoding.png" target="_blank"><img src="/images/papers/decoding.png" alt="Constrained Decoding"></a>
</div>
<div class="pub-right">
<div class="pub-title">Efficient and Asymptotically Unbiased Constrained Decoding for Large Language Models</div>
<div class="pub-authors">Haotian Ye, Himanshu Jain, Chong You, Ananda Theertha Suresh, Haowei Lin, James Zou, Felix Yu</div>
<div class="pub-links"><a href="https://arxiv.org/abs/2504.09135">[Paper]</a> <a href="https://github.com/YWolfeee/Large-Scale-Selection-for-LLMs">[Code]</a></div>
</div>
</div>

<div class="pub-item">
<div class="pub-left">
<abbr class="badge-highlight">NeurIPS 2024 Spotlight</abbr>
<a href="/images/papers/tfg.jpg" target="_blank"><img src="/images/papers/tfg.jpg" alt="TFG"></a>
</div>
<div class="pub-right">
<div class="pub-title">TFG: Unified Training-Free Guidance for Diffusion Models</div>
<div class="pub-authors">Haotian Ye*, Haowei Lin*, Jiaqi Han*, Minkai Xu, Sheng Liu, Yitao Liang, Jianzhu Ma, James Zou, Stefano Ermon</div>
<div class="pub-links"><a href="https://arxiv.org/abs/2409.15761">[Paper]</a> <a href="https://github.com/YWolfeee/Training-Free-Guidance">[Code]</a> <a href="https://x.com/haotian_yeee/status/1859672842658512908">[Twitter]</a></div>
</div>
</div>

<div class="pub-item">
<div class="pub-left">
<abbr class="badge">Nature Machine Intelligence</abbr>
<a href="/images/papers/lapnet.png" target="_blank"><img src="/images/papers/lapnet.png" alt="Laplacian"></a>
</div>
<div class="pub-right">
<div class="pub-title">A computational framework for neural network-based variational Monte Carlo with Forward Laplacian</div>
<div class="pub-authors">Ruichen Li*, Haotian Ye*, Du Jiang, Xuelan Wen, Chuwei Wang, Zhe Li, Xiang Li, Di He, Ji Chen, Weiluo Ren, Liwei Wang</div>
<div class="pub-links"><a href="https://www.nature.com/articles/s42256-024-00794-x">[Paper]</a> <a href="https://github.com/YWolfeee/lapjax">[Code]</a></div>
</div>
</div>

<div class="pub-item">
<div class="pub-left">
<abbr class="badge-highlight">NeurIPS 2023 Oral</abbr>
<a href="/images/papers/cot.png" target="_blank"><img src="/images/papers/cot.png" alt="CoT"></a>
</div>
<div class="pub-right">
<div class="pub-title">Towards Revealing the Mystery behind Chain of Thought: a Theoretical Perspective</div>
<div class="pub-authors">Guhao Feng*, Bohang Zhang*, Yuntian Gu*, Haotian Ye*, Di He, Liwei Wang</div>
<div class="pub-links"><a href="https://arxiv.org/abs/2305.15408">[Paper]</a> <a href="https://youtu.be/nOIRuVluCyE">[Video]</a> <a href="https://haotianye.com/files/NeurIPS23/Slides_NeurIPS23_CoT.pdf">[Slides]</a></div>
</div>
</div>

<div class="pub-item">
<div class="pub-left">
<abbr class="badge-highlight">ICML 2023 Oral</abbr>
<a href="/images/papers/rlgeneralization.png" target="_blank"><img src="/images/papers/rlgeneralization.png" alt="Pre-training"></a>
</div>
<div class="pub-right">
<div class="pub-title">On the Power of Pre-training for Generalization in RL: Provable Benefits and Hardness</div>
<div class="pub-authors">Haotian Ye*, Xiaoyu Chen*, Liwei Wang, Simon Shaolei Du</div>
<div class="pub-links"><a href="https://arxiv.org/abs/2210.10464">[Paper]</a></div>
</div>
</div>

<!-- <div class="pub-item">
<div class="pub-left">
<abbr class="badge">AISTATS 2023</abbr>
<img src="/images/papers/ftt.png" alt="FTT">
</div>
<div class="pub-right">
<div class="pub-title">Freeze then Train: Towards Provable Representation Learning under Spurious Correlations and Feature Noise</div>
<div class="pub-authors">Haotian Ye, James Zou, Linjun Zhang</div>
<div class="pub-links"><a href="https://arxiv.org/abs/2210.11075">[Paper]</a> <a href="https://github.com/YWolfeee/Freeze-Then-Train">[Code]</a> <a href="https://www.youtube.com/watch?v=K9evpKADRpk">[Video]</a> <a href="https://haotianye.com/files/AISTATS23/slides_AISTATS23_FTT.pdf">[Slides]</a></div>
</div>
</div> -->

<div class="pub-item">
<div class="pub-left">
<abbr class="badge">ICLR 2023</abbr>
<a href="/images/papers/dlk.png" target="_blank"><img src="/images/papers/dlk.png" alt="CCS"></a>
</div>
<div class="pub-right">
<div class="pub-title">Discovering Latent Knowledge in Language Models Without Supervision</div>
<div class="pub-authors">Collin Burns*, Haotian Ye*, Dan Klein, Jacob Steinhardt</div>
<div class="pub-links"><a href="https://arxiv.org/abs/2212.03827">[Paper]</a></div>
</div>
</div>


<h2 id="talks">Invited Talks</h2>

- [NVIDIA Research](https://research.nvidia.com/), Oct. 2025
<br/>*Data-regularized Reinforcement Learning for Diffusion Models at Scale*

- [NVIDIA Research](https://research.nvidia.com/), July 2025
<br/>*InfoTok: Adaptive Discrete Video Tokenizer via Information-Theoretic Compression*

- [Google Research](https://research.google/), March 2025
<br/>*Efficient and Asymptotically Unbiased Constrained Decoding for Large Language Models*

- [The Hong Kong University of Science and Technology](https://hkust.edu.hk/), Dec. 2023
<br/>*Towards Revealing the Mystery behind Chain of Thought: A Theoretical Perspective*

- [Google Brain](https://research.google/teams/brain/), May 2023
<br/>*Towards Revealing the Mystery behind Chain of Thought: A Theoretical Perspective*

<h2 id="services">Professional Services</h2>
- **Reviewer**: NeurIPS (2022-2025), ICLR (2024-2026), ICML (2024-2025), AISTATS (2023, 2025, *Top Reviewer*), ICCV (2025), EMNLP (2022)

<h2 id="awards">Selected Awards</h2>
- Weiming Scholar of Peking University (1%), 2023
- [Person of the Year](http://m.cyol.com/gb/articles/2021-12/28/content_XM2l5spYg.html) of Peking University (10 people/year), 2021
- May 4 scholarship (1%, Rank 1), 2021
- National scholarship (1%, Rank 2), 2019
- Leo Koguan scholarship (1%), 2020
- Merit student pacesetter (2%), 2019
- Chinese Mathematical Olympiad (First Prize, Rank 7 in China), 2017

<h2 id="misc">Miscellaneous</h2>
I spend most of my free time on photography, scuba diving (check the avatar!), and soccer (<a href="http://www.paasl.org/build.cfm?root=template.cfm&CONTENT=main.cfm">Palo Alto Adult Soccer League</a>)!
