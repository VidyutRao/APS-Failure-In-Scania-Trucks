# APS-Failure-In-Scania-Trucks
The dataset consists of data collected from heavy Scania trucks in everyday usage. The system in focus is the Air Pressure system (APS) which generates pressurized air that are utilized in various functions in a truck, such as braking and gear changes. The dataset positive class consists of component failures for a specific component of the APS system. The negative class consists of trucks with failures for components not related to the APS. The data consists of a subset of all available data, selected by experts.
The dataset was released by Scania CV AB on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/APS+Failure+at+Scania+Trucks). The challenge was to predict the failure of Scania Air Pressure System (APS) in trucks to enable preventive maintenance and thereby reduce the maintenance costs. The dataset is anonymized and contains binned values due to proprietary reasons.
Our goal is to minimize the costs associated with:
1. Unnecessary checks done by a mechanic. ($10)
2. Missing a faulty truck, which may cause a breakdown in the future. ($500)
However the main objective will be to predict and minimize the cost of failures associated with these combinations of readings.
