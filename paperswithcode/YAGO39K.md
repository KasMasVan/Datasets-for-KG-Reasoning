# source
[Differentiating Concepts and Instances for Knowledge Graph Embedding](Differentiating Concepts and Instances for Knowledge Graph Embedding)
# description
>We construct a subset of YAGO named
>YAGO39K for evaluation through the following
>steps:
>(1) We randomly select some relational triples
>like (h, r, t) from the whole YAGO dataset as our
>relational triple set Sl
>.
>(2) For every instance and instance relation existed in our relational triples, we save it to construct >instance set I and instance relation set Rl
>respectively.
>(3) For every instanceOf triple (i, re, c) in
>YAGO, if i ∈ I, we save this triple to construct
>instanceOf triple set Se.
>(4) For every concept existed in instanceOf
>triple set Se, we save it to construct concept set C.
>(5) For every subClassOf triple (ci
>, rc, cj ) in
>YAGO, if ci ∈ C ∧ cj ∈ C, we save this triple to
>construct subClassOf triple set Sc.
>(6) Finally, we achieve our triple set S = Se ∪
>Sc ∪ Sl and our relation set R = {re, rc} ∪ Rl.
# statistics
![image](https://user-images.githubusercontent.com/51369075/96973528-95cdfc80-154a-11eb-97e1-64115d18706f.png)
# example

# referenced by
[Probability Calibration for Knowledge Graph Embedding Models](https://openreview.net/pdf?id=S1g8K1BFwS)
