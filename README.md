# Rasa-Waste-Awareness-Chatbot

Installation process for setting up a Rasa chatbot using Anaconda with Python version 3.9.18.

## Prerequisites
- [Anaconda](https://www.anaconda.com/products/distribution)
- [Python 3.9.18](https://www.python.org/downloads/release)

## Step 1: Clone the Repository
```bash
git clone https://github.com/Sanketgadekar31/Rasa-Waste-Awareness-Chatbot.git
cd Rasa-Waste-Awareness-Chatbot
```

## Step 2: Create and Activate Virtual Environment
```bash
conda create --name rasabot python=3.9.18
conda activate rasabot
```

## Step 3: Install Rasa

```bash
pip install rasa
```

## Step 4: Train the Chatbot

```bash
rasa train
```

This will train your chatbot using the configured NLU (Natural Language Understanding) and dialogue models.

## Step 5: Run the Chatbot in terminal

```bash
rasa shell
```

This will start the Rasa chatbot in the interactive shell, allowing you to interact with it.

## Additional Steps

- We have created a frontend for our Smart Waste Management Awareness Chatbot
- To use the interface run following command in ternimal while the rasa environment is activated

  ```bash
  rasa run --enable-api --cors="*"
  ```

- Now open the index.html file
- For more advanced configurations and deployment options, refer to the [Rasa Documentation](https://rasa.com/docs/rasa).

@sanketgadekar31
