# AudioIdentification


# Music Information Retreival Project : Audio Identification

Prepared By Rahul Agarwal, April 2018

The Project used two methods for Audio Identification :

1.Matching through Spectral Peaks
2.Local Senstive Hashing of Audio Files

# Audio Identification Through Spectral Peaks

Here we try to identify given audio samples with already present audio files in database . The identification process is based on finding the spectral peaks in both test sample and present audios files which act as identifier for that audio. We find most powerful frequencies (frequencies corrosponding to maximum amplitute) which forms spectral envelope of test audio and try to match with frequency peaks of audio present in database.


# Local Sensitive Hashing

Here we implement Local Sensitive Hashing to our DataSet . Locality Sensitive Hashing (LSH) is an algorithm known for enabling scalable, approximate nearest neighbor search of objects. LSH enables a precomputation of a hash that can be quickly compared with another hash to ascertain their similarity. We extract the features of files in out dataset and compute thier hash and stores in a table. Similarly, Hash is calculated for given test audio file and we match its hash with already stored hashes.


