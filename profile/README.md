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
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/sp25-realsight-deepfake-detection"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/sp25-realsight-deepfake-frame.jpg" width="220" alt="A frame from the deepfake video the system analyzed: a synthetic Morgan Freeman against a black background"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/sp25-realsight-deepfake-detection">RealSight: Probabilistic Deepfake Detection</a></b><br>
      Spring 2025 · Suyog Mahale, Zeel Patel<br><br>
      A pipeline from a YouTube URL to a forensic report: frame suspicion from a deepfake detector with Monte Carlo dropout, lip motion tracked against Whisper's word timestamps, BERT perplexity of the transcript, and a PyMC fusion with a credible interval. Shown as the authors' slides, because the code is private while they develop it further.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/sp25-bayes-beats"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/sp25-bayes-beats.jpg" width="220" alt="A pianist in headphones at a grand piano, in neon colors: the project's own banner art"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/sp25-bayes-beats">Bayes' Beats: Music from the Mood of an Image</a></b><br>
      Spring 2025 · Ariel Azria, Gabe Barrett, Kwaku Ofori-Atta, Danielle Rosenthal<br><br>
      ACE-Step, an open text-to-music diffusion model, fine-tuned with LoRA on 200 five-second Jamendo clips, behind a <a href="https://import-ariel.github.io/bayes_beats/">small site</a> where a picture picks a tune. A generative AI project shown for its engineering and its candor: the variational layer the team planned was not built, and the staff section says what else the write-up promises that the code does not do.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/au25-arena-preference-regression"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/au25-arena-two-agents.jpg" width="220" alt="Two chatbots, one teal and one gold, exchanging speech bubbles, with a question mark between them: which answer was better?"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/au25-arena-preference-regression">Conversation Analysis: What Makes a Chatbot Win a Human Preference Vote</a></b><br>
      Autumn 2025 · Yusen Wu, Yifei Zhou<br><br>
      A Bayesian logistic regression in PyMC on 23,294 Chatbot Arena battles, with each side's provenance, length, LLM-read formatting flags and prompt topic entered as differences, so the intercept is position bias, plus a topic-interaction model the authors flag as overfit. Shown with a staff section on partial pooling, model identity as the missing term, and validating features you got from an LLM.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/au25-nsf-grant-language"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/au25-nsf-logo.png" width="220" alt="The National Science Foundation logo"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/au25-nsf-grant-language">NSF Grant Data Analysis: Did the Language of Funded Research Change in 2025?</a></b><br>
      Autumn 2025 · Riley Morrison, Evan Fantozzi, Teddy Kolios<br><br>
      On 82,000 NSF award abstracts from 2019 to 2025: LDA topics per division with hand-written labels, an index of flagged words, a PyMC changepoint model on the yearly drift of abstract embeddings, and a Bayesian regression of which awards were terminated. Shown with a staff section on baselines that contain their own test year, priors on the wrong scale, and reading a changepoint posterior that sits on the boundary.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/wi26-sneaker-design-vae"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/wi26-sneaker-design-vae.jpg" width="220" alt="Nine blurry sneakers in different colors generated by the project's β-VAE, on white"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/wi26-sneaker-design-vae">New Sneaker Designs from Existing Design Data</a></b><br>
      Winter 2026 · Ethan Wang, Steven Si, Wenbo Zhao, Diana Chen, Justin Yang<br><br>
      A β-VAE with 16 latent dimensions trained on 12,856 UT Zappos50K sneaker photos at 64 × 64, with KL annealing, eight latent-space diagnostics and a slider-driven designer in a notebook and a small web page. Shown with a staff section on reporting what a figure shows rather than what you hoped, calibrating β to the scale of the loss, and measuring an improvement on held-out data.
    </td>
  </tr>
</table>

## Resources

- [Interactive tutorials](https://batu-uchicago.github.io/bayes-tutorials/): short warm-ups for selected sessions.
- [Course notebooks and applications](https://github.com/batu-uchicago/bayes-applications): the code used in class.

## Continuing a project

If you built one of these projects and want it in your own account, make a standalone copy with the full history rather than a fork, so your commits count on your profile. Each example README explains how. Add a line at the top of your copy saying where it started, with a link back here. That link credits your teammates.
