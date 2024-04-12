# 💰 Real time payment simulator
System to simulate payment validation in real time using pix

## 🚀 Techs
Python, Flask, Websocket, Pytest


## 🛠️ Clone

To clone and run this application, you'll need Python installed on your computer.

📥 Clone the repository:

```bash
  git clone https://github.com/lucaslomba/real-time-flask.git
```

📂 Navigate to the project directory:

```bash
  cd real-time-flask
```

## 🛠️ Install dependencies

📥 Install using requirements.txt:

```bash
    pip3 install -r requirements.txt --upgrade
```

### Start project 

```bash
$ python3 app.py

```

### Access webpage 

🌎 Access http://127.0.0.1:5000/payments/pix/1

## API Reference

### Create payment

```http
  POST api_url/payments/pix
```

Request body

```JSON
{
    "value": 1999
}
```

### Pix payment confirmation

```http
  POST api_url/payments/pix/confirmation
```

Request body

```JSON
{
    "bank_payment_id": "string",
    "value": 1999.0
}
```

## Authors

- [@lucaslomba](https://github.com/lucaslomba)

