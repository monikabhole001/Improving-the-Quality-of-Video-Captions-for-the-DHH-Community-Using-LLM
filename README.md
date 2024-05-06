
# Improving the Quality of Video Captions for the DHH Community Using LLM

In an era saturated with digital content, ensuring universal accessibility, particularly for the DHH community, is of utmost significance. Captions are an essential component for the DHH community to access audiovisual resources. Nevertheless, they encounter substantial challenges while trying to access online video material.  While captions have improved accessibility to some degree, the existing captioning methods, often fail to capture the exact meaning and the context. This inadequacy might also cause the distorted meaning or omitting of the essential information that will disrupt the accessibility of the content to DHH communicators. So the project aims to use the capabilities of LLM to improve the quality of video captions.


## Acknowledgements

 - [Accessibility in Online Courses: Understanding the Deaf Learner](https://doi.org/10.1007/s11528-019-00385-3)
 - [Improving Real-Time Captioning Experiences for Deaf and Hard of Hearing Students](https://doi.org/10.1145/2982142.2982164)
 - [Understanding BLEU and ROUGE score for NLP evaluation](https://medium.com/@sthanikamsanthosh1994/understanding-bleu-and-rouge-score-for-nlp-evaluation-1ab334ecadcb)


## Dataset

- Download the dataset here - https://drive.google.com/drive/folders/17TFsjQMDKk5pOiqhfyg24vw2EJSSbplw?usp=sharing 
- Excel Sheet-1 containing the YouTube link used for generating Dataset - https://docs.google.com/spreadsheets/d/1EDoaB_8-qUaNzIbjFBtd-nHtkY0YC9reRBRF0jafoE8/edit?usp=sharing
- Excel Sheet-2 containing Youtube_Captions, Reference_Captions, ChatGPT3.5_Captions, Llama2_Captions and Evaluation_Results- https://docs.google.com/spreadsheets/d/1p9M-ZXef9KtHLCn0jeM1Xg-z5Yyc3bBZfTR6pNM8-r8/edit?usp=sharing 


## Documentation

- [Download_YT_Video.ipynb](https://github.com/monikabhole001/Improving-the-Quality-of-Video-Captions-for-the-DHH-Community-Using-LLM/blob/main/Download_YT_Video.ipynb) : This file downloads the YouTube video using the YouTube videos link given in Excel Sheet-1
- [YouTube_Caption_Generator_For_Dataset.ipynb](https://github.com/monikabhole001/Improving-the-Quality-of-Video-Captions-for-the-DHH-Community-Using-LLM/blob/main/YouTube_Caption_Generator_For_Dataset.ipynb) : This file generates the YouTube video captions and store it in Excel Sheet-2
- [Evaluation.ipynb](https://github.com/monikabhole001/Improving-the-Quality-of-Video-Captions-for-the-DHH-Community-Using-LLM/blob/main/Evaluation.ipynb) : This file calculates the results using WER, ROUGE and BLEU stores it in Excel Sheet-2
- [T5.ipynb](https://github.com/monikabhole001/Improving-the-Quality-of-Video-Captions-for-the-DHH-Community-Using-LLM/blob/main/T5.ipynb) : This file contains implementation for T5
- [GPT2.ipynb](https://github.com/monikabhole001/Improving-the-Quality-of-Video-Captions-for-the-DHH-Community-Using-LLM/blob/main/GPT2.ipynb) : This notebook file  contains code of OpenAI's GPT-2 model. 
- [Gemini.ipynb](https://github.com/monikabhole001/Improving-the-Quality-of-Video-Captions-for-the-DHH-Community-Using-LLM/blob/main/Gemini.ipynb) : Contains implementation for Gemini.
- [GPT3_5_openai_api_Azure.ipynb](https://github.com/monikabhole001/Improving-the-Quality-of-Video-Captions-for-the-DHH-Community-Using-LLM/blob/main/GPT3_5_openai_api_Azure.ipynb) : This notebook file is related to using OpenAI's GPT-3.5 model via their API, integrated with Microsoft Azure services.
- [llama2_7b_ggml.ipynb](https://github.com/monikabhole001/Improving-the-Quality-of-Video-Captions-for-the-DHH-Community-Using-LLM/blob/main/llama2_7b_ggml.ipynb) : Contains implementation for llama2-7B-GGML
- [llama2_replicate.ipynb](https://github.com/monikabhole001/Improving-the-Quality-of-Video-Captions-for-the-DHH-Community-Using-LLM/blob/main/llama2_replicate.ipynb) : Demonstrates implementation for llama2-13B using Replicates API key.

