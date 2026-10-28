<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/banner-dark.png">
  <img alt="The University of Chicago, MS in Applied Data Science. ADSP 32014 course projects." src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/banner-light.png">
</picture>

# Bayesian Machine Learning with Generative AI Applications

This organization holds the course projects of ADSP 32014 in the [Master of Science in Applied Data Science](https://datascience.uchicago.edu/education/masters-programs/in-person-program/) at the University of Chicago.

In teams of three or four, students pose a question where quantifying uncertainty matters, choose a dataset, and answer it with a Bayesian method from the course: Bayesian networks, changepoint detection, hidden Markov models, Monte Carlo methods, variational inference and the generative models built on it, or Bayesian neural networks. Each team keeps its work in a repository here and presents it at the end of the quarter.

## Example projects

Selected projects from earlier quarters, shown with the authors' work and commit history intact. Course staff tidied each one and noted their changes in its README. Browse them all under the topic [example-project](https://github.com/orgs/uchicago-dsi-bayesianml/repositories?q=topic%3Aexample-project).

<table>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/wi25-age-transform-vae"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/wi25-age-transform-vae.jpg" width="220" alt="A face shown at three ages"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/wi25-age-transform-vae">Conditional Variational Autoencoders for Age Transformation in Facial Imagery</a></b><br>
      Winter 2025 · Bradley Stoller, Cassandra Maldonado, John Melel, Kyler Rosen<br><br>
      A conditional VAE trained on 55,000 labeled faces ages or de-ages a photo while keeping the person recognizable. Most of the work went into bringing new photos into the training distribution: eye alignment, background masking, and brightness and histogram matching.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/wi25-bayesian-book-rec"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/wi25-bayesian-book-rec.jpg" width="220" alt="Three book covers, as shown by the recommender app"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/wi25-bayesian-book-rec">Book Recommendation System Using Bayesian Machine Learning</a></b><br>
      Winter 2025 · Daniel Sa, Samuel Fisher, Hyunji Kim, Jazil Kalim<br><br>
      A hierarchical Poisson matrix factorization in PyMC, fit with NUTS and with ADVI, whose posterior samples drive an uncertainty-aware ranking rule, behind a Streamlit app. Shown with a staff section on what to learn from it, including a subsampling mistake that is easy to make.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/wi25-sdxl-conan-lora"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/wi25-sdxl-conan-lora.jpg" width="220" alt="A character in a dark coat drawn in anime style"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/wi25-sdxl-conan-lora">Fine-Tuning SDXL with LoRA for Conan Image Generation</a></b><br>
      Winter 2025 · Yifei Wang, Xinyi Jiang, Ke Wang, Maxine Wu<br><br>
      Stable Diffusion XL taught the drawing style of one anime series with a 60 MB low-rank adapter, a tuning log with reasons, an FID comparison, and a hand-written derivation of the DDPM objective. Shown with a staff section on crediting borrowed pieces and reporting metrics properly.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/au25-chord-progression-hmm"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/au25-chord-progression-hmm.jpg" width="220" alt="Piano roll of a song the project generated: melody, bridge and predicted piano accompaniment"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/au25-chord-progression-hmm">Bayesian and Neural Approaches for Chord Generation in Pop Music</a></b><br>
      Autumn 2025 · Michelle Peng, Luna Lu, Wen Yao<br><br>
      Chord progressions in 909 pop songs, predicted with Markov chains over absolute and functional chords, a Bayesian HMM with a key-aware prior fit by Gibbs sampling, and a duration-modeling variant, all generating playable MIDI, next to an LSTM that writes piano accompaniment from a melody.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/au25-nfl-player-movement"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/au25-nfl-player-movement.gif" width="220" alt="Animated play: heatmaps of where each defender is predicted to be next, as the pass is thrown"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/au25-nfl-player-movement">Bayesian Kinematic Models of NFL Player Movement</a></b><br>
      Autumn 2025 · Mitch Verhelle, Richard Huang, Claire Fenton<br><br>
      Constant-acceleration physics as the mean, learned noise around it in PyMC, position-group hierarchies for the spread, and a Bayesian logistic regression for pass completion, with posterior predictive cones and heatmaps animated on the field. Shown with a staff section on reporting evidence for every model compared.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/sp25-biscuit-anomaly-detection"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/sp25-biscuit-anomaly-detection.jpg" width="220" alt="Six defective biscuits: misshapen, colored, and one with a metal nut baked in"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/sp25-biscuit-anomaly-detection">Industrial Biscuit Defect Detection</a></b><br>
      Spring 2025 · Rithik Alluri, Alex Lee, Zimeng Huang, Manas Vemuri<br><br>
      Four generative models trained only on good biscuits, an autoencoder, a VAE, a DCGAN with latent optimization and a Vision Transformer VAE, flag defects by reconstruction error, and the VAE's latent space separates harmless misshapen biscuits from dangerous ones. Shown with a staff section on crediting borrowed code and reporting the numbers the code produced.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/sp25-lastfm-bayesian-recommender"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/sp25-lastfm-tag-cloud.jpg" width="220" alt="Cloud of genre tags written by Last.fm listeners: rock, pop, electronic, indie, and hundreds more"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/sp25-lastfm-bayesian-recommender">Personalized Music Recommendation with Bayesian Matrix Factorization</a></b><br>
      Spring 2025 · Peyton Nash, Apoorva Gupta, Zoe Calianos, Kirthi Rao<br><br>
      Hierarchical Bayesian matrix factorization of Last.fm play counts in PyMC, fit with variational inference after NUTS proved too slow for the full data, with a clear account of what ADVI buys and costs. Shown with a staff section on using the posterior you computed and measuring recommendations, not just regression error.
    </td>
  </tr>
</table>

## Resources

- [Interactive tutorials](https://batu-uchicago.github.io/bayes-tutorials/): short warm-ups for selected sessions.
- [Course notebooks and applications](https://github.com/batu-uchicago/bayes-applications): the code used in class.

## Continuing a project

If you built one of these projects and want it in your own account, make a standalone copy with the full history rather than a fork, so your commits count on your profile. Each example README explains how. Add a line at the top of your copy saying where it started, with a link back here. That link credits your teammates.
