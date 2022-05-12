# Archetypal Character Analysis on Literary Fiction for Young Adults
Leveraging the power of NLP, we analyse the lead characters of literature written for the youth. We investigate if the characters archetype is correlated with its gender, as well as with the overall success and public perception of the book. Furthermore, factors like the authors gender and the publishing year are con- sidered. Through our work, we aim to identify if a gender gap in young adult literature exists.

## Documentation
Please refer to the project report or the poster (presented at UC Berkeley Digital Humanities Fair 2022) for more details on the goals and findings of this project. 

## Code
- archetype_classifier.ipynb -> Various models to predict archetype category labels, based on a book description
- archetype_analysis.ipynb -> Analysis of the annotated data and predicted character/author gender distribution

## Data
- /70
  - Includes 1000 book descriptions and hand-annotated archetype category label of main character
  - Divided into train, dev, following a 60:20:20 split
- /final_data
  - Merged data from UCSD Book Graph with predicted/annotated labels
  - book_data includes information about 13782 youth books
  - character_data includes more detailed information about the main character of the first 1000 of these books

Please note that the data provided through this repo is only a small portion and processed version of the original dataset.
The original data set was downloaded in March 2022 from: https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home
Please visit that website or read the following papers for more information about the datasets.
- Mengting Wan, Julian McAuley, "Item Recommendation on Monotonic Behavior Chains", in RecSys'18.
- Mengting Wan, Rishabh Misra, Ndapa Nakashole, Julian McAuley, "Fine-Grained Spoiler Detection from Large-Scale Review Corpora", in ACL'19.

The data is publically available but for academic use only.
