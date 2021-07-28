# Description

Direct Pose Regression under Domain Shift

with
- PyraPose
- Segmentation Driven Pose
- Pixel-wise Voting Network

## Version requirements

My [docker-repository](https://github.com/sThalham/docker) provides Dockerfiles satisfying the version requirements

## Installation

for PyraPose:  
python setup.py build\_ext --inplace

for Segmentation Driven Pose:  
None

## Branches

PyraPoseDR: PyraPose + sequential direct regression  
PyraPosePDR: PyraPose + parallel direct regression  
PyraPoseDSDR: PyraPose + direct regression working under domain shift  

SegDrivenPoseDR: Segmentation Driven Pose + sequential direct regression  
SegDrivenPosePDR: Segmentation Driven Pose + parallel direct regression  
SegDrivenPoseDSDR: Segmentation Driven Pose + direct regression working under domain shift  

PVNetDR: PVNet + sequential direct regression  
PVNetPDR: PVNet + parallel direct regression  
PVNetDSDR: PVNet + direct regression working under domain shift  
