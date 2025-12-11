setup:
	pip install -r requirements.txt

clean:
	find . -type d -name "__pycache__" -exec rm -rf {} +
	find . -type d -name ".ipynb_checkpoints" -exec rm -rf {} +

test:
	pytest

lint:
	flake8 . --count --select=E9,F63,F7,F82 --show-source --statistics
