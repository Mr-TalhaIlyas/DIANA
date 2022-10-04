# DIANA

The emergence of Deep Neural Networks has allowed the development of fully automated and efficient diagnostic systems for plant disease and pest phenotyping. Although previous approaches have proven to be promising, they are limited, especially in real-life scenarios, to properly diagnose and characterize the problem. In this work, we propose a framework which besides recognizing and localizing various plant abnormalities also informs the user about the severity of the diseases infecting the plant. By taking a single image as input our algorithm is able to generate detailed descriptive phrases (user-defined) that displays the location, severity stage and visual attributes of all the abnormalities that are present in the image. Our framework is comprised of three main components. One of them is a detector that accurately and efficiently recognizes and localizes the abnormalities in plants by extracting region-based anomaly features using a deep neural network based feature extractor. The second one is an encoder-decoder network that performs pixel-level analysis to generate abnormality specific severity levels. Lastly, an integration unit which aggregates the information of these units and assigns unique IDs to all the detected anomaly instances. Thus, generating descriptive sentences describing location, severity and class of anomalies infecting plants. We discuss two possible ways of utilizing the above-mentioned units in a single framework. We evaluate and analyze the efficacy of both approaches on newly constructed diverse paprika disease and pest recognition dataset, comprising six anomaly categories along with eleven different severity levels. Our algorithm achieves mean average precision of 91.7% for abnormality detection task and mean panoptic quality score of 70.78% for severity level prediction. Our algorithm provides practical and cost-efficient solution to farmers that facilitates proper handling of crops.

 [**Full paper**](https://www.frontiersin.org/articles/10.3389/fpls.2022.983625/abstract) 
 
![Alt text](https://github.com/Mr-TalhaIlyas/DIANA/blob/main/Figuers/Figure%201.jpg)

## Dataset 

The dataset used in the paper can be downloaded from the following link

[One Drive](https://o365jbnu-my.sharepoint.com/:f:/g/personal/talha_student_jbnu_ac_kr/EtY7EzFK6LhEq2ibaVmK_V4BP712j8fZNUuz7DaqiZGFlA?e=QMWVhH)
