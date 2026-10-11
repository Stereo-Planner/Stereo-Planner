# Stereo-Planner: Learning Stereo-to-Trajectory Planning for Zero-Shot Sim-to-Real Quadrotor Navigation

Stereo-Planner is an end-to-end vision-to-action framework that directly generates agile, collision-free trajectories from onboard stereo RGB observations and enables zero-shot sim-to-real transfer without explicit depth reconstruction or dedicated depth sensors.

![Network Architecture](doc/NetworkArchitecture.jpg)

Training exclusively on simulation data enables agile flight in real-world environments.

<div align="center">
  <img src="doc/RealFlightTraj.gif" alt="Real-world flight trajectory" width="99%" /><br />
  <em>Zero-Shot Flight in the Real World at Over 7 m/s</em>
</div>

<p align="center">
  <img src="doc/RealFlightTPV.gif" alt="Third-person view of real-world flight" width="49%" />
  <img src="doc/RealFlightFPV.gif" alt="First-person view of real-world flight" width="49%" /><br />
  <em>Third-Person View (left) · First-Person View (right)</em>
</p>

Our simulator, built on the Unity game engine, enables plug-and-play scene construction using assets from the [Unity Asset Store](https://assetstore.unity.com/) and will be released as open source.

<p align="center">
  <img src="doc/Forest10mpsTest.gif" alt="Forest simulation flight test at 10 m/s" width="49%" />
  <img src="doc/Industy10mpsTest.gif" alt="Industrial simulation flight test at 10 m/s" width="49%" /><br />
  <em>Forest Flight at 10 m/s (left) · Industrial Flight at 10 m/s (right)</em>
</p>

Our drone design and SOLIDWORKS CAD files will also be released as open source.

<div align="center">
  <img src="doc/Platform.jpg" alt="Drone hardware platform" width="99%" />
</div>

## Acknowledgments
This project builds on [Depth Anything V3](https://github.com/ByteDance-Seed/depth-anything-3). We thank the authors for their excellent work!

## Additional Information
<!-- If you find this work useful or interesting, please give us a star ⭐. If you use this repository in your research, please cite our paper. Thank you! -->

```bibtex
    @ARTICLE{
    author={Shen, Hongming and Lu, Junjie and Chen, Xun and Wang, Wei and Xu, Xinhang and Tian, Bailing and Xie, Lihua},
    title={Stereo-Planner: Learning Stereo-to-Trajectory Planning for Zero-Shot Sim-to-Real Quadrotor Navigation}, 
    year={2026}}
```
