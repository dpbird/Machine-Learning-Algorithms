C:\Python27\python.exe learnhmm.py trainwords.txt index_to_word.txt index_to_tag.txt hmmprior.txt hmmemit.txt hmmtrans.txt

C:\Python27\python.exe learnhmm.py toytrain.txt toy_index_to_word.txt toy_index_to_tag.txt hmmprior.txt hmmemit.txt hmmtrans.txt

C:\Python27\python.exe forwardbackward.py toytrain.txt toy_index_to_word.txt toy_index_to_tag.txt hmmprior.txt hmmemit.txt hmmtrans.txt toy_predicted.txt toy_metric.txt

C:\Python27\python.exe forwardbackward.py testwords.txt index_to_word.txt index_to_tag.txt hmmprior.txt hmmemit.txt hmmtrans.txt predicted.txt metric.txt


tar -cvf hmm.tar learnhmm.py forwardbackward.py

forwardbackward_withou_normalization

C:\Python27\python.exe forwardbackward_withou_normalization.py testwords.txt index_to_word.txt index_to_tag.txt hmmprior.txt hmmemit.txt hmmtrans.txt predicted.txt metric.txt

C:\Python27\python.exe forwardbackward_withou_normalization.py toytest.txt toy_index_to_word.txt toy_index_to_tag.txt hmmprior.txt hmmemit.txt hmmtrans.txt predicted_toy.txt metric_toy.txt


python learnhmm.py trainwords.txt index_to_word.txt index_to_tag.txt hmmprior.txt hmmemit.txt hmmtrans.txt
python forwardbackward.py testwords.txt index_to_word.txt index_to_tag.txt hmmprior.txt hmmemit.txt hmmtrans.txt predicted.txt metric.txt

