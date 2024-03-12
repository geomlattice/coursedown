# Evolutionary Biology Problem Set 3

## Problem 1

Sometimes we would like to learn about the recent evolutionary history of a population, for example, that of humans. Coalescent theory provides a powerful toolkit for finding signatures of recent evolutionary events (e.g., population expansion or contraction; natural selection) in the standing genetic variation of a present-day population. We explore the intuition of some of this below. We will use the term nucleotide variant to refer to a nucleotide at a position in a sequence/chromosome that differs from the nucleotide found at the same position in other sequences. Variants are said to be at high or low frequency in a population depending on whether a large or small proportion of the sequences in that population have the variant nucleotide. A variant is called a “singleton” when it is only found in only one sampled sequence (e.g., the G in position 2 of sequence 1 in part (c) of this problem).

1. You have obtained the sequences of some predetermined region of the genome from a number of randomly selected individuals. Imagine that the genomic region in question is under strong purifying selection (i.e., mutations in this region confer greatly reduced fitness to the organisms that carry them). Will the variants in these sequences tend to be found at high frequency or at low frequency/as singletons (i.e., found only in one individual/on one chromosome)? (Hint: think about how selection affects the probability of fixation of a new allele and its time to extinction.)

> . . .

2. Recall that Π is the average number of nucleotide differences between a pair of randomly selected sequences

Seq 1: A A A A

Seq 2: A T A A

Seq 3: A T A C

For example, for the (3 choose 2) = 3 unique pairs of the three sequences above, &prod; = (1 + 2 + 1) / 3 = 1.33. Will &prod; be larger for a set of sequences with mostly singleton variants or a set with mostly high frequency variants? (Hint: think about variation at a single site. Will &prod; be higher is there is one A and many G's or if there are an equal number of A's and G's?)

> . . . 

2. Below are the sequences of a 20-nucleotide stretch of five randomly selected chromosomes from a popu- lation. An asterisk ‘*’ indicates that the sequence has the same base as the reference in that position. How many segregating sites, S, are there in this sample? (S is more properly denoted S5 here, as there are 5 sequences in the sample.) Recall that S is defined as the number of sites at which one or more sequences has a variant nucleotide

Ref0: A A T G A C T A G C T T A G A C A G G G

Seq1: * G * * * * * * * * * * * * * * T * * *

Seq2: * * * A * * * * * * * * * * * * * * * *

Seq3: * * * C * * * * * * * * * * * * * * * *

Seq4: * * * * * * A * * * * * * * * * * * A *

Seq5: * * * * * * A * * * * * G * * * * * * *

> . . . 

4. Calculate the average nucleotide diversity, &prod; D , of this sample. Note that we are not asking you to calculate &prod; hat D , the expectation of this average as presented in lecture, but rather just &prod; D , the standard arithmetic average

## Problem 2

1. In the kestrel study mentioned in class and in the textbook (Table 10.1, page 228), what are the relative fitnesses of the control birds and the birds with manipulated clutches? For your convenience, the relevant table is presented here.

![Kestrel Falcons](../../originalfiles/evo/pset3_fig1.png)
    
> . . . 

2. Assume that the population consists only of individuals producing one egg less than the optimum and that there is a single gene affecting clutch size with its normal allele designated A1. A mutant allele, A2, arises at this locus, such that the heterozygous A1A2 females have a clutch size size increased by one egg and the homozygous A2A2 females have a clutch size increased by two eggs. Would you expect this locus to be under directional selection, balancing selection, or disruptive selection?

> . . . 

3. Assume the initial value of the A2 allele is 0.01. Using the selective advantage calculated in part (a) and the population genetic model for selection at a single locus in a large population, calculate the frequency of A2 in the next generation.

> . . . 

4. One feature of kestrel biology which violates the assumptions of our standard population genetic model is that kestrel generations overlap. Considering this, will the actual change in allele frequency be greater or smaller than your approximation? Explain briefly.

> . . . 

5. If the results of the kestrel study had been different, and the enlarged clutches actually imparted a higher total reproductive value than did the control clutches, how would you rationalize the apparently “sub- optimal” clutch size of these birds? (Assume further that clutch size is at equilibrium; it is not still evolving towards an as yet unattained optimum.)

> . . .

## Problem 3

1. Explain how sexual selection can be advantageous for the evolution of a population

> Sexual Selection allows for traits recogizable by choosing partners as indexing or mapping to some heritable genotype. The role of the agent in being attracted or seduced factors into complexity of selection and the richness of forms produced thereof.

2. Sexual selection can result in large disparities in reproductive success among members of the competing sex. How might this be disadvantageous for the evolution of a population?

> Competition here burns up resources so to speak. If there is some subset of sexual allurement which maps to nothing of actual efficacy, then all competition derived thereof is sort of like Brownian motion. Instead of integrating towards a particular direction, the forms of life spin around, averaging no real movement at all. This can likely create situations wherein investment of not only resources but all attention is wasted as a sort of excess.

3. Is sexual selection stronger or weaker in monogamous species? When might monogamy be a successful mating strategy? Explain briefly.

> Sexual selection is weaker in monogamous species. This reduces the difference proliferative under the process of sexual selection often leading to very little of a 'gender' divide in not only apperance but also behavior. Overall we see a reduction in constitutive agitation (known as competition).

## Problem 4

The t haplotype polymorphism in mice involves a Mendelian transmission distortion favoring t-bearing chromosomes in heterozygous +/t individuals. Consider a theoretical case in which segregation distortion occurs in both males and females, and in which both homozygous tt males and females die before reproductive age (but the survivorship of heterozygous +/t individuals is unaffected). Suppose that of the gametes produced by +/t heterozygotes, a fraction k has the genotype t and a fraction 1−k has the genotype +, where k ≥ 0.5. Assume a population genetic model for selection at a single locus.

1. Write down an expression for the allele frequency, q′. (Hint: It’s useful to think of q′ as the as the fraction of all gametes released by members of the current generation that are t-bearing gametes.)

> . . . 

2. Plot the change in allele frequency when k = 0.68. (note that by change we mean for you to compute the difference rather than the ratio) Make sure to include any computer code you wrote to generate this plot

> . . .

3. Write down an expression for the allele frequency that leads to equilibrium in terms of k. Explain how you got your answer. (Hint: you can use part (a) to spot check your answer)

4. Why does this equation make intuitive sense? Specifically, why does the t allele go extinct when k = 0.5? Why does it reach an equilibrium frequency between zero and one when 1/2 < k < 1?

> . . . 

## Problem 5

During cell division, microtubules of the spindle apparatus attach to chromosomes at their centromeres. In most eukaryotes, centromeric DNA consists of large arrays of repeated sequences. Cen- tromeric histone-like proteins package centromeric DNA into specialized nucleosomes that can be linked to the spindle apparatus. This creates an opportunity for competition between allelic centromeres, as those that can contact and be packaged more efficiently by centromeric histone-like proteins can increase their chances of transmission during meiosis.

1. Explain how centromere drive, the biased transmission of one centromeric allele over others, could be disadvantageous to a species in which it is operating.

> . . .

2. Why is it the case that centromere drive is generally seen in the context of female, rather than male, meiosis. (Hint: what happens during the process of oogenesis?)

> . . .

3. Explain how centromeric histone-like proteins could play a role in ameliorating the conflict between the chromosome and the whole organism created by centromere drive?

> . . .

4. The sequences of the centromeric DNA repeats are subject to very rapid evolution. Is this rapid evolution an example of the Red Queen effect? Explain your answer.

> . . .

5. Centromere evolution has been proposed as a possible mechanism for speciation. Explain how centromere evolution might lead to the reproductive isolation of two subpopulations of a species that have been physically isolated for some time.

> . . . 



