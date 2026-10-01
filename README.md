# Assisting-Intellect
An intellect that thinks.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: What is the answer, intellect?" \
  | uvx assisting-intellect \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install assisting-intellect
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
assisting-intellect -a multilogue.txt
```
Or:
```bash
assisting-intellect multilogue.txt > response.txt
```
Or:
```bash
assisting-intellect -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import assisting_intellect
```
