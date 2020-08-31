# hellospark

## Install

wget http://apache.crihan.fr/dist/spark/spark-2.3.1/spark-2.3.1-bin-hadoop2.7.tgz
tar xzf spark-2.3.1-bin-hadoop2.7.tgz

$ wget http://classics.mit.edu/Homer/iliad.mb.txt

## Run

./spark-2.3.1-bin-hadoop2.7/bin/spark-submit ./wordcount.py ./text.txt

## Run  Dist
park-2.3.1-bin-hadoop2.7/bin/spark-submit --master local[4] ../spark/wordcount/wordcount.py ./iliad100.txt
