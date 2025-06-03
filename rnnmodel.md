```python
pip install miditok miditoolkit
```

    Collecting miditok
      Downloading miditok-3.0.5.post1-py3-none-any.whl.metadata (10 kB)
    Requirement already satisfied: miditoolkit in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (1.0.1)
    Collecting huggingface-hub>=0.16.4 (from miditok)
      Downloading huggingface_hub-0.32.3-py3-none-any.whl.metadata (14 kB)
    Requirement already satisfied: numpy>=1.19 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from miditok) (1.26.4)
    Collecting symusic>=0.5.0 (from miditok)
      Downloading symusic-0.5.8-cp312-cp312-win_amd64.whl.metadata (9.0 kB)
    Collecting tokenizers>=0.13.0 (from miditok)
      Downloading tokenizers-0.21.1-cp39-abi3-win_amd64.whl.metadata (6.9 kB)
    Requirement already satisfied: tqdm in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from miditok) (4.67.1)
    Requirement already satisfied: matplotlib in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from miditoolkit) (3.9.2)
    Requirement already satisfied: mido>=1.1.16 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from miditoolkit) (1.3.3)
    Requirement already satisfied: filelock in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from huggingface-hub>=0.16.4->miditok) (3.18.0)
    Requirement already satisfied: fsspec>=2023.5.0 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from huggingface-hub>=0.16.4->miditok) (2025.3.2)
    Requirement already satisfied: packaging>=20.9 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from huggingface-hub>=0.16.4->miditok) (24.1)
    Collecting pyyaml>=5.1 (from huggingface-hub>=0.16.4->miditok)
      Downloading PyYAML-6.0.2-cp312-cp312-win_amd64.whl.metadata (2.1 kB)
    Requirement already satisfied: requests in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from huggingface-hub>=0.16.4->miditok) (2.32.3)
    Requirement already satisfied: typing-extensions>=3.7.4.3 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from huggingface-hub>=0.16.4->miditok) (4.13.1)
    Collecting pySmartDL (from symusic>=0.5.0->miditok)
      Downloading pySmartDL-1.3.4-py3-none-any.whl.metadata (2.8 kB)
    Requirement already satisfied: platformdirs in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from symusic>=0.5.0->miditok) (4.3.6)
    Requirement already satisfied: colorama in c:\users\schng\appdata\roaming\python\python312\site-packages (from tqdm->miditok) (0.4.6)
    Requirement already satisfied: contourpy>=1.0.1 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from matplotlib->miditoolkit) (1.2.1)
    Requirement already satisfied: cycler>=0.10 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from matplotlib->miditoolkit) (0.12.1)
    Requirement already satisfied: fonttools>=4.22.0 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from matplotlib->miditoolkit) (4.53.1)
    Requirement already satisfied: kiwisolver>=1.3.1 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from matplotlib->miditoolkit) (1.4.5)
    Requirement already satisfied: pillow>=8 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from matplotlib->miditoolkit) (10.4.0)
    Requirement already satisfied: pyparsing>=2.3.1 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from matplotlib->miditoolkit) (3.1.2)
    Requirement already satisfied: python-dateutil>=2.7 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from matplotlib->miditoolkit) (2.9.0.post0)
    Requirement already satisfied: six>=1.5 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from python-dateutil>=2.7->matplotlib->miditoolkit) (1.16.0)
    Requirement already satisfied: charset-normalizer<4,>=2 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from requests->huggingface-hub>=0.16.4->miditok) (3.3.2)
    Requirement already satisfied: idna<4,>=2.5 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from requests->huggingface-hub>=0.16.4->miditok) (3.7)
    Requirement already satisfied: urllib3<3,>=1.21.1 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from requests->huggingface-hub>=0.16.4->miditok) (2.2.2)
    Requirement already satisfied: certifi>=2017.4.17 in c:\users\schng\appdata\local\programs\python\python312\lib\site-packages (from requests->huggingface-hub>=0.16.4->miditok) (2024.7.4)
    Downloading miditok-3.0.5.post1-py3-none-any.whl (158 kB)
    Downloading huggingface_hub-0.32.3-py3-none-any.whl (512 kB)
    Downloading symusic-0.5.8-cp312-cp312-win_amd64.whl (2.1 MB)
       ---------------------------------------- 0.0/2.1 MB ? eta -:--:--
       ---------------------------------------- 2.1/2.1 MB 57.7 MB/s eta 0:00:00
    Downloading tokenizers-0.21.1-cp39-abi3-win_amd64.whl (2.4 MB)
       ---------------------------------------- 0.0/2.4 MB ? eta -:--:--
       ---------------------------------------- 2.4/2.4 MB 35.1 MB/s eta 0:00:00
    Downloading PyYAML-6.0.2-cp312-cp312-win_amd64.whl (156 kB)
    Downloading pySmartDL-1.3.4-py3-none-any.whl (20 kB)
    Installing collected packages: pySmartDL, symusic, pyyaml, huggingface-hub, tokenizers, miditok
    Successfully installed huggingface-hub-0.32.3 miditok-3.0.5.post1 pySmartDL-1.3.4 pyyaml-6.0.2 symusic-0.5.8 tokenizers-0.21.1
    Note: you may need to restart the kernel to use updated packages.
    

    
    [notice] A new release of pip is available: 24.2 -> 25.1.1
    [notice] To update, run: python.exe -m pip install --upgrade pip
    


```python
!git clone https://github.com/music-x-lab/POP909-Dataset.git
!cd POP909-Dataset
```

    Cloning into 'POP909-Dataset'...
    Updating files:   7% (590/7450)
    Updating files:   8% (596/7450)
    Updating files:   9% (671/7450)
    Updating files:  10% (745/7450)
    Updating files:  11% (820/7450)
    Updating files:  12% (894/7450)
    Updating files:  13% (969/7450)
    Updating files:  14% (1043/7450)
    Updating files:  15% (1118/7450)
    Updating files:  16% (1192/7450)
    Updating files:  17% (1267/7450)
    Updating files:  18% (1341/7450)
    Updating files:  19% (1416/7450)
    Updating files:  20% (1490/7450)
    Updating files:  21% (1565/7450)
    Updating files:  22% (1639/7450)
    Updating files:  23% (1714/7450)
    Updating files:  23% (1723/7450)
    Updating files:  24% (1788/7450)
    Updating files:  25% (1863/7450)
    Updating files:  26% (1937/7450)
    Updating files:  27% (2012/7450)
    Updating files:  28% (2086/7450)
    Updating files:  29% (2161/7450)
    Updating files:  30% (2235/7450)
    Updating files:  31% (2310/7450)
    Updating files:  32% (2384/7450)
    Updating files:  33% (2459/7450)
    Updating files:  34% (2533/7450)
    Updating files:  35% (2608/7450)
    Updating files:  36% (2682/7450)
    Updating files:  37% (2757/7450)
    Updating files:  37% (2810/7450)
    Updating files:  38% (2831/7450)
    Updating files:  39% (2906/7450)
    Updating files:  40% (2980/7450)
    Updating files:  41% (3055/7450)
    Updating files:  42% (3129/7450)
    Updating files:  43% (3204/7450)
    Updating files:  44% (3278/7450)
    Updating files:  45% (3353/7450)
    Updating files:  46% (3427/7450)
    Updating files:  47% (3502/7450)
    Updating files:  48% (3576/7450)
    Updating files:  49% (3651/7450)
    Updating files:  50% (3725/7450)
    Updating files:  51% (3800/7450)
    Updating files:  51% (3845/7450)
    Updating files:  52% (3874/7450)
    Updating files:  53% (3949/7450)
    Updating files:  54% (4023/7450)
    Updating files:  55% (4098/7450)
    Updating files:  56% (4172/7450)
    Updating files:  57% (4247/7450)
    Updating files:  58% (4321/7450)
    Updating files:  59% (4396/7450)
    Updating files:  60% (4470/7450)
    Updating files:  61% (4545/7450)
    Updating files:  62% (4619/7450)
    Updating files:  63% (4694/7450)
    Updating files:  64% (4768/7450)
    Updating files:  65% (4843/7450)
    Updating files:  65% (4869/7450)
    Updating files:  66% (4917/7450)
    Updating files:  67% (4992/7450)
    Updating files:  68% (5066/7450)
    Updating files:  69% (5141/7450)
    Updating files:  70% (5215/7450)
    Updating files:  71% (5290/7450)
    Updating files:  72% (5364/7450)
    Updating files:  73% (5439/7450)
    Updating files:  74% (5513/7450)
    Updating files:  75% (5588/7450)
    Updating files:  76% (5662/7450)
    Updating files:  77% (5737/7450)
    Updating files:  78% (5811/7450)
    Updating files:  78% (5857/7450)
    Updating files:  79% (5886/7450)
    Updating files:  80% (5960/7450)
    Updating files:  81% (6035/7450)
    Updating files:  82% (6109/7450)
    Updating files:  83% (6184/7450)
    Updating files:  84% (6258/7450)
    Updating files:  85% (6333/7450)
    Updating files:  86% (6407/7450)
    Updating files:  87% (6482/7450)
    Updating files:  88% (6556/7450)
    Updating files:  89% (6631/7450)
    Updating files:  90% (6705/7450)
    Updating files:  91% (6780/7450)
    Updating files:  91% (6806/7450)
    Updating files:  92% (6854/7450)
    Updating files:  93% (6929/7450)
    Updating files:  94% (7003/7450)
    Updating files:  95% (7078/7450)
    Updating files:  96% (7152/7450)
    Updating files:  97% (7227/7450)
    Updating files:  98% (7301/7450)
    Updating files:  99% (7376/7450)
    Updating files: 100% (7450/7450)
    Updating files: 100% (7450/7450), done.
    


```python
import os
import pretty_midi   

def extract_notes_from_midi(file_path):
    midi = pretty_midi.PrettyMIDI(file_path)
    notes = []
    for instrument in midi.instruments:
        if not instrument.is_drum:
            for note in instrument.notes:
                pitch = note.pitch
                start = note.start
                duration = round(note.end - start, 3)
                notes.append((start, pitch, duration))
    notes.sort()           # sort by start-time
    return notes


def collect_pop909_notes():
    base_dir = r".\POP909-Dataset\POP909"
    all_notes = {}

    # sub-folders 001 → 909 (zero-padded to width 3)
    for folder_id in range(1, 910):
        folder_name = f"{folder_id:03d}"
        folder_path = os.path.join(base_dir, folder_name)

        # skip if the folder somehow doesn’t exist
        if not os.path.isdir(folder_path):
            continue

        # any file ending in .mid or .midi
        for fname in os.listdir(folder_path):
            if fname.lower().endswith((".mid", ".midi")):
                fpath = os.path.join(folder_path, fname)
                all_notes[fpath] = extract_notes_from_midi(fpath)

    return all_notes
```


```python
def quantize(value, step=0.25):
    # Round to nearest multiple of step
    return round(value / step) * step

def notes_to_token_sequence(notes, time_step=0.25):
    tokens = []
    prev_start = 0.0

    for start, pitch, duration in notes:
        time_shift = quantize(start - prev_start, time_step)
        token = f"TS_{time_shift:.2f}_P_{pitch}_D_{duration:.2f}"
        tokens.append(token)
        prev_start = start

    return tokens
```


```python
notes_by_file = collect_pop909_notes()
print(f"Parsed {len(notes_by_file)} MIDI files.")
# e.g. inspect the first one
some_file, notes = next(iter(notes_by_file.items()))
print(some_file)
print(notes[:10])   # first 10 note tuples
```

    Parsed 909 MIDI files.
    .\POP909-Dataset\POP909\001\001.mid
    [(2.3888829166666667, 66, 0.283), (2.7222154166666668, 47, 0.926), (2.7222154166666668, 75, 0.329), (2.888881666666667, 54, 0.79), (3.055547916666667, 59, 0.526), (3.055547916666667, 73, 0.182), (3.222214166666667, 66, 0.811), (3.388880416666667, 71, 0.206), (3.722212916666667, 80, 0.132), (3.888879166666667, 82, 0.16)]
    


```python
token_sequence = notes_to_token_sequence(notes)
print(token_sequence[:100])
```

    ['TS_2.50_P_66_D_0.28', 'TS_0.25_P_47_D_0.93', 'TS_0.00_P_75_D_0.33', 'TS_0.25_P_54_D_0.79', 'TS_0.25_P_59_D_0.53', 'TS_0.00_P_73_D_0.18', 'TS_0.25_P_66_D_0.81', 'TS_0.25_P_71_D_0.21', 'TS_0.25_P_80_D_0.13', 'TS_0.25_P_82_D_0.16', 'TS_0.25_P_49_D_0.83', 'TS_0.00_P_80_D_0.83', 'TS_0.25_P_56_D_0.59', 'TS_0.25_P_61_D_0.61', 'TS_0.25_P_65_D_0.46', 'TS_0.50_P_66_D_0.23', 'TS_0.25_P_46_D_1.09', 'TS_0.00_P_75_D_0.34', 'TS_0.25_P_53_D_0.89', 'TS_0.25_P_58_D_0.98', 'TS_0.00_P_73_D_0.52', 'TS_0.25_P_61_D_0.74', 'TS_0.50_P_70_D_1.04', 'TS_0.25_P_51_D_0.35', 'TS_0.25_P_54_D_0.86', 'TS_0.25_P_58_D_0.80', 'TS_0.25_P_66_D_0.73', 'TS_0.50_P_73_D_0.20', 'TS_0.25_P_47_D_0.90', 'TS_0.00_P_78_D_0.17', 'TS_0.25_P_54_D_0.73', 'TS_0.00_P_80_D_0.08', 'TS_0.25_P_59_D_0.59', 'TS_0.00_P_82_D_0.58', 'TS_0.25_P_63_D_0.63', 'TS_0.50_P_73_D_0.14', 'TS_0.25_P_49_D_0.92', 'TS_0.00_P_56_D_0.23', 'TS_0.00_P_61_D_0.55', 'TS_0.00_P_78_D_0.14', 'TS_0.25_P_80_D_0.09', 'TS_0.25_P_56_D_0.21', 'TS_0.00_P_82_D_0.46', 'TS_0.25_P_65_D_0.41', 'TS_0.75_P_42_D_1.23', 'TS_0.25_P_49_D_0.99', 'TS_0.25_P_54_D_0.85', 'TS_0.00_P_66_D_0.26', 'TS_0.25_P_61_D_0.60', 'TS_0.25_P_75_D_0.26', 'TS_0.25_P_58_D_0.20', 'TS_0.00_P_73_D_1.16', 'TS_0.25_P_42_D_0.88', 'TS_0.00_P_54_D_0.55', 'TS_0.00_P_58_D_0.39', 'TS_0.00_P_61_D_0.38', 'TS_0.00_P_66_D_0.45', 'TS_0.25_P_49_D_0.47', 'TS_0.25_P_54_D_0.24', 'TS_0.00_P_58_D_0.23', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.28', 'TS_0.25_P_63_D_0.06', 'TS_0.25_P_66_D_0.07', 'TS_0.25_P_68_D_0.08', 'TS_0.25_P_47_D_0.76', 'TS_0.00_P_59_D_0.36', 'TS_0.00_P_63_D_0.44', 'TS_0.00_P_70_D_0.11', 'TS_0.25_P_78_D_0.10', 'TS_0.25_P_54_D_0.47', 'TS_0.00_P_66_D_0.21', 'TS_0.00_P_80_D_0.09', 'TS_0.25_P_59_D_0.28', 'TS_0.00_P_82_D_0.14', 'TS_0.25_P_63_D_0.24', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_61_D_0.76', 'TS_0.00_P_65_D_0.72', 'TS_0.00_P_68_D_0.99', 'TS_0.25_P_49_D_0.79', 'TS_0.25_P_56_D_0.40', 'TS_0.00_P_80_D_0.10', 'TS_0.25_P_82_D_0.08', 'TS_0.25_P_61_D_0.15', 'TS_0.00_P_65_D_0.23', 'TS_0.00_P_68_D_0.38', 'TS_0.00_P_80_D_0.23', 'TS_0.25_P_61_D_0.10', 'TS_0.25_P_46_D_0.90', 'TS_0.00_P_58_D_0.32', 'TS_0.00_P_61_D_0.34', 'TS_0.00_P_68_D_0.23', 'TS_0.25_P_53_D_0.50', 'TS_0.00_P_65_D_0.19', 'TS_0.25_P_58_D_0.11', 'TS_0.25_P_58_D_0.14', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.19', 'TS_0.00_P_65_D_0.16']
    


```python
import tensorflow as tf
from tensorflow.keras import layers
import numpy as np

# 1. Build vocab
unique_tokens = sorted(set(token_sequence))
token_to_id = {tok: i for i, tok in enumerate(unique_tokens)}
id_to_token = {i: tok for tok, i in token_to_id.items()}

# 2. Encode tokens to ids
encoded_sequence = [token_to_id[tok] for tok in token_sequence]

seq_length = 20  # how many tokens in input sequence

inputs = []
targets = []

for i in range(len(encoded_sequence) - seq_length):
    inputs.append(encoded_sequence[i:i+seq_length])
    targets.append(encoded_sequence[i+1:i+seq_length+1])

inputs = np.array(inputs)
targets = np.array(targets)

vocab_size = len(unique_tokens)
embedding_dim = 64
rnn_units = 128

model = tf.keras.Sequential([
    layers.Embedding(vocab_size, embedding_dim, input_length=seq_length),
    layers.LSTM(rnn_units, return_sequences=True),
    layers.Dense(vocab_size, activation='softmax')
])

model.compile(optimizer='adam', loss='sparse_categorical_crossentropy')

model.fit(inputs, targets, epochs=30, batch_size=64)

model.summary()
```

    Epoch 1/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m2s[0m 20ms/step - loss: 6.0627
    Epoch 2/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 22ms/step - loss: 5.6894
    Epoch 3/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 20ms/step - loss: 5.0866
    Epoch 4/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 21ms/step - loss: 4.4806
    Epoch 5/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 20ms/step - loss: 4.0745
    Epoch 6/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 20ms/step - loss: 3.6475
    Epoch 7/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 19ms/step - loss: 3.2637
    Epoch 8/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 19ms/step - loss: 2.9578
    Epoch 9/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 20ms/step - loss: 2.6834
    Epoch 10/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 22ms/step - loss: 2.4581
    Epoch 11/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 19ms/step - loss: 2.1807
    Epoch 12/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 20ms/step - loss: 2.0534
    Epoch 13/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 21ms/step - loss: 1.8326
    Epoch 14/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 20ms/step - loss: 1.6655
    Epoch 15/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 20ms/step - loss: 1.4667
    Epoch 16/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 20ms/step - loss: 1.3241
    Epoch 17/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 20ms/step - loss: 1.2261
    Epoch 18/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 22ms/step - loss: 1.0787
    Epoch 19/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 22ms/step - loss: 0.9640
    Epoch 20/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 21ms/step - loss: 0.8643
    Epoch 21/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 21ms/step - loss: 0.7500
    Epoch 22/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 21ms/step - loss: 0.6894
    Epoch 23/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 21ms/step - loss: 0.6066
    Epoch 24/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 22ms/step - loss: 0.5553
    Epoch 25/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 20ms/step - loss: 0.4854
    Epoch 26/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 20ms/step - loss: 0.4448
    Epoch 27/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 21ms/step - loss: 0.4019
    Epoch 28/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m1s[0m 20ms/step - loss: 0.3573
    Epoch 29/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 19ms/step - loss: 0.3270
    Epoch 30/30
    [1m24/24[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 19ms/step - loss: 0.3050
    


<pre style="white-space:pre;overflow-x:auto;line-height:normal;font-family:Menlo,'DejaVu Sans Mono',consolas,'Courier New',monospace"><span style="font-weight: bold">Model: "sequential_3"</span>
</pre>




<pre style="white-space:pre;overflow-x:auto;line-height:normal;font-family:Menlo,'DejaVu Sans Mono',consolas,'Courier New',monospace">┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━┓
┃<span style="font-weight: bold"> Layer (type)                    </span>┃<span style="font-weight: bold"> Output Shape           </span>┃<span style="font-weight: bold">       Param # </span>┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━┩
│ embedding_3 (<span style="color: #0087ff; text-decoration-color: #0087ff">Embedding</span>)         │ (<span style="color: #00af00; text-decoration-color: #00af00">64</span>, <span style="color: #00af00; text-decoration-color: #00af00">20</span>, <span style="color: #00af00; text-decoration-color: #00af00">64</span>)           │        <span style="color: #00af00; text-decoration-color: #00af00">28,224</span> │
├─────────────────────────────────┼────────────────────────┼───────────────┤
│ lstm_3 (<span style="color: #0087ff; text-decoration-color: #0087ff">LSTM</span>)                   │ (<span style="color: #00af00; text-decoration-color: #00af00">64</span>, <span style="color: #00af00; text-decoration-color: #00af00">20</span>, <span style="color: #00af00; text-decoration-color: #00af00">128</span>)          │        <span style="color: #00af00; text-decoration-color: #00af00">98,816</span> │
├─────────────────────────────────┼────────────────────────┼───────────────┤
│ dense_3 (<span style="color: #0087ff; text-decoration-color: #0087ff">Dense</span>)                 │ (<span style="color: #00af00; text-decoration-color: #00af00">64</span>, <span style="color: #00af00; text-decoration-color: #00af00">20</span>, <span style="color: #00af00; text-decoration-color: #00af00">441</span>)          │        <span style="color: #00af00; text-decoration-color: #00af00">56,889</span> │
└─────────────────────────────────┴────────────────────────┴───────────────┘
</pre>




<pre style="white-space:pre;overflow-x:auto;line-height:normal;font-family:Menlo,'DejaVu Sans Mono',consolas,'Courier New',monospace"><span style="font-weight: bold"> Total params: </span><span style="color: #00af00; text-decoration-color: #00af00">551,789</span> (2.10 MB)
</pre>




<pre style="white-space:pre;overflow-x:auto;line-height:normal;font-family:Menlo,'DejaVu Sans Mono',consolas,'Courier New',monospace"><span style="font-weight: bold"> Trainable params: </span><span style="color: #00af00; text-decoration-color: #00af00">183,929</span> (718.47 KB)
</pre>




<pre style="white-space:pre;overflow-x:auto;line-height:normal;font-family:Menlo,'DejaVu Sans Mono',consolas,'Courier New',monospace"><span style="font-weight: bold"> Non-trainable params: </span><span style="color: #00af00; text-decoration-color: #00af00">0</span> (0.00 B)
</pre>




<pre style="white-space:pre;overflow-x:auto;line-height:normal;font-family:Menlo,'DejaVu Sans Mono',consolas,'Courier New',monospace"><span style="font-weight: bold"> Optimizer params: </span><span style="color: #00af00; text-decoration-color: #00af00">367,860</span> (1.40 MB)
</pre>




```python
def generate_tokens(model, seed_sequence, gen_length=1000, temperature=1.0):
    generated = list(seed_sequence)
    for _ in range(gen_length):
        input_seq = np.array(generated[-seq_length:])[None, :]  # batch size 1
        preds = model.predict(input_seq)[0, -1]
        preds = np.log(preds) / temperature
        exp_preds = np.exp(preds)
        preds = exp_preds / np.sum(exp_preds)
        next_id = np.random.choice(len(preds), p=preds)
        generated.append(next_id)
    return generated

# Start generation with the first sequence as seed
seed_seq = encoded_sequence[:seq_length]
generated_ids = generate_tokens(model, seed_seq)

generated_tokens = [id_to_token[i] for i in generated_ids]
print(generated_tokens)
```

    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 156ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 47ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 45ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 51ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 42ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 42ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 43ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 43ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 42ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 42ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 42ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 45ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 48ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 44ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 45ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 56ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 47ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 59ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 47ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 52ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 50ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 48ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 53ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 57ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 56ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 52ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 47ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 46ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 46ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 52ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 50ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 54ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 54ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 61ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 52ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 50ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 43ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 46ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 46ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 51ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 42ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 43ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 43ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 48ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 42ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 44ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 43ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 44ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 32ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 44ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 43ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 42ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 47ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 49ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 43ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 43ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 57ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 32ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 43ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 42ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 50ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 42ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 48ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 46ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 40ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 41ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 33ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 45ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 45ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 39ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 38ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 36ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 34ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 35ms/step
    [1m1/1[0m [32m━━━━━━━━━━━━━━━━━━━━[0m[37m[0m [1m0s[0m 37ms/step
    ['TS_2.50_P_66_D_0.28', 'TS_0.25_P_47_D_0.93', 'TS_0.00_P_75_D_0.33', 'TS_0.25_P_54_D_0.79', 'TS_0.25_P_59_D_0.53', 'TS_0.00_P_73_D_0.18', 'TS_0.25_P_66_D_0.81', 'TS_0.25_P_71_D_0.21', 'TS_0.25_P_80_D_0.13', 'TS_0.25_P_82_D_0.16', 'TS_0.25_P_49_D_0.83', 'TS_0.00_P_80_D_0.83', 'TS_0.25_P_56_D_0.59', 'TS_0.25_P_61_D_0.61', 'TS_0.25_P_65_D_0.46', 'TS_0.50_P_66_D_0.23', 'TS_0.25_P_46_D_1.09', 'TS_0.00_P_75_D_0.34', 'TS_0.25_P_53_D_0.89', 'TS_0.25_P_58_D_0.98', 'TS_0.00_P_73_D_0.52', 'TS_0.25_P_61_D_0.74', 'TS_0.50_P_70_D_1.04', 'TS_0.25_P_54_D_0.86', 'TS_0.25_P_54_D_0.86', 'TS_0.25_P_58_D_0.80', 'TS_0.25_P_66_D_0.73', 'TS_0.25_P_66_D_0.73', 'TS_0.25_P_47_D_0.90', 'TS_0.00_P_78_D_0.17', 'TS_0.25_P_54_D_0.73', 'TS_0.00_P_80_D_0.08', 'TS_0.25_P_59_D_0.59', 'TS_0.00_P_82_D_0.58', 'TS_0.25_P_63_D_0.63', 'TS_0.50_P_73_D_0.14', 'TS_0.25_P_49_D_0.92', 'TS_0.00_P_61_D_0.55', 'TS_0.00_P_61_D_0.55', 'TS_0.00_P_78_D_0.14', 'TS_0.25_P_80_D_0.09', 'TS_0.25_P_56_D_0.21', 'TS_0.00_P_82_D_0.46', 'TS_0.25_P_65_D_0.41', 'TS_0.75_P_42_D_1.23', 'TS_0.25_P_49_D_0.99', 'TS_0.00_P_66_D_0.26', 'TS_0.25_P_61_D_0.60', 'TS_0.00_P_66_D_0.26', 'TS_0.25_P_61_D_0.60', 'TS_0.00_P_54_D_0.55', 'TS_0.00_P_73_D_1.16', 'TS_0.25_P_42_D_0.88', 'TS_0.00_P_54_D_0.55', 'TS_0.00_P_58_D_0.39', 'TS_0.00_P_61_D_0.38', 'TS_0.00_P_66_D_0.45', 'TS_0.25_P_49_D_0.47', 'TS_0.25_P_54_D_0.24', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.28', 'TS_0.25_P_63_D_0.06', 'TS_0.25_P_66_D_0.07', 'TS_0.25_P_68_D_0.08', 'TS_0.00_P_54_D_0.45', 'TS_0.00_P_59_D_0.45', 'TS_0.00_P_70_D_0.11', 'TS_0.25_P_66_D_0.21', 'TS_0.25_P_54_D_0.21', 'TS_0.00_P_59_D_0.23', 'TS_0.00_P_63_D_0.24', 'TS_0.00_P_63_D_0.24', 'TS_0.00_P_63_D_0.24', 'TS_0.25_P_49_D_0.80', 'TS_0.00_P_56_D_0.41', 'TS_0.00_P_61_D_0.35', 'TS_0.00_P_65_D_0.39', 'TS_0.75_P_56_D_0.21', 'TS_0.00_P_61_D_0.33', 'TS_0.00_P_65_D_0.36', 'TS_0.75_P_46_D_0.69', 'TS_0.00_P_58_D_0.45', 'TS_0.00_P_61_D_0.41', 'TS_0.00_P_65_D_0.46', 'TS_0.00_P_68_D_0.23', 'TS_0.00_P_80_D_0.23', 'TS_0.25_P_53_D_0.27', 'TS_0.00_P_77_D_0.19', 'TS_0.25_P_58_D_0.17', 'TS_0.00_P_61_D_0.34', 'TS_0.00_P_65_D_0.34', 'TS_0.00_P_73_D_0.19', 'TS_0.25_P_58_D_0.13', 'TS_0.00_P_78_D_0.77', 'TS_0.25_P_39_D_0.77', 'TS_0.00_P_51_D_0.48', 'TS_0.00_P_54_D_0.37', 'TS_0.25_P_46_D_0.36', 'TS_0.25_P_51_D_0.10', 'TS_0.00_P_54_D_0.34', 'TS_0.00_P_58_D_0.36', 'TS_0.00_P_73_D_0.10', 'TS_0.25_P_75_D_0.07', 'TS_0.25_P_78_D_0.07', 'TS_0.00_P_73_D_0.10', 'TS_0.25_P_80_D_0.09', 'TS_0.25_P_47_D_0.77', 'TS_0.00_P_54_D_0.44', 'TS_0.00_P_59_D_0.47', 'TS_0.00_P_82_D_0.10', 'TS_0.25_P_78_D_0.21', 'TS_0.25_P_54_D_0.12', 'TS_0.00_P_59_D_0.33', 'TS_0.00_P_63_D_0.36', 'TS_0.00_P_75_D_0.16', 'TS_0.25_P_80_D_0.49', 'TS_0.25_P_49_D_0.89', 'TS_0.25_P_49_D_0.89', 'TS_0.00_P_56_D_0.40', 'TS_0.00_P_61_D_0.41', 'TS_0.00_P_65_D_0.41', 'TS_0.25_P_56_D_0.15', 'TS_0.00_P_61_D_0.36', 'TS_0.00_P_65_D_0.36', 'TS_0.00_P_80_D_0.13', 'TS_0.00_P_80_D_0.13', 'TS_0.25_P_56_D_0.11', 'TS_0.00_P_78_D_1.22', 'TS_0.25_P_42_D_2.43', 'TS_0.00_P_54_D_0.47', 'TS_0.25_P_49_D_0.44', 'TS_0.25_P_54_D_0.28', 'TS_0.25_P_54_D_0.28', 'TS_0.00_P_58_D_0.27', 'TS_0.25_P_49_D_0.40', 'TS_0.00_P_61_D_0.25', 'TS_0.00_P_61_D_0.32', 'TS_0.00_P_58_D_0.27', 'TS_0.00_P_61_D_0.32', 'TS_0.00_P_75_D_0.28', 'TS_0.25_P_49_D_0.75', 'TS_0.00_P_73_D_0.11', 'TS_0.25_P_68_D_0.08', 'TS_0.25_P_68_D_0.08', 'TS_0.00_P_58_D_0.48', 'TS_0.00_P_61_D_0.50', 'TS_0.00_P_70_D_0.18', 'TS_0.00_P_70_D_0.18', 'TS_0.00_P_61_D_0.50', 'TS_0.25_P_68_D_0.12', 'TS_0.00_P_75_D_0.06', 'TS_0.00_P_68_D_0.12', 'TS_0.25_P_54_D_0.20', 'TS_0.00_P_66_D_0.07', 'TS_0.00_P_66_D_0.33', 'TS_0.25_P_68_D_0.08', 'TS_0.25_P_47_D_0.76', 'TS_0.00_P_59_D_0.36', 'TS_0.00_P_63_D_0.44', 'TS_0.00_P_70_D_0.11', 'TS_0.25_P_54_D_0.47', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_59_D_0.28', 'TS_0.25_P_63_D_0.24', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_61_D_0.76', 'TS_0.00_P_65_D_0.72', 'TS_0.00_P_68_D_0.99', 'TS_0.25_P_49_D_0.79', 'TS_0.25_P_56_D_0.40', 'TS_0.25_P_61_D_0.15', 'TS_0.00_P_65_D_0.23', 'TS_0.00_P_68_D_0.38', 'TS_0.25_P_61_D_0.10', 'TS_0.25_P_46_D_0.90', 'TS_0.00_P_58_D_0.32', 'TS_0.00_P_61_D_0.34', 'TS_0.00_P_68_D_0.23', 'TS_0.25_P_53_D_0.50', 'TS_0.00_P_65_D_0.19', 'TS_0.25_P_58_D_0.11', 'TS_0.25_P_58_D_0.14', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.19', 'TS_0.00_P_65_D_0.16', 'TS_0.25_P_58_D_0.69', 'TS_0.00_P_63_D_0.70', 'TS_0.00_P_66_D_0.77', 'TS_0.25_P_51_D_1.02', 'TS_0.25_P_54_D_0.67', 'TS_0.25_P_58_D_0.17', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_63_D_0.36', 'TS_0.00_P_66_D_0.40', 'TS_0.25_P_63_D_0.07', 'TS_0.25_P_58_D_0.10', 'TS_0.00_P_66_D_0.07', 'TS_0.25_P_68_D_0.09', 'TS_0.25_P_47_D_0.75', 'TS_0.00_P_59_D_0.36', 'TS_0.00_P_63_D_0.37', 'TS_0.00_P_70_D_0.10', 'TS_0.25_P_54_D_0.43', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_59_D_0.13', 'TS_0.25_P_59_D_0.13', 'TS_0.00_P_63_D_0.11', 'TS_0.00_P_63_D_0.16', 'TS_0.00_P_66_D_0.15', 'TS_0.25_P_61_D_0.74', 'TS_0.00_P_65_D_0.71', 'TS_0.00_P_68_D_0.49', 'TS_0.25_P_49_D_0.88', 'TS_0.25_P_56_D_0.43', 'TS_0.00_P_61_D_0.13', 'TS_0.25_P_61_D_0.17', 'TS_0.00_P_65_D_0.42', 'TS_0.00_P_68_D_0.13', 'TS_0.25_P_61_D_0.20', 'TS_0.00_P_66_D_1.22', 'TS_0.25_P_42_D_2.43', 'TS_0.25_P_42_D_2.43', 'TS_0.00_P_58_D_0.40', 'TS_0.25_P_49_D_0.43', 'TS_0.00_P_78_D_0.14', 'TS_0.25_P_85_D_0.09', 'TS_0.00_P_54_D_0.05', 'TS_0.00_P_58_D_0.39', 'TS_0.00_P_61_D_0.40', 'TS_0.00_P_87_D_0.29', 'TS_0.25_P_85_D_0.11', 'TS_0.00_P_49_D_0.47', 'TS_0.25_P_54_D_0.14', 'TS_0.25_P_85_D_0.08', 'TS_0.00_P_54_D_0.44', 'TS_0.00_P_58_D_0.44', 'TS_0.00_P_61_D_0.43', 'TS_0.00_P_58_D_0.44', 'TS_0.00_P_61_D_0.43', 'TS_0.00_P_66_D_0.39', 'TS_0.00_P_87_D_0.34', 'TS_0.25_P_85_D_0.10', 'TS_0.00_P_49_D_0.45', 'TS_0.25_P_80_D_0.08', 'TS_0.00_P_82_D_0.19', 'TS_0.00_P_54_D_0.32', 'TS_0.00_P_58_D_0.49', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.28', 'TS_0.25_P_63_D_0.06', 'TS_0.00_P_80_D_0.12', 'TS_0.25_P_49_D_0.21', 'TS_0.00_P_66_D_0.07', 'TS_0.00_P_78_D_0.26', 'TS_0.25_P_54_D_0.17', 'TS_0.00_P_68_D_0.08', 'TS_0.25_P_47_D_0.76', 'TS_0.00_P_59_D_0.36', 'TS_0.00_P_63_D_0.44', 'TS_0.00_P_70_D_0.11', 'TS_0.25_P_78_D_0.10', 'TS_0.00_P_66_D_0.21', 'TS_0.00_P_80_D_0.09', 'TS_0.25_P_59_D_0.28', 'TS_0.00_P_82_D_0.14', 'TS_0.00_P_82_D_0.14', 'TS_0.25_P_63_D_0.24', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_61_D_0.76', 'TS_0.00_P_65_D_0.72', 'TS_0.00_P_68_D_0.99', 'TS_0.25_P_49_D_0.79', 'TS_0.25_P_56_D_0.40', 'TS_0.00_P_80_D_0.10', 'TS_0.25_P_82_D_0.08', 'TS_0.25_P_61_D_0.15', 'TS_0.00_P_65_D_0.23', 'TS_0.00_P_68_D_0.38', 'TS_0.00_P_80_D_0.23', 'TS_0.25_P_61_D_0.10', 'TS_0.25_P_46_D_0.90', 'TS_0.00_P_58_D_0.32', 'TS_0.00_P_61_D_0.34', 'TS_0.00_P_68_D_0.23', 'TS_0.25_P_53_D_0.50', 'TS_0.00_P_65_D_0.19', 'TS_0.25_P_58_D_0.11', 'TS_0.25_P_58_D_0.14', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.19', 'TS_0.00_P_65_D_0.16', 'TS_0.00_P_65_D_0.16', 'TS_0.25_P_58_D_0.69', 'TS_0.00_P_63_D_0.70', 'TS_0.00_P_66_D_0.77', 'TS_0.25_P_51_D_1.02', 'TS_0.00_P_78_D_0.07', 'TS_0.25_P_80_D_0.10', 'TS_0.25_P_54_D_0.67', 'TS_0.00_P_82_D_0.25', 'TS_0.25_P_58_D_0.17', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_63_D_0.36', 'TS_0.00_P_66_D_0.40', 'TS_0.25_P_63_D_0.07', 'TS_0.25_P_58_D_0.10', 'TS_0.00_P_66_D_0.07', 'TS_0.25_P_68_D_0.09', 'TS_0.25_P_68_D_0.09', 'TS_0.25_P_47_D_0.75', 'TS_0.00_P_59_D_0.36', 'TS_0.00_P_63_D_0.37', 'TS_0.00_P_70_D_0.10', 'TS_0.25_P_54_D_0.43', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_59_D_0.13', 'TS_0.25_P_59_D_0.13', 'TS_0.00_P_63_D_0.11', 'TS_0.00_P_63_D_0.16', 'TS_0.00_P_66_D_0.15', 'TS_0.00_P_65_D_0.71', 'TS_0.00_P_68_D_0.49', 'TS_0.25_P_49_D_0.88', 'TS_0.25_P_56_D_0.43', 'TS_0.00_P_61_D_0.13', 'TS_0.25_P_61_D_0.17', 'TS_0.00_P_65_D_0.42', 'TS_0.00_P_68_D_0.13', 'TS_0.00_P_68_D_0.41', 'TS_0.25_P_61_D_0.20', 'TS_0.00_P_66_D_1.22', 'TS_0.25_P_42_D_2.43', 'TS_0.00_P_54_D_0.46', 'TS_0.25_P_49_D_0.43', 'TS_0.25_P_49_D_0.43', 'TS_0.00_P_78_D_0.14', 'TS_0.00_P_54_D_0.05', 'TS_0.00_P_58_D_0.39', 'TS_0.00_P_61_D_0.40', 'TS_0.00_P_87_D_0.29', 'TS_0.25_P_85_D_0.11', 'TS_0.00_P_49_D_0.47', 'TS_0.00_P_49_D_0.47', 'TS_0.00_P_54_D_0.44', 'TS_0.00_P_58_D_0.44', 'TS_0.00_P_61_D_0.43', 'TS_0.00_P_66_D_0.39', 'TS_0.00_P_87_D_0.34', 'TS_0.25_P_85_D_0.10', 'TS_0.00_P_49_D_0.45', 'TS_0.25_P_80_D_0.08', 'TS_0.00_P_82_D_0.19', 'TS_0.00_P_54_D_0.32', 'TS_0.00_P_58_D_0.49', 'TS_0.00_P_61_D_0.10', 'TS_0.25_P_63_D_0.06', 'TS_0.00_P_80_D_0.12', 'TS_0.00_P_66_D_0.07', 'TS_0.00_P_78_D_0.26', 'TS_0.25_P_54_D_0.17', 'TS_0.00_P_68_D_0.08', 'TS_0.25_P_47_D_0.76', 'TS_0.00_P_59_D_0.36', 'TS_0.00_P_63_D_0.44', 'TS_0.00_P_70_D_0.11', 'TS_0.25_P_78_D_0.10', 'TS_0.25_P_54_D_0.47', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_59_D_0.28', 'TS_0.25_P_63_D_0.24', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_61_D_0.76', 'TS_0.00_P_65_D_0.72', 'TS_0.00_P_68_D_0.99', 'TS_0.25_P_49_D_0.79', 'TS_0.25_P_56_D_0.40', 'TS_0.25_P_61_D_0.15', 'TS_0.00_P_65_D_0.23', 'TS_0.00_P_68_D_0.38', 'TS_0.25_P_61_D_0.10', 'TS_0.25_P_46_D_0.90', 'TS_0.00_P_58_D_0.32', 'TS_0.00_P_61_D_0.34', 'TS_0.00_P_68_D_0.23', 'TS_0.25_P_53_D_0.50', 'TS_0.25_P_53_D_0.50', 'TS_0.00_P_65_D_0.19', 'TS_0.00_P_77_D_0.19', 'TS_0.25_P_58_D_0.11', 'TS_0.25_P_58_D_0.14', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.19', 'TS_0.00_P_65_D_0.16', 'TS_0.25_P_58_D_0.69', 'TS_0.00_P_63_D_0.70', 'TS_0.00_P_66_D_0.77', 'TS_0.25_P_51_D_1.02', 'TS_0.00_P_78_D_0.07', 'TS_0.25_P_80_D_0.10', 'TS_0.25_P_54_D_0.67', 'TS_0.00_P_82_D_0.25', 'TS_0.25_P_58_D_0.17', 'TS_0.00_P_63_D_0.36', 'TS_0.00_P_66_D_0.40', 'TS_0.25_P_63_D_0.07', 'TS_0.25_P_58_D_0.10', 'TS_0.00_P_66_D_0.07', 'TS_0.25_P_68_D_0.09', 'TS_0.25_P_47_D_0.75', 'TS_0.00_P_59_D_0.36', 'TS_0.00_P_63_D_0.37', 'TS_0.00_P_70_D_0.10', 'TS_0.25_P_54_D_0.43', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_59_D_0.13', 'TS_0.25_P_59_D_0.13', 'TS_0.00_P_63_D_0.11', 'TS_0.00_P_63_D_0.16', 'TS_0.00_P_66_D_0.15', 'TS_0.25_P_61_D_0.74', 'TS_0.00_P_65_D_0.71', 'TS_0.00_P_68_D_0.49', 'TS_0.25_P_49_D_0.88', 'TS_0.25_P_56_D_0.43', 'TS_0.00_P_61_D_0.13', 'TS_0.25_P_61_D_0.17', 'TS_0.00_P_65_D_0.42', 'TS_0.00_P_68_D_0.13', 'TS_0.00_P_68_D_0.41', 'TS_0.25_P_61_D_0.20', 'TS_0.00_P_66_D_1.22', 'TS_0.25_P_42_D_2.43', 'TS_0.00_P_54_D_0.46', 'TS_0.00_P_58_D_0.40', 'TS_0.25_P_49_D_0.43', 'TS_0.25_P_54_D_0.05', 'TS_0.00_P_58_D_0.39', 'TS_0.00_P_61_D_0.40', 'TS_0.25_P_49_D_0.47', 'TS_0.25_P_54_D_0.14', 'TS_0.25_P_54_D_0.44', 'TS_0.00_P_58_D_0.44', 'TS_0.00_P_61_D_0.43', 'TS_0.00_P_66_D_0.39', 'TS_0.25_P_49_D_0.45', 'TS_0.25_P_54_D_0.32', 'TS_0.00_P_58_D_0.49', 'TS_0.00_P_73_D_0.10', 'TS_0.00_P_73_D_0.14', 'TS_0.25_P_75_D_0.10', 'TS_0.00_P_78_D_0.09', 'TS_0.25_P_54_D_0.17', 'TS_0.00_P_80_D_0.11', 'TS_0.25_P_47_D_1.01', 'TS_0.25_P_47_D_1.01', 'TS_0.00_P_59_D_0.38', 'TS_0.00_P_59_D_0.38', 'TS_0.00_P_82_D_0.26', 'TS_0.00_P_82_D_0.26', 'TS_0.00_P_66_D_0.21', 'TS_0.00_P_80_D_0.09', 'TS_0.25_P_59_D_0.28', 'TS_0.00_P_82_D_0.10', 'TS_0.00_P_75_D_0.24', 'TS_0.25_P_54_D_0.12', 'TS_0.25_P_61_D_0.76', 'TS_0.25_P_61_D_0.76', 'TS_0.00_P_65_D_0.72', 'TS_0.00_P_80_D_0.99', 'TS_0.25_P_49_D_0.79', 'TS_0.00_P_80_D_0.99', 'TS_0.25_P_56_D_0.40', 'TS_0.25_P_61_D_0.15', 'TS_0.00_P_65_D_0.23', 'TS_0.25_P_61_D_0.10', 'TS_0.25_P_46_D_0.90', 'TS_0.00_P_58_D_0.32', 'TS_0.00_P_61_D_0.34', 'TS_0.00_P_68_D_0.23', 'TS_0.25_P_53_D_0.50', 'TS_0.00_P_65_D_0.19', 'TS_0.25_P_58_D_0.11', 'TS_0.25_P_58_D_0.14', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.19', 'TS_0.00_P_65_D_0.16', 'TS_0.25_P_58_D_0.69', 'TS_0.00_P_63_D_0.70', 'TS_0.00_P_66_D_0.77', 'TS_0.25_P_51_D_1.02', 'TS_0.25_P_54_D_0.67', 'TS_0.25_P_80_D_0.10', 'TS_0.25_P_54_D_0.67', 'TS_0.00_P_82_D_0.25', 'TS_0.25_P_58_D_0.17', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_63_D_0.36', 'TS_0.00_P_66_D_0.40', 'TS_0.25_P_63_D_0.07', 'TS_0.25_P_58_D_0.10', 'TS_0.00_P_66_D_0.07', 'TS_0.25_P_68_D_0.09', 'TS_0.25_P_47_D_0.75', 'TS_0.00_P_59_D_0.36', 'TS_0.00_P_63_D_0.37', 'TS_0.00_P_70_D_0.10', 'TS_0.25_P_54_D_0.43', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_59_D_0.13', 'TS_0.25_P_59_D_0.13', 'TS_0.00_P_63_D_0.11', 'TS_0.00_P_63_D_0.16', 'TS_0.00_P_66_D_0.15', 'TS_0.25_P_61_D_0.74', 'TS_0.00_P_65_D_0.71', 'TS_0.00_P_68_D_0.49', 'TS_0.25_P_49_D_0.88', 'TS_0.25_P_56_D_0.43', 'TS_0.00_P_61_D_0.13', 'TS_0.25_P_61_D_0.17', 'TS_0.00_P_65_D_0.42', 'TS_0.00_P_68_D_0.13', 'TS_0.00_P_68_D_0.41', 'TS_0.25_P_61_D_0.20', 'TS_0.00_P_66_D_1.22', 'TS_0.25_P_42_D_2.43', 'TS_0.00_P_54_D_0.46', 'TS_0.00_P_58_D_0.40', 'TS_0.25_P_49_D_0.43', 'TS_0.25_P_54_D_0.05', 'TS_0.00_P_58_D_0.39', 'TS_0.00_P_61_D_0.40', 'TS_0.25_P_49_D_0.47', 'TS_0.25_P_49_D_0.47', 'TS_0.25_P_54_D_0.14', 'TS_0.25_P_54_D_0.44', 'TS_0.00_P_58_D_0.44', 'TS_0.00_P_61_D_0.43', 'TS_0.00_P_87_D_0.34', 'TS_0.25_P_49_D_0.45', 'TS_0.00_P_58_D_0.49', 'TS_0.00_P_58_D_0.49', 'TS_0.00_P_73_D_0.14', 'TS_0.25_P_75_D_0.10', 'TS_0.25_P_75_D_0.10', 'TS_0.25_P_49_D_0.21', 'TS_0.00_P_78_D_0.09', 'TS_0.25_P_54_D_0.17', 'TS_0.00_P_80_D_0.11', 'TS_0.25_P_47_D_1.01', 'TS_0.00_P_59_D_0.38', 'TS_0.00_P_63_D_0.49', 'TS_0.00_P_82_D_0.26', 'TS_0.25_P_54_D_0.67', 'TS_0.00_P_80_D_0.09', 'TS_0.00_P_82_D_0.14', 'TS_0.00_P_80_D_0.09', 'TS_0.25_P_78_D_0.21', 'TS_0.00_P_78_D_0.10', 'TS_0.25_P_66_D_0.52', 'TS_0.00_P_75_D_0.24', 'TS_0.25_P_80_D_0.99', 'TS_0.00_P_63_D_0.24', 'TS_0.25_P_49_D_0.80', 'TS_0.00_P_56_D_0.41', 'TS_0.00_P_61_D_0.35', 'TS_0.00_P_65_D_0.39', 'TS_0.75_P_56_D_0.21', 'TS_0.00_P_61_D_0.33', 'TS_0.00_P_68_D_0.14', 'TS_0.00_P_61_D_0.33', 'TS_0.00_P_65_D_0.36', 'TS_0.75_P_46_D_0.69', 'TS_0.00_P_58_D_0.45', 'TS_0.00_P_61_D_0.41', 'TS_0.00_P_65_D_0.46', 'TS_0.00_P_80_D_0.23', 'TS_0.25_P_53_D_0.27', 'TS_0.00_P_65_D_0.19', 'TS_0.25_P_58_D_0.17', 'TS_0.00_P_61_D_0.34', 'TS_0.00_P_65_D_0.34', 'TS_0.00_P_73_D_0.19', 'TS_0.25_P_58_D_0.13', 'TS_0.00_P_66_D_0.77', 'TS_0.25_P_51_D_1.02', 'TS_0.25_P_39_D_0.77', 'TS_0.00_P_51_D_0.48', 'TS_0.00_P_51_D_0.48', 'TS_0.00_P_54_D_0.37', 'TS_0.25_P_46_D_0.36', 'TS_0.25_P_51_D_0.10', 'TS_0.00_P_54_D_0.34', 'TS_0.00_P_58_D_0.36', 'TS_0.25_P_58_D_0.10', 'TS_0.25_P_63_D_0.07', 'TS_0.25_P_68_D_0.09', 'TS_0.25_P_47_D_0.77', 'TS_0.00_P_54_D_0.44', 'TS_0.00_P_59_D_0.47', 'TS_0.00_P_82_D_0.10', 'TS_0.25_P_54_D_0.12', 'TS_0.00_P_59_D_0.33', 'TS_0.25_P_54_D_0.12', 'TS_0.00_P_75_D_0.16', 'TS_0.00_P_63_D_0.36', 'TS_0.25_P_49_D_0.89', 'TS_0.25_P_49_D_0.89', 'TS_0.00_P_56_D_0.40', 'TS_0.00_P_61_D_0.41', 'TS_0.00_P_65_D_0.41', 'TS_0.25_P_73_D_0.13', 'TS_0.25_P_56_D_0.15', 'TS_0.00_P_61_D_0.36', 'TS_0.00_P_80_D_0.13', 'TS_0.00_P_65_D_0.36', 'TS_0.00_P_78_D_1.22', 'TS_0.25_P_42_D_2.43', 'TS_0.00_P_54_D_0.47', 'TS_0.00_P_54_D_0.47', 'TS_0.00_P_58_D_0.44', 'TS_0.25_P_49_D_0.44', 'TS_0.25_P_54_D_0.28', 'TS_0.25_P_54_D_0.28', 'TS_0.00_P_61_D_0.25', 'TS_0.00_P_61_D_0.25', 'TS_0.25_P_49_D_0.40', 'TS_0.00_P_58_D_0.27', 'TS_0.00_P_61_D_0.32', 'TS_0.25_P_73_D_0.09', 'TS_0.25_P_49_D_0.75', 'TS_0.00_P_73_D_0.11', 'TS_0.25_P_68_D_0.08', 'TS_0.00_P_58_D_0.48', 'TS_0.00_P_61_D_0.50', 'TS_0.00_P_66_D_0.50', 'TS_0.00_P_70_D_0.18', 'TS_0.00_P_73_D_0.10', 'TS_0.25_P_68_D_0.12', 'TS_0.00_P_75_D_0.06', 'TS_0.25_P_54_D_0.20', 'TS_0.00_P_66_D_0.33', 'TS_0.00_P_78_D_0.07', 'TS_0.25_P_80_D_0.08', 'TS_0.25_P_80_D_0.08', 'TS_0.00_P_54_D_0.45', 'TS_0.00_P_63_D_0.45', 'TS_0.00_P_82_D_0.11', 'TS_0.25_P_78_D_0.21', 'TS_0.25_P_54_D_0.21', 'TS_0.00_P_59_D_0.23', 'TS_0.00_P_63_D_0.24', 'TS_0.00_P_75_D_0.24', 'TS_0.25_P_80_D_0.99', 'TS_0.25_P_49_D_0.80', 'TS_0.00_P_56_D_0.41', 'TS_0.00_P_61_D_0.35', 'TS_0.00_P_65_D_0.39', 'TS_0.75_P_56_D_0.21', 'TS_0.00_P_61_D_0.33', 'TS_0.00_P_65_D_0.36', 'TS_0.75_P_46_D_0.69', 'TS_0.00_P_58_D_0.45', 'TS_0.00_P_61_D_0.41', 'TS_0.00_P_65_D_0.46', 'TS_0.00_P_68_D_0.23', 'TS_0.25_P_53_D_0.27', 'TS_0.25_P_53_D_0.50', 'TS_0.00_P_65_D_0.19', 'TS_0.25_P_58_D_0.11', 'TS_0.25_P_58_D_0.14', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.19', 'TS_0.00_P_61_D_0.19', 'TS_0.00_P_65_D_0.16', 'TS_0.25_P_58_D_0.69', 'TS_0.25_P_39_D_0.77', 'TS_0.00_P_66_D_0.77', 'TS_0.25_P_39_D_0.77', 'TS_0.00_P_51_D_0.48', 'TS_0.25_P_46_D_0.36', 'TS_0.25_P_51_D_0.10', 'TS_0.00_P_54_D_0.34', 'TS_0.00_P_58_D_0.36', 'TS_0.25_P_75_D_0.07', 'TS_0.25_P_78_D_0.07', 'TS_0.25_P_80_D_0.09', 'TS_0.25_P_47_D_0.77', 'TS_0.00_P_54_D_0.44', 'TS_0.00_P_59_D_0.47', 'TS_0.00_P_82_D_0.10', 'TS_0.25_P_78_D_0.21', 'TS_0.25_P_54_D_0.12', 'TS_0.00_P_59_D_0.33', 'TS_0.00_P_63_D_0.36', 'TS_0.00_P_75_D_0.16', 'TS_0.25_P_80_D_0.49', 'TS_0.00_P_56_D_0.40', 'TS_0.00_P_61_D_0.41', 'TS_0.00_P_65_D_0.41', 'TS_0.00_P_65_D_0.41', 'TS_0.25_P_56_D_0.15', 'TS_0.25_P_56_D_0.15', 'TS_0.00_P_61_D_0.36', 'TS_0.00_P_65_D_0.36', 'TS_0.00_P_68_D_0.13', 'TS_0.25_P_56_D_0.11', 'TS_0.25_P_42_D_2.43', 'TS_0.00_P_54_D_0.47', 'TS_0.00_P_54_D_0.47', 'TS_0.00_P_58_D_0.44', 'TS_0.25_P_49_D_0.44', 'TS_0.25_P_54_D_0.28', 'TS_0.00_P_58_D_0.27', 'TS_0.00_P_61_D_0.25', 'TS_0.25_P_58_D_0.27', 'TS_0.25_P_58_D_0.27', 'TS_0.25_P_58_D_0.48', 'TS_0.00_P_61_D_0.32', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.58', 'TS_0.00_P_68_D_0.09', 'TS_0.25_P_68_D_0.08', 'TS_0.00_P_63_D_0.06', 'TS_0.25_P_49_D_0.25', 'TS_0.00_P_68_D_0.12', 'TS_0.00_P_66_D_0.07', 'TS_0.25_P_68_D_0.08', 'TS_0.25_P_47_D_0.76', 'TS_0.00_P_59_D_0.36', 'TS_0.00_P_63_D_0.44', 'TS_0.00_P_70_D_0.11', 'TS_0.25_P_78_D_0.10', 'TS_0.25_P_54_D_0.47', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_59_D_0.28', 'TS_0.25_P_63_D_0.24', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_61_D_0.76', 'TS_0.00_P_65_D_0.72', 'TS_0.00_P_68_D_0.99', 'TS_0.25_P_61_D_0.15', 'TS_0.00_P_65_D_0.23', 'TS_0.00_P_68_D_0.38', 'TS_0.25_P_61_D_0.10', 'TS_0.25_P_46_D_0.90', 'TS_0.00_P_58_D_0.32', 'TS_0.00_P_61_D_0.34', 'TS_0.00_P_68_D_0.23', 'TS_0.25_P_53_D_0.50', 'TS_0.00_P_65_D_0.19', 'TS_0.25_P_58_D_0.11', 'TS_0.25_P_58_D_0.14', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.19', 'TS_0.00_P_65_D_0.16', 'TS_0.25_P_58_D_0.69', 'TS_0.00_P_63_D_0.70', 'TS_0.00_P_63_D_0.70', 'TS_0.25_P_51_D_1.02', 'TS_0.00_P_78_D_0.07', 'TS_0.25_P_80_D_0.10', 'TS_0.25_P_54_D_0.67', 'TS_0.00_P_82_D_0.25', 'TS_0.25_P_54_D_0.67', 'TS_0.25_P_58_D_0.17', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_63_D_0.36', 'TS_0.00_P_66_D_0.40', 'TS_0.25_P_63_D_0.07', 'TS_0.25_P_58_D_0.10', 'TS_0.00_P_66_D_0.07', 'TS_0.25_P_68_D_0.09', 'TS_0.25_P_47_D_0.75', 'TS_0.00_P_59_D_0.36', 'TS_0.00_P_63_D_0.37', 'TS_0.00_P_70_D_0.10', 'TS_0.25_P_54_D_0.43', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_59_D_0.13', 'TS_0.25_P_59_D_0.13', 'TS_0.00_P_63_D_0.11', 'TS_0.00_P_75_D_0.16', 'TS_0.00_P_75_D_0.16', 'TS_0.00_P_75_D_0.16', 'TS_0.25_P_61_D_0.74', 'TS_0.00_P_73_D_0.13', 'TS_0.25_P_49_D_0.89', 'TS_0.00_P_70_D_0.18', 'TS_0.25_P_61_D_0.17', 'TS_0.00_P_73_D_0.13', 'TS_0.00_P_73_D_0.13', 'TS_0.00_P_68_D_0.41', 'TS_0.25_P_61_D_0.20', 'TS_0.00_P_78_D_1.22', 'TS_0.25_P_42_D_2.43', 'TS_0.00_P_54_D_0.46', 'TS_0.00_P_58_D_0.40', 'TS_0.25_P_49_D_0.43', 'TS_0.25_P_85_D_0.09', 'TS_0.00_P_58_D_0.39', 'TS_0.00_P_61_D_0.40', 'TS_0.00_P_87_D_0.29', 'TS_0.25_P_85_D_0.11', 'TS_0.00_P_49_D_0.47', 'TS_0.25_P_54_D_0.14', 'TS_0.25_P_85_D_0.08', 'TS_0.00_P_54_D_0.44', 'TS_0.00_P_58_D_0.44', 'TS_0.00_P_61_D_0.43', 'TS_0.00_P_66_D_0.39', 'TS_0.00_P_87_D_0.34', 'TS_0.25_P_85_D_0.10', 'TS_0.00_P_49_D_0.45', 'TS_0.00_P_82_D_0.19', 'TS_0.00_P_54_D_0.32', 'TS_0.00_P_58_D_0.49', 'TS_0.00_P_61_D_0.10', 'TS_0.25_P_63_D_0.06', 'TS_0.25_P_49_D_0.21', 'TS_0.00_P_70_D_0.10', 'TS_0.00_P_78_D_0.26', 'TS_0.25_P_54_D_0.17', 'TS_0.00_P_70_D_0.18', 'TS_0.25_P_47_D_0.76', 'TS_0.00_P_59_D_0.36', 'TS_0.00_P_63_D_0.44', 'TS_0.00_P_63_D_0.44', 'TS_0.25_P_54_D_0.47', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_59_D_0.28', 'TS_0.25_P_63_D_0.24', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_61_D_0.76', 'TS_0.00_P_65_D_0.72', 'TS_0.00_P_68_D_0.99', 'TS_0.25_P_49_D_0.79', 'TS_0.25_P_56_D_0.40', 'TS_0.25_P_61_D_0.15', 'TS_0.00_P_65_D_0.23', 'TS_0.00_P_68_D_0.38', 'TS_0.25_P_61_D_0.10', 'TS_0.25_P_46_D_0.90', 'TS_0.00_P_58_D_0.32', 'TS_0.00_P_61_D_0.34', 'TS_0.00_P_68_D_0.23', 'TS_0.25_P_53_D_0.50', 'TS_0.00_P_65_D_0.19', 'TS_0.25_P_58_D_0.11', 'TS_0.25_P_58_D_0.14', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_61_D_0.19', 'TS_0.00_P_65_D_0.16', 'TS_0.25_P_58_D_0.69', 'TS_0.00_P_63_D_0.70', 'TS_0.00_P_66_D_0.77', 'TS_0.25_P_51_D_1.02', 'TS_0.00_P_78_D_0.07', 'TS_0.25_P_80_D_0.10', 'TS_0.25_P_54_D_0.67', 'TS_0.00_P_82_D_0.25', 'TS_0.25_P_58_D_0.17', 'TS_0.00_P_61_D_0.10', 'TS_0.00_P_63_D_0.36', 'TS_0.00_P_66_D_0.40', 'TS_0.25_P_63_D_0.07', 'TS_0.25_P_58_D_0.10', 'TS_0.00_P_66_D_0.07', 'TS_0.25_P_47_D_0.75', 'TS_0.00_P_59_D_0.36', 'TS_0.00_P_63_D_0.37', 'TS_0.00_P_70_D_0.10', 'TS_0.25_P_54_D_0.43', 'TS_0.00_P_66_D_0.21', 'TS_0.25_P_59_D_0.13', 'TS_0.25_P_59_D_0.13', 'TS_0.00_P_63_D_0.11', 'TS_0.00_P_63_D_0.16', 'TS_0.00_P_66_D_0.15', 'TS_0.25_P_61_D_0.74', 'TS_0.00_P_65_D_0.71', 'TS_0.00_P_68_D_0.49', 'TS_0.25_P_49_D_0.88', 'TS_0.25_P_56_D_0.43', 'TS_0.00_P_61_D_0.13', 'TS_0.00_P_65_D_0.42', 'TS_0.00_P_68_D_0.13', 'TS_0.00_P_68_D_0.41', 'TS_0.25_P_61_D_0.20', 'TS_0.00_P_66_D_1.22', 'TS_0.25_P_42_D_2.43', 'TS_0.00_P_54_D_0.46', 'TS_0.00_P_58_D_0.40', 'TS_0.25_P_49_D_0.43', 'TS_0.25_P_54_D_0.05', 'TS_0.00_P_58_D_0.39', 'TS_0.00_P_61_D_0.40', 'TS_0.25_P_49_D_0.47', 'TS_0.25_P_54_D_0.14', 'TS_0.25_P_54_D_0.44', 'TS_0.00_P_58_D_0.44', 'TS_0.00_P_61_D_0.43', 'TS_0.00_P_66_D_0.39', 'TS_0.25_P_49_D_0.45', 'TS_0.25_P_54_D_0.32', 'TS_0.00_P_58_D_0.49', 'TS_0.25_P_54_D_0.17', 'TS_0.25_P_47_D_0.68', 'TS_0.00_P_66_D_0.41', 'TS_0.25_P_54_D_0.49', 'TS_0.25_P_59_D_0.48', 'TS_0.25_P_63_D_0.29', 'TS_0.00_P_66_D_0.31', 'TS_0.25_P_66_D_0.35', 'TS_0.75_P_49_D_0.67', 'TS_0.00_P_65_D_0.20', 'TS_0.25_P_56_D_0.46', 'TS_0.25_P_61_D_0.43', 'TS_0.25_P_56_D_0.46', 'TS_0.00_P_66_D_0.09', 'TS_0.25_P_65_D_0.23', 'TS_0.00_P_65_D_0.24', 'TS_0.25_P_73_D_0.08', 'TS_0.25_P_73_D_0.08', 'TS_0.00_P_75_D_0.27', 'TS_0.25_P_73_D_0.23', 'TS_0.25_P_46_D_0.72', 'TS_0.00_P_65_D_0.14', 'TS_0.25_P_53_D_0.49', 'TS_0.25_P_58_D_0.35', 'TS_0.00_P_66_D_0.09', 'TS_0.25_P_61_D_0.16', 'TS_0.00_P_65_D_0.10', 'TS_0.25_P_61_D_0.11', 'TS_0.25_P_63_D_0.62', 'TS_0.25_P_51_D_0.68', 'TS_0.25_P_54_D_0.55', 'TS_0.25_P_58_D_0.44', 'TS_0.00_P_68_D_0.09', 'TS_0.00_P_70_D_0.40', 'TS_0.00_P_70_D_0.40', 'TS_0.00_P_66_D_0.25', 'TS_0.00_P_66_D_0.09', 'TS_0.25_P_65_D_0.08', 'TS_0.00_P_68_D_0.08', 'TS_0.25_P_47_D_0.79', 'TS_0.00_P_66_D_0.49', 'TS_0.00_P_70_D_0.35', 'TS_0.00_P_70_D_0.35', 'TS_0.25_P_54_D_0.61', 'TS_0.25_P_59_D_0.42', 'TS_0.25_P_63_D_0.23', 'TS_0.00_P_66_D_0.25', 'TS_0.00_P_68_D_0.12', 'TS_0.00_P_65_D_0.18', 'TS_0.25_P_56_D_0.56', 'TS_0.25_P_56_D_0.56', 'TS_0.25_P_61_D_0.38', 'TS_0.25_P_65_D_0.18', 'TS_0.00_P_65_D_0.18', 'TS_0.00_P_68_D_0.13', 'TS_0.25_P_66_D_0.16', 'TS_0.00_P_58_D_0.39', 'TS_0.00_P_66_D_1.07', 'TS_0.25_P_78_D_0.10', 'TS_0.00_P_49_D_0.43', 'TS_0.25_P_80_D_0.08', 'TS_0.25_P_80_D_0.08', 'TS_0.25_P_54_D_0.33', 'TS_0.00_P_66_D_0.31', 'TS_0.00_P_80_D_0.09', 'TS_0.00_P_82_D_0.14', 'TS_0.00_P_80_D_0.13', 'TS_0.00_P_49_D_0.47', 'TS_0.00_P_78_D_0.09', 'TS_0.25_P_54_D_0.40', 'TS_0.25_P_54_D_0.40', 'TS_0.00_P_61_D_0.55', 'TS_0.00_P_73_D_0.11', 'TS_0.00_P_73_D_0.11', 'TS_0.00_P_75_D_0.24', 'TS_0.25_P_49_D_0.61', 'TS_0.00_P_80_D_0.09', 'TS_0.00_P_49_D_0.25', 'TS_0.00_P_54_D_0.77', 'TS_0.00_P_61_D_0.58', 'TS_0.00_P_66_D_0.58', 'TS_0.00_P_70_D_0.13', 'TS_0.00_P_70_D_0.13', 'TS_0.00_P_68_D_0.13', 'TS_0.00_P_49_D_0.25', 'TS_0.00_P_66_D_0.27', 'TS_0.25_P_47_D_0.68', 'TS_0.00_P_66_D_0.37', 'TS_0.25_P_54_D_0.49', 'TS_0.25_P_59_D_0.48', 'TS_0.25_P_63_D_0.29', 'TS_0.00_P_66_D_0.31', 'TS_0.25_P_66_D_0.45', 'TS_0.75_P_49_D_0.67', 'TS_0.00_P_68_D_0.17', 'TS_0.25_P_56_D_0.46', 'TS_0.25_P_61_D_0.43', 'TS_0.00_P_70_D_0.08', 'TS_0.25_P_65_D_0.24', 'TS_0.00_P_68_D_0.18', 'TS_0.00_P_75_D_0.28', 'TS_0.25_P_73_D_0.10', 'TS_0.00_P_75_D_0.28', 'TS_0.25_P_73_D_0.15', 'TS_0.00_P_68_D_0.17', 'TS_0.25_P_53_D_0.49', 'TS_0.25_P_58_D_0.35', 'TS_0.00_P_70_D_0.08', 'TS_0.25_P_61_D_0.16', 'TS_0.00_P_68_D_0.14', 'TS_0.25_P_65_D_0.12', 'TS_0.25_P_66_D_0.87', 'TS_0.25_P_51_D_0.68']
    


```python
def token_sequence_to_notes(token_sequence):
    notes = []
    current_time = 0.0

    for token in token_sequence:
        try:
            parts = token.split('_')
            step = float(parts[1])
            pitch = int(parts[3])
            duration = float(parts[5])
        except:
            continue  # skip malformed tokens

        start_time = current_time + step
        end_time = start_time + duration
        notes.append((pitch, start_time, end_time))
        current_time = start_time  # update time based on step

    return notes

def notes_to_midi_file(notes, output_file='generated.mid'):
    midi = pretty_midi.PrettyMIDI()
    instrument = pretty_midi.Instrument(program=0)

    for pitch, start, end in notes:
        note = pretty_midi.Note(velocity=100, pitch=pitch, start=start, end=end)
        instrument.notes.append(note)

    midi.instruments.append(instrument)
    midi.write(output_file)
    print(f"✅ MIDI file saved as {output_file}")

notes = token_sequence_to_notes(generated_tokens)
notes_to_midi_file(notes, 'generated_music.mid')

```

    ✅ MIDI file saved as generated_music.mid
    
