# FindYourTherapist
Front-end for website matching patients with therapists with whom they share common ground

## Inspiration
Culturally sensitive therapy emphasizes the understanding of a patient’s background (i.e. childhood and life experiences, identification, religion, and ethnicity). Having such an understanding may result in a more nuanced and impressionable rapport between the therapist and patient. Conversely, shortfalls in understanding the patient’s cultural background can lead to misinterpretation of their symptoms. In the diverse community of North America, it is important for patients to find therapists who have an appreciation for their background.

## What it does
The app surveys the patient’s demographic information, life experiences, cultural background and preferred counselling style in order to generate recommended therapists. The therapist can similarly match with patients. The app extracts the semantic representation of the survey responses by transforming it into higher-dimensional numerical vectors via machine learning. It then compares the cosine distances against similar representations within a registry of therapists and patients. As a result, the similarity between the diverse narratives can be optimized. The app then recommends a list of potential therapists based on shared experiences.
FindYourTherapist harnesses state-of-the-art natural language processing to produce a context-aware analysis of the patient’s narrative. The app seeks similarities between patients and therapists on the style of speech, expression of opinions and lived experiences in order to produce an optimal match with regards to cultural sensitivity.

## How we built it
The front end of the software is built with HTML, CSS, and JS. The questionnaire is designed to intake both demographic data (such as age, gender, ethnicity & religion) and narrative data (regarding upbringing and life experience). For the demographic data, the patient can assign each category with a ‘weight factor’ to indicate how important that aspect is for them. The text data from the entire survey is then sent to the back-end API.

## Link to website
[FindYourTherapist](http://www.findyourtherapist.me/)

## License
[MIT](https://choosealicense.com/licenses/mit/)
