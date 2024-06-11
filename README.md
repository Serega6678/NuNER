# NuNER: Entity Recognition Encoder Pre-training via LLM-Annotated Data


[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/nuner-entity-recognition-encoder-pre-training/zero-shot-named-entity-recognition-ner-on-1)](https://paperswithcode.com/sota/zero-shot-named-entity-recognition-ner-on-1?p=nuner-entity-recognition-encoder-pre-training)[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/nuner-entity-recognition-encoder-pre-training/few-shot-ner-on-few-nerd-intra)](https://paperswithcode.com/sota/few-shot-ner-on-few-nerd-intra?p=nuner-entity-recognition-encoder-pre-training) [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/nuner-entity-recognition-encoder-pre-training/few-shot-ner-on-few-nerd-inter)](https://paperswithcode.com/sota/few-shot-ner-on-few-nerd-inter?p=nuner-entity-recognition-encoder-pre-training) [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/nuner-entity-recognition-encoder-pre-training/named-entity-recognition-on-few-nerd-sup)](https://paperswithcode.com/sota/named-entity-recognition-on-few-nerd-sup?p=nuner-entity-recognition-encoder-pre-training)

NuNER is the family of SOTA Foundation and Zero-shot for Entity Recognition

## Foundation models:

[HuggingFace](https://huggingface.co/collections/numind/nuner-token-classification-and-ner-backbones-65e1f6e14639e2a465af823b)

- **NuNER 2.0**: `numind/NuNER-v2.0` *(MIT)* - the most powerful English NER model
- **NuNER multilingual** `numind/NuNER-multilingual-v0.1` *(MIT)* - the most powerful multilingual NER model
- **NuNER 1.0** `numind/NuNER-v1.0` *(MIT)* - the main model from our [paper](https://arxiv.org/abs/2402.15343)
- **NuNER BERT** `numind/NuNER-BERT-v1.0`*(MIT)* - the model used in the **TadNER** section of our [paper](https://arxiv.org/abs/2402.15343)

## Zero-shot models:

[HuggingFace](https://huggingface.co/collections/numind/nunerzero-zero-shot-ner-662b59803b9b438ff56e49e2)

- **GLiNER NuNerZero span**: `numind/NuNER_Zero-span`  *(MIT)* - +4.5% more powerful GLiNER Large v2.1
- **NuNerZero**: `numind/NuNER_Zero`  *(MIT)* - +3% more powerful GLiNER Large v2.1, better suitable to detect multi-word entities
- **NuNerZero 4k context**: `numind/NuNER_Zero-4k`  *(MIT)* - 4k-long-context NuNerZero

The last 2 models are word-level GLiNER models with unlimited entity length supported

## Citation
```
@misc{bogdanov2024nuner,
      title={NuNER: Entity Recognition Encoder Pre-training via LLM-Annotated Data}, 
      author={Sergei Bogdanov and Alexandre Constantin and Timothée Bernard and Benoit Crabbé and Etienne Bernard},
      year={2024},
      eprint={2402.15343},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```


