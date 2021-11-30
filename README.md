# Run Keras tests in Colab

<a href="https://colab.research.google.com/github/AdityaKane2001/keras_build_test/blob/main/Keras_build_test_notebook.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

**This repo has an accompanying blog post on [Towards Data Science](https://towardsdatascience.com/building-keras-from-source-a-follow-along-guide-2bcc4cea3aec).**

Keras has taken a step towards improving developer experience by hosting the codebase in a separate repository. This drastically improves testing times and is a catalyst for rapid open source development. It is now possible to build Keras from source and test it locally. 

Why mess up your local environment when you have Colab? Just click on the "Open in Colab" button, enter your username and branch and you're ready to roll! This notebook will:
- Clone your fork and the desired branch
- Set up dependencies and Bazel
- Build and (re)install Keras
- Run tests on newly installed version of Keras

This notebook is completely based on the [contributing instructions](https://github.com/keras-team/keras/blob/master/CONTRIBUTING.md#option-2-setup-a-local-environment) from the Keras repository itself.

You can run individual tests for modules fairly easily and subsequent build times are drastically lower due to graph-based build in Bazel. 
