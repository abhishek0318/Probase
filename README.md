# Probase

Implementation of Iterative Extraction method in "Probase: A Probabilistic Taxonomy for Text Understanding" ([Wu et al., 2012](https://www.microsoft.com/en-us/research/wp-content/uploads/2012/05/paper.pdf))

# Usage
````
usage: main.py [-h] [--epsilon EPSILON]
               [--threshold_super_concept THRESHOLD_SUPER_CONCEPT]
               [--threshold_k THRESHOLD_K]
               corpus_file output_file

Generate probase

positional arguments:
  corpus_file           Path to corpus
  output_file           Path to ouput file

optional arguments:
  -h, --help            show this help message and exit
  --epsilon EPSILON     Eplison
  --threshold_super_concept THRESHOLD_SUPER_CONCEPT
                        Threshold (super-concept)
  --threshold_k THRESHOLD_K
                        Threshold (k)
````                        

# Output

Superconcept followed by subconcept, followed by their appearance count in the corpus.

```
animal cat 100
animal dog 200
mammal cat 50
mammal dog 70
```

# Authors
* [Abhinav Gupta](https://github.com/abhigupta768)
* [Abhishek Sharma](https://github.com/abhishek0318)
