# INQUISITIVE Dataset 
A dataset of about 20k questions that are elicited from readers as they naturally read through a document sentence by sentence.  Compared to existing datasets, INQUISITIVE questions target more towards high-level (semantic and discourse) comprehension of text. Because these questions are generated while the readers are pro-cessing the information, the questions directly communicate gaps between the reader’s and writer’s knowledge about the events described in the text, and are not necessarily answered in the document itself. This type of question reflects a real-world scenario: if one has questions during reading, some of them are answered by the text later on, the rest are not, but any of them would help further the reader’s understanding at the  particular point when they asked it.  This resource could enable question generation models to simulate human-like curiosity and cognitive processing, which may open up a new realm of applications. 

**Citation:**
```
@inproceedings{ko2020inquisitive,
  title={Inquisitive Question Generation for High Level Text Comprehension},
  author={Ko, Wei-Jen and Chen, Te-yuan and Huang, Yiyan and Durrett, Greg and Li, Junyi Jessy},
  booktitle={Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
  pages={6544--6555},
  year={2020}
}
```


# Data split
Validation: 1\~100, 1051\~1100

Test: 101\~150, 501\~550, 1101\~1150

The remaining articles are the training set.

# Article Sources
WSJ: 51\~259, 551\~590, 696\~900, 1446\~1491

Newsela: 1\~50, 260\~550, 901\~1050, 1492\~1500

AP: 591\~695, 1051\~1445

Since the articles are copyrighted, please send us an email to ask for the articles (jessy@utexas.edu). For the Newsela portion of the data, please obtain permission from newsela (https://newsela.com/data) first before emailing us. (Newsela data is free to obtain for researchers).


# Note on span
The Span_Start_Position	and Span_End_Position are calculated by counting the white spaces. Note that in some sentences there are consecutive white spaces.
