# Revisiting Communication in Federated Learning: A Comparative Study of Parameter and Knowledge-Based Strategies

## Authors

- Leonor Ramos
- Carlos Serrão
- Ana Maria de Almeida

## Resources

- 📄 Full Paper: [ArticleFlExperiments.pdf](ArticleFlExperiments.pdf)
- 🖼️ Poster: [poster.pdf](poster.pdf)

## Abstract

Federated Learning (FL) enables collaborative model training without centralizing sensitive medical data, making it particularly attractive for healthcare applications. However, conventional weight exchange introduces substantial communication costs and potential privacy risks.

This work compares parameter-based and knowledge-based communication strategies for federated fall detection using three public datasets. While unweighted FedAvg achieved the strongest performance (0.9692 global PR-AUC), alternative no-weight approaches maintained competitive local results. Notably, soft-label communication reduced the communication payload from 49,665 parameters to only two values per communication round, providing the most effective communication-performance trade-off.

These findings highlight the potential of lightweight knowledge-sharing mechanisms for resource-constrained wearable healthcare systems.

## Main Results

| Strategy | Local PR-AUC | Global PR-AUC | Payload |
|-----------|-----------|-----------|-----------|
| FedAvg | **0.9153** | **0.9692** | 49,665 |
| Knowledge Distillation | 0.9143 | 0.9573 | 49,665 |
| Soft Labels | 0.8169 | **0.7365** | **2** |
| Prototypes | **0.8186** | 0.7005 | ~131 |

### Key Findings

- FedAvg achieved the highest predictive performance.
- Knowledge Distillation offered no significant improvement over FedAvg.
- Prototype communication achieved competitive local performance without exchanging model weights.
- Soft-label communication reduced communication cost by approximately **99.996%**.

## Datasets

- KFall Dataset
- SisFall Dataset
- UP-Fall Dataset

## References

[1] McMahan et al., *Communication-Efficient Learning of Deep Networks from Decentralized Data*, 2017.

[2] Kairouz et al., *Advances and Open Problems in Federated Learning*, 2021.

[3] Hinton et al., *Distilling the Knowledge in a Neural Network*, 2015.

[4] Li and Wang, *FedMD: Heterogeneous Federated Learning via Model Distillation*, 2019.

[5] Wu et al., *Communication-Efficient Federated Learning via Knowledge Distillation*, 2022.

[6] Yan et al., *FedRFQ: Prototype-Based Federated Learning*, 2024.

[7] Wang et al., *Heterogeneous Defect Prediction Based on Federated Prototype Learning*, 2023.

[8] Yu et al., *KFall Dataset*, 2021.

[9] Sucerquia et al., *SisFall Dataset*, 2017.

[10] Martínez-Villaseñor et al., *UP-Fall Detection Dataset*, 2019.
