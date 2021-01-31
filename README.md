# CVPR/ICCV Template

This is a new Latex template for IEEE CVPR/ICCV submission, rebuttal, and final version. The last version of CVPR/ICCV latex template has been developed by Paolo.Ienne@di.epfl.ch and awf@acm.org about 15 years ago. The previous version suffer from several issues:

* Authors needs several individual files: cvpr.sty, cvpr_eso.sty, eso-pic.sty.
* For CVPR/ICCV rebuttal another verison of cvpr.cls is required.
* Several warnings exists due to depreiciated options.

This style file is intended to be used as a single style file that could help to build review, rebuttal and final files with a single style file, simply by using one of the following commands:

```Tex
\documentclass[review]{cvpr}
%\documentclass[rebuttal]{cvpr}
%\documentclass[final]{cvpr}

\def\cvprPaperID{****} % *** Enter the CVPR/ICCV Paper ID here
\def\confName{ICCV}
\def\confYear{2021}

```

For an online preview, please refer to the overleaf project: https://www.overleaf.com/read/zygbpnbccrmr If you find any bug or have any further suggestions, please contact Ming-Ming Cheng by email cmm_spam@nankai.edu.cn or leave an issue on https://github.com/MCG-NKU/CVPR_Template

# Acknowledge
This template is modified by Ming-Ming Cheng from Nankai University. This version is modified from the the old cvpr template files contributed by Paolo.Ienne@di.epfl.ch and awf@acm.org. 


