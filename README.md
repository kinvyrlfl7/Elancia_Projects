# Elanica Project
<!-- 본 저장소는 현재 작성중인 논문 "Resource Integrity Vulnerabilities and Protections in RPG Games: A Case Study of Elancia" 에 포함될 실험 영상을 공유하기 위해 생성됨.-->

This repository was created to share experimental footage that will be included in the paper currently in progress, "Resource Integrity Vulnerabilities and Protections in RPG Games: A Case Study of Elancia"

## Experimental Environment
- Windows 11 Pro: 24H2 (OS Build 26100.4061)
- OBS Studio: 31.0.3
- DaVinci Resolve: 19
- VMWare 17 Pro: 17.6.3 build-24583834
    - Windows 10: 22H2 (OS Build 19045.5854)
    - HxD: 2.5.0.0(x86-64)
    - Elancia: 2025/05/15(lastest check)

## List of experimental videos
1. Movement Speed Tampering_720p.mp4
    - An experiment that creates two virtual environments, places an item between a user who modifies the movement speed value of MOVESPEED.TBL and a user who does not, and checks who gets the item faster

2. Music Tampering_720p.mp4
    - Experiment to check whether the music output in the server selection window changes when the music file SNDBGMTHESTHEME_0.WAV in Hastur.dat, which is the music output in the server selection window, is replaced with another music file.
