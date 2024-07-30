# Model endpoint compatibility
## Endpoint	                    ## Latest models
/v1/assistants	                All GPT-4 and GPT-3.5 Turbo models. The retrieval tool requires gpt-4-turbo-preview (and subsequent dated model releases) or gpt-3.5-turbo-1106 (and subsequent versions).
/v1/audio/transcriptions	    whisper-1
/v1/audio/translations	        whisper-1
/v1/audio/speech	            tts-1, tts-1-hd
/v1/chat/completions	        gpt-4 and dated model releases, gpt-4-turbo-preview and dated model releases, gpt-3.5-turbo and dated model releases, fine-tuned versions of gpt-3.5-turbo
/v1/embeddings	                text-embedding-3-small, text-embedding-3-large, text-embedding-ada-002
/v1/fine_tuning/jobs	        gpt-3.5-turbo, babbage-002, davinci-002
/v1/moderations	                text-moderation-stable, text-moderation-latest
/v1/images/generations	        dall-e-2, dall-e-3

# Model usage
Only these models can be used in UstadAI project.

## Allowed models
gpt-4o
gpt-4o-mini
text-embedding-3-large
text-embedding-3-small
whisper-1
tts-1
tts-1-hd
gpt-4-turbo-preview
gpt-4-turbo
gpt-3.5-turbo
dall-e-2
dall-e-3

