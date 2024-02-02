# Unity-Dialogue-Model

This project aims to design a conversational model using Unity ML-Agents. The project explores how to train and test an agent that can interact with the user via text, using different data sources, NLP tools, and reward functions. The project also demonstrates how to adapt and extend the existing ML-Agents examples to create a type writer that outputs letters instead of numbers. The project is a fun and challenging way to learn and apply Unity ML-Agents and NLP techniques.

## Getting Started

To run this project, you will need the following:

- Unity, a cross-platform game engine
- Unity ML-Agents, a toolkit for training and testing agents using reinforcement learning, imitation learning, and other methods
- Hugging Face, a platform for NLP models
- Cornell Movie Dialogs Corpus, a collection of movie scripts
- GitHub Desktop, a tool that simplifies the GitHub workflow
- Visual Studio Code, an editor that integrates well with GitHub and Unity
- TensorBoard, a tool to visualize the training results and metrics

## How It Works

The project consists of two main parts: the conversational model and the type writer.

### Conversational Model

The conversational model is an agent that can interact with the user via text. The agent has the following components:

- **Goal and Reward Function**: The agent's goal is to learn from the conversation and produce coherent, relevant, and engaging responses. The agent receives a reward for each correct response and a penalty for each incorrect response. The agent also has an attention mechanism that allows it to focus on a subset of the words.
- **Input and Output Channels**: The agent uses a simple command console and a C# API to communicate with the user via text. The agent also uses some NLP tools to parse and generate text, such as Hugging Face, a platform for NLP models.
- **Environment and Curriculum**: The agent is exposed to different situations and topics, and the difficulty and complexity of the conversation increases over time. The agent uses some existing datasets or corpora of dialogues, or custom scenarios and scripts, as the source of data. The agent uses the Cornell Movie Dialogs Corpus, a collection of movie scripts, as an example of data.
- **Training and Testing Methods**: The agent is trained and tested using the Unity ML-Agents toolkit, which provides a framework for training and testing agents using reinforcement learning, imitation learning, and other methods. The agent is also interacted with and evaluated using the ML-Agents Python API, and the training results and metrics are visualized using the TensorBoard tool.

### Type Writer

The type writer is an adaptation and extension of the Sorter demo example in ML-Agents, which is an environment where the agent has to sort the numbers on the wall by pointing at them in ascending order. The type writer has the following modifications:

- **Numbers to Letters**: The numbers on the wall are changed to letters, and each letter is mapped to a corresponding ASCII code.
- **Reward Function**: The reward function is changed to reward the agent for producing meaningful words or sentences, and penalize it for producing gibberish or errors. The reward function also uses some NLP tools to analyze and generate the text, such as Hugging Face, a platform for NLP models.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
