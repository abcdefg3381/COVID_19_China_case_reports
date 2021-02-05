# Repository for a massive COVID-19 epidemiological dataset

## What you are expected to find in our datasets
Chinese prefectural level governments started to report details of confirmed COVID-19 cases online on a daily basis, starting from January 2020. The disclosures may contain the mobility, potential exposure scenario, epidemiological characteristics, and other useful information of individual cases.

We organized a group of content coders since early March 2020, kept monitoring updates from the local health committees (except for the ones in Hubei Province), manually extracted useful information from the public disclosures, and compiled a line-list dataset. The dataset now contains 10,000+ cases and counting.

A detailed data description can be found on [Scientific Data](https://doi.org/10.1038/s41597-021-00844-8).

## Call for help
Fighting COVID-19 is a course for the entire human species. We welcome any form of collaborations with us and reuse of our dataset. We highly encourage interested parties to help examine the data, report errors in our coding, and help us to keep the data updated.

## File usage
The datasets are stored on our [GitHub repository](https://github.com/abcdefg3381/COVID_19_China_case_reports).
* `data_sources.csv`: the URLs to online disclosure venues.

* `dataset EN.csv`: coded information in English.

* `reasons_for_missing_data.csv`: The reasons for missing cases in some prefecturals.

## Data curators
[Prof. Xiao-Ke Xu](http://www.bigdataanalysis.xyz/test/testShow?name=Xiaoke%20Xu), Dalian Minzu University, China

[Prof. Ye Wu](https://sjc.bnu.edu.cn/sztd/jsdw2/js/29551.html), Beijing Normal University, China

[Dr. Xiaofan Liu](http://www.cityu.edu.hk/com/Profile.aspx?u=xliu347), City University of Hong Kong, China

Special thanks to the the research assistants for their relentless efforts!

## Suggested citation
Liu, X.F., Xu, XK. & Wu, Y. Mobility, exposure, and epidemiological timelines of COVID-19 infections in China outside Hubei province. Sci Data 8, 54 (2021). https://doi.org/10.1038/s41597-021-00844-8

## A list of supported publications
The dataset has supported multiple scientific articles since the beginning of the pandemic.

1. Lin Zhang, Jiahua Zhu, Xuyuan Wang, Juan Yang, Xiao Fan Liu* and Xiao-Ke Xu*. Characterizing COVID-19 Transmission: Incubation Period, Reproduction Rate, and Multiple-Generation Spreading. Frontiers in Physics, 2021, 8:589963. [pdf](../main/published_manuscripts/20210111_Characterizing%20COVID-19%20Transmission-Incubation%20Period%2C%20Reproduction%20Rate%2C%20and%20Multiple-Generation%20Spreading.pdf)
1. Xiao-Ke Xu#, Lin Wang#, Sen Pei#*, Multiscale mobility explains differential associations between the gross domestic product and COVID-19 transmission in Chinese cities, Journal of Travel Medicine, 2021, taaa236, https://doi.org/10.1093/jtm/taaa236 [pdf](../main/published_manuscripts/20210104_Multiscale%20mobility%20explains%20differential%20associations%20between%20the%20gross%20domestic%20product%20and%20COVID-19%20transmission%20in%20Chinese%20cities.pdf)
1. Daihai He, Shi Zhao, Xiao-Ke Xu, Qiangying Lin, Zian Zhuang, Peihua Cao, Maggie H. Wang, Yijun Lou, Li Xiao, Ye Wu*, Lin Yang*.Low dispersion in the infectiousness of COVID-19 cases implies difficulty n control, BMC Public Health, 2020, 20: 1558. [pdf](../main/published_manuscripts/20201016_Low%20dispersion%20in%20the%20infectiousness%20of%20COVID-19%20cases%20implies%20difficulty%20in%20control%20.pdf)
1. Zhanwei Du, Xiao-Ke Xu, Lin Wang, Spencer J. Fox, Benjamin J. Cowling, Alison P. Galvani, and Lauren Ancel Meyers*. Effects of proactive social distancing on COVID-19 outbreaks in 58 cities, China. Emerging Infectious Diseases, 2020, 26(9): 2269-2271 [pdf](../main/published_manuscripts/20200910_Effects%20of%20Proactive%20Social%20Distancing%20on%20COVID-19%20Outbreaks%20in%2058%20Cities%2C%20China.pdf)
1. Sheikh Taslim Ali#, Lin Wang#, Eric HY Lau#, Xiao-Ke Xu, Zhanwei Du, Ye Wu, Gabriel M. Leung,  Benjamin J. Cowling*, Evolution of effective serial interval of SARS-CoV-2 by non-pharmaceutical interventions, Science, 2020, 369: 1106-1109 [pdf](../main/published_manuscripts/20200827_Serial%20interval%20of%20SARS-CoV-2%20was%20shortened%20over%20time%20by%20nonpharmaceutical%20interventions.pdf)
1. Xiao-Ke Xu#, Xiao Fan Liu#, Ye Wu#, Sheikh Taslim Ali#, Zhanwei Du#, Paolo Bosetti, Eric H Y Lau, Benjamin J Cowling, Lin Wang*, Reconstruction of Transmission Pairs for novel Coronavirus Disease 2019 (COVID-19) in mainland China: Estimation of Super-spreading Events, Serial Interval, and Hazard of Infection, Clinical Infectious Diseases, 2020, 71(12):3163-3167 [pdf](../main/published_manuscripts/20200618_Reconstruction%20of%20Transmission%20Pairs.pdf)
1. Zhanwei Du#, Xiaoke Xu#, Ye Wu#, Lin Wang, Benjamin J. Cowling, and Lauren Ancel Meyers*, The serial interval of COVID-19 from publicly reported confirmed cases, Emerging Infectious Diseases. 2020, 26(6):1341-1343. [pdf](../main/published_manuscripts/20200615_Serial%20Interval%20of%20COVID-19%20among%20Publicly%20Reported%20Confirmed%20Cases.pdf)
1. Zhanwei Du#, Lin Wang#, Simon Cauchemez, Xiao-Ke Xu, Xianwen Wang, Benjamin J. Cowling, and Lauren Ancel Meyers*, Risk for transportation of 2019 novel coronavirus disease from Wuhan to other cities in China. Emerging Infectious Diseases. 2020, 26(5):1049-1052. [pdf](../main/published_manuscripts/20200225_Risk%20for%20Transportation%20of%202019%20Novel%20Coronavirus%20Disease%20from%20Wuhan%20to%20Other%20Cities%20in%20China.pdf)
1. 王国强, 张烁, 杨俊元*, 许小可*. 耦合不同年龄层接触模式的新冠肺炎传播模型, 物理学报, 2021, 70(1)：010201. [pdf](../main/published_manuscripts/20210115_%E8%80%A6%E5%90%88%E4%B8%8D%E5%90%8C%E5%B9%B4%E9%BE%84%E5%B1%82%E6%8E%A5%E8%A7%A6%E6%A8%A1%E5%BC%8F%E7%9A%84%E6%96%B0%E5%86%A0%E8%82%BA%E7%82%8E%E4%BC%A0%E6%92%AD%E6%A8%A1%E5%9E%8B.pdf)
1. 孙皓宸, 刘肖凡, 许小可*, 吴晔*.  基于连续感染模型的新冠肺炎校园传播与防控策略分析, 物理学报, 2020, 69(24)：240201. [pdf](../main/published_manuscripts/20201220_%E5%9F%BA%E4%BA%8E%E8%BF%9E%E7%BB%AD%E6%84%9F%E6%9F%93%E6%A8%A1%E5%9E%8B%E7%9A%84%E6%96%B0%E5%86%A0%E8%82%BA%E7%82%8E%E6%A0%A1%E5%9B%AD%E4%BC%A0%E6%92%AD%E4%B8%8E%E9%98%B2%E6%8E%A7%E7%AD%96%E7%95%A5%E5%88%86%E6%9E%90.pdf)
1. 刘肖凡*, 吴晔, 许小可.  媒体在流行病爆发事件中的干预作用：基于传染病模型理论和新型冠状病毒疫情案例的分析, 全球传媒学刊, 2020, 7:(01)：4-17 [pdf](../main/published_manuscripts/20200331_%E5%AA%92%E4%BD%93%E5%9C%A8%E6%B5%81%E8%A1%8C%E7%97%85%E7%88%86%E5%8F%91%E4%BA%8B%E4%BB%B6%E4%B8%AD%E7%9A%84%E5%B9%B2%E9%A2%84%E4%BD%9C%E7%94%A8_%E5%88%98%E8%82%96%E5%87%A1.pdf)
1. 曹文静, 刘小菲, 韩卓, 冯鑫*, 张琳*, 刘肖凡, 许小可, 吴晔. 新冠肺炎疫情确诊病例的统计分析及自回归建模, 物理学报, 2020, 69(9): 090203 [pdf](../main/published_manuscripts/20200430_%E6%96%B0%E5%9E%8B%E5%86%A0%E7%8A%B6%E7%97%85%E6%AF%92%E8%82%BA%E7%82%8E%E7%96%AB%E6%83%85%E7%A1%AE%E8%AF%8A%E7%97%85%E4%BE%8B%E7%9A%84%E7%BB%9F%E8%AE%A1%E5%88%86%E6%9E%90%E5%8F%8A%E8%87%AA%E5%9B%9E%E5%BD%92%E5%BB%BA%E6%A8%A1.pdf)
1. 许小可, 文成, 张光耀, 孙皓宸, 刘波, 王贤文*.  新冠肺炎爆发前期武汉外流人口的地理去向分布及影响, 电子科技大学学报, 2020, 49(3): 324-329 [pdf](../main/published_manuscripts/20200203_%E6%96%B0%E5%86%A0%E8%82%BA%E7%82%8E%E7%88%86%E5%8F%91%E5%89%8D%E6%9C%9F%E6%AD%A6%E6%B1%89%E5%A4%96%E6%B5%81%E4%BA%BA%E5%8F%A3%E7%9A%84%E5%9C%B0%E7%90%86%E5%8E%BB%E5%90%91%E5%88%86%E5%B8%83%E5%8F%8A%E5%BD%B1%E5%93%8D_%E8%AE%B8%E5%B0%8F%E5%8F%AF.pdf)
1. 孙皓宸, 徐铭达, 许小可*.  基于真实人际接触数据的新冠肺炎校园传播与防控, 电子科技大学学报, 49(3)：399-407 [pdf](../main/published_manuscripts/20200422_%E5%9F%BA%E4%BA%8E%E7%9C%9F%E5%AE%9E%E4%BA%BA%E9%99%85%E6%8E%A5%E8%A7%A6%E6%95%B0%E6%8D%AE%E7%9A%84%E6%96%B0%E5%86%A0%E8%82%BA%E7%82%8E%E6%A0%A1%E5%9B%AD%E4%BC%A0%E6%92%AD%E4%B8%8E%E9%98%B2%E6%8E%A7.pdf)

#: equally contributed, *: corresponding

## License
This project is licensed under the terms of the Creative Commons Attribution 4.0 International (CC BY 4.0) license. View [license deed](https://creativecommons.org/licenses/by/4.0/deed.en) and [legal code](https://creativecommons.org/licenses/by/4.0/legalcode).
