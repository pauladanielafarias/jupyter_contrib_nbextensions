# Installing jupyter_contrib_nbextensions

### How to install the jupyter_contrib_nbextensions and which are the extensions provided.

# Installing with Conda

1. There are conda packages for the notebook extensions and the [jupyter_nbextensions_configurator](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator) available from [conda-forge](https://conda-forge.org/). You can install both using:

```
conda install -c conda-forge jupyter_contrib_nbextensions
```


2. The _jupyter_nbextensions_configurator_ jupyter server extension provides **graphical user interfaces** for configuring which nbextensions are _enabled_ (load automatically for every notebook). In addition, for nbextensions which include an appropriate yaml descriptor file (see below), the interface also renders their markdown readme files, and provides controls to configure the nbextensions' options.

```
conda install -c conda-forge jupyter_nbextensions_configurator
```

3. Once _jupyter_nbextensions_configurator_ is installed and enabled, and your notebook server has been **restarted**, you should be able to find the nbextensions configuration interface at the url http://localhost:8889/tree in the _Nbextensions_ tab.


<img width="1261" alt="nbextensions configuration interface" src="https://user-images.githubusercontent.com/47432769/109993317-eb7d9700-7cea-11eb-8dd7-17223a4ccf3f.png">

The information above is an abstract from the information available at: 

- [Installing jupyter_contrib_nbextensions](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html)
- [Jupyter-contrib/jupyter_nbextensions_configurator](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator)

-----------------------

# Extensions provided

### Some of the extensions to make the notebook more user friendly:

- [Hinterland](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/hinterland/README.html): This extension enables **code autocompletion menu** for every keypress in a code cell, instead of only enabling it with tab.

- [Code prettify](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/code_prettify/README_code_prettify.html): This extension uses kernel-specific code to **reformat/prettify the contents of code cells*.

- [Code folding](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/codefolding/readme.html): This extension enables the CodeMirror feature to allow **codefolding in code cells**.

- [ExecuteTime](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/execute_time/readme.html): This extension displays **when** each cell has been **executed** and **how long** it took.

- [Snippets Menu](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/snippets_menu/readme.html): This extension adds a _customizable menu item_ to **insert code and markdown snippets**. Comes with extensive defaults for popular python modules, including fairly complete listings of many important functions and constants, to save searching through documentation.

- [ScrollDown](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/scroll_down/readme.html): This extension **scrolls cells' outputs** down automatically as they are **enlarged**. (It can be enabled and disabled using the toolbar button).

- [Hide input](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/hide_input/readme.html): This extension **toggles display** of selected code cell's **input**

- [Spellchecker](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/spellchecker/README.html): This extension adds a CodeMirror overlay mode for Typo.js **spellchecking**. (Default language is en_US)

- [Highlighter](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/highlighter/readme.html): This extension provides several _toolbar buttons_ for **highlighting** a selected text within a **markdown cell**. 

- 


Here's the list of all the available extensions that can be enabled:
[List of provided nbextensions](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions.html)


<img width="1261" alt="List of jupyter_contrib_nbextensions" src="https://user-images.githubusercontent.com/47432769/109993404-03edb180-7ceb-11eb-8fa1-2fa4f5eec285.png">

