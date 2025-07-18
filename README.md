# SceneScribe 🖼️🗣️
SceneScribe is a project that aims to generate natural language captions for images. It uses a deep learning model called Blip-image-captioning-base to encode the visual features of an image and decode them into a meaningful sentence. The model is trained on the Flickr30k dataset, which contains 30,000 images and five captions for each image.



# Getting Started

To get started with using this tool, you might want to clone or download the repository.

```bash
git clone https://https://github.com/JohnPaulGummapu/SceneScribe
cd SceneScribe
```

# Requirements 📋
You can install the dependencies by running:

``` bash
pip install -r requirements.txt
``` 

# Usage 🚀
To use this project, you can either run it as a command-line tool or as a web interface.

### Command-line tool 💻
To run the project as a command-line tool, you can use the following command:

```bash
python caption.py --image <path_to_image>
```
This will generate a caption for the image and print it to the standard output.

### Web interface 🌐
To run the project as a web interface, you can use the following command:

```bash
python app.py
```
This will launch a Flask server and open a web page in your browser. You can then upload an image and see the generated caption.

# Contribution 💪
This project is open source and welcomes any contribution to fine-tune the model or improve the user experience. You can fork this repository and submit a pull request with your changes. Please follow the code style and documentation guidelines.

