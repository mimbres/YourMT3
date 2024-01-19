![yourmt3-low-resolution-color-logo-crop](https://user-images.githubusercontent.com/26891722/204390355-001877a1-d019-46d7-a33c-d3a3adc0743c.png)
### YourMT3: Multi-task and multi-track music transcription for everyone


### [Work-in-progress Demo](https://zenodo.org/records/10531675) | [Video](https://www.youtube.com/channel/UCbH4dDVnflLMITujb_IntHQ)

UPDATE (2023 29 Oct.):
- Regrettably, due to the policy of the company I am currently working with on this project, open code will likely be possible on January 2024. 

UPDATE (2023 6 Oct.):
- YourMT3+ is currently achieving on-par with or clearly better performance (using our own augmentation) than MT3.
- YourMT3+ achieves comparable performance with PerceiverTF on Slakh when our own augmentation (similar to PerceiverTF) is applied.
- Our toolkit comes with easy-to-use auto-downloader/installer for full dataset of MT3 (except for Cerberus, which has overlap with Slakh) + MIR-ST500 for singing.
- Improved data-loading that enables everything on-the-fly by custom batching pipeline (not using auto-batch of PyTorch DataLoader)
- Note-processing and tokenization are implemented dependency-free from `noteseq`, `prettymidi`.
- System requirements for fully reproducing result: 500GB disk space, 80G (recommended) GPU memory
- ~~We are going to present this work (YourMT3+) as an ISMIR Late-breaking Demo next month in Milano.~~


