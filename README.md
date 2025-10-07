# TFM_Escritura-Creativa-con-IA
Trabajo Final de Maestria

Resumen
Este repositorio acompaña la tesis de máster “Evaluación de escritura creativa en español con modelos de lenguaje”. Reúne el pipeline completo: preparación del corpus, fine-tuning (GPT-2 en español), generación controlada por prompts, evaluación humana (coherencia, estilo, sorpresa, human-likeness), métricas automáticas sin referencia (Self-BLEU y baja repetición) y construcción de una métrica híbrida de creatividad. La infraestructura de experimentación se basa en Google Colab Pro (GPU A100), con almacenamiento persistente en Google Drive y exportación de resultados y figuras reproducibles.

Requisitos
Google Colab Pro (recomendado) o entorno local con GPU (>= 16 GB VRAM para pruebas; A100 para réplicas completas).
Python 3.10+

Librerías principales:
transformers>=4.40
datasets>=2.19
accelerate
sentencepiece
pandas
numpy
matplotlib
sacrebleu



