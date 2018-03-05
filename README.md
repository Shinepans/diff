Reviewer: 1
Comments to the Author
The paper presents a multi-threshold segmentation problem for cement scanning electron microscope (SEM) images, and uses a fireworks algorithm to find optimal solution for the problem.
The topic fits the scope of the journal well, the idea behind the proposed approach is reasonable, the experiments are appropriately-designed, and the paper writing is generally clear.
The mathematical presentations can be improved. Currently they might hinder the understanding of the proposed approach.
In the text behind Eq. (6), please give the range of quantifier \max. The same applies to the \min in the text behind Eq. (8).
Eq. (4), what is the meaning of superscript c, as you later explain that c is the number of sparks?
Eq. (10), a box appears after R_a.
Eq. (12), you use \sum{b=1}^c in the numerator but use \sum{b\in c} in the denominator.
Please be consistent in using italic fonts for mathematical variables in both the equations and the main text
The literature review can be improved. Some suggested related work on fireworks algorithms:
[1] Parametric optimization of ultrasonic machining process using gravitational search and fireworks algorithms. https://doi.org/10.1016/j.asej.2014.10.009
[2] Multiobjective fireworks optimization for variable-rate fertilization in oil crop production. https://doi.org/10.1016/j.asoc.2013.07.004
[3] A hybrid fireworks optimization method with differential evolution operators. https://doi.org/10.1016/j.neucom.2012.08.075
Reviewer: 2
Comments to the Author
This paper concerns the use of an Otsu based method to segment phases in images of cement-based materials obtained from SEM. The authors applied this method onto 5 images of cement (shown in Fig 3) and compared the results with several classical algorithm that apparently show “similar” results on visual comparison. They argued that the proposed method is more “efficient” and “stable” but provided no evidence on this. Another flaw with the work is lack of validation of the proposed method. How do we know that the segmentation gave accurate results beyond a simple visual comparison? 
The authors went on great lengths to describe the importance of calcium silicate hydrates (C-S-H) and research challenges in the first three pages. However, their method was tested on images of cement (Fig. 3) rather than C-S-H as far as I can see. It is also not clear to me why the authors tested their method on images collected on rough or fractured surfaces rather on polished surfaces. Normally, segmentation is carried out to facilitate quantitative image analysis. This requires images obtained on cross-sections / flat surfaces so that stereological rules can apply to carry out phase analysis. 
Unfortunately, the paper is poorly written and presented. Many studies already exist on segmentation of cement-based materials. The Otsu segmentation is a well-known method. Therefore, it is not clear to me what the main problem that the research is trying to solve. It is also unclear to me what is new and significant that has arisen from the work.
Editorial comments:
Although the second report does not accept this manuscript, it has many positive suggestions that the authors should actually go through these suggestions carefully and make suitable changes. You are given an opportunity to revise the paper and we look forward to receive a revised version addressing all the concerns above.
