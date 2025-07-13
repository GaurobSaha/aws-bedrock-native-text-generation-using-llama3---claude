"# aws-bedrock-native-text-generation-using-llama3---claude" 


This project demonstrates native text generation using AWS Bedrock's low-level runtime API. It provides clean, dependency-light Python scripts to invoke two industry-leading foundation models:

Meta LLaMA 3 70B Instruct

Anthropic Claude 3

The code sends raw text prompts formatted in each model’s native structure and handles both the request payload construction and response parsing directly via the boto3 client. It showcases how to:

Authenticate and call Bedrock Runtime API using boto3

Construct native prompt formats (e.g., <|begin_of_text|> tokens for LLaMA, structured messages for Claude)

Set inference parameters like temperature, max_tokens, etc.

Parse JSON responses and extract generated completions

Persist outputs to .txt files for downstream processing or audit

This implementation avoidsgives developers full control over prompt engineering and response handling for production or research use cases.


