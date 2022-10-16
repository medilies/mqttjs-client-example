# MQTT.JS client example

## Setup

```bash
git clone https://github.com/medilies/mqttjs-client-example
```

```bash
cd mqttjs-client-example
```

```bash
npm install
```

```bash
cp .env.example .env
```

-   Edit `.env`.
-   Edit `sub_topics.json`.

## Usage

Start a broker. For example:

```bash
mosquitto -p 1883 -v
```

Start the client:

```bash
npm start
```
