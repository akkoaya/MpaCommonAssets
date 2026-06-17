# PaddleOCR model

2026/06/17

from <https://github.com/PaddlePaddle/PaddleOCR/blob/main/docs/version3.x/module_usage/text_detection.en.md>

from <https://github.com/PaddlePaddle/PaddleOCR/blob/main/docs/version3.x/module_usage/text_recognition.en.md>

## det model

PP-OCRv6 detection is shared. Please use `ppocr_v6/zh_cn/det.onnx`.

The `en_us` folder keeps a local copy only for compatibility with existing path conventions.

Official ONNX model:

<https://huggingface.co/PaddlePaddle/PP-OCRv6_small_det_onnx>

## rec model

PP-OCRv6 recognition is shared. `en_us/rec.onnx` uses the same multilingual model as `zh_cn/rec.onnx`.

Official ONNX model:

<https://huggingface.co/PaddlePaddle/PP-OCRv6_small_rec_onnx>

## rec label

PP-OCRv6 uses a shared multilingual dictionary. `en_us/keys.txt` matches the shared model and is intentionally not `en_dict.txt`.

<https://github.com/PaddlePaddle/PaddleOCR/blob/main/ppocr/utils/dict/ppocrv6_dict.txt>
