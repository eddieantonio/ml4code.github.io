---
layout: publication
title: "Finding and correcting syntax errors using recurrent neural networks"
authors: E. A. Santos, J. C. Campbell, A. Hindle, J. N. Amaral
conference: "PeerJ Preprints"
year: 2017
bibkey: santos2017finding
additional_links:
 - {name: "PeerJ", url: "https://peerj.com/preprints/3123v1/"}
 - {name: "Models", url: "https://archive.org/details/lstm-javascript-tiny"}
 - {name: "Code", url: "https://github.com/eddieantonio/training-grammar-guru/tree/cmput680"}
---
Minor syntax errors are made by novice and experienced programmers alike;
however, novice programmers lack the years of intuition that help them resolve these tiny errors.
Standard LR parsers typically resolve syntax errors and their precise location poorly.
We propose a methodology that helps locate where syntax errors occur, but also suggests possible changes to the token stream that can fix the error identified.
This methodology finds syntax errors by checking if two language models “agree” on each token.
If the models disagree, it indicates a possible syntax error; the methodology tries to suggest a fix by finding an alternative token sequence obtained from the models.
We trained two LSTM (Long short-term memory) language models on a large corpus of JavaScript code collected from GitHub.
The dual LSTM neural network model predicts the correct location of the syntax error 54.74% in its top 4 suggestions and produces an exact fix up to 35.50% of the time.
The results show that this tool and methodology can locate and suggest corrections for syntax errors.
Our methodology is of practical use to all programmers, but will be especially useful to novices frustrated with incomprehensible syntax errors.
