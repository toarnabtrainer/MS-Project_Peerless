# MS-Project_Peerless

**GitHub Link:** https://github.com/toarnabtrainer/MS-Project_Peerless<br>
**or** https://tinyurl.com/54jum4xy

**PERT - Program Evaluation Review Technique**<br>
**Three-point analysis:**<br>
* **Most Likely Estimate (M)** = Estimate of the most likely value of the duration <br>
* **Optimistic Estimate (O)** = Estimate of the duration under the most favourable conditions <br>
* **Pessimistic Estimate (P)** = Estimate of the duration under the most unfavourable conditions <br>

**PERT = (P + O + 4M) / 6**<br>
**Standard Deviation = (P - O) / 6**<br>
**Variance = Standard Deviation ^ 2**<br>

**Note on BCWS, BCWP and EVM Variables available in this link:**<br>
https://acqnotes.com/acqnote/tasks/budgeted-cost-of-work-scheduled#:~:text=BCWS%20%3D%20Budgeted%20Cost%20of%20Work,Actual%20Cost%20of%20Work%20Performed <br>
and<br>
https://www.pinnaclemanagement.com/blog/earned-value-management-an-introduction#:~:text=Earned%20Value%20Management%20(EVM)%20is,extent%2C%20schedule)%20at%20completion.

* **Project 2021 Beginner Tutorial (2 Hours 27 Minutes):** https://www.youtube.com/watch?v=l3ypMRwW9tc
* **Project 2021 Advanced Tutorial (3 Hours 11 inutes):** https://www.youtube.com/watch?v=NnVLgvvkBo8
* **Project 2019 Advanced Tutorial (2 Hours 10 inutes):** https://www.youtube.com/watch?v=xc38Om2HtBA
* **MS-Project 2016 Step by Step Tutorial PDF:** https://tinyurl.com/bdfauhz8
* **MS-Project TutorialsPoint Tutorial PDF:** https://tinyurl.com/5zm6np2t

**PERT Calculations in MS-Project:**
Based on the problem given in the file "Introduction to Project Management.pptx"
* My_O (Number1) Put values in the column manually.<br>
* My_M (Number2) Put values in the column manually.<br>
* My_P (Number3) Put values in the column manually.<br>
* My_PERT (Number4) => ([Number1]+4*[Number2]+[Number3])/6<br>
* My_PERT_Round (Number5) => IIf([Number4]-<br>
Int([Number4])>=0.5,Int([Number4])+1,Int([Number4]))<br>
* My_PERT_Ceil (Number6) => IIf([Number4]-Int([Number4])>0,Int([Number4])+1,Int([Number4]))<br>
* My_PERT_Floor (Number7) => Int([Number4])<br>
* My_PERT_Variance (Number8) => (([Number3]-[Number1])/6)^2<br>
* My_PERT_StdDev (Number9) => Sqr([Number8])<br>

**MS-Office/O365 Reference Tutorial Links -**<br>
* **MS-Office 2007:** https://edu.gcfglobal.org/en/topics/office2007/
* **MS-Office 2010:** https://edu.gcfglobal.org/en/topics/office2010/
* **MS-Office 2013:** https://edu.gcfglobal.org/en/topics/office2013/
* **MS-Office 2016:** https://edu.gcfglobal.org/en/topics/office2016/
* **MS-Excel Formulas:** https://edu.gcfglobal.org/en/excelformulas/
* **50 Tips to Master Excel ebook:** https://drive.google.com/file/d/0ByEvd0vhZtF3Zm9tY09YNWpuUnM/view
* **How to remove password from an Excel Worksheet:** https://www.youtube.com/watch?v=fsVb6id97_E&list=PLmkaw6oRnRv9uEamCt-PXS-bP-rmoxcLc&index=3
* **MS-Excel Cheat Sheet:**	https://drive.google.com/file/d/1dGDoOiIhFFD71FxUxMO-ZYYE2UYLNGhR/view?usp=sharing
