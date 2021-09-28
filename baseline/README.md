# Описание
Это бенчмарк скрипт для хакатона от Раййфайзенбанка по оценке коммерческой недвижимости

## Вариант с requirements.txt
<ol>
    <li> убедиться, что у вас стоит python3.6 или выше </li>
    <li> установить зависимости:
    
    pip install -r requirements.txt 
</li>
    <li> запустить обучение

    python3 train.py --train_data <path_to_train_data> --model_path <path_to_pickle_ml_model>
</li>
    <li> запустить предикт
    
    python3 predict.py --model_path <path_to_pickled_model> --test_data <path_to_test_data> --output <path_to_output_csv_file>
</li>
</ol>
