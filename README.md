# Child-ASR-Paper
A curated list of papers and resources for children's automatic speech recognition.

# Table of Contents
* [Datasets](#Datasets)
* [Papers](#Papers)
* [Special Sessions](#Special-Sessions)
* [Contributing](#Contributing)

## Datasets

- [My Science Tutor (MyST)](https://arxiv.org/abs/2309.13347)
  - Freely available  for non-commercial use
  - Age: Grade 3-5
  - 400k hours, 230k utterances, coversational speech
  - 100k utterances have been transcribed
- [CSLU Kids' Speech Corpus (OGI)](https://catalog.ldc.upenn.edu/LDC2007S18)
  - Age: K0 - G11
- [PF-STAR](http://www.thespeechark.com/pf-star-page.html)
  - Age: 4-14 years old
- [The CMU Kids Corpus](https://catalog.ldc.upenn.edu/LDC97S63)
- [Wikipedia Page](https://en.wikipedia.org/wiki/List_of_children%27s_speech_corpora)


## Papers

### ICASSP 2024 - updated in 4/1/2024
- [Automatic Speech Recognition Tuned for Child Speech in the Classroom](https://ieeexplore.ieee.org/document/10447428)
- [Improved Children’s Automatic Speech Recognition Combining Adapters and Synthetic Data Augmentation](https://ieeexplore.ieee.org/document/10446889)
- [Build a 50+ Hours Chinese Mandarin Corpus for Children’s Speech Recognition](https://ieeexplore.ieee.org/document/10445913)
- [Exploring Adapters with Conformers for Children’s Automatic Speech Recognition](https://ieeexplore.ieee.org/document/10447091)
- [Sparsely Shared LoRA on Whisper for Child Speech Recognition](https://arxiv.org/abs/2309.11756)
- SASB workshop [Analysis of Self-Supervised Speech Models on Children's Speech and Infant Vocalizations](https://arxiv.org/abs/2402.06888)
- SASB workshop [SOA: Reducing domain mismatch in SSL Pipeline by Speech Only Adaptation for low resource ASR](https://www.seas.ucla.edu/spapl/paper/SOA-icassp-workshop.pdf)

### Normalization and Data Augmentation
- JASA 2024 - [ChildAugment: Data Augmentation Methods for Zero-Resource Children's Speaker Verification](https://arxiv.org/abs/2402.15214)
- Interspeech 2023 - [Data augmentation for children ASR and child-adult speaker classification using voice conversion methods](https://www.isca-archive.org/interspeech_2023/zhao23c_interspeech.html)
- ICASSP 2023 - [Using Modified Adult Speech as Data Augmentation for Child Speech Recognition](https://ieeexplore.ieee.org/abstract/document/10094966?casa_token=eDn4effx8JoAAAAA:skz-YShAgfIGFn4s_nUpKjFIYXwBH7JDR5kSM7QUzZq5c3wFIYqHmTO0SHwvyLSQP0p-T1Tz)
- Interspeech 2022 - [Spectral Modification Based Data Augmentation for Improving End-to-End ASR for Children’s Speech](https://www.isca-archive.org/interspeech_2022/singh22b_interspeech.pdf)
- ICASSP 2022 - [LPC Augment: An LPC-Based ASR Data Augmentation Algorithm for Low and Zero-Resource Children's Dialects](https://arxiv.org/abs/2202.09529)
- Speech Communication 2021 - [Fundamental frequency feature warping for frequency normalization and data augmentation in child automatic speech recognition](https://www.sciencedirect.com/science/article/abs/pii/S0167639321000881)
- ICASSP 2021 - [Fundamental Frequency Feature Normalization and Data Augmentation for Child Speech Recognition](https://arxiv.org/abs/2102.09106)
- Interspeech 2020 - [Data Augmentation Using Prosody and False Starts to Recognize Non-native Children’s Speech](https://isca-speech.org/archive/Interspeech_2020/pdfs/2199.pdf)
- Interspeech 2020 - [Voice Conversion Based Data Augmentation to Improve Children’s Speech Recognition in Limited Data Scenario](http://www.interspeech2020.org/uploadfile/pdf/Thu-2-8-10.pdf)
- ASRU 2019 - [Data Augmentation Based on Vowel Stretch for Improving Children's Speech Recognition](https://ieeexplore.ieee.org/abstract/document/9003741)
- ASRU 2019 - [GANs for Chidren: A Generative Data Augmentation Strategy for Children Speech Recognirion](https://ieeexplore.ieee.org/abstract/document/9003933)
Interspeech 2019 - [A Frequency Normalization Technique for Kindergarten Speech Recognition Inspired by the Role of fo in Vowel Perception](https://www.isca-archive.org/interspeech_2019/yeung19_interspeech.html)
- IEEE SPL 2019 - [Significance of Pitch-Based Spectral Normalization for Children’s Speech Recognition](https://ieeexplore.ieee.org/abstract/document/8889398)
- Interspeech 2016 - [Improving Children’s Speech Recognition through Out-of-Domain Data Augmentation](http://www.cstr.inf.ed.ac.uk/downloads/publications/2016/master.pdf)

### Pretraining + Finetuning
- IEEE Acess 2024 - [Exploring Native and Non-Native English Child Speech Recognition With Whisper](https://ieeexplore.ieee.org/abstract/document/10474352)
- Arxiv 2023 - [Kid-Whisper: Towards Bridging the Performance Gap in Automatic Speech Recognition for Children VS. Adults](https://arxiv.org/abs/2309.07927)
- Interspeech 2023 - [Adaptation of Whisper models to child speech recognition](https://arxiv.org/abs/2307.13008)
- Under-review Speech Communication 2022 - [Improving Children's Speech Recognition by Fine-tuning Self-supervised Adult Speech Representations](https://arxiv.org/abs/2211.07769)
- IEEE JSTSP 2022 - [Towards Better Domain Adaptation for Self-supervised Models: A Case Study of Child ASR](https://arxiv.org/abs/2305.00115)
- Interspeech 2022 - [DRAFT: A Novel Framework to Reduce Domain Shifting in Self-supervised Learning and Its Application to Children's ASR](https://arxiv.org/abs/2206.07931)
- Interspeech 2022 - [Transfer Learning for Robust Low-Resource Children's Speech ASR with Transformers and Source-Filter Warping](https://arxiv.org/abs/2206.09396)
- ICASSP 2021 - [Bi-APC: Bidirectional Autoregressive Predictive Coding for Unsupervised Pre-training and Its Application to Children's ASR](https://arxiv.org/abs/2102.06816)
- Computer Speech & Language 2020 - [Transfer Learning from Adult to Children for Speech Recognition: Evaluation, Analysis and Recommendations](https://arxiv.org/abs/1805.03322)
- Interspeech 2019 - [Improving ASR Systems for Children with Autism and Language Impairment Using Domain-Focused DNN Transfer Techniques](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7575194/)
- WOCCI 2016 - [Improving DNN-Based Automatic Recognition of Non-native Children's Speech with Adult Speech](https://www.isca-archive.org/wocci_2016/qian16_wocci.pdf)


### Other topics
- ASRU 2023 - [No Pitch Left Behind: Addressing Gender Unbalance In Automatic Speech Recognition Through Pitch Manipulation](https://arxiv.org/abs/2310.06590)
- SLT 2022 - [A Zero-Shot Approach to Identifying Children's Speech in Automatic Gender Classification](https://ieeexplore.ieee.org/abstract/document/10023121?casa_token=4FZWdp0UYLsAAAAA:HGg90fdpN0hfneDU_P2RRtY5gLOWI2gKu9g8KaTgtSZgDWPLaBoIK1L1OZbntiHQE8zWIC08)
- ICASSP 2022 - [Towards Better Meta-Initialization with Task Augmentation for Kindergarten-aged Speech Recognition](https://arxiv.org/abs/2202.12326)
- Interspeech 2021 - [Age-Invariant Training for End-to-End Child Speech Recognition using Adversarial Multi-Task Learning](https://www.isca-archive.org/interspeech_2021/rumberg21_interspeech.pdf)
- ICASSP 2020 - [Learning Domain Invariant Representations for Child-Adult Classification from Speech](https://arxiv.org/abs/1910.11472)
- Interspeech 2019 - [Advances in Automatic Speech Recognition for Child Speech Using Factored Time Delay Neural Network](https://www.isca-archive.org/interspeech_2019/wu19_interspeech.html)
- ISCSLP 2018 - [A Study on Acoustic Modeling for Child Speech Based on Multi-Task Learning](https://ieeexplore.ieee.org/document/8706703)
- ICASSP 2019 - [Improving Children Speech Recognition Through Feature Learning from Raw Speech Signal](http://publications.idiap.ch/downloads/papers/2019/Dubagunta_ICASSP-3_2019.pdf)



## Special Sessions
- [Connecting Speech science and Speech technology for Children’s Speech](https://sites.google.com/view/sciencetech4childspeech-is24/home)
  - Interspeech 2023, Interspeech 2024
- [MERLIon CCS Challenge: Language Identification on Code-Switched Child-Directed Speech](https://sites.google.com/view/merlion-ccs-challenge)
  - Interspeech 2023
- [ETLT 2021: Shared Task on ASR for Non-Native Children's Speech](https://www.isca-archive.org/interspeech_2021/gretter21_interspeech.html)
  - Interspeech 2021
- [CSRC: Children Speech Recognition Challenge](https://www.data-baker.com/csrc_challenge.html)
  - SLT 2021 
- [Spoken Language Processing for Children's Speech](https://sites.google.com/view/wocci/home/interspeech-2019-special-session)
  - Interspeech 2019

## Contributing

This is an active repository and your contributions are always welcome!
