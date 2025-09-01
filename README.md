# e-Therapist_R&D
- This is a credited course DS691_2024 (R&D Project), that includes implementation and deployment of a chatbot to assist mental health patients.
- Two LLMs are considered here LlaMa-2 and Mistral (generative) for building the chatbot.
- These two LLMs are fine-tuned on a conversational dataset (MotiVate) for generating motivational and empathetic responses.
- The MotiVate dataset consists of 4 conversational text data for depression, anxiety, OCD and PTSD. The data is taken from a forum, where conversation is between a patient (diagnosed with mental health condition) and a psychologist. There are 7000 dialogues in the dataset, comprising alternating utterance text (multi-turn dialogues) between patient and psychologist.
- As a part of data analysis, sentiment analysis is conducted on the data, where the result shows that negative sentiment prevails in the patients' diaglogues in majority of cases. Word clouds have also been constructed to see the frequent word usages of the patients. And figures are represented in the report.
- Here two files are provided, that includes code for fine-tuning LlaMa and Mistral model on the MotiVate dataset.
- The evaluation of the generated responses are done using metrics like Bleu score and perplexity.
