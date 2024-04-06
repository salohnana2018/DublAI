
# DublAI: AI-Powered Dubbing Application

Welcome to DublAI, an innovative AI-based application designed for seamless dubbing from English to Arabic and vice versa. Leveraging the latest in artificial intelligence, DublAI combines the prowess of OpenAI's Transformer models, the Whisper model for speech recognition and generation, and Cuco API for efficient language translation. With a user-friendly interface powered by Gradio, DublAI offers an accessible and efficient solution for professionals and enthusiasts alike to overcome language barrie...

## Features

- **Bi-directional Dubbing:** Effortlessly dub content from English to Arabic and from Arabic to English, making your media accessible to a broader audience.
- **State-of-the-Art AI Models:** Utilizes OpenAI's advanced Transformer and Whisper models for accurate speech recognition and generation.
- **Cuco API Integration:** Leverages the power of Cuco API for seamless and accurate language translation, ensuring the essence of the content remains intact.
- **Gradio Interface:** Offers a simple and intuitive Gradio-based web interface, making it easy for users to upload, translate, and download dubbed content.
- **High-Quality Audio Output:** Produces clear and natural-sounding dubbed audio, thanks to the advanced AI algorithms and models at its core.

## Repository Contents

- `requirements.txt`: Contains the list of libraries necessary for running DublAI, with a focus on excluding pre-installed libraries in Google Colab to streamline setup.
- `Audio_translation_Voice_cloning_Gradio.ipynb`: A Colab notebook that contains a demo of DublAI.

## Getting Started

### Prerequisites

Before you begin, ensure you have a Google Colab account for running the notebook. The `requirements.txt` file has been carefully curated to include only the necessary libraries not preinstalled in Google Colab, ensuring an efficient setup process.


### Running DublAI

Navigate to `Audio_translation_Voice_cloning_Gradio.ipynb` and open it in [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/salohnana2018/DublAI/blob/main/Audio_translation_Voice_cloning_Gradio.ipynb).



2. **Install Dependencies**

   Run the first cell in the notebook to install dependencies from `requirements.txt`.

3. **Follow the Notebook Instructions**

   The notebook will guide you through uploading your media, selecting the target language, processing the dubbing, and downloading your dubbed media.

## How It Works

1. **Upload Your Media:** Through the Gradio interface in the notebook, upload the media file you wish to dub.
2. **Select Target Language:** Choose whether you want to dub the content into English or Arabic.
3. **Process:** Follow the instructions in the notebook to dub your media. DublAI will first transcribe the audio using OpenAI's Whisper model, translate the text using Cuco API, and finally generate the dubbed audio in the target language.
4. **Download:** Once processed, you can download the dubbed version of your media directly through the interface.




