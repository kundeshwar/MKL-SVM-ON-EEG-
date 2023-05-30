
## MKL-SVM Algorithm for Semi-Supervised Learning in Schizophrenia Study
### Introduction
> This project aims to evaluate brain connectivity using electroencephalography (EEG) data from patients with schizophrenia and healthy controls. The study applies the MKL-SVM (Multiple Kernel Learning Support Vector Machine) algorithm for semi-supervised learning on the dataset.

### Data and Methods
> The study utilizes EEG data from 14 patients with schizophrenia and 14 healthy controls. The data is processed as follows:

1. Preprocessing: Artifacts and noise are removed from the EEG data.
2. Connectivity Measures: PLV, PLI, and DTF are calculated for the original EEG data and after applying CSD transformation, AVERAGE re-referencing, and REST re-referencing techniques.
3. Graph Theory Analysis: Graph theory-based indices are computed using the adjacency matrices obtained from the connectivity measures.
### MKL-SVM Algorithm
The MKL-SVM algorithm is employed for semi-supervised learning on the processed EEG data. The steps involved are as follows:

1. Feature Extraction: Relevant features such as connectivity measures or graph-based indices are extracted from the EEG data.
2. Data Labeling: Labels are assigned to a subset of the data (e.g., schizophrenia patients) while leaving the remaining data unlabeled.
3. Kernel Generation: Multiple kernels are generated using different representations of the data, such as PLV, PLI, DTF, or graph-based indices.
4. Multiple Kernel Learning: The optimal combination of kernels is learned using the MKL framework to capture discriminative information from the labeled and unlabeled data.
5. Support Vector Machine: An SVM classifier is trained on the combined kernel matrix to classify the unlabeled data and evaluate the model's performance.
### Results and Analysis
The results of the study indicate the following findings:

1. Reduced connectivity strength, lower clustering coefficient, and shorter characteristic path length were observed in schizophrenia patients compared to healthy controls in the alpha band.
2. Schizophrenic patients exhibited increased directional flow from the occipital region in the alpha band.
3. The sources of alpha activity were found to be located at parietal derivations following REST re-referencing.
4. Different connectivity measures showed group differences in fronto-posterior asymmetry, with significant results obtained using CSD transformation, PLV, and DTF. REST re-referencing showed significant differences only for PLI.
5. DTF calculated for REST identified group differences in inter-hemispheric asymmetry.
### Conclusion
> The MKL-SVM algorithm combined with various connectivity measures and graph-based indices > > > provides insights into the disconnectivity patterns in schizophrenia. The study emphasizes the importance of considering different frequency bands and connectivity measures to understand the underlying brain connectivity alterations in psychiatric disorders.

### Future Work
Future work in this area could involve:

- Exploring additional machine learning algorithms and techniques to further improve the classification performance.
- Investigating the impact of different preprocessing steps and connectivity measures on the results.
- Expanding the study to a larger dataset and including more diverse clinical populations for a comprehensive analysis.
### Acknowledgements
We would like to acknowledge the support and contributions of Kundeshwar V. Pundalik in the completion of this project.

### License
> This project is licensed under the MIT. See the LICENSE file for details.

### References
> If any, include a list of references to relevant papers, datasets, or resources used in the project.

### Contact Information
For any inquiries or questions, please contact kundeshwar15000@gmail.com.
