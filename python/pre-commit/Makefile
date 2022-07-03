
...


lint:
	@echo "Running flake8 ..."
	@echo $(SRC_FILES) | xargs flake8 --max-line-length=119

	@echo "Running pycodestyle ..."
	@echo $(SRC_FILES) | xargs pycodestyle --show-pep8 --show-source --max-line-length=119 --exclude='./venv/*'

	@echo "Running blue ..."
	@blue --diff --color --check --line-length=119 .
  
  
  ...
