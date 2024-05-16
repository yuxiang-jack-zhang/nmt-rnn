# nmt-rnn
Implementation of a sequence-to-sequence (Seq2Seq) network with attention to build a Neural Machine Translation (NMT) system, part of assign3 for CS224n Spring 2024. Uses a Bidirectional LSTM Encoder and a Unidirectional LSTM Decoder. 

To set up environment:
'''
conda env create −−file env−cpu.yml
conda activate cs224n −cpu
'''

To test model:
'''
sh run.sh test
'''
