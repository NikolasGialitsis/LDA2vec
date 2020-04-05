# LDA2vec
python3 example of LDA2vec usage
two types of vectors:  word-vectors and topic-vectors
skip-gram: iteratively use a word as a pivot and try to guess its surrounding words (word2vec). In LDA2vec the pivot is represented as w + a0 * t1 + a1*t2 + ... + an*tn , where w is the pivot word and the a0*t0 the document vector, that is the topics composition of the document
notes: to run the GPU-related commands, change notebook settings 'Hardware Accelerator' to 'GPU'
