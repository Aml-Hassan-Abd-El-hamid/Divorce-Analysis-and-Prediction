# Divorce Analysis and Prediction

<img src="https://github.com/Aml-Hassan-Abd-El-hamid/Divorce-Analysis-and-Prediction/blob/main/divorce-rings.jpg">

In this project I conduct an analysis for the divorce dataset from Kaggle, you can find the dataset in the following link: https://www.kaggle.com/datasets/andrewmvd/divorce-prediction

## About this dataset:

This dataset contains data about 150 couples with their corresponding Divorce Predictors Scale variables (DPS) on the basis of Gottman couples therapy.

The couples are from various regions of Turkey wherein the records were acquired from face-to-face interviews with couples who were already divorced or happily married.

All responses were collected on a 5 point scale (0=Never, 1=Seldom, 2=Averagely, 3=Frequently, 4=Always).

**The questions from the dataset:**

1 - If one of us apologizes when our discussion deteriorates, the discussion ends.<br>
2 - I know we can ignore our differences, even if things get hard sometimes.<br>
3 - When we need it, we can take our discussions with my spouse from the beginning and correct it.<br>
4 - When I discuss with my spouse, to contact him will eventually work.<br>
5 - The time I spent with my wife is special for us.<br>
6 - We don't have time at home as partners.<br>
7 - We are like two strangers who share the same environment at home rather than family.<br>
8 - I enjoy our holidays with my wife.<br>
9 - I enjoy traveling with my wife.<br>
10 - Most of our goals are common to my spouse.<br>
11 - I think that one day in the future, when I look back, I see that my spouse and I have been in harmony with each other.<br>
12 - My spouse and I have similar values in terms of personal freedom.<br>
13 - My spouse and I have similar sense of entertainment.<br>
14 - Most of our goals for people (children, friends, etc.) are the same.<br>
15 - Our dreams with my spouse are similar and harmonious.<br>
16 - We're compatible with my spouse about what love should be.<br>
17 - We share the same views about being happy in our life with my spouse.<br>
18 - My spouse and I have similar ideas about how marriage should be.<br>
19 - My spouse and I have similar ideas about how roles should be in marriage.<br>
20 - My spouse and I have similar values in trust.<br>
21 - I know exactly what my wife likes.<br>
22 - I know how my spouse wants to be taken care of when she/he sick.<br>
23 - I know my spouse's favorite food.<br>
24 - I can tell you what kind of stress my spouse is facing in her/his life.<br>
25 - I have knowledge of my spouse's inner world.<br>
26 - I know my spouse's basic anxieties.<br>
27 - I know what my spouse's current sources of stress are.<br>
28 - I know my spouse's hopes and wishes.<br>
29 - I know my spouse very well.<br>
30 - I know my spouse's friends and their social relationships.<br>
31 - I feel aggressive when I argue with my spouse.<br>
32 - When discussing with my spouse, I usually use expressions such as ‘you always’ or ‘you never’ .<br>
33 - I can use negative statements about my spouse's personality during our discussions.<br>
34 - I can use offensive expressions during our discussions.<br>
35 - I can insult my spouse during our discussions.<br>
36 - I can be humiliating when we discussions.<br>
37 - My discussion with my spouse is not calm.<br>
38 - I hate my spouse's way of open a subject.<br>
39 - Our discussions often occur suddenly.<br>
40 - We're just starting a discussion before I know what's going on.<br>
41 - When I talk to my spouse about something, my calm suddenly breaks.<br>
42 - When I argue with my spouse, ı only go out and I don't say a word.<br>
43 - I mostly stay silent to calm the environment a little bit.<br>
44 - Sometimes I think it's good for me to leave home for a while.<br>
45 - I'd rather stay silent than discuss with my spouse.<br>
46 - Even if I'm right in the discussion, I stay silent to hurt my spouse.<br>
47 - When I discuss with my spouse, I stay silent because I am afraid of not being able to control my anger.<br>
48 - I feel right in our discussions.<br>
49 - I have nothing to do with what I've been accused of.<br>
50 - I'm not actually the one who's guilty about what I'm accused of.<br>
51 - I'm not the one who's wrong about problems at home.<br>
52 - I wouldn't hesitate to tell my spouse about her/his inadequacy.<br>
53 - When I discuss, I remind my spouse of her/his inadequacy.<br>
54 - I'm not afraid to tell my spouse about her/his incompetence.


## Stages of the project:

- Cheaking and cleaning the data.
- Conducting Exploratory Data Analysis.
- Modeling.

## Cheaking and cleaning the data:

This dataset has 54 features and one target which is labelled as "divorce" which has a value of zero for not-divorced and one for divorced.

The original dataset has 170 rows, but there were duplicates in the dataset so after removing those duplicated rows, I was left with 150 rows. 

The dataset got no missing values.

## Conducting Exploratory Data Analysis

The EDA results of that dataset were really surprising to me, I'm not a relationship expert myself but I had assumptions regarding what a marriage that would last would look like.

For example: I assumed that couples that stayed together know a lot about each other so I expected the answer for the questions from 21 to 30 to have a 3 or 4 answer from the couples who stayed together but in this dataset, those questions were mostly answered by 0 or 1! 


