# Spotify Recomendation System Based on Song Properties

This is my first personal project . It is small and not too good, but any way I will try to describe you how it works and how to use it

## 1) The Main idea and used technologies

The idea was pretty simple:
1) I want to look songs, which sound like any given referencee.
2) Based on downoalded data ( with almost all songs for the end of 2025 - 255 mill. songs - 12 gb of parquet. ) find out songs with similar properties.

 Amount of the data is the reason why I chose a Polars lib

 ## 2) How work with it

2.0) Clone the repository

2.1) Creat a folder in the main and call it 'data_general'

2.2) In this folder paste data, which you can download from [this](https://huggingface.co/datasets/ozefe/spotify_audio_features/tree/main/data)

2.3) Put the URI of your reference song here
 <img width="1360" height="50" alt="изображение" src="https://github.com/user-attachments/assets/72cb1ec7-32dc-406b-a27b-d89b782ad3c9" />

2.4) If you want, change the real_multiplier:
<img width="776" height="38" alt="изображение" src="https://github.com/user-attachments/assets/a692fe21-e961-49d4-bddc-66fee7c6a3d2" />

2.5) Run all

2.6) Open new csv in folder 'output' 

2.7) Cut out any line like this one.
<img width="433" height="22" alt="изображение" src="https://github.com/user-attachments/assets/0bf1de7a-ab82-4393-a662-b846fe4a4f42" />

2.8)Put in Spotify Search bar

<img width="1783" height="77" alt="изображение" src="https://github.com/user-attachments/assets/dedb7283-b2a1-4492-a193-e7b0356a6b2a" />

## 3) Honest conclusion

Honestly, I expected more. Main problem of this, is that similar properties != similar sound. Even with all filters only 1/10 or 1/15 is actualy similar to the reference. This is a fundamental problem and a reason why I decided to not support the project in the future. But, if you want to tast a project, I appreciate this.

