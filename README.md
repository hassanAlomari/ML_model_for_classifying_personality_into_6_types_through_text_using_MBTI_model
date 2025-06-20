# ML_model_for_classifying_personality_into_6_types_through_text_using_MBTI_model
Classify your personality type into 6 types, according to the MBTI model, by attaching a post to the model on Facebook or a tweet on Twitter.

First, to run the project, we must download the following libraries:
1. pandas   -->   (pip install pandas)

-----------> to applyTF-IDF and linear SVC:

2. sklearn  -->   (pip install sklearn)
3. numpy    -->   (pip install numpy)

nots: "Large data can take time to convert to TF_IDF and apply Linear SVC algorithm."

Secondly, the data must be downloaded to the device in CSV format and read at the beginning of the code.

Thirdly, running the code will work immediately , When running it will load a little, due to the large amount of data.

Fourth, if you want to test the model with your own text, go to the word written in the code "test model: ..." and put the text you want in --> query_tf_idf = v_tfidf.transform(['text']))
Make sure there is --> [] in the code.

resulte : accuracy  -->  0.86 
