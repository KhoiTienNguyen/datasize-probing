# datasize-probing
Reproduced and expanded on experiments from "On the Importance of Data Size in Probing Fine-tuned Models" by Houman Mehrafarin, Sara Rajaee, Mohammad Taher Pilehva. https://arxiv.org/pdf/2203.09627v1.pdf

Use `Finetune_GLUE.ipynb` to finetune BERT model on GLUE tasks.

Use `Finetune_SuperGLUE.ipynb` to finetune BERT model on SuperGLUE tasks.

Use `SentEval_Probing_notebook.ipynb` to perform probing experiments. This code was provided by the author. https://github.com/hmehrafarin/data-size-analysis

Notes about release: Code was simple and mostly uses other libraries so we did not think it warranted a separate PyPi package.