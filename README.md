
# Digital Methods
- [Introduction (7,10,12)](#introduction)
- [Netnography (7)](#netnography)
  * [Key findings (10)](#key-findings)
  * [Discussion (12)](#discussion)
- [Network Analysis (7)](#network-analysis)
  * [Manual Networks (10)](#manual-networks)
    + [Key findings (12)](#key-findings-1)
  * [Twitter data collection (7)](#twitter-data-collection)
  * [Automated retweet network (10)](#automated-retweet-network)
    + [Key findings (12)](#key-findings-2)
    + [Discussion (7)](#discussion-1)
- [Content Analysis (10)](#content-analysis)
  * [Key findings(12)](#key-findings-3)
  * [Discussion (7)](#discussion-2)
- [Quali-quantitative integration across methods (10)](#quali-quantitative-integration-across-methods)
   * [Interplay of netnography, network analysis and content analysis (12)](#interplay-of-netnography-network-analysis-and-content-analysis)
   * [Computationally-led vs. computationally-assisted approaches to the analysis of content (7)](#computationally-led-vs-computationally-assisted-approaches-to-the-analysis-of-content)
   * [Overall methodological considerations (10)](#overall-methodological-considerations)
 - [Conclusion (7,10,12)](#conclusion)
 - [References](#references)


# ASDS2 
  * [Research Questions (13,15,16)](#research-questions)
  * [Methods and analytical choices (13)](#methods-and-analytical-choices)
    + [Dataset (15)](#dataset)
      - [Word2Vec (16)](#word2vec)
      - [Preprocessing (13)](#preprocessing)
    + [Topic models (15)](#topic-models)
    + [Text Classification (16)](#text-classification)
  * [Results (13)](#results)
    + [Topic models (15)](#topic-models-1)
    + [Text classification (16)](#text-classification-1)
  * [References](#references)
 

## Introduction

On social media, the Covid-19 vaccination programs have been widely discussed since the first Covid-19 vaccines were approved for use in late 2020. Recent studies of this debate have paid particular attention to vaccine hesitancy (Eibensteiner et al., 2021; Islam et al., 2021; Puri et al., 2020) and in our project, we follow a similar research interest: We map the public issue of Covid-19 vaccine hesitancy for three countries, Denmark, Germany and Poland, and explore differences and similarities between these public debates. The idea of cross-country comparison is rooted in our nationalities and we argue that this language and country-specific knowledge is crucial throughout the process for us to make informed analytical decisions. Thus, our project is aimed to answer the overarching research question: _What are the similarities and differences in the Covid-19 anti-vaccine debate between Denmark, Germany and Poland?_

Methodologically, the project combines computer-assisted qualitative and quantitative methods in order to explore the broad landscape of practices through which actors and digital platforms shape the phenomenon of vaccine hesitancy (Rogers & Marres, 2000; Caliandro, 2017). We explore this phenomenon by answering four sub-questions:


**RQ1: Which narratives do anti-vaccine actors invoke in relation to the public issue of Covid-19 vaccines?**

We conduct a netnographic campaign in the form of what Airoldi (2018) calls meta-fieldwork by following anti-vaccine ideas and keywords across platforms to identify key actors and narratives. Our immersive engagement also accounts for how these actors are related by creating digital trace-based manual networks that allow us to analyse the second sub-question:

**RQ2: On which platforms are key anti-vaccine actors present and how do they relate to each other through digital traces?**

Shifting the analytical focus from a cross-platform perspective to Twitter, we ask:

**RQ3: Where are anti-vaccine actors situated in the broader social network of users contributing to the general Covid-19 vaccine debate on Twitter?**

We investigate anti-vaccine actors' positions through exploratory visual analysis of retweet networks. Finally, we are interested in the content of tweets relating to the Covid-19 vaccine debate:

**RQ4: In which semantic contexts is the term &#39;vaccine&#39; currently used on Twitter?

In order to answer this question, we create semantic networks and qualitatively analyze the content of tweets assigned to clusters of co-occurring words.

## Netnography

As we use our netnographic campaign to gain deep and qualitative insights into the socio-symbolic relations between actors and to ground, contextualize, and challenge both the network and the content analysis, we considered it crucial for each group member to immerse themselves in one of the respective national debates online. We each worked in our country-specific immersion journal, but to ensure comparability between the netnographic investigation of the respective digital landscapes (Airoldi, 2018; Kozinets, 2019), we initially agreed on a template for the immersion journals.

We started our netnographic campaign with a broad interest in the public issue of Covid-19 vaccines since we initially conceptualized vaccines as a tool used to pursue a sustainable transition back to reopening of public life. Our early netnography found several sub-discourses in the wider vaccine debate, focussing for instance on side effects, risks associated with vaccines or the vaccine passports. However, we discovered that neither the theme nor the language of sustainability were prevalent among the actors we had observed so far. Instead, the anti-vaccine discourse emerged as an interesting and relevant issue that was common to all three national debates while also differing between the countries. As netnography is characterized by an iterative research process that involves constant reflection and the exploration of emerging analytical ideas (Kozinets, 2019; Krieg et al., 2017), we decided to pursue our findings about anti-vaccine actors for the second stage of our netnographic investigation. 

To do so, we followed anti-vaccine ideas and narratives across various platforms (Marcus, 1995). Importantly, this approach allowed us to study the role of digital media platforms and their affordances (Venturini et al., 2018) that “shape the observed social behavior” (Airoldi, 2018, p. 669). We focused on social media platforms, e.g. Facebook, Twitter and Telegram, as well as news websites and blogs that actors on social media linked to. We agreed on including both individual actors, for instance private Twitter users, as well as collective actors, such as Facebook groups or Telegram channels.

### Key findings

We will first outline netnographic findings that were common to the three national debates, and then describe crucial differences across countries (RQ1). 

Firstly, we found that some anti-vaccine actors refer to conspiracy theories that portray Covid-19 and the vaccination programs as tools to subjugate the world population to a regime of oppression. This is exemplified by a quote from a German attorney and conspiracy theorist who explains that ‘the other side’ uses vaccines to ‘gain control over all of us’ (‘um Kontrolle über uns zu erlangen’) and to reduce the world population (‘Bevölkerungsreduktion’). According to this narrative, people supporting Covid-19 vaccination are portrayed as sheep blindly following government orders without thinking for themselves. 

Secondly, we identified a theme organized around personal freedom: actors argue that there is an indirect coercion to get vaccinated, since only the people who are vaccinated (will) get to enjoy more freedoms such as travel or restaurant visits. For instance, a Danish Twitter user writes about the split of Danish society into two groups: “Coronapasset er et voldsomt indgreb i vores alles liv og frihed og er samtidig et absurd uproportionelt magtmiddel, som deler befolkningen op i et A- og B-hold med forskellige rettigheder.”

Among historical references to systems of oppression, we found that references to Nazi Germany are often used by anti-vaccine actors across countries. These references include comparisons of vaccine passports to Jewish passports during the Third Reich and comparing politicians and doctors to Nazi actors. For instance, a visitor on the Polish right-wing news portal DoRzeczy.pl comments that ‘it’s no longer “arbeit macht frei” [Nazi slogan saying ‘work sets you free’], but 'impfung macht frei [‘vaccination sets you free’]’ (‘teraz to nie “arbeit macht frei", tylko “impfung macht frei”’).

Shifting from the common narratives to country-specific findings, we found that the Polish debate on vaccines is often grounded in dichotomies related to heavy polarization of the political scene. The anti-vaccination attitude is characteristic to actors found on the right wing side of the political spectrum, especially radicals declaring distrust towards government, liberal economic views, adherence to traditional catholic values, nationalism and supporting the idea of Poland leaving the EU (Polexit).

In the German-speaking debate, we discovered a key distinction between moderate and radical actors. The more moderate actors place a heavy emphasis on the risks associated with vaccination of children. Interestingly, they share the same platforms and social media groups with the radical actors and thus place themselves within this more radical anti-vaccine discourse.

In the Danish debate, we noticed a similar group of moderate vaccine sceptics. As opposed to Germany, these Danish actors are willing to get vaccinated as they judge the health risks of Covid-19 to be greater than vaccine side effects. The discourse by these actors is centred around risk assessment and they emphasize the comparison to other risks such as the side effects associated with birth control.

### Discussion

Our immersive engagement with the different data sites allowed us to gain qualitative insights on the types of actors and prevalent patterns in the anti-vaccine discourse, yet our netnographic campaign comes with several shortcomings. The most crucial shortcoming was resource constraints as we could have gone both more wide and in-depth with more time available.

Moreover, working in different languages poses additional challenges, as we spent a lot of time translating and explaining our findings to each other, and found that nuances and lexical particularities get easily lost in this process. Since we could each only do the netnography in our respective language, we also ended up with slightly different versions of our immersion journals.

In relation to the quality of our netnographic data, it is important to point out that especially the data in our early netnographic efforts at times lacked richness since we, during the first couple of weeks, were very focused on Twitter which only provides very short and rather shallow data (Kozinets, 2019). The early netnographic campaign also did not account for relations and interactions between users, a shortcoming which we later on addressed by introducing a section for relational data in the immersion journal.


## Network Analysis

### Manual Networks

To analyse the key actors and their relations to each other (Campagnolo, 2020, Krieg et al., 2017), we created manual networks visualizing the relations, in the form of digital traces, which we observed in the netnographic campaigns (RQ2). The manual network visualizations were created from edgelists using the Python module *pyvis:* In the graphs below (figures 1-3), the node shape reflects the types of actor (individual or collective) and the node color reflects the type of platform on which we encountered an actor. The edge color reflects the type of digital trace where grey edges represent hyperlinks and blue edges represent retweets. 

#### Key findings

In the analysis of our manual networks, we find important differences across countries:

<img src="https://user-images.githubusercontent.com/86028042/122399337-fd720580-cf7a-11eb-992c-2230a0e58d11.png">

**Network of Polish-speaking actors.** The anti-vaccine debate appears to be shaped mostly by collective actors, such as right-wing, often radical media portals, for instance “Nasza Polska” or “Polonia Christiana 24”. The liberal-conservative news media website “Najwyższy czas!” holds a central position in Polish network, being referred to by both individual and collective actors. Furthermore, the Facebook page “Stop compulsory vaccination” which is followed by 19,279 users is a key actor in the debate. However, it mostly links to other anti-vaccine actors, and its individual users do not engage actively in creating its content. Conspiracy-theory blogs take peripheral positions in the network, often referring to each other, and rarely being linked to by other actors. Lastly, the popular microblogging webpage wykop.pl is also placed in the periphery and its users refer to a wider array of sources, including direct links to official institutions.



<img src="https://user-images.githubusercontent.com/86028042/122399335-fd720580-cf7a-11eb-9e8c-3b76fcb502c9.png">

**Network of German-speaking actors.**  During the netnography, it was very difficult to find anti-vaccine actors and discussions on mainstream social media sites and through Google searches. An inactive anti-vaccine Facebook page led to the messaging app Telegram and the public channel @impfenmussfreiwilligbleiben which turned out to be a key actor. The network is therefore centred around this channel, showing hyperlink traces connecting it with other, mainly collective, actors such as websites, blogs, other Telegram channels and media outlets. The channel acts as a curator of anti-vaccine content selected and posted by the (anonymous) owners of the channel and its users. In this curation of content, the users do not distinguish between legacy media outlets and alternative media sources or conspiracy theory websites, linking to all types of sources. Moreover, links to mainstream social media platforms are very rare and Twitter does not seem to be an important site for anti-vaccine users, a relevant finding which contextualizes the automated retweet network in the following chapter. 


<img src="https://user-images.githubusercontent.com/86028042/122399330-fc40d880-cf7a-11eb-89bf-7bba789744b4.png">

**Network of Danish-speaking actors.** In contrast, the Danish actors are spread across mainstream platforms and the discourse is driven by a few individual actors which are present on both Twitter and Facebook. On Twitter, the central actors are highly connected to one another and retweet each other frequently. In the immersive engagement with these actors on Twitter, it became clear that some of these central actors provide a lot of resources and material, e.g. by linking to locked Google Drives or Dropbox folders. Beyond Twitter, the manual network shows a demarcation between mainstream and niche social media platforms. The niche platforms such as Rumble, Odyssey, BitChute or BitTube have no content moderation and users can upload any content without facing removal or the deletion of their account. These platforms form their own cluster in the network, largely disconnected from the mainstream social media sites.

After having explored the relations between key anti-vaccine actors, our analysis moves on to explore where these actors are situated in the broader Covid-19 vaccine debate on Twitter (RQ3).

### Twitter data collection

The collection of the three country-specific datasets was conducted in two rounds, first by sampling tweets based on the Danish, German and Polish vaccine-related terms identified in the netnographic campaign. We then trained the word embedding model word2vec on our three tweet corpora to subsequently find similar words to the query terms of the first sampling round (see ASDS2 section). We manually selected vaccine-related terms, finalized our list of query terms (see appendix pdf 1) and sampled our final three datasets.

For the data collection, we used the Search endpoint of the Twitter API which only allows the retrieval of tweets from the past seven days. Thus, our datasets give a snapshot of the current Twitter discourse but they neither represent a random nor an exhaustive sample of the entire Covid-19 vaccine debate. Yet we argue that, given the limitation of nonprobability sampling, our datasets still constitute defensible samples: We ran multiple variations of the query including specifications for retweets or original tweets only and, as Rafail (2017) notes, the large amount of redundant tweets indicates that we’ve exhaustively collected tweets (we ended up with 15.9% unique tweets (Germany), 56.8% unique tweets (Denmark) and 65.4% unique tweets (Poland) respectively). 

After removing duplicates, the quality of the dataset was assessed by a manual inspection of a subsample of tweets. We encountered several issues which were addressed accordingly:

**Language:** The language tagging of the Twitter API appeared to be flawed, so an additional inspection of each dataset was performed using the Python package *langdetect.* However, as the package is not optimized for very short pieces of text, tweets labeled as other languages were manually investigated, ensuring that only tweets that were actually non-Danish, non-German or non-Polish were removed from the respective datasets (see appendix *code* 3). 

**Other vaccines:** We inspected occurrences of other vaccines such as HPV, the flu, or polio in our datasets. However, the majority were present in relation to the Covid-19 vaccine and were therefore kept. 

The final datasets contained tweets (including retweets) created in between 21 May and 28 May 2021. The Danish dataset comprises 4,665 tweets, the German dataset comprises 204,412 tweets and the Polish dataset comprises 100,985 tweets. 


### Automated retweet network

We created three automated networks based on the retweet relations in our datasets. Since we did not base our data collection on a clearly demarcated set of actors, these networks are very large and hence we decided that additional information on the nodes was needed in order to interpret the networks. Using an active learning approach (see ASDS2 section), we trained a classifier to label all tweets as either anti-vaccine, pro-vaccine, neutral or not-vaccine-related. Based on this labelling of tweets, we marked users as belonging to one of these groups depending on which category the majority of their tweets were labelled as. To achieve a “spatialization of the topology of the network” (Decuypere, 2020, p. 81), we used the ForceAtlas2 algorithm in Gephi for the visualization of the graphs. To further ease the interpretation of the network structure, we performed a modularity community detection using the Python package *python-louvain* which provides an implementation of the Louvain algorithm. Additionally, we conducted a k-core decomposition analysis to get an overview of the distribution of anti-vaccine actors in the core and the periphery of the network (see appendix *code* 9).

#### Key findings

In the graphs below (see figures 4-6), we excluded users marked as not-vaccine-related in order to focus on the actual Covid-19 vaccine-related retweet network. For each dataset, the first graph shows the six largest communities coded by color, whereas the second graph shows the same network with anti-vaccine users marked in blue.

<img src="https://user-images.githubusercontent.com/86028042/122355066-e10da300-cf51-11eb-873f-9f5069cdbc99.png">

<img src="https://user-images.githubusercontent.com/86028042/122355071-e23ed000-cf51-11eb-9970-9435192c1b60.png">

<img src="https://user-images.githubusercontent.com/86028042/122355074-e23ed000-cf51-11eb-9a46-87302e14c25e.png">

Apart from the different sizes of the networks, we find that the clusters and positions of anti-vaccine users differ considerably: The majority of the Danish network consists of anti-vaccine users which form a strongly connected retweeting community, placed on the right-hand side of the graph. The Polish network only shows one such strongly connected community of anti-vaccine users on the right-hand side of the graph. In comparison, the German anti-vaccine users are scattered throughout the detected communities and no clear anti-vaccine cluster is visible.

The k-core decomposition shows further differences in the proportion of anti-vaccine actors in the core of the network (the higher k-shells) as opposed to the periphery (lower k-shells) of the network (see figure 7). 


<img src="https://user-images.githubusercontent.com/86028042/122355787-79a42300-cf52-11eb-96e5-a0f0f81de80a.png"> 

There is a lively anti-vaccine debate on Danish Twitter with users in both the core and the periphery of the network participating in this debate. The Polish anti-vaccine actors are partly active on Twitter, while Twitter does not play a major role in the German-speaking anti-vaccine debate. Overall, these findings are in line with our conclusions drawn from the manual networks and they highlight the importance of a cross-platform netnographic investigation: Insights gained from Twitter data are highly medium-specific and do not necessarily represent a wider debate.


#### Discussion

The most important shortcoming of our automated network analysis is related to the labelling of users: The active learning classification is not fault-free and especially the evaluation of the Polish classifier showed that it often mislabeled tweets (see ASDS2 section). More generally, the classification is often ambiguous and the issues that thus arise spill over into our network analysis. To mitigate this and contextualize the findings from the automated retweet network further, we netnographically investigated the users that were identified as most central by the k-core decomposition analysis. [Very brief summary of what we found: any issues? Did this confirm our network analysis? Refer to the rows in the immersion journals here].

## Content Analysis

In order to explore the semantic contexts in which Twitter users refer to the word ‘vaccine’ in the different national debates (RQ4), we deployed semantic networks and subsequent qualitative reading of tweets. For this analysis of content, we found that semantic word networks are preferable to actor-word relations because our datasets consist of tweets from many different Twitter users rather than a predefined set of actors.

Prior to the analysis, the data was preprocessed, i.e. we removed URLs, emojis, punctuation, @mentions, numbers and single characters; subsequently we used the Python package spaCy to remove stopwords and to tokenize, lemmatize and lowercase all words in the corpora. Furthermore, we only kept selected categories of words using part-of-speech tagging provided by the spaCy package and removed rare words. When constructing the semantic network, we followed the approach suggested by Fuhse et al. (2020): We constructed a co-occurrence matrix that counts the number of times two words appear in a tweet together. We found the 60 words which most frequently co-occur with the term ‘vaccine’ in the respective languages and extracted the co-occurrences between these words. Importantly, in this step we diverged from the semantic network analysis outlined by Fuhse et al. (2020) as the symmetric association values returned semantic clusters of very specialized words, such as a cluster referring to ‘thrombocytopenia’. Therefore, we decided against adjusting for the frequency of word pairs and used the absolute co-occurrence values instead. After having created a graph based on this sub-matrix, we performed a modularity community detection using the *python-louvain* package and visualized the results deploying the ForceAtlas2 algorithm in Gephi (see appendix *code* 15). However, while the community detection returned several clusters in each semantic network, in the interpretation of these semantic clusters we still faced the ‘meaning problem’ as outlined by Munk (2019). We therefore randomly sampled 25 tweets from each of the semantic clusters to perform a qualitative content analysis, allowing for better understanding how the word ‘vaccine’ is semantically contextualized in the Twitter corpora. Subsequently, we qualitatively coded the content of the sampled tweets (Airoldi, 2018). This process allowed us to identify previously uncovered themes, that are described in detail in the codebook (see appendix pdf 3), which has been developed in order to organize, combine, and collate data found through the qualitative methods applied in our project (Airoldi, 2018; MacQueen et al., 1998; Kozinets, 2019).


### Key findings

Below, we present the three semantic networks containing the word lemmas in the original languages (Figures 8-10). A translation and more extensive description of the clusters can be found in the appendix (see appendix *pdf* 4).

<img src="https://user-images.githubusercontent.com/86028042/122357975-7f9b0380-cf54-11eb-85b7-92075145938a.png">
In the German tweets, the focal point is the topic of vaccinating children (cluster ‘Children’). The qualitative content analysis showed that this cluster is related to the rest of the clusters because the vaccination of children was mentioned all throughout the tweets sampled from the different clusters. Interestingly, this topic emerged as a key point of the moderate anti-vaccine actors during the netnographic campaign as well. This indicates that, while the anti-vaccine discourse takes place on different sites and is led by different actors, both the general vaccine debate and the anti-vaccine debate share a similar use of terms and are thus connected through symbolic relations.


<img src="https://user-images.githubusercontent.com/86028042/122357978-80339a00-cf54-11eb-8d40-8db945c0b406.png">
In the Polish semantic network, the anti-vaccine narratives are found mainly in three clusters (‘Covid-19 tests’, ‘Health risks’, ‘Death and disease’), however in none of them it is a dominating part of the debate. Anti-vaccine tweets were most prevalent in the cluster ‘Death and disease’ consisting of tweets discussing vaccine-related deaths, diseases, and adverse health effects. The qualitative reading revealed that in all clusters, anti-vaccine tweets most often refer to conspiracy theories or conceptualize vaccines as a medical experiment. Content referring to personal experiences with vaccines and organization of the Polish vaccination program appears to dominate the vaccine debate, as tweets on these topics can be found in all clusters.


<img src="https://user-images.githubusercontent.com/86028042/122357973-7f026d00-cf54-11eb-90eb-451851290719.png">
In accordance with the Danish retweet network, the majority of the clusters in the semantic network were characterized as being driven by anti-vaccine themes, while only one cluster (‘Miscellaneous’) more generally consisted of tweets related to statistics, status of the vaccine plan or prioritization. The remaining clusters contained obvious anti-vaccine trends including various narratives revolving around side effects, government mistrust, public promotion of vaccines, manipulation, vaccinating children, de facto force to obtain a corona passport, fascism and communism, gene therapy, and medical experiments.


### Discussion

Overall, the clustering of co-occurring words worked well and we were able to interpret the majority of them, however the analysis should still be assessed in light of the following shortcomings: The part-of-speech tagger only correctly tagged around three quarters of the words. Moreover, our sampling strategy to retrieve tweets from each cluster could be improved: We randomly sampled tweets that contain the word ‘vaccine’ and one other word from a cluster, and since some of the clusters comprise words carrying little semantic meaning such as e.g. ‘(to) take’ or ‘yay’, the sampled tweets did not always seem to be related to a clearly demarcated theme. Moreover, as a next step in future analyses, we would consider a multi-dimensional scaling approach to map the similarities and differences between these terms.

# ASDS2

## Research Questions

The overarching aim of the project is to explore similarities and differences in the Covid-19 anti-vaccine debate between Denmark, Germany and Poland. In this section, the scope is to investigate the following sub-questions:

### RQ 1: What is the topical distribution of tweets on the Covid-19 vaccine debate?

The analysis aims to examine the topical distributions in each dataset, exploring both the ‘themes’ of the topics and degree of meaningfulness. Moreover, the performance of a hSBM (hierarchical Stochastic Block Model) will be compared to a LDA (Latent Dirichlet Allocation) to examine and evaluate possible differences in their results. 

### RQ 2: What type of users partake in the Covid-19 vaccine debate on Twitter?

This sub-question aims to utilize a combination of Active Learning and Supervised Learning to label Twitter users by classifying tweets as either being pro- or anti-vaccine. In addition to exploring the proportions of user types, the predicted labels will be integrated in the automated retweet network in the Digital Methods section. 

## Methods and analytical choices

### Dataset

#### Word2Vec

Word2Vec was used in the data collection process to extend the search queries in the attempt to improve dataset quality and decrease sampling bias (see appendix *code* 6). By utilizing the vector representation of words,  search queries can be extended based on word embeddings generated using a shallow neural network. Due to the (relatively) small corpora (DK: 3.431 tweets, GER: 100.314 tweets, PL: 46.310 tweets), this paper used CBOW and a vector-size of 32 as these yielded more meaningful results. However, the word2vec did not work equally well for the datasets, which is probably due to the different sizes of the corpora. 

#### Preprocessing

Prior to conducting the analyses, the text was preprocessed through the following steps: removing URLs, emojis,  @ mentions, &amp; and removing dashes - , colons : and * . Then, all non-alphanumeric characters (excl. # for hashtags), numbers, single characters, multiple whitespaces, and leading and trailing whitespaces were removed. Finally, all text was lowercased and (language-specific) stopwords were removed before tokenizing and lemmatizing using SpaCy (see appendix *code* 7). 


### Topic models

It is hypothesized that the hSBM will outperform the LDA in terms of quality, here meaningfulness of the detected topics, and therefore both models are run for comparison. Among the advantages of the hSBM is the ability to identify the optimal number of topics and  best parameters. The hSBM is thus run first, and the number of topics it detects are used in the LDA, while the remaining parameters are defaulted. Another drawback of the LDA is that topics are drawn from a dirichlet distribution which introduces an assumption of homogeneity (Gerlach et al., 2018).

Both of the topic models are run on bi-grams from the lemmatized tweets, as the tokens yielded topics that clustered together different word forms of the same lexeme. Moreover, both models were run on the entire Danish dataset, while a random subset of 20,000 samples were taken from each of the German and Polish datasets, as the hSBM does not scale well. Moreover, as the German and Polish corpora were considerably larger than the Danish, a threshold of a minimum of two occurrences was set for a word to be included in the corpus (see appendix *code* 10 and 11).


### Text Classification

Initially, the ‘superintendent’ module is used to deploy an active learning strategy to efficiently label tweets using optimized query strategies for each of the three datasets. Active learning relies on and makes use of predicted probabilities and can be used to mitigate bias. The procedure involves creating a labeling widget which takes as input unlabeled data, a classifier, and a learning strategy, and then returns the tweets to be manually labeled depending on the learning strategy. By iteratively retraining the model, the data is automatically re-ordered to prioritise the optimal subsequent data points for labelling. The main analytical choices of the active learning procedure involved specifying learning sampling (certainty), training model (multinomial logistic regression model using a lbfgs-solver), and scoring of the 3-fold cross validation (accuracy, default). Furthermore, rather than opting for a binary classification task, inspection of the datasets identified both ‘trash’ tweets (spam, irrelevant, not vaccine related), and ‘neutral’ tweets and hence, four class options were available during the manual labeling. Lastly,  an arbitrary minimum threshold of 1200 tweets to be manually labeled in each dataset was introduced. 

Subsequent to active learning, the labelled datasets are used for text classification, as the outcome variable (label) is categorical. The text classification is conducted through supervised learning, comparing several classifiers with the goal of finding the optimal model for each language-specific dataset. As seen in figure A, the labeled datasets revealed unbalanced classes and thus, stratified 80:20 splits of the datasets are done to preserve the class proportion of the datasets in the training and test data, attempting to avoid overfitting. After creating the train and test sets for each county, the following multinomial classifiers are implemented: Logistic Regression, Naïve Bayes, SVM, Bagging, and Boosting. The classifiers' hyperparameters are tuned on each of the country-specific datasets to ensure optimal performance. To enable the classifiers to process natural language, the raw data is vectorized to create numerical representations using either document-term matrix or tf-idf, as specified in the vectorizer parameters  in the model pipelines.  

<img src="https://user-images.githubusercontent.com/86028042/122384872-68681000-cf6c-11eb-8d59-c05dbff5823d.png">

The overall strategy for the hyperparameter search is a ‘bounded exploration’, in which the initial search consists of searching (exponentially) for fewer parameters with a wider range of values. Subsequently, an iterative process of parameter-tuning is performed to narrow in on the optimal values in the search space, for all classifiers and all datasets. The evaluation criteria of the 5-fold cross-validation is assessed on the f1_micro score, as the default of evaluating on accuracy could potentially lead to models biased towards the majority class. Moreover, the weighted f1-score balances precision and recall and accounts for the expected imbalanced class proportions by aggregating the contributions of all classes to compute the average metric. Lastly, it should be noted that the vectorizer parameter of whether to remove English stop words was included as manual inspection of the datasets indicated that ‘trash’ tweets were often irrelevant English tweets, and thus removing stop words might improve classification of these. 


## Results

### Topic models

Based on manual inspection and qualitative evaluations of the meaningfulness of the topics of each of the datasets, the hSBM was found to outperform the LDA which generally produced conglomerates and  ‘junk’ topics (appendix pdf 2). While the qualitative assessment revealed that junk topics were also present in the hSBM, the majority of the topics were meaningful. Further details of the exact topic summarizations and country specific evaluations should be found in appendix pdf 2. The topical distributions and qualitative evaluation of the individual topics are visualized in figures B-D. In general, the hSBM appeared to yield better results for the German dataset, with the majority of the topics being meaningful. In contrast, in the Danish and Polish topic models, the meaningless topics were among the most prevalent topics. However, the qualitative evaluation of the individual topics predominantly yielded meaningful insights of the topics associated with the Covid-19 vaccine debate on Twitter for all three countries.

<img src="https://user-images.githubusercontent.com/86028042/122384875-68681000-cf6c-11eb-8bdf-2e9f05ac20f7.png">
<img src="https://user-images.githubusercontent.com/86028042/122384878-6900a680-cf6c-11eb-957e-b7f37e312057.png">
<img src="https://user-images.githubusercontent.com/86028042/122384868-6736e300-cf6c-11eb-8bcc-f309c5fca86e.png">


### Text classification
The best models were chosen based on an evaluation combining performance metrics and the aim of the task. Thus, keeping the objective of labelling pro- and anti-vaccine users in mind, in addition to accuracy and AUC, the best models were selected in relation to best balance between the f1-scores for the pro- and anti-vaccine labels. The specific search grids, final parameters of the best models, and evaluation metrics are found in appendix code 14. The best models for each of the countries were fitted on the entire labeled datasets (respective to the country) prior to classifying the unlabeled tweets. The predicted class proportions are depicted in figures E-G. The classifier performance was evaluated by randomly sampling from the predictions and manually labeling the sampled tweets to assess the quality of the predictions, yielding the following  metrics: 


<img src="https://user-images.githubusercontent.com/86028042/122357283-e4099300-cf53-11eb-8d9e-025226bc7885.png"> 

The Danish SVM-classifier had an accuracy of .58 and a weighted f1-score of .62, possibly due to unbalanced classes. Precision, recall, and f1-scores indicate a tendency of predicting the label ‘trash’ with a high recall score of .94, but only a precision of .62, while the ‘neutral’ class appears to be impacted by this, having a recall of only .32 and precision of .14. Hence, the poor performance reflected in the accuracy might result from the classifier predictions being biased towards the ‘trash’ class. However, in relation to the main objective to predict ‘anti-vaxx’ and ‘vaxx’ labels, the f1-scores of .65 and .59 are relatively good. 


<img src="https://user-images.githubusercontent.com/86028042/122357275-e2d86600-cf53-11eb-8ab4-0770cc383559.png"> 

The German SVM-classifier had an accuracy of .73 and a weighted f1-score of .72, thus approximately even. The f1-score for both the ‘vaxx’ and ‘anti-vaxx’ classes were .80, thereby indicating superior performance of the classifier on these classes in comparison to ‘neutral’ (.57) and ‘trash’ (.76).  


<img src="https://user-images.githubusercontent.com/86028042/122357276-e370fc80-cf53-11eb-9f7d-a0b7e1ce8000.png"> 

The Polish SVM-classifier yielded both a low accuracy (.36) and a low weighted f1-score (.39). Inspection of the evaluation metrics indicate unbalanced classes, and thus the weighted precision is .57 in comparison to the weighted recall of .35. Moreover, the ‘neutral’ class had a high precision of 0.68 and a low recall of .26 and in combination with visual inspection of the confusion matrix, this may suggest a bias towards the ‘neutral’ class, supported further by the highly unbalanced class proportions of the predicted labels (figure H). 

<img src="https://user-images.githubusercontent.com/86028042/122399338-fe0a9c00-cf7a-11eb-8496-f11c4d4ff91c.png">  


Overall, the results of the classifier evaluations were mixed and especially the Polish classifier performed poorly. This could be caused by various factors including (bad) data quality, manual errors during active learning, and bias. Thus, future steps should prioritize bias detection and correction. This should focus on correcting proportional estimates aggregated from the respective classifiers by estimating the misclassification probabilities and using these to correct the raw estimates of the class proportions. After using a new labelled test set to calculate the specific misclassification probabilities between each pair of classifications, the resulting confusion matrix should be used to find the corrective frequency (with regards to the individual classes) by taking the number of positive predictions (pos^) and multiplying it with the true positive rate (TPR=TP/(TP+FP)), then subtract the number of negative predictions (neg^) multiplied by the false negative rate (FNR=FN/(FN+TN), and finally dividing by the total number of predictions in the new test set. However, as this was not within the scope of the initial project, the results should be interpreted with caution. 

To summarize, for all three datasets, the SVM-classifier yielded the best results. However, the performance was generally not great, suggesting that future steps should involve bias correction and possibly include transfer learning. 


## Quali-quantitative integration across methods

### Interplay of netnography, network analysis and content analysis

The interplay of the different digital methods used throughout this project elicited both overlaps and discrepancies between findings, ultimately fostering reflection on the validity of the results. 

The netnographic campaigns provided the points of departure for the manual visual networks, along with contextual grounding and cross-platform exploration guidance. Findings from the automated retweet network supported the insights obtained from the netographic analyses and manual networks: For Denmark, we found that the anti-vaccine debate occurs primarily on Twitter, while in Germany it is not clearly visible on this platform. In Poland, Twitter is often used by vaccine-skeptical actors, but it is not the main site of their activity.

Additionally, the findings from the netnographic campaign, which focused on the anti-vaccine discourse, and results of the analysis of the semantic networks, that were based on the more general vaccine debate, complemented each other: The immersive engagement with the Polish debate showed a strong polarization in pro-vaccine and anti-vaccine actors which we would have not been able to see based on the Twitter content analysis alone. For Germany, the combination of the methods revealed that the theme of vaccinating children is found in both the general and the vaccine-sceptic debate, while the Danish semantic network revealed multiple new themes discussed by anti-vaccine users which had not been identified in the netnography.

Moreover, the findings from the automated network were further reflected in the semantic networks. As an example, the Danish retweet network revealed prevalent anti-vaccine clusters throughout the network, which can be used to provide contextual understanding of why the majority of the clusters in the semantic network are dominated by anti-vaccine themes. Similarly, the patterns of anti-vaccine actors being more scattered throughout the German and Polish retweet network are mimicked in the semantic networks which consist of more general contextualization of the term ‘vaccine’. 


### Computationally-led vs. computationally-assisted approaches to the analysis of content

The analyses we conducted as part of the ASDS2 section contributed to the project in several ways: First, the word embedding model word2vec proved to be useful in our data collection phase. It allowed us to extend our query list in order to collect a more extensive sample of tweets which we considered a crucial step since all subsequent conclusions drawn from the Twitter data are dependent on the quality of the dataset (King et al., 2017). 

Second, the active learning and supervised classification of tweets in ASDS2 provided us with user labels which were helpful in analysing the retweet networks. Although we acknowledge that the user labelling is not flawless and that the results thus should be interpreted with caution, the integration of supervised classification extended our automated network analysis. 

Third, the content analysis of the ASDS2 part which comprised hSBM and LDA topic models provided indications of general themes in the tweets. However, for the Danish and Polish datasets, the semantic networks yielded more interpretable results. While we acknowledge that we did not pursue the exact same objective with the semantic networks (which provided the semantic contexts of the term ‘vaccine’) and the topic models (which detected topics in the entire corpus), the discrepancies we found invite critical reflections on how the various approaches to analyzing text differ. 

We mainly see this difference between the text analysis methods of ASDS2 and Digital Methods in their use of computational tools (Carlsen & Ralund, 2021). The methods in the ASDS2 section are computer-led as, for instance, the hSBM is an unsupervised machine learning model that detects topics without our intervention. In contrast, the semantic networks and qualitative reading constitute a computer-assisted qualitative method: The semantic networks help structuring our large datasets, but the actual analysis and interpretation of the topics in the Covid-19 debate is achieved through the qualitative reading of tweets. This analysis is contextualized and grounded by the insights gained in our netnographic investigations as we are aware of the country and medium specificity that shape the content of these tweets.


### Overall methodological considerations

In general, we draw on digital methods to conduct an explorative project with no a priori theorization, operating in between grounded interpretive research tradition and black-box data mining (Babones, 2015). Among the most crucial considerations in our project is the collection of data from Twitter which comes with certain medium-specific affordances. On one hand, these affordances eased the exploration of certain aspects of the data as we used the predefined retweet metrics to investigate the symbolic interactions between users. On the other hand, the content analysis of tweets is an example of interface methods in which we work against predominant Twitter metrics by creating ‘associationist measures’ based on word co-occurrence (Marres & Gerlitz, 2016). In doing so, we follow a style the quali-quantitative that Munk (2019) refers to as curation, as we repurpose online traces to explore certain phenomena relevant for specific research questions (Kozinets, 2019; Venturini et al., 2018). 

The project should also be assessed in the light of the choices made in relation to spatiality and temporality (Brooker et al., 2016). It is important to note that our analysis is for the most part not cross-temporal as the Twitter data collection produced a snapshot of the debates at a specific point in time. A next step would be to monitor changes of time and how these changes shape and change the debate (Brooker et al., 2016). However, the netnographic campaigns monitored digital sites over several weeks, thus introducing a small temporal aspect into the analysis. While this temporal aspect is not directly investigated or reflected in the research questions, the continuous netnographic observations provided great insights, which could be used to ground and further understand how instability of digital traces can affect the analysis and findings. As an example, many of the links and websites included in our immersion journals have been deactivated, and some actors have been banned by platforms.
 
Spatially, our analysis was limited to the Danish, Polish and German-speaking Covid-19 vaccine debates. The cross-country comparison enabled us to contextualize the country-specific findings, aiding us in identifying which events, narratives, actor-relations, and platforms were exceptions or country-specific, and hence, provided additional levels of reflections in relation to both the individual findings and general cross-country patterns. 

Finally, we acknowledge the fact that time constraints and the rather broad scope of our analysis did not allow for deeper exploration of the phenomenon of Covid-19 vaccine hesitancy in the individual countries. Such potentially interesting analytical efforts might include examining the interplay between anti-vaccine symbols and the actors that are using them (Fuhse et al., 2020).


## Conclusion

In this project, we set out to identify similarities and differences in the Covid-19 anti-vaccine debate in Denmark, Germany and Poland. The netnographic analysis revealed common narratives shared between the national anti-vaccine debates such as a freedom theme or references to conspiracy theories. It also indicated some country-specific narratives, such as political polarization and critique of government in the Polish debate (RQ1). Building on the netnographic campaign, our manual network mapped relations between anti-vaccine actors on an individual and organizational level. The visual network showed that although mainstream and niche social media platforms are present in the three countries, the extent to which actors use these platforms differs. For instance, the German anti-vaccine debate is centred around Telegram while the mainstream social media platforms such as Twitter only appear peripherally (RQ2). The insights gathered from the manual networks were echoed in the large-scale retweet networks where we found a stark contrast regarding the composition of the Danish retweet network in contrast to the Polish and German ones: The largest clusters of users in the Danish network consist of anti-vaccine actors which are densely connected (RQ3). Lastly, the semantic network analysis and manual reading revealed key differences regarding the semantic contexts in which the term ‘vaccine’ appears: These contexts included anti-vaccine themes (Denmark), the vaccination of children (Germany), and organization of the vaccination program (Poland).

Future research should explore other platforms apart from Twitter more comprehensively as our analysis indicated that a considerable portion of the anti-vaccine debate takes place on other platforms as wykop.pl in Poland or Telegram in the German-speaking debate. Additionally, conducting a temporal analysis might show how anti-vaccine actors, narratives, sites and relations unfold over time.


## References

Airoldi, M. (2018). Ethnography and the digital fields of social media. International Journal of Social Research Methodology, 21(6), 661–673. [https://doi.org/10.1080/13645579.2018.1465622](https://doi.org/10.1080/13645579.2018.1465622)

Babones, S. (2015). Interpretive Quantitative Methods for the Social Sciences. Sociology, 50(3), 453–469. [https://doi.org/10.1177/0038038515583637](https://doi.org/10.1177/0038038515583637)

Brooker, P., Barnett, J., &amp; Cribbin, T. (2016). Doing social media analytics. Big Data &amp; Society, 3(2), 205395171665806. [https://doi.org/10.1177/2053951716658060](https://doi.org/10.1177/2053951716658060)

Caliandro, A. (2017). Digital Methods for Ethnography: Analytical Concepts for Ethnographers Exploring Social Media Environments. Journal of Contemporary Ethnography, 089124161770296. [https://doi.org/10.1177/0891241617702960](https://doi.org/10.1177/0891241617702960)

Campagnolo G.M. (2020). The Analogue Mapping. In: Social Data Science Xennials. Palgrave Macmillan, Cham. [https://doi.org/10.1007/978-3-030-60358-8\_3](https://doi.org/10.1007/978-3-030-60358-8_3)

Carlsen H. & Ralund S. (2021) &quot;Computational grounded theory revisited: from computer lead to computer assisted text analysis&quot;. Working Paper.

Decuypere, M. (2019). Visual Network Analysis: a qualitative method for researching sociomaterial practice. Qualitative Research, 20(1), 73–90. https://doi.org/10.1177/1468794118816613

Eibensteiner, F., Ritschl, V., Nawaz, F. A., Fazel, S. S., Tsagkaris, C., Kulnik, S. T., Crutzen, R., Klager, E., Völkl-Kernstock, S., Schaden, E., Kletecka-Pulker, M., Willschke, H., &amp; Atanasov, A. G. (2021). People&#39;s Willingness to Vaccinate Against COVID-19 Despite Their Safety Concerns: Twitter Poll Analysis. Journal of medical Internet research, 23(4), e28973. [https://doi.org/10.2196/28973](https://doi.org/10.2196/28973)

Fuhse, J., Stuhler, O., Riebling, J., &amp; Martin, J. L. (2020). Relating social and symbolic relations in quantitative text analysis. A study of parliamentary discourse in the Weimar Republic. Poetics, 78, 101363. [https://doi.org/10.1016/j.poetic.2019.04.004](https://doi.org/10.1016/j.poetic.2019.04.004)

Gerlach, M., Peixoto, T. P., &amp; Altmann, E. G. (2018). A network approach to topic models. Science Advances, 4(7), eaaq1360. https://doi.org/10.1126/sciadv.aaq1360

Islam, M. S., Kamal, A. M., Kabir, A., Southern, D. L., Khan, S. H., Hasan, S., Sarkar, T., Sharmin, S., Das, S., Roy, T., Harun, M., Chughtai, A. A., Homaira, N., &amp; Seale, H. (2021). COVID-19 vaccine rumors and conspiracy theories: The need for cognitive inoculation against misinformation to improve vaccine adherence. PloS one, 16(5), e0251605. [https://doi.org/10.1371/journal.pone.0251605](https://doi.org/10.1371/journal.pone.0251605)

King, G., Lam, P., & Roberts, M. E. (2017). Computer-Assisted Keyword and Document Set Discovery from Unstructured Text. American Journal of Political Science, 61(4), 971–988. https://doi.org/10.1111/ajps.12291

Kozinets, R. (2019). Netnography: The Essential Guide to Qualitative Social Media Research (Third ed.). SAGE Publications Ltd.

Krieg, L., Berning, M. &amp; Hardon, A. (2017). Anthropology with algorithms?: An exploration of online drug knowledge using digital methods. Medicine Anthropology Theory | An open-access journal in the anthropology of health illness and medicine. 4. 21. https://doi.org/10.17157/mat.4.3.458

MacQueen, K. M., McLellan, E., Kay, K., &amp; Milstein, B. (1998). Codebook Development for Team-Based Qualitative Analysis. CAM Journal, 10(2), 31–36. https://doi.org/10.1177/1525822x980100020301

Marcus, G. (1995). Ethnography in/of the World System: The Emergence of Multi-Sited Ethnography. Annual Review of Anthropology, 24, 95-117. Retrieved June 17, 2021, from [http://www.jstor.org/stable/2155931](http://www.jstor.org/stable/2155931)

Marres, N., &amp; Gerlitz, C. (2016). Interface Methods: Renegotiating Relations between Digital Social Research, STS and Sociology. The Sociological Review, 64(1), 21–46. https://doi.org/10.1111/1467-954x.12314

Munk, A. K. (2019). Four Styles of Quali-Quantitative Analysis. Nordicom Review, 40(s1), 159–176. [https://doi.org/10.2478/nor-2019-0020](https://doi.org/10.2478/nor-2019-0020)

Puri, N., Coomes, E. A., Haghbayan, H., &amp; Gunaratne, K. (2020). Social media and vaccine hesitancy: new updates for the era of COVID-19 and globalized infectious diseases. Human vaccines &amp; immunotherapeutics, 16(11), 2586–2593. [https://doi.org/10.1080/21645515.2020.1780846](https://doi.org/10.1080/21645515.2020.1780846)

Rafail, P. (2017). Nonprobability Sampling and Twitter. Social Science Computer Review, 36(2), 195–211. https://doi.org/10.1177/0894439317709431

Rogers, R., &amp; Marres, N. (2000). Landscaping climate change: a mapping technique for understanding science and technology debates on the World Wide Web. Public Understanding of Science, 9(2), 141–163. [https://doi.org/10.1088/0963-6625/9/2/304](https://doi.org/10.1088/0963-6625/9/2/304)

Venturini, T., Bounegru, L., Gray, J., &amp; Rogers, R. (2018). A Reality Check(-List) for Digital Methods. SSRN Electronic Journal. Published. [https://doi.org/10.2139/ssrn.3168664](https://doi.org/10.2139/ssrn.3168664)

