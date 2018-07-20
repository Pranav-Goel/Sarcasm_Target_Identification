## Sarcasm Target Identification: Dataset and An Introductory Approach
by **Aditya Joshi, Pranav Goel, Pushpak Bhattacharyya, and Mark J Carman**

This repository contains all the documented scripts and files to run our experiments which can serve as a baseline system for future systems built for the new task introduced by us -  Sarcasm Target Identification.

**Details (including results) can be found in our paper (with the title above) accepted for publication at LREC 2018 (full main conference paper). The PDF of the paper can be found at [here](http://www.lrec-conf.org/proceedings/lrec2018/pdf/583.pdf).**

### If the code or the experiments described in the paper help your own work, or you use our dataset for your own experiments, or the the task we introduce is relevant, *please cite our paper* -
@InProceedings{JOSHI18.583,
  author = {Aditya Joshi and Pranav Goel and Pushpak Bhattacharyya and Mark Carman},
  title = "{Sarcasm Target Identification: Dataset and An Introductory Approach}",
  booktitle = {Proceedings of the Eleventh International Conference on Language Resources and Evaluation (LREC 2018)},
  year = {2018},
  month = {May 7-12, 2018},
  address = {Miyazaki, Japan},
  editor = {Nicoletta Calzolari (Conference chair) and Khalid Choukri and Christopher Cieri and Thierry Declerck and Sara Goggi and Koiti Hasida and Hitoshi Isahara and Bente Maegaard and Joseph Mariani and Hélène Mazo and Asuncion Moreno and Jan Odijk and Stelios Piperidis and Takenobu Tokunaga},
  publisher = {European Language Resources Association (ELRA)},
  isbn = {979-10-95546-00-9},
  language = {english}
  }
  
  
Abstract: Past work in computational sarcasm deals primarily with sarcasm detection. In this paper, we introduce a novel, related problem: sarcasm target identification (i.e., extracting the target of ridicule in a sarcastic sentence). As a benchmark, we introduce a new dataset for the task. This dataset is manually annotated for the sarcasm target in book snippets and tweets based on our formulation of the task. We then introduce an automatic approach for sarcasm target identification. It is based on a combination of two types of extractors: one based on rules, and another consisting of a statistical classifier. Our introductory approach establishes the viability of sarcasm target identification, and will serve as a baseline for future work.

Keywords: Sentiment Analysis, Computational Sarcasm, Aspect Extraction


### Subdirectories - 

Code/			- 		This contains all the Python Scripts, and bash instructions.

Data/			- 		This provides link to our data, and also the external sentiment lexicon we used.

Manual/			- 		This contains an User Manual and a Programmer Manual which will be of great use in order to run the codes.
