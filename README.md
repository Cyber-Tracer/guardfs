# GuardFS

This repository points to all resources leveraged in the scope of the [GuardFS paper](https://arxiv.org/abs/2401.17917).

## Ransomware Testbed
A set of scripts to bring up a VM, that mounts benign data into a ZFS dataset, and optionally a defense technique as an overlay. Multiple ransomware samples can then be executed through a container. Upon exiting the container, data loss is computed using ZFS diffs.
[Cyber-Tracer/Ransomare-Testbed](https://github.com/Cyber-Tracer/Ransomare-Testbed)

## GuardFS 
The models and defense system are in [Cyber-Tracer/FS-MTD-Detection](https://github.com/Cyber-Tracer/FS-MTD-Detection)

## Data and Samples
For the experiments, the following samples were used:
* DarkRadiation, as described in [21458_BA-Besken_14924609.pdf](https://capuana.ifi.uzh.ch/publications/PDFs/21458_BA-Besken_14924609.pdf)
* [Babuk](https://github.com/Hildaboo/BabukRansomwareSourceCode.git)
* BlackBasta (MalwareBazaar SHA256 `800ba31611d4fdb098716a98cd5861dc197de0a0cf7e0cedf31d23cda8f29f49`)
* BlackCat (MalwareBazaar SHA256 `8a5216a6088dae2c99816b326fcf925f4afca40adec7080ca0f048206b0a84ee`)
* buhti (MalwareBazaar SHA256 `5663eddf61b0e811a2178caa22d7668732d419c448a44bade7e062d0a286bcfd`)
* cia (MalwareBazaar SHA256 `1b3ff5c542a05310b6e81728fd959b3805702e84dffdc86545a511d090b6624b`)
* cl0p (MalwareBazaar SHA256 `64485c94c9672465ce58b9a4526be22209c0bd63434c86a8679e8718eb04f152`)
* conti (MalwareBazaar SHA256 `6136a400c7d1c58d91ce837aa29b1c06fdb042825cec6abab7fc5648fd4fa687`)
* [CryptoTrooper](https://github.com/jdsecurity/CryptoTrooper.git)
* [gocry](https://github.com/wille/cry))
* [gonnacry](https://github.com/tarcisio-marinho/GonnaCry)
* hive (MalwareBazaar SHA256 `90531d5ba35b2732f79a5b827aadb2dfd46f795bf76089d9b3ec136aca00743f`)
* [javaRansomware](https://github.com/PanagiotisDrakatos/JavaRansomware)
* lockbit (MalwareBazaar SHA256 `0d65aef9fe0059bcb51aca1429265c9051fce8267e18b6136d95929776ebbc93`)
* [lollocker](https://github.com/zmallen/lollocker)
* monti (MalwareBazaar SHA256 `a3edba2bcc5f77827c3d6421d6ce90e412a504e5dd6576acaff09f6c2fb0e652`)
* RaasNet, as described in [22763_BA_Thesis_Dennis_Shushack_15703341.pdf](https://capuana.ifi.uzh.ch/publications/PDFs/22763_BA_Thesis_Dennis_Shushack_15703341.pdf)
* [Ransomware-PoC](https://github.com/jimmy-ly00/Ransomware-PoC)
* royal (MalwareBazaar SHA256 `b442938f0ace23a30a0ad728ed07bcb01ffe341154f2c64a7b294c6f90066f22`)

The JMeter scripts to simulate benign behavior and the collected data are available in [this release](https://github.com/Cyber-Tracer/FS-MTD-Detection/releases/tag/MA_Robert_Oles).
