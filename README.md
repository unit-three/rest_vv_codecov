# 'little-and-often': 'the brain that changes itself'

[![Gitter](https://badges.gitter.im/repo.svg)](https://app.gitter.im/#/room/!fopQaELIbMGIwdwYRu:gitter.im)
<!-- https://github.com/DAVFoundation/api_doc/issues/6 -->

... from Discord, ['Nascent Road-map'](https://discord.com/channels/1258378561648197643/1258378561648197646/threads/1261313288411676672)


Testing and test-driven development is a good way to continue this journey following on from the learning materials.  

The very nature of being able to effectively collaborate using Git via GitHub is a delicate skill in and of itself.  

Checkpoints mentioned:
1) **Getting Started**: Simple testing suite for flask app.py from learning materials.

2)  **Pete's Challenge:** Setup our fork of openvar/rest_variantValidator.  From this Fork submit pull-request with 1 valid test. 

3) **100% codecov :** Continue creating tests together and aim to  get codecov into the green and ideally 100% for openvar/rest_variantValidator via a fork. 

<br>


### This repo 'rest_vv_codecov' is Checkpoint 1. Getting Started.


[Can use .yml file to conda env create -f <filename>](https://docs.conda.io/projects/conda/en/latest/commands/env/create.html)


** Jérôme Cukier **
built testing frameworks at GoogleAuthor has 4.4K answers and 89.3M answer viewsJun 17
Related
How effective are AI-generated unit tests in achieving good code coverage, and is that enough for reliable software testing?

Codegen is very good at getting full code coverage. With state of the art tools you can definitely generate unit tests for every single branch of a piece of code in any common language.

The problem with those tests is that:

    they will assert that the code works as it is implemented, not as how it’s supposed to do things - a bit similar to how writing unit tests years after the fact.
    These tests are typically not super legible. AI are not great at naming things or at generating meaningful use cases. Human-written tests are sometimes thought of as a way to explain what the code does, and code-gen’d tests are simply not good at that.

Unit tests are usually a very safe investment because they are cheap to write and cheap to run but provide immediate value. LLM generated tests are even cheaper to write, though i’d argue the value is much less, and while the cost of running these tests is very low it’s not always negligible, so the question of their ROI isn’t trivial.
