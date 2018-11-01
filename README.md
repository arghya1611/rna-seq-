# Differential expression analysis with edgeR
#Contributed by jdblischak @ GitGists

This is a tutorial I have presented for the class Genomics and Systems Biology at the University of Chicago.
In this course the students learn about study design, normalization, and statistical testing for genomic studies.
This is meant to introduce them to how these ideas are implemented in practice.
The specific example is a differential expression analysis with edgeR starting with a table of counts and ending with a list of differentially expressed genes.

Past versions:

*  [Tuesday, April 26, 2016](https://gist.github.com/jdblischak/11384914/a4b57e05fd77a3cd1012977662d7b0b31158dc8f)
*  [Tuesday, April 21, 2015](https://gist.github.com/jdblischak/11384914/fd4563da540b02852808cb59c3c95024dc358f36)
*  [Tuesday, April 29, 2014](https://gist.github.com/jdblischak/11384914/9e6363755a0760f307b5011b66022675fd73afa2)

For all the example code to work, you will need to install an R version greater than 3.0.

**License:** This lesson is available under the [CC-BY license][cc-by] ([legalcode][cc-by-legalcode]).
Essentially you can do whatever you want with it (teach it verbatim or a modified version) as long as you attribute me as the original source and provide a link to this Gist.

[cc-by]: https://creativecommons.org/licenses/by/2.0/
[cc-by-legalcode]: https://creativecommons.org/licenses/by/2.0/legalcode
