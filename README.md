# Revisiting Communication in Federated Learning: A Comparative Study of Parameter and Knowledge-Based Strategies

## Authors

- Leonor Ramos
- Carlos Serrão
- Ana Maria de Almeida

## Resources

- 📄 Full Paper (`paper.pdf`)
- 🖼 Poster (`poster.pdf`)

## Abstract

Federated Learning (FL) enables collaborative model training without sharing raw data, making it particularly suitable for privacy-sensitive healthcare applications. However, the effectiveness of FL strongly depends on the communication mechanism used between clients and the server, especially under heterogeneous and non-IID data distributions.

This work presents a comparative experimental study of parameter-based and knowledge-based communication strategies, including FedAvg, knowledge distillation with weight sharing, soft-label communication, and prototype-based methods. Experiments were conducted on three wearable fall detection datasets under a realistic client-disjoint setting.

Results show that FedAvg achieves the best global performance under non-IID data, whereas knowledge-only strategies achieve more competitive local performance, suggesting their relevance for personalization-oriented Federated Learning.

## References

[1] Joshi, M., Pal, A., Sankarasubbu, M. (2022). *Federated Learning for Healthcare Domain – Pipeline, Applications and Challenges*. ACM Transactions on Computing for Healthcare.

[2] Kairouz, P. et al. (2021). *Advances and Open Problems in Federated Learning*.

[3] McMahan, H. B., Moore, E., Ramage, D., Hampson, S., Arcas, B. (2017). *Communication-Efficient Learning of Deep Networks from Decentralized Data*.

[4] Li, T., Sahu, A. K., Talwalkar, A., Smith, V. (2020). *Federated Learning: Challenges, Methods, and Future Directions*. IEEE Signal Processing Magazine.

[5] Li, Y., Li, Y., Xu, H., Ren, S. (2021). *An Adaptive Communication-Efficient Federated Learning to Resist Gradient-Based Reconstruction Attacks*. Security and Communication Networks.

[6] Li, X., Huang, K., Yang, W., Wang, S., Zhang, Z. (2020). *On the Convergence of FedAvg on Non-IID Data*.

[7] Gao, J., Wang, W., Liu, Z., Billah, M. F. R. M., Campbell, B. (2021). *Decentralized Federated Learning Framework for the Neighborhood: A Case Study on Residential Building Load Forecasting*.

[8] Li, D., Wang, J. (2019). *FedMD: Heterogeneous Federated Learning via Model Distillation*.

[9] Wu, C., Wu, F., Lyu, L., Huang, Y., Xie, X. (2022). *Communication-Efficient Federated Learning via Knowledge Distillation*. Nature Communications.

[10] Itahara, S., Nishio, T., Koda, Y., Morikura, M., Yamamoto, K. (2023). *Distillation-Based Semi-Supervised Federated Learning for Communication-Efficient Collaborative Training With Non-IID Private Data*.

[11] Wang, A., Yang, L., Wu, H., Iwahori, Y. (2023). *Heterogeneous Defect Prediction Based on Federated Prototype Learning*. IEEE Access.

[12] Beutel, D. J. et al. (2020). *Flower: A Friendly Federated Learning Research Framework*.

### Datasets

[13] Yu, X., Jang, J., Xiong, S. (2021). *KFall: A Large-Scale Open Motion Dataset and Benchmark Algorithms for Detecting Pre-impact Falls*.

[14] Sucerquia, A., López, J. D., Vargas-Bonilla, J. F. (2017). *SisFall: A Fall and Movement Dataset*.

[15] Martínez-Villaseñor, L. et al. (2019). *UP-Fall Detection Dataset: A Multimodal Approach*.

### Fall Detection and Healthcare Applications

[16] Ghayvat, H. et al. (2019). *Smart Aging System: Uncovering the Hidden Wellness Parameter for Well-Being Monitoring and Anomaly Detection*.

[17] Nawaz, A., Khan, S. S., Ahmad, A. (2024). *Ensemble of Autoencoders for Anomaly Detection in Biomedical Data: A Narrative Review*.

[18] Wazzeh, M. et al. (2024). *Resource-Aware Split Federated Learning for Fall Detection in the Metaverse*.

[19] Haref, Q. M., Long, J., Yang, Z. (2025). *Fall Detection Using Federated Lightweight CNN Models: A Comparison of Decentralized vs. Centralized Learning*.

[20] Aime, L. B. et al. (2025). *Human-Centric Edge Intelligence with Gaussian Splatting for Privacy-Aware Elderly Care*.
