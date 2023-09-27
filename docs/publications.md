# THAURUS: An innovative multimodal chatbot based on the next generation of conversational AI
The next generation of conversational AI has brought incredible capabilities such as high contextuality, naturalness, multimodality, and extended knowledge, but also important challenges such as high user expectations, high latencies, large computational requirements, as well as more subtle problems such as mismatch on existing databases for fine-tuning purposes, difficulties for pre-trained LLMs models to handle dialogue interactions, and the integration of multimodal capabilities.

This paper describes the architecture, methodology, and results of our THAURUS chatbot developed for the Alexa Prize Socialbot Grand Challenge (SGC5). Our proposal relies on several innovative ideas to take advantage of existing LLMs to create engaging user experiences that are capable of handling real users in a scalable way and without compromising the competition rules. Different SotA dialogue generators were fine-tuned and incorporated to give variability and handling the wide range of topic conversations; we also developed mechanisms to control the quality of the responses (e.g., detecting and handling toxic interactions, keeping topic coherence, and increasing engagement by providing up-to-date information in a conversational style).

In addition, our system extends the capabilities of the Cobot architecture by incorporating modules to automatically generate images, provide voice cloning capabilities with fictional characters, serve contextual sounds for detected entities in the dialogue, better capitalization and punctuation capabilities, and to provide natural expressions of interest.

Finally, we also included a trained generative selector and a reference-free model for automatic evaluation of turns that could reduce latencies and complement the ranker’s capabilities to select the best generative answer.

    @Inproceedings{Madrid2023,
    author = {Universidad Politécnica de Madrid},
    title = {THAURUS: An innovative multimodal chatbot based on the next generation of conversational AI},
    year = {2023},
    url = {https://www.amazon.science/alexa-prize/proceedings/thaurus-an-innovative-multimodal-chatbot-based-on-the-next-generation-of-conversational-ai},
    booktitle = {Alexa Prize SocialBot Grand Challenge 5 Proceedings},
    }

# GTH-UPM at DETOXIS-IberLEF 2021: Automatic Detection of Toxic Comments in Social Networks
Sadly, the presence of toxic messages on social networks, whether in the form of stereotypes, sarcasm, mockery, insult, inappropriate language, aggressiveness, intolerance, or typical of hate speech against immigrants and / or women, among others, is relatively frequent. This presence should not be ignored by the scientific community, since it is their responsibility to develop tools and systems that allow their automatic detection and elimination. In this paper, we present an exploratory analysis in which different deep learning (DL) models for the detection of toxic expressions have been evaluated on the DETOXIS IberLEF 2021 challenge using the official release of the NewsCom-TOX corpus. Particularly, we compare traditional RNN and state-of-the-art transformer models. Our experiments confirmed that optimum performance can be obtained from transformer models. Specifically, top performance was achieved by fine tuning a BETO model (the pre-trained BERT model for the Spanish language from the Universidad de Chile) for the toxicity detection tasks. Another contribution of this analysis is the validation of the proposed method for adding task-specific vocabulary (new tokens) that could help

    @inproceedings{inproceedings,
    author = {Romero, Sergio and Kleinlein, Ricardo and Luna Jiménez, Cristina and Montero, Juan and Fernández-Martínez, Fernando},
    year = {2021},
    month = {06},
    pages = {},
    title = {GTH-UPM at DETOXIS-IberLEF 2021: Automatic Detection of Toxic Comments in Social Networks}
    }