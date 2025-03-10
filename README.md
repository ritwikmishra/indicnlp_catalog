
# :bookmark: The Indic NLP Catalog
_A Collaborative Catalog of Resources for Indic Language NLP_

The **Indic NLP Catalog** repository is an attempt to **collaboratively** build the **most comprehensive** catalog of NLP datasets, models and other resources for all languages of the Indian subcontinent.

_Please suggest any other resources you may be aware of. Raise a pull request or an issue to add more resources to the catalog. Put the proposed entry in the following format:_

  \[Wikipedia Dumps\]\(https://dumps.wikimedia.org/)

_Add a small, informative description of the dataset and provide links to any paper/article/site documenting the resource. Mention your name too. We would like to acknowlege your contribution to building this catalog in the [CONTRIBUTORS](CONTRIBUTORS.md) list._

## :+1: Featured Resources

Indian language NLP has come a long way. We feature a few resources that are illustrative of the trends in recent times along various axes and point to a bright future.  
 
- [Universal Language Contribution API (ULCA)](https://bhashini.gov.in/ulca): **ULCA** is a standard API and open scalable data platform (supporting various types of datasets) for Indian language datasets and models. ULCA is part of the [Bhasini mission](https://bhashini.gov.in). You can upload, discover models, datasets and benchmarks here. This is one repository we really need and hope to see this evolving into a standard, large-scale platform for resource discovery and dissemination.
- We are seeing the rise of large-scale datasets across many tasks like **IndicCorp** (text corpus/9 billion tokens), **Samanantar** (parallel corpus/50 million sentence pairs), **Naamapadam** (named entity/5.7 million sentences), **HiNER** (named entity/100k sentences), **Aksharantar** (transliteration/26 million pairs) , _etc_. These are being built using either large-scale mining of web-resource or large human annotation efforts or both. 
- As we aim higher, the datasets and models are achieving higher language coverage. While earlier datasets would be available for only a handful of Indian languages, then for 10-12 languages - we are now reaching the next frontier where we are creating resources like **Aksharantar** (transliteration/21 languages), **FLORES-200** (translation/27 languages), **IndoWordNet** (wordnet/18 languages) spanning almost all languages listed in the Indian constitution and more.  Datasets and models spanning a large number of languages. 
- Particularly, we are seeing datasets getting created for extremely low-resourced languages or languages not yet covered in any dataset like **Bodo**, **Kangri**, **Khasi**, _etc_.
- From a handful of institutes who pioneered the development of NLP in India, we now have an increasing number of institutes/interest groups and passionate volunteers like **AI4Bharat**, **BUET CSE NLP**, **KMI**, **L3Cube**, **iNLTK**, **IIT Patna**, _etc_. who are contributing to building resources for Indian languages.

## Browse the entire catalog...

:raising_hand:**Note**: Many known resources have not yet been classified into the catalog. They can be found as open issues in the repo.
	
<!-- vscode-markdown-toc -->
* [Major Indic Language NLP Repositories](#MajorIndicLanguageNLPRepositories)
* [Libraries and Tools](#Libraries)
* [Evaluation Benchmarks](#Benchmarks)
* [Standards](#Standards)
	* [Unicode Standard](#UnicodeStandard)
* [Text Corpora](#TextCorpora)
	* [Monolingual Corpus](#MonolingualCorpus)
	* [Language Identification](#LanguageIdentification)	
	* [Lexical Resources](#LexicalResources)
	* [NER Corpora](#NERCorpora)
	* [Parallel Translation Corpus](#ParallelTranslationCorpus)
	* [Parallel Transliteration Corpus](#ParallelTransliterationCorpus)
	* [Text Classification](#TextualClassification)
	* [Textual Entailment/Natural Language Inference](#TextualEntailment)
	* [Paraphrase](#Paraphrase)
	* [Sentiment, Sarcasm, Emotion  Analysis](#SentimentAnalysis)
	* [Hate Speech and Offensive Comments](#HateSpeech)
	* [Question Answering](#QuestionAnswering)
	* [Dialog](#Dialog)
	* [Discourse](#Discourse)
	* [Information Extraction](#InformationExtraction)
	* [POS Tagged corpus](#POSTaggedcorpus)
	* [Chunk Corpus](#ChunkCorpus)
	* [Dependency Parse Corpus](#DependencyParseCorpus)
	* [Co-reference Corpus](#CoreferenceCorpus)
	* [Summarization](#Summarization)
	* [Data to Text](#DatatoText)
* [Models](#Models)
	* [Word Embeddings](#WordEmbeddings)
	* [Pre-trained Language Models](#PreTrainedLanguageModels)
	* [Multilingual Word Embeddings](#MultilingualWordEmbeddings)
	* [Morphanalyzers](#Morphanalyzers)
	* [Translation Models](#TranslationModels)
	* [Speech Models](#SpeechModels)
	* [NER](#NER)
* [Speech Corpora](#SpeechCorpora)
* [OCR Corpora](#OCRCorpora)
* [Multimodal Corpora](#MultimodalCorpora)
* [Language Specific Catalogs](#LanguageSpecificCatalogs)	


<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->


## <a name='MajorIndicLanguageNLPRepositories'></a>Major Indic Language NLP Repositories
- [Universal Language Contribution API (ULCA)](https://bhashini.gov.in/ulca)
- [Technology Development for Indian Languages (TDIL)](http://tdil-dc.in)
- [Center for Indian Language Technology (CFILT)](http://www.cfilt.iitb.ac.in/)
- [Language Technologies Research Center (LTRC)](https://ltrc.iiit.ac.in/download.php)
- [AI4Bharat IndicNLP](https://ai4bharat.iitm.ac.in/)
- [Linguistic Data Consortium For Indian Languages (LDCIL)](https://data.ldcil.org)
- [University of Hyderabad - Sanskrit NLP](http://sanskrit.uohyd.ac.in/scl)
- [National Platform for Language Technology](https://nplt.in/demo/index.php?route=product/category&path=75_59&limit=100)
- [BUET CSE NLP Group](https://csebuetnlp.github.io)
- [KMI Linguistics](https://github.com/kmi-linguistics)
- [L3Cube](https://github.com/l3cube-pune/MarathiNLP)
- [IIT Patna](https://www.iitp.ac.in/~ai-nlp-ml/resources.html)


## <a name='Libraries'></a>Libraries and Tools

- [Indic NLP Library](https://github.com/anoopkunchukuttan/indic_nlp_library): Python Library for various Indian language NLP tasks like tokenization, sentence splitting, normalization, script conversion, transliteration, _etc_
	- [Devnagri to Roman transliteration](https://github.com/ritwikmishra/devanagari-to-roman-script-transliteration) using hand-crafted rules and lexicons.
- [pyiwn](https://github.com/riteshpanjwani/pyiwn): Python Interface to IndoWordNet
- [Indic-OCR](https://indic-ocr.github.io/) : OCR for Indic Scripts
- [CLTK](https://github.com/cltk/cltk/tree/master/cltk): Toolkit for many of the world's classical languages. Support for Sanskrit. Some parts of the Sanskrit library are forked from the Indic NLP Library.
- [iNLTK](https://github.com/goru001/inltk): iNLTK aims to provide out of the box support for various NLP tasks that an application developer might need for Indic languages.
- [Sanskrit Coders Indic Transliteration](https://github.com/sanskrit-coders/indic_transliteration): Script conversion and romanization for Indian languages.
- [Smart Sanskirt Annotator](https://github.com/iamdsc/smart-sanskrit-annotator): Annotation tool for Sanskrit [paper](http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.874.pdf)
- [BNLP](https://github.com/sagorbrur/bnlp): Bengali language processing toolkit with tokenization, embedding, POS tagging, NER suppport
- [CodeSwitch](https://github.com/sagorbrur/codeswitch): Language identification, POS Tagging, NER, sentiment analysis support for code mixed data including Hindi and Nepali language
- [IndIE](https://github.com/ritwikmishra/IndIE): An Open Information Extraction tool (triple extractor) in Hindi. It is conjectured to work for Tamil, Telugu, and Urdu as well.
- [Hindi-BenchIE](https://github.com/ritwikmishra/hindi-benchie): A triple evaluation tool for 112 Hindi sentences.

## <a name='Benchmarks'></a>Evaluation Benchmarks

Benchmarks spanning multiple tasks.

- [AI4Bharat IndicGLUE](https://ai4bharat.iitm.ac.in/indic-glue): NLU benchmark for 11 languages.
- [AI4Bharat IndicNLG Suite](https://ai4bharat.iitm.ac.in/indic-nlg-suite): NLG benchmark for 11 languages spanning 5 generation tasks: biography generation, sentence summarization, headline generation, paraphrase generation and question generation.
- [GLUECoS](https://microsoft.github.io/GLUECoS): For Hindi-English code-mixed benchmark containing the following tasks - Language Identification (LID), POS Tagging (POS), Named Entity Recognition (NER), Sentiment Analysis (SA), Question Answering (QA), Natural Language Inference (NLI).
- [AI4Bharat Text Classification](https://github.com/ai4bharat/indicnlp_corpus#publicly-available-classification-datasets): A compilation of classification datasets for 10 languages.
- [WAT 2021 Translation Dataset](http://lotus.kuee.kyoto-u.ac.jp/WAT/indic-multilingual): Standard train and test sets for translation between English and 10 Indian languages.

## <a name='Standards'></a>Standards

- Unicode Standard for Indic Scripts
   - [An Introduction to Indic Scripts](https://www.w3.org/2002/Talks/09-ri-indic/indic-paper.pdf)
   - [Unicode Standard for South Asian Scripts](http://www.unicode.org/versions/Unicode12.1.0/ch12.pdf)

## <a name='TextCorpora'></a>Text Corpora

### <a name='MonolingualCorpus'></a>Monolingual Corpus

- [AIBharat IndicCorp](https://ai4bharat.iitm.ac.in/indic-corp): contains 8.9 billion tokens from 12 Indian languages (including Indian English).
- [Wikipedia Dumps](https://dumps.wikimedia.org)
- Common Crawl
	- [OSCAR Corpus](https://traces1.inria.fr/oscar): Released in 2019, large-scaled processed CommonCrawl.	
	- [WMT Common Crawl Dumps](http://data.statmt.org/ngrams/raw): Crawls between 2012 and 2016. Noisy text, needs to be filtered.
	- [CC-100 Corpus](): Facebook CommonCrawl extracted data. They provide scripts for processing CommonCrawl. StatMT has built a replica of the CC-100 corpus using these scripts. You can find it [HERE](http://data.statmt.org/cc-100). This corpus also has romanized corpora for some Indian languages.
- [WMT NEWS Crawl](http://data.statmt.org/news-crawl)
- [LDCIL Monolingual Corpus](https://data.ldcil.org)
- [Charles University Hindi Monolingual Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0023-625F-0)
- [Charles University Urdu Monolingual Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0023-65A9-5)
- [IIT Bombay Hindi Monolingual Corpus](http://www.cfilt.iitb.ac.in/iitb_parallel/iitb_corpus_download/monolingual.hi.tgz)
- [EMILLE Corpus (multiple Indian languages)](https://www.lancaster.ac.uk/fass/projects/corpus/emille/)
- [Janmabhumi Malayalam Corpus](https://github.com/ABHISHEKVALSAN/Malayalam-Newspaper-Article-Dataset)
- [Leipzig Corpus](http://wortschatz.uni-leipzig.de/en/download/)
- [Sanskrit Monolingual and Sandhi-split Corpus](http://sanskrit.uohyd.ac.in/Corpus/)
- [Lot Of Indic Tweets Corpus](https://github.com/bedapudi6788/LOIT): Large twitter datasets for telugu (7.9 million) and hindi (17.6 million) and fasttext skipgram and cbow word vectors for the same.
- [CMU Romanized Hinglish Corpus](https://github.com/khyathiraghavi/multi_task_code_switched_language_modeling/tree/master/hinglishData): See [THIS PAPER](https://www.aclweb.org/anthology/W18-3211.pdf) for details. 
- [JNU-BHLTR Bhojpuri Corpus](https://github.com/shashwatup9k/bho-resources/tree/master/mono-bho-corpus): Bhojpuri corpus of 45k sentences.
- [KMI Magahi Corpus](https://github.com/kmi-linguistics/magahi): 
- [KMI Awadhi Corpus](https://github.com/kmi-linguistics/awadhi): 
- [KMI Linguistics Bodo](https://github.com/kmi-linguistics/bodo): Contains the Bodo corpus and the frequency-ordered word and punctuation list.
- [SMC Malayalam text corpus](https://gitlab.com/smc/corpus)
- [DNLP-Tel Telugu Corpus](https://drive.google.com/drive/folders/1fEt7aIzYWGQKto3Nt51M5CdjtzxMqdCz?usp=sharing): Telugu corpus of 280M tokens and 23M sentences along with skip-gram model trained with word2vec.
- [Ema-lon Manipuri Corpus](http://catalog.elra.info/en-us/repository/browse/ELRA-W0316/): The first comparable corpus built for the Manipuri (mni)-English (eng) language pair with the monolingual data comprising of 1,034,715 Manipuri sentences and 846,796 English sentences in version 1 and 1,880,035 Manipuri sentences and 1,450,053 English sentences in version 2.
- [SinMin Corpus](https://osf.io/a5quv/): Contains texts of different genres and styles of the modern and old Sinhala language.
- [Kangri_corpus](https://github.com/chauhanshweta/Kangri_corpus): Monolingual corpus of Himachali low resource endangered language, Kangri comprising of 1,81,552 sentences. Described in [this paper](https://arxiv.org/abs/2103.11596).
- [Sanskrit-Hindi-MT](https://github.com/priyanshu2103/Sanskrit-Hindi-Machine-Translation): The Sanskrit Monolingual Data is available [here](https://drive.google.com/file/d/1_qclc7unNLvToiDK8t2scIgj5oxJDEGm/view?usp=sharing).
- [FacebookDecadeCorpora](https://github.com/samithaj/FacebookDecadeCorpora): Contains two language corpora of colloquial Sinhala content extracted from Facebook using the Crowdtangle platform. The larger corpus contains 28,825,820 to 29,549,672 words of text, mostly in Sinhala, English and Tamil and the smaller corpus amounts to 5,402,76 words of only Sinhala text extracted from Corpus-Alpha. Described in [this paper](https://arxiv.org/ftp/arxiv/papers/2007/2007.07884.pdf).
- [Nepali National corpus](http://catalog.elra.info/product_info.php?products_id=1216): The Nepali Monolingual written corpus comprises the core corpus containing 802,000 words and the general corpus containing 1,400,000 words. Described [here](https://www.sketchengine.eu/nepali-national-corpus/).

### <a name='LanguageIdentification'></a>Language Identification

- [VarDial 2018 Language Identification Dataset](https://github.com/kmi-linguistics/vardial2018): 5 languages - Hindi, Braj, Awadhi, Bhojpuri, Magahi.

### <a name='LexicalResources'></a>Lexical Resources and Semantic Similarity

- [IndoWordNet](http://www.cfilt.iitb.ac.in/indowordnet/)
- [IIIT-Hyderabad Word Similarity Database](https://github.com/syedsarfarazakhtar/Word-Similarity-Datasets-for-Indian-Languages): 7 Indian languages
- [Facebook Hindi Analogy Dataset](https://dl.fbaipublicfiles.com/fasttext/word-analogies/questions-words-hi.txt)
- [MGAD Hindi Analogy dataset](https://github.com/rutrastone/MGAD)
- [AI4Bharat Word Frequency Lists](https://github.com/AI4Bharat/indicnlp_corpus#text-corpora): Tokens and their frequencies from the AI4Bharat corpus, a large monolingual corpus.
- [Hindi RG-63](https://github.com/ashwinivd/similarity_hindi): Hindi version of the Rubenstein and Goodenough (RG-65) word similarity dataset
- [IITB Cognate Datasets](https://github.com/dipteshkanojia/challengeCognateFF): Dataset of Cognates and False Friend Pairs for 12 Indian Languages. [(Paper)](https://aclanthology.org/2020.lrec-1.378.pdf)
- [AI4Bharat Cross-lingual Semantic Textual Similarity](https://storage.googleapis.com/samanantar-public/human_annotations.tsv): 10 sentences across 11 en-Indic language pairs annotated on a scale of 0-5 as per SemEval cross-lingual STS guidelines.
- [Toxicity-200](https://github.com/facebookresearch/flores/blob/main/toxicity): Toxicity Lists for 200 languages including 27 Indian languages.
- [FacebookDecadeCorpora](https://github.com/samithaj/FacebookDecadeCorpora): Contains a list of algorithmically derived stopwords extracted from Corpus-Sinhala-Redux. Described in [this paper](https://arxiv.org/ftp/arxiv/papers/2007/2007.07884.pdf).

### <a name='NERCorpora'></a>NER Corpora

- [FIRE 2013 AUKBC NER Corpus](http://au-kbc.org/nlp/NER-FIRE2013)
- [FIRE 2014 AUKBC NER Corpus](http://www.au-kbc.org/nlp/NER-FIRE2014/)
- [IIT Bombay Marathi NER Corpus](http://www.cfilt.iitb.ac.in/ner/download_data.html)
- [WikiAnn NER Corpus](https://elisa-ie.github.io/wikiann) (_Noisy_)  [DOWNLOAD](https://drive.google.com/drive/folders/1Q-xdT99SeaCghihGa7nRkcXGwRGUIsKN?usp=sharing)  (Old broken [LINK](http://nlp.cs.rpi.edu))
- [IJCNLP 200 NER Corpus](http://ltrc.iiit.ac.in/ner-ssea-08/index.cgi?topic=5): NER corpora for hi, bn, or, te, ur.
- [a-mma NER data](https://github.com/a-mma/NER_Open_Data)
- [AI4Bharat Naamapadam](https://huggingface.co/datasets/ai4bharat/naamapadam): NER dataset for 11 Indic languages.
- [AsNER](https://arxiv.org/ftp/arxiv/papers/2207/2207.03422.pdf): A named entity annotation dataset for low resource Assamese language containing 99k tokens.
- [L3Cube-MahaNER](https://github.com/l3cube-pune/MarathiNLP/tree/main/L3Cube-MahaNER): The first major gold standard named entity recognition dataset in Marathi consisting of 25,000 sentences in Marathi language. Described in [this paper](http://www.lrec-conf.org/proceedings/lrec2022/workshops/WILDRE6/pdf/2022.wildre6-1.6.pdf).
- [CFILT HiNER](https://github.com/cfiltnlp/hiner): A large Hindi NER dataset containing 109,146 sentences and 2,220,856 tokens. Described in [this paper](https://arxiv.org/abs/2204.13743).
- [MultiCoNER](https://multiconer.github.io/): A multilingual complex Named Entity Recognition dataset composed of 2.3 million instances for 11 languages(including dataset for Indic languages Hindi and Bangla) representing three domains(wiki sentences, questions, and search queries) plus multilingual and code-mixed subsets.The NER tag-set consists of six classes viz.: PER,LOC,CORP,GRP,PROD and CW. Described in [this paper](https://aclanthology.org/2022.semeval-1.196.pdf).

### <a name='ParallelTranslationCorpus'></a>Parallel Translation Corpus

- [Samanantar Parallel Corpus](https://ai4bharat.iitm.ac.in/samanantar): Largest parallel corpus for English and 11 Indian languages. It comprises 46m sentence pairs between English-Indian languages and 82m sentence  pairs between Indian languages.
- [FLORES-101](https://github.com/facebookresearch/flores): Human translated evaluation sets for 101 languages released by Facebook. It includes 14 Indic languages. The testsets are n-way parallel. 
- [FLORES-200](https://github.com/facebookresearch/flores/tree/main/flores200): Human translated evaluation sets for 200 languages released by Facebook. It includes 24 Indic languages. The testsets are n-way parallel. 
- [IIT Bombay English-Hindi Parallel Corpus](http://www.cfilt.iitb.ac.in/iitb_parallel): Largest en-hi parallel corpora in public domain (about 1.5 million segments)
- [CVIT-IIITH PIB Multilingual Corpus](http://preon.iiit.ac.in/~jerin/resources/datasets/pib-v0.tar): Mined from Press Information Bureau for many Indian languages. Contains both English-IL and IL-IL corpora (IL=Indian language).
- [CVIT-IIITH Mann ki Baat Corpus](http://preon.iiit.ac.in/~jerin/resources/datasets/mkb-v0.tar): Mined from Indian PM Narendra Modi's _Mann ki Baat_ speeches.
- [PMIndia](http://data.statmt.org/pmindia): Parallel corpus for En-Indian languages mined from _Mann ki Baat_ speeches of the PM of India ([paper](https://arxiv.org/abs/2001.09907)).
- [OPUS corpus](http://opus.nlpl.eu/)
- [WAT 2018 Parallel Corpus](http://lotus.kuee.kyoto-u.ac.jp/WAT/indic-multilingual/index.html): There may significant overlap between WAT and OPUS.
- [Charles University English-Hindi Parallel Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0001-BD17-1): This is included in the IITB parallel corpus.
- [Charles University English-Tamil Parallel Corpus](http://ufal.mff.cuni.cz/~ramasamy/parallel/html/)
- [Charles University English-Odia Parallel Corpus v1.0](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2879)
- [Charles University English-Odia Parallel Corpus v2.0](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-3211)
- [Charles University English-Urdu Religious Parallel Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2582)
- [Indian Language Corpora Initiative](http://sanskrit.jnu.ac.in/ilci/index.jsp): Available on TDIL portal on request
- [IndoWordnet Parallel Corpus](https://github.com/anoopkunchukuttan/indowordnet_parallel): Parallel corpora mined from IndoWordNet gloss and/or examples for Indian-Indian language corpora  (6.3 million segments, 18 languages). 
- [MTurk Indian Parallel Corpus](https://github.com/joshua-decoder/indian-parallel-corpora)
- [TED Parallel Corpus](https://github.com/ajinkyakulkarni14/TED-Multilingual-Parallel-Corpus)
- [JW300 Corpus](http://opus.nlpl.eu/JW300.php): Parallel corpus mined from jw.org. Religious text from Jehovah's Witness. 
- [ALT Parallel Corpus](http://www2.nict.go.jp/astrec-att/member/mutiyama/ALT): 10k sentences for Bengali, Hindi in parallel with English and many East Asian languages.
- [FLORES dataset](https://github.com/facebookresearch/flores): English-Sinhala and English-Nepali corpora
- [Uka Tarsadia University Corpus](https://github.com/shahparth123/eng_guj_parallel_corpus): 65k English-Gujarati sentence pairs. Corpus is described in [this paper](https://arxiv.org/abs/2002.02758)
- [NLPC-UoM English-Tamil Corpus](https://github.com/nlpc-uom/English-Tamil-Parallel-Corpus): 9k sentences, 24k glossary terms
- Wikititles: from statmt
   - [English-Tamil Wiki Titles](http://data.statmt.org/wikititles/v2/wikititles-v2.ta-en.tsv.gz) 
   - [English-Gujarati Wiki Titles](http://data.statmt.org/wikititles/v1/wikititles-v1.gu-en.tsv.gz)
- [JNU-BHLTR Bhojpuri Corpus](https://github.com/shashwatup9k/bho-resources): English-Bhojpuri corpus of 65k sentences
- [EILMT Corpus](http://tdil-dc.in/index.php?searchword=EILMT&searchphrase=all&option=com_search&lang=en)
- [QED Corpus](http://alt.qcri.org/resources/qedcorpus): English-Hindi corpus of 43k sentences from the educational domain.
- [WikiMatrix Corpus](https://ai.facebook.com/blog/wikimatrix): Mined from Wikipedia, looks noisy.
- [CCMatrix](https://github.com/facebookresearch/LASER/tree/master/tasks/CCMatrix): Parallel corpus mined from CommonCrawl, looks noisy ([statmt repo](http://data.statmt.org/cc-matrix)).
- [CGNetSwara](http://cgnetswara.org/hindi-gondi-corpus.html): Hindi-Gondi parallel corpus (19k sentence pairs)
- [MTEnglish2Odia](https://github.com/soumendrak/MTEnglish2Odia): English-Odia (42k pairs)
- [SAP Software Documentation](https://github.com/SAP/software-documentation-data-set-for-machine-translation): test and evaluation set for English-Hindi in the  software documentation domain [[paper](https://arxiv.org/abs/2008.04550)]
- [BUET English-Bangla Corpus, EMNLP-2020](https://github.com/csebuetnlp/banglanmt): 2.7M sentences (has overlaps with OPUS)
- [CLE Parallel Corpus](https://www.cle.org.pk/software/ling_resources/UrduNepaliEnglishParallelCorpus.htm): Parallel corpus for English, Urdu and Nepali.
- [Itihasa Parallel Corpus](https://github.com/rahular/itihasa): 93k parallel sentences between English and Sanskrit from the Ramanyana and Mahabharata.
- [Ema-lon Manipuri Corpus](http://catalog.elra.info/en-us/repository/browse/ELRA-W0316/): The first comparable corpus built for the Manipuri (mni)-English (eng) language pair with parallel data comprising of 124,975 Manipuri-English aligned sentences.
- [PHINC](https://zenodo.org/record/3605597#.YvjqEXZBy5d): A Parallel Hinglish Social Media Code-Mixed Corpus consisting of 13,738 code-mixed English-Hindi sentences and their corresponding translation in English. Described in [this paper](https://aclanthology.org/2020.wnut-1.7.pdf).
- [IIIT-H en-hi-codemixed-corpus](https://github.com/mrinaldhar/en-hi-codemixed-corpus): A gold standard parallel corpus consisting of 6096 English-Hindi code-mixed sentences containing a total of 63,913 tokens and monolingual English. Described in [this paper](https://aclanthology.org/W18-3817.pdf).
- [CALCS 2021 Eng-Hinglish dataset](https://ritual.uh.edu/lince/datasets): Eng-Hinglish parallel corpus containing 10k pairs of sentences. Described in [this paper](https://arxiv.org/pdf/2202.09625.pdf).
- [Kangri_corpus](https://github.com/chauhanshweta/Kangri_corpus): The corpus contains 27,362 Hindi-Kangri Parallel corpora. Described in [this paper] (https://arxiv.org/abs/2103.11596).
- [NLLB-Seed](https://github.com/facebookresearch/flores/tree/main/nllb_seed): Small human-translated parallel corpora from Wikipedia articles for very low resource languages. Includes 5 Indian languages: Kashmiri, Manipuri, Maithili, Bhojpuri, Chattisgarhi. 
- [NLLB-MD](https://github.com/facebookresearch/flores/tree/main/nllb_seed): NLLB Multi Domain is a set of professionally-translated sentences in News, Unscripted informal speech, and Health domains. Cover Bhojpuri amongst Indian languages.
- [NLLB-Mined](https://huggingface.co/datasets/allenai/nllb): All the parallel corpora mined by the NLLB project. This repository was reconstructed by AllenAI based on metadata released by the NLLB Project.
- [PHINC](https://zenodo.org/record/3605597#.YvjqEXZBy5d): A Parallel Hinglish Social Media Code-Mixed Corpus consisting of 13,738 code-mixed English-Hindi sentences and their corresponding translation in English. Described in [this paper](https://aclanthology.org/2020.wnut-1.7.pdf).
- [Sanskrit-Hindi-MT](https://github.com/priyanshu2103/Sanskrit-Hindi-Machine-Translation): Machine Translation from Sanskrit to Hindi using Unsupervised and Supervised Learning. Contains Sanskrit-English parallel data and Sanskrit-Hindi parallel(test) data.
- [Nepali National corpus]( http://catalog.elra.info/product_info.php?products_id=1217): The English-Nepali Parallel Corpus consists of a small set of data aligned at the sentence level with 27,060 English words and 21,756 Nepali words and a larger set of texts at the document level with 617,340 English words and 596,571 Nepali words. An additional set of monolingual data is also provided with 386,879 words in Nepali. Described [here](https://www.sketchengine.eu/nepali-national-corpus/).
- [Kathmandu University-English–Nepali Parallel Corpus](https://github.com/sharad461/nepali-translator): A parallel corpus of size 1.8 million sentence pairs for a low resource language pair Nepali–English. Described in [this paper](https://lt4all.elra.info/proceedings/lt4all2019/pdf/2019.lt4all-1.94.pdf).
- [CCAligned](https://statmt.org/cc-aligned/): A Massive Collection of more than 100 million cross-lingual web-document pairs in 137 languages aligned with English.

### <a name='ParallelTransliterationCorpus'></a>Parallel Transliteration Corpus

- [Dakshina Dataset](https://github.com/google-research-datasets/dakshina): The Dakshina dataset is a collection of text in both Latin and native scripts for 12 South Asian languages. Contains an aggregate of around 300k word pairs and 120k sentence pairs.
- [BrahmiNet Corpus](http://www.cfilt.iitb.ac.in/brahminet/static/download.html): 110 language pairs mined from ILCI parallel corpus.
- [Xlit-Crowd](https://github.com/anoopkunchukuttan/crowd-indic-transliteration-data): Hindi-English Transliteration Corpus created via crowdsourcing.
- [Xlit-IITB-Par](http://www.cfilt.iitb.ac.in/iitb_parallel/supplementary_resources/xlit-iitb-par.tgz): Hindi-English Transliteration Corpus mined from parallel translation corpora.
- [FIRE 2013 Track on Transliterated Search](https://cse.iitkgp.ac.in/resgrp/cnerg/qa/fire13translit/index.html): Transliteration dataset of native words in Hindi, Bengali and Gujarati.
- [NEWS 2018 Shared Task dataset](http://workshop.colips.org/news2018/dataset.html): Transliteration datasets for Kannada, Tamil, Bengali and Hindi created by Microsoft Research India.
- [AI4Bharat StoryWeaver Xlit Dataset](http://transliteration.ai4bharat.org/#/resources) - Transliteration datasets for Hindi, Maithili & Konkani
- [Hindi WikiData Transliteration Pairs](https://trigonaminima.github.io/2019/11/transliteration-wikidata/) - Hindi dataset (90k pairs)
- [NotAI-tech English-Telugu](https://github.com/notAI-tech/Datasets/tree/master/En-Te_Transliteration): Around 38k word pairs
- [AI4Bharat Aksharantar](https://ai4bharat.iitm.ac.in/aksharantar): The largest publicly available transliteration dataset for 21 Indic languages consisting of 26M Indic language-English transliteration pairs. Described in [this paper](https://arxiv.org/abs/2205.03018).

### <a name='TextualClassification'></a>Text Classification

- [BBC news articles classification dataset](https://github.com/NirantK/hindi2vec/releases/tag/bbc-hindi-v0.1): 14 class classification
- [iNLTK News Headlines classification](https://github.com/goru001/inltk): Datasets for multiple Indian languages.
- [AI4Bharat IndicNLP News Articles](https://github.com/ai4bharat/indicnlp_corpus): Word embeddings for 10 Indian languages.
- [KMI Linguistics TRAC - 1](https://github.com/kmi-linguistics/trac-1): Contains aggression-annotated dataset (in English and Hindi) for the Shared Task on Aggression Identification during First Workshop on Trolling, Aggression and Cyberbullying (TRAC - 1) at COLING - 2018.
- [XCOPA](https://github.com/cambridgeltl/xcopa): A Multilingual Dataset for Causal Commonsense Reasoning in 11 languages (includes Tamil). Described in [this paper](https://ducdauge.github.io/files/xcopa.pdf).

### <a name='TextualEntailment'></a>Textual Entailment/Natural Language Inference

- [XNLI corpus](https://github.com/facebookresearch/XNLI): Hindi and Urdu test sets and machine translated training sets (from English MultiNLI).
- [csebuetnlp Bangla NLI](https://huggingface.co/datasets/csebuetnlp/xnli_bn): A Natural Language Inference (NLI) dataset for Bengali. Described in [this paper](https://arxiv.org/abs/2101.00204).

### <a name='Paraphrase'></a> Paraphrase

- [Amrita University-DPIL Corpus](https://nlp.amrita.edu/dpil_cen/index.html): Sentence level paraphrase identification for four Indian languages (Tamil, Malayalam, Hindi and Punjabi).

### <a name='SentimentAnalysis'></a>Sentiment, Sarcasm, Emotion Analysis

- [IIT Bombay movie review datasets for Hindi and Marathi](http://www.cfilt.iitb.ac.in/Sentiment_Analysis_Resources.html)
- [IIT Patna movie review datasets for Hindi](http://www.iitp.ac.in/~ai-nlp-ml/resources.html)
- [IIIT-H LTRC Multi-domain dataset for Telugu](https://ltrc.iiit.ac.in/showfile.php?filename=downloads/sentiraama/)
- [ACTSA corpus for Telugu](https://github.com/NirantK/bharatNLP/releases)
- [BHAAV (भाव) Corpus](https://github.com/midas-research/bhaav): A Text Corpus for Emotion Analysis from Hindi Stories
- [SentiWordNet - SAIL](http://amitavadas.com/SAIL/il_res.html) - Hindi, Bangla, Tamil & Telugu
- [Dravidian-CodeMix - FIRE 2020](https://dravidian-codemix.github.io/2020/datasets.html) - Tamil & Malayalam
- [Bengali Sentiment Analysis - Classification Benchmark, 2020](https://github.com/rezacsedu/BengFastText): 8k sentences
- [SentNoB](https://github.com/KhondokerIslam/SentNoB): sentiment dataset for Bangla from 3 domains on user comments containing 15k examples [(Paper)](https://aclanthology.org/2021.findings-emnlp.278.pdf)  [(Dataset)](https://www.kaggle.com/cryptexcode/sentnob-sentiment-analysis-in-noisy-bangla-texts)
- [UoM-Sinhala Sentiment Analysis](https://github.com/LahiruSen/sinhala_sentiment_anlaysis_tallip#data-set): Sentiment Analysis for Sinhala Language. Consists of a multi-class annotated data set with 15059 sentiment annotated Sinhala news comments extracted from two Sinhala online news papers with four sentiment categories namely POSITIVE, NEGATIVE, NEUTRAL and CONFLICT and a corpus of 9.48 million tokens. Described in [this paper](https://arxiv.org/pdf/2011.07280.pdf).

### <a name='HateSpeech'></a>Hate Speech and Offensive Comments

- [Hate Speech and Offensive Content Identification in Indo-European Languages](https://hasocfire.github.io/hasoc/2020/dataset.html):  (HASOC FIRE-2020)
- [An Indian Language Social Media Collection for Hate and Offensive Speech, 2020](https://www.aclweb.org/anthology/2020.restup-1.2/): Hinglish Tweets and FB Comments collected during Parliamentary Election 2019 of India (Dataset available on request)
- [Aggression-annotated Corpus of Hindi-English Code-mixed Data, 2018](https://sites.google.com/view/trac1/shared-task): Scraped from Facebook (21k) & Twitter (18k) ([Paper](https://arxiv.org/abs/1803.09402))
- [Did You Offend Me? Classification of Offensive Tweets in Hinglish Language, 2018](https://github.com/pmathur5k10/Hinglish-Offensive-Text-Classification/tree/b8433ff1ebb885bd657f5117eab6bd3798f20408): 3k tweets ([Paper](https://www.aclweb.org/anthology/W18-5118))
- [A Dataset of Hindi-English Code-Mixed Social Media Text for Hate Speech Detection, 2018](https://github.com/punyajoy/HateSpeech-Hindi-English-Code-Mixed-Social-Media-Text): 4.5k Tweets ([Paper](https://www.aclweb.org/anthology/W18-1105))
- [Roman Urdu Offensive Language Detection, 2020](https://github.com/haroonshakeel/roman_urdu_hate_speech): 10k tweets, can also used for Hindi, ([Paper](https://www.aclweb.org/anthology/2020.emnlp-main.197))
- [Bengali Hate Speech - Classification Benchmark, 2020](https://github.com/rezacsedu/BengFastText): 1.5k sentences
- [Offensive Language Identification in Dravidian Languages, EACL 2021](https://dravidianlangtech.github.io/2021/): Tamil, Malayalam, Kannada
- [Fear Speech in Indian WhatsApp Groups, 2021](https://github.com/punyajoy/Fear-speech-analysis)
- [HateCheckHIn](https://github.com/hate-alert/HateCheckHIn): An evaluation dataset for Hindi Hate Speech Detection Models having a total of 34 functionalities out of which 28 functionalities are monolingual and the remaining 6 are multilingual. Hindi is used as the base language. Described in [this paper](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.575.pdf).

### <a name='QuestionAnswering'></a>Question Answering
- [Facebook Multilingual QA datasets](https://github.com/facebookresearch/MLQA): Contains dev and test sets for Hindi.
- [TyDi QA datasets](https://github.com/google-research-datasets/tydiqa): QA dataset for Bengali and Telugu.
- [bAbi 1.2 dataset](http://www.thespermwhale.com/jaseweston/babi/tasks_1-20_v1-2.tar.gz): Has Hindi version of bAbi tasks in romanized Hindi.
- [MMQA dataset](https://github.com/deepaknlp/MMQA): Hindi QA dataset described in [this paper](https://www.aclweb.org/anthology/L18-1440.pdf)
- [XQuAD](https://github.com/deepmind/xquad): testset for Hindi QA from human translation of subset of SQuAD v1.1. Described in [this paper](https://arxiv.org/abs/1910.11856)
- [XQA](http://github.com/thunlp/XQA): testset for Tamil QA. Described in [this paper](https://www.aclweb.org/anthology/P19-1227.pdf)
- [HindiRC](https://github.com/erzaliator/HindiRC-Data): A Dataset for Reading Comprehension in Hindi containing 127 questions and 24 passages. Described in [this paper](https://www.researchgate.net/publication/342424208_HindiRC_A_Dataset_for_Reading_Comprehension_in_Hindi)
- [IITH HiDG](https://github.com/kaushal0494/ZmBART): A Distractor Generation [Dataset](https://drive.google.com/drive/folders/1XlY9yOfk0XcfHNO5k0QGsbLQU1nMekG-) for Hindi consisting of 1k/1k/5k (train/validation/test) split. Described in [this paper](https://arxiv.org/pdf/2106.01597.pdf)
- [Chaii](https://www.kaggle.com/c/chaii-hindi-and-tamil-question-answering/overview) a Kaggle challenge which consists of 1104 Questions in Hindi and Tamil. Moreover, [here](https://www.kaggle.com/c/chaii-hindi-and-tamil-question-answering/discussion/264695) is a good collection of papers on multilingual Question Answering.
- [csebuetnlp Bangla QA](https://huggingface.co/datasets/csebuetnlp/squad_bn): A Question Answering (QA) dataset for Bengali. Described in [this paper](https://arxiv.org/abs/2101.00204).
- [XOR QA](https://github.com/AkariAsai/XORQA): A large-scale cross-lingual open-retrieval QA dataset (includes Bengali and Telugu) with 40k newly annotated open-retrieval questions that cover seven typologically diverse languages. Described in [this paper](https://arxiv.org/pdf/2010.11856.pdf). More information is available [here](https://nlp.cs.washington.edu/xorqa/).
- [IITB HiQuAD](https://www.cse.iitb.ac.in/~ganesh/HiQuAD/clqg/clqg_data.tar.gz): A question answering dataset in Hindi consisting of 6555 question-answer pairs. Described in [this paper](https://www.cse.iitb.ac.in/~ganesh/papers/acl2019a.pdf).

### <a name='Dialog'></a>Dialog
- [a-mma Indic Casual Dialogs Datasets](https://github.com/a-mma/indic_casual_dialogs_dataset)
- [A Code-Mixed Medical Task-Oriented Dialog Dataset](https://github.com/suman101112/Code-Mixed-TOD-Medical-Dataset): The dataset contains 3005 Telugu–English Code-Mixed dialogs with 29 k utterances covering ten specializations with an average code-mixing index (CMI) of 33.3%. Described in [this paper](https://www.sciencedirect.com/science/article/abs/pii/S0885230822000729).

### <a name='Discourse'></a>Discourse
- [MIDAS-Hindi Discourse Analysis](https://github.com/midas-research/hindi-discourse)

### <a name='InformationExtraction'></a>Information Extraction
- [EventXtract-IL](http://78.46.86.133/EventXtractionIL-FIRE2018): Event extraction for Tamil and Hindi. Described in [this paper](http://ceur-ws.org/Vol-2266/T5-1.pdf).
- [EDNIL-FIRE2020]https://ednilfire.github.io/ednil/2020/index.html): Event extraction for Tamil, Hindi, Bengali, Marathi, English. Described in [this paper](http://ceur-ws.org/Vol-2266/T5-1.pdf).
- [Amazon MASSIVE](https://github.com/alexa/massive): A Multilingual Amazon SLURP (SLU resource package) for Slot Filling, Intent Classification, and Virtual-Assistant Evaluation containing one million realistic, parallel, labeled virtual-assistant text utterances spanning 51 languages, 18 domains, 60 intents, and 55 slots. Described in [this paper](https://arxiv.org/abs/2204.08582).
- [Facebook - MTOP Benchmark](https://fb.me/mtop_dataset): A Comprehensive Multilingual Task-Oriented Semantic Parsing Benchmark with a dataset comprising of 100k annotated utterances in 6 languages(including Indic language: Hindi) across 11 domains. Described in [this paper](https://arxiv.org/pdf/2008.09335.pdf).

### <a name='POSTaggedcorpus'></a>POS Tagged corpus

- [Indian Language Corpora Initiative](http://sanskrit.jnu.ac.in/ilci/index.jsp)
- [Universal Dependencies](https://universaldependencies.org/)
- [IIITH Paninian Treebank](https://kcis.iiit.ac.in/LT/): POS annotations for hi, bn, kn, ml and mr.
- [Code Mixed Dataset for Hindi, Bengali and Telugu, ICON 2016 shared task](https://amitavadas.com/Code-Mixing.html)
- [JNU-BHLTR Bhojpuri Corpus](https://github.com/shashwatup9k/bho-resources/tree/master/mono-bho-corpus): Bhojpuri corpus of 5000 sentences.
- [KMI Magahi Corpus](https://github.com/kmi-linguistics/magahi): 
- [KMI Awadhi Corpus](https://github.com/kmi-linguistics/awadhi): 
- [Tham Khasi Corpus](http://catalog.elra.info/en-us/repository/browse/ELRA-W0321/#): An annotated Khasi POS tagged corpus containing 83,312 words, 4,386 sentences, 5,465 word types which amounts to 94,651 tokens (including punctuations).

### <a name='ChunkCorpus'></a>Chunk Corpus

- [Indian Language Corpora Initiative](http://sanskrit.jnu.ac.in/ilci/index.jsp)
- [Indian Languages Treebanking Project](https://ltrc.iiit.ac.in/showfile.php?filename=downloads/kolhi): Chunk annotations for hi, bn, kn, ml and mr.

### <a name='DependencyParseCorpus'></a>Dependency Parse Corpus

- [IIIT Hyderabad Hindi Treebank](http://tdil-dc.in/index.php?option=com_download&task=showresourceDetails&toolid=1977&lang=en)
- [Universal Dependencies](https://universaldependencies.org/)
- [Universal Dependencies Hindi Treebank](https://github.com/UniversalDependencies/UD_Hindi-HDTB)
- [Universal Dependencies Urdu Treebank](https://github.com/UniversalDependencies/UD_Urdu-UDTB)
- [IIITH Paninian Treebank](https://ltrc.iiit.ac.in/showfile.php?filename=downloads/kolhi): Paninian Grammar Framework annotations along with mappings to Stanford dependency annotations for hi, bn, kn, ml and mr.
- [Vedic Sanskrit Treebank](https://github.com/OliverHellwig/sanskrit/tree/master/papers/2020lrec): 4k Sanskrit dependency treebank [paper](https://www.aclweb.org/anthology/2020.lrec-1.632.pdf)

### <a name='CoreferenceCorpus'></a>Coreference Corpus

- [IIITH Coreference Anaphora Annotated Data](https://ltrc.iiit.ac.in/showfile.php?filename=downloads/kolhi/): Hindi
- [IIITH Coreference Annotated Data](https://ltrc.iiit.ac.in/showfile.php?filename=downloads/kolhi/): Hindi

### <a name='Summarization'></a>Summarization

- [XL-Sum](https://github.com/csebuetnlp/xl-sum): A Large-Scale Multilingual Abstractive Summarization for 44 Languages with a comprehensive and diverse dataset comprising of 1 million professionally annotated article-summary pairs from BBC. Described in [this paper](https://arxiv.org/abs/2106.13822).

### <a name='DatatoText'></a>Data to Text

- [XAlign](https://github.com/tushar117/XAlign): Cross-lingual Fact-to-Text Alignment and Generation for Low-Resource Languages comprising of a high quality XF2T dataset in 7 languages: Hindi, Marathi, Gujarati, Telugu, Tamil, Kannada, Bengali, and monolingual dataset in English. The dataset is available upon request. Described in [this paper](https://arxiv.org/abs/2202.00291).

## <a name='Models'></a>Models

### <a name='LIDModels'></a>Language Identification

- [NLLB-200](https://github.com/facebookresearch/fairseq/tree/nllb#lid-model): LID for 200 languages including 27 Indic languages.

### <a name='WordEmbeddings'></a>Word Embeddings

- [AI4Bharat IndicFT](https://ai4bharat.iitm.ac.in/indic-ft): Fast-text word embeddings for 11 Indian languages.
- [FastText CommonCrawl+Wikipedia](https://fasttext.cc/docs/en/crawl-vectors.html)
- [FastText Wikipedia](https://fasttext.cc/docs/en/pretrained-vectors.html)
- [Polyglot](https://sites.google.com/site/rmyeid/projects/polyglot)
- [EM-FT](http://catalog.elra.info/en-us/repository/browse/ELRA-W0316/): The first FastText word embedding available for Manipuri language trained on 1,880,035 Manipuri sentences.
- [Sanskrit-Hindi-MT](https://github.com/priyanshu2103/Sanskrit-Hindi-Machine-Translation): The FastText embeddings for Sanskrit is available [here](https://drive.google.com/file/d/1k5INFw9oaxV7yoWRg0qscmcFrOHVhdzW/view?usp=sharing) and for Hindi [here](https://drive.google.com/file/d/1Md9N7Ux2P9JCky1_9RgL2KjXRGb_lpXj/view?usp=sharing). 
- [UoM-Sinhala Sentiment Analysis- FastText 300](https://github.com/LahiruSen/sinhala_sentiment_anlaysis_tallip#word-embedding-models): The FastText word embedding model for Sinhala language. Described in [this paper](https://arxiv.org/pdf/2011.07280.pdf).

### <a name='PreTrainedLanguageModels'></a>Pre-trained Language Models

- [AI4Bharat IndicBERT](https://ai4bharat.iitm.ac.in/indic-bert): Multilingual ALBERT based embeddings spanning 12 languages for Natural Language Understanding (including Indian English).
- [AI4Bharat IndicBART](https://ai4bharat.iitm.ac.in/indic-bart): A multilingual,sequence-to-sequence pre-trained model based on the mBART architecture focusing on 11 Indic languages and English for Natural Language Generation of Indic Languages. Described in [this paper](https://arxiv.org/abs/2109.02903).
- [MuRIL](https://huggingface.co/google/muril-base-cased): Multilingual mBERT based embeddings spanning 17 languages and their transliterated counterparts for Natural Language Understanding [(paper)](https://arxiv.org/abs/2103.10730).
- [BERT Multilingual](https://github.com/google-research/bert): BERT model trained on Wikipedias of many languages (including major Indic languages).
- [mBART50](https://huggingface.co/facebook/mbart-large-50): seq2seq pre-trained model trained on CommonCrawl of many languages (including major Indic languages).
- [BLOOM](https://huggingface.co/bigscience/bloom): GPT3 like multilingual transformer-decoder language model (includes major Indic languages.
- [iNLTK](https://github.com/goru001/inltk): ULMFit and TransformerXL pre-trained embeddings for many languages trained on Wikipedia and some News articles. 
- [albert-base-sanskrit](https://huggingface.co/surajp/albert-base-sanskrit): ALBERT-based model trained on Sanskrit Wikipedia.
- [RoBERTa-hindi-guj-san](https://huggingface.co/surajp/RoBERTa-hindi-guj-san): Multilingual RoBERTa like model trained on Hindi, Sanskrit and Gujarati.
- [Bangla-BERT-Base](https://github.com/sagorbrur/bangla-bert): Bengali BERT model trained on Bengali wikipedia and OSCAR datasets.
- [BanglaBERT](https://github.com/csebuetnlp/banglabert): Language Model Pretraining and Benchmarks for Low-Resource Language Understanding Evaluation in Bangla. Described in [this paper](https://arxiv.org/abs/2101.00204).
- [EM-ALBERT](http://catalog.elra.info/en-us/repository/browse/ELRA-W0316/): The first ALBERT model available for Manipuri language which is trained on 1,034,715 Manipuri sentences.
- [LaBSE](https://tfhub.dev/google/LaBSE/2): Encoder models suitable for sentence retrieval tasks supporting 109 languages (including  all major Indic languages) [[paper]](https://arxiv.org/abs/2007.01852).
- [LASER3](https://github.com/facebookresearch/fairseq/tree/nllb#laser3-encoder-models): Encoder models suitable for sentence retrieval tasks supporting 200 languages (including 27 Indic languges).

### <a name='MultilingualWordEmbeddings'></a>Multilingual Word Embeddings

- [GeoMM](https://github.com/anoopkunchukuttan/geomm)
- [Babylon Partners](https://github.com/Babylonpartners/fastText_multilingual)

### <a name='Morphanalyzers'></a>Morphanalyzers

- [AI4Bharat IndicNLP Project](https://github.com/ai4bharat/indicnlp_corpus): Unsupervised morphanalyzers for 10 Indian languages learnt using morfessor.

### <a name='TranslationModels'></a>Translation Models

- [IndicTrans](https://ai4bharat.iitm.ac.in/indic-trans): Multilingual neural translation models for translation between English and 11 Indian languages. Supports translation between Indian langauges as well. A total of 110 translation directions are supported.
- [Shata-Anuvaadak](http://www.cfilt.iitb.ac.in/~moses/shata_anuvaadak/): SMT for 110 language pairs (all pairs between English and 10 Indian languages.
- [LTRC Vanee](https://ltrc.iiit.ac.in/downloads/tools/Vaanee.tgz): Dependency based Statistical MT system from English to Hindi.
- [NLLB-200](https://github.com/facebookresearch/fairseq/tree/nllb#open-sourced-models-and-community-integrations): Models for 200 languages including 27 Indic languages.

### <a name='TransliterationModels'></a>Transliteration Models

- [AI4Bharat IndicXlit](https://ai4bharat.iitm.ac.in/indic-xlit): A transformer-based multilingual transliteration model with 11M parameters for Roman to native script conversion and vice versa that supports 21 Indic languages. Described in [this paper](https://arxiv.org/abs/2205.03018).

### <a name='SpeechModels'></a>Speech Models

- [AI4Bharat IndicWav2Vec](https://ai4bharat.iitm.ac.in/indic-wav-2-vec): Multilingual pre-trained models for 40 Indian languages based on Wav2Vec 2.0.
- [Vakyansh CLSRIL-23](https://github.com/Open-Speech-EkStep/vakyansh-models): Pretrained wav2vec2 model trained on 10,000 hours of Speech data in 23 Indic Languages [(documentation)](https://open-speech-ekstep.github.io/) [(experimentation platform)](https://github.com/Open-Speech-EkStep/vakyansh-wav2vec2-experimentation).
- [arijitx/wav2vec2-large-xlsr-bengali](https://huggingface.co/arijitx/wav2vec2-large-xlsr-bengali): Pretrained wav2vec2-large-xlsr trained on ~50 hrs(40,000 utterances) of OpenSLR Bengali data. Test WER 32.45% without LM.

### <a name='NER'></a>NER

- [AI4Bharat IndicNER](https://huggingface.co/ai4bharat/IndicNER): NER model for 11 Indic languages.
- [AsNER](https://arxiv.org/ftp/arxiv/papers/2207/2207.03422.pdf): A Baseline Assamese NER model.
- [L3Cube-MahaNER-BERT](https://huggingface.co/l3cube-pune/marathi-ner): A 752 million token multilingual BERT model. Described in [this paper](http://www.lrec-conf.org/proceedings/lrec2022/workshops/WILDRE6/pdf/2022.wildre6-1.6.pdf).
- [CFILT HiNER](https://github.com/cfiltnlp/hiner#models): Hindi NER models trained on CFILT HiNER dataset. Described in [this paper](https://arxiv.org/abs/2204.13743).

## <a name='SpeechCorpora'></a>Speech Corpora

- [Microsoft Speech Corpus](https://msropendata.com/datasets/7230b4b1-912d-400e-be58-f84e0512985e): Speech corpus for Telugu, Tamil and Gujarati.
- [Microsoft-IITB Marathi Speech Corpus](https://www.cse.iitb.ac.in/~pjyothi/indiccorpora/#marathi): 109 hours of speech data collected via crowdsourcing.
- [AccentDB](https://accentdb.org/): Database of Indian English accents from native speakers in Bangla, Malayalam, Telugu and Oriya. 
- [IIT Madras TTS database](https://www.iitm.ac.in/donlab/tts/index.php)
- [BABEL Speech Corpus](https://en.wikipedia.org/wiki/BABEL_Speech_Corpus): includes some Indian languages
- [WikiPron](https://pypi.org/project/wikipron/): Words and their pronunciations in IPA mined from Wiktionary. Includes Indian languages. [paper](https://www.aclweb.org/anthology/2020.lrec-1.521)
- [CVIT IndicSpeech](http://cvit.iiit.ac.in/research/projects/cvit-projects/text-to-speech-dataset-for-indian-languages): TTS data for 3 Indian languages: Malayalam, Bengali and Hindi (24 hours each).
- [Google Speech Corpus](http://www.openslr.org/resources.php): TTS data for 6 Indian languages: Malayalam, Marathi, Telugu, Kannada, Gujarati, Tamil (upto 9 hours each). Resources SLR#63-#66, #78-#79. [(paper)](http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.800.pdf)
- [CoVoST 2](https://github.com/facebookresearch/covost): Tamil 2 hrs data
- [SMC Malayalam Speech Corpus](https://blog.smc.org.in/malayalam-speech-corpus/) - [Download link](https://releases.smc.org.in/msc-reviewed-speech/)
- [Vāksañcayaḥ Sanskrit Speech Corpus](https://github.com/cyfer0618/Vaksanca) : 78 hours of speech corpus in Sanskrit prose, with a speaker disjoint splits of train, dev and test. It also contains an additional out of domain test data with speakers having pronunciation influences from L1 [(paper)](https://arxiv.org/abs/2106.05852).
- [IISc-MILE Kannada ASR Corpus](http://www.openslr.org/126/): Transcribed speech corpus containing ~350 hours of read speech data for training ASR systems for Kannada language. Described in [this paper](https://arxiv.org/abs/2207.13331).
- [IISc-MILE Tamil ASR Corpus](http://www.openslr.org/127/): Transcribed speech corpus containing ~150 hours of read speech data for training ASR systems for Tamil language. Described in [this paper](https://arxiv.org/abs/2207.13331).
- [MUCS 2021 Dataset](https://navana-tech.github.io/MUCS2021/data.html): (Gujarati, Hindi, Marathi, Odia, Tamil, Telugu) Multilingual and Code-Switching ASR Challenges for Low Resource Indian Languages 
- [Gramvaani](https://sites.google.com/view/gramvaaniasrchallenge/dataset): 100 hours of labelled data and 1000 hours of pretraining data for Hindi
- [Kashmiri Data Corpus](https://www.openslr.org/122/): Collection of transcribed Kashmiri recordings taken from native speakers
- [Hindi-Tamil-English ASR Challenge](https://sites.google.com/view/indian-language-asrchallenge/home): 490 hours of transcribed speeech data in three Indian Languages
- [Large Sinhala ASR training data set](http://openslr.org/52): Sinhala ASR training data set containing ~185K utterances
- [Large Bengali ASR training data set](http://openslr.org/53): Bengali ASR training data set containing ~196K utterances
- [Large Nepali ASR training data set](http://openslr.org/54): Nepali ASR training data set containing ~157K utterances
- [Crowdsourced high-quality Gujarati multi-speaker speech data set](https://www.openslr.org/78/): Contains recordings of native speakers of Gujarati
- [Crowdsourced high-quality Kannada multi-speaker speech data set](https://www.openslr.org/79/): Contains recordings of native speakers of Kannada
- [Crowdsourced high-quality Malayalam multi-speaker speech data set](https://www.openslr.org/63/): Contains recordings of native speakers of Malayalam
- [Crowdsourced high-quality Marathi multi-speaker speech data set](https://www.openslr.org/64/): Contains recordings of native speakers of Marathi
- [Crowdsourced high-quality Tamil multi-speaker speech data set](https://www.openslr.org/65/): Contains recordings of native speakers of Tamil
- [Crowdsourced high-quality Telugu multi-speaker speech data set](https://www.openslr.org/66/): Contains recordings of native speakers of Telugu
- [Nepali National corpus](http://catalog.elra.info/product_info.php?products_id=1219): The Nepali Spoken Corpus contains audio recordings from different 17 types of social activities with a total temporal recording duration of 31 hours and 26 minutes. Described [here](https://www.sketchengine.eu/nepali-national-corpus/).
- [Shrutilipi](https://ai4bharat.org/shrutilipi): Over 6400 hours of transcribed speech corpus across 12 Indian languages: Bengali, Gujarati, Hindi, Kannada, Malayalam, Marathi, Odia, Punjabi, Sanskrit, Tamil, Telugu, Urdu


## <a name='OCRCorpora'></a>OCR Corpora

- [Kannada MNIST](https://www.kaggle.com/higgstachyon/kannada-mnist) ([Paper](
http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.800.pdf))
- [Devanagari MNIST](https://www.kaggle.com/ashokpant/devanagari-character-dataset-large)
- [SynthTextHindi](https://github.com/IngleJaya95/SynthTextHindi) ([Dataset link](https://ai4bharat.org/articles/sign-board))

## <a name='MultimodalCorpora'></a>Multimodal Corpora

- [English-Hindi Visual Genome](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2997): Images captioned in both English and Hindi.
- [English-Hindi Flickr 8k](https://arxiv.org/pdf/2004.11954.pdf): A subset of images from [Flickr8k](https://jair.org/index.php/jair/article/view/10833) images captioned by native speakers in both English and Hindi. Code and data available [here](https://github.com/madaan/PML4DC-Comparable-Data-Collection).

## <a name='LanguageSpecificCatalogs'></a>Language Specific Catalogs 

 Pointers to language-specific NLP resource catalogs
 
 - [Nepali](https://github.com/amitness/ml-datasets)
 - [Odia](https://github.com/shantipriyap/Odia-NLP-Resource-Catalog)
 - [Tamil](https://narvidhai.github.io/tamil-nlp-catalog/)
 - [Sinhala](https://lknlp.github.io): [[git repo]](https://github.com/lknlp/lknlp.github.io)
 - [Urdu](https://github.com/urduhack/awesome-urdu)
