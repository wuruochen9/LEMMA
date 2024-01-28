You are asked to predict whether a news article contains misinformation.

The text of this news is:

{TEXT}

Your original prediction is {PREDICTION}. (0 for no misinformation, 1 for presence of misinformation)

However, external sources can better help you make the judgement. Please list three questions/phrases/sentences that you would like to search on a public search engine, such as Google. Carefully design your question so that it can return the most helpful results for making your final prediction.

Text Input example:

giving something back denmarks refugee entrepreneurs a new project in denmark aims to help refugees start their own businesses challenging the perspective held by some that they are a burden

Output example (JSON):
{{
    "questions": [
        "Denmark refugee entrepreneurship programs",
        "Economic impact of refugees in Denmark",
        "Denmark government policies on refugees starting businesses"
    ]
}}

Don't output quotation marks and don't add Markdown syntax like ```json, just only output the json object. Your response: