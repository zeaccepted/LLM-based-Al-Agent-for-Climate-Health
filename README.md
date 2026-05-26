# LLM-based AI multi-agent framework for climate–health literature analysis

This repository contains the code used for "Automated Analysis Framework for Multilingual Climate-Health Literature Based on Multi-Agent Large Language Model"


## 📖 Introduction
Climate-related health risks are rising rapidly in cities, yet it remains unclear whether scientific research reflects the geography and mechanisms of these emerging risks. Here we systematically map city-level climate–health research in China using a large language model–based framework applied to both Chinese- and English-language publications from 1993–2023. We identify 2,902 studies, including 1,151 city-level analyses covering 2,012 mentions of 408 unique cities in the articles. Research attention is highly concentrated in a small number of metropolitan areas, with strong geographic inequality in research exposure. Across 408 cities, the growth of climate-related health risks is negatively correlated with research attention (r = −0.329), indicating a mismatch between emerging risks and the distribution of scientific evidence. The literature also focuses predominantly on exposure–disease relationships, while vulnerability, socioeconomic determinants, and system-level responses remain underexplored. These findings highlight structural gaps in the climate–health evidence base and underscore the need for geographically balanced and mechanism-oriented research to support urban climate adaptation.

<img width="970" height="529" alt="image" src="https://github.com/user-attachments/assets/62395f2a-3464-4dad-8943-2b5f738b4158" />


### Prerequisites
- Python 3.8+
- PyTorch 1.12+

## 📁 Dataset
A systematic literature search was conducted to identify studies examining climate–health relationships in China. Publications were retrieved from both international and Chinese academic databases, including OpenAlex, China National Knowledge Infrastructure (CNKI), and Baidu Scholar. The search covered publications from 1993 to 2023.
Search queries combined climate-related and health-related keywords in both English and Chinese. Climate-related keywords included terms such as climate change, global warming, extreme weather, heatwave, drought, flood, tropical cyclone, and related expressions. Health-related keywords included health, mortality, morbidity, infectious disease, respiratory disease, cardiovascular disease, mental health, and related outcomes. The full keyword lists are provided in Supplementary Tables S1 and S2.
Searches were conducted within the title, abstract, and keyword fields. To ensure minimum publication quality, only articles published in journals indexed in SCI, EI, China technology journals, core journals of Peking University, CSCD index journals, CSSCI were included.
The initial search returned 62,440 publications. After screening and deduplication, 32,642 studies were retained for analysis.


## 🏃‍♂️ Training and Evaluation
commit soon...

## 📜 Citation


## 📧 Contact
For any questions or suggestions, please contact [Yuze Sun] at [syz23@mails.tsinghua.edu.cn] or open an issue on GitHub.

## 📄 License
This project is licensed under the MIT License.
