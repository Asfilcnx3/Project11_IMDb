# Project11_IMDb

## Español
> Proyecto usando transformers con el modelo "bert-base-uncased" como tokenizador y modelo de clasificación principal, se usó el set de datos "stanfordnlp/imdb" para clasificar los sentimientos en categorías. 

## English
> Project using transformers with "bert-base-uncased" as tokenizer and classificator model, using the "stanfordnlp/imdb" dataset to classify the sentiments on 2 different categories (1 - 0)

## Descripción / Description
> - Es un proyecto para la comparación de formas de entrenamiento, usando el atributo .train como entrenamiento automático y "accelerate " como entrenamiento manual sobre el modelo "bert-base-uncased" para clasificación de sentimientos. 
> 
> - Se utilizó "transformers" como herramienta principal y el set de datos "stanfordnlp/imdb" que viene de `load_dataset from datasets`.
>
> - Se comparó las métricas "accuracy" y "f1" por ser una tarea de clasificación.
> 
> - Se Trabajó clasificando sentimientos de reseñas en un dataset de peliculas en inglés.
>  
> - Se entrenó a 5 épocas de entrenamiento totales.
> 
> - BatchSize de 8 datos usando "dataloader".
> 
> - Trabajamos con set de Entrenamiento, Validación y Prueba.

> -------------------

> - It´s a project to compare 2 different types of training, using the atribute ".train" as automatic training loop and "accelerate" as manual training loop in the model "bert-base-uncased" to sentimets classification.
> 
> - Using transformers as main tool and the "stanfordnlp/imdb" dataset that you can find on `load_dataset from datasets`.
>
> - The metrics "accuracy" and "f1" was used and compared as a classification task.
> 
> - Worked with "sentiment clasification" using a dataset from movie reviews in english.
> 
> - 5 total train epochs.
>
> - BatchSize = 8 using "dataloader"
>
> - Worked with train, valid and test split.

## Tecnologías usadas / Used Technologies
- Python (main)
- PyTorch
- Google Colab / Jupyter NoteBook
- Datasets (from HuggingFace)
- Transformers (from HuggingFace)
- Accelerate
- Evaluate (from HuggingFace)
- Matplotlib.pyplot
- Train (from HuggingFace)
- tqdm

## Final Results / Resultados Finales
On evaluation split / En el set de evaluación:

        Manual Model Test Set Results:
                             Accuracy: 0.921
                             F1 score: 0.921
                                 Loss: 1.164
        Trainer Model Test Set Results:
                              Accuracy: 0.916
                              F1 score: 0.916
                                  Loss: 0.597
