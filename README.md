# Robust Asynchronous Q Learning under Reward and State Corruption via Batching

Motivated by reinforcement learning in harsh
environments, we consider the problem of learning an optimal
policy subject to adversarially corrupted feedback. Specifically,
at each time-step, an adversary can perturb both the reward
and state observations of the learner following the Huber
contamination model. To defend against such data corruption,
we propose 𝙱𝚁-𝙰𝚜𝚢𝚗𝚌𝚀 : a novel, epoch-based, robust Qlearning
algorithm built upon two key ideas: (i) partitioning
the online data stream into batches to reduce variance, and
(ii) constructing robust estimates of the Bellman optimality
operator using such batched data. We prove a high-probability
ℓ∞ error bound for 𝙱𝚁-𝙰𝚜𝚢𝚗𝚌𝚀 that matches that for vanilla
Q-learning, up to a small additive term that scales with the
fraction of corrupted samples. To our knowledge, this provides
the first robustness guarantee for asynchronous Q-learning subject
to both reward and state corruption. Furthermore, when
only rewards are corrupted, the dependence of our algorithm’s
bound on the corruption fraction is minimax optimal.


## Figures
<table>
<tr>
  <td>
    <img src="https://github.com/sreejeetm1729/Robust-Asynchronous-Q-Learning-under-Reward-and-State-Corruption-via-Batching/blob/main/Vanilla_Q_error_asymmetric_corruption_300dpi%20(1).png" style="width:400px">
    <img src="https://github.com/sreejeetm1729/Robust-Asynchronous-Q-Learning-under-Reward-and-State-Corruption-via-Batching/blob/main/BR_Q_error_asymmetric_corruption_300dpi%20(1).png" style="width:400px">
    <img src="https://github.com/sreejeetm1729/Robust-Asynchronous-Q-Learning-under-Reward-and-State-Corruption-via-Batching/blob/main/BR_Q_error_batch_size_high_corruption_preview_300dpi%20(1).png" style="width:400px">
    <img src="https://github.com/sreejeetm1729/Robust-Asynchronous-Q-Learning-under-Reward-and-State-Corruption-via-Batching/blob/main/BR_Q_error_batch_size_low_corruption_preview_300dpi%20(1).png" style="width:400px">
  </td>
</tr>
</table>

<table>
<tr>
  <td>
    <img src="https://github.com/sreejeetm1729/Robust-Asynchronous-Q-Learning-under-Reward-and-State-Corruption-via-Batching/blob/main/Robust_BR-Async-Q.png" style="width:400px">
    <img src="https://github.com/sreejeetm1729/Robust-Asynchronous-Q-Learning-under-Reward-and-State-Corruption-via-Batching/blob/main/Robust_BR_varying_variance.png" style="width:400px">
    <img src="https://github.com/sreejeetm1729/Robust-Asynchronous-Q-Learning-under-Reward-and-State-Corruption-via-Batching/blob/main/Vanilla_varying_epsilon.png" style="width:400px">
    <img src="https://github.com/sreejeetm1729/Robust-Asynchronous-Q-Learning-under-Reward-and-State-Corruption-via-Batching/blob/main/Vanilla_varying_variance.png" style="width:400px">
  </td>
</tr>
