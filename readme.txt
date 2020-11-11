Package: RAIMC
Type: Package
Title: Prediction of RNA-binding protein and alternative splicing event associations during epithelial-mesenchymal transition based on inductive matrix completion
Version: 1.0
Author: Yushan Qiu <yushan.qiu@szu.edu.cn>
Maintainer: Quan Zou <zouquan@nclab.net>
Description: This pakege implemented the RAIMC algorithm that applying a inductive matrix completion algorithm, which aims to complete missing or unknown RBP-AS event associations based on known associations and on integrated RBP and AS event similarities.
        
Depends:
    MATLAB (>= 2012a)
License: All source code is copyright, under the Artistic-2.0 License.
		For more information on Artistic-2.0 License see [http://opensource.org/licenses/Artistic-2.0](http://opensource.org/licenses/Artistic-2.0)
		
To operate:
	* for the example of IsoFun:
		we have provided some pre-data for RAIMC, if you want to run RAIMC framwork, please run the script "RAIMC_demo" directly.      
    		
	**  All data loading processes are included in "RAIMC_demo" script

Files:

RAIMC_demo.m: RAIMC running code.

combine_kernels.m: integrating different simialrity matrices into integrated new one.

FKL_weights.m: assigning different wrights to similarity matrices.

kernel_gip.m: generating the GIP similarity matrix for RBPs and AS events.

LapIMC.m: denoising the integrated similarity matrix and utilizing inductive matrix completion for the known RBP-AS associations and RBP¡¢AS event similarity matrix.




 - If you have any problem, please contact Yushan Qiu (yushan.qiu@szu.edu.cn) and Quan Zou (zouquan@nclab.net)!