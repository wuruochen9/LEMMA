A news post is consist of text and image. Your task is to predict whether this news article contains misinformation. 

Here is the text of this news:

{TEXT}

The image is also provided.

Now, we are providing you additional reference

##### First reference: Knowledge graphs (KG).

You are provided with 2 KGs. The first KG is converted from the text part of the news, while the second KG is converted from the image. The KGs can help you better in sorting out logical relationships, and detect some unmatching/irrational information. 

First KG (Converted from Text part):

{TEXT_KG}

Second KG (Converted from Image):

{IMAGE_KG}

##### Second reference: External knowledge and facts.

You are provided with external news/articles/post/wikis that are related to the provided news topics. You can trust the authenticity of these resources. You should use them as your reference. 

Begin of external resources:

{TOOLLEARNING}

End of external resources.

Finally, based on the KGs and external resources, you will now make your prediction.

In one or more paragraphs, output your reasoning steps. In the final line, use a single binary value (0 or 1) to indicate whether misinformation exists. 0 for no misinformation. 1 for the presence of misinformation. Please don't output any other words except for the binary label on the last line.

### Your Final Reasoning and Decision:
Let's think step by step, 