Grouping objects such as text documents and images into categories of
substantive scientific relevance is as central as it is important to social
science research. Without some sort of classification, it would be difficult
make advancements in our conceptualization and measurement of the social
phenomena we study [@baileyTypologiesTaxonomiesIntroduction1994; @grimmerGeneralPurposeComputerassisted2011]. The availability to new kinds of
data at scale previosuly unimaginable to the social scientist warants the 
development of new methods to make sense of it. In this context, unsupervised
clustering methods provide an interesting way for scholars to learn patterns
and extract knowledge from unstructured data, such as images
[@zhangImageClusteringUnsupervised2022]. It has several benefits compared
to completely supervised methods. First of all, it is much less costly, since
it does not require a training set of images to be annotated with corresponding
categories. Secondly, unsupervised methods are well suited for an inductive
research agenda when the goal is also to discover new categories
[@grimmerMachineLearningSocial2021]. A principal challenge with
unsupervised methods such as clustering is that validation is very difficult.
How can we know that the clusters are ``correct'' or meaningful for our
specific substantive question, if we have no ground truth to compare them to?
Clustering is inherently subjective (there is rarely a single true clustering),
so it is also necessarily model dependent, since different algorithms encode
and optimize notions about distance and similarity differently. How to know
which algorithm will be suitable (if any) and produce valid results for our
specific task is to a large extent an open question
[@estivill-castroWhyManyClustering2002; @grimmerGeneralPurposeComputerassisted2011].
%Moreover, it is generally accepted that clustering is inherently subjective
%(the curious reader can search for the Uggly Duckling Theorem). So while
%clustering methods optimize some particular objective function, there is
%actually nothing objective about it. How to know which objective function to
%use (if any) will be suitable for our specific task?
While unsupervised methods applied to images in the social science is still in
its infancy, this question of validity has been studied and discussed
extensively in the context of text data and in particular unsupervised topic
models [@robertsStructuralTopicModels2014; @quinnHowAnalyzePolitical2010, @grimmerTextDataPromise2013; @dennyTextPreprocessingUnsupervised2018]. We can hopefully draw and learn a lot from
this literature, while keeping in mind that images are fundamentally different
from text, i.e. the atomic unit of text is a word wich caries meaning, while 
in images it is a pixel.

