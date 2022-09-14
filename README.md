# MscProjTREC

To set up the project GCS connection needs to be set up and a google bucket with the name trecuofg is set up and all the data is uploaded into the buckets and is mounted to the colab. TREC CAsT tools available in the GitHub repository are required for pre-processing and downloading the 2021 Manual Evaluation topics. As the datasets took a considerable amount of storage, Google cloud storage Virtual instances and buckets are used. Ubuntu-2204 Operating system, 450 GB storage and e2-standard-4(4 cores) are the configurations for the virtual instance. Preprocessing and Indexing is done in the Anaconda Navigator environment which is Python 3. The remaining implementation is done in Google collab for efficient use of subscription charge given overhead when registered under it.



The following are the datasets used and generated in this project:

Raw Datasets: https://gla-my.sharepoint.com/:f:/g/personal/2663312p_student_gla_ac_uk/EsVND9JS5fZEsOeBKhhJXt0Bqwe83H3Kh94L_L5ETpUkKg?e=bCSDWl


Reformulated/Pre-processed Dataset: https://gla-my.sharepoint.com/:f:/g/personal/2663312p_student_gla_ac_uk/Esvk4cIMCj1FlCZzD1sKi-MBBIEeTblB-Z_tkz11k1AUjw?e=xfblc3

Indexed Data: https://gla-my.sharepoint.com/:f:/g/personal/2663312p_student_gla_ac_uk/En6kHP4-nP5IjnERb6gQnA0B4SML32ieYGqrCLLSmpy1_A?e=jAXC1N

Canard Dataset used for T5 large: https://gla-my.sharepoint.com/:f:/g/personal/2663312p_student_gla_ac_uk/EqEh7FQdkJZGkbuLWeNXvjoB38iKjSpNqKn3A6abjfEpNA?e=19wKcb

Scores: https://gla-my.sharepoint.com/:f:/g/personal/2663312p_student_gla_ac_uk/EpDgOdRX7TdOkXUKk1a6ZokB35-0q_A_sJxGyG0TF1BxSA?e=xVMnq0



