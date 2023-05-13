<font size="4">This project includes the introduction and the access method of three datasets for closed contiguous sequential pattern mining.</font><br />

<font size="4">dataset #1: Kosarak</font><br />
This is a very large dataset containing 990 000 sequences of click-stream data from an hungarian news portal.
The dataset uses the original data from: http://fimi.ua.ac.be/data/. The dataset for mining closed contiguous sequential patterns is processed. Here is an example from the processed dataset:  

```
69 -1 11 -1 1 -1 6 -1 -2  
11 -1 70 -1 6 -1 -2  
6 -1 3 -1 71 -1 -2  
```
This example dataset includes three sequences, '-2' is the marker at the end of each sequence, and '-1' is the separator between items. Different items in the dataset represent different click items.  

Kosarak Dataset are currently available from the following websites:  
https://www.philippe-fournier-viger.com/spmf/datasets/kosarak_sequences.txt  
https://mypikpak.com/s/VNVEdqo2R4Npnse32eziL911o1  
password (提取码) ：dj4k <br />


<font size="4">dataset #2: Protein </font><br /> 
The biological dataset Protein was publicly provided by the National Center for Biotechnology Information (NCBI, https://www.ncbi.nlm.nih.gov/). Protein was extracted by the conjunction of (1) search category = “Protein”, (2) species =  “Bacteria”, (3) release date = [2022/3/1—2022/5/15], and (4) organism = “Escherichia coli”. The dataset file is in _fasta_ format. 
Since the dataset is very large, it currently needs to be accessed through a network disk. Network disk links are as follows:  
link #1: https://mypikpak.com/s/VNVEe4fDgd0QHay2oFQfmBDCo1  
password (提取码) ：nu8e  
link #2：https://pan.baidu.com/s/1KPEVsKXKvF8x9X1EkFVFnA   
password (提取码) ：lszn <br />


<font size="4">dataset #3: CDtaxi</font><br />
CDtaxi includes trajectory data of over 10,000 taxis in Chengdu within the most 25 days. There are more than 1 billion GPS messages in the track. The data comes from a data analysis competition called "智慧中国杯" (https://www.pkbigdata.com/common/zhzgbCmptDetails.html). Here is an example from the dataset:  

```
1,30.593305,104.067773,1,2014/8/30 19:59:40
1,30.598553,104.067605,1,2014/8/30 19:59:10
1,30.601324,104.124101,1,2014/8/30 13:53:36
1,30.601326,104.124119,1,2014/8/30 13:54:06
1,30.601589,104.123913,1,2014/8/30 13:53:06
```

The meaning of the data is as follows: the first column is the taxi ID, the second column is the latitude, the third column is the longitude, the fourth column is the passenger status, and the fifth column is the current time. 

This dataset needs to be preprocessed by the road network matching algorithm to obtain the trajectory sequence before it can be used for closed contiguous sequential pattern mining. During the process of road network matching, only four columns 1, 3, 4, and 5 are used.

Since the dataset is also very large, it currently needs to be accessed through a network disk. The network disk link is as follows:
https://pan.baidu.com/s/1phfGPIn6uul4jPt8BfBRwg  
password (提取码) ：a2dh
https://mypikpak.com/s/VNVFb39Sgd0QHay2oFQfzFcyo1  
password (提取码) ：6gnn  
https://pan.baidu.com/share/init?surl=o84gtPS  
password (提取码) ：meq5
