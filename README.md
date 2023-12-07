# SMC-CHALLENGE-IEEE-SUPCOM-SB
# Grasping the complex interplay in students' lives.

# Work description: 
# Introduction:
The scope of the challenge involves conducting data analysis to investigate the resilience of students' social, health, or emotional systems. This challenge includes a project that entails data gathering, thorough analysis, and offering actionable suggestions to enhance student well-being.



# Methodology:

## Data Collection:
Thе data collеction procеss bеgan by utilizing Googlе Forms, whеrе participants were asked to rеspond to a sеriеs of quеstionnairе statеmеnts еncompassing thrее kеy catеgoriеs: Physical and mеntal hеalth, Studеnts' Social rеlationships, and Emotional Rеsiliеncе.

The data collection process involved distributing a questionnaire to participants through various online platforms. Firstly, the questionnaire became shared among individuals via Facebook groups, namely "Tunisia.AI," "My Prepa," and the Facebook organization committed to students of Sfax Preparatory Engineering Institute,ESSTHS and Sup'Com. Additionally, the survey's link was made available by posting it in Instagram stories. Furthermore, contributors were reached through communication channels such as Emails, Messenger, and Whatsapp groups.

Participants received a link to a Google Form survey.

## Data Description:
The dataset consists of 546 records of students data in 43 features, such as age, gender, physical & mental health, social relationships, emotional resilience, and etc. The target is "Academic Results" ranging from 1 to 10.

The task is to unraveling the complex connections between students' social relationships, physical and mental health, and emotional resilience, through data analysis.

There are 3 key axes in the dataset:

* Physical & Mental Health
* Social relationships
* Emotional Resilience
## Data Cleaning:
We Performd data cleaning to address any issues or inconsistencies in the dataset. This didn't involve handling missing values because we haven't any optional field in our google form survey but it included dealing with outliers, and correcting data entry errors.
## Data Transformation:
To enhance our analysis, we introduced innovative columns synthesizing existing data. One such column, 'psych_well_being,' combines data from 'burnout' and 'motivation,' offering a more holistic view of subjects' psychological wellness.

Additionally, the 'interaction_term' column resulted from merging 'concentration' and 'team work,' allowing a closer examination of individual focus and collaborative efficiency dynamics. These new columns provide valuable insights into the nuanced interactions between key variables.

To facilitate analysis, we encoded categorical data using the label encoder and employed a mapping function for yes/no questions.




# Insights’ results:
## Introduction:
Data exploration has unveiled intriguing insights, shedding light on pivotal factors influencing the investigated phenomenon. Careful analysis has revealed intricate patterns and relationships, exposing previously undiscovered connections and nuances.##
## 1.General Insights:
![405978889_910731203801427_6641714995836896288_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/c4b82a41-1a0f-
![370100884_2431319860393213_522297059849387177_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/ba582507-c72a-40f4-923d-93a26df44525)
![370231357_365153966193286_7703346626831358151_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/d68268fd-9105-4390-a422-47cb9c80e69d)
![371845492_1375491169733386_1197616633136832011_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/2bec64cb-4c31-4771-b4eb-d89ed91cef1d)
![393161949_1279769942672354_8367903540059012972_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/bbdecf82-da19-4c66-aaba-cddaf38f9a29)
![406178695_385165457196817_616912133851562411_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/c5e9e1fd-aa50-423d-9b66-83bfb0c85b30)
![405558934_1038340367407890_7822053933057003849_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/0cea01ae-36eb-4916-96db-ffcceab00143)
![386848514_905238511157832_6337123672575771130_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/0992a4b4-6ccf-40a9-a404-027e0c4ec64d)
![385544243_888773995772036_8718953656885868127_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/c79322ff-404e-4f78-ac77-eebde119d32c)
![406067991_1514250589488784_7084488286162652356_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/0f9dfac4-2344-491e-bf92-43eb463d828f)
![384554732_3245439375764343_8857606594304978071_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/981173da-c871-4abd-9f6f-6d9bead353a7)



## 2.Specific Insights:

![393092845_1737555993430100_3176606614255505110_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/e8ce241b-7161-45c4-8ea9-3fb15d648297)
![403629101_791371229672400_2705971684903581953_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/b5ac2958-4b42-43e4-a92d-a91e301abac6)
![394076160_365182642672832_2005095655273236981_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/d42787bf-3650-44a0-85ae-30ec74ee34d8)
![403611466_732872781573117_4370932225516009473_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/424d34e2-28a0-4ae9-9c59-d76f2079b263)
![403620005_328438943466555_2457076993207895375_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/9c9cbe02-d4aa-4f54-a2a6-863b210d7645)
![393188186_7278340485523809_4074686483797740092_n](https://github.com/ihebbettaibe/ZERAZER/assets/152183684/bac6259b-6061-4cc5-9feb-4af553cfcb71)
![377149845_880689720104945_7321997319304349567_n](https://github.com/ih




# Solution:
## Introduction: 
The "Study Hub" feature addresses student challenges—burnout, motivation, concentration, and collaborative learning. It supports effective time management, goal setting, and regular breaks to enhance the overall learning experience on educational platforms.
## Description of the features
The "Study Hub" feature enhances the learning environment on educational platforms. Students can study alone or in groups, setting study durations, breaks, and engaging in activities during breaks. Pop-ups ensure connection, and students choose their courses. Group study options include random pairings or choosing acquaintances for synchronized courses, chat, or voice calls. Weekly, students set study goals with progress bars and motivational messages.

# The Study Hub:
## Figma prototype 
### Link :
https://www.figma.com/file/3DPFTenpeIpe5ESiGM3WIa/Untitled?type=design&node-id=0%3A1&mode=design&t=gONfKpVSJk6P00Mm-1

### Screenshots :
![387466463_1593055814795944_6829108503946726984_n](https://github.com/fathi-hamed/SMC-CHALLENGE-IEEE-SUPCOM-SB/assets/138572009/f321385f-25eb-4ab8-be94-845c3583474d)
![377241610_922838522791925_7603780219790794036_n](https://github.com/fathi-hamed/SMC-CHALLENGE-IEEE-SUPCOM-SB/assets/138572009/d1aa8d7a-fe06-4478-b100-ed2f8dccf620)
![387495484_1096689051319808_7127970696305827894_n](https://github.com/fathi-hamed/SMC-CHALLENGE-IEEE-SUPCOM-SB/assets/138572009/06f75b74-2584-4e0d-b94f-46e85c0c545a)
![371069149_899143395119715_1369189332640772060_n](https://github.com/fathi-hamed/SMC-CHALLENGE-IEEE-SUPCOM-SB/assets/138572009/d1d7e5af-c882-449c-b25f-3e452cbc0cdd)
![371517484_1423532711564804_951234786841429645_n](https://github.com/fathi-hamed/SMC-CHALLENGE-IEEE-SUPCOM-SB/assets/138572009/43d00081-5214-4708-bc59-632c42a51e03)
![387508042_6780058568696967_8802605973564677204_n](https://github.com/fathi-hamed/SMC-CHALLENGE-IEEE-SUPCOM-SB/assets/138572009/8f91ec9a-3508-4632-8544-5d999677fbdb)
![385513671_1846324059157363_2398260064427888571_n](https://github.com/fathi-hamed/SMC-CHALLENGE-IEEE-SUPCOM-SB/assets/138572009/b0e0769c-0cfb-4393-a43a-2f029ab3f6ff)
![371533088_738187954410976_4509182988880657210_n](https://github.com/fathi-hamed/SMC-CHALLENGE-IEEE-SUPCOM-SB/assets/138572009/7ac0318d-1e3e-4d65-8f2d-fe00d5992902)
![370248610_284181657459953_8838472550836867597_n](https://github.com/fathi-hamed/SMC-CHALLENGE-IEEE-SUPCOM-SB/assets/138572009/99dc58a8-d72e-4fc2-ac1e-cc8d34540e2a)
![370049185_1303647113641073_6735373581773550990_n](https://github.com/fathi-hamed/SMC-CHALLENGE-IEEE-SUPCOM-SB/assets/138572009/8e78de12-138c-407a-8e66-b3a8051da52f)
![370302173_1015115583110833_1284401823324251876_n](https://github.com/fathi-hamed/SMC-CHALLENGE-IEEE-SUPCOM-SB/assets/138572009/1fda4d2f-54b4-4af2-ba4c-5cb656c46154)

# Video Demo :






