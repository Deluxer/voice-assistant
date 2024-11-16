# Voice Assistan

## 1. Install and run LIvekit server `livekit-server --dev`

```shell
curl -sSL https://get.livekit.io | bash
```

Run the command `livekit-server --dev`

## 2. Install agent assistant to configure the model.

```shell
pip install -r requirements.txt
```

Set up environment variables

`copy .env.example to .env`

## 3. Install agent playground

Clone the repo and install dependencies.

```shell
git clone git@github.com:livekit/agents-playground.git
cd agents-playground
```
Set up environment and replace the variables values.

`copy .env.example to .env`