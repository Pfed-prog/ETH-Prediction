# ETH Price: Round Three

[The Challenge Readme](https://github.com/oceanprotocol/predict-eth/blob/main/challenges/main4.md)

[The Challenge on Desights](https://desights.ai/g/challenge/4)

`INFO:ocean:Successfully created NFT with address 0x97b579afbC8bd572Ca95EF17175F51BA8Fe05Da2.
INFO:ocean:Successfully created datatoken with address 0x856985D66A0EC897fBec867CE8d554bd5914676c.`

[Arweave prediction saved](https://arweave.net/VBRTXIlFaVOCSCS_RhrhoLukPevcaF6sRXNeF6fjV30)

## Input data

Ocean Marketplace Data Endpoint at 'https://cexa.oceanprotocol.io/ohlc?exchange=binance&pair=ETH/USDT&period=1h'

## Processing and Prediction

`lstm-ocean.ipynb` - predictions and model.

Next, we uploaded data to bundlr with `upload.py`. Uploaded data to ocean with `upload_to_ocean.py`. And sent the data to judges via `send_to_judges.py`.
