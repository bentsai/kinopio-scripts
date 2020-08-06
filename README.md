# Kinopio scripts

Scripts for interacting with the Kinopio API

## Quick add

### Install pre-requisites

```
% brew install httpie
```

### Configure

Create `.kinopio` with these variables:

```
KINOPIO_API_KEY=<find using `JSON.parse(localStorage.user).apiKey`>
KINOPIO_SPACE_ID=<it's in the URL>
```

### Run

```
./ko-create-card.sh "your message"
```
