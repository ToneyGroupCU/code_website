Visit website at: https://toneygroupcu.github.io/code_website/

Setup a github account, join ToneyGroupCU organization.

# How to contribute to this website
Install git, setup your SSH and link it to your github account. (Ask chatgpt if you don't know how to do it)

Create python environment (>=3.7):

```python
conda create -n group_page python=3.8 pip
```

Activate environment:

```python
conda activate group_page
```

Validate the environment:

```python
which python
```

Clone the repo to local path:

```python
git clone https://github.com/ToneyGroupCU/code_website.git
cd code_website
```

Install requirements:

```python
pip install -r requirements.txt
```
#### Add your own content to the website
Preview the docs:

```python
mkdocs serve -s
```

Build the site

```python
mkdocs build
```

Push the project to group_page repo (after testing your build)
```python
git add --all
git commit -m "updating the group_page repo"
git push
```