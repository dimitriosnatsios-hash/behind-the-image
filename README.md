# Behind the Image

Building AI course project

## Summary

Behind the Image is an AI-based tool that aims to increase transparency in fashion imagery. It analyses fashion images to identify possible AI-generated or AI-modified content and provides users with a simple transparency label.

## Background

AI-generated images are becoming increasingly common in fashion. Brands can now create models, campaigns, locations and entire visual worlds without producing them physically.

This creates new creative possibilities, but it also raises questions about transparency. When we see a fashion image online, it can be difficult to know whether we are looking at a photograph, an AI-generated image, or a combination of both.

This also affects the creative work behind fashion imagery. Photographers, models, stylists, make-up artists, set designers and other professionals may traditionally be involved in producing a campaign. When AI is used, some of this human work can become invisible or may not have existed at all.

My background is in fashion, styling and visual communication, and I am interested in how AI is changing the way fashion images are produced and understood. My motivation for this project is not to argue against AI-generated imagery, but to explore how AI itself could be used to create more transparency around its use.

## How is it used?

A user could upload a fashion image or provide an image from an online fashion campaign.

Behind the Image would analyse the image and estimate whether it contains signs of AI generation or significant AI modification.

The result could be presented through a simple transparency label, for example:

**AI involvement detected**

*This image may contain AI-generated or AI-modified elements.*

The tool could be useful for consumers, journalists, researchers and people working within the fashion industry. Fashion brands could also use the system voluntarily to provide more information about how their visual content was produced.

The purpose would not be to decide whether an image is "good" or "bad", but to give the viewer more information about what they are looking at.

## Data sources and AI methods

The project would require a dataset containing different types of fashion imagery, including:

* traditional fashion photography
* fully AI-generated fashion images
* photographs modified using generative AI
* images combining photographed and synthetic elements

A supervised machine learning model could be trained using images that have already been labelled according to how they were produced.

Computer vision and image classification techniques could then be used to identify patterns associated with AI-generated content.

Instead of producing only a binary result such as "AI" or "not AI", the system could provide a probability score. This is important because AI detection is not always certain.

Metadata could also be used when available. Information about the origin and editing history of an image could complement the visual analysis.

## Challenges

Behind the Image would not be able to determine with complete certainty whether every image was generated or modified using AI.

Generative AI develops quickly, and newer systems can produce increasingly realistic images. A detection system trained on existing images could therefore become less accurate when new technologies appear.

There is also a risk of false positives. A real photograph could potentially be classified as AI-generated, while a sophisticated AI-generated image could remain undetected.

Another limitation is that detecting AI does not explain the entire production process. An image may involve both human creative work and AI tools. The distinction between "human-made" and "AI-made" is therefore not always simple.

The project would also need to consider copyright, privacy, bias in training data and the rights of the creators whose images are included in the dataset.

For these reasons, the tool should provide information and probabilities rather than claim to establish an absolute truth about an image.

## What next?

The project could eventually develop beyond simple image detection.

A future version could provide more detailed information about different kinds of AI involvement, such as whether the background, model, clothing or other elements appear to have been generated or modified.

Another development could be a browser extension that displays transparency information while users browse fashion websites or social media.

The project could also explore a voluntary transparency system for fashion brands. Instead of relying only on AI detection, brands could provide information about how their images were created.

In the longer term, Behind the Image could contribute to a broader discussion about transparency, authorship and human creative labour in the age of generative AI.

## Acknowledgments

This project was developed as part of the Building AI course by Reaktor Innovations and the University of Helsinki.

The idea is inspired by my own professional and academic interest in fashion imagery, visual communication, artificial intelligence, authenticity and creative labour.

No external code, images or datasets are currently included in this project.
