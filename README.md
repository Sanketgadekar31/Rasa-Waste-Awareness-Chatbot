# Rasa-Waste-Awareness-Chatbot

Installation process for setting up a Rasa chatbot using Anaconda with Python version 3.9.18.

## Prerequisites
- [Anaconda](https://www.anaconda.com/products/distribution)
- [Python 3.9.18](https://www.python.org/downloads/release)

## Step 1: Clone the Repository
```bash
git clone [<repository_url>](https://github.com/Sanketgadekar31/Rasa-Waste-Awareness-Chatbot.git)
cd Rasa-Waste-Awareness-Chatbot
```

## Step 2: Create and Activate Virtual Environment
```bash
conda create --name my_rasa_env python=3.9.18
conda activate my_rasa_env
```

## Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

Replace `requirements.txt` with the actual name of your requirements file.

## Step 4: Install Rasa

```bash
pip install rasa
```

## Step 5: Initialize Rasa Project

```bash
rasa init
```

Follow the prompts to set up your Rasa project. This will create necessary files and directories for your chatbot.

## Step 6: Train the Chatbot

```bash
rasa train
```

This will train your chatbot using the configured NLU (Natural Language Understanding) and dialogue models.

## Step 7: Run the Chatbot

```bash
rasa shell
```

This will start the Rasa chatbot in the interactive shell, allowing you to interact with it.

## Additional Steps

- If you have a custom action server, start it using:

  ```bash
  rasa run actions
  ```

- For more advanced configurations and deployment options, refer to the [Rasa Documentation](https://rasa.com/docs/rasa).

## Troubleshooting

If you encounter any issues during the installation or setup process, please refer to the [Rasa Community Forum](https://forum.rasa.com/) or the [Rasa Documentation](https://rasa.com/docs/rasa) for assistance.

Happy Chatbot Building!
```

Make sure to replace `<repository_url>` and `<repository_folder>` with the actual URL and folder name of your Rasa chatbot repository. Additionally, update the `requirements.txt` file and any other placeholders with the appropriate details for your project.
