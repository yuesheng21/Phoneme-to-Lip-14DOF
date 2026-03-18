# Phoneme-to-Lip-14DOF

### Realistic Lip Motion Generation Based on 3D Dynamic Viseme and Coarticulation Modeling for Human-Robot Interaction

This is the data repository for the paper. This project proposes a dynamic viseme generation method tailored for the Chinese linguistic environment and successfully achieves high-fidelity lip synchronization on a 14-DOF humanoid robot platform. 

## 📊 3D Dynamic Viseme Library

This project releases the core **3D Dynamic Viseme Dictionary**, which includes 14 sets of non-linear temporal trajectories specifically designed for core Chinese pronunciations.

## Data Specifications:

- **Sampling Rate**: 60 FPS (normalized to a 1s standard duration)
- **Dimensionality**: 27-dimensional Blendshapes (ARKit standard)
- **Format**: CSV (includes Timecode, BlendshapeCount, and individual channel values)

| **Directory** | **Description**                                              |
| ------------- | ------------------------------------------------------------ |
| `/nor_data`   | Normalized CSV files for 14 types of dynamic visemes         |
| `/video`      | A real-robot demonstration video containing 14 dynamic visemes and the corpus test set. |

## 📩 Contact

For academic exchange or hardware adaptation questions, please reach out to: **[M202570574@hust.edu.cn]** (ShengLi**Intelligent Mechatronics and Control Research Laboratory**, HUST).