# PFLD-pytorch
## Reference
코드: https://github.com/polarisZhao/PFLD-pytorch
논문: https://arxiv.org/abs/1902.10859
WFLW 데이터 셋: https://wywu.github.io/projects/LAB/WFLW.html

## 평가 방법
- WFLW 데이터 셋으로 훈련시킨 PFLD 모델을 300W의 테스트 셋에 대해서 평가함


## Structure
![pfld1](image/pdlf.png)

## Evaluation Result

| Model         | NME(%) | FPS  | VRAM(M) |
|---------------|--------|------|---------|
| PFLD-pytroch  | 5.27   |  263 | 210     |
