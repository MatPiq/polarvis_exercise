Grouping objects such as text documents and images into categories of
substantive scientific relevance is as central as it is important to social
science research. Without some sort of classification, it would be difficult
make advancements in our conceptualization and measurement of the social
phenomena we study [@baileyTypologiesTaxonomiesIntroduction1994; @grimmerGeneralPurposeComputerassisted2011]. 
The availability to new kinds of data at a scale previosuly unimaginable to the
social scientist warrants the need to develop new methods to make sense of it. In
this context, unsupervised clustering methods provide an interesting way for
scholars to learn patterns and extract knowledge from unstructured data, such
as images [@zhangImageClusteringUnsupervised2022]. It has several benefits
compared to completely supervised methods. First of all, it is much less
costly, since it does not require a training set of images to be annotated with
corresponding categories. Secondly, unsupervised methods are well suited for an
inductive research agenda when the goal is also to discover new categories
[@grimmerMachineLearningSocial2021]. 

A principal challenge with unsupervised methods such as clustering is that
validation is very difficult. How can we know that the clusters are "correct"
or meaningful for our specific substantive question, if we have no ground truth
to compare them to? Clustering is inherently subjective (there is rarely a
single true clustering), so it is also necessarily model dependent, since
different algorithms encode and optimize notions about distance and similarity
differently. How to know which algorithm will be suitable (if any) and produce
valid results for our specific task is to a large extent an open question
[@estivill-castroWhyManyClustering2002; @grimmerGeneralPurposeComputerassisted2011].
While unsupervised methods applied to images in the social science is still in
its infancy, this question of validity has been studied and discussed
extensively in the context of text data and in particular unsupervised topic
models [@robertsStructuralTopicModels2014; @quinnHowAnalyzePolitical2010, @grimmerTextDataPromise2013; @dennyTextPreprocessingUnsupervised2018]. 
We can hopefully draw and learn from this literature, while keeping in mind
that images are fundamentally different from text, i.e. the atomic unit of text
is a word which caries meaning, while in images it is a pixel which without
context provides little to no information.

In this tab we will briefly detail how the clustering of the images was
performed (see next [section](clustering.md)), as well as discuss additional
validation strategies that can complement and guide the more direct type of
validation we performed in the exercise by looking at image collocations (see
[section](validation_strategies.md)). In doing this, we will focus on intuition,
try to skip technical details and instead provide references where relevant. We
also want to stress that this is **not** part of the exercise—this is purely
intended for you to look at in case you are interested in some additional
background and information.

