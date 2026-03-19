# Musicoterap.IA: Prova de Conceito (PoC)

Este repositório contém a documentação técnica e o código-fonte (R/Python) referente à Prova de Conceito do sistema **Musicoterap.IA**, submetido à Chamada FAPEMIG 01/2026 (Demanda Universal - Categoria B).

## 🚀 Objetivo
Validar a predição automatizada do **Fator Geral de Interatividade (Fator G)** em sessões de Musicoterapia para Transtornos do Neurodesenvolvimento (TND), integrando modelos de fundação de áudio e psicometria de padrão-ouro.

## 📊 Principais Resultados
- **R² = 0,827** na predição de interatividade para o Paciente A (Autismo).
- **Homologia Estrutural (ρ = 0,54)** entre a percepção humana e o modelo MERT.
- Identificação de pontos cegos na generalização (NMT vs NR), justificando a necessidade de expansão multimodal.

## 🛠️ Stack Tecnológica
- **Audio Embeddings:** MERT (Large-Scale Self-supervised Training).
- **MIR Features:** Librosa (Python) / TuneR (R).
- **Modelagem:** Random Forest, Elastic Net, Conditional Inference Trees (ctree).
- **Ground Truth:** Escalas Nordoff-Robbins validadas (André, 2021).

## 👥 Equipe
- **Coordenação:** Dr. Frederico Pedrosa (UFMG - CEGeME)
- **Subcoordenação:** Dra. Aline André (UFMG - Laboratório de Musicoterapia)
- **Colaboração:** Dra. Marina Freire (UFMG / New York University)
