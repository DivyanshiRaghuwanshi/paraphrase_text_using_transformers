## paraphrase_text_using_transformers

This project implements a Paraphrasing System that generates reworded versions of input sentences using state-of-the-art Transformer-based language models. It is designed to help rewrite content while retaining its original meaning — useful for content creation, academic writing, and NLP tasks.

## Model Loading

The Pegasus-based paraphrasing model is loaded using the Hugging Face `transformers` library:

from transformers import PegasusForConditionalGeneration, PegasusTokenizer

model = PegasusForConditionalGeneration.from_pretrained('tuner007/pegasus_paraphrase')
tokenizer = PegasusTokenizer.from_pretrained('tuner007/pegasus_paraphrase')

