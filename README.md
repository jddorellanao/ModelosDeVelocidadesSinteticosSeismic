# SyntheticVelocityModels
Este repositorio se crea con la finalidad de mostrar y obtener unos de los modelos de velocidades, 2D y 3D, con mayor uso en sísmica de exploración. 

En las carpetas que llevan por título el nombre del modelo se tienen los archivos originales y los archivos en formato `.npy`

El cuaderno de trabajo P_2DSyntheticModelsToNumpy consiste en la obtención de tres modelos 2D:
- BP 2004: obtenido del sitio web de la [SEG](https://wiki.seg.org/wiki/2004_BP_velocity_estimation_benchmark_model) denominado modelo exacto. Se puede obtener el archivo gz [aqui](http://s3.amazonaws.com/open.source.geoscience/open_data/bpvelanal2004/vel_z6.25m_x12.5m_exact.segy.gz)
- Marmousi2 (Vp): modificación del modelo Marmousi. Se puede obtener el modelo en formato `.mat` [aquí](https://drive.google.com/drive/folders/19Sur5hdEB9TpZvmIgBpUqkF_QzGiU96i?usp=sharing). En este caso, se utilizo la versión 'pequeña del modelo'. Estos datos se utilizaron en una inversión sísmica de impedancia acústica, [repo](https://github.com/rafalunelli/SeismicInversion_WGAN-GP)
- SEAM N23900 (Vp): obtenido del sitio web de la [SEG](https://wiki.seg.org/wiki/Elastic_2DEW_Classic). El modelo usado es el de la velocidad de la onda P, se puede obtener [aquí](https://drive.google.com/file/d/0B2YKn_VsUkhNalJOWk9naV9MZXc/view?resourcekey=0-4VOHs6uRo0juNxLJThy9Cw).
