# Vehicle Cut In Detection

**CUT-IN DEFINITION:** Cut-in is defined as a lane change maneuver performed by an adjacent vehicle into the ego lane.

**PURPOSE:** The model aims to identify critical situations on the road by detecting vehicles that abruptly change lanes (cut-in) in front of a designated target vehicle. This includes identifying the cut-in maneuver itself, as well as the specific vehicle performing the cut-in, based on sensor data and visual information. By predicting these cut-in events, the model can help prevent potential collisions and improve overall driving safety.

**SCOPE:** The model focuses on detecting abrupt lane changes (cut-ins) by other vehicles directly in front of a target vehicle within a typical highway or multi-lane road environment.

**MODEL:** A hybrid (spatio-temporal) model integrating image and location prediction for advanced object detection, bounding box refinement, and predictive collision analysis.

**DATASET:** The Indian Driving Dataset (IDD) is a multimodal dataset specifically designed for road scene understanding in the challenging and unique conditions of Indian roads. It provides a rich source of data for developing algorithms capable of handling the complexities of Indian traffic scenarios.

Source: https://idd.insaan.iiit.ac.in/ 

**DETAILED REPORT:** https://docs.google.com/document/d/1mSLcKjEgBXetyix6NaLDzYyCfG8IphaIqFhMfyVT9tc/edit?usp=sharing 
