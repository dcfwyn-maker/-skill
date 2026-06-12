---
name: main-image-analysis-template
description: Use when analyzing ecommerce main images, product thumbnails, hero product images, competitor product images, or marketplace listing visuals. Produces a practical click-through-focused diagnosis, main-image structure, copy options, competitor comparison, revision checklist, A/B test ideas, and a reusable template for future products.
metadata:
  short-description: Analyze ecommerce main images
---

# Main Image Analysis Template

Use this skill when the user wants to analyze, improve, compare, or generate a reusable workflow for ecommerce main images. It applies to Taobao, Tmall, JD, Pinduoduo, Douyin ecommerce, Amazon, TikTok Shop, Temu, independent stores, and similar marketplaces.

## Inputs To Ask For Or Infer

Work with whatever the user provides. If key inputs are missing, make reasonable assumptions and label them.

Prefer these inputs:

- Product details: product name, category, price band, specs, materials, features, claimed benefits.
- Current main image: image file, screenshot, URL, or written description.
- Target marketplace and audience.
- Competitor images or competitor image descriptions.
- Buyer reviews, Q&A, customer service issues, or negative reviews.
- Business goal: improve click-through, improve conversion, launch a new product, test a bundle, emphasize price, or reposition the product.

If images are provided, inspect them directly when possible. If only text is provided, analyze from the text and say that visual judgments are inferred.

## Core Principle

Do not give generic aesthetic feedback like "more premium" or "optimize layout" unless it is translated into a concrete change. Treat the main image as a click entry, not an artwork.

Every analysis should answer:

1. What does the user see in the first second?
2. Is the product clear enough?
3. What concrete reason makes the user click?
4. How is this image different from competitor images?
5. What should the next version change?

## Output Structure

### 1. Product And User Judgment

Create a table:

| Item | Conclusion |
| --- | --- |
| Product type | |
| Target user | |
| Core usage scenario | |
| Main pain points | |
| Purchase concerns | |
| Strongest click reason | |

### 2. First-Second Information

Evaluate:

- Visual focus: product, person, text, scene, price, result, or proof.
- Product clarity: size, recognizability, cropping, angle, and contrast.
- Main selling point: whether one clear reason dominates.
- Information load: whether labels and text compete.
- Thumbnail readability: whether the image still works when small.

Use a table:

| Dimension | Current state | Problem | Recommendation |
| --- | --- | --- | --- |

### 3. Click Reason

Classify the current click reason into one or more types:

- Pain-point solution.
- Result promise.
- Trust proof.
- Scenario identification.
- Price or value.
- Bundle or convenience.

Then produce 10 short main-image headline options. Each should be specific, concrete, and short enough for a product thumbnail. For Chinese ecommerce, keep each option within about 10 Chinese characters unless the user asks otherwise.

### 4. Composition Structure

Judge which structure the image uses and whether it fits the product:

| Structure | Best for |
| --- | --- |
| Big product + one-line selling point | New products, low-awareness products, clear functional products |
| Product + 3 trust labels | Beauty, food, mother and baby, cleaning, daily goods |
| Pain scene + product solution | Cleaning, storage, small appliances, pet, office |
| Before/after comparison + result | Cleaning, organizing, skincare, fitness, repair |
| Multi-SKU or bundle display | Sets, gift boxes, consumables, stock-up items |
| User scenario + usage result | Wearables, home, outdoor, personal care, gifts |

Recommend one structure for the next version:

```text
Visual subject:
Main headline:
Support labels:
Background or scene:
Trust elements:
Avoid:
```

### 5. Competitor Comparison

If competitor images are available, compare them directly. If not, infer likely competitor patterns from the category and label them as assumptions.

| Comparison item | Our image | Competitor image | Opportunity |
| --- | --- | --- | --- |
| First visual focus | | | |
| Main selling point | | | |
| Product clarity | | | |
| Trust elements | | | |
| Scenario identification | | | |
| Differentiation | | | |

### 6. Next-Version Revision Checklist

Split recommendations into:

- Must change: changes that directly affect click-through or comprehension.
- Nice to improve: helpful but not fatal.
- Keep: current strengths that should not be lost.
- A/B tests: alternative directions worth testing.

Make each recommendation concrete enough for a designer or image-generation prompt.

### 7. Reusable Product Template

End with a reusable template for future products in the same category:

| Module | Template |
| --- | --- |
| Suitable category | |
| Suitable audience | |
| First-second selling-point formula | |
| Main-image structure | |
| Headline rule | |
| Label rule | |
| Trust elements | |
| Test directions | |

## Optional Score

When useful, score the image from 1 to 5 on each item:

- Product recognition.
- Product clarity.
- Selling-point specificity.
- Information hierarchy.
- Trust proof.
- Competitor differentiation.
- Actionability.

Interpretation:

- 30-35: ready for testing.
- 24-29: direction is usable; optimize selling point or structure.
- 18-23: unclear; create a new version.
- Below 18: restart positioning and structure.

## Style

- Be direct, practical, and specific.
- Prefer tables when comparing or diagnosing.
- Use short product-image copy, not long advertising copy.
- Avoid vague design adjectives unless paired with exact changes.
- If the user asks for image prompts, convert the final recommendation into prompt-ready instructions.
