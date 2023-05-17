<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="AutoTubeGPT" />

  &#xa0;

  <!-- <a href="https://AutoTubeGPT.netlify.app">Demo</a> -->
</div>

<h1 align="center">AutoTubeGPT</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/jordanistan/AutoTubeGPT?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/jordanistan/AutoTubeGPT?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/jordanistan/AutoTubeGPT?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/jordanistan/AutoTubeGPT?color=56BEB8">

</p>


<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/jordanistan" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

Overview
The YouTube Page Generator is a unique tool designed to help content creators brainstorm and generate YouTube video titles and scripts. It leverages the power of OpenAI's language model, Wikipedia's extensive database, and the Streamlit framework to provide a highly interactive and user-friendly interface.

The app takes in a user-provided prompt, uses it to generate a YouTube video title, performs research on the topic via Wikipedia, and then produces a script for the video based on the generated title and the Wikipedia research.

The app is built with Python and utilizes several libraries and APIs to achieve its functionality.

## :sparkles: Features ##
:heavy_check_mark: OpenAI API: The app utilizes the OpenAI API to generate creative YouTube video titles and scripts. The OpenAI language model is trained on a wide range of internet text and can generate human-like text based on the provided prompts.

:heavy_check_mark: Wikipedia API Wrapper: This is used to fetch research information about the user-provided prompt from Wikipedia. This data is then used to enhance the video script generation process.

:heavy_check_mark: Prompt Templates: The app uses two main prompts to interact with the OpenAI API. The first generates a YouTube video title about the given topic, and the second generates a video script based on the title and the Wikipedia research.

:heavy_check_mark: Memory Buffers: The app uses conversation buffers to keep track of the chat history for both the title generation and script generation processes. This allows users to see how the generated title and script evolved over time.

:heavy_check_mark: Interactive UI: The app uses Streamlit, a framework for building interactive web applications with Python, to deliver a user-friendly interface. Users can input their prompts, see the generated title and script, and also view the title history, script history, and Wikipedia research in expandable sections.

## :rocket: How to Use ##

Input Prompt: Enter your desired topic or idea in the text input field labeled "Plug in your prompt here".

Generate Title & Script: After you've entered your prompt, the app will automatically generate a YouTube video title and script. The generated title and script will be displayed on the page.

View History & Research: You can click on the 'Title History', 'Script History', and 'Wikipedia Research' expanders to view the respective information.

## :white_check_mark: Dependencies

Python 3.6 or later
OpenAI's GPT-4
Streamlit
langchain
chromadb 
tiktoken
Wikipedia API

Install Required Libraries: The app uses Streamlit for the interface and makes API calls to OpenAI and Wikipedia. These libraries can be installed using pip, Python's package installer. Open your terminal, navigate to the directory containing the Python file, and run the following commands:


```pip install streamlit langchain openai chromadb tiktoken wikipedia```


## :white_check_mark: Environment Variables
The app uses an environment variable to store the OpenAI API key. You will need to set this in your environment or in the apikey.py file.

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/jordanistan/AutoTubeGPT

# Access
$ cd AutoTubeGPT

# Install dependencies
$ pip install streamlit langchain openai chromadb tiktoken wikipedia

# Run the project
$ streamlit run AutoTubeGPT.py 

# The server will initialize in the <http://localhost:8501>
```

## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.


Made with :heart: by <a href="https://github.com/jordanistan" target="_blank">El Gato</a>

&#xa0;

<a href="#top">Back to top</a>
