# Style Transfer Assistant

This project takes an input text and rewrites it in a different tone using prompt engineering. 

Currently supported tone: **Professional**

## How it Works

- Load a prompt template with `{{TEXT}}` placeholder
- Load a sample input text
- Format the prompt by inserting the text
- Output a ready-to-use prompt (for use with ChatGPT, Claude, etc.)

## File Structure

- `prompts/style_transfer_prompt.txt` – prompt template
- `samples/sample_input.txt` – text to rewrite
- `main.py` – core script

## Example Output

Rewrite the following text in a more professional tone:

```
hey i just wanted to let u know that we’re not gonna make it to the meeting today, something came up
```


## Future Ideas

- Add multiple tones (casual, persuasive, academic)
- Connect to OpenAI or Anthropic API
- Build a Streamlit web app
