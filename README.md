MetaGeneConsensus
===========
Gene prediction is an important approach in analyzing metagenomic sequence data. There has been many gene prediction tools developed for metagenomic sequences. MetaGeneConsensus provides a software integration platform and as a foundation for software development of consensus based on multiple gene prediction tools.

Usage
-----

        Version 1.0
        Usage: ./mgc <command>

Command:

       FragGeneScan        --Show the help of FragGeneScan
       Prodigal            --Show the help of Prodigal
       MetaGeneAnnotator   --Show the help of MetaGeneAnnotator
       Orphelia            --Show the help of Orphelia
       Glimmer3            --Show the help of Glimmer3
       GeneMarkS-2         --Show the help of GeneMarkS-2
       frame               --Show the help of how to transform the ORFs into unified coordinates style
       protein             --Show the help of how to generate protein sequences according to ORFs
       cd-hit              --Show the help of cd-hit
       validate            --Identify whether a gene is true or false and give statistical results
       consensus           --Show the help of consensus algorithm for gene prediction 

System Requirements
-------

Environment configuration:

     x86_64-linux (Run "uname -a" to check.)
     gcc (GCC) 4.8+ (Run "gcc --version" to check.)
     perl 5.24+ (Run "perl --version" to check.)


Statement
---------
The tools used in the packages/ directroy are all copied from the following links. Please add all the bottom references of this README.md file when you using this perl module. Make sure you have installed the following tools before you install or get them from packages/ directroy.

  1. FragGeneScan: <https://github.com/COL-IU/FragGeneScan>
  2. Prodigal: <https://github.com/hyattpd/prodigal>
  3. MetaGeneAnnotator: <http://metagene.cb.k.u-tokyo.ac.jp/metagene/download_mga.html>
  4. Orphelia: <http://orphelia.gobics.de/>
  5. Glimmer3: <http://ccb.jhu.edu/software/glimmer/index.shtml>
  6. GeneMarkS-2: <http://exon.gatech.edu/GeneMark/>
  7. CD-HIT: <https://github.com/weizhongli/cdhit/releases>

Installation
--------

Clone the gclust repos, and build the `gclust` binary:

     git clone https://github.com/niu-lab/MetaGeneConsensus
     cd MetaGeneConsensus

To install this module, run the following commands:

        cd MetaGeneConsensus
        perl Makefile.PL
        make
        make test
        make install 

Support
--------
For user support please email lirl@sccas.cn

Citation
--------
LI Ruilin, SHANG Qiuming, HAN Xinyin, ZHANG Yu, ZHU Haidong, LI Weizhong, NIU Beifang*. Benchmarking of Gene Prediction Software for Metagenomic Long Fragments. Journal of Computer Applications (In Chinese), 2018 (Retirement)

References
--------
    [1] Rho M, Tang H, Ye Y. FragGeneScan: predicting genes in short and error-prone reads. Springer US, 2015.
    [2] Hyatt D, Chen G, LoCascio PF, et al. Prodigal: prokaryotic gene recognition and translation initiation site identification. BMC Bioinformatics 2010;11:119.
    [3] Noguchi H, Taniguchi T,Itoh T. MetaGeneAnnotator: Detecting Species-Specific Patterns of Ribosomal Binding Site for Precise Gene Prediction in Anonymous Prokaryotic and Phage Genomes. DNA Research,15,6(2008-10-21) 2008;15:387-96.
    [4] Hoff KJ, Lingner T, Meinicke P, et al. Orphelia: predicting genes in metagenomic sequencing reads. Nucleic Acids Research 2009;37:101-5.
    [5] Delcher AL, Bratke KA, Powers EC, et al. Identifying bacterial genes and endosymbiont DNA with Glimmer. Bioinformatics 2007;23:673.
    [6] Lomsadze A, Gemayel K, Tang S, Borodovsky M. Modeling leaderless transcription and atypical genes results in more accurate gene prediction in prokaryotes. Genome Research 2018;28:1079.
    [7] FU L, NIU B, ZHU Z, , et al. CD-HIT: accelerated for clustering the next-generation sequencing data. Bioinformatics 2012;28:3150-2.
LICENSE AND COPYRIGHT

Copyright (C) 2018 Ruilin Li et al.

This program is free software; you can redistribute it and/or modify it
under the terms of the the Artistic License (2.0). You may obtain a
copy of the full license at:

L<http://www.perlfoundation.org/artistic_license_2_0>

Any use, modification, and distribution of the Standard or Modified
Versions is governed by this Artistic License. By using, modifying or
distributing the Package, you accept this license. Do not use, modify,
or distribute the Package, if you do not accept this license.

If your Modified Version has been derived from a Modified Version made
by someone other than you, you are nevertheless required to ensure that
your Modified Version complies with the requirements of this license.

This license does not grant you the right to use any trademark, service
mark, tradename, or logo of the Copyright Holder.

This license includes the non-exclusive, worldwide, free-of-charge
patent license to make, have made, use, offer to sell, sell, import and
otherwise transfer the Package with respect to any patent claims
licensable by the Copyright Holder that are necessarily infringed by the
Package. If you institute patent litigation (including a cross-claim or
counterclaim) against any party alleging that the Package constitutes
direct or contributory patent infringement, then this Artistic License
to you shall terminate on the date that such litigation is filed.

Disclaimer of Warranty: THE PACKAGE IS PROVIDED BY THE COPYRIGHT HOLDER
AND CONTRIBUTORS "AS IS' AND WITHOUT ANY EXPRESS OR IMPLIED WARRANTIES.
THE IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR
PURPOSE, OR NON-INFRINGEMENT ARE DISCLAIMED TO THE EXTENT PERMITTED BY
YOUR LOCAL LAW. UNLESS REQUIRED BY LAW, NO COPYRIGHT HOLDER OR
CONTRIBUTOR WILL BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, OR
CONSEQUENTIAL DAMAGES ARISING IN ANY WAY OUT OF THE USE OF THE PACKAGE,
EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

