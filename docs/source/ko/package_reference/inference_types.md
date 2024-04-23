
<!--⚠️ Note that this file is in Markdown but contain specific syntax for our doc-builder (similar to MDX) that may not be
rendered properly in your Markdown viewer.
-->
<!--⚠️ Note that this file is auto-generated by `utils/generate_inference_types.py`. Do not modify it manually.-->


# 추론 타입[[inference-types]]

이 페이지에는 Hugging Face Hub에서 지원하는 타입(예: 데이터 클래스)이 나열되어 있습니다.
각 작업은 JSON 스키마를 사용하여 지정되며, 이러한 스키마에 의해서 타입이 생성됩니다. 이때 Python 요구 사항으로 인해 일부 사용자 정의가 있을 수 있습니다.
 
각 작업의 JSON 스키마를 확인하려면 [@huggingface.js/tasks](https://github.com/huggingface/huggingface.js/tree/main/packages/tasks/src/tasks)를 확인하세요.

라이브러리에서 이 부분은 아직 개발 중이며, 향후 릴리즈에서 개선될 예정입니다.



## audio_classification[[huggingface_hub.AudioClassificationInput]]

[[autodoc]] huggingface_hub.AudioClassificationInput

[[autodoc]] huggingface_hub.AudioClassificationOutputElement

[[autodoc]] huggingface_hub.AudioClassificationParameters



## audio_to_audio[[huggingface_hub.AudioToAudioInput]]

[[autodoc]] huggingface_hub.AudioToAudioInput

[[autodoc]] huggingface_hub.AudioToAudioOutputElement



## automatic_speech_recognition[[huggingface_hub.AutomaticSpeechRecognitionGenerationParameters]]

[[autodoc]] huggingface_hub.AutomaticSpeechRecognitionGenerationParameters

[[autodoc]] huggingface_hub.AutomaticSpeechRecognitionInput

[[autodoc]] huggingface_hub.AutomaticSpeechRecognitionOutput

[[autodoc]] huggingface_hub.AutomaticSpeechRecognitionOutputChunk

[[autodoc]] huggingface_hub.AutomaticSpeechRecognitionParameters



## chat_completion[[huggingface_hub.ChatCompletionInput]]

[[autodoc]] huggingface_hub.ChatCompletionInput

[[autodoc]] huggingface_hub.ChatCompletionInputMessage

[[autodoc]] huggingface_hub.ChatCompletionOutput

[[autodoc]] huggingface_hub.ChatCompletionOutputChoice

[[autodoc]] huggingface_hub.ChatCompletionOutputChoiceMessage

[[autodoc]] huggingface_hub.ChatCompletionStreamOutput

[[autodoc]] huggingface_hub.ChatCompletionStreamOutputChoice

[[autodoc]] huggingface_hub.ChatCompletionStreamOutputDelta



## depth_estimation[[huggingface_hub.DepthEstimationInput]]

[[autodoc]] huggingface_hub.DepthEstimationInput

[[autodoc]] huggingface_hub.DepthEstimationOutput



## document_question_answering[[huggingface_hub.DocumentQuestionAnsweringInput]]

[[autodoc]] huggingface_hub.DocumentQuestionAnsweringInput

[[autodoc]] huggingface_hub.DocumentQuestionAnsweringInputData

[[autodoc]] huggingface_hub.DocumentQuestionAnsweringOutputElement

[[autodoc]] huggingface_hub.DocumentQuestionAnsweringParameters



## feature_extraction[[huggingface_hub.FeatureExtractionInput]]

[[autodoc]] huggingface_hub.FeatureExtractionInput



## fill_mask[[huggingface_hub.FillMaskInput]]

[[autodoc]] huggingface_hub.FillMaskInput

[[autodoc]] huggingface_hub.FillMaskOutputElement

[[autodoc]] huggingface_hub.FillMaskParameters



## image_classification[[huggingface_hub.ImageClassificationInput]]

[[autodoc]] huggingface_hub.ImageClassificationInput

[[autodoc]] huggingface_hub.ImageClassificationOutputElement

[[autodoc]] huggingface_hub.ImageClassificationParameters



## image_segmentation[[huggingface_hub.ImageSegmentationInput]]

[[autodoc]] huggingface_hub.ImageSegmentationInput

[[autodoc]] huggingface_hub.ImageSegmentationOutputElement

[[autodoc]] huggingface_hub.ImageSegmentationParameters



## image_to_image[[huggingface_hub.ImageToImageInput]]

[[autodoc]] huggingface_hub.ImageToImageInput

[[autodoc]] huggingface_hub.ImageToImageOutput

[[autodoc]] huggingface_hub.ImageToImageParameters

[[autodoc]] huggingface_hub.ImageToImageTargetSize



## image_to_text[[huggingface_hub.ImageToTextGenerationParameters]]

[[autodoc]] huggingface_hub.ImageToTextGenerationParameters

[[autodoc]] huggingface_hub.ImageToTextInput

[[autodoc]] huggingface_hub.ImageToTextOutput

[[autodoc]] huggingface_hub.ImageToTextParameters



## object_detection[[huggingface_hub.ObjectDetectionBoundingBox]]

[[autodoc]] huggingface_hub.ObjectDetectionBoundingBox

[[autodoc]] huggingface_hub.ObjectDetectionInput

[[autodoc]] huggingface_hub.ObjectDetectionOutputElement

[[autodoc]] huggingface_hub.ObjectDetectionParameters



## question_answering[[huggingface_hub.QuestionAnsweringInput]]

[[autodoc]] huggingface_hub.QuestionAnsweringInput

[[autodoc]] huggingface_hub.QuestionAnsweringInputData

[[autodoc]] huggingface_hub.QuestionAnsweringOutputElement

[[autodoc]] huggingface_hub.QuestionAnsweringParameters



## sentence_similarity[[huggingface_hub.SentenceSimilarityInput]]

[[autodoc]] huggingface_hub.SentenceSimilarityInput

[[autodoc]] huggingface_hub.SentenceSimilarityInputData



## summarization[[huggingface_hub.SummarizationGenerationParameters]]

[[autodoc]] huggingface_hub.SummarizationGenerationParameters

[[autodoc]] huggingface_hub.SummarizationInput

[[autodoc]] huggingface_hub.SummarizationOutput



## table_question_answering[[huggingface_hub.TableQuestionAnsweringInput]]

[[autodoc]] huggingface_hub.TableQuestionAnsweringInput

[[autodoc]] huggingface_hub.TableQuestionAnsweringInputData

[[autodoc]] huggingface_hub.TableQuestionAnsweringOutputElement



## text2text_generation[[huggingface_hub.Text2TextGenerationInput]]

[[autodoc]] huggingface_hub.Text2TextGenerationInput

[[autodoc]] huggingface_hub.Text2TextGenerationOutput

[[autodoc]] huggingface_hub.Text2TextGenerationParameters



## text_classification[[huggingface_hub.TextClassificationInput]]

[[autodoc]] huggingface_hub.TextClassificationInput

[[autodoc]] huggingface_hub.TextClassificationOutputElement

[[autodoc]] huggingface_hub.TextClassificationParameters



## text_generation[[huggingface_hub.TextGenerationInput]]

[[autodoc]] huggingface_hub.TextGenerationInput

[[autodoc]] huggingface_hub.TextGenerationOutput

[[autodoc]] huggingface_hub.TextGenerationOutputDetails

[[autodoc]] huggingface_hub.TextGenerationOutputSequenceDetails

[[autodoc]] huggingface_hub.TextGenerationOutputToken

[[autodoc]] huggingface_hub.TextGenerationParameters

[[autodoc]] huggingface_hub.TextGenerationPrefillToken

[[autodoc]] huggingface_hub.TextGenerationStreamDetails

[[autodoc]] huggingface_hub.TextGenerationStreamOutput



## text_to_audio[[huggingface_hub.TextToAudioGenerationParameters]]

[[autodoc]] huggingface_hub.TextToAudioGenerationParameters

[[autodoc]] huggingface_hub.TextToAudioInput

[[autodoc]] huggingface_hub.TextToAudioOutput

[[autodoc]] huggingface_hub.TextToAudioParameters



## text_to_image[[huggingface_hub.TextToImageInput]]

[[autodoc]] huggingface_hub.TextToImageInput

[[autodoc]] huggingface_hub.TextToImageOutput

[[autodoc]] huggingface_hub.TextToImageParameters

[[autodoc]] huggingface_hub.TextToImageTargetSize



## token_classification[[huggingface_hub.TokenClassificationInput]]

[[autodoc]] huggingface_hub.TokenClassificationInput

[[autodoc]] huggingface_hub.TokenClassificationOutputElement

[[autodoc]] huggingface_hub.TokenClassificationParameters



## translation[[huggingface_hub.TranslationGenerationParameters]]

[[autodoc]] huggingface_hub.TranslationGenerationParameters

[[autodoc]] huggingface_hub.TranslationInput

[[autodoc]] huggingface_hub.TranslationOutput



## video_classification[[huggingface_hub.VideoClassificationInput]]

[[autodoc]] huggingface_hub.VideoClassificationInput

[[autodoc]] huggingface_hub.VideoClassificationOutputElement

[[autodoc]] huggingface_hub.VideoClassificationParameters



## visual_question_answering[[huggingface_hub.VisualQuestionAnsweringInput]]

[[autodoc]] huggingface_hub.VisualQuestionAnsweringInput

[[autodoc]] huggingface_hub.VisualQuestionAnsweringInputData

[[autodoc]] huggingface_hub.VisualQuestionAnsweringOutputElement

[[autodoc]] huggingface_hub.VisualQuestionAnsweringParameters



## zero_shot_classification[[huggingface_hub.ZeroShotClassificationInput]]

[[autodoc]] huggingface_hub.ZeroShotClassificationInput

[[autodoc]] huggingface_hub.ZeroShotClassificationInputData

[[autodoc]] huggingface_hub.ZeroShotClassificationOutputElement

[[autodoc]] huggingface_hub.ZeroShotClassificationParameters



## zero_shot_image_classification[[huggingface_hub.ZeroShotImageClassificationInput]]

[[autodoc]] huggingface_hub.ZeroShotImageClassificationInput

[[autodoc]] huggingface_hub.ZeroShotImageClassificationInputData

[[autodoc]] huggingface_hub.ZeroShotImageClassificationOutputElement

[[autodoc]] huggingface_hub.ZeroShotImageClassificationParameters



## zero_shot_object_detection[[huggingface_hub.ZeroShotObjectDetectionBoundingBox]]

[[autodoc]] huggingface_hub.ZeroShotObjectDetectionBoundingBox

[[autodoc]] huggingface_hub.ZeroShotObjectDetectionInput

[[autodoc]] huggingface_hub.ZeroShotObjectDetectionInputData

[[autodoc]] huggingface_hub.ZeroShotObjectDetectionOutputElement

