Text Description of the Used Database

The experiments used the University of Ottawa Ball-Bearing Vibration and Acoustic Fault Data Under Constant Load and Speed Conditions (UODS-VAFDC). This database contains vibration signals collected from ball bearings operating under constant mechanical conditions. It includes several bearing states such as healthy bearings and different localized faults, recorded using high-quality vibration sensors.

To evaluate the robustness of the proposed method in noisy environments, Additive White Gaussian Noise (AWGN) was injected into the original clean vibration signals. Noisy versions of the dataset were created at different Signal-to-Noise Ratio (SNR) levels, including moderate and high SNRs (+1 dB, +3 dB, +5 dB) and low SNRs (–1 dB, –3 dB, –5 dB). These different SNR versions allowed the generation of datasets with increasing noise intensity.

The purpose of adding noise was to assess how well the model generalizes under realistic industrial conditions. At higher SNR levels, the added noise does not severely distort the signal, and the classifier maintains strong performance. However, at lower SNR levels, the noise significantly degrades the vibration signals, which makes the classification task more challenging and highlights the model’s limitations under very noisy conditions.
