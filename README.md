# RayDynamics
RayDynamics Model provides a Novel and holistic approach for White Blood Cell (WBC) movement dynamics

# First Example od RayDynamics Model Simulation
Following Figure displays a plot showing how the WBC speed changes under different scenarios (by varying Pd and Cr). It helps us to compare which mechanism results in faster speeds under different conditions. 
* We'll vary the parameters Pd and Cr (coefficients for paddling and crawling) over a range to simulate various scenarios.
* The other influencing factors, such as s_w and S_surface (surface adhesion strength), will be kept constant for this simple comparison.
* We'll plot the resulting speeds for both mechanisms over the range of varying parameters.

![Screenshot from 2023-08-14 14-29-08](https://github.com/ParthaPRay/RayDynamics/assets/1689639/5544a3c3-cdf3-4a8b-bc33-b9c03c39c4c3)

# Second Example od RayDynamics Model Simulation

To determine the time taken by the WBC to engulf a pathogen, we need to define some additional factors:
* Distance to the Pathogen: The distance that a WBC needs to travel to reach and engulf a pathogen. For this illustration, let's consider a constant distance, d = 100 units (you can change it as per your requirement).
* Engulfment Speed: How quickly the WBC engulfs the pathogen once it reaches it. This might differ slightly based on whether the WBC is crawling or paddling, but for the sake of simplicity, let's consider a constant value.
* Given that speed is distance over time (speed = distance/time), the time taken to reach the pathogen is time = distance/speed.


![Screenshot from 2023-08-14 14-37-49](https://github.com/ParthaPRay/RayDynamics/assets/1689639/8ff01262-cacf-4afb-aaec-5236e4fb852b)


