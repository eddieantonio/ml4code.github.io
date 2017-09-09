---
layout: page
title: Taxonomy
---
A probabilistic model of source code is a probability distribution 
over code artifacts. To group these family of models
in terms of shared design choices,
we separate these models into three categories,
based on the form of the equation of the modeled probability 
distribution and their inputs and outputs. Some models fall into multiple categories
because decompositions of their equations fall into different categories.


 * **Code-generating Models** generate code by
    stochastically modeling the generation of smaller and simpler parts of code, _e.g._
    tokens or AST nodes.

 * **Representational Models of Code** take an abstract representation of
    code as input.  Example representations include token contexts or data flow.
    The resulting model yields a conditional probability distribution over code
    element properties, like the types of variables, and can predict them.

 * **Pattern Mining Models** infer, without supervision, a likely latent
    structure within code. These models are an instantiation of clustering
    in the code domain; they can find reusable and human-interpretable patterns.
