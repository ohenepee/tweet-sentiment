download: NRC Sentiment140 BingLiu NRC_Emotion

NRC:
	wget http://www.saifmohammad.com/Lexicons/NRC-Hashtag-Sentiment-Lexicon-v0.1.zip
	unzip NRC-Hashtag-Sentiment-Lexicon-v0.1.zip
	rm NRC-Hashtag-Sentiment-Lexicon-v0.1.zip

Sentiment140:
	wget http://www.saifmohammad.com/Lexicons/Sentiment140-Lexicon-v0.1.zip
	unzip Sentiment140-Lexicon-v0.1.zip
	rm Sentiment140-Lexicon-v0.1.zip

BingLiu:
	wget http://www.cs.uic.edu/~liub/FBS/opinion-lexicon-English.rar
	unrar x opinion-lexicon-English.rar
	rm opinion-lexicon-English.rar

NRC_Emotion:
	wget http://www.saifmohammad.com/Lexicons/NRC-Emotion-Lexicon-v0.92.zip
	unzip NRC-Emotion-Lexicon-v0.92.zip
	rm NRC-Emotion-Lexicon-v0.92.zip

clean:
	rm -rf ./Sentiment140-Lexicon-v0.1
	rm -rf ./__MACOSX
	rm -f negative-words.txt
	rm -f positive-words.txt
	rm -rf ./NRC-Hashtag-Sentiment-Lexicon-v0.1
	rm -rf ./NRC-Emotion-Lexicon-v0.92
	rm -f *.zip
	rm -f *.rar

.PHONY: clean, download
