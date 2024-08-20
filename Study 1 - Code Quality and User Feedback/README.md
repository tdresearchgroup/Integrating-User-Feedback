### This repository contains all of the data and artifacts of our study. It also contains supplementary images for our statistical analysis.

#### The repository is structured as follows:
```
REPLICATION PACKAGE
│
│   
├───Data    
|   |   APPLICATIONS.XLSX                       (The metadata collected for all the applications after the exclusion & inclusion criteria)
|   |   REVIEWS                                 (The reviews collected for the 9 applications analyzed)
|   |
│   ├───Complied Data                           (The data used in our analysis, code quality metrics measured, and app reviews artifacts for each application)
│   │       audio_recorder_data.xlsx
│   │       battery_indicator_data.xlsx
│   │       slide_data.xlsx
│   │       hackers_keyboard_data.xlsx
│   │       chess_data.xlsx
│   │       ministock_Data.xlsx
│   │       dailydozen_Data.xlsx
│   │       wifi_auto_data.xlsx
│   │       unit_converter_data.xlsx
│   │       
│   |───Individual Smells                       (The code smells present in each version of each application)
│   |        all_smells_hackerskeyboard.xlsx
│   |        all_smells_UnitConverterUltimate.xlsx
│   |        all_smells_ministocks.xlsx
│   |        all_smells_Battery-Indicator-Free.xlsx
│   |        all_smells_AudioRecorder.xlsx
│   |        all_smells_android-chess.xlsx
│   |        all_smells_Daily_dozen.xlsx
│   |        all_smells_wifi_auto_off.xlsx
│   |        all_smells_slide.xlsx
|   |
│   ├───Correlations                            (Spearman's correlation and p-value for each RQ)
│   │   │   RQ3 (Review Type).xlsx
│   │   │   RQ1_RQ2 (Rating+Sentiment+Toxicity).xlsx
│   │   │   
│   │   └───Individual Smells Correlation       (Spearman's correlation and p-value between individual code smells and app reviews artifacts)
│   │           PDs.xlsx
│   │           Rating.xlsx
│   │           Toxicity.xlsx
│   │           FRs.xlsx
│   │           Sentiment.xlsx           
│           
├───Images                                      (Visualization of the correlation between individual code smells and app reviews artifacts)
│       Rating Smells Corr.png
│       FR Smells Corr.png
│       PD Smells Corr.png
│       Toxicity Smells Corr.png
│       Sentiment Smells Corr.png
│       
└───Scripts (The scripts used in our study)
        COLLECT_REVIEWS.ipynb
        EXTRACT_APPS_METADATA.ipynb
        
```