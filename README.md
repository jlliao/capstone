# capstone

<div style='border: 2px solid #f00;'>
  <img width="640" src="slam.gif">
</div>
</br>

The simultaneous localization and mapping (SLAM) problem questions the autonomy of a mobile robot in an unfamiliarised environment: would a robot be able to explore and incrementally construct the information of its surroundings, yet at the same time accurately locate its position in the complex, realistic environment. 

In this capstone project I introduce real-time filtering system for the current [SLAMBench program](https://github.com/jlliao/slambench2). This filtering system enables researchers to evaluate the impact of various filtering and preprocessing techniques on different open source or proprietary SLAM systems. It is a tool that ensures the reproducibility of results for existing filtering methods and allows the integration and evaluation of new filters for SLAM algorithms. Through a series of testing and experimentations, we demonstrate its configurability, extensibility and its ease of use to benchmark different filters for SLAM systems. In summary, we present the following contributions:
* A publicly available filtering system, integrated with SLAMBench, that supports quantitative, reproducible comparison of different filtering techniques for SLAM systems.
* A filtering system that is configurable, extensible and enables plug and play of new filters.
* Various experimenting cases of different filters (resize, blur, random drop, etc.) on state-of-art SLAM systems.
