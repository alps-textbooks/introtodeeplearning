# About This Book

![2Sigma School](2sigma-school-logo.svg)

**MIT Introduction to Deep Learning** · *Software labs from MIT 6.S191*

**2Sigma School** · Alps edition · Updated October 2026

These are the software labs from MIT Introduction to Deep Learning: neural network basics, music generation with RNNs, computer vision and debiasing, and fine-tuning large language models. This Alps edition keeps the labs' words and code, so that they can be read in the page beside the rest of a course.

| At a glance | |
|---|---|
| **3 labs** | Intro to Deep Learning; Computer Vision; Large Language Models |
| **9 notebooks** | In PyTorch and TensorFlow |
| **199 cells for reference** | Code that needs PyTorch, TensorFlow or a hosted service, shown as written |
| **19 cells that run** | Code that needs none of these |

## How to Use It

Read this edition as a guided reading of each lab. The labs are written for PyTorch, TensorFlow and hosted services, which do not run in the browser runtime yet, so most of their code is shown for reference: those cells stay on the page, cannot be edited, and are stepped over by **Run all cells**. To run a lab in full, choose **Run in Google Colab** at the top of its page.

> **Found a problem?** Teachers: choose Report Bug in the left menu, then select the bug icon on the item, or highlight the text. Students: tell your teacher. You can also email [support@alps.2sigma.us](mailto:support@alps.2sigma.us) with the book, chapter and page name.

## Credits

© MIT Introduction to Deep Learning, [http://introtodeeplearning.com](http://introtodeeplearning.com)

Source: [https://github.com/MITDeepLearning/introtodeeplearning](https://github.com/MITDeepLearning/introtodeeplearning)

License: MIT License. This edition is shared under the same license, and each lab keeps its copyright notice.

This edition has been adapted for Alps. As with every book on Alps, its preparation draws on Alps's content-enhancement capabilities, which include the use of language models.

MIT Introduction to Deep Learning is not affiliated with, and does not endorse, this edition.

## Alps Compatibility Changes

The labs' text and code are as their authors wrote them. These are the only changes, and each one is there so the labs import and display in Alps. The numbering of the book's chapters is not affected: this page comes after them.

**A table of contents is added.** The source is a collection of notebooks, so this edition adds one to make it a book. Each lab takes its title from its own Part heading, with the framework added where the PyTorch and TensorFlow versions would share a title.

**Cells are marked, not rewritten.** A cell is shown for reference when it needs PyTorch, torchvision, torchsummary, TensorFlow, Keras, Transformers, Datasets, PEFT, Lion, Comet, Opik or the course's `mitdeeplearning` package, when it needs an API key for a hosted service, when it holds a blank to fill in, or when it reads a name only such cells define.

**Setup cells are split.** Where a setup cell installs or imports these libraries beside others, those lines move to a new cell after it, so the rest of the setup still runs. No line of code is changed.

| Lab | Cells for reference | Cells that run | Setup cell split |
|---|---|---|---|
| Part 1: Intro to PyTorch | 18 | 2 | Yes |
| Part 2: Music Generation with RNNs (PyTorch) | 24 | 1 | |
| Part 1: Intro to TensorFlow | 18 | 2 | Yes |
| Part 2: Music Generation with RNNs (TensorFlow) | 26 | 1 | Yes |
| Part 1: MNIST Digit Classification (PyTorch) | 24 | 2 | Yes |
| Part 2: Debiasing Facial Detection Systems (PyTorch) | 22 | 2 | Yes |
| Part 1: MNIST Digit Classification (TensorFlow) | 20 | 2 | Yes |
| Part 2: Debiasing Facial Detection Systems (TensorFlow) | 19 | 2 | |
| Part 1: Fine-tuning an LLM for Style | 28 | 5 | Yes |
