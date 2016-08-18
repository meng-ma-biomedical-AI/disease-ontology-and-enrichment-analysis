DOSE: Disease Ontology Semantic and Enrichment analysis
=======================================================

[![platform](http://www.bioconductor.org/shields/availability/devel/DOSE.svg)](https://www.bioconductor.org/packages/devel/bioc/html/DOSE.html#archives) [![Build Status](http://www.bioconductor.org/shields/build/devel/bioc/DOSE.svg)](https://bioconductor.org/checkResults/devel/bioc-LATEST/DOSE/) [![Linux/Mac Travis Build Status](https://img.shields.io/travis/GuangchuangYu/DOSE/master.svg?label=Mac%20OSX%20%26%20Linux)](https://travis-ci.org/GuangchuangYu/DOSE) [![AppVeyor Build Status](https://img.shields.io/appveyor/ci/Guangchuangyu/DOSE/master.svg?label=Windows)](https://ci.appveyor.com/project/GuangchuangYu/DOSE) [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-green.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-dose/README.html)

[![Project Status: Active - The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active) [![codecov](https://codecov.io/gh/GuangchuangYu/DOSE/branch/master/graph/badge.svg)](https://codecov.io/gh/GuangchuangYu/DOSE/) [![Last-changedate](https://img.shields.io/badge/last%20change-2016--08--18-green.svg)](https://github.com/GuangchuangYu/DOSE/commits/master) [![commit](http://www.bioconductor.org/shields/commits/bioc/DOSE.svg)](https://www.bioconductor.org/packages/devel/bioc/html/DOSE.html#svn_source) [![GitHub forks](https://img.shields.io/github/forks/GuangchuangYu/DOSE.svg)](https://github.com/GuangchuangYu/DOSE/network) [![GitHub stars](https://img.shields.io/github/stars/GuangchuangYu/DOSE.svg)](https://github.com/GuangchuangYu/DOSE/stargazers)

[![releaseVersion](https://img.shields.io/badge/release%20version-2.10.7-green.svg?style=flat)](https://bioconductor.org/packages/DOSE) [![develVersion](https://img.shields.io/badge/devel%20version-2.11.9-green.svg?style=flat)](https://github.com/GuangchuangYu/DOSE) [![Bioc](http://www.bioconductor.org/shields/years-in-bioc/DOSE.svg)](https://www.bioconductor.org/packages/devel/bioc/html/DOSE.html#since) [![post](http://www.bioconductor.org/shields/posts/DOSE.svg)](https://support.bioconductor.org/t/DOSE/) [![download](http://www.bioconductor.org/shields/downloads/DOSE.svg)](https://bioconductor.org/packages/stats/bioc/DOSE/)

This package implements five methods proposed by *Resnik*, *Schlicker*, *Jiang*, *Lin* and *Wang* respectively for measuring semantic similarities among DO terms and gene products. Enrichment analyses including hypergeometric model and gene set enrichment analysis are also implemented for discovering disease associations of high-throughput biological data.

[![Twitter](https://img.shields.io/twitter/url/https/github.com/GuangchuangYu/DOSE.svg?style=social)](https://twitter.com/intent/tweet?hashtags=DOSE&url=https://guangchuangyu.github.io/DOSE)

------------------------------------------------------------------------

Please cite the following article when using `DOSE`:

***G Yu***, LG Wang, GR Yan, QY He. DOSE: an R/Bioconductor package for Disease Ontology Semantic and Enrichment analysis. ***Bioinformatics*** 2015, 31(4):608-609.

[![doi](https://img.shields.io/badge/doi-10.1093/bioinformatics/btu684-green.svg?style=flat)](http://dx.doi.org/10.1093/bioinformatics/btu684) [![citation](https://img.shields.io/badge/cited%20by-18-green.svg?style=flat)](https://scholar.google.com.hk/scholar?oi=bibs&hl=en&cites=16627502277303919270)

------------------------------------------------------------------------

For details, please visit our project website, <https://guangchuangyu.github.io/DOSE>.

-   [Documentation](https://guangchuangyu.github.io/DOSE/documentation/)
-   [Featured Articles](https://guangchuangyu.github.io/DOSE/featuredArticles/)
-   [Feedback](https://guangchuangyu.github.io/DOSE/#feedback)

### Citation

[![citation](https://img.shields.io/badge/cited%20by-18-green.svg?style=flat)](https://scholar.google.com.hk/scholar?oi=bibs&hl=en&cites=16627502277303919270)

       +-+---------+---------+---------+---------+---------+---+
    12 +                                                       +
       |                                                       |
       |                                                       |
       |                                                       |
    10 +                                                       +
       |                                                       |
       | *                                                 *   |
     8 +                                                       +
       |                                                       |
       |                                                       |
       |                                                       |
     6 +                                                       +
       +-+---------+---------+---------+---------+---------+---+
       2015     2015.2    2015.4    2015.6    2015.8     2016   

### Download stats

[![download](http://www.bioconductor.org/shields/downloads/DOSE.svg)](https://bioconductor.org/packages/stats/bioc/DOSE/) [![total](https://img.shields.io/badge/downloads-43109/total-blue.svg?style=flat)](https://bioconductor.org/packages/stats/bioc/DOSE/) [![month](https://img.shields.io/badge/downloads-2353/month-blue.svg?style=flat)](https://bioconductor.org/packages/stats/bioc/DOSE/)

         +------------+---------------+----------------+---------------+----------------+--------------+
         |                                                                                     *  *    |
         |                                                                                             |
         |                                                                                      *      |
    2000 +                                                                                   *         +
         |                                                                                             |
         |                                                                                             |
         |                                                                                             |
         |                                                                                             |
    1500 +                                                                                  *          +
         |                                                                               *             |
         |                                                                       *  *** *              |
         |                                                                        *        *           |
    1000 +                                                                   *  *                      +
         |                                                                 *  *                        |
         |                                                        ** **  **                            |
         |                                                  * ***                                      |
         |                                   **     ** *   *           *                               |
     500 +                 *              * *    * *    *                                              +
         |                * *      * *   *      *        *                                             |
         |              *     ** **   * *                                                              |
         |          * **                                                                               |
       0 +   * *** *                                                                                   +
         +------------+---------------+----------------+---------------+----------------+--------------+
                    2012            2013             2014            2015             2016
