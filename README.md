# Using Deep Learning to Annotate the Protein Universe

Understanding the relationship between amino acid sequence and protein function is a long-standing problem in molecular biology with far-reaching scientific implications. Despite six decades of progress, state-of-the-art techniques cannot annotate 1/3 of microbial protein sequences, hampering our ability to exploit sequences collected from diverse organisms. In this code, i explore an alternative methodology based on deep learning that learns the relationship between unaligned amino acid sequences and their functional annotations across all 17929 families of the Pfam database. 
![amino-acids-cover](https://user-images.githubusercontent.com/108609519/201396947-91987829-a3ef-489a-8ae7-12b7d65aeb60.jpg)

My study focused on only 600 families out of all the families included in the dataset.

# Model Architecture

|  | #Architecture    |
| :---:   | :---: |
| Model | ![download (83)](https://user-images.githubusercontent.com/108609519/201386439-1ad68172-1c0f-4b6f-b7c6-922755cdc40d.png)  |


# Result:

|  | (Training) Accuracy vs Validation Accuracy    | (Training) Loss vs Validation Loss    |
| :---:   | :---: | :---: |
| result | ![download (85)](https://user-images.githubusercontent.com/108609519/201387044-cc2e769a-cd5a-46da-bf84-c75252a8bb2f.png)   | ![download (84)](https://user-images.githubusercontent.com/108609519/201386961-8a1206bf-9d5d-4bce-85b5-c42a0160beb4.png)   |

# Model Evaluation
![image](https://user-images.githubusercontent.com/108609519/201387251-deb8bf9d-8bb3-4e0d-8472-5a9484cd0592.png)

# Notice:
pre-trainde model: https://drive.google.com/file/d/12ZsTkRlEPG8DL50Wb_tdDmHINv9pKTbj/view?usp=share_link

pre-trainde model weights: https://drive.google.com/file/d/1bj4uJBu7rbO6OaIZg--IkOC5yke_WiLn/view?usp=share_link

Tokenizer: https://drive.google.com/file/d/1-01g2VBsa6hMSCRB-DGylfffJDrCRXu4/view?usp=share_link

# References:
https://www.biorxiv.org/content/10.1101/626507v4.full.pdf




