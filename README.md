# Deeply Nonverbal Vocalization Data
__Contact for any inquiries__ Email: contact@deeplyinc.com | Web: http://deeplyinc.com/ | Tel: (+82) 70-7459-0704
## Summary
The Nonverbal Vocalization Dataset is <u>*__a human nonverbal vocal sound dataset(a.k.a. vocal characterizer)__*</u> consisting of <u>*__56.7 hours__*</u> of short clips from <u>*__1419 speakers__*</u>, crowdsourced by the general public in South Korea. Also, the dataset includes metadata such as age, sex, noise level, and quality of utterance. 16 classes of Included human nonverbal sound data contain <u>*__‘teeth-chattering’, ‘teeth-grinding’, ‘tongue-clicking’, ‘nose-blowing’, ‘coughing’, ‘yawning’, ‘throat clearing’, ‘sighing’, ‘lip-popping’, ‘lip-smacking’, ‘panting’, ’crying’, ‘laughing’, ‘sneezing’, ‘moaning’, and ‘screaming’.__*</u>

  **Device** | **Android phones** |
  :-:|:-:|
  **Volume(Sample)** | **\~ 57(~ 0.6) hours, ~ 70,000(~ 800) utterances,<br /> ~ 18(~ 0.1) GB, ~ 1500(~ 500) speakers** |
  **Format** | **wav/h5(16/44.1kHz, 16-bit, mono)** |


Refer to the dataset descriptions in 'docs' for detailed description and statistics of the full set of the dataset.

The sample audio data is a subset(approximately 1%) of a much bigger dataset which were recorded under the same circumstances as these open source samples. Please contact us(contact@deeplyinc.com) for the pricing and licensing.

### Feature Nonverbal Sound
* __Coughing Sound__
https://user-images.githubusercontent.com/49251855/141922222-ddc5dcda-9ed9-45dd-bf29-7206ff8573ee.mov
* __Crying Sound__
https://user-images.githubusercontent.com/49251855/141922259-4ccb9de7-3fc4-41ee-8440-e75736ecb4ec.mov
* __Screaming Sound__
https://user-images.githubusercontent.com/49251855/141922281-854edd08-241f-4e0d-9ef5-0aaf9d2c9d47.mov
* __Moaning Sound__
https://user-images.githubusercontent.com/49251855/141922300-4900ceb5-0fc7-48a8-aca2-e0fb1415c26f.mov
* __Laughing Sound__
https://user-images.githubusercontent.com/49251855/141922313-455bb7f9-00dd-40cf-a153-dfa92f9aa44a.mov
* __And 11 more Sound!__

**[Click here to download sample](https://www.openslr.org/resources/99/NonverbalVocalization.tgz)**

## Dataset statistics
The illustrations below are the statistics about the Deeply Nonverbal Vocalization dataset. The first two are from the sample audio data, And the others are from the full dataset. To attain more insight about the dataset, please refer to the detailed description in 'docs'.

<p float="left">
  <img src="https://github.com/deeplyinc/Nonverbal-Vocalization-Dataset/blob/main/etc/fig0.png" width="400" />
  <img src="https://github.com/deeplyinc/Nonverbal-Vocalization-Dataset/blob/main/etc/fig1.png" width="400" /> 
</p>
<p float="left">
  <img src="https://github.com/deeplyinc/Nonverbal-Vocalization-Dataset/blob/main/etc/fig2.png" width="400" />
  <img src="https://github.com/deeplyinc/Nonverbal-Vocalization-Dataset/blob/main/etc/fig3.png" width="400" /> 
</p>
  <img src="https://github.com/deeplyinc/Nonverbal-Vocalization-Dataset/blob/main/etc/fig4.png" width="800" /> 

## Structure
```
├── dataset
│   ├── Nonverbal_Vocalization_metadata.json
│   ├── coughing
│   │   ├── 0C1S_4_8_0_27_0_1_1.wav
│   │   ├── ...
│   ├── crying
│   │   ├── 1TCO_11_10_0_20_0_0_0.wav
│   │   ├── ...
│   ├── ...
│   ├── ...
│   ├── tongue-clicking
│   │   ├── 06RU_2_7_1_38_0_0_0.wav
│   │   ├── ...
│   └── yawning
│       ├── 0DYI_5_10_1_12_0_1_0.wav
│       ├── ...
└── docs
    ├── Deeply\ Nonverbal\ Vocalization\ Dataset\ description_Eng.pdf
    └── Deeply\ Nonverbal\ Vocalization\ Dataset\ description_Kor.pdf
```

```
Nonverbal_Vocalization_metadata.json
{
    'LAA7': {'sex': 'Male',
    'age': 22,
    'class': ['teeth-chattering', 'teeth-grinding', 'lip-smacking']},
    ...
    'WVST': {'sex': 'Female',
    'age': 15,
    'class': ['nose-blowing','coughing','yawning','throat-clearing','sighing',
    'lip-popping','sneezing','screaming']}
}
```

### Filename convention
{speaker_ID}\_{class}\_{trial}\_{sex}\_{age}\_{location}\_{quality}\_{noise}.wav
```
Class: {0: ‘teeth-chattering’, 1: ‘teeth-grinding’, 2: ‘tongue-clicking’, 3: ‘nose-blowing’, 
        4: ‘coughing’, 5: ‘yawning’, 6: ‘throat-clearing’, 7: ‘sighing’, 8: ‘lip-popping’, 
        9: ‘lip-smacking’, 10: ‘panting’, 11: ‘crying’, 12: ‘laughing’, 13: ‘sneezing’, 14: ‘moaning’, 15: screaming’}
Sex: {0: ‘Female’, 1: ‘Male’}
Location: {0: ‘indoor’, 1: ‘outdoor’}
Quality: {0: ‘High’, 1: ‘Low’}
Noise: {0: ‘Noiseless’, 1: ‘Noisy’}
```

## License
Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)  
![Vue](https://github.com/deeplyinc/Nonverbal-Vocalization-Dataset/blob/main/etc/by-nc-nd.png)

## Other Deeply datasets
* **[Deeply Korean Read Speech Corpus](https://github.com/deeplyinc/Korean-Read-Speech-Corpus)**
  - Pairs of Korean reading the scripts with 3 text sentiments using 3 vocal sentiments. Recorded in 3 types of places, at 3 distinct distances, with 2 types of smartphone.
* **[Deeply Parent-Child Vocal Interaction Dataset](https://github.com/deeplyinc/Parent-Child-Vocal-Interaction-Dataset)**
  - The interaction of pairs of parent and child(reading fairy tales, singing children’s songs, conversing, and others).Recorded in 3 types of places, at 3 distinct distances, with 2 types of smartphone.

## Contact
Tel:   (+82) 70-7459-0704  
Web:   http://deeplyinc.com/  
Email: contact@deeplyinc.com

