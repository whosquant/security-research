# security-research
海通研报付现，债券因子研究（research on bond's factor）
This project is the realization of the research report of Haitong Securities, and the idea comes from practice. At the same time, it is also the examination of the content of the research report. The final research results are basically consistent with those in the research report.
## 
This project is a personal hobby for sharing and is prohibited for any academic use.

### research background
In recent years, with the in-depth research of investors on the stock selection system, the treatment of stock selection factor value is also gradually refined. This paper mainly discusses the orthogonality of dry stock selection factors. The reason why we discuss the orthogonality of factors is that in the traditional multi-factor model, there is often a certain degree of correlation between the selected factors, and this correlation will complicate the allocation of factor weights. For a multi-factor model with equal weight allocation of factor weights, the model may actually have a higher exposure to a factor (e.g., market value factor) due to the existence of correlation between factors. For weighted optimized models, the influence of correlation may be greater. Therefore, this project considered eliminating the dry correlation during the construction of factors to achieve a more controlled exposure to factors.


#### research intention
This paper is divided into three parts. The first part explains the necessity of factor orthogonality and the related processing methods in the process of orthogonality. The second part compares the historical performance of the orthogonal multifactor model with the original multifactor model. The third part discusses the determination of orthogonal order.
