Judgements for the 2019 Medical Misinformation Track

All files contain qrels for only the first 30 topics (Topic number 1-31, excluding 14 which was not assessed by NIST)

Files included:
(1) 2019_qrels.DynEval.cal.txt - Set of judgements selected using Dynamic Sampling, created on the full ClueWeb12 corpus.
(2) 2019_qrels.DynEval.trec.1-31.cw12b13.txt - Set of judgements selected using depth-k pooling by NIST (with topics 32-51 removed), created on the ClueWeb12B sub-corpus.
(3) 2019_qrels.DynEval.trec.1-31.txt - NIST judgements from (2) with the inclusion probabilities, meant for evaluating systems on their performance on the full ClueWeb12 corpus.

Usage with dyn_eval:

dyn_eval -q 2019_qrels.DynEval.cal.txt /path/to/run

See https://cormack.uwaterloo.ca/sample/ to learn more about DynEval
