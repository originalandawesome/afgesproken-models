# Afgesproken – modellen

Deze repo bevat geen code, alleen **modelreleases** voor Afgesproken: spraakmodellen die we zelf hebben omgezet en die geen officiële downloadbron hebben. De app haalt ze op via een vaste URL en controleert de SHA256 voordat een model wordt gebruikt.

| Release | Model | Bron | Licentie |
|---|---|---|---|
| `models-parakeet-tdt-0.6b-dutch-v1` | Nederlandse Parakeet TDT 0.6B, int8, sherpa-onnx-formaat | [yuriyvnv/parakeet-tdt-0.6b-dutch](https://huggingface.co/yuriyvnv/parakeet-tdt-0.6b-dutch) (fine-tune van NVIDIA Parakeet TDT 0.6B v3) | [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/) |

Elke release vermeldt het bronmodel, de maker, de licentie, wat er is gewijzigd en de SHA256 van elk bestand. Tags worden nooit verplaatst; een nieuwe versie krijgt een nieuwe tag.
