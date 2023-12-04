Open In Colab
  - https://colab.research.google.com/github/garnold2020/HITL-Art/blob/main/src/Bias_Benchmarking.ipynb
  - Open, insert ngrok auth token after [registering](https://dashboard.ngrok.com/login), scroll down to "Testing Section", click on it, click "Runtime" -> "Run before"
    
Weekly Meeting Minutes, Survey, etc. (Request Access)
  - https://drive.google.com/drive/folders/1WLycaqx58UtYXURz1CrHp3XcY_dej7Am?usp=share_link

Task Tracking
  - See Projects -> HITL-Art-Kanban

Folder Structure
- **local_folder**
  - **static** (*Hosted on Github*)
    - styles.css
  - **templates** (*Hosted on Github*)
    - start.html
    - index_plotly.html
  - **data** *Hosted on Azure*
    - **prompt_filler_1** (*E.g., "High quality photo of a \_ person"*)
      - **model_1**
        - **prompt_images**
          - prompt_1
            - image1.png
            - ...
            - embeddings.csv
          - prompt_2
            - image3.png
            - ...
            - embeddings.csv
        - **cluster_images**
          - cluster_1
            - image5.png
            - ...
            - embeddings.csv
          - cluster_2
            - image7.png
            - ...
            - embeddings.csv
        - ...
        - clusters.json
      - **model_2**
        - ... (same structure as model_1)
      - **model_3**
        - ... (same structure as model_1)
    - **prompt_filler_2**
      - ... (same structure as prompt_filler_1)
    - ...
