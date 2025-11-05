# 🎨✨ Do It Yourself (DIY): Modifying Images for Poems in a Zero-Shot Setting Using Weighted Prompt Manipulation


---

## 🧠 Abstract

Poetry is an expressive form of art that invites multiple interpretations, as readers often bring their own emotions, experiences, and cultural backgrounds into their understanding of a poem. Recognizing this, we aim to **generate and refine images for poems** in a **zero-shot setting**, empowering audiences to **modify images as per their artistic or emotional intent**.

To achieve this, we introduce a novel **Weighted Prompt Manipulation (WPM)** technique — a mechanism that systematically modifies **attention weights** and **text embeddings** within diffusion models.  
By dynamically adjusting the importance of specific words, **WPM** can enhance or suppress their influence in the final generated image, resulting in **semantically richer** and **contextually accurate visualizations**.

Our approach leverages:
- 🌀 **Diffusion Models** for generative image synthesis  
- 🤖 **Large Language Models (LLMs)** such as GPT for prompt analysis  
- 📜 **Poetry datasets** for contextual grounding  

Together, these form a comprehensive methodology for **zero-shot poetic image generation**, enabling deeper human–AI co-creation in the literary domain.

> 🪶 *To the best of our knowledge, this is the first attempt at integrating weighted prompt manipulation for enhancing imagery in poetic language.*

---

## 🚀 Key Features

- 🎭 **Weighted Prompt Manipulation (WPM):** Adjust attention and text embeddings to refine generated imagery.  
- 🧩 **Zero-Shot Adaptation:** Generate and modify poetic visuals without fine-tuning.  
- 💡 **LLM Integration:** Use GPT models for semantic understanding of poems.  
- 🖼️ **User-Driven Modification:** Interactively alter visual emphasis in poem-based images.  
- 📚 **Dataset-Backed Framework:** Utilize existing poetry corpora for grounding.

---


If you use this work or find it helpful, please cite as follows:

@inproceedings{jamil-etal-2025-diy,
    title = "$\textit{Do It Yourself (DIY)}$: Modifying Images for Poems in a Zero-Shot Setting Using Weighted Prompt Manipulation",
    author = "Jamil, Sofia  and
      Charan, Kotla Sai  and
      Saha, Sriparna  and
      Goswami, Koustava  and
      J, Joseph K",
    editor = "Christodoulopoulos, Christos  and
      Chakraborty, Tanmoy  and
      Rose, Carolyn  and
      Peng, Violet",
    booktitle = "Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2025",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.emnlp-main.994/",
    pages = "19668--19676",
    ISBN = "979-8-89176-332-6",
}
