# olf
A tiny CLI that pipes a prompt and a file into Ollama

## ollama-file (olf)

**ollama-file** is a tiny helper script for running [Ollama](https://ollama.ai) against a text file with a custom prompt.  
It combines your prompt with the file contents and streams the result from Ollama.  

---

## Usage

```bash
olf <filename>
```
## Example
```bash
olf report.txt
Prompt: Summarize this report
```
