## Complimenting Deficient Bug Reports With Missing Information Leveraging Neural Text Generation

### Author
Usmi Mukherjee

### University 
Dalhousie University

### Year
2023

#### Abstract
Software bug reports often lack crucial information (e.g., steps to reproduce, expected behaviour), which makes bug resolution challenging. A recent study found that 78% of bug reports from open-source projects (e.g., Eclipse) contain less than 100 words each and thus require the developers to spend more time on bug resolution. According to an existing survey, 77% of 327 professional developers from major technology companies (e.g., Google, Meta) consider missing information a major problem and emphasize complementing them with useful information (e.g., environment configuration). In this thesis, we propose and evaluate two novel approaches that complement deficient bug reports with relevant information using Generative AI. In our first study, we propose --- BugMentor --- a novel approach that combines structured information retrieval and neural text generation (e.g., CodeT5) to generate appropriate answers to the follow-up questions from bug reports. Our approach identifies past, relevant bug reports to a given bug report, constructs the context and then leverages it to generate the answers. According to our evaluation, BugMentor generates good answers and outperforms three existing baselines significantly in terms of four appropriate metrics (e.g., BLEU, Semantic Similarity). We also conduct a developer study involving 10 participants where BugMentor’s answers were found to be more accurate, precise, concise and useful. In our second study, we propose --- BugEnricher --- a novel approach that enriches bug reports with meaningful explanations using neural text generation. We fine-tuned the T5 model on software-specific vocabulary (e.g., Stack Overflow tags) to generate explanations against software-specific terms and jargon, which has the potential to enrich a bug report. Our evaluation using three performance metrics shows that BugEnricher generates understandable to good explanations according to Google’s standards and outperforms two baselines from the literature. We also conduct a case study to demonstrate the benefit of our bug report enhancement and found that it was able to improve an existing technique in detecting textually dissimilar duplicate bug reports, which has been reported as a major challenge. Given the empirical evidence above, our approaches have strong potential to support bug resolution and bug report management.


URI : http://hdl.handle.net/10222/83339

Slide Deck : https://speakerdeck.com/usmimukherjee/masters-thesis-usmi-mukherjee
