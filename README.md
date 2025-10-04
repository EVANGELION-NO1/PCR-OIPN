# PCR-OIPN
Physics-Guided Counterfactual Causal Learning for Explainable Single-Source Domain Generalization Cross-Machine Bearing Fault Diagnosis
.
├── main.py                 # Main training and testing script
├── data_set.py            # Dataset configuration and loading module
├── generate_bearing_fault_angular.py  # Counterfactual sample generator
├── model.py               # Deep learning model definition

The dataset files included with the code are for demonstration purposes only. Users may download the dataset themselves and organize the dataset files according to the established format. The labels corresponding to the three health states—healthy, inner race fault, and outer race fault—are 0, 1, and 2, respectively. Since the code assigns data labels based on the order of file names, please ensure that the data order within each folder is arranged as healthy, inner race fault, and outer race fault.
