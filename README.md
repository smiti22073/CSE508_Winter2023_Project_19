# CSE508_Winter2023_Project_19

## The submissions done includes three different stages of the project:

1. Baseline Results - In this submission, individual music recommendation and book recommendation systems were developed.
                      The music recommendation system was for a dataset containing Hindi songs.

2. Mid-Project Review - In this stage of the project, the music and book recommenders systems were connected for some genres of the music dataset.
                        At this stage, the number of book genres was decreased on the basis of human understanding.
                        A basic UI was also developed at this point.

3. Final Project Deliverables - This is the final stage of the project. Here the book genres were clustered using cosine similarity and word embedding.
                                The music and book recommendation systems were connected fully and the same was also extended to be applied to a dataset
                                having English songs. At this stage, a book-to-book recommendation system was also developed.
                                An interactive UI was developed for showcasing the live results of our project where music or book can be input and
                                similar books can be recommended to the system.

## Following are the installation requirements for running this project:
pip install numpy==1.23.5
pip install audioread==3.0.0
pip install pandas==2.0.1
pip install librosa==0.8.0
pip install tabulate==0.9.0
pip install flask==2.3.2
pip install sklearn==1.2.2
pip install lightgbm==3.3.5
pip install nltk==3.8.1

After the installations of these packages, the user needs to -
1. Git clone the repository: !git clone https://github.com/smiti22073/CSE508_Winter2023_Project_19.git
2. Run main.py file.
