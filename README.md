# GameGPT

GameGPT is a conversational entertainment robot that differs from most games, which are almost always based on specific game rules (such as Monopoly, Snakes and Ladders, Life Simulator, etc.). Instead, GameGPT provides an open-option, open-world gaming platform where users can choose their own path and have engaging interactive experiences in the game plot.

## Getting Started


1. Create virtual environment.
```
conda create -n game_gpt python=3.10
```

2. Clone the repository and install dependency.
```
git clone git@github.com:prismleong/GameGPT.git
cd GameGPT
pip install -r requirements.txt
```

3. Paste your openai api key in main.py
```
# fill in your openai api key
openai.api_key = "sk-..."
```

4. Run the application:
```
streamlit run main.py
```

5. start game!
