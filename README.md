# Cht

A command-line tool to record audio and generate a one-liner bash command based on the content.

## Installation

1. Clone this repository:

```bash
git clone https://github.com/qwertyaya/Cht_terminal.git
```

## Install the required packages:
``` bash
pip3 install -r requirements.txt
```

## Make the script executable and move it to a directory in your system's PATH:
``` bash
chmod +x cht
sudo mv cht /usr/local/bin/
```

# Usage

Firstly, we will add the API toke, can be created through OpenAI -> Account -> Api keys

## To set the API token, use the -t or --token flag:
Once you set the API, the script will run and you can start talking :)
The deafult duration is 13 seconds.

```bash
cht -t YOUR_API_KEY
```

## To use the cht command, run it in your terminal:
It'll run the deafult 13 seconds till it's done recording and give you the response back

```bash
cht
```

## You can specify the recording duration with the -d or --duration flag:
```bash
cht -d 10
```

## To list available models, use the -m or --list-models flag:

```bash
cht -m
```