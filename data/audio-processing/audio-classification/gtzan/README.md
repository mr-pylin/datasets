# 🗃️ GTZAN Audio Dataset
   - A widely used dataset for music genre classification, containing audio files from 10 different music genres.
   - **Reference Paper**:
      - [**Musical genre classification of audio signals**](https://ieeexplore.ieee.org/document/1021072) by [*George Tzanetakis*](https://ieeexplore.ieee.org/author/37295800700) and [*Panos Cook*](https://ieeexplore.ieee.org/author/37299003100) in 2002.
   - **Creators**:
      - [George Tzanetakis](https://ieeexplore.ieee.org/author/37295800700)
      - [Panos Cook](https://ieeexplore.ieee.org/author/37299003100)

## 🔍 More Details
   - **Total Number of Tracks**: 1,000
   - **Genres**: 10 (Blues, Classical, Country, Disco, HipHop, Jazz, Metal, Pop, Reggae, Rock)
   - **Number of Tracks per Genre**: 100
   - **Audio Length**: Each track is exactly 30 seconds long.
   - **Audio Format**: WAV (Waveform Audio File Format)
   - **Bitrate**: 1,411 kbps (for 16-bit PCM WAV files)
   - **Sampling Rate**: 22,050 Hz (samples per second)
   - **Channels**: Mono (1 channel)

### 🆔 Track IDs and Sequences
The audio tracks are named with a convention based on their genre and an ID number. The files are arranged sequentially by genre, as follows:
<table style="margin:0 auto;">
   <thead>
      <tr>
         <th rowspan="2">File Naming Sequence</th>
         <th colspan="10" style="text-align: center;">Genres</th>
      </tr>
      <tr>
         <th style="text-align: center;">Blues</th>
         <th style="text-align: center;">Classical</th>
         <th style="text-align: center;">Country</th>
         <th style="text-align: center;">Disco</th>
         <th style="text-align: center;">HipHop</th>
         <th style="text-align: center;">Jazz</th>
         <th style="text-align: center;">Metal</th>
         <th style="text-align: center;">Pop</th>
         <th style="text-align: center;">Reggae</th>
         <th style="text-align: center;">Rock</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>From</td>
         <td>blues.00000.wav</td>
         <td>classical.00000.wav</td>
         <td>country.00000.wav</td>
         <td>disco.00000.wav</td>
         <td>hiphop.00000.wav</td>
         <td>jazz.00000.wav</td>
         <td>metal.00000.wav</td>
         <td>pop.00000.wav</td>
         <td>reggae.00000.wav</td>
         <td>rock.00000.wav</td>
      </tr>
      <tr>
         <td>To</td>
         <td>blues.00099.wav</td>
         <td>classical.00099.wav</td>
         <td>country.00099.wav</td>
         <td>disco.00099.wav</td>
         <td>hiphop.00099.wav</td>
         <td>jazz.00099.wav</td>
         <td>metal.00099.wav</td>
         <td>pop.00099.wav</td>
         <td>reggae.00099.wav</td>
         <td>rock.00099.wav</td>
      </tr>
   </tbody>
</table>

### 📊 Dataset Usage
The GTZAN dataset is often used in machine learning and deep learning projects for:
   - **Music Genre Classification**: Identifying the genre of a music track based on audio features.
   - **Feature Extraction**: Evaluating which features best represent musical styles and genres.
   - **Model Evaluation**: Comparing the performance of different machine learning models in the classification task.

## 📥 Access the Dataset
   - The GTZAN dataset is not directly included in this repository due to its size **[~1.3 GB]**.
   - You can download the dataset from the following link:
      - [**kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification**](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)
   - ⚠️ **Known Issues**:
      - `jazz.00054.wav` is **corrupted**, make sure to **delete**/**replace**/**skip** this audio when loading the dataset from above link.
      - You can replace the corrupted audio with [**this**](https://drive.google.com/file/d/1ReErUq7w1T_FOkJqBsjFhOlpbw1ukiG8/view?usp=sharing) one (thanks to [*Rémi Mignot*](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification/discussion/158649#1860479) 👏).
   - ✍️ **Notes**:
      - If the equality of audio lengths is important to you, **not** all the audio files have the **exact** same length.
      - **Most** of the audio files e.g., `blues.00000.wav`, have a length of 30.01 seconds (which can be considered a **"valid length"**).
      - **Some** of the audio files e.g., `classical.00042.wav`, are **longer** than usual (and needs to be **clipped**).
      - **Some** of the audio files e.g., `classical.00051.wav`, are **shorted** than usual (and needs to be **padded**).

### 📄 Contents within the Dataset
   - **genres_original/**
      - This folder contains the 1,000 audio tracks arranged by genre.
      - Each genre has 100 tracks, and the audio files are named following the pattern `genre.00000.wav` to `genre.00099.wav`.
   - **images_original/**
      - This folder contains a set of **Mel spectrogram images** (in PNG format) corresponding to each audio file in the **genres_original/** folder.
      - These images can be used for machine learning tasks such as **image-based** genre classification.
   - **features_30_sec.csv**
      - this CSV file contains extracted features over the entire **30-second** length of each audio track.
      - It includes features like **spectral contrast**, **zero-crossing rate**, and **Mel-frequency cepstral coefficients (MFCCs)** for each audio clip.
   - **features_3_sec.csv**
      - This CSV file contains extracted features from the audio tracks, computed over **3-second** windows.
      - It includes features like **spectral contrast**, **zero-crossing rate**, and **Mel-frequency cepstral coefficients (MFCCs)** for each audio clip.

# 📄 License
This dataset does not appear to have a specific license or formal usage agreement provided by its creators or maintainers.  
Users are encouraged to verify usage terms if needed.

# ©️ Credit
Visit [**Marsyas Audio Software**](http://marsyas.info/downloads/datasets.html) [DEAD] or [**Kaggle**](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification) for more information.