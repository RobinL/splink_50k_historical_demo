
# Splink 50k Historical Demo

This demo shows how to run the Splink 50k historical data linking example.  You can run it in your web browser at the following link:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RobinL/splink_50k_historical_demo/blob/main/50k_demo.ipynb)

If you want to run this locally, follow the instructions below:

## Mac:

```bash
# Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Add virtual environment as a Jupyter kernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)"

# Run the Jupyter notebook
jupyter notebook 50k_demo.ipynb
```

## Windows:

```bash
# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Add virtual environment as a Jupyter kernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)"

# Run the Jupyter notebook
jupyter notebook 50k_demo.ipynb
```

## Note:

If you don't have Jupyter installed globally, you can install it directly into the virtual environment by running:

```bash
pip install jupyter
```



You can also run this demo in Google Colab by clicking the badge above.
