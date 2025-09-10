# LateralNet

Developed by Raiyan Aaijaz & Heeya Shah

LateralNet explores biologically inspired **lateral inhibition and excitation** in convolutional networks to improve **face recognition under occlusion**. By modifying ResNet-18/50 with custom PyTorch layers, the project demonstrates improved robustness when faces are partially obscured (e.g., masks, sunglasses).

---

## Key Features
- **Custom PyTorch layers** simulating lateral inhibition/excitation
- Evaluation on the **[Real-World Occluded Faces (ROF)](https://github.com/ekremerakin/RealWorldOccludedFaces)** dataset
- Improved masked-face recognition accuracy by **up to 17% over baseline**
- Experiments comparing **ResNet-18 vs ResNet-50** across occlusion types

---

## Repository Structure
- `notebooks/` – Jupyter notebook containing training, evaluation, and visualizations
- `results/` – Accuracy tables and heatmaps
- `docs/` – Project report (optional)

---

## Installation
```bash
git clone https://github.com/raiyanjaz/lateralnet.git
cd lateralnet
pip install -r requirements.txt
