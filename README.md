# OpenKeySound
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

Free live-recorded key tones.  
免费实录按键音

## File structure
```
Root
├─ KeyTone
│  ├─ README.md
│  ├─ Record-[N]
│  │  ├─ xxxx.wav
│  │  └─ yyyy.wav
│  └─ Record-[N]
│     ├─ xxx.wav
│     └─ yyy.wav
└─ README.md
```
All recordings are stored in the `KeyTone` directory, and the `README.md` file describes the configuration of each recording. The recordings for each configuration are stored in a separate "Record" directory.  

The file naming format is `kt{NN}-{TTTT}-{p}-{nn}`, where:  
- **NN** is the recording configuration number,  
- **TTTT** is the recording type,  
- **p** is the parameter (set to 0 if no parameter exists),  
- **nn** is the sequence number.  

Examples:  
- `kt01-click-03-02` represents the 2nd set of "click" sounds with a force level of 03, recorded under the kt01 configuration.  
- `kt05-release-00-05` represents the 5th set of "release" sounds recorded under the kt05 configuration (with no parameter).
## License

This repository is licensed under the [CC BY-NC 4.0 License](http://creativecommons.org/licenses/by-nc/4.0/).  
- **You are free to**: Use, modify, and share the files, but attribution (credit to the original author) is required.
- **You may not**: Use the material for commercial purposes.

本项目的音频文件采用 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) 许可。  
- **您可以**：自由使用、修改、分享，但需**署名**（注明原作者）。  
- **您不可**：用于商业用途。  
