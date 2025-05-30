# 🧠 Temporal GAN for Anomaly Detection

Este projeto utiliza uma abordagem baseada em redes adversariais generativas (GANs) para detecção de anomalias em séries temporais de métricas da AWS, usando a base **NAB (Numenta Anomaly Benchmark)**.

![ganomaly](https://img.shields.io/badge/GANomaly-PyTorch-blue)


---

## 📊 Objetivo

Detectar **falhas contínuas**, **picos súbitos** ou **comportamentos anômalos** em métricas como o uso de CPU de instâncias EC2, sem depender de métodos estatísticos tradicionais como outliers ou desvio padrão.

A detecção é feita comparando janelas reais com janelas geradas por uma GAN, utilizando a diferença entre elas como score de anomalia.

---

## 🗃️ Base de Dados

**📁 Dataset**: [NAB - Numenta Anomaly Benchmark](https://github.com/numenta/NAB)
