# Nlp with Ruby Overview

Curated List: Practical Natural Language Processing done in Ruby

[🏠 Home](/README.md) · [🔥 Feed](https://test.trackawesomelist.com/arbox/nlp-with-ruby/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 arbox/nlp-with-ruby](https://github.com/arbox/nlp-with-ruby/blob/master/readme.md) · ⭐ 966 · 🏷️ Computer Science

[ [Daily](/content/arbox/nlp-with-ruby/README.md) / [Weekly](/content/arbox/nlp-with-ruby/week/README.md) / Overview ]

---

<img src="https://github.com/arbox/nlp-with-ruby/raw/master/header.png" align="center">

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme) [![Support Me](https://img.shields.io/badge/%F0%9F%92%97-Support%20Me-blue.svg?style=flat-square)](https://www.patreon.com/arbox)

\[[RubyML](https://github.com/arbox/machine-learning-with-ruby) |
[RubyDataScience](https://github.com/arbox/data-science-with-ruby) |
[RubyInterop](https://github.com/arbox/ruby-interoperability)]

# Awesome NLP with Ruby [<img src="https://github.com/arbox/nlp-with-ruby/raw/master/ruby.jpg" align="left" width="30px" height="30px" />][ruby]

> Useful resources for text processing in Ruby

This curated list comprises [*awesome*](https://github.com/sindresorhus/awesome/blob/master/awesome.md)
resources, libraries, information sources about computational processing of texts
in human languages with the [Ruby programming language](https://github.com/arbox/nlp-with-ruby/blob/master/readme.md/ruby).
That field is often referred to as
[NLP](https://en.wikipedia.org/wiki/Natural_language_processing),
[Computational Linguistics](https://en.wikipedia.org/wiki/Computational_linguistics),
[HLT](https://en.wikipedia.org/wiki/Language_technology) (Human Language Technology)
and can be brought in conjunction with
[Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence),
[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning),
[Information Retrieval](https://en.wikipedia.org/wiki/Information_retrieval),
[Text Mining](https://en.wikipedia.org/wiki/Text_mining),
[Knowledge Extraction](https://en.wikipedia.org/wiki/Knowledge_extraction)
and other related disciplines.

This list comes from our day to day work on Language Models and NLP Tools.
Read [why](https://github.com/arbox/nlp-with-ruby/blob/master/readme.md/motivation.md) this list is awesome. Our [FAQ](https://github.com/arbox/nlp-with-ruby/blob/master/readme.md/FAQ.md) describes the
important decisions and useful answers you may be interested in.

:sparkles: Every [contribution](#contributing) is welcome! Add links through pull
requests or create an issue to start a discussion.

Follow us on [Twitter](https://twitter.com/NonWebRuby)
and please spread the word using the `#RubyNLP` hash tag!

<!-- nodoc -->

## Contents

<!-- toc -->

*   [:sparkles: Tutorials](#sparkles-tutorials)
*   [NLP Pipeline Subtasks](#nlp-pipeline-subtasks)
    *   [Pipeline Generation](#pipeline-generation)
    *   [Multipurpose Engines](#multipurpose-engines)
        *   [On-line APIs](#on-line-apis)
    *   [Language Identification](#language-identification)
    *   [Segmentation](#segmentation)
    *   [Lexical Processing](#lexical-processing)
        *   [Stemming](#stemming)
        *   [Lemmatization](#lemmatization)
        *   [Lexical Statistics: Counting Types and Tokens](#lexical-statistics-counting-types-and-tokens)
        *   [Filtering Stop Words](#filtering-stop-words)
    *   [Phrasal Level Processing](#phrasal-level-processing)
    *   [Syntactic Processing](#syntactic-processing)
        *   [Constituency Parsing](#constituency-parsing)
    *   [Semantic Analysis](#semantic-analysis)
    *   [Pragmatical Analysis](#pragmatical-analysis)
*   [High Level Tasks](#high-level-tasks)
    *   [Spelling and Error Correction](#spelling-and-error-correction)
    *   [Text Alignment](#text-alignment)
    *   [Machine Translation](#machine-translation)
    *   [Sentiment Analysis](#sentiment-analysis)
    *   [Numbers, Dates, and Time Parsing](#numbers-dates-and-time-parsing)
    *   [Named Entity Recognition](#named-entity-recognition)
    *   [Text-to-Speech-to-Text](#text-to-speech-to-text)
*   [Dialog Agents, Assistants, and Chatbots](#dialog-agents-assistants-and-chatbots)
*   [Linguistic Resources](#linguistic-resources)
*   [Machine Learning Libraries](#machine-learning-libraries)
*   [Data Visualization](#data-visualization)
*   [Optical Character Recognition](#optical-character-recognition)
*   [Text Extraction](#text-extraction)
*   [Full Text Search, Information Retrieval, Indexing](#full-text-search-information-retrieval-indexing)
*   [Language Aware String Manipulation](#language-aware-string-manipulation)
*   [Articles, Posts, Talks, and Presentations](#articles-posts-talks-and-presentations)
*   [Projects and Code Examples](#projects-and-code-examples)
*   [Books](#books)
*   [Community](#community)
*   [Needs your Help!](#needs-your-help)
*   [Related Resources](#related-resources)
*   [License](#license)

<!-- tocstop -->

<!-- doc -->

## :sparkles: Tutorials

Please help us to fill out this section! :smiley:

## NLP Pipeline Subtasks

An NLP Pipeline starts with a plain text.

### Pipeline Generation

*   [composable\_operations](https://github.com/t6d/composable_operations) -
    Definition framework for operation pipelines.
*   [ruby-spark](https://github.com/ondra-m/ruby-spark) -
    Spark bindings with an easy to understand DSL.
*   [phobos](https://github.com/phobos/phobos) -
    Simplified Ruby Client for [Apache Kafka](https://kafka.apache.org/).
*   [parallel](https://github.com/grosser/parallel) -
    Supervisor for parallel execution on multiple CPUs or in many threads.
*   [pwrake](https://github.com/masa16/pwrake) -
    Rake extensions to run local and remote tasks in parallel.

### Multipurpose Engines

*   [open-nlp](https://github.com/louismullie/open-nlp) -
    Ruby Bindings for the [OpenNLP](https://opennlp.apache.org/) Toolkit.
*   [stanford-core-nlp](https://github.com/louismullie/stanford-core-nlp) -
    Ruby Bindings for the Stanford [CoreNLP](https://github.com/stanfordnlp/CoreNLP) tools.
*   [treat](https://github.com/louismullie/treat) -
    Natural Language Processing framework for Ruby (like [NLTK](http://www.nltk.org/) for Python).
*   [nlp\_toolz](https://github.com/LeFnord/nlp_toolz) -
    Wrapper over some [OpenNLP](https://opennlp.apache.org/) classes and
    the original [Berkeley Parser](https://github.com/slavpetrov/berkeleyparser).
*   [open\_nlp](https://github.com/hck/open_nlp) -
    JRuby Bindings for the [OpenNLP](https://opennlp.apache.org/) Toolkit.
*   [ruby-spacy](https://github.com/yohasebe/ruby-spacy) —
    Wrapper module for spaCy NLP library via [PyCall](https://github.com/mrkn/pycall.rb).

#### On-line APIs

*   [alchemyapi\_ruby](https://github.com/alchemyapi/alchemyapi_ruby) -
    Legacy Ruby SDK for AlchemyAPI/Bluemix.
*   [wit-ruby](https://github.com/wit-ai/wit-ruby) -
    Ruby client library for the [Wit.ai](https://wit.ai/) Language Understanding Platform.
*   [wlapi](https://github.com/arbox/wlapi) - Ruby client library for
    [Wortschatz Leipzig](http://wortschatz.uni-leipzig.de/de) web services.
*   [monkeylearn-ruby](https://github.com/monkeylearn/monkeylearn-ruby) - Sentiment
    Analysis, Topic Modelling, Language Detection, Named Entity Recognition via
    a Ruby based Web API client.
*   [google-cloud-language](https://github.com/googleapis/google-cloud-ruby/tree/master/google-cloud-language) -
    Google's Natural Language service API for Ruby.

### Language Identification

Language Identification is one of the first crucial steps in every NLP Pipeline.

*   [scylla](https://github.com/hashwin/scylla) -
    Language Categorization and Identification.

### Segmentation

Tools for Tokenization, Word and Sentence Boundary Detection and Disambiguation.

*   [tokenizer](https://github.com/arbox/tokenizer) -
    Simple multilingual tokenizer. <sup>\[[tutorial](https://github.com/arbox/nlp-with-ruby/blob/master/readme.md/tutorials/tokenizer.md)]</sup>
*   [pragmatic\_tokenizer](https://github.com/diasks2/pragmatic_tokenizer) -
    Multilingual tokenizer to split a string into tokens.
*   [nlp-pure](https://github.com/parhamr/nlp-pure) -
    Natural language processing algorithms implemented in pure Ruby with minimal dependencies.
*   [textoken](https://github.com/manorie/textoken) -
    Simple and customizable text tokenization library.
*   [pragmatic\_segmenter](https://github.com/diasks2/pragmatic_segmenter) -
    Word Boundary Disambiguation with many cookies.
*   [punkt-segmenter](https://github.com/lfcipriani/punkt-segmenter) -
    Pure Ruby implementation of the Punkt Segmenter.
*   [tactful\_tokenizer](https://github.com/zencephalon/Tactful_Tokenizer) -
    RegExp based tokenizer for different languages.
*   [scapel](https://github.com/louismullie/scalpel) -
    Sentence Boundary Disambiguation tool.

### Lexical Processing

#### Stemming

Stemming is the term used in information retrieval to describe the process for
reducing wordforms to some base representation. Stemming should be distinguished
from [Lemmatization](#lemmatization) since `stems` are not necessarily have
linguistic motivation.

*   [ruby-stemmer](https://github.com/aurelian/ruby-stemmer) -
    Ruby-Stemmer exposes the SnowBall API to Ruby.
*   [uea-stemmer](https://github.com/ealdent/uea-stemmer) -
    Conservative stemmer for search and indexing.

#### Lemmatization

Lemmatization is considered a process of finding a base form of a word. Lemmas
are often collected in dictionaries.

*   [lemmatizer](https://github.com/yohasebe/lemmatizer) -
    WordNet based Lemmatizer for English texts.

#### Lexical Statistics: Counting Types and Tokens

*   [wc](https://github.com/thesp0nge/wc) -
    Facilities to count word occurrences in a text.
*   [word\_count](https://github.com/AtelierConvivialite/word_count) -
    Word counter for `String` and `Hash` objects.
*   [words\_counted](https://github.com/abitdodgy/words_counted) -
    Pure Ruby library counting word statistics with different custom options.

#### Filtering Stop Words

*   [stopwords-filter](https://github.com/brenes/stopwords-filter) - Filter and
    Stop Word Lexicon based on the SnowBall lemmatizer.

### Phrasal Level Processing

*   [n\_gram](https://github.com/reddavis/N-Gram) -
    N-Gram generator.
*   [ruby-ngram](https://github.com/tkellen/ruby-ngram) -
    Break words and phrases into ngrams.
*   [raingrams](https://github.com/postmodern/raingrams) -
    Flexible and general-purpose ngrams library written in pure Ruby.

### Syntactic Processing

#### Constituency Parsing

*   [stanfordparser](https://rubygems.org/gems/stanfordparser) -
    Ruby based wrapper for the Stanford Parser.
*   [rley](https://github.com/famished-tiger/Rley) -
    Pure Ruby implementation of the [Earley](https://en.wikipedia.org/wiki/Earley_parser)
    Parsing Algorithm for Context-Free Constituency Grammars.
*   [rsyntaxtree](https://github.com/yohasebe/rsyntaxtree) -
    Visualization for syntactic trees in Ruby based on [RMagick](https://github.com/rmagick/rmagick). <sup>\[dep: [ImageMagick](#imagemagick)]</sup>

### Semantic Analysis

*   [amatch](https://github.com/flori/amatch) -
    Set of five distance types between strings (including Levenshtein, Sellers, Jaro-Winkler, 'pair distance').
*   [damerau-levenshtein](https://github.com/GlobalNamesArchitecture/damerau-levenshtein) -
    Calculates edit distance using the Damerau-Levenshtein algorithm.
*   [hotwater](https://github.com/colinsurprenant/hotwater) -
    Fast Ruby FFI string edit distance algorithms.
*   [levenshtein-ffi](https://github.com/dbalatero/levenshtein-ffi) -
    Fast string edit distance computation, using the Damerau-Levenshtein algorithm.
*   [tf\_idf](https://github.com/reddavis/TF-IDF) -
    Term Frequency / Inverse Document Frequency in pure Ruby.
*   [tf-idf-similarity](https://github.com/jpmckinney/tf-idf-similarity) -
    Calculate the similarity between texts using TF/IDF.

### Pragmatical Analysis

*   [SentimentLib](https://github.com/nzaillian/sentiment_lib) -
    Simple extensible sentiment analysis gem.

## High Level Tasks

### Spelling and Error Correction

*   [gingerice](https://github.com/subosito/gingerice) -
    Spelling and Grammar corrections via the [Ginger](https://www.gingersoftware.com/) API.
*   [hunspell-i18n](https://github.com/romanbsd/hunspell) -
    Ruby bindings to the standard [Hunspell](https://hunspell.github.io/) Spell Checker.
*   [ffi-hunspell](https://github.com/postmodern/ffi-hunspell) -
    FFI based Ruby bindings for [Hunspell](https://hunspell.github.io/).
*   [hunspell](https://github.com/segabor/Hunspell) -
    Ruby bindings to [Hunspell](https://hunspell.github.io/) via Ruby C API.

### Text Alignment

*   [alignment](https://github.com/povilasjurcys/alignment) -
    Alignment routines for bilingual texts (Gale-Church implementation).

### Machine Translation

*   [google-api-client](https://github.com/googleapis/google-api-ruby-client) -
    Google API Ruby Client.
*   [microsoft\_translator](https://github.com/ikayzo/microsoft_translator) -
    Ruby client for the microsoft translator API.
*   [termit](https://github.com/pawurb/termit) -
    Google Translate with speech synthesis in your terminal.
*   [zipf](https://github.com/pks/zipf) -
    implementation of BLEU and other base algorithms.

### Sentiment Analysis

*   [stimmung](https://github.com/pachacamac/stimmung) -
    Semantic Polarity based on the
    [SentiWS](http://wortschatz.uni-leipzig.de/en/download) lexicon.

### Numbers, Dates, and Time Parsing

*   [chronic](https://github.com/mojombo/chronic) -
    Pure Ruby natural language date parser.
*   [chronic\_between](https://github.com/jrobertson/chronic_between) -
    Simple Ruby natural language parser for date and time ranges.
*   [chronic\_duration](https://github.com/henrypoydar/chronic_duration) -
    Pure Ruby parser for elapsed time.
*   [kronic](https://github.com/xaviershay/kronic) -
    Methods for parsing and formatting human readable dates.
*   [nickel](https://github.com/iainbeeston/nickel) -
    Extracts date, time, and message information from naturally worded text.
*   [tickle](https://github.com/yb66/tickle) -
    Parser for recurring and repeating events.
*   [numerizer](https://github.com/jduff/numerizer) -
    Ruby parser for English number expressions.

### Named Entity Recognition

*   [ruby-ner](https://github.com/mblongii/ruby-ner) -
    Named Entity Recognition with Stanford NER and Ruby.
*   [ruby-nlp](https://github.com/tiendung/ruby-nlp) -
    Ruby Binding for Stanford Pos-Tagger and Name Entity Recognizer.

### Text-to-Speech-to-Text

*   [espeak-ruby](https://github.com/dejan/espeak-ruby) -
    Small Ruby API for utilizing 'espeak' and 'lame' to create text-to-speech mp3 files.
*   [tts](https://github.com/c2h2/tts) -
    Text-to-Speech conversion using the Google translate service.
*   [att\_speech](https://github.com/adhearsion/att_speech) -
    Ruby wrapper over the AT\&T Speech API for speech to text.
*   [pocketsphinx-ruby](https://github.com/watsonbox/pocketsphinx-ruby) -
    Pocketsphinx bindings.

## Dialog Agents, Assistants, and Chatbots

*   [chatterbot](https://github.com/muffinista/chatterbot) -
    Straightforward ruby-based Twitter Bot Framework, using OAuth to authenticate.
*   [lita](https://github.com/litaio/lita) -
    Highly extensible chat operation bot framework written with persistent storage on [Redis](https://redis.io/).

## Linguistic Resources

*   [rwordnet](https://github.com/doches/rwordnet) -
    Pure Ruby self contained API library for the [Princeton WordNet®](https://wordnet.princeton.edu/).
*   [wordnet](https://github.com/ged/ruby-wordnet/blob/master/README.rdoc) -
    Performance tuned bindings for the [Princeton WordNet®](https://wordnet.princeton.edu/).

## Machine Learning Libraries

[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning) Algorithms
in pure Ruby or written in other programming languages with appropriate bindings
for Ruby.

For more up-to-date list please look at the [Awesome ML with Ruby][ml-with-ruby] list.

*   [rb-libsvm](https://github.com/febeling/rb-libsvm) -
    Support Vector Machines with Ruby.
*   [weka](https://github.com/paulgoetze/weka-jruby) -
    JRuby bindings for Weka, different ML algorithms implemented through Weka.
*   [decisiontree](https://github.com/igrigorik/decisiontree) -
    Decision Tree ID3 Algorithm in pure Ruby <sup>\[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>.
*   [rtimbl](https://github.com/maspwr/rtimbl) -
    Memory based learners from the Timbl framework.
*   [classifier-reborn](https://github.com/jekyll/classifier-reborn) -
    General classifier module to allow Bayesian and other types of classifications.
*   [lda-ruby](https://github.com/ealdent/lda-ruby) -
    Ruby implementation of the [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)
    (Latent Dirichlet Allocation) for automatic Topic Modelling and Document Clustering.
*   [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) -
    Ruby interface to LIBLINEAR (much more efficient than LIBSVM for text classification).
*   [linnaeus](https://github.com/djcp/linnaeus) -
    Redis-backed Bayesian classifier.
*   [maxent\_string\_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) -
    JRuby maximum entropy classifier for string data, based on the OpenNLP Maxent framework.
*   [naive\_bayes](https://github.com/reddavis/Naive-Bayes) -
    Simple Naive Bayes classifier.
*   [nbayes](https://github.com/oasic/nbayes) -
    Full-featured, Ruby implementation of Naive Bayes.
*   [omnicat](https://github.com/mustafaturan/omnicat) -
    Generalized rack framework for text classifications.
*   [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) -
    Naive Bayes text classification implementation as an OmniCat classifier strategy.
*   [ruby-fann](https://github.com/tangledpath/ruby-fann) -
    Ruby bindings to the [Fast Artificial Neural Network Library (FANN)](http://leenissen.dk/fann/wp/).
*   [rblearn](https://github.com/himkt/rblearn) - Feature Extraction and Crossvalidation library.

## Data Visualization

Please refer to the [Data Visualization](https://github.com/arbox/data-science-with-ruby#visualization)
section on the [Data Science with Ruby][ds-with-ruby] list.

## Optical Character Recognition

*   [tesseract-ocr](https://github.com/meh/ruby-tesseract-ocr) -
    FFI based wrapper over the [Tesseract OCR Engine](https://github.com/tesseract-ocr/tesseract).

## Text Extraction

*   [yomu](https://github.com/yomurb/yomu) -
    library for extracting text and metadata from files and documents
    using the [Apache Tika](https://tika.apache.org/) content analysis toolkit.

## Full Text Search, Information Retrieval, Indexing

*   [rsolr](https://github.com/rsolr/rsolr) -
    Ruby and Rails client library for [Apache Solr](http://lucene.apache.org/solr/).
*   [sunspot](https://github.com/sunspot/sunspot) -
    Rails centric client for [Apache Solr](http://lucene.apache.org/solr/).
*   [thinking-sphinx](https://github.com/pat/thinking-sphinx) -
    [Active Record](https://guides.rubyonrails.org/active_record_basics.html)
    plugin for using [Sphinx](http://sphinxsearch.com/) in (not only) Rails based projects.
*   [elasticsearch](https://github.com/elastic/elasticsearch-ruby/tree/master/elasticsearch) -
    Ruby client and API for [Elasticsearch](https://www.elastic.co/).
*   [elasticsearch-rails](https://github.com/elastic/elasticsearch-rails) -
    Ruby and Rails integrations for [Elasticsearch](https://www.elastic.co/).
*   [google-api-client](https://github.com/googleapis/google-api-ruby-client) -
    Ruby API library for [Google](https://developers.google.com/api-client-library/ruby/) services.

## Language Aware String Manipulation

Libraries for language aware string manipulation, i.e. search, pattern matching,
case conversion, transcoding, regular expressions which need information about
the underlying language.

*   [fuzzy\_match](https://github.com/seamusabshere/fuzzy_match) -
    Fuzzy string comparison with Distance measures and Regular Expression.
*   [fuzzy-string-match](https://github.com/kiyoka/fuzzy-string-match) -
    Fuzzy string matching library for Ruby.
*   [active\_support](https://github.com/rails/rails/tree/master/activesupport/lib/active_support) -
    RoR `ActiveSupport` gem has various string extensions that can handle case.
*   [fuzzy\_tools](https://github.com/brianhempel/fuzzy_tools) -
    Toolset for fuzzy searches in Ruby tuned for accuracy.
*   [u](http://disu.se/software/u-1.0/) -
    U extends Ruby’s Unicode support.
*   [unicode](https://github.com/blackwinter/unicode) -
    Unicode normalization library.
*   [CommonRegexRuby](https://github.com/talyssonoc/CommonRegexRuby) -
    Find a lot of kinds of common information in a string.
*   [regexp-examples](https://github.com/tom-lord/regexp-examples) -
    Generate strings that match a given regular expression.
*   [verbal\_expressions](https://github.com/ryan-endacott/verbal_expressions) -
    Make difficult regular expressions easy.
*   [translit\_kit](https://github.com/AnalyzePlatypus/TranslitKit) -
    Transliterate Hebrew & Yiddish text into Latin characters.
*   [re2](https://github.com/mudge/re2) -
    hight-speed Regular Expression library for Text Mining and Text Extraction.
*   [regex\_sample](https://github.com/mochizukikotaro/regex_sample) -
    sample string generation from a given Regular Expression.
*   [iuliia](https://github.com/adnikiforov/iuliia-rb) —
    transliteration Cyrillic to Latin in many possible ways (defined by the [reference implementation](https://github.com/nalgeon/iuliia)).

## Articles, Posts, Talks, and Presentations

*   2019
    *   *Extracting Text From Images Using Ruby* by [aonemd](https://twitter.com/aonemd) <sup>\[[post](https://aonemd.github.io/blog/extracting-text-from-images-using-ruby) |
        [code](https://gist.github.com/aonemd/7bb3c4760d9e47a9ce8e270198cb40a0)]</sup>
*   2018
    *   *Natural Language Processing and Tweet Sentiment Analysis* by [Cassandra Corrales](https://twitter.com/casita305) <sup>\[[post](https://medium.com/@cmcorrales3/natural-language-processing-and-tweet-sentiment-analysis-fa1edbb5ddd5)]</sup>
*   2017
    *   *The Google NLP API Meets Ruby* by [Aja Hammerly](https://twitter.com/the_thagomizer) <sup>\[[post](http://www.thagomizer.com/blog/2017/04/13/the-google-nlp-api-meets-ruby.html)]</sup>
    *   *Syntax Isn't Everything: NLP For Rubyists* by [Aja Hammerly](https://twitter.com/the_thagomizer) <sup>\[[slides](http://www.thagomizer.com/files/NLP_RailsConf2017.pdf)]</sup>
    *   *Scientific Computing on JRuby* by [Prasun Anand](https://twitter.com/prasun_anand) <sup>\[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) |
        [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) |
        [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) |
        [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)]</sup>
    *   *Unicode Normalization in Ruby* by [Starr Horne](https://twitter.com/starrhorne) <sup>\[[post](https://blog.honeybadger.io/ruby_unicode_normalization/)]</sup>
*   2016
    *   *Quickly Create a Telegram Bot in Ruby* by [Ardian Haxha](https://twitter.com/ArdianHaxha) <sup>\[[tutorial](https://www.sitepoint.com/quickly-create-a-telegram-bot-in-ruby/)]</sup>
    *   *Deep Learning: An Introduction for Ruby Developers* by [Geoffrey Litt](https://twitter.com/geoffreylitt) <sup>\[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)]</sup>
    *   *How I made a pure-Ruby word2vec program more than 3x faster* by [Kei Sawada](https://twitter.com/remore) <sup>\[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)]</sup>
    *   *Dōmo arigatō, Mr. Roboto: Machine Learning with Ruby* by [Eric Weinstein](https://twitter.com/ericqweinstein) <sup>\[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) | [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)]</sup>
*   2015
    *   *N-gram Analysis for Fun and Profit* by [Jesus Castello](https://github.com/matugm) <sup>\[[tutorial](https://www.rubyguides.com/2015/09/ngram-analysis-ruby/)]</sup>
    *   *Machine Learning made simple with Ruby* by [Lorenzo Masini](https://github.com/rugginoso) <sup>\[[tutorial](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
    *   *Using Ruby Machine Learning to Find Paris Hilton Quotes* by [Rick Carlino](https://github.com/RickCarlino) <sup>\[[tutorial](http://web.archive.org/web/20160414072324/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>
    *   *Exploring Natural Language Processing in Ruby* by [Kevin Dias](https://github.com/diasks2) <sup>\[[slides](https://www.slideshare.net/diasks2/exploring-natural-language-processing-in-ruby)]</sup>
    *   *Machine Learning made simple with Ruby* by [Lorenzo Masini](https://twitter.com/rugginoso) <sup>\[[post](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
    *   *Practical Data Science in Ruby* by Bobby Grayson <sup>\[[slides](http://slides.com/bobbygrayson/p#/)]</sup>
*   2014
    *   *Natural Language Parsing with Ruby* by [Glauco Custódio](https://github.com/glaucocustodio) <sup>\[[tutorial](http://glaucocustodio.github.io/2014/11/10/natural-language-parsing-with-ruby/)]</sup>
    *   *Demystifying Data Science: Analyzing Conference Talks with Rails and Ngrams* by
        [Todd Schneider](https://github.com/toddwschneider) <sup>\[[video](https://www.youtube.com/watch?v=2ZDCxwB29Bg) | [code](https://github.com/Genius/abstractogram)]</sup>
    *   *Natural Language Processing with Ruby* by [Konstantin Tennhard](https://github.com/t6d) <sup>\[[video](https://www.youtube.com/watch?v=5u86qVh8r0M) | [video](https://www.youtube.com/watch?v=oFmy_QBQ5DU) |
        [video](https://www.youtube.com/watch?v=sPkeeWnsMn0) |
        [slides](http://euruko2013.org/speakers/presentations/natural_language_processing_with_ruby_and_opennlp-tennhard.pdf)]</sup>
*   2013
    *   *How to parse 'go' - Natural Language Processing in Ruby* by
        [Tom Cartwright](https://twitter.com/tomcartwrightuk) <sup>\[[slides](https://www.slideshare.net/TomCartwright/natual-language-processing-in-ruby) |
        [video](https://skillsmatter.com/skillscasts/4883-how-to-parse-go)]</sup>
    *   *Natural Language Processing in Ruby* by [Brandon Black](https://twitter.com/brandonmblack) <sup>\[[slides](https://speakerdeck.com/brandonblack/natural-language-processing-in-ruby) |
        [video](http://confreaks.tv/videos/railsconf2013-natural-language-processing-with-ruby)]</sup>
    *   *Natural Language Processing with Ruby: n-grams* by [Nathan Kleyn](https://github.com/nathankleyn) <sup>\[[tutorial](https://www.sitepoint.com/natural-language-processing-ruby-n-grams/) |
        [code](https://github.com/nathankleyn/ruby-nlp)]</sup>
    *   *Seeking Lovecraft, Part 1: An introduction to NLP and the Treat Gem* by
        [Robert Qualls](https://github.com/rlqualls) <sup>\[[tutorial](https://www.sitepoint.com/seeking-lovecraft-part-1-an-introduction-to-nlp-and-the-treat-gem/)]</sup>
*   2012
    *   *Machine Learning with Ruby, Part One* by [Vasily Vasinov](https://twitter.com/vasinov) <sup>\[[tutorial](http://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)]</sup>
*   2011
    *   *Ruby one-liners* by [Benoit Hamelin](https://twitter.com/benoithamelin) <sup>\[[post](http://benoithamelin.tumblr.com/ruby1line)]</sup>
    *   *Clustering in Ruby* by [Colin Drake](https://twitter.com/colinfdrake) <sup>\[[post](https://colindrake.me/post/k-means-clustering-in-ruby/)/)]</sup>
*   2010
    *   *bayes\_motel – Bayesian classification for Ruby* by [Mike Perham](https://twitter.com/mperham) <sup>\[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)]</sup>
*   2009
    *   *Porting the UEA-Lite Stemmer to Ruby* by [Jason Adams](https://twitter.com/ealdent) <sup>\[[post](https://ealdent.wordpress.com/2009/07/16/porting-the-uea-lite-stemmer-to-ruby/)]</sup>
    *   *NLP Resources for Ruby* by [Jason Adams](https://twitter.com/ealdent) <sup>\[[post](https://ealdent.wordpress.com/2009/09/13/nlp-resources-for-ruby/)]</sup>
*   2008
    *   *Support Vector Machines (SVM) in Ruby* by [Ilya Grigorik](https://twitter.com/igrigorik) <sup>\[[post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)]</sup>
    *   *Practical text classification with Ruby* by [Gleicon Moraes](https://twitter.com/gleicon) <sup>\[[post](https://zenmachine.wordpress.com/practical-text-classification-with-ruby/) |
        [code](https://github.com/gleicon/zenmachine)]</sup>
*   2007
    *   *Decision Tree Learning in Ruby* by [Ilya Grigorik](https://twitter.com/igrigorik) <sup>\[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>
*   2006
    *   *Speak My Language: Natural Language Processing With Ruby* by [Michael Granger](https://deveiate.org/resume.html) <sup>\[[slides](https://deveiate.org/misc/Speak-My-Language.pdf) |
        [write-up](http://blog.nicksieger.com/articles/2006/10/22/rubyconf-natural-language-generation-and-processing-in-ruby/) |
        [write-up](http://juixe.com/papers/RubyConf2006.pdf)]</sup>

## Projects and Code Examples

*   [Going the Distance](https://github.com/schneems/going_the_distance) -
    Implementations of various distance algorithms with example calculations.
*   [Named entity recognition with Stanford NER and Ruby](https://github.com/mblongii/ruby-ner) -
    NER Examples in Ruby and Java with some [explanations](https://web.archive.org/web/20120722225402/http://mblongii.com/2012/04/15/named-entity-recognition-with-stanford-ner-and-ruby/).
*   [Words Counted](http://rubywordcount.com/) -
    examples of customizable word statistics powered by
    [words\_counted](https://github.com/abitdodgy/words_counted).
*   [RSyntaxTree](https://yohasebe.com/rsyntaxtree/) -
    Web based demonstration of the syntactic tree visualization.

## Books

*   [Miller, Rob](https://twitter.com/robmil/).
    *Text Processing with Ruby: Extract Value from the Data That Surrounds You.*
    Pragmatic Programmers, 2015. <sup>\[[link](https://www.amazon.com/Text-Processing-Ruby-Extract-Surrounds/dp/1680500708)]</sup>
*   [Watson, Mark](https://twitter.com/mark_l_watson).
    *Scripting Intelligence: Web 3.0 Information Gathering and Processing.*
    APRESS, 2010. <sup>\[[link](https://www.amazon.de/Scripting-Intelligence-Information-Gathering-Processing/dp/1430223510)]</sup>
*   [Watson, Mark](https://twitter.com/mark_l_watson).
    *Practical Semantic Web and Linked Data Applications.* Lulu, 2010. <sup>\[[link](http://www.lulu.com/shop/mark-watson/practical-semantic-web-and-linked-data-applications-java-edition/paperback/product-10915016.html)]</sup>

## Community

*   [Reddit](https://www.reddit.com/r/LanguageTechnology/search?q=ruby\&restrict_sr=on)
*   [Stack Overflow](https://stackoverflow.com/search?q=%5Bnlp%5D+and+%5Bruby%5D)
*   [Twitter](https://twitter.com/search?q=Ruby%20NLP%20%23ruby%20OR%20%23nlproc%20OR%20%23rubynlp%20OR%20%23nlp\&src=typd\&lang=en)

## Needs your Help!

All projects in this section are really important for the community but need
more attention. Please if you have spare time and dedication spend some hours
on the code here.

*   [ferret](https://github.com/dbalmain/ferret) -
    Information Retrieval in C and Ruby.
*   [summarize](https://github.com/ssoper/summarize) -
    Ruby native wrapper for [Open Text Summarizer](https://github.com/neopunisher/Open-Text-Summarizer).

## Related Resources

*   [Neural Machine Translation Implementations](https://github.com/jonsafari/nmt-list)
*   [Awesome Ruby](https://github.com/markets/awesome-ruby#natural-language-processing) -
    Among other awesome items a short list of NLP related projects.
*   [Ruby NLP](https://github.com/diasks2/ruby-nlp) -
    State-of-Art collection of Ruby libraries for NLP.
*   [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing) -
    General List of NLP related resources (mostly not for Ruby programmers).
*   [Scientific Ruby](http://sciruby.com/) -
    Linear Algebra, Visualization and Scientific Computing for Ruby.
*   [iRuby](https://github.com/SciRuby/iruby) - IRuby kernel for Jupyter (formelly IPython).
*   [Awesome OCR](https://github.com/kba/awesome-ocr) -
    Multitude of OCR (Optical Character Recognition) resources.
*   [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) -
    Machine Learning with TensorFlow libraries.
*   <a name="imagemagic"></a>
    [ImageMagick](https://imagemagick.org/index.php)

## License

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/) `Awesome NLP with Ruby` by [Andrei Beliankou](https://github.com/arbox) and
[Contributors](https://github.com/arbox/nlp-with-ruby/graphs/contributors).

To the extent possible under law, the person who associated CC0 with
`Awesome NLP with Ruby` has waived all copyright and related or neighboring rights
to `Awesome NLP with Ruby`.

You should have received a copy of the CC0 legalcode along with this
work. If not, see <https://creativecommons.org/publicdomain/zero/1.0/>.

<!--- Links --->

[ruby]: https://www.ruby-lang.org/en/

[motivation]: https://github.com/arbox/nlp-with-ruby/blob/master/motivation.md

[faq]: https://github.com/arbox/nlp-with-ruby/blob/master/FAQ.md

[ds-with-ruby]: https://github.com/arbox/data-science-with-ruby

[ml-with-ruby]: https://github.com/arbox/machine-learning-with-ruby

[change-pr]: https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md

