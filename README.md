# Branch Predictor TAGE

This project was done as part of CSCE 614 Computer Architecture course project.

The Tagged Geometric Branch Predictor (TAGE) provides state-of-the-art predictive accuracy for conditional branches, with equivalent storage budget outperforming all other predictors showcased at the Championship Branch Prediction in December 2004. It is one of the most commonly used branch predictor(BP), employing Geometric History Length similar to the O-GEHL predictor where history lengths are increased in Geometric series. This approach enhances prediction accuracy, as different branches often require varying history lengths. Additionally, it utilizes partially tagged components, similar to a PPM-like predictor. TAGE selects the most suitable partially tagged entry using a confidence counter known as usefulness, effectively mitigating aliasing issues.

## References
#### [1] SEZNEC, A. The o-gehl branch predictor.
#### [2] SEZNEC, A. A new case for the tage branch predictor. MICRO 2011 : The 44th Annual IEEE/ACM International Symposium on Microarchitecture (2011).
#### [3] MICHAUD, P. A ppm-like, tag-based branch predictor. The Journal of Instruction-Level Parallelism (2005), pp.10.
#### [4] MIFTAKHUTDINOV, R. Why tage is the best (website).
#### [5] SCHLAIS, D. J., AND LIPASTI, M. H. Badgr: A practical ghr implementation for tage branch predictors. 2016 IEEE 34th International Conference on Computer Design (ICCD) (2016), 536–543.
#### [6] GOBER, N., CHACON, G., WANG, L., GRATZ, P. V., JIMENEZ, D. A., TERAN, E., PUGSLEY, S., AND KIM, J. The Championship Simulator: Architectural Simulation for Education and Competition.
