# Final Data Project README file

Final project for Ironhack Bootcamp of Data Analytics: NLP text generation for haikus and lyrics

![Image](https://res.cloudinary.com/springboard-images/image/upload/q_auto,f_auto,fl_lossy/wordpress/2019/05/aiexcerpt.png)

---

### :raising_hand: **Models Summary**

This project contains three different NLP models with different approaches:

- LSTM for Haikus generation
	Dataset: https://www.kaggle.com/hjhalani30/haiku-dataset
	This is the simpler one. A sequential model containing the following layers:
	Embedding
	Bidirectional LSTM
	Dense

- LSTM for Lyrics generation
	Dataset: included in the repository
	Sequential model containing these layers:
	Embedding
	Bidirectional LSTM
	Dropout
	Unidirectional LSTM
	Embedding

- GPT-2 for Haikus generation


### :wrench: **Configuration**
Requeriments, prerequisites, dependencies, installation instructions.


### :file_folder: **Folder structure**
```
└── final_project
    ├── .gitignore
    ├── README.md
    ├── LSTM_haiku
    │   ├── raw_data
    │   ├── processed_data
    │   ├── LSTM_haiku_preprocessing.ipynb
    │   └── LSTM_haiku_train.ipynb
    │
    ├── LSTM_extremoduro
    │   ├── raw_data
    │   ├── processed_data
    │   ├── LSTM_extremoduro_preprocessing.ipynb
    │   └── LSTM_extremoduro_train.ipynb
    │
    └── gpt2_haiku
        ├── raw_data
        ├── processed_data
        ├── gpt2_haiku_preprocessing.ipynb
        └── gpt2_haiku_train-ipynb

```


---
