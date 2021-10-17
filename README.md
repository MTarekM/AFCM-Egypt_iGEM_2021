# AFCM-Egypt_iGEM_2021
The repository for all the software created by the team AFCM-Egypt of iGEM 2021. 
 
#This repo was created by team AFCM-Egypt


An Approach to Deep Learning-Assisted Zero-N Directed Evolution of Proteins

Summary:

Engineering enhanced versions of proteins requires complex processes that integrate various measurements. This process is often overwhelmed by challenges that are specific for each engineering case. Herein, we have developed a computational approach that integrates predictions of mutational effects on evolutionary fitness with encodings for local and global features representations of protein sequences. These features were used to design a machine learning framework in an approach to accurately predict fit variants without necessitating experimental inputs. 

![Pipeline](https://raw.githubusercontent.com/MTarekM/AFCM-Egypt_iGEM_2021/main/1.jpg)

This Repo contains four notebooks, each represent functions to encode relevant features:

1-Generate_&_Compute_Independent_&_Epistatic_effects_of_Combinatorial_&_Scanning_libraries(1).ipynb

This runs the generator function and performs the independent and epistatic effects predictions. The notebook is based on an example with
the Oligopeptide transport ATP-binding protein AmiE.

#Function_Encoder2 > Provides epistatic predictions based on coupling potential four only mutated positions vs Encoder that provides coupling potentials for the whole protein sequence. Where the Encoder provides more accurate predictions, while Encoder2 is more time-efficient.

2-Functions_for_Global_Evo_features.ipynb

This encodes global evolutioanry features.

3-Functions_for_Local_Evo_features.ipynb

This encodes local evolutioanry features.

4-Functions_for_Physicochemical_paramters_features_&_components.ipynb

This encodes physicochemical paramters.

Feel free to know more about our computational approach for protein engineeting
https://2021.igem.org/Team:AFCM-Egypt/Software


