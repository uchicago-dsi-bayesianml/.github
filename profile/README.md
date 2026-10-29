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
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/wi26-sepsis-progression-hmm"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/wi26-sepsis-icu-monitor.png" width="220" alt="A drawn bedside ICU monitor showing three traces, an ECG in gold, a pulse wave in teal and a blood-pressure wave in red, with an IV bag beside it"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/wi26-sepsis-progression-hmm">Bayesian Modeling of Sepsis Progression in ICU Patients</a></b><br>
      Winter 2026 · Ryan Abdelrahim, Collin Kim, Yuta Kobayashi, Hoon Yum, Nick Thompson<br><br>
      Two hidden Markov models of sepsis severity on 1,502 MIMIC-IV ICU stays: an hmmlearn baseline, and a Bayesian HMM in PyMC with a hand-written forward algorithm, treatment-dependent transitions and ADVI, driving a decision-support layer that compares treatments and delays. Shown with a staff section on a treatment effect built into the state definition, counterfactuals outside the data, in-sample validation, and state posteriors that are never uncertain.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/wi26-pedestrian-trajectory-uncertainty"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/wi26-pedestrian-crossing.png" width="220" alt="A drawn top-down street scene at night: a pedestrian at a zebra crossing with three dashed possible paths fanning across the road, one of them red and heading toward a yellow car approaching with its headlights on"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/wi26-pedestrian-trajectory-uncertainty">Bayesian Trajectory Prediction for Autonomous Driving Safety</a></b><br>
      Winter 2026 · Amulya Rayasam, Haiyang Hu, Ian Kidwell, Khadija Shuaib, Nikhil Sharma<br><br>
      An encoder-decoder LSTM on the ETH/UCY pedestrian benchmark, made Bayesian two ways: MC dropout averaged over 50 passes, and a Pyro variational posterior over the output layer, with a notebook that turns the spread of predicted paths into proceed, slow or yield decisions. Shown with a staff section on a variational model whose LSTM never trained, a test evaluation that never ran, and trajectory plots drawn in the wrong coordinates.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/wi26-deepfake-uncertainty"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/wi26-deepfake-face.png" width="220" alt="A drawn head-and-shoulders silhouette in cream whose right side breaks apart into small teal, gold and red pixel blocks drifting away"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/wi26-deepfake-uncertainty">Deepfake Detection with Bayesian Uncertainty Quantification</a></b><br>
      Winter 2026 · Anais Morales, Estella Hu, Gaoyuan Gu, Khalil He<br><br>
      Four heads on frozen Xception features for 1,952 in-the-wild images from Deepfake-Eval-2024: logistic regression, Gaussian Naive Bayes, an MC dropout network and a variational linear layer written from scratch, evaluated on whether their uncertainty marks their errors and on a reject option. Shown with a staff section on a KL-dominated variational fit, a memorizing dropout head, the missing confidence baseline, thresholds tuned on the test set, and a demo that does not compute what the notebooks did.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/wi26-borg-failure-hmm"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/wi26-borg-rack.png" width="220" alt="A drawn server rack of six units with teal status lights, the fourth unit lit red and glowing, beside a gold telemetry trace that drops and flatlines in red at the height of the failing unit"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/wi26-borg-failure-hmm">Bayesian Job Failure Prediction in Distributed Systems</a></b><br>
      Winter 2026 · Dhawal Dixit, Jenitha Patel, RJ Xia, Sabayna Ali, Sameeksha Kini<br><br>
      A three-state Gaussian hidden Markov model over resource telemetry from a month of Google's Borg cluster traces, fit by stochastic variational inference in NumPyro with the hidden states enumerated exactly, decoded with a hand-written forward filter and Viterbi, and checked against where tasks were killed, with a teammate's NUTS run on the marginalized model alongside. Shown with a staff section on a transition matrix too flat to make the HMM more than a mixture, a kill-row validation that scores the label's own footprint, a training loop that saw only the first ten windows of each task, and a hierarchy that stayed on paper.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/wi26-turbofan-rul"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/wi26-turbofan-engine.png" width="220" alt="A drawn turbofan engine seen from the front, its teal fan blades swept around a cream spinner with a gold spiral, one blade tinted red, and a gold wrench lying beside it"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/wi26-turbofan-rul">Predictive Maintenance for Aircraft Engines: RUL Estimation</a></b><br>
      Winter 2026 · Adi Singh, Eduardo Tovilla Rivera, Mukul Ramesh, Ryan Chen, William Niu<br><br>
      Models of the remaining useful life of NASA's simulated turbofan engines (C-MAPSS FD001), one per team member: a hierarchical Student-t regression sampled with NUTS in PyMC, a dynamic Bayesian network and an unscented Kalman filter, a linear Kalman filter beside a random-forest ensemble, Prophet, and a CNN, attention and LSTM network with Monte Carlo dropout whose labels start at an onset found by a hand-written Bayesian online changepoint detector. Shown with a staff section on swapped constants in the benchmark's score, a network result chosen on the test set and scored against rewritten labels, a random forest presented as a Bayesian time-series model, and a Kalman-filter grid search that cannot change anything.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/wi26-fall-detection-hmm"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/wi26-fall-alert.png" width="220" alt="A drawn older person with grey hair tipping forward toward the floor as a cane falls away, four glowing teal tags at the chest, belt and both ankles, and a gold bell inside a house outline sending out red alert waves"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/wi26-fall-detection-hmm">Smart Home Fall Detection for Elderly Safety</a></b><br>
      Winter 2026 · Lexi Lin, Xiaojing Fang<br><br>
      Per-activity Gaussian hidden Markov models, a random forest smoothed by Viterbi decoding over an activity transition matrix, a hidden semi-Markov model with Poisson durations and a weighted bidirectional LSTM, compared on 25 recordings of four body-worn location tags from UCI's Localization Data for Person Activity, with a Streamlit dashboard that raises an ensemble fall alarm. Shown with a staff section on a smoother that cuts false alarms from 155 to 4 per hour, which the team never measured, test chunks and durations taken from the labels, a threshold tuned on the test folds, and falls a model can find by where in the room they happen.
    </td>
  </tr>
  <tr>
    <td width="240">
      <a href="https://github.com/uchicago-dsi-bayesianml/su26-glicko2-audit"><img src="https://raw.githubusercontent.com/uchicago-dsi-bayesianml/.github/main/profile/assets/thumbs/su26-chess-king-clock.png" width="220" alt="A drawn cream chess king with a gold cross standing on a dark chessboard beside a chess clock, its left flag up in teal and its right dial's red flag about to fall"></a>
    </td>
    <td>
      <b><a href="https://github.com/uchicago-dsi-bayesianml/su26-glicko2-audit">Beyond Glicko-2: Hierarchical Bayesian Estimation of Latent Chess Skill</a></b><br>
      Summer 2026 · John Henry Oliphant<br><br>
      Ordered-probit models of latent chess skill fit to 5.2 million Lichess games between 21,488 blitz players, with hand-written JAX samplers (data augmentation, forward filtering and backward sampling, and a two-skill model of board strength and clock discipline) compared with the Lichess Glicko-2 ratings on a two-month holdout. Shown with a staff section on a headline win that scores games selected by how they ended, a "same data" comparison in which the model sees a fifth of the cohort's games while the ratings keep updating, a single chain whose drift estimate is still falling, and a simultaneous skill update that understates posterior spread.
    </td>
  </tr>
</table>

## Resources

- [Interactive tutorials](https://batu-uchicago.github.io/bayes-tutorials/): short warm-ups for selected sessions.
- [Course notebooks and applications](https://github.com/batu-uchicago/bayes-applications): the code used in class.

## Continuing a project

If you built one of these projects and want it in your own account, make a standalone copy with the full history rather than a fork, so your commits count on your profile. Each example README explains how. Add a line at the top of your copy saying where it started, with a link back here. That link credits your teammates.
