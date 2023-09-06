---
title: Sentzi
emoji: 😄
colorFrom: blue
colorTo: yellow
sdk: streamlit
sdk_version: 1.26.0
app_file: app.py
pinned: false
---

# Sentzi

## 🎉 Try now on `Streamlit` [`Cloud`](https://sentzi.streamlit.app/) (_`recommended`_) (or) [`Space`](https://huggingface.co/spaces/Sreezx/Sentzi) (_`very laggy !`_)

https://github.com/sreezx/Sentzi/assets/121812287/6cdc0681-56c2-44dd-bce6-e595056a8a6b

A fun 🥳 project made to demonstrate the practical application of sentiment analysis 

This is a demo app made using [`Streamlit`](streamlit.io) Library ( the best Python library for creating beautiful web apps )

The sentiment analysis is achieved using [`Textblob`](https://github.com/sloria/TextBlob)

## Installation 📦

> To run the application locally 
- **(Optional)** Create a `venv` (_sentzi-venv_) and activate it using 
```cmd
$ py -m venv sentzi-venv
$ sentzi-venv\Scripts\Activate.ps1 (for windows powershell)
(or )
  sentzi-venv\Scripts\activate.bat (for windows cmd)
(or )
  source bin/activate (for unix or linux)
```
- Install the dependencies using 
```cmd
$ pip install -r requirements.txt
```
- Make sure the project structure is _**similar**_ to this 

<img src="data/tree.png" alt="tree" width="280"/>

- Head to `root` dir and create a `.env` with the following code 

```cmd
DEV_EMAIL_ID=an_emailID_to_use_for_email_bot

DEV_PASS=password_of_that_emailID
```

- Everything is ready ! Run the `streamlit` app using 
```cmd
$ streamlit run app.py
```
and enjoy 😎 !

## Testing ⚙️ 

You can test the application locally using the `test\sentzi-test.py` CLI tool . 

> `sentzi-test.py` is an extension of the sentzi project made primarily to test the sentzi backend modules . 
---
_`sentzi-test help`_
<img src="data/test-help.png" alt="sentzi-test-help" style="max-width: 100% ;" />

---
_`Using '-with' option to get setiment of a text and saving it as 'json' file . '-o "show"' is default . `_

<video style="max-width: 100% ;" controls>
<source src="data/test-simple-text.mp4" type="video/mp4">
Your browser does not support video tag
</video>

---
_`Using '-with' option to get setiment from a text file . Here logging is disabled . `_

<video style="max-width: 100% ;" controls>
<source src="data/test-from-file.mp4" type="video/mp4">
Your browser does not support video tag
</video>

---
_`Using '-with' option to get setiment from an external dataset . Here output is hidden. `_

<video style="max-width: 100% ;" controls>
<source src="data/test-ext-1.mp4" type="video/mp4">
Your browser does not support video tag
</video>

---
_`Using '-with' option to get setiment from an external dataset . Here 12 reviews are retrieved from the dataset `_

<video style="max-width: 100% ;" controls>
<source src="data/test-ext-2.mp4" type="video/mp4">
Your browser does not support video tag
</video>










