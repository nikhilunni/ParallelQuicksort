OpenMP implementation of a parallel quicksort.
It pretty reliably outperforms std::sort on most modern architectures.
It can sort any vector of a generic class that has a < comparator (as in it's templatized).