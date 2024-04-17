# Sentiment-Analysis-and-Data-Anonymisation

This is a dump for all the code that was used, written, tested, iterated over for this project. This is not the code  that can be used out of the box. Going over different cells of the notebook, you might notice some errors. There errors were resolved in the future iterations, manipulated based on each file for a particular purpose. 

There are 4 files here. 
1. Finetuning: This file contains all the code that was used to finetune the model. Towards the end, you will see that code to export the trained model, import it manually and then manually test some tweets has been written.
2. Redaction and Faker : This file was first started to test how redaction can be performed. Once POC was done, it was further edited to have redaction and then faking performed in the same iteration. Along the way, different techniques were tried to test how checkpointing can be done and data can be store in batches incase of failures.
3. entity_analysis_results: This is a checkpoint file used to track progress of file2. If the code crashes, we use the content here to start again.
4. Results: this is not a file that was generated through code but was manually created based on the results of numerous iterations.
