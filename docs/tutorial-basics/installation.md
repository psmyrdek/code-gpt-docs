---
sidebar_position: 1
---

# Installation

## Install Visual Studio Code
Visual Studio Code: [Download](https://code.visualstudio.com/download)

## Install the Code GPT Extension
You can install the extension from the Visual Studio Marketplace, Open VSX, or directly from the Extensions tab in Visual Studio Code.
- <details>
      <summary>Search for Code GPT in the Extensions tab, or</summary>
      <div><img src="https://user-images.githubusercontent.com/6216945/212494271-256734c6-6cab-4c12-bb8f-dae1ffa74b33.png"/></div>
    </details>
- [Download from Marketplace](https://marketplace.visualstudio.com/items?itemName=DanielSanMedium.dscodegpt), or 
- [Download from Open VSX](https://open-vsx.org/extension/DanielSanMedium/dscodegpt)

## Get your API key
This will differ depending on the provider you choose:
- ### OpenAI
  - Go to the [API Keys page on OpenAI](https://platform.openai.com/account/api-keys).
  - Log in with your OpenAI account (or [create a new account](https://platform.openai.com/signup))
  - Click the button labeled **`Create a new secret key`**
  - A new dialog window will appear, containing a text box with your API key. 
  - Copy this API Key to your clipboard.

---

- ### Google PaLM 2
  - Request to PaLM 2 in this link [PaLM 2 Waitlist](https://makersuite.google.com/)
  - Go to the [Get API key](https://makersuite.google.com/app/apikey) menu
  - Create a new API key
  - Copy this API Key to your clipboard.

---

- ### Judini
  - Request your API Key from the [Judini's](https://judini.ai) team
  - Go to the Settings section and copy your **`User ID`**
  - In VSCode press ```cmd + shift + p``` and search **`Set Judini Data`**
  - Paste the API Key and User ID

---

- ### Cohere
  - Create an account in [cohere.ai](https://cohere.ai/)
  - Go to your [dashboard](https://dashboard.cohere.ai/)
  - Copy the API Key

---

- ### AI21
  - Create an account in [AI21](https://console.anthropic.com/)
  - Go to your [account](https://studio.ai21.com/account/account)
  - Copy the API Key

---

- ### Anthropic
  - Create an account in [Anthropic](https://www.ai21.com/)
  - Go to yours [API Keys](https://console.anthropic.com/account/keys)
  - Generate and copy the API Key

---

- ### GPT4All
  - Download GPT4All at the following link: [gpt4all.io](https://gpt4all.io/)
  - Go to the **`Downloads`** menu and download all the models you want to use
  - Go to the **`Settings`** section and enable the **`Enable web server`** option

---

- ### Huggingface
  - Create an account in [Huggingface](https://huggingface.co/)
  - Go to your [Profile - Settings - Access Tokens](https://huggingface.co/settings/tokens)
  - Generate and copy the API Key

## Enter your API Key
Once you have your API Key, you can enter it into CodeGPT:
- Open up Visual Studio Code 
- In VSCode, open the Command Palette by clicking **`View` > `Command Palette`** (or use the keyboard shortcut **⌘+⇧+P**)
- In the Command Palette, search for `CodeGPT: Set API KEY` and press **Enter⏎**
- A new dialog window will appear, prompting you to enter your API Key. 
- Paste your API Key into the text box and press **Enter⏎**.
- Run the command `Developer: Reload Window`

:::caution

If you want to remove your API Key from CodeGPT, open the Command Palette and search for `CodeGPT: Remove API KEY`.

:::


