{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Paradigma lógico (declarativo)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "A programação lógica se basea em 3 princípios:\n",
    " * linguagem formal para representação de conhecimento\n",
    " * regras de inferência para manipulação de conhecimento\n",
    " * estratégia de busca para controle de inferências\n",
    "\n",
    "# A linguagem PROLOG\n",
    "\n",
    "<img src=\"sistema_prolog.png\" />\n",
    " - **Interface**: permite que o usuário entre com premissas codificadas em\n",
    "uma linguagem lógica e faça consultas para extrair conclusões destas\n",
    "premissas\n",
    " - **Motor de inferência**: atualiza a base de conhecimento com\n",
    "premissas fornecidas pelo usuário e faz inferências para extrair\n",
    "informações implı́citas\n",
    " - **Base de conhecimento**: armazena fatos e regras, fornecidas pelo usuário. \n",
    " Ex)\n",
    "\n",
    "**FATOS**\n",
    "\n",
    "`progenitor(boris, jane).\n",
    "progenitor(boris, marcia).\n",
    "progenitor(adelia, jane).\n",
    "progenitor(jane, tiago).`\n",
    " \n",
    "\n",
    "**REGRAS**\n",
    "\n",
    "`avo(X,Z) :- progenitor(X,Y), progenitor(Y,Z).`\n",
    " "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.6.5"
  },
  "latex_envs": {
   "LaTeX_envs_menu_present": true,
   "autoclose": false,
   "autocomplete": true,
   "bibliofile": "biblio.bib",
   "cite_by": "apalike",
   "current_citInitial": 1,
   "eqLabelWithNumbers": true,
   "eqNumInitial": 1,
   "hotkeys": {
    "equation": "Ctrl-E",
    "itemize": "Ctrl-I"
   },
   "labels_anchors": false,
   "latex_user_defs": false,
   "report_style_numbering": false,
   "user_envs_cfg": false
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
