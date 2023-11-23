# huggingface-transformers-cheatsheet
This is just a cheat sheet repo for how to upload tf models to the huggingface transformers website


## Getting Started with Hugging Face `git` and `git-lfs` Interface

### Create a Repository
- Install Hugging Face Hub: `$pip install huggingface_hub`
- Log in: `$huggingface-cli login`
- Create a repo: `$huggingface-cli repo create repo_name --type {model, dataset, space}`

### Clone Locally
- Install git-lfs: `$git lfs install`
- Clone your repo: `$git clone https://huggingface.co/username/repo_name`

### Add, Commit, and Push Files
- Add files: `$git add .`
- Commit changes: `$git commit -m "commit from $USER"`
- Push to repo: `$git push`

### Accessing Your Repo
- Your repo can be accessed with: `username/repo_name`

### Loading a Transformers Model
- Load tokenizer: `tokenizer = AutoTokenizer.from_pretrained("username/repo_name")`
- Load model: `model = AutoModel.from_pretrained("username/repo_name")`&#8203;``【oaicite:0】``&#8203;.

