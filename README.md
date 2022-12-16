# wonkyphonky
cse168 final

1. Install requirements.
`pip install -r requirements.txt`

2. Generate mfcc data by first creating a folder called `genrest_original`. Inside of this folder add another folder for each genre you plan to have with their corresponding .wav files. finally run `wavs_to_json.ipynb`. This will generate a file called `mfcc_data.json`.

3. After `mfcc_data.json` is generated run `mfcc_trainer.ipynb`. 
