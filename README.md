# mt-exercise-4-repo

# change working directory:
	cd mt-exercise-4-repo

# create a new virtualenv, and activate it
	./scripts/make_virtualenv.sh
	source venvs/torch3/bin/activate

# install JoeyNMT in editable mode
	pip install -e .

# run the train scripts for each model:
	./scripts/train_pre.sh
	./scripts/train_post.sh
	
	>>> create two models 'deen_transformer_pre' and 'deen_transformer_post' in file './models'
	>>> create log files 'deen_transformer_pre_norm' and 'deen_transformer_post_norm' in file './logs'
