# Assignment 4 Grading

Assignment 4 is graded out of 100 points.

Submit `Attention.py`, `EncoderGRU.py`, `DecoderGRU.py`, `Seq2Seq.py`, `train.py`, `evaluate.py`, and `performance_table.csv`. 

## Run the two models

After activating your course environment, start in the `Assignment_4` directory and run:

```bash
python3 runner_without_attention.py
python3 runner.py
```

`runner_without_attention.py` loads your Assignment 3 Seq2Seq files and produces the baseline metrics. `runner.py` loads your Assignment 4 attention model. Copy the final validation loss, token accuracy, and BLEU values from both runs into `performance_table.csv`.

Do not submit either runner file. Keep the `Assignment_3` and `Assignment_4` directories next to each other when running the baseline.

## Point distribution

| Component | Points |
| --- | ---: |
| Attention | 10 |
| Encoder | 10 |
| Decoder with attention | 20 |
| Seq2Seq integration | 30 |
| Training loop | 10 |
| Evaluation and token accuracy | 10 |
| Performance table | 10 |
| **Total** | **100** |
