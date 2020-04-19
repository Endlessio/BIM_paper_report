###  COVID-19: Epidemiology, Evolution, and Cross-Disciplinary Perspectives Report (Article 3)

<center>Student Name: Zheyuan Zhou</center>

<center> Student ID: 117010423
##### Problem statement and motivations  

###### **problem statement**

This article focuses on the COVID-19, which recently outbreak in Wuhan wet seafood market firstly and then spread to the whole world. COVID-19 is clustered into CoVs, which is a class of generic diverse viruses discovered in many host species like birds and mammals. Before COVID-19, there exists two main CoVs: SARS-CoV: Severe Acute Respiratory Syndrome Coronavirus and MERS-CoV: Middle East Respiratory Syndrome Coronavirus. There are usually two concerns when talking about epidemiology: fatality rate and transmit rate. For the fatality rate, according to current data, COVID-19’s rate is lower than SARS and MERS; however, for the transmit rate, COVID-19 is higher than SARS and MERS.

###### **motivations**

Lacking of the knowledge of COVID-19, the outbreak is still exacerbating from the whole world point of view. Therefore, acquiring more information of COVID-19 is necessary. This article tends to obtain the knowledge of it from mainly three fields: epidemiology, evolution and cross-disciplinary:

For the epidemiology realm, the authors try to figure out two points: the epidemiology curve and the clinical phenotype of COVID-19. For the evolution realm, the origin of the virus and evolution information are studied. The cross-disciplinary realm focuses on the topic that whether the COVID-19 can infect species besides homo species by comparing the structures of spike protein between COVID-19 and other CoVs, the sequences and molecular differences of ACE2 receptors among human and other species.

##### Highlights of the proposed method  

The highlights of the proposed methods will be categorized into three parts, each corresponds to one of the authors’ three motivations.

###### Epidemiology

To apply the research on epidemiology, basic statistic method and corresponding epidemiology model is constructed to calculated basic reproductive number (R0). 

In order to generate the epidemiology curve, the authors use the China as the research target, since it is the place where the first outbreak happened, collected the number of confirmed cases and fatalities (1)in different regions of China (2)in different time periods (3)among different persons: like medical-related staff and normal people, to calculate the increase rate, death rate and so on. Furthermore, basic reproductive number(R0) of COVID-19 is evaluated and compared with the number of SARS-CoV, MERS-CoV to form the idea of contagiousness or transmissibility of infectious agent$^{[1]}$.

In order to acquire clinical phenotype of COVID-19, basic statistic method is used, including atypical symptom rate, patient gender rate, death rate in different stages, patient age rate, current mortality rate in different regions, fatality rate$^{[1]}$. These data can be further analyzed to obtain the features of symptoms and tendency of COVID-19.

###### Evolution

To apply evolution analysis, three methods are used: sequences analyzed, sequence alignment and potential recombination analysis, and phylogenetic analysis.

The sequences resources come from GISAID and the National Center for Biotechnology Information GenBank databases, 18 betacoronavirus sequences and 95 full-length 2019-nCoV genomes kindlymade are collected with proper length, without sequencing artefacts.

sequence alignment and potential recombination analysis are based on MAFFT, MEGA7, GARD and Simplot$^{[1]}$. The basic procedure is: firstly, use MATTF to do the sequence alignment; secondly, use the MEGA7 to adjust teh results manually; thirdly, use GARD to detect the breakpoints based on the phylogenetic incongruence among segments; finally, use Simplot to visualize the data.

Generate ML trees to observe the inheritical results between genomes/betacoronavirus sequences using the general time reversible substitution model with gamma distributed rate heterogeneity and 1000 bootstraps by RAxML.

###### Cross-disciplinary

Two parts are discussed logically: the spike protein structure and function of COVID-19, and ACE2 receptor between different species.

The spike protein is highlighted cause it is the major determinant of cell tropism and is highly related to transmission of CoVs. The authors compared the protein structures of COVID-19, HR domain of spike protein of SARS-CoVs and HR1 domain of spike protein of SARS-CoVs by presenting the 3D structure with Pymol and corresponding pdb files. Some specific sights are underlined: the S1/S2, S2′ cleavage sites, the N terminal domain (NTD) of S2, the C terminal domain (CTD) of S2, heptad repeat (HR) domains: HR1 and HR2, peptide inhibitor EK1 and receptor-binding domain RBD$^{[1]}$. Moreover, the structure  is compared sequentially: before and after membrane fusion, since the procedure of the virus comes into host cell needs spike protein's catalyzation.

The logic to do research on ACE2 receptor according to authors is that the contact residues between the receptor-binding site can be used to estimate other species. therefore, ACE2 residues are compared among different species with the similar method as gene local alignment: for certain, determined amino acid sets, construct gene profile and determine the differences. Despite the gene profile, using 3D structure generated by Pymol of spike protein and ACE2 receptor to have a mroe concrete sense$^{[1]}$.

knowing about the structure of spike protein is significant for potential drug design, which will be described in the significant results and novel findings part.

##### Significant results and novel findings  

The significant results and novel findings part will be categorized into three parts, each corresponds to one of the authors’ three motivations.

###### Epidemiology

- The epidemiology curve of COVID-19 can be roughly divided into three phases: the first phase(2019.12 - 2020.1.13) is the local outbreak, at which the person-to-person transmission has already occurred; the feature of the second phase(2020.1.13 - 2020.1.26) is the disease sharply spreaded in hospitals and families, and corresponding lock-down policy in China published; the third phase(2020.1.26 - now) is marked by rapid increase of cluster cases$^{[1]}$.
- The basic reproductive number(R0) of COVID-19 is roughly 1.4 - 3.9, the lower limit is smaller than SARS-CoVs, the upper limit is larger than SARS-CoVs; and larger than MERS-CoVs, which might imply it is relatively hard to control the break. However, R0 is dynamic, which is related to socio-behavioral and other factors$^{[1]}$.
- It is possible that patient has COVID-19 shows atypical symptoms. The patient age won't affect the transmission. The death rate of first and second phases is higher than third phase$^{[1]}$. Overall, for the fatality rate, according to current data, COVID-19’s rate is lower than SARS and MERS; however, for the transmit rate, COVID-19 is higher than SARS and MERS.

###### Evolution

- Although it is highly possible the virus, with rich genetic diversity and frequent recombination, is transmitted from animal on the Wuhan market, the species and circumstance of the species barrier for the virus can not be determined yet.
- The Simplot and phylogenetic trees show there are two similar regions and one region with alternative source. From both nt 1 to nt 13521 and nt 13522 to nt 23686$^{[1]}$, the most similar sequence is BeraCoV/Bat/RaTG13, which implies they share the same ancestor. However, it is not valid to claim the virus was directly transmitted from bat.
- COVID-19 envolves slowly among human for their highly conserved spike protein, which is conflicted with the fasting evolving RNA virus.

###### Cross-disciplinary$^{[1]}$

- The spike protein of COVID-19 is similar to MERS-CoVs.

- The relatively large CoV genome pushes on the possiblity of adaptive mutations, resulted in easier attacnment between virus's spike protein and diverse celluar receptors, but different host receptors.

- The mechanism of COVID-19 is similar to avian influence virus for they both be cleaved by furin during biosynthesis, this information may imply that COVID-19 can adapt to multiple cell types, inducing infection among diverse species.

- Although many animal don't share N90 with human, some of them exist other glycosylation motif, which shows the possiblity of infection, need to pay attention to pet cat and farm animals.

- There are mainly two drug design possiblities, each of them need to induce multiple inhibitors: first type of drug can choose HR1 region of spike protein COVID-19 as binding site with E1 involved; second type of drug can be cellular enzymes targeted to fatty acids of cysteines in virus cytoplasmic tail of spike protein.


##### Personal evaluations and prospects on this topic

 The motivation of this topic is worth to affirm, the data is compelling, the analysis is detailed and logical, the results are objective and meaningful for further study.

However, the writer has some personal proposals and advice to generate a more comprehensive, derivative-oriented and convincing result, which will mainly focus on epidemiology part and evolution part, since the writer don't actually have solid foundation in drug design and related biology knowledge.

###### Epidemiology

In article, it only refers to the basic reproductive number and gives a relatively easy analysis. The writer, hence, tends to give further analysis by providing corresponding model to predict the transmission situation.

Basically, exists three simplest infection model: SI, SIS, SIR model, considering the patient can be infected again after recovery, use SIS model, where S: susceptible population, I: infected, $\beta$: the transition rate that multiplies the product of the S and I populations, $\gamma$: the transition rate that multiplies just the I population. 
$$
\frac {dS(t)}{dt} = -\gamma I(t) - \beta S(t)I(t)
$$

$$
\frac {dI(t)}{dt} = \beta S(t)I(t) - \gamma I(t)
$$

if $ \beta$ < $\gamma$, the infected proportion increases exponentially. If  $ \beta$ > $\gamma$, a sigmoidal curve of I(t) going up will be wistnessed, but not to 100% since some of the infected will be going back to the susceptible state. The exact saturation percentage of I(t) depends on $ \beta$ / $\gamma$, which is **the basic reproductive number**, denoted as $\sigma = \beta /\gamma$. Closed-form solution can be obtained by using S(t) = 1 - I(t) and solving the resulting dierential equation in I(t) having for some constant c, which depends on the initial condition and the corresponding figure is following ,typical curve of an epidemic outbreak$^{[2]}$:
$$
I(t) = (1 - \gamma / \beta)\frac {ce^{(\beta - \gamma)t}}{1+ce^{(\beta - \gamma)t}}
$$
<img src="/Users/endlessio/Library/Containers/com.tencent.xinWeChat/Data/Library/Application Support/com.tencent.xinWeChat/2.0b4.0.9/026cf7f197c3cb807d2e364f29a01459/Message/MessageTemp/9e20f478899dc29eb19741386f9343c8/Image/10321587176204_.pic.jpg" alt="10321587176204_.pic" style="zoom:33%;" />

However, as the article says: *whether this current COVID-19 epidemic ‘frizzles out’ or expands into a full-blown pandemic remains to be seen*. The SI model is used for the second situation: full-blown pandemic; if vaccinum is developed, then we should estimate transmission by SIR model:
$$
\frac {dS(t)}{dt} = -\beta S(t)I(t)
$$

$$
\frac {dI(t)}{dt} = \beta S(t)I(t) - \gamma I(t)
$$

$$
\frac {dR(t)}{dt} = \gamma I(t)
$$

Substitute twice to eliminate two of the three equations above, but there is no closed-form solution. However, it can be telled that $\sigma$ S(0) plays the role of threshold level that determines whether I(t) will go up rst before coming down. The trajectory of this SIR model has the following properties over a period of time [0; T]:

If $\sigma$ S(0) $\le$ 1, then I(t) decreases to 0 as t $\rightarrow$ $\infty$. There is not enough S(0) initially to create an epidemic.

If $\sigma$ S(0) $\gt$ 1, then I(t) increases to the maximum$^{[2]}$:
$$
I_{max} = I(0) + S(0) - 1/\sigma - log(\sigma S(0))/\sigma
$$
S(t) is always a decreasing function, the limit S(1) as t$\rightarrow$ $\infty$ is the unique root in (0, 1/$\sigma$) of the following equation:
$$
I(0)+S(0)-S(\infty)+\frac {1}{\sigma}log(\frac {S(\infty)}{S(0)}) = 0
$$
And the corresponding figure is following ,typical curve of an epidemic outbreak:

<img src="/Users/endlessio/Library/Containers/com.tencent.xinWeChat/Data/Library/Application Support/com.tencent.xinWeChat/2.0b4.0.9/026cf7f197c3cb807d2e364f29a01459/Message/MessageTemp/9e20f478899dc29eb19741386f9343c8/Image/10311587142658_.pic.jpg" alt="10311587142658_.pic" style="zoom: 33%;" />

###### Evolution

- When applying evolution analysis, the slide windows were set as 1000 bp, with each step 500 bp for sequence alignment and potential recombination analysis. However, it is admitted that different slide window might generate different results and it is difficult to determine the optimal step size. Therefore, I suggest to try different slide window and step size to observe the results.
- When compare the structure and function of spike protein of COVID-19, the authors actually only compare the structures between COVID-19 and SARS-CoVs, it might be more helpful if the MERS-CoV is included and given a more intact figure.

##### Reference

[1] Jiumeng S., Wan-Ting H., Lifang W.. *COVID-19: Epidemiology, Evolution, and Cross-Disciplinary Perspectives*. Trends in Molecular Medicine. https://doi.org/10.1016/j.molmed.2020.02.008.

[2] Chiang, M. (2010). *Networked life: 20 questions and answers*. Cambridge University Press. https://doi.org/10.1017/CBO9781139176200

