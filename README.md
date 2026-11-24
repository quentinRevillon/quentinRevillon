# Quentin Revillon

Machine learning and computer vision for medical and satellite imaging. MSc in AI and Data Science (IASD,
Paris-Dauphine-PSL) and engineering degree at Télécom Paris. Previously research intern at Mila - Quebec AI
Institute & NeuroPoly (spinal cord MRI) and computer vision intern at Synspective (SAR imagery, Tokyo).

## Selected work

- [**sc-crop**](https://github.com/ivadomed/sc-crop): Python package and CLI that detects the spinal cord in
  MRI/CT and crops the volume around it. Main contributor, published on
  [PyPI](https://pypi.org/project/sc-crop/) and integrated into
  [Spinal Cord Toolbox](https://github.com/spinalcordtoolbox/spinalcordtoolbox), where it brings CPU
  segmentation from about 2 min to 10-20 s.
  and segment NIfTI images with ONNX Runtime and NumPy, without PyTorch.
- [**lv-segmentation-cardiac-mri**](https://github.com/quentinRevillon/lv-segmentation-cardiac-mri):
  left-ventricle segmentation in cardiac cine MRI (ACDC) with Hough-transform seed detection and region
  growing, no deep learning. 3D Dice 0.92 at end-diastole on 50 test patients.
- [**acdc-cardiac-diagnosis**](https://github.com/quentinRevillon/acdc-cardiac-diagnosis): cardiac pathology
  classification from morphological LV reconstruction and cardiac biomarkers. 88% accuracy on the Kaggle
  private leaderboard.
- [**SinGAN**](https://github.com/quentinRevillon/SinGAN): PyTorch re-implementation of SinGAN and a
  discriminator-free Sliced Wasserstein variant (team of 4, Télécom Paris).
- [**sar-subaperture-decomposition**](https://github.com/quentinRevillon/sar-subaperture-decomposition):
  re-implementation of the subaperture decomposition of Ristea et al. (2022) for Sentinel-1 wave-mode SLC
  imagettes.

At Synspective, I trained a SegFormer-B0 to segment meteorological phenomena in SAR ocean imagery; the project
was selected for JAXA's On-Orbit Demonstration of AI Applications program (code not public).

## Skills

Python, PyTorch, Hugging Face, OpenCV, nnU-Net, ONNX Runtime, Docker, Git, Linux.

## Contact

[LinkedIn](https://linkedin.com/in/quentin-revillon)
