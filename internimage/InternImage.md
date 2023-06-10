# InternImage: Exploring Large-Scale Vision Foundation Models with

## Ключевые особенности

* Сверточная сеть, в основанная на деформируемых свертках (deformable convolutions), котороя позиционируется как большая фундаментальная модель для компьютерного зрения по аналогии с большими языковыми моделями (LLM);
* Backbone (каркас) InternImage может быть использован для задач классификации, детекции, сегментации и других задач, нужно только присоединить нужную "голову";
* Такие универсальные модели выкатывались и раньше, однако отличие данной модели в количестве параметров - более 1 млрд и 400 млн. обучающих примеров;
* Результаты сопоставимы с трансформерами. Очень хороший результат в детекции на COCO датасете - 65 mAP;


> While these results suggest that CNNs are inferior to ViTs in the era of massive parameters and data, we argue that **CNN-based foundation models can also achieve comparable or even better performance than ViTs** when equipped with similar operator-/architecture-level designs, scaling-up parameters, and massive data.
