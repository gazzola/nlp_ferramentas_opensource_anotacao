# 🏷 Ferramentas _open-source_ de Anotação e Rotulagem de dados

[![maintained-by-zenml](https://user-images.githubusercontent.com/3348134/173032050-ad923313-f2ce-4583-b27a-afcaa8b355e2.png)](https://github.com/zenml-io/zenml)

Na [ZenML](https://github.com/zenml-io/zenml) acreditamos que fluxos de trabalho de **anotação** e **rotulagem** são parte central do ciclo de vida de machine learning. Como uma ferramenta open source, quisemos destacar e reconhecer a variedade de ferramentas disponíveis para tornar seus fluxos mais **centrados em dados**. Tivemos três critérios principais para decidir se uma ferramenta poderia entrar na lista:

* A ferramenta tem licença open source.
* A ferramenta é ativamente mantida.
* A ferramenta é funcional e adequada ao propósito.

Recebemos contribuições para esta lista; se você conhece alguma ferramenta que deixamos de fora ou se você próprio criou uma, crie um PR!

🔥 **Você usa essas ferramentas ou quer adicionar uma ao seu stack de MLOps?** Na ZenML, buscamos parcerias de design e colaboração para desenvolver integrações e fluxos em torno do uso de anotação dentro do ciclo de vida de MLOps. Se quiser saber mais, por favor [entre no nosso Slack](https://zenml.io/slack-invite/) e deixe uma mensagem!

## Conteúdo

* [Multimodal / Multidomínio](#multi-modal-multi-domain)
* [Texto](#text)
* [Imagens](#images)
* [Áudio](#audio)
* [Vídeo](#video)
* [Séries Temporais](#time-series)
* [Outros](#other)

# Multimodal / Multidomínio

| Nome                                                                                                        | Descrição                                                                                                                           | Licença  |
| ----------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [Acharya](https://github.com/astutic/Acharya)                                                               | Uma ferramenta de MLOps centrada em dados para seus projetos de Reconhecimento de Entidades Nomeadas                                | ?        |
| [Adala](https://github.com/HumanSignal/Adala)                                                               | Um framework de Agente de Dados (Rotulagem) Autônomo                                                                                | Apache-2 |
| [Anudesh](https://github.com/AI4Bharat/Anudesh)                                                             | Plataforma open source para anotar dados para grandes modelos de linguagem — em escala                                              | MIT      |
| [Classifai](https://github.com/CertifaiAI/classifai)                                                        | Uma plataforma open source abrangente de anotação de dados                                                                          | Apache-2 |
| [Computer Vision Annotation Tool (CVAT)](https://github.com/openvinotoolkit/cvat)                           | Ferramenta gratuita, online e interativa para anotação de vídeo e imagem para visão computacional                                   | MIT      |
| [Data Annotator for Machine Learning (DAML)](https://github.com/vmware/data-annotator-for-machine-learning) | Aplicativo que ajuda times de ML a facilitar a criação e o gerenciamento de anotações                                               | Apache-2 |
| [DataGym](https://github.com/datagym-ai/datagym-core)                                                       | Ferramenta open source de anotação e rotulagem para ativos de imagem e vídeo                                                        | MIT      |
| [Diffgram](https://github.com/diffgram/diffgram)                                                            | Dados de Treino (Rotulagem, Anotação, Workflow) para todos os tipos de dados (Imagem, Vídeo, 3D, Texto, Geo, Áudio, etc.) em escala | ELv2     |
| [Hover](https://github.com/phurwicz/hover)                                                                  | Explore e rotule em um “mapa” de dados brutos. Lida com texto, áudio e imagens                                                      | MIT      |
| [Label Studio](https://github.com/heartexlabs/label-studio)                                                 | Ferramenta de anotação e rotulagem multimodal com formato de saída padronizado                                                      | Apache-2 |
| [Pigeon](https://github.com/agermanidis/pigeon)                                                             | Widget simples para anotar rapidamente um conjunto de exemplos sem rótulo direto do seu Jupyter Notebook                            | Apache-2 |
| [QSL: Quick and Simple Labeler](https://github.com/faustomorales/qsl)                                       | Ferramenta rápida e simples para rotular imagens, vídeos e séries temporais, direto do Jupyter                                      | MIT      |
| [Shoonya](https://github.com/AI4Bharat/Shoonya)                                                             | Plataforma para anotar e rotular dados em escala                                                                                    | MIT      |
| [Tator](https://github.com/cvisionai/tator)                                                                 | Plataforma web de análise de vídeo                                                                                                  | AGPL-3   |
| [TornadoAi](https://github.com/slrbl/human-in-the-loop-machine-learning-tool-tornado)                       | Framework de machine learning com humano-no-loop                                                                                    | AGPL-3   |
| [Universal Data Tool](https://github.com/UniversalDataTool/universal-data-tool)                             | App web/desktop para editar e anotar imagens, texto, áudio, documentos e visualizar/editar dados nos padrões .udt.json e .udt.csv   | MIT      |
| [VGG Image Annotator (VIA)](https://gitlab.com/vgg/via)                                                     | Aplicativo autônomo de anotação de imagens empacotado como um único arquivo HTML (< 400 KB) que roda nos navegadores modernos       | BSD-2    |
| [VIAME](https://github.com/VIAME/VIAME)                                                                     | Análise de Vídeo e Imagem para Múltiplos Ambientes                                                                                  | Custom   |
| [Xtreme1](https://github.com/xtreme1-io/xtreme1)                                                            | Plataforma tudo-em-um de rotulagem/anotação para treinamento de dados multimodais; suporta nuvem de pontos LiDAR 3D, imagem e LLM   | Apache-2 |

# Texto

| Nome                                                                       | Descrição                                                                                                                           | Licença         |
| -------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| [Annotation Lab](https://nlp.johnsnowlabs.com/docs/en/alab/quickstart)     | Ferramenta de anotação em NLP incluída no `spark-nlp`                                                                               | Apache-2        |
| [bulk](https://github.com/koaning/bulk)                                    | Ferramenta rápida para desenvolvedores aplicarem rótulos em lote                                                                    | MIT             |
| [CoreNLP](https://github.com/stanfordnlp/CoreNLP)                          | Suíte Java de ferramentas centrais de NLP                                                                                           | GPL-3           |
| [DataQA](https://github.com/dataqa/nlp-labelling)                          | Plataforma de rotulagem para texto usando supervisão fraca                                                                          | GPL-3           |
| [doccano](https://github.com/doccano/doccano)                              | Ferramenta open source de anotação de texto que suporta classificação, rotulagem de sequência e tarefas seq2seq                     | MIT             |
| [FLAT - FoLiA Linguistic Annotation Tool](https://github.com/proycon/flat) | Ambiente web de anotação linguística baseado no formato FoLiA (XML)                                                                 | GPL-3           |
| [INCEpTION](https://github.com/inception-project/inception)                | Plataforma de anotação semântica com assistência inteligente e gestão de conhecimento                                               | Apache-2        |
| [knodle](https://github.com/knodle/knodle)                                 | Knodle (Framework de Aprendizado Profundo supervisionado por Conhecimento)                                                          | Apache-2        |
| [Label Sleuth](https://github.com/label-sleuth/label-sleuth)               | Sistema open source sem código para anotar texto e construir classificadores de texto                                               | Apache-2        |
| [Markup](https://github.com/samueldobbie/markup)                           | Ferramenta web de anotação de documentos, com GPT-4                                                                                 | Unknown         |
| [NER Annotator for Spacy](https://github.com/tecoholic/ner-annotator)      | Anotador NER para SpaCy para criar dados de treino com tags personalizadas                                                          | MIT             |
| [NPLM](https://github.com/BatsResearch/nplm)                               | Noisy Partial Label Model (NPLM)                                                                                                    | N/A             |
| [Potato](https://github.com/davidjurgens/potato)                           | Framework de anotação com 20+ templates, UI editável, controle de qualidade, gestão de dados e opção de pesquisa para crowdsourcing | PolyForm Shield |
| [refinery](https://github.com/code-kern-ai/refinery)                       | A escolha open source de cientistas de dados para escalar, avaliar e manter dados de linguagem natural                              | Apache-2        |
| [Slate](https://github.com/jkkummerfeld/slate)                             | Ferramenta de anotação super-leve para especialistas: rotule texto no terminal apenas com Python                                    | ISC             |
| [SMART](https://github.com/RTIInternational/SMART)                         | Ferramenta para construir conjuntos de treino rotulados para tarefas de ML supervisionado em NLP                                    | MIT             |
| [SpaCy annotator](https://github.com/ieriii/spacy-annotator)               | Anotador NER do SpaCy usando ipywidgets                                                                                             | N/A             |
| [Small-Text](https://github.com/webis-de/small-text)                       | Aprendizado Ativo para Classificação de Texto                                                                                       | MIT             |
| [Snorkel](https://github.com/snorkel-team/snorkel)                         | Construa e gerencie programaticamente dados de treino                                                                               | Apache-2        |
| [skweak](https://github.com/NorskRegnesentral/skweak)                      | skweak: supervisão fraca para NLP                                                                                                   | MIT             |
| [TALEN](https://github.com/CogComp/talen)                                  | Uma forma de fazer anotações para NER                                                                                               | Custom          |
| [Theme](https://github.com/Oxid15/theme)                                   | Ferramenta minimalista de rotulagem via CLI para classificação de texto                                                             | MIT             |
| [YEDDA](https://github.com/jiesutd/YEDDA)                                  | Ferramenta leve e colaborativa para anotação de spans de texto                                                                      | Apache-2        |
| [WeaSEL](https://github.com/autonlab/weasel)                               | WeaSEL: aprendizado de ponta a ponta com supervisão fraca                                                                           | Apache-2        |

# Imagens

| Nome                                                              | Descrição                                                                                                                                     | Licença  |
| ----------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [3D Slicer](https://www.slicer.org)                               | Visualização, processamento, segmentação, registro e análise de imagens/meshes 3D médicas, biomédicas e outras                                | BSD      |
| [Annotate Lab](https://github.com/sumn2u/annotate-lab)            | Simplificando a anotação de imagens                                                                                                           | MIT      |
| [Annotorious](https://github.com/recogito/annotorious)            | Biblioteca JavaScript para anotação de imagens                                                                                                | BSD-3    |
| [AnyLabeling](https://github.com/vietanhdev/anylabeling)          | Rotulagem de imagens com assistência de IA (YOLO, Segment Anything, MobileSAM)                                                                | GPL-3    |
| [autodistill](https://github.com/autodistill/autodistill)         | Do conjunto de imagens à inferência sem rotulagem manual (use modelos fundacionais para treinar modelos supervisionados)                      | Apache-2 |
| [bbox-visualizer](https://github.com/shoumikchow/bbox-visualizer) | Facilita desenhar e rotular caixas delimitadoras                                                                                              | MIT      |
| [Bounding Box Editor](https://github.com/mfl28/BoundingBoxEditor) | Aplicativo desktop JavaFX para criar anotações de objetos em imagens com bounding boxes                                                       | GPL-3    |
| [CATMAID](https://github.com/catmaid/CATMAID)                     | Toolkit colaborativo de anotação para grandes quantidades de dados de imagem                                                                  | GPL-3    |
| [COCO Annotator](https://github.com/jsbroks/coco-annotator)       | Ferramenta web de segmentação de imagens para detecção, localização e keypoints                                                               | MIT      |
| [DeepLabel](https://github.com/jveitchmichaelis/deeplabel)        | Ferramenta desktop multiplataforma de anotação de imagens para ML                                                                             | MIT      |
| [Etichetta](https://github.com/trikko/etichetta)                  | Um anotador para YOLO, feito para pessoas                                                                                                     | MIT      |
| [ilastik](https://github.com/ilastik/ilastik)                     | Segmente, classifique, rastreie e conte células ou outros dados experimentais                                                                 | Custom   |
| [ImageTagger](https://github.com/bit-bots/imagetagger)            | Plataforma online open source para rotulagem colaborativa de imagens                                                                          | MIT      |
| [imglab](https://github.com/NaturalIntelligence/imglab)           | Ferramenta web para rotular imagens para detectores do dlib ou outros                                                                         | MIT      |
| [KNOSSOS](https://github.com/knossos-project/knossos)             | Ferramenta para visualização e anotação de dados 3D, criada para reconstrução rápida de morfologia e conectividade neural                     | GPL-2    |
| [labelCloud](https://github.com/ch-sa/labelCloud)                 | Ferramenta leve para rotular caixas 3D em nuvens de pontos                                                                                    | GPL-3    |
| [LabelFlow](https://github.com/labelflow/labelflow)               | Plataforma aberta para rotulagem de imagens                                                                                                   | Custom   |
| [labelme](https://github.com/wkentaro/labelme)                    | Anotação poligonal de imagens em Python (polígono, retângulo, círculo, linha, ponto e flag em nível de imagem)                                | Custom   |
| [LabelImg](https://github.com/tzutalin/labelImg)                  | Ferramenta gráfica para anotar e rotular caixas delimitadoras em imagens                                                                      | MIT      |
| [LOST](https://github.com/l3p-cv/lost)                            | Framework web flexível para anotação semi-automática de imagens                                                                               | MIT      |
| [Make Sense](https://github.com/SkalskiP/make-sense)              | Ferramenta online gratuita para rotular fotos                                                                                                 | GPL-3    |
| [MyVision](https://github.com/OvidijusParsiunas/myvision)         | Ferramenta para geração de dados de treino de visão computacional                                                                             | GPL-3    |
| [OHIF Medical Imaging Viewer](https://github.com/OHIF/Viewers)    | Visualizador DICOM “zero-footprint” e rastreador de lesões específico para oncologia                                                          | MIT      |
| [OpenLabeler](https://github.com/kinhong/OpenLabeler)             | Aplicativo desktop open source para anotar objetos para aplicações de IA                                                                      | Apache-2 |
| [Pixano](https://github.com/pixano/pixano-app)                    | Ferramenta web de “smart-annotation” para aplicações de visão computacional                                                                   | CeCILL-C |
| [Scalabel](https://github.com/scalabel/scalabel)                  | Ferramenta web de anotação visual, com suporte a rotulagem 2D e 3D                                                                            | Apache-2 |
| [webKnossos](https://github.com/scalableminds/webknossos)         | Ferramenta totalmente em nuvem/navegador para anotação 3D distribuída em análises de grande escala de conectômica por luz/elétron-microscopia | AGPL-3   |
| [Yolo\_Label](https://github.com/developer0hye/Yolo_Label)        | GUI para marcar caixas delimitadoras em imagens para treinar YOLO                                                                             | MIT      |

# Vídeo

| Nome                                                                | Descrição                                                                                      | Licença  |
| ------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | -------- |
| [Chitralekha](https://github.com/AI4Bharat/Chitralekha)             | Ferramenta open source de “transcreation” de vídeo                                             | MIT      |
| [DIVE](https://github.com/Kitware/dive)                             | Ferramentas de anotação e análise de mídia para web e desktop                                  | Apache-2 |
| [UltimateLabeling](https://github.com/alexandre01/UltimateLabeling) | GUI multipropósito para rotulagem de vídeo em Python com detector e rastreador SOTA integrados | MIT      |

# Áudio

| Nome                                                        | Descrição                                                                 | Licença |
| ----------------------------------------------------------- | ------------------------------------------------------------------------- | ------- |
| [aubio](https://aubio.org)                                  | Biblioteca para análise de áudio e música                                 | GPL-3   |
| [audino](https://github.com/midas-research/audino)          | Ferramenta open source de anotação de áudio                               | MIT     |
| [Praat](https://github.com/praat/praat)                     | Ferramenta de anotação para análise fonética                              | GPL-3   |
| [Peaks.js](https://github.com/bbc/peaks.js)                 | Componente de UI em JavaScript para interação com formas de onda de áudio | LGPL-3  |
| [Wavesurfer.js](https://github.com/katspaugh/wavesurfer.js) | Forma de onda navegável construída sobre Web Audio e Canvas               | BSD-3   |

# Séries Temporais

| Nome                                       | Descrição                                            | Licença |
| ------------------------------------------ | ---------------------------------------------------- | ------- |
| [sktime](https://github.com/sktime/sktime) | Framework para machine learning com séries temporais | BSD-3   |

# Outros

| Nome                                                                     | Descrição                                                                                                                                     | Licença  |
| ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| [Compose](https://github.com/alteryx/compose)                            | Engenharia de predição automatizada. Permite estruturar problemas de predição e gerar rótulos para aprendizagem supervisionada com facilidade | BSD-3    |
| [Encord Active](https://github.com/encord-team/encord-active/)           | Toolkit para testar, validar e avaliar modelos; revelar, curar e priorizar os dados mais valiosos para rotulagem                              | Apache-2 |
| [Label App](https://github.com/javserjod/label-app)                      | Aplicativo para auxiliar na edição manual, visualização e rotulagem de conjuntos de dados de porte moderado                                   | Apache-2 |
| [NeuroTrALE](https://github.com/mit-ll/NeuroTrALE-data-manager)          | Software de anotação para mapeamento cerebral, com suporte a imagem e anotação 3D                                                             | BSD-2    |
| [OpenCRAVAT](https://github.com/KarchinLab/open-cravat)                  | Ferramenta modular de anotação para variantes genômicas                                                                                       | MIT      |
| [PatchSorter](https://github.com/choosehappy/PatchSorter)                | Ferramenta open source de patologia digital para rotulagem de objetos histológicos                                                            | BSD-3    |
| [Personal Cancer Genome Reporter (PCGR)](https://github.com/sigven/pcgr) | Pacote de software standalone para traduzir genomas tumorais individuais para medicina de precisão do câncer                                  | MIT      |
| [Quepid](https://github.com/o19s/quepid)                                 | Colete julgamentos humanos (avaliações explícitas) para qualidade de busca. Também é um espaço seguro para brincar com seu algoritmo de busca | Apache-2 |

# Agradecimentos

Agradecimentos aos criadores destes
[repositórios](https://github.com/jsbroks/awesome-dataset-tools),
[destes outros](https://github.com/doccano/awesome-annotation-tools)
e [deste aqui](https://github.com/taivop/awesome-data-annotation) (e [também deste](https://github.com/heartexlabs/awesome-data-labeling)!) por nos colocarem no caminho de criar o nosso próprio. Usei esses esforços como ponto de partida no meu panorama do espaço antes de adicionar, atualizar e podar de acordo com os critérios de open source e outros especificados acima.
