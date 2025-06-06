# ASMUS Workshop '25

<div align="center">
 <img src="im/asmus.png" width="239" height="150">
</div>

**The 6th International Workshop of Advances in Simplifying Medical UltraSound (ASMUS) - a workshop held in conjunction with [MICCAI 2025](https://conferences.miccai.org/2025/en/default.asp), the 28th International Conference on Medical Image Computing and Computer Assisted Intervention.**

**ASMUS is the official workshop of the [MICCAI Special Interest Group on Medical Ultrasound](https://miccai-ultrasound.github.io/).**

## Call for Papers

**NEWS: We are happy to share with you that an interesting J-BHI special issue on [Next-Generation AI-Powered Medical Ultrasound Imaging: Methods and Systems](https://www.embs.org/jbhi/special-issues/) is newly launched, which aligns quite well with the ASMUS workshop. Extension of the workshop papers are encouraged to be summited to this special issue.**

Papers will consist of a maximum of 8 pages (text, figures, and tables) + up to 2 pages for references only.
They are to be submitted electronically in [Springer LNCS (Lecture Notes in Computer Science) style](https://www.springer.com/gp/computer-science/lncs/conference-proceedings-guidelines) and are subject to double-blind review.
The workshop sessions (oral and posters) will be held in person only, and by submitting a paper authors commit to presenting them in person if accepted for publication.

The papers will be evaluated by external reviewers and our organizing committee for inclusion in the workshop as a presentation (oral or poster).
Accepted full-length manuscripts will be published with Springer LNCS, and the best papers will be selected for industry-sponsored awards.
Original research contributions are invited.
Proof-of-concept research from novel research directions is also encouraged.
This year, we encourage submissions exploring emerging frontiers in ultrasound research, with special emphasis on: 1) clinical-guided design in ultrasound workflow, and 2) large multimodal foundation model-driven AI technologies in ultrasound.

Building on the success of previous interactive live demonstrations, ASMUS 2025 will continue this feature to showcase cutting-edge ultrasound innovations. We invite researchers to demonstrate novel systems leveraging ultrasound's unique real-time capabilities and clinical portability. All accepted papers will be offered the option to present a live demonstration.

The submission system will be open on May 10th, 2025. You may start submitting the papers at [Springer Nature Meteor](https://meteor.springer.com/ASMUS2025). **Please note that the deadline for paper submission is June 28th 2025, 23:59 PT.** E-mail registration is required before submission, which can be accessed by clicking the "here" button on the previous link.
If you have any issues registering or with the submission process, please contact the PC Chairs via the platform or E-Mail.

This multidisciplinary workshop will foster cross-sector collaboration, rigorously reviewing, publishing, and engaging participants in discussions about cutting-edge advancements. Contributors from academia, underserved regions, industry, and clinical settings are invited to share insights. Selected full papers will appear in a Springer publication, with top submissions receiving awards supported by industry partners. We welcome original research submissions and actively seek proof-of-concept studies pioneering innovative methodologies. Key focus areas include:

### Ultrasound Assisted by Artificial Intelligence and Medical Robotics:

- Machine learning methods in ultrasound analysis, dignosis, and guidance
- Automated interpretation and measurement for ultrasound
- Ultrasound quality and skill assessment
- Human-in-the-loop clinical decision support
- Clinical-guided design in ultrasound workflow
- Large multimodal foundation model-driven AI technologies in ultrasound

### Multimodality Ultrasound Imaging:

- Ultrasound with other non-imaging sensory information, e.g. positional and eye tracking
- Ultrasound with another pre-/intra-procedural imaging, e.g. camera videos, CT, MR, fluorescence
- Different modes of ultrasound imaging, e.g. photoacoustic, Doppler, functional ultrasound, tissue quantification

### Applications:

- Global healthcare
- Training sonographers and other users
- Assisting non-expert healthcare professionals
- Point-of-care ultrasound systems and scenarios
- Assisting surgery and interventions
- Streamlining clinical ultrasound workflow
- Sonography data science and ultrasound foundation model pre-training and fine-tuning

| Workshop Timeline  |                            |
| -----------------  | -------------------------- |
| June 28th 2025     | Paper Submission Deadline  |
| July 12th 2025     | Reviews Due                |
| July 19th 2025     | Notification of Acceptance |
| August 6th 2025    | Camera Ready Submission    |
| September 27th 2025 (TBD)| ASMUS Workshop    |

## Program

### Morning Session
- **Keynote**: David Ouyang  
- **Orals & Poster Presentations**  
  *Including Demo Teasers*

### Afternoon Session
- **Trackerless 3D Freehand Ultrasound Reconstruction Challenge**  
- **Landmark Detection Challenge for Intrapartum Ultrasound Measurement Meeting the Actual Clinical Assessment of Labor Progress**

## Keynote Speaker

### [David Ouyang](https://douyang.github.io/)

![David Ouyang](im/david_ouyang.jpg)

_Bio:_ David Ouyang, MD, is a research scientist at the Kaiser Permanente Northern California Division of Research and a non-invasive cardiologist and echocardiographer at Kaiser Permanente Santa Clara Medical Center. Dr. Ouyang’s group works on applications of deep learning, computer vision, and the statistical analysis of large datasets within cardiovascular medicine. His work has been published in Nature, Nature Medicine, NEJM AI, Circulation, JACC, JAMA Cardiology, EHJ, and other venues. He is also a Deputy Editor for New England Journal of Medicine (NEJM) AI.

A physician-scientist and statistician with a focus on cardiology and imaging, Dr. Ouyang majored in statistics at Rice University, obtained his MD at the University of California, San Francisco, and received post-graduate medical education in internal medicine, cardiology, and a postdoctoral fellowship in computer science and biomedical data science at Stanford University. He is the recipient of an NHLBI K99/R00 and two R01 grants focused on applications of computer vision in echocardiography. He is the Principal Investigator (PI) or Co-Investigator on multiple investigator-initiated pragmatic clinical trials of AI in cardiovascular medicine.

## Challenge

### [Trackerless 3D Freehand Ultrasound Reconstruction Challenge](https://github-pages.ucl.ac.uk/tus-rec-challenge/)

Reconstructing 2D Ultrasound (US) images into a 3D volume enables 3D representations of anatomy to be generated which are beneficial to a wide range of downstream tasks such as quantitative biometric measurement, multimodal registration, 3D visualization, and interventional guidance.
Although substantive progress has been made recently through non-deep-learning- and deep-learning-based approaches, this application is still challenging due to 1) inherent accumulated error - frame-to-frame transformation error will be accumulated through time when reconstructing long sequence of US frames, and 2) a lack of publicly-accessible data with synchronized spatial location, often obtained from tracking devices, for benchmarking the performance and for training learning-based methods.
The TUS-REC challenge aims to provide a benchmark for freehand US reconstruction with publicly available in vivo US data from the forearms of one hundred volunteers, using multiple predefined scanning protocols, targeted to improve the reconstruction performance in this challenging task.
The outcome of the challenge includes 1) open-sourcing the first largest tracked US datasets with accurate positional information; and 2) establishing one of the first benchmarks for 3D US reconstruction, suitable for modern learning-based data-driven approaches.

### [Landmark Detection Challenge for Intrapartum Ultrasound Measurement Meeting the Actual Clinical Assessment of Labor Progress](https://www.codabench.org/competitions/7108/)

A cornerstone of ultrasound-based labor assessment is the identification of landmarks in intrapartum images, which form the basis for calculating key parameters like the angle of progression (AoP). The AoP provides critical insight into fetal head descent and rotation during labor and directly influences decisions about interventions. However, obtaining consistent landmark annotations remains a major challenge: current workflows require time-consuming manual analysis by experienced obstetricians, and intra-/inter-observer variability compromises measurement reliability. This bottleneck highlights the urgent need for automated solutions to standardize intrapartum assessments and align with the LCG's goal of enhancing care quality.
To address this need, the challenge tasks participants with developing a fully automated fetal biometry method. The solution should identify three key anatomical landmarks in intrapartum ultrasound images and get the AoP.

## Organizers

### Chairs

- Dong Ni (Chair, Shenzhen University, CN)
- Alison Noble (Co-Chair, University of Oxford, UK)

### Organising Committee

- Dong Ni (Shenzhen University, CN)
- Alison Noble (University of Oxford, UK)
- Stephen Aylward (Kitware, USA)
- Yipeng Hu (Univ. College London, UK)
- Purang Abolmaesumi (Univ. of British Columbia, CA)
- Alberto Gomez (Ultromics, UK)
- Andrew King (King’s College London, UK)
- Bishesh Khanal (NAAMII, Nepal)
- Ana Namburete (Univ. of Oxford, UK)
- Bernhard Kainz (FAU Erlangen-Nürnberg, DE, and Imperial College London, UK)
- Emad Boctor (Johns Hopkins Univ., USA)
- Thomas van den Heuvel (Radboud Univ., NL)
- Wolfgang Wein (ImFusion, DE)
- Parvin Mousavi (Queen’s Univ., CA)
- Veronika Zimmer (Technical Univ. of Munich, DE)
- Qingjie Meng (University of Birmingham, UK)

### Delivery Team

- Ruobing Huang (Program Chair, Shenzhen University, CN)
- Wufeng Xue (Program Chair, Shenzhen University, CN)
- Wei Wang (Clinical Chair, Sun Yat-sen University, CN)
- Jieyun Bai (Challenge Chair, Jinan University, CN)
- Qi Li (Challenge Chair, Univ. College London, UK)
- Jun Cheng (Communication Chair, Shenzhen University, CN)
- Xin Yang (Demonstrations Chair, Shenzhen University, CN)
- Yi Wang (Web Chair, Shenzhen University, CN)

### Advisory Board

- Gabor Fichtinger (Queen’s Univ., Canada)
- Kawal Rhode (King’s College London, UK)
- Russ Taylor (Johns Hopkins Univ., USA)
- Chris de Korte (Radboud Univ. Nijmegen, NL)
- Nassir Navab (Technical Univ. of Munich, Germany)
- Reza Razavi (King’s College London, UK)
- Joseph Hajnal (King’s College London, UK)


