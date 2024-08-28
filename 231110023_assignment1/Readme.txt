Q1.> It is represented by Qusn1.ipynb, Unicode correction will be stored in ans vector once we run the code, since corpus is very big,
     I am not printing the output, we can see result by uncommenting the last line, i.e. (" print(ans) ")
     I have conidered unicode correction words like "चाँद" as " च + आ + अं + द + अ "

Q2.> It is represented by Q2.ipynb, it is printing top 20 characters and top 20 unigram syllables and top 20 bigram syllables in hindi corpus

Q4.> Unigram 1k and 2k is represented by unigram1k.ipynb and unigram2k.ipynb, it is trained on hindi corpus;
     
     Bpe 1k and Bpe 2k is represented by BPE1k.ipynb abd BPE.ipynb. 
     here, since corpus is very large and due to limitation of my machine, tokenization is done on demo_hindi file, pls replace 
     demo_hindi.txt with hi_100.txt to get result, Sorry for inconvinience;

     mBert 1k and 2k is represented mBert_1k and mBert_2k respectively

     indicBert 1k and indicBert 2k is represented by indicBert1k.ipynb and indicBert2k.ipynb. 
     here, since corpus is very large and due to limitation of my machine, tokenization is done on demo_hindi file, pls replace 
     demo_hindi.txt with hi_100.txt to get result, Sorry for inconvinience;
	
     WhiteSpaceTokenizer is represented by whitespacetk.ipynb
		
Q5.> Q5.ipynb file, it is printing (precison, recall, f score) respectively for every tokenizer
Q6 is represented by Q6.pdf

pls install
1 - conda install sentencepiece
2 - conda install protobuf
3 - conda install transformer
