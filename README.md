# Single-Track Vehicle Analysis

This project is focused on conducting handling analysis using a single-track vehicle model. In this model, the wheels on the front and rear axles are simplified into one front tire and one rear tire. The analysis assumes very small angles and considers the tires to operate within the linear region of their performance.

<div style="text-align: center;">
    <img src="https://github.com/MoBehtash/linear_single_track_vehicle/blob/main/images/schematic.jpg " alt="Time Domain Analysis" width = "500"  />
    <p><em>Figure 1: Schematic of the Single-Track (Bicycle) Model</em></p>
</div>

## Features
-**Time Domain Analysis:** Understand how the vehicle reacts dynamically to sudden steering input, providing insights into its transient behavior.

-**Frequency Domain Analysis:** Gain insights into the vehicle's frequency response characteristics, which are crucial for understanding stability and control.

## Limitations
-**Linear Tire Models:** The analysis assumes linearity of the tire models, which may not accurately capture non-linear tire behavior.

-**Small Angle Assumption:** The analysis assumes very small angles, which may not hold true in all real-world scenarios.

## Results
You can visualize the results of the suspension analysis below:

![Time Domain Analysis](https://github.com/MoBehtash/linear_single_track_vehicle/blob/main/images/time_res.jpg )
*Figure 2: Example of Time Domain Analysis*

![Frequency Domain Analysis](https://github.com/MoBehtash/linear_single_track_vehicle/blob/main/images/freq_res.jpg)
*Figure 3: Example of Frequency Domain Analysis*

## Disclaimer
Please note that while this vehicle model and analysis framework can provide valuable insights, there is no guarantee of its accuracy in representing real-world vehicle behavior. The model's simplicity and assumptions may not fully capture the complexities of actual automotive vehicles.

**Note:** Feel free to contribute, share your insights, or open issues for discussion. Collaboration is key to expanding our understanding of vehicle dynamics.


## Languages and Utilities Used
- Python 3.12</b>
- Packages: numpy, matplotlib, scipy, math
