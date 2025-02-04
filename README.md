# ML-chatbot
Use of token for supervised learning of chatbot model
In this project, I've developed a chatbot powered by a classifier engine, employing supervised learning techniques. The dataset I utilized was sourced from three distinct repositories, outlined in the subsequent section. This dataset comprises labeled entries featuring three distinct tags, along with corresponding questions/patterns and responses. Leveraging a neural network, the chatbot learns the semantic nuances of the input patterns, enabling it to classify the appropriate labels from the given set and generate corresponding responses.


\subsection{Data}
The data  I used was in json files with the following structure.
\begin{lstlisting}
{"intents": [
   {
    "tag": "hello",
    "patterns": [ "Hello","Hi there","Good morning",
                    "What's up ],
    "responses": ["Hey!","Hello","Hi!","Good morning!" ],
    "context": ""
  },
  { "tag": "noanswer",
    "patterns": [],
    "responses": ["Sorry, can't understand you", 
    "Please give me more info", "Not sure I understand" ],
    "context": [""]
  },
        
  {
    "tag": "job",
    "patterns": ["What is your job", "What is your work"],
    "responses":["My job is to make you
                feel like everything is okay.",
      "I work to serve you as well as possible"],
    "context": ""
  }
]}
\end{lstlisting}
Code reference:https://medium.com/@ramakrushnamohapatra/create-an-ai-chatbot-from-scratch-738ea385d108 
https://handsonai.medium.com/developing-a-simple-chatbot-with-python-and-tensorflow-a-step-by-step-tutorial-0d35767e113b
https://towardsdatascience.com/how-to-build-a-basic-chatbot-from-scratch-f63a2ccf5262


