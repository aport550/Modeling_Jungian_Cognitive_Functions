# Modeling_Jungian_Cognitive_Functions
Using Machine Learning Techniques to Classify Possession of Jungian Cognitive Functions

# Introduction

The famous 20th century psychologist Carl Jung formulated a theory of personality that included the identification
of 8 cognitive functions that would help explain the differences between how different people processed information.  

Jung theorized that each person possesses a primary method of perceiving the world (perception in this case meaning
the manner in which they filter and encode  information extracted from their senses) and a primary method 
of judging those perceptions.  Jung believed people either perceive via what he referred to as sensing or intuition
and in either internalized or externalized orientations(introverted vs extraverted).    He also identified
judgment as either through what he called "feeling" or "thinking" in either introverted or extraverted manners. 
Therefore, per the jungian theory, each person possess a primary method of perception (introverted intuition,
extraverted intution, introverted sensing or extraverted sensing) and a primary method of judgment (
introverted feeling, extraverted feeling, introverted thinking, extraverted thinking).   They also cannot possess
primary perceiving and judging functions that are of the same orientation meaning that for example one cannot
possess both extraverted perception and extraverted judgment.  Instead, per the classification system,
one must possess one extraverted primary cognitive function and one introverted primary cognitive function.

Note that the more popular Myers Briggs Type Indicator was created somewhat based on these Jungian cognitive functions
but instead assigned 4 basic dichotomies for introversion/extraversion, sensing/intuition, feeling/thinking and
perceiving/judging.  

The purpose of this project is to try and determine if processing text can predict the Jungian Functions
the author of the text possesses.  Note that we will classify functions in this case one by one and try to
find which methods work best in classifying each cognitive function separately.  We will not necessarily simply
use multiclass classification as what model works best in predicting one cognitive function may not work best in 
predicting another.  

