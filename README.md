# BookGenreClassification
Books are the source of knowledge. There are
hundreds and thousands of books in libraries. To reduce
the time to search for a particular book in the aisles of
the library, we can set up a system to scan the image of
the book cover or enter the book title to give the genre
and aisle number according to the title. Digitalization, in
the world of books, is possible by using, Deep Learning
and Machine Learning models. The learning capability
of the designed model helps us to predict the genre of
the books.

There are multiple ways to organize books in
libraries. For instance, one can use the Authors and
book title, or date published and book title. However,
organizing books based on genres, makes life easier for
both the reader and librarian. There are multiple type of
genres. The report only focusses on 30 of them which
are presented in the Book Genre Classification dataset
extracted from the paper

In the project, the genres of the books are identified
based on the title of the book. The book cover image is
used to extract the title using Optical Character Recognition
(OCR). OCR is implemented using tesseract in
OpenCv library in Python. To process the obtained text,
the latest technique like Natural Language Processing
(NLP) is used. The obtained features are passed to
the Recurrent Neural Network (RNN) model which has
Long-Short Term Memory (LSTM) layer
A
book cover image is captured and passed to OCR module
to identify and recognize the title. The obtained title is
preprocessed using NLP techniques and passed to the
trained LSTM model to obtain the genre of the book.


Accuracy is used as an evaluation metric to evaluate the
performance of the model.
The project tries to identify the comparison between
different ways of generating the word embeddings from
the corpus of text dataset available. Moreover, multiple
types of deep learning models like CNN, RNN, simple
neural network are developed to compare their performances.
The entire project is developed in Python 3.6
language and utilizes its various libraries like Keras,
numpy, pandas, matplolib, gensim, scikit-learn, NLTK,
Open-CV, pytesseract, Wordcloud.

Approach
