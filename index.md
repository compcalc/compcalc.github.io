> "The derivative, as this notion appears in the elementary differential calculus, is a familiar mathematical example of a function for which both [the domain and the range] consist of functions. Or, turning to the integral calculus, if in the expression <img src="https://render.githubusercontent.com/render/math?math=\int^{1}_0(f x)dx"> we take the function <img src="https://render.githubusercontent.com/render/math?math=f"> as independent variable, we are led to a function for which the range of arguments consists of functions and the range of values, of numbers."
>
> - Alonzo Church (1941), [The Calculi of Lambda Conversion](http://www.cap-lore.com/Languages/lambda/math/Alonzo/book.html)

Calculus is a broad subject with a variety of applications in classical and statistical computing. Broadly, it encompasses any formal system for manipulating symbolic expressions according to a fixed set of rules. We are specifically interested in its applications to programming. Each week, we will read one or two related papers and hold a short discussion. All are welcome to attend.

## Schedule

### Winter/Spring 2021

| Date              | Talk                                 | Presenter          |
|:------------------|:-------------------------------------|:-------------------|
| Feb. 5, 9:30 am   | Automatic Differentiation in PyTorch | Breandan Considine |
| Feb. 12, 1:00 pm  | Programming with Probabilities       | Breandan Considine |
| Feb. 19, 1:00 pm  | Introduction to Sequent Calculus     | Breandan Considine |
| Feb. 26, 10:00 am | Quantitative Equational Reasoning    | Prakash Panangaden |

If you would like to sign up to present or wish to receive an invitation to join the reading group, please reach out to the organizer by electronic mail using the following address: bre at ndan dot co.

## Reading Materials

A few recent papers on differential, integral and logical calculi are listed for illustrative purposes below, following the general theme of topics we plan to discuss. Other suggested reading materials are also welcome!

### Differential

Differentiable programming concerns the calculus of infinitesimal change and change propagation through a computation graph. This subject is the original and primary focus of this reading group.

* [PyTorch: An Imperative Style, High-Performance Deep Learning Library](https://papers.nips.cc/paper/2019/file/bdbca288fee7f92f2bfa9f7012727740-Paper.pdf), Paszke et al. (2019)
* [λ<sub>S</sub>: Computable semantics for differentiable programming](https://arxiv.org/pdf/2007.08017.pdf), Sherman et al. (2020)
* [Instead of Rewriting Foreign Code for Machine Learning, Automatically Synthesize Fast Gradients](https://arxiv.org/pdf/2010.01709.pdf), Moses and Churavy (2020)
* [Differentiable Weighted Finite-State Transducers](https://arxiv.org/pdf/2010.01003.pdf), Hannun et al. (2020)
* [Differentiate Everything with a Reversible Domain-Specific Language](https://arxiv.org/pdf/2003.04617.pdf), Liu and Zhao (2020)
* [The Simple Essence of Automatic Differentiation](https://arxiv.org/pdf/1804.00746.pdf), Elliott (2018)
* [Automatic differentiation in ML: Where we are and where we should be going](https://arxiv.org/pdf/1810.11530.pdf), Merriënboer et al. (2018)
* [Automatic differentiation in machine learning: a survey](https://www.jmlr.org/papers/volume18/17-468/17-468.pdf), Baydin et al. (2017)

### Integral

We will also discuss some topics in automatic integration or probabilistic programming, i.e. the study of volume, density and how to derive their exact or approximate quantity.

* [Quantitative Equational Reasoning](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/4B76BCCD4D6A3A37459C35ED2CE5FF93/9781108488518c10_333-360.pdf/quantitative_equational_reasoning.pdf), Bacci, Mardare, Panangaden, and Plotkin (2020)
* [miniKanren as a Tool for Symbolic Computation in Python](https://arxiv.org/pdf/2005.11644.pdf), Willard (2020)
* [Probabilistic Circuits: A Unifying Framework for Tractable Probabilistic Models](http://starai.cs.ucla.edu/papers/ProbCirc20.pdf), Choi et al. (2020)
* [Probabilistic Programming with CuPPL](https://arxiv.org/pdf/2010.08454.pdf), Collins and Grover (2020)
* [Automatic Reparameterisation of Probabilistic Programs](https://arxiv.org/pdf/1906.03028.pdf), Gorinova et al. (2019)
* [Deep Learning for Symbolic Mathematics](https://arxiv.org/pdf/1912.01412.pdf), Lample and Charton (2019)
* [Augur: Data-Parallel Probabilistic Modeling](https://papers.nips.cc/paper/2014/file/cf9a242b70f45317ffd281241fa66502-Paper.pdf), Tristan et al. (2014)

#### Books

* [An Introduction to Probabilistic Programming](https://arxiv.org/pdf/1809.10756.pdf), Van de Meen et al. (2018)
* [Foundations of Probabilistic Programming](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/819623B1B5B33836476618AC0621F0EE/9781108488518AR.pdf), Barthe et al. (2020)

### Logical

Finally, we plan to discuss some related topics in other logical calculi, including combinatory logic, sequent calculus and other formal systems. This material will be primarily introductory and no prior experience is expected or required.

* [Constructive Mathematics and Computer Programming](https://www.cs.tufts.edu/~nr/cs257/archive/per-martin-lof/constructive-math.pdf), Per Martin-Löf (1976)
* [Lecture Notes on the Lambda Calculus](https://www.irif.fr/~mellies/mpri/mpri-ens/biblio/Selinger-Lambda-Calculus-Notes.pdf), Selinger (2013)
* [The differential lambda-calculus](https://core.ac.uk/download/pdf/82396223.pdf), Ehrhard and Regnier (2001)
* [A general definition of dependent type theories](https://arxiv.org/pdf/2009.05539.pdf), Bauer (2020)
* [Binary Lambda Calculus and Combinatory Logic](https://drops.dagstuhl.de/opus/volltexte/2006/628/pdf/06051.TrompJohn.Paper.628.pdf), Tromp (2006)
* [The SKI Combinator Calculus, a universal formal system](http://people.cs.uchicago.edu/~odonnell/Teacher/Lectures/Formal_Organization_of_Knowledge/Examples/combinator_calculus.texpdf.pdf), O'Donnell