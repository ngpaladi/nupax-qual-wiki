## Outline
1. Neutrino Oscillations
2. Atmospheric Neutrinos
3. IceCube

## [[Neutrino Oscillations]]
 - First suggestion of neutrino mixing  was deficit in [[Solar Neutrinos]]  
 - Reactor Experiments
	 - Daya Bay
 - PMNS Matrix: $$\begin{pmatrix} \nu_e \\ \nu_\mu \\\nu_\tau\end{pmatrix} = \begin{pmatrix}1 & 0 & 0 \\ 0 & c_{23} & s_{23} \\ 0 & -s_{23} & c_{23}\end{pmatrix} \begin{pmatrix}c_{13} & 0 & e^{-i\delta} s_{13} \\ 0 & 1 & 0 \\ -e^{i\delta}s_{13} & 0 & c_{13}\end{pmatrix}\begin{pmatrix}c_{12} & s_{12} & 0 \\ -s_{12} & c_{12} & 0 \\ 0 & 0 & 1\end{pmatrix}\begin{pmatrix} \nu_1 \\ \nu_2 \\\nu_3\end{pmatrix}$$
	 - Parameterized by 3 angles: $\theta_{12},\theta_{13},\theta_{23}$ and 1 complex phase $\delta$
 - Primarily measure parameters related to $\theta_{23}$, $\Delta m_{23}^2$
 - Oscillation probability: $$P_{\nu_\mu\rightarrow \nu_\tau} = \sin^2(2\theta) \sin^2 \left(\Delta m^2 \frac{L}{4E}\right)$$
	 - $L$ (travel distance)
	 - $E$ (neutrino energy)
		 ![[Pasted image 20230508104255.png|400]]
 - Probe L/E range 0-1200 (km/GeV)
 
## Atmospheric Neutrinos
	 ![[Pasted image 20230508125119.png|300]]
	 - [[Cosmic Rays]] are ~90% protons, ~9% alphas, ~1% heavier nuclei and electrons
	 - Showers dominantly to $\pi^\pm$
	 - $(\nu_\mu+\overline{\nu}_\mu)/(\nu_e+\overline{\nu}_e) \approx 2$
	 - 
 - Measure $\nu_\mu$ dissappearance and $\nu_\tau$ appearance
	 - $\nu_\mu$: muon tracks in detector
	 - $\nu_\mu$ & $\nu_e$: **cascades** from [[Deep Inelastic Scattering]] 

## [[IceCube Detector]]
![[Pasted image 20230508011333.png|400]]
![[Pasted image 20230507205239.png|400]]
 -  [[Cherenkov Detectors]] with ~1 cubic km instrumented volume
 - 86 Strings of 60 [[Digital Optical Modules]]
	 - Spaced 125 m apart
	 - Span from 1.5-2.5km depth
 - 8 Strings in DeepCore
	 - 7m vertical spacing, 70m horizontal
	 - Higher efficiency PMTs
	 - In clearest ice
	 - 10-200 GeV Range
 - Signal
	 - Upwards muon
	 - Cascades ([[Neutrino Scattering]], particularly [[Deep Inelastic Scattering]])
		 - $\nu_e$, $\nu_\tau$, NC interaction
 - Systematics
	 - Dust layer
		 - Can lead to "double bang" tau-like events
	 - Poor energy resolution 
		 - Order of magnitude
	 - Layered effect of ice
		 - Can be calibrated against
	 - Atmospheric neutrino flux
 - Measure $\theta_{23}$ and $\Delta m_{32}^2$
	 - Filter data with BDTs
	 - Reconstruct "tracks" of muons
	 - Further filtering with BDTs to cut down atmospheric muon background
	 - Ensure upgoing by checking average height vs first timing quartile average height
	 - Fit dissappearance data with respect to zenith angle
 - Primarily looking for ~5Gev-200GeV neutrinos
 - Sensitivity to [[Neutrino Mass]] ordering through matter effects
	 - Primarily through Earth's core
 - Backgrounds:
	 - Atmospheric muons
	 - Radioactive decays in DOM glass
	 - $10^6$ higher rate than signal
 - Results
    ![[Pasted image 20230508095023.png|400]]
	 - $\sin^2 \theta_{23} \sim 0.5$
	 - $\Delta m^2_{32} \sim 2.4\times10^{-3} \text{ eV}^2$
 
## Random Facts
- ORCA detector at KM3Net similar idea but in the Medditerranean sea
	- Use more isotropic PMT configuration
- 