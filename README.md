# TUNIZI-Dataset: Context and Topics
On social media, Arabic speakers tend to express themselves in their own local dialect. To do so,
Tunisians use "Tunisian Arabizi", which consists in supplementing numerals to the Latin script rather
than the Arabic alphabet. 
TUNIZI is the first Tunisian Arabizi Dataset including 3K sentences, balanced, covering different topics, preprocessed and annotated as positive and negative.
# Collection Process
TUNIZI is collected from comments on social media.
All data was directly observable and did not require other data to be inferred from.
The latest comment existing in TUNIZI was published in 30/08/2019 and the most recent comment in 08/01/2020.
Comments were collected using scraping to extract our data from YouTube videos.
During the collection, any non arabizi comment is removed. 
The dataset is composed of 1500 positive comments and 1500 negative.
Data was collected by the iCompass team (http://www.icompass.tn).

# Preprocessing and Annotation Process
TUNIZI was preprocessed by removing links, emoji symbols and punctuation.
Annotation was then performed by five Tunisian native speakers, three males and two females at a higher education level (Master/PhD). 
Comments are annotated as positive (1) or negative(-1).


# Paper citation

@inproceedings{Chayma2020, 

title={TUNIZI: a Tunisian Arabizi sentiment analysis Dataset},

author={Fourati, Chayma and Messaoudi, Abir and Haddad, Hatem},

booktitle={AfricaNLP Workshop, Putting Africa on the NLP Map. ICLR 2020, Virtual Event},

volume    = {arXiv:3091079},

year      = {2020},

url       = {https://arxiv.org/submit/3091079},

}
