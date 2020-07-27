# Work Practices and Perceptions from Women Core Developers in OSS Communities

### Authors

   * Edna Dias Canedo 
   * Rodrigo Bonifácio 
   * Márcio Okimoto 
   * Alexander Serebrenik
   * Gustavo Pinto
   * Eduardo Monteiro
   
### Abstract 

**Background.** The effect of gender diversity in open source communities has gained increasing attention from practitioners and researchers. For instance, organizations such as the Python Software Foundation and the OpenStack Foundation started actions to increase gender diversity and promote women to top positions in the communities. **Problem.** Although the general underrepresentation of women (a.k.a. horizontal segregation) in open source communities has been explored in a number of research studies, little is known about the vertical segregation in open source communities---which occurs when there are fewer women in high level positions. **Aims.** To address this research gap, in this paper we present the results of a mixed-methods study on gender diversity and work practices of core developers contributing to open-source communities. **Method.** In the first study, we used mining-software repositories procedures to identify the core developers of 711 open source projects, in order to understand how common are women core developers in open source communities and characterize their work practices. In the second study, we surveyed the women core developers we identified in the first study to collect their perceptions of gender diversity and gender bias they might have observed while contributing to open source systems. **Results.** Our findings show that open source communities present both horizontal and vertical segregation (only 2.3% of the core developers are women). Nevertheless, differently from previous studies, most of the women core developers (65.7%) report never having experienced gender discrimination when contributing to an open source project. Finally, we did not note substantial differences between the work practices among women and men core developers. **Conclusions.** We reflect on these findings and present some ideas that might increase the participation of women in open source communities. 

### Alternative Repository 

Please, we also provide an up to date version of this package in a specific [GitHub respository](https://github.com/ednacanedo/oss-gender-kd-research.git) 

### First Study: Mining Software Repositories 

#### tools 

The tools we used to mine the GitHub repositories are available at [https://github.com/marciobtos/gitgender/](https://github.com/marciobtos/gitgender/). **Note**, part of these tools use the 
GitHub API. Changes in this API might break these tools. 

#### datasets
   * [all developers](./datasets/all_commiters_repo.csv)
   * [all truck factor developer](./datasets/tf.csv)
   * [contributions of WCD core developers](./datasets/commits_female_categorized.csv)
   * [contributions of MCD1 core developers](./datasets/commits_male_s1_categorized.csv)
   * [contributions of MCD2 core developers](./datasets/commits_male_s2_categorized.csv)
   * [contributions of MCD3 core developers](./datasets/commits_male_s3_categorized.csv)
   

#### scripts
   * (RQ1) How common are women core developers in OSS?
      * [RMD File](./analysis/RQ1.Rmd)  
      * [HTML File](./analysis/RQ1.html)
   * (RQ2) Are there differences in the work practices of women or men core developers? 
      * [RMD File](./analysis/RQ2.Rmd) 
      * [HTML File](./analysis/RQ2.html)
   

### Second Study: A survey 

#### datasets 

 * [answers to the likert scale](./datasets/survey-closed-questions.csv)
  
#### scripts

 * Assessment of the likert scale questions
      * [RMD File](./analysis/RQS.Rmd) 
      * [HTML File](./analysis/RQS.html)

#### Artifacts 

   * [Survey Questions](./survey/questions.html)
   * [Table SM1](./survey/tableSM1.html)
   * [Table SM2](./survey/tableSM2.html)
   
