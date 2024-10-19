# disaster-tweet-jax
<a target="_blank" href="https://colab.research.google.com/github/PLippmann/disaster-tweet-jax/blob/main/solution.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

This solves the [Disaster Tweet Kaggle Competition](https://www.kaggle.com/c/nlp-getting-started) using a standard BERT-based approach in [Jax](https://github.com/jax-ml/jax).

There are few available approaches to problems like this using Jax, so I thought I would share mine. This can be easily modified for most classification tasks.

It will get you an eval score on the hidden test set of around 0.836, placing you close to the top of the rolling leaderboard. I'm sure that you can push this further if you optimize hypers, clean the training text, and choose a more capable model.

This implementation also trains fast (~3 mins on TPUv2), compared to unoptimized versions you might use, due to the use of JIT.

Reach out if you have any comments (:
