## NLP for Korean Tools
ᆮA curated specific tools list of Natural Language Processing(NLP) of Korean.

### Morpheme/형태소 분석기 +  Part of Speech(PoS)/품사 Tagger
- Hannanum (한나눔) (Java, C) [[link](https://kldp.net/hannanum/)]
	- KoNLPy (Python) [[link](http://konlpy.org/en/v0.4.4/api/konlpy.tag/#module-konlpy.tag._hannanum)]
- Kkma (꼬꼬마) (Java) [[link](http://kkma.snu.ac.kr/documents/index.jsp)] [[paper](http://ids.snu.ac.kr/w/images/f/f8/CPL2010-therocks.pdf)]
	- KoNLPy (Python) [[link](http://konlpy.org/en/v0.4.4/api/konlpy.tag/#module-konlpy.tag._kkma)]
- Komoran (Java) [[link](http://www.shineware.co.kr/?page_id=835)]
	- KoNLPy (Python) [[link](http://konlpy.org/en/v0.4.4/api/konlpy.tag/#module-konlpy.tag._komoran)]
- Mecab-ko (C++) [[link](https://bitbucket.org/eunjeon/mecab-ko)]
	- KoNLPy (Python) [[link](http://konlpy.org/en/v0.4.4/api/konlpy.tag/#mecab-class)]
- Twitter (Scala, Java) [[link](https://github.com/twitter/twitter-korean-text)]
	- KoNLPy (Python) [[link](http://konlpy.org/en/v0.4.4/api/konlpy.tag/#module-konlpy.tag._twitter)]
	- .NET, Node.js, Python, Ruby, Elasitc Search bindings
- dparser (REST API) [[link](http://findyou.readthedocs.io/ko/latest/dparser.html)]
- UTagger [[link](http://nlplab.ulsan.ac.kr/doku.php?id=utagger)]
- Arirang (Lucence, Java) [[link](http://cafe.naver.com/korlucene)]
- Rouzeta [[link](https://shleekr.github.io/)] [[slide](http://www.slideshare.net/JieunLee5/ss-67333029?ref=https://readme.skplanet.com/?p=13166)] [[video](https://www.youtube.com/watch?v=tkSVbfWZgn8)]
- seunjeon (Scala, Java) [[link](https://bitbucket.org/eunjeon/seunjeon)]
- RHINO (라이노) [[link](https://sourceforge.net/projects/koreananalyzer/)]
- KTS [[paper](http://scholar.ndsl.kr/schDetail.do?cn=NPAP07926299#)]
- 깜짝새 [[link](https://ryubook.wordpress.com/%EA%B9%9C%EC%A7%9D%EC%83%88-1-5-5-beta/)]

### Named Entity(NE) Tagger / 개체명 인식기
- annie [[link](https://github.com/krikit/annie)]

### Spell Checker / 맞춤법 검사기
- PNU Spell Checker [[link](http://speller.cs.pusan.ac.kr/)]
- Naver Spell Checker [[link](https://search.naver.com/search.naver?where=nexearch&sm=tab_jum&ie=utf8&query=%ED%95%9C%EA%B8%80+%EB%A7%9E%EC%B6%A4%EB%B2%95+%EA%B2%80%EC%82%AC%EA%B8%B0)]
- Daum Spell Checker [[link](http://alldic.daum.net/grammar_checker.do)]
- hunspell-ko [[link](https://github.com/changwoo/hunspell-dict-ko)]

### Syntax Parser / 구문 분석기
- dparser (REST API) [[link](http://findyou.readthedocs.io/ko/latest/dparser.html)]
- NLP HUB (Java) [[link](http://semanticweb.kaist.ac.kr/home/index.php/NLP_HUB)]

### Sentimental Analysis / 감정 분석기
- OpenHangul (오픈한글) [[link](http://openhangul.com/)] [[paper](http://web.yonsei.ac.kr/dslab/Journal/sentiment%20dictionary.pdf)]

### Translator / 번역기
- Naver NMT [[link](http://labspace.naver.com/nmt/)]
- OpenNMT [[link](http://opennmt.net/)]
- Google Translator [[link](https://translate.google.com/)]

### Packages
- KoNLP (R\) [[link](https://cran.r-project.org/web/packages/KoNLP/index.html)]
- KoNLPy (Python) [[link](konlpy.org)] [[paper](http://dmlab.snu.ac.kr/~lucypark/docs/2014-10-10-hclt.pdf)]
- KoalaNLP (Scala) [[link](https://nearbydelta.github.io/KoalaNLP/)]
- NLTK (Python) [[link](http://www.nltk.org/)] [[paper](http://www.aclweb.org/anthology/P04-3031)]
- gensim (Python) [[link](https://radimrehurek.com/gensim/)]
- FastText (C) [[link](https://github.com/facebookresearch/fastText)]
- FastText.py (Python) [[link](https://github.com/salestock/fastText.py)]

###  Others
- Hangulpy (Python) [[link](https://github.com/rhobot/Hangulpy)]
- 자동 조사/접미사 첨부, 자모 분해 및 결합
- Hangulize (Python) [[link](https://github.com/sublee/hangulize)]
- 외래어 한글 변환
- Hanja (Python) [[link](https://pypi.python.org/pypi/hanja)]
- 한자 한글 변환
- kroman [[link](https://github.com/zhangkaiyulw/kroman)]
- Hangul Romanization
- [Ruby](https://github.com/cheunghy/kroman-gem), [Python](https://github.com/zhangkaiyulw/kroman-py), [NodeJS](https://github.com/cheunghy/kroman-js), [Objective-C](https://github.com/cheunghy/kroman-objc), [Swift](https://github.com/cheunghy/kroman-swift)
- hangul (Perl) [[link](https://github.com/dragoncrane/hangul)]
- Hangul Romanization
- textrankr (Python) [[link](https://github.com/theeluwin/textrankr)] [[demo](https://summariz3.herokuapp.com)]
- TextRank 기반 한국어 문서 요약
- 한국어 Word2Vec [[demo](http://virgon.snu.ac.kr:8000/)] [[paper](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDozMjkyYjRkYWViM2Q0MzU2)]
- 한국어 Word2Vec의 analogy test 데모
- 나쁜 단어 사전 [[link](http://badworddictionary.xyz/)]
- crowdsourced dic about badword in korean

## A list of NLP paper for Korean Tools
- 2014 [한국어 의미역 말뭉치 구축을 위한 반자동 태깅 도구 개발](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE02444107)

# References
A curated list of Natural Language Processing (NLP) of Korean text.
[NLP paper of Korean tools](https://github.com/datanada/Awesome-Korean-NLP.git)
