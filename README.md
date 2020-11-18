**Twitter analysis on topics of discussion by feminist activists in India during COVID-19**  
This analysis aims to identify key topics of discussion from a corpus of tweets by Indian feminist activists, tweeted during the COVID-19 pandemic (March 2020 to August 2020). This analysis includes a total of 69,198 tweets from 59 user accounts, tweeted between 25 March 2020 and 14 August 2020. The user accounts for which the tweets were extracted using Twitter's official API were identified based on a systematic method involving expert and snowball sampling.  
  
All the code used in the analysis is available in this Git repository. Please feel free to create issues in this Git repository or send an email to ndehingi@health.ucsd.edu.  
  
**Key questions**  
1. What are the distinct topics of discusssion on Twitter among feminist activists in India?
2. When examined over time, do these topics follow any trends?  
  
**Descriptive analysis of hashtags**  
We first identified the most occurring hashtags in the Twitter dataset. We qualitatively assessed the top 25 most tweeted hashtags and were categorized into different themes where possible.   
  
The most tweeted hashtag was #covid, followed by #india (Figure 1). The hashtags #covid, #lockdown, and #pandemic were categorized as a single theme: COVID-19. Hashtags related to *caste*, a marker of social class in India, were also among the top 25 most tweeted hashtags: #theyinspireme, #dalithistorymonth, and #dalitwomenfight (Dalits are the marginalized caste group in India). The hashtag #theyinspireme was used by feminist activists in our sample to tweet inspiring stories about Dalit women in India. Multiple hashtags on gender-based violence were also identified - #domesticviolence, #violencegainstwomen and #akhirkyon. The hashtag #akhirkyon is a Hindi expression which translates to “But why?” and was used by Twitter users to generate awareness about domestic violence in India. Other hashtags related to gender issues that were among the top 25 most tweeted hashtags included #thesexedchallenge, #womeninstem, #bodyimage, #metoo, #sexgentech. The hashtag #sexgentech was used in discussions on gender inclusivity of current technologies. In response to the arrest of two activists who accompanied a gang rape survivor to court, the hashtags #freetanmay, #freekalyani, and #sunwayichahiye were trending on Indian Twitter, and were among the top 25 most tweeted hashtags in our study. ‘Sunwayi chahiye’ is a Hindi phrase that translates as ‘we want a hearing’.    

![Top 25 hashtags](/successful.pnghashtag_freq.png)

The number of tweets with hashtags related to COVID-19 decreased from March to August. Hashtags related to gender-based violence peaked on 29 May 2020, with 106 tweets including the relevant hashtags on that single day. Qualitative analysis of the tweets in our sample with hashtags related to gender-based violence indicated that this spike could be attributed to a social media campaign by few feminist organizations which aimed to shed light on the prevalence of domestic violence in India, particularly during the lockdown. In April 2020, India reported an increase in calls to women’s helpline center since the COVID-19 related lockdown, which could have led to the small increase in gender-based violence related hashtags in the month of April.   
  
**Topic modelling using Latent Dirichlet Allocation (LDA)**  
To identify the topics from the dataset of tweets, we used Latent Dirichlet Allocation (LDA). LDA is a commonly used method for topic-modelling; it is a generative probabilistic topic model where each document is represented as a random mixture of latent topics. We relied on Coherence scores as well as a subjective evaluation of model results to determine the number of topics for our LDA model. Higher the Coherence score, higher the similarity in the words within each topic. We ran LDA models with increasing value of number of topics, ranging from 10 to 40, and identified the models with high relative Coherence scores. We then examined the interpretability of results for the models. We found the model with 18 topics to have a high Coherence score of 0.45, as well as interpretable results. The output of the LDA model included a list of the most commonly occurring words for each identified topic. The qualitative annotation of the topics was done through a process of discussion and deliberation, based on the top 30 most prevalent words for each topic. One researcher also studied the top tweets corresponding to each topic to get a better contextual understanding of the words. The temporal trend of topics was examined by assessing the number of tweets per day for each topic (tweets categorized as dominant topic). 
  
    
    
The LDA model specified 18 topics across our sample of tweets (Figure 3). The topic covering maximum number of tweets was on migrant worker crises during the COVID-19 lockdown in India. The most commonly occurring words for this topic included worker, home, lockdown, migrant, work, back, state, food, labour, government, month, pay, train, poor, walk, water, due, job, leave, left, light, wage, paid, distance, and travel (Table 1). The next topic with highest number of tweets was on Twitter posts expressing feelings. These tweets were generic posts that did not necessarily cover a common theme, but contained words related to feelings such as, love, friend, happy, always, sorry, and sad.  Four topics relevant to gender issues were identified: 1) violence against women, which included tweets on domestic violence, sexual violence against women, as well as religion and caste-based violence, 2) education which focused on sex education, and gender gaps in education and technology, 3) feminism in the context of socially marginalized groups (minority groups based on sexual orientation, gender identity and caste), and  4) webinars and events related to gender. Tweets corresponding to the topic violence against women included informational posts with helpline numbers for domestic violence victims, as well as posts that were meant to raise awareness about the issue of gender-based violence in India. The topic on education covered posts that aimed to raise awareness about the importance of sex education and an understanding of consent among young boys. It also included posts on challenges faced by students with regards to digital education during the COVID-19 lockdown.  


On examining the temporal trends of each topic, it was observed that number of tweets for COVID-19 related topics remained overall consistent. Tweets related to COVID-19 related health services were highest during the beginning of the lockdown in India, i.e., from 25 March 2020 to 05 April 2020 (Figure 4). Tweets on migrant crises due to the COVID-19 related lockdown also remained consistent over the course of the time period for which tweets were collected in our sample. 
The topic on violence against women peaked on the first week of May 2020. A qualitative analysis of the tweets corresponding to this topic showed that this surge was because of an increase in tweets related to domestic violence. A social media campaign initiated by non-profit feminist organizations, using the hashtag #akhirkyon, aimed to highlight the increasing rates of reported domestic violence cases in India during the lockdown. ‘Akhir kyon’ is a Hindi phrase which translates to ‘but why?’. Peaks identified for other topics also corresponded to related offline events, according to our qualitative analysis. 

In conclusion, Twitter data mining could be used as an essential tool for understanding gender issues that are of priority for feminist activists. 
