# SAC-FoG Experiment Results
<p>
  <img src="https://github.com/nothingbutbut/ICML-structure/blob/main/humanoid-run-performance.png" alt="humanhttps://github.com/nothingbutbut/ICML-structure/blob/main/humanoid-walk-performance.png" alt="humanoid-walk" style="width:48%; float:left; margin-left:2%;">
</p>
<p style="clear:both;">
  <img src="https://github.com/nothingbutbut/ICML-structure/blob/main/HalfCheetah-v4-performance.png" alt="HalfCheetah-v4" style="width:48%; float:left; margin-right:2%;">
  <img src="https://github.com/nothingbutbut/ICML-structure/blob/main/dog-run-performance.png" alt="dog-run" style="width:48%; float:left; margin-left:2%;">
</p>
<p style="clear:both; font-size:18px; margin-top:20px;">
  This experiment was conducted to evaluate the performance of the FoG with SAC algorithm backbone. We compare the performance of FoG with SAC to the performance of SimBa and BRO with SAC. The results are shown in the figures above. We use depth=10 (~42M params) for BRO and SimBa, which is almost twice the number of parameters of a maximal depth FoG model. All methods use a replay ratio of 2. While FoG still outperforms these strong baselines, its performance drops considerably compared to our original OBAC version. Adopting OBAC as the algorithm backbone is beneficial for both sample efficiency and parameter scalability.
</p>
