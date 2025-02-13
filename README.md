# Estancia de Investigación: Modelado de Tópicos Shark Tank
## Autores: Delia Zaret Cárdenas Moreno - Daan Tonatiuh González Espinosa
## Objetivos:
 - Analizar la existencia y naturaleza de sesgos de género en el proceso de evaluación y financiamiento de startups en
el ecosistema de venture capital en México, examinando las interacciones entre inversionistas y emprendedores durante el
proceso de evaluación de los proyectos de emprendimiento (pitches).
 - Cuantificar las disparidades en montos de financiamiento y valuaciones asignadas entre startups lideradas por mujeres
y hombres, para determinar la existencia de una brecha de género estadísticamente significativa en el acceso a capital.
Este objetivo establece la base cuantitativa del estudio. Nos permite confirmar si existe una brecha de género medible
en términos de resultados financieros concretos. Este análisis inicial proporciona el contexto necesario para profundizar
en las causas y manifestaciones de estas disparidades.
 - Determinar si existe una correlación significativa entre el género del inversionista y la proporción de inversiones rea-
lizadas en startups fundadas por mujeres, evaluando patrones de asignación de capital entre inversionistas mexicanos.
Este objetivo examina uno de los posibles mecanismos detrás de la brecha identificada: la relación entre el género del
inversionista y sus decisiones de inversión. Este análisis correlacional nos ayuda a entender si los sesgos operan a nivel
de la composición demográfica de los inversionistas.
 - Analizar comparativamente el contenido, enfoque y complejidad de las preguntas formuladas por inversionistas a em-
prendedores y emprendedoras durante procesos de evaluación de los proyectos de emprendimiento, para identificar
potenciales sesgos en el escrutinio aplicado según el género del emprendedor. Este objetivo profundiza en los mecanis-
mos cualitativos mediante los cuales podrían manifestarse los sesgos, examinando las diferencias en el tipo de escrutinio
aplicado según el género del emprendedor.
 - dentificar y caracterizar las diferencias en los marcos de evaluación entre inversionistas hombres y mujeres mediante el
análisis del contenido y estructura de las preguntas formuladas durante sesiones de pitch. Este objetivo examina cómo
el género del inversionista influye en sus marcos conceptuales de evaluación, proporcionando una comprensión más
profunda de cómo los sesgos de género operan desde ambos lados de la decisión de inversión.

## Pasos del proyecto  

| Análisis | Código | Explicación |
|----------|------------|------------|
| **Análisis Exploratorio** | 0.EDA final.ipynb | Este código proporciona un análisis descriptivo de la base consolidada para conocer mejor a la población, dentro de la carpeta data se encuentra el archivo: Shark_tank_baseconsolidada.csv |
| **Tópicos respecto al género del inversionista (Segundo Enfoque)** | obtener_topicos_inversionista_segundo_enfoque.py | Dentro de la carpeta Modelado_topicos_segundo_enfoque correr el código para obtener las sintesis de los pitches así como los modelos LDA |
| **Tópicos respecto al género del emprendedor (Segundo Enfoque)** | obtener_topicos_emprendedor_segundo_enfoque.py | Dentro de la carpeta Modelado_topicos_segundo_enfoque |
| **Análisis** |  | Dentro de la carpeta  |                                              |

## **Demostración del proyecto**  

Al final del proyecto se evaluarán las siguientes hipótesis:  

- **H1**: El porcentaje de acuerdos logrados por emprendedores hombres es mayor que el alcanzado por emprendedoras mujeres.  
- **H2**: El monto de apoyo ofrecido será menor para las emprendedoras mujeres que para los hombres.  
- **H3**: La tasa de retención de la valuación será menor para las emprendedoras mujeres que para los hombres.  
- **H4**: La decisión de invertir de las mujeres inversionistas es independiente del género del emprendedor.  
- **H5**: Los criterios de evaluación de los proyectos que utilizan los inversionistas no son independientes del género del emprendedor.  
- **H6**: Los inversionistas evalúan a las mujeres emprendedoras con un enfoque de prevención y a los hombres con un enfoque de promoción.  
- **H7**: Los inversionistas formularán preguntas de índole operativa a las mujeres emprendedoras, mientras que los cuestionamientos serán de tipo estratégico para los hombres.  
- **H8**: Los criterios de inversión de las inversionistas mujeres serán diferentes de los considerados por los inversionistas hombres.  


## **Ligas de interés** 
- [Shap Documentation](https://shap.readthedocs.io/en/latest/)  
- [Balachandra et al. (2019) - Don’t pitch like a girl!](https://journals.sagepub.com/doi/10.1177/1042258717729910)  
- [Balachandra (2020) - How gender biases drive venture capital decision-making](https://www.emerald.com/insight/content/doi/10.1108/GM-09-2019-0158/full/html)  
- [Bapna & Ganco (2021) - Gender gaps in equity crowdfunding](https://pubsonline.informs.org/doi/10.1287/mnsc.2020.3730)  
- [Becker (1957) - The Economics of Discrimination](https://press.uchicago.edu/ucp/books/book/chicago/E/bo28503666.html)  
- [Benjamin & Margulis (2005) - Angel Capital: How to Raise Early-Stage Private Equity Financing](https://www.wiley.com/en-us/Angel+Capital%3A+How+to+Raise+Early+Stage+Private+Equity+Financing-p-9780471690613)  
- [Blei (2012) - Probabilistic Topic Models](https://dl.acm.org/doi/10.1145/2133806.2133826)  
- [Blei, Ng & Jordan (2003) - Latent Dirichlet Allocation](https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)  
- [Bordalo et al. (2016) - Stereotypes](https://academic.oup.com/qje/article/131/4/1753/2468875)  
- [Brooks et al. (2014) - Investors prefer entrepreneurial ventures pitched by attractive men](https://www.pnas.org/doi/10.1073/pnas.1321202111)  
- [Brush et al. (2014) - The Diana Project](https://www.babson.edu/media/babson/site-assets/content-assets/about/academics/centres-and-institutes/centres/blank-institute/diana-research/2014-diana-project-report.pdf)  
- [Brush, Greene & Welter (2020) - The Diana Project: A legacy for research on gender in entrepreneurship](https://www.emerald.com/insight/content/doi/10.1108/IJGE-12-2019-0199/full/html)  
- [Caliskan, Bryson & Narayanan (2017) - Semantics derived automatically from language corpora contain human-like biases](https://www.science.org/doi/10.1126/science.aal4230)  
- [Cassion et al. (2020) - Investors embrace gender diversity, not female CEOs](https://link.springer.com/chapter/10.1007/978-3-030-53956-6_9)  
- [Cassion et al. (2021) - Investors embrace gender diversity, not female CEOs (arXiv)](https://arxiv.org/abs/2101.12008)  
- [Chuang, Manning & Heer (2012) - Termite: Visualization Techniques for Assessing Textual Topic Models](https://ieeexplore.ieee.org/document/6467133)  
- [Devlin et al. (2019) - BERT: Pre-training of Deep Bidirectional Transformers](https://arxiv.org/abs/1810.04805)  
- [Eagly & Karau (2002) - Role congruity theory of prejudice toward female leaders](https://psycnet.apa.org/record/2002-14063-005)  
- [Eddleston & Powell (2008) - Gender identity in explaining sex differences in business owners’ career satisfier preferences](https://www.sciencedirect.com/science/article/pii/S0883902607000396)  
- [Färber & Klein (2021) - Are Investors Biased Against Women? (arXiv)](https://arxiv.org/abs/2112.00859)  
- [Kahneman & Tversky (1979) - Prospect theory: An analysis of decision under risk](https://www.jstor.org/stable/1914185)  
- [Tversky & Kahneman (1981) - The framing of decisions and the psychology of choice](https://www.science.org/doi/10.1126/science.7455683)  
