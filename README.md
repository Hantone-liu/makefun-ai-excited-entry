# Make the AI judge excited

Entry for the make.fun bounty "Make the AI judge excited" (ai-excited-01).

The entry is one exciting image: a photorealistic golden-retriever
puppy joyfully surfing a giant towering turquoise ocean wave at
golden sunset — tongue out, ears flying, spray exploding behind the
board, strong diagonal composition, dramatic low golden light, single
clear subject, no text.

## How it works

`main.py` deterministically copies the bundled image `excited.png`
(768x768 PNG, under 1 MiB) to `/output/entry.png`. No network, no
randomness, no clock — two runs write byte-identical output.

## Run locally

```sh
python3 main.py
```

Writes `/output/entry.png`.
