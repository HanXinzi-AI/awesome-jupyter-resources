<!-- markdownlint-disable -->
<h1 align="center">
    Jupyter资源与工具库大全
    <br>
</h1>

<p align="center">
    <strong>Jupyter开源工具库资源大全，划分子版块并梳理排行，每周自动更新</strong>
</p>

<p align="center">
    <a href="#Contents" title="项目数量"><img src="https://img.shields.io/badge/projects-270-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="欢迎完善"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/HanXinzi-AI/awesome-jupyter-resources/releases" title="最近更新"><img src="https://img.shields.io/github/release-date/HanXinzi-AI/awesome-jupyter-resources?color=green&label=updated"></a>
</p>

本资源清单包含270个jupyter相关的开源工具资源，这些热门工具总共分成13个不同的子板块，这些项目目前在github上已经收到270K个点赞。所有的工具资源每周会自动从GitHub和工具维护平台采集信息，并更新排行展示。本清单参考[best-of模板](https://github.com/best-of-lists/best-of)完成，内容参考了[awesome-jupyter](https://github.com/markusschanta/awesome-jupyter)，欢迎大家提PR丰富本清单。
## Contents

- [Notebook Environments](#notebook-environments) _13 projects_
- [Interactive Widgets & Visualization](#interactive-widgets--visualization) _49 projects_
- [Jupyter Extensions](#jupyter-extensions) _23 projects_
- [Jupyter Magic](#jupyter-magic) _10 projects_
- [Jupyter Kernels](#jupyter-kernels) _36 projects_
- [Notebook Sharing & Conversion](#notebook-sharing--conversion) _23 projects_
- [Notebook Tools](#notebook-tools) _24 projects_
- [JupyterLab Renderer](#jupyterlab-renderer) _7 projects_
- [JupyterLab Themes](#jupyterlab-themes) _8 projects_
- [JupyterLab Extensions](#jupyterlab-extensions) _50 projects_
- [JupyterHub Authenticators](#jupyterhub-authenticators) _15 projects_
- [JupyterHub Spawners](#jupyterhub-spawners) _8 projects_
- [Jupyter Components](#jupyter-components) _3 projects_
- [Others](#others) _4 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects

<br>

## Notebook Environments

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Development environments with support for Jupyter Notebooks._

<details><summary><b><a href="https://github.com/jupyter/notebook">Jupyter</a></b> (🥇29 ·  ⭐ 11K) - Jupyter Interactive Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/notebook) (👨‍💻 630 · 🔀 3.9K · 📥 11K · 📦 19 · 📋 4.6K - 43% open · ⏱️ 30.03.2023):

	```
	git clone https://github.com/jupyter/notebook
	```
- [PyPi](https://pypi.org/project/notebook) (📥 12M / month):
	```
	pip install notebook
	```
- [Conda](https://anaconda.org/conda-forge/jupyter) (📥 3.1M · ⏱️ 05.12.2022):
	```
	conda install -c conda-forge jupyter
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/datascience-notebook) (📥 29M · ⭐ 990 · ⏱️ 27.03.2023):
	```
	docker pull jupyter/datascience-notebook
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyterhub">JupyterHub</a></b> (🥇25 ·  ⭐ 7.4K) - Multi-user server for Jupyter notebooks. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyterhub/jupyterhub) (👨‍💻 330 · 🔀 1.8K · 📦 2.2K · 📋 2.2K - 7% open · ⏱️ 30.03.2023):

	```
	git clone https://github.com/jupyterhub/jupyterhub
	```
- [PyPi](https://pypi.org/project/jupyterhub) (📥 190K / month):
	```
	pip install jupyterhub
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub) (📥 880K · ⏱️ 27.01.2023):
	```
	conda install -c conda-forge jupyterhub
	```
- [Docker Hub](https://hub.docker.com/r/jupyterhub/jupyterhub) (📥 3.7M · ⭐ 320 · ⏱️ 30.03.2023):
	```
	docker pull jupyterhub/jupyterhub
	```
</details>
<details><summary><b><a href="https://github.com/nteract/nteract">nteract</a></b> (🥇25 ·  ⭐ 6K) - The interactive computing suite for you!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/nteract) (👨‍💻 180 · 🔀 530 · 📥 1.4M · 📦 2 · 📋 1.7K - 9% open · ⏱️ 26.03.2023):

	```
	git clone https://github.com/nteract/nteract
	```
- [PyPi](https://pypi.org/project/nteract_on_jupyter) (📥 3.4K / month):
	```
	pip install nteract_on_jupyter
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/docker-stacks">Docker Stacks</a></b> (🥈22 ·  ⭐ 7.6K) - Ready-to-run Docker images containing Jupyter applications. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/docker-stacks) (👨‍💻 230 · 🔀 2.7K · 📋 810 - 2% open · ⏱️ 13.03.2023):

	```
	git clone https://github.com/jupyter/docker-stacks
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/scipy-notebook) (📥 89M · ⭐ 390 · ⏱️ 27.03.2023):
	```
	docker pull jupyter/scipy-notebook
	```
</details>
<details><summary><b><a href="https://github.com/googledatalab/datalab">DataLab</a></b> (🥈22 ·  ⭐ 980) - Interactive tools and developer experiences for Big Data on.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/googledatalab/datalab) (👨‍💻 53 · 🔀 250 · 📋 890 - 25% open · ⏱️ 02.09.2022):

	```
	git clone https://github.com/googledatalab/datalab
	```
- [PyPi](https://pypi.org/project/datalab) (📥 86K / month):
	```
	pip install datalab
	```
</details>
<details><summary><b><a href="https://github.com/vatlab/sos">sos</a></b> (🥈22 ·  ⭐ 250) - SoS workflow system for daily data analysis. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/sos) (👨‍💻 36 · 🔀 34 · 📦 3.8K · 📋 1.4K - 4% open · ⏱️ 18.02.2023):

	```
	git clone https://github.com/vatlab/SOS
	```
</details>
<details><summary><b><a href="https://github.com/nteract/hydrogen">Hydrogen</a></b> (🥉20 ·  ⭐ 3.8K) - Run code interactively, inspect data, and plot. All the power of Jupyter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nteract/hydrogen) (👨‍💻 90 · 🔀 320 · 📋 1.3K - 13% open · ⏱️ 10.01.2023):

	```
	git clone https://github.com/nteract/hydrogen
	```
</details>
<details><summary><b><a href="https://github.com/Kaggle/docker-python">docker-python</a></b> (🥉19 ·  ⭐ 2.3K) - Kaggle Python docker image. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Kaggle/docker-python) (👨‍💻 150 · 🔀 840 · 📋 310 - 6% open · ⏱️ 28.03.2023):

	```
	git clone https://github.com/kaggle/docker-python
	```
- [Docker Hub](https://hub.docker.com/r/kaggle/python) (📥 190K · ⭐ 170 · ⏱️ 28.03.2023):
	```
	docker pull kaggle/python
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/ml-workspace">ML Workspace</a></b> (🥉18 ·  ⭐ 3K · 💀) - All-in-one web-based IDE specialized for machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ml-tooling/ml-workspace) (👨‍💻 11 · 🔀 370 · 📋 91 - 1% open · ⏱️ 22.11.2021):

	```
	git clone https://github.com/ml-tooling/ml-workspace
	```
- [Docker Hub](https://hub.docker.com/r/mltooling/ml-workspace) (📥 520K · ⭐ 26 · ⏱️ 13.07.2021):
	```
	docker pull mltooling/ml-workspace
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/retrolab">jupyterlab-classic</a></b> (🥉17 ·  ⭐ 270) - The next-gen old-school notebook UI. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/retrolab) (👨‍💻 17 · 🔀 46 · 📥 940 · 📦 110 · ⏱️ 16.02.2023):

	```
	git clone https://github.com/jtpio/jupyterlab-classic
	```
- [PyPi](https://pypi.org/project/jupyterlab-classic) (📥 77 / month):
	```
	pip install jupyterlab-classic
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/vscode-jupyter">VSCode Jupyter</a></b> (🥉16 ·  ⭐ 960) - VS Code Jupyter extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/vscode-jupyter) (👨‍💻 260 · 🔀 200 · 📋 8.7K - 5% open · ⏱️ 30.03.2023):

	```
	git clone https://github.com/microsoft/vscode-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/ml-hub">ML Hub</a></b> (🥉16 ·  ⭐ 270 · 💀) - Multi-user development platform for machine learning teams. Simple.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ml-tooling/ml-hub) (👨‍💻 7 · 🔀 58 · 📥 2K · 📋 26 - 57% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/ml-tooling/ml-hub
	```
- [Docker Hub](https://hub.docker.com/r/mltooling/ml-hub) (📥 45K · ⭐ 5 · ⏱️ 18.02.2020):
	```
	docker pull mltooling/ml-hub
	```
</details>
<details><summary><b><a href="https://github.com/iot-salzburg/gpu-jupyter">gpu-jupyter</a></b> (🥉15 ·  ⭐ 490) - Leverage the flexibility of Jupyterlab through the power of your.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iot-salzburg/gpu-jupyter) (👨‍💻 12 · 🔀 170 · 📋 71 - 4% open · ⏱️ 24.03.2023):

	```
	git clone https://github.com/iot-salzburg/gpu-jupyter
	```
</details>
<br>

## Interactive Widgets & Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that provide interactive UI-widgets and visualization tools._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-ml-python#data-visualization">best-of-ml-python - Data Visualization</a></b>  - Python-based data visualization libraries.

<details><summary><b><a href="https://github.com/ydataai/ydata-profiling">pandas-profiling</a></b> (🥇31 ·  ⭐ 10K) - Create HTML profiling reports from pandas DataFrame.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ydataai/ydata-profiling) (👨‍💻 110 · 🔀 1.4K · 📦 190 · 📋 650 - 21% open · ⏱️ 28.03.2023):

	```
	git clone https://github.com/pandas-profiling/pandas-profiling
	```
- [PyPi](https://pypi.org/project/pandas-profiling) (📥 1.1M / month):
	```
	pip install pandas-profiling
	```
- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 350K · ⏱️ 25.01.2023):
	```
	conda install -c conda-forge pandas-profiling
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipywidgets">ipywidgets</a></b> (🥇31 ·  ⭐ 2.8K · 📉) - Interactive Widgets for the Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipywidgets) (👨‍💻 200 · 🔀 870 · 📦 6.4K · 📋 1.9K - 32% open · ⏱️ 28.03.2023):

	```
	git clone https://github.com/jupyter-widgets/ipywidgets
	```
- [PyPi](https://pypi.org/project/ipywidgets) (📥 8.9M / month):
	```
	pip install ipywidgets
	```
- [Conda](https://anaconda.org/conda-forge/ipywidgets) (📥 8.5M · ⏱️ 28.03.2023):
	```
	conda install -c conda-forge ipywidgets
	```
- [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 71K / month):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥇31 ·  ⭐ 1.3K) - A Jupyter - Leaflet.js bridge. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 82 · 🔀 320 · 📦 4K · 📋 540 - 39% open · ⏱️ 10.02.2023):

	```
	git clone https://github.com/jupyter-widgets/ipyleaflet
	```
- [PyPi](https://pypi.org/project/ipyleaflet) (📥 160K / month):
	```
	pip install ipyleaflet
	```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 980K · ⏱️ 19.10.2022):
	```
	conda install -c conda-forge ipyleaflet
	```
- [NPM](https://www.npmjs.com/package/jupyter-leaflet) (📥 61K / month):
	```
	npm install jupyter-leaflet
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/bokeh">bokeh</a></b> (🥇29 ·  ⭐ 17K) - Interactive Data Visualization in the browser, from Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 650 · 🔀 4K · 📦 200 · 📋 7.2K - 9% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh) (📥 3.5M / month):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 11M · ⏱️ 14.03.2023):
	```
	conda install -c conda-forge bokeh
	```
</details>
<details><summary><b><a href="https://github.com/matplotlib/ipympl">jupyter-matplotlib</a></b> (🥇28 ·  ⭐ 1.4K) - Matplotlib Jupyter Integration. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/matplotlib/ipympl) (👨‍💻 31 · 🔀 210 · 📦 6.9K · 📋 280 - 46% open · ⏱️ 27.02.2023):

	```
	git clone https://github.com/matplotlib/ipympl
	```
- [PyPi](https://pypi.org/project/ipympl) (📥 210K / month):
	```
	pip install ipympl
	```
- [NPM](https://www.npmjs.com/package/jupyter-matplotlib) (📥 25K / month):
	```
	npm install jupyter-matplotlib
	```
</details>
<details><summary><b><a href="https://github.com/nteract/papermill">papermill</a></b> (🥈27 ·  ⭐ 5.2K) - Parameterize, execute, and analyze notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/papermill) (👨‍💻 110 · 🔀 370 · 📦 4.7K · 📋 360 - 32% open · ⏱️ 18.10.2022):

	```
	git clone https://github.com/nteract/papermill
	```
- [PyPi](https://pypi.org/project/papermill) (📥 1.1M / month):
	```
	pip install papermill
	```
- [Conda](https://anaconda.org/conda-forge/papermill) (📥 400K · ⏱️ 23.01.2022):
	```
	conda install -c conda-forge papermill
	```
</details>
<details><summary><b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥈27 ·  ⭐ 4K) - Visualizer for Pandas Data Structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/man-group/dtale) (👨‍💻 29 · 🔀 330 · 📦 650 · 📋 500 - 8% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/man-group/dtale
	```
- [PyPi](https://pypi.org/project/dtale) (📥 210K / month):
	```
	pip install dtale
	```
- [Conda](https://anaconda.org/conda-forge/dtale) (📥 200K · ⏱️ 03.03.2023):
	```
	conda install -c conda-forge dtale
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/facets">facets-overview</a></b> (🥈26 ·  ⭐ 7.1K) - Visualizations for machine learning datasets. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/facets) (👨‍💻 30 · 🔀 860 · 📦 170 · 📋 160 - 49% open · ⏱️ 18.02.2023):

	```
	git clone https://github.com/pair-code/facets
	```
- [PyPi](https://pypi.org/project/facets-overview) (📥 310K / month):
	```
	pip install facets-overview
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈26 ·  ⭐ 3.4K) - Plotting library for IPython/Jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 60 · 🔀 440 · 📦 38 · 📋 580 - 37% open · ⏱️ 27.03.2023):

	```
	git clone https://github.com/bqplot/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot) (📥 150K / month):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 1.1M · ⏱️ 29.03.2023):
	```
	conda install -c conda-forge bqplot
	```
- [NPM](https://www.npmjs.com/package/bqplot) (📥 3.2K / month):
	```
	npm install bqplot
	```
</details>
<details><summary><b><a href="https://github.com/plotly/jupyter-dash">jupyter-dash</a></b> (🥈26 ·  ⭐ 890) - Develop Dash apps in the Jupyter Notebook and JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/jupyter-dash) (👨‍💻 10 · 🔀 240 · 📥 82 · 📦 2.6K · 📋 70 - 67% open · ⏱️ 21.10.2022):

	```
	git clone https://github.com/plotly/jupyter-dash
	```
- [PyPi](https://pypi.org/project/jupyter-dash) (📥 310K / month):
	```
	pip install jupyter-dash
	```
</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvolume">ipyvolume</a></b> (🥈24 ·  ⭐ 1.8K · 📉) - 3d plotting for Python in the Jupyter notebook based on IPython.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/widgetti/ipyvolume) (👨‍💻 45 · 🔀 230 · 📦 15 · 📋 310 - 58% open · ⏱️ 25.02.2023):

	```
	git clone https://github.com/maartenbreddels/ipyvolume
	```
- [PyPi](https://pypi.org/project/ipyvolume) (📥 65K / month):
	```
	pip install ipyvolume
	```
- [Conda](https://anaconda.org/conda-forge/ipyvolume) (📥 420K · ⏱️ 25.02.2023):
	```
	conda install -c conda-forge ipyvolume
	```
- [NPM](https://www.npmjs.com/package/ipyvolume) (📥 2K / month):
	```
	npm install ipyvolume
	```
</details>
<details><summary><b><a href="https://github.com/InsightSoftwareConsortium/itkwidgets">itkwidgets</a></b> (🥈24 ·  ⭐ 510) - Interactive Jupyter widgets to visualize images, point sets, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/InsightSoftwareConsortium/itkwidgets) (👨‍💻 6 · 🔀 72 · 📥 75 · 📦 230 · 📋 240 - 42% open · ⏱️ 23.03.2023):

	```
	git clone https://github.com/InsightSoftwareConsortium/itkwidgets
	```
- [PyPi](https://pypi.org/project/itkwidgets) (📥 8.2K / month):
	```
	pip install itkwidgets
	```
- [NPM](https://www.npmjs.com/package/itkwidgets) (📥 1.3K / month):
	```
	npm install itkwidgets
	```
</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvuetify">ipyvuetify</a></b> (🥈24 ·  ⭐ 290) - Jupyter widgets based on vuetify UI components. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/widgetti/ipyvuetify) (👨‍💻 11 · 🔀 49 · 📦 750 · 📋 180 - 29% open · ⏱️ 21.03.2023):

	```
	git clone https://github.com/mariobuikhuizen/ipyvuetify
	```
- [PyPi](https://pypi.org/project/ipyvuetify) (📥 140K / month):
	```
	pip install ipyvuetify
	```
- [Conda](https://anaconda.org/conda-forge/ipyvuetify) (📥 110K · ⏱️ 02.09.2022):
	```
	conda install -c conda-forge ipyvuetify
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥈23 ·  ⭐ 860) - A Jupyter - Three.js bridge. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter-widgets/pythreejs) (👨‍💻 30 · 🔀 170 · 📦 24 · 📋 230 - 24% open · ⏱️ 20.02.2023):

	```
	git clone https://github.com/jupyter-widgets/pythreejs
	```
- [PyPi](https://pypi.org/project/pythreejs) (📥 82K / month):
	```
	pip install pythreejs
	```
- [Conda](https://anaconda.org/conda-forge/pythreejs) (📥 470K · ⏱️ 16.03.2023):
	```
	conda install -c conda-forge pythreejs
	```
- [NPM](https://www.npmjs.com/package/jupyter-threejs) (📥 4.8K / month):
	```
	npm install jupyter-threejs
	```
</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipywebrtc">ipywebrtc</a></b> (🥈23 ·  ⭐ 220) - WebRTC for Jupyter notebook/lab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maartenbreddels/ipywebrtc) (👨‍💻 9 · 🔀 37 · 📦 730 · 📋 57 - 50% open · ⏱️ 06.03.2023):

	```
	git clone https://github.com/maartenbreddels/ipywebrtc
	```
- [PyPi](https://pypi.org/project/ipywebrtc) (📥 63K / month):
	```
	pip install ipywebrtc
	```
- [Conda](https://anaconda.org/conda-forge/ipywebrtc) (📥 300K · ⏱️ 29.03.2021):
	```
	conda install -c conda-forge ipywebrtc
	```
- [NPM](https://www.npmjs.com/package/jupyter-webrtc) (📥 460 / month):
	```
	npm install jupyter-webrtc
	```
</details>
<details><summary><b><a href="https://github.com/evidentlyai/evidently">evidently</a></b> (🥈22 ·  ⭐ 3.3K) - Interactive reports to analyze machine learning models during.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/evidentlyai/evidently) (👨‍💻 37 · 🔀 360 · 📦 1.5K · 📋 190 - 27% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/evidentlyai/evidently
	```
</details>
<details><summary><b><a href="https://github.com/quantopian/qgrid">qgrid</a></b> (🥈22 ·  ⭐ 3K · 💀) - An interactive grid for sorting, filtering, and editing DataFrames.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/qgrid) (👨‍💻 30 · 🔀 400 · 📦 2 · 📋 280 - 55% open · ⏱️ 07.04.2020):

	```
	git clone https://github.com/quantopian/qgrid
	```
- [PyPi](https://pypi.org/project/qgrid) (📥 68K / month):
	```
	pip install qgrid
	```
- [Conda](https://anaconda.org/conda-forge/qgrid) (📥 380K · ⏱️ 02.11.2022):
	```
	conda install -c conda-forge qgrid
	```
- [NPM](https://www.npmjs.com/package/qgrid) (📥 730 / month):
	```
	npm install qgrid
	```
</details>
<details><summary><b><a href="https://github.com/martinRenou/ipycanvas">ipycanvas</a></b> (🥈22 ·  ⭐ 650) - Interactive Canvas in Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/martinRenou/ipycanvas) (👨‍💻 21 · 🔀 56 · 📦 7 · 📋 130 - 38% open · ⏱️ 24.10.2022):

	```
	git clone https://github.com/martinRenou/ipycanvas
	```
- [PyPi](https://pypi.org/project/ipycanvas) (📥 14K / month):
	```
	pip install ipycanvas
	```
- [Conda](https://anaconda.org/conda-forge/ipycanvas) (📥 140K · ⏱️ 29.08.2022):
	```
	conda install -c conda-forge ipycanvas
	```
</details>
<details><summary><b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥈22 ·  ⭐ 630 · 💀) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mapbox/mapboxgl-jupyter) (👨‍💻 21 · 🔀 130 · 📦 150 · 📋 100 - 33% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/mapbox/mapboxgl-jupyter
	```
- [PyPi](https://pypi.org/project/mapboxgl) (📥 14K / month):
	```
	pip install mapboxgl
	```
</details>
<details><summary><b><a href="https://github.com/mwouts/itables">itables</a></b> (🥈22 ·  ⭐ 420) - Interactive Tables in Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/itables) (👨‍💻 6 · 🔀 36 · 📦 220 · 📋 83 - 14% open · ⏱️ 26.03.2023):

	```
	git clone https://github.com/mwouts/itables
	```
- [PyPi](https://pypi.org/project/itables) (📥 40K / month):
	```
	pip install itables
	```
</details>
<details><summary><b><a href="https://github.com/cytoscape/ipycytoscape">ipycytoscape</a></b> (🥈22 ·  ⭐ 220) - A Cytoscape Jupyter widget. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/cytoscape/ipycytoscape) (👨‍💻 32 · 🔀 57 · 📥 3 · 📦 130 · 📋 160 - 37% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/QuantStack/ipycytoscape
	```
- [Conda](https://anaconda.org/conda-forge/ipycytoscape) (📥 270K · ⏱️ 12.09.2022):
	```
	conda install -c conda-forge ipycytoscape
	```
</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvue">ipyvue</a></b> (🥉21 ·  ⭐ 48) - Jupyter widgets base for Vue libraries. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/widgetti/ipyvue) (👨‍💻 3 · 🔀 12 · 📦 420 · 📋 8 - 37% open · ⏱️ 23.02.2023):

	```
	git clone https://github.com/mariobuikhuizen/ipyvue
	```
- [PyPi](https://pypi.org/project/ipyvue) (📥 140K / month):
	```
	pip install ipyvue
	```
- [Conda](https://anaconda.org/conda-forge/ipyvue) (📥 80K · ⏱️ 26.09.2022):
	```
	conda install -c conda-forge ipyvue
	```
</details>
<details><summary><b><a href="https://github.com/vidartf/ipydatawidgets">ipydatawidgets</a></b> (🥉21 ·  ⭐ 36) - A set of widgets to help facilitate reuse of large.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/vidartf/ipydatawidgets) (👨‍💻 5 · 🔀 9 · 📦 740 · 📋 12 - 25% open · ⏱️ 19.02.2023):

	```
	git clone https://github.com/vidartf/ipydatawidgets
	```
- [PyPi](https://pypi.org/project/ipydatawidgets) (📥 86K / month):
	```
	pip install ipydatawidgets
	```
- [Conda](https://anaconda.org/conda-forge/ipydatawidgets) (📥 220K · ⏱️ 24.08.2022):
	```
	conda install -c conda-forge ipydatawidgets
	```
</details>
<details><summary><b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉19 ·  ⭐ 750 · 💀) - Google maps for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pbugnion/gmaps) (👨‍💻 16 · 🔀 150 · 📦 3 · 📋 210 - 34% open · ⏱️ 22.07.2019):

	```
	git clone https://github.com/pbugnion/gmaps
	```
- [PyPi](https://pypi.org/project/gmaps) (📥 7.5K / month):
	```
	pip install gmaps
	```
- [Conda](https://anaconda.org/conda-forge/gmaps) (📥 290K · ⏱️ 02.08.2019):
	```
	conda install -c conda-forge gmaps
	```
- [NPM](https://www.npmjs.com/package/jupyter-gmaps) (📥 1.5K / month):
	```
	npm install jupyter-gmaps
	```
</details>
<details><summary><b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉19 ·  ⭐ 540 · 💀) - Dragndrop Pivot Tables and Charts for Jupyter/IPython.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nicolaskruchten/jupyter_pivottablejs) (👨‍💻 3 · 🔀 66 · 📦 310 · 📋 61 - 32% open · ⏱️ 04.12.2018):

	```
	git clone https://github.com/nicolaskruchten/jupyter_pivottablejs
	```
- [PyPi](https://pypi.org/project/pivottablejs) (📥 28K / month):
	```
	pip install pivottablejs
	```
</details>
<details><summary><b><a href="https://github.com/QuantStack/ipysheet">ipysheet</a></b> (🥉19 ·  ⭐ 520) - Jupyter handsontable integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QuantStack/ipysheet) (👨‍💻 13 · 🔀 63 · 📦 6 · 📋 120 - 50% open · ⏱️ 28.11.2022):

	```
	git clone https://github.com/QuantStack/ipysheet
	```
- [PyPi](https://pypi.org/project/ipysheet) (📥 46K / month):
	```
	pip install ipysheet
	```
- [Conda](https://anaconda.org/conda-forge/ipysheet) (📥 75K · ⏱️ 28.11.2022):
	```
	conda install -c conda-forge ipysheet
	```
- [NPM](https://www.npmjs.com/package/ipysheet) (📥 1.8K / month):
	```
	npm install ipysheet
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉18 ·  ⭐ 790 · 💀) - Source code/webpage/demos for the What-If Tool. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/what-if-tool) (👨‍💻 20 · 🔀 150 · 📋 120 - 53% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/PAIR-code/what-if-tool
	```
- [PyPi](https://pypi.org/project/witwidget) (📥 10K / month):
	```
	pip install witwidget
	```
- [NPM](https://www.npmjs.com/package/wit-widget) (📥 1.2K / month):
	```
	npm install wit-widget
	```
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉18 ·  ⭐ 340) - IPython/Jupyter notebook module for Vega and Vega-Lite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 13 · 🔀 58 · 📦 2 · 📋 100 - 11% open · ⏱️ 28.02.2023):

	```
	git clone https://github.com/vega/ipyvega
	```
- [PyPi](https://pypi.org/project/vega) (📥 12K / month):
	```
	pip install vega
	```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 540K · ⏱️ 05.12.2022):
	```
	conda install -c conda-forge vega
	```
</details>
<details><summary><b><a href="https://github.com/QuantStack/ipytree">ipytree</a></b> (🥉18 ·  ⭐ 110) - A Tree Widget using Jupyter-widgets protocol and jsTree. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QuantStack/ipytree) (👨‍💻 9 · 🔀 27 · 📦 2 · 📋 36 - 52% open · ⏱️ 23.11.2022):

	```
	git clone https://github.com/QuantStack/ipytree
	```
- [PyPi](https://pypi.org/project/ipytree) (📥 75K / month):
	```
	pip install ipytree
	```
- [Conda](https://anaconda.org/conda-forge/ipytree) (📥 66K · ⏱️ 23.08.2022):
	```
	conda install -c conda-forge ipytree
	```
</details>
<details><summary><b><a href="https://github.com/medialab/ipysigma">ipysigma</a></b> (🥉18 ·  ⭐ 87 · 📈) - A custom Jupyter widget library to display graphs using sigma.js. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/medialab/ipysigma) (👨‍💻 6 · 🔀 10 · 📦 20 · 📋 190 - 21% open · ⏱️ 04.02.2023):

	```
	git clone https://github.com/Yomguithereal/ipysigma
	```
- [PyPi](https://pypi.org/project/ipysigma) (📥 560 / month):
	```
	pip install ipysigma
	```
- [NPM](https://www.npmjs.com/package/ipysigma) (📥 520 / month):
	```
	npm install ipysigma
	```
</details>
<details><summary><b><a href="https://github.com/g2nb/igv-jupyter">igv.js widget</a></b> (🥉17 ·  ⭐ 150) - Extension for Jupyter Notebook which integrates igv.js. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/g2nb/igv-jupyter) (👨‍💻 5 · 🔀 15 · 📦 12 · ⏱️ 03.01.2023):

	```
	git clone https://github.com/igvteam/igv-jupyter
	```
- [PyPi](https://pypi.org/project/igv-jupyter) (📥 490 / month):
	```
	pip install igv-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/finos/ipyregulartable">ipyregulartable</a></b> (🥉17 ·  ⭐ 80) - High performance, editable, stylable datagrids in jupyter.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/ipyregulartable) (👨‍💻 5 · 🔀 15 · 📦 11 · 📋 26 - 38% open · ⏱️ 28.03.2023):

	```
	git clone https://github.com/jpmorganchase/ipyregulartable
	```
- [PyPi](https://pypi.org/project/ipyregulartable) (📥 140 / month):
	```
	pip install ipyregulartable
	```
- [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 71K / month):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/vidartf/ipyscales">ipyscales</a></b> (🥉17 ·  ⭐ 13) - A widget library for scales. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vidartf/ipyscales) (👨‍💻 4 · 🔀 4 · 📦 56 · 📋 6 - 33% open · ⏱️ 01.09.2022):

	```
	git clone https://github.com/vidartf/ipyscales
	```
- [PyPi](https://pypi.org/project/ipyscales) (📥 97 / month):
	```
	pip install ipyscales
	```
- [Conda](https://anaconda.org/conda-forge/ipyscales) (📥 57K · ⏱️ 12.10.2022):
	```
	conda install -c conda-forge ipyscales
	```
</details>
<details><summary><b><a href="https://github.com/spacetelescope/jdaviz">jdaviz</a></b> (🥉16 ·  ⭐ 87) - JWST astronomical data analysis tools in the Jupyter platform. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/spacetelescope/jdaviz) (👨‍💻 31 · 🔀 44 · 📋 850 - 32% open · ⏱️ 30.03.2023):

	```
	git clone https://github.com/spacetelescope/jdaviz
	```
- [PyPi](https://pypi.org/project/jdaviz) (📥 460 / month):
	```
	pip install jdaviz
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair_viewer">Altair Viewer</a></b> (🥉16 ·  ⭐ 58) - Viewer for Altair and Vega-Lite visualizations. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair_viewer) (👨‍💻 3 · 🔀 8 · 📋 9 - 55% open · ⏱️ 23.02.2023):

	```
	git clone https://github.com/altair-viz/altair_viewer
	```
- [PyPi](https://pypi.org/project/altair_viewer) (📥 45K / month):
	```
	pip install altair_viewer
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/ipydagred3">ipydagred3</a></b> (🥉16 ·  ⭐ 49) - ipywidgets library for drawing directed acyclic graphs in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/ipydagred3) (👨‍💻 3 · 🔀 7 · 📦 2 · 📋 20 - 15% open · ⏱️ 28.03.2023):

	```
	git clone https://github.com/timkpaine/ipydagred3
	```
- [PyPi](https://pypi.org/project/ipydagred3) (📥 350 / month):
	```
	pip install ipydagred3
	```
- [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 71K / month):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/OpenGeoscience/geonotebook">geonotebook</a></b> (🥉15 ·  ⭐ 1.1K · 💀) - A Jupyter notebook extension for geospatial visualization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/OpenGeoscience/geonotebook) (👨‍💻 9 · 🔀 140 · 📋 83 - 44% open · ⏱️ 21.01.2019):

	```
	git clone https://github.com/OpenGeoscience/geonotebook
	```
- [Docker Hub](https://hub.docker.com/r/geonotebook/geonotebook) (📥 130K · ⭐ 7 · ⏱️ 21.01.2019):
	```
	docker pull geonotebook/geonotebook
	```
</details>
<details><summary><b><a href="https://github.com/lgpage/nbtutor">nbtutor</a></b> (🥉15 ·  ⭐ 430) - Visualize Python code execution (line-by-line) in Jupyter.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lgpage/nbtutor) (👨‍💻 4 · 🔀 39 · 📦 33 · 📋 36 - 33% open · ⏱️ 23.03.2023):

	```
	git clone https://github.com/lgpage/nbtutor
	```
- [Conda](https://anaconda.org/conda-forge/nbtutor) (📥 130K · ⏱️ 19.04.2022):
	```
	conda install -c conda-forge nbtutor
	```
</details>
<details><summary><b><a href="https://github.com/nipy/niwidgets">niwidgets</a></b> (🥉14 ·  ⭐ 81 · 💀) - Neuroimaging widgets for jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nipy/niwidgets) (👨‍💻 16 · 🔀 33 · 📦 28 · 📋 34 - 50% open · ⏱️ 24.03.2020):

	```
	git clone https://github.com/nipy/niwidgets
	```
- [PyPi](https://pypi.org/project/niwidgets) (📥 78 / month):
	```
	pip install niwidgets
	```
</details>
<details><summary><b><a href="https://github.com/CermakM/jupyter-datatables">Jupyter DataTables</a></b> (🥉13 ·  ⭐ 200 · 💀) - Jupyter Notebook extension leveraging pandas DataFrames.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CermakM/jupyter-datatables) (👨‍💻 4 · 🔀 23 · 📋 28 - 46% open · ⏱️ 11.12.2019):

	```
	git clone https://github.com/CermakM/jupyter-datatables
	```
- [PyPi](https://pypi.org/project/jupyter-datatables) (📥 980 / month):
	```
	pip install jupyter-datatables
	```
</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipymaterialui">ipymaterialui</a></b> (🥉12 ·  ⭐ 84 · 💀) - Jupyter Widgets based on React Material UI components. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maartenbreddels/ipymaterialui) (👨‍💻 3 · 🔀 14 · 📦 7 · 📋 10 - 70% open · ⏱️ 29.10.2019):

	```
	git clone https://github.com/maartenbreddels/ipymaterialui
	```
- [PyPi](https://pypi.org/project/ipymaterialui) (📥 41 / month):
	```
	pip install ipymaterialui
	```
- [NPM](https://www.npmjs.com/package/jupyter-materialui) (📥 12 / month):
	```
	npm install jupyter-materialui
	```
</details>
<details><summary><b><a href="https://github.com/ipyannotate/ipyannotate">ipyannotate</a></b> (🥉10 ·  ⭐ 140 · 💀) - Jupyter Widget for data annotation. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipyannotate/ipyannotate) (👨‍💻 3 · 🔀 13 · ⏱️ 20.09.2020):

	```
	git clone https://github.com/ipyannotate/ipyannotate
	```
- [PyPi](https://pypi.org/project/ipyannotate) (📥 550 / month):
	```
	pip install ipyannotate
	```
- [NPM](https://www.npmjs.com/package/ipyannotate) (📥 27 / month):
	```
	npm install ipyannotate
	```
</details>
<details><summary><b><a href="https://github.com/leifwalsh/perfume">perfume</a></b> (🥉10 ·  ⭐ 33 · 💀) - Interactive performance benchmarking in Jupyter. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/leifwalsh/perfume) (👨‍💻 3 · 🔀 4 · 📋 6 - 33% open · ⏱️ 31.10.2020):

	```
	git clone https://github.com/leifwalsh/perfume
	```
- [PyPi](https://pypi.org/project/perfume-bench) (📥 16 / month):
	```
	pip install perfume-bench
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/tributary">tributary</a></b> (🥉10 ·  ⭐ 7) - Streaming reactive and dataflow graphs in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/tributary) (👨‍💻 7 · ⏱️ 22.11.2022):

	```
	git clone https://github.com/timkpaine/tributary
	```
- [PyPi](https://pypi.org/project/tributary) (📥 120 / month):
	```
	pip install tributary
	```
- [Conda](https://anaconda.org/conda-forge/tributary) (📥 27K · ⏱️ 17.05.2022):
	```
	conda install -c conda-forge tributary
	```
</details>
<details><summary><b><a href="https://github.com/asvcode/Vision_UI">Vision UI</a></b> (🥉9 ·  ⭐ 250 · 💀) - UI visual interface for fastai - now compatible with Google.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/asvcode/Vision_UI) (👨‍💻 3 · 🔀 33 · 📋 3 - 33% open · ⏱️ 05.07.2020):

	```
	git clone https://github.com/asvcode/Vision_UI
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/ipyp5">ipyp5</a></b> (🥉9 ·  ⭐ 33 · 💀) - p5.js Jupyter Widget. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/ipyp5) (👨‍💻 2 · 🔀 5 · 📦 1 · ⏱️ 16.10.2020):

	```
	git clone https://github.com/jtpio/ipyp5
	```
- [PyPi](https://pypi.org/project/ipyp5) (📥 16 / month):
	```
	pip install ipyp5
	```
</details>
<details><summary><b><a href="https://github.com/DGothrek/ipyaggrid">ipyaggrid</a></b> (🥉9 ·  ⭐ 11 · 💀) - Jupyter widget - ag-grid in the notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/DGothrek/ipyaggrid) (👨‍💻 2 · ⏱️ 06.05.2019):

	```
	git clone https://github.com/DGothrek/ipyaggrid
	```
- [PyPi](https://pypi.org/project/ipyaggrid) (📥 6K / month):
	```
	pip install ipyaggrid
	```
- [NPM](https://www.npmjs.com/package/ipyaggrid) (📥 910 / month):
	```
	npm install ipyaggrid
	```
</details>
<details><summary><b><a href="https://github.com/GianniBalistreri/easyexplore">easyexplore</a></b> (🥉9 ·  ⭐ 4 · 💤) - Toolbox for easy and effective data exploration in Python. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/GianniBalistreri/easyexplore) (👨‍💻 4 · 🔀 2 · 📦 1 · 📋 24 - 33% open · ⏱️ 08.06.2022):

	```
	git clone https://github.com/GianniBalistreri/easyexplore
	```
- [PyPi](https://pypi.org/project/easyexplore) (📥 780 / month):
	```
	pip install easyexplore
	```
</details>
<br>

## Jupyter Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of Jupyter itself._

<details><summary><b><a href="https://github.com/jupyter/nbgrader">nbgrader</a></b> (🥇24 ·  ⭐ 1.2K) - A system for assigning and grading notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbgrader) (👨‍💻 100 · 🔀 300 · 📥 110 · 📦 410 · 📋 860 - 26% open · ⏱️ 28.03.2023):

	```
	git clone https://github.com/jupyter/nbgrader
	```
- [PyPi](https://pypi.org/project/nbgrader) (📥 5.4K / month):
	```
	pip install nbgrader
	```
- [Conda](https://anaconda.org/conda-forge/nbgrader) (📥 140K · ⏱️ 28.09.2022):
	```
	conda install -c conda-forge nbgrader
	```
</details>
<details><summary><b><a href="https://github.com/ipython-contrib/jupyter_contrib_nbextensions">Contrib NBextensions</a></b> (🥇23 ·  ⭐ 5K) - A collection of various notebook extensions for.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) (👨‍💻 140 · 🔀 770 · 📋 790 - 42% open · ⏱️ 21.12.2022):

	```
	git clone https://github.com/ipython-contrib/jupyter_contrib_nbextensions
	```
- [PyPi](https://pypi.org/project/jupyter_contrib_nbextensions) (📥 360K / month):
	```
	pip install jupyter_contrib_nbextensions
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter-resource-usage">Resource Usage</a></b> (🥇23 ·  ⭐ 360) - Jupyter Notebook Extension for monitoring your own Resource.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter-resource-usage) (👨‍💻 31 · 🔀 86 · 📥 180 · 📦 320 · 📋 73 - 49% open · ⏱️ 21.03.2023):

	```
	git clone https://github.com/jupyter-server/jupyter-resource-usage
	```
- [PyPi](https://pypi.org/project/jupyter-resource-usage) (📥 24K / month):
	```
	pip install jupyter-resource-usage
	```
- [Conda](https://anaconda.org/conda-forge/nbresuse) (📥 530K · ⏱️ 23.11.2020):
	```
	conda install -c conda-forge nbresuse
	```
</details>
<details><summary><b><a href="https://github.com/oschuett/appmode">Appmode</a></b> (🥈21 ·  ⭐ 420) - A Jupyter extensions that turns notebooks into web applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oschuett/appmode) (👨‍💻 9 · 🔀 71 · 📦 340 · 📋 57 - 12% open · ⏱️ 09.03.2023):

	```
	git clone https://github.com/oschuett/appmode
	```
- [PyPi](https://pypi.org/project/appmode) (📥 2K / month):
	```
	pip install appmode
	```
- [Conda](https://anaconda.org/conda-forge/appmode) (📥 200K · ⏱️ 08.11.2022):
	```
	conda install -c conda-forge appmode
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nbgitpuller">nbgitpuller</a></b> (🥈21 ·  ⭐ 180) - Jupyter server extension to sync a git repository one-way to a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nbgitpuller) (👨‍💻 27 · 🔀 67 · 📦 620 · 📋 140 - 41% open · ⏱️ 21.03.2023):

	```
	git clone https://github.com/jupyterhub/nbgitpuller
	```
- [PyPi](https://pypi.org/project/nbgitpuller) (📥 11K / month):
	```
	pip install nbgitpuller
	```
- [Conda](https://anaconda.org/conda-forge/nbgitpuller) (📥 59K · ⏱️ 09.11.2022):
	```
	conda install -c conda-forge nbgitpuller
	```
</details>
<details><summary><b><a href="https://github.com/dunovank/jupyter-themes">Jupyter Themes</a></b> (🥈20 ·  ⭐ 9.5K · 💀) - Custom Jupyter Notebook Themes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dunovank/jupyter-themes) (👨‍💻 43 · 🔀 1K · 📋 390 - 48% open · ⏱️ 03.02.2022):

	```
	git clone https://github.com/dunovank/jupyter-themes
	```
- [PyPi](https://pypi.org/project/jupyterthemes) (📥 43K / month):
	```
	pip install jupyterthemes
	```
</details>
<details><summary><b><a href="https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator">NBextensions Configurator</a></b> (🥈20 ·  ⭐ 930) - A jupyter notebook serverextension providing config.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator) (👨‍💻 22 · 🔀 110 · 📋 89 - 64% open · ⏱️ 21.12.2022):

	```
	git clone https://github.com/jupyter-contrib/jupyter_nbextensions_configurator
	```
- [PyPi](https://pypi.org/project/jupyter_nbextensions_configurator) (📥 390K / month):
	```
	pip install jupyter_nbextensions_configurator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-rsession-proxy">Rsession Proxy</a></b> (🥈20 ·  ⭐ 100) - Jupyter extensions for running an RStudio rsession proxy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-rsession-proxy) (👨‍💻 21 · 🔀 74 · 📦 43 · 📋 75 - 37% open · ⏱️ 24.09.2022):

	```
	git clone https://github.com/jupyterhub/jupyter-rsession-proxy
	```
- [PyPi](https://pypi.org/project/jupyter-rsession-proxy) (📥 17K / month):
	```
	pip install jupyter-rsession-proxy
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-server-proxy">jupyter-server-proxy</a></b> (🥈19 ·  ⭐ 280) - Jupyter notebook server extension to proxy web services. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-server-proxy) (👨‍💻 66 · 🔀 120 · 📦 2 · 📋 170 - 35% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/jupyterhub/jupyter-server-proxy
	```
- [PyPi](https://pypi.org/project/jupyter-server-proxy) (📥 150K / month):
	```
	pip install jupyter-server-proxy
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-server-proxy) (📥 1.3M · ⏱️ 08.09.2022):
	```
	conda install -c conda-forge jupyter-server-proxy
	```
</details>
<details><summary><b><a href="https://github.com/mamba-org/gator">gator</a></b> (🥈19 ·  ⭐ 240) - Conda environment and package management extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/gator) (👨‍💻 25 · 🔀 24 · 📥 2 · 📦 4 · 📋 54 - 24% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/mamba-org/gator
	```
- [Conda](https://anaconda.org/conda-forge/mamba_gator) (📥 28K · ⏱️ 26.07.2022):
	```
	conda install -c conda-forge mamba_gator
	```
- [NPM](https://www.npmjs.com/package/@mamba-org/gator-lab) (📥 100 / month):
	```
	npm install @mamba-org/gator-lab
	```
</details>
<details><summary><b><a href="https://github.com/8080labs/pyforest">pyforest</a></b> (🥉18 ·  ⭐ 1K · 💀) - pyforest - feel the bliss of automated imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/8080labs/pyforest) (👨‍💻 13 · 🔀 190 · 📋 24 - 41% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/8080labs/pyforest
	```
- [PyPi](https://pypi.org/project/pyforest) (📥 14K / month):
	```
	pip install pyforest
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/jupyter-spark">Jupyter Spark</a></b> (🥉16 ·  ⭐ 190 · 💀) - Jupyter Notebook extension for Apache Spark integration. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/mozilla/jupyter-spark) (👨‍💻 12 · 🔀 29 · 📦 18 · 📋 27 - 48% open · ⏱️ 01.12.2020):

	```
	git clone https://github.com/mozilla/jupyter-spark
	```
- [PyPi](https://pypi.org/project/jupyter-spark) (📥 2.4K / month):
	```
	pip install jupyter-spark
	```
</details>
<details><summary><b><a href="https://github.com/krishnan-r/sparkmonitor">Spark Monitor</a></b> (🥉16 ·  ⭐ 170 · 💤) - Monitor Apache Spark from Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/krishnan-r/sparkmonitor) (👨‍💻 3 · 🔀 49 · 📥 2.4K · 📋 22 - 68% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/krishnan-r/sparkmonitor
	```
- [PyPi](https://pypi.org/project/sparkmonitor) (📥 920 / month):
	```
	pip install sparkmonitor
	```
- [Docker Hub](https://hub.docker.com/r/krishnanr/sparkmonitor) (📥 940 · ⏱️ 04.10.2019):
	```
	docker pull krishnanr/sparkmonitor
	```
</details>
<details><summary><b><a href="https://github.com/data-8/nbzip">nbzip</a></b> (🥉16 ·  ⭐ 80 · 💀) - Zips and downloads all the contents of a jupyter notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/data-8/nbzip) (👨‍💻 6 · 🔀 16 · 📦 340 · 📋 14 - 64% open · ⏱️ 22.11.2019):

	```
	git clone https://github.com/data-8/nbzip
	```
- [PyPi](https://pypi.org/project/nbzip) (📥 4.6K / month):
	```
	pip install nbzip
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyter-archive">jupyter-archive</a></b> (🥉16 ·  ⭐ 61) - A Jupyter/Jupyterlab extension to make, download and extract.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyter-archive) (👨‍💻 10 · 🔀 11 · 📥 3.3K · 📦 2 · 📋 36 - 2% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/jupyterlab-contrib/jupyter-archive
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-archive) (📥 39K · ⏱️ 16.03.2023):
	```
	conda install -c conda-forge jupyter-archive
	```
</details>
<details><summary><b><a href="https://github.com/lspvic/jupyter_tensorboard">jupyter-tensorboard</a></b> (🥉15 ·  ⭐ 460 · 💀) - Start Tensorboard in Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lspvic/jupyter_tensorboard) (👨‍💻 4 · 🔀 70 · 📋 69 - 57% open · ⏱️ 16.02.2020):

	```
	git clone https://github.com/lspvic/jupyter_tensorboard
	```
- [PyPi](https://pypi.org/project/jupyter-tensorboard) (📥 16K / month):
	```
	pip install jupyter-tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/googlecolab/jupyter_http_over_ws">HTTP-over-WebSocket</a></b> (🥉15 ·  ⭐ 260 · 💀) - Jupyter support for HTTP-over-ws. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/googlecolab/jupyter_http_over_ws) (👨‍💻 3 · 🔀 47 · 📋 30 - 70% open · ⏱️ 30.08.2021):

	```
	git clone https://github.com/googlecolab/jupyter_http_over_ws
	```
- [PyPi](https://pypi.org/project/jupyter_http_over_ws) (📥 38K / month):
	```
	pip install jupyter_http_over_ws
	```
</details>
<details><summary><b><a href="https://github.com/Anaconda-Platform/nb_conda">nb_conda</a></b> (🥉15 ·  ⭐ 130 · 💀) - Conda environment and package access extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Anaconda-Platform/nb_conda) (👨‍💻 14 · 🔀 29 · 📋 63 - 55% open · ⏱️ 11.09.2020):

	```
	git clone https://github.com/Anaconda-Platform/nb_conda
	```
- [Conda](https://anaconda.org/conda-forge/nb_conda) (📥 490K · ⏱️ 05.06.2022):
	```
	conda install -c conda-forge nb_conda
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-incubator/contentmanagement">Content Management</a></b> (🥉14 ·  ⭐ 76 · 💀) - Jupyter Content Management Extensions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-incubator/contentmanagement) (👨‍💻 8 · 🔀 27 · 📋 27 - 25% open · ⏱️ 11.06.2018):

	```
	git clone https://github.com/jupyter-incubator/contentmanagement
	```
- [PyPi](https://pypi.org/project/jupyter_cms) (📥 210 / month):
	```
	pip install jupyter_cms
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_cms) (📥 85K · ⏱️ 07.11.2022):
	```
	conda install -c conda-forge jupyter_cms
	```
</details>
<details><summary><b><a href="https://github.com/thoth-station/jupyter-nbrequirements">jupyter-nbrequirements</a></b> (🥉12 ·  ⭐ 14) - Dependency management and optimization in Jupyter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thoth-station/jupyter-nbrequirements) (👨‍💻 12 · 🔀 7 · 📋 33 - 3% open · ⏱️ 20.09.2022):

	```
	git clone https://github.com/thoth-station/jupyter-nbrequirements
	```
</details>
<details><summary><b><a href="https://github.com/drillan/jupyter-black">Jupyter Black</a></b> (🥉9 ·  ⭐ 420 · 💀) - Black formatter for Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/drillan/jupyter-black) (👨‍💻 2 · 🔀 23 · 📋 22 - 40% open · ⏱️ 01.02.2020):

	```
	git clone https://github.com/drillan/jupyter-black
	```
</details>
<details><summary><b><a href="https://github.com/paypal/PPExtensions">PPExtensions</a></b> (🥉9 ·  ⭐ 48 · 💀) - Set of iPython and Jupyter extensions to improve user.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/paypal/PPExtensions) (👨‍💻 9 · 🔀 27 · 📦 1 · 📋 38 - 42% open · ⏱️ 07.12.2018):

	```
	git clone https://github.com/paypal/PPExtensions
	```
- [PyPi](https://pypi.org/project/ppextensions) (📥 31 / month):
	```
	pip install ppextensions
	```
</details>
<details><summary><b><a href="https://github.com/willkessler/jupyterterminals">jupyterterminals</a></b> (🥉7 ·  ⭐ 8) - Jupyter plugin to support inline terminal shells along with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/willkessler/jupyterterminals) (👨‍💻 2 · 🔀 2 · 📦 2 · ⏱️ 05.01.2023):

	```
	git clone https://github.com/willkessler/jupyterterminals
	```
</details>
<br>

## Jupyter Magic

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that provide magic commands to access convenient functionality within a notebook._

<details><summary><b><a href="https://github.com/catherinedevlin/ipython-sql">ipython-sql</a></b> (🥇28 ·  ⭐ 1.7K) - %%sql magic for IPython, hopefully evolving into full SQL client. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/catherinedevlin/ipython-sql) (👨‍💻 55 · 🔀 260 · 📦 4.2K · 📋 150 - 72% open · ⏱️ 26.02.2023):

	```
	git clone https://github.com/catherinedevlin/ipython-sql
	```
- [PyPi](https://pypi.org/project/ipython-sql) (📥 120K / month):
	```
	pip install ipython-sql
	```
- [Conda](https://anaconda.org/conda-forge/ipython-sql) (📥 210K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge ipython-sql
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-incubator/sparkmagic">sparkmagic</a></b> (🥇26 ·  ⭐ 1.2K) - Jupyter magics and kernels for working with remote Spark.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter-incubator/sparkmagic) (👨‍💻 59 · 🔀 400 · 📦 300 · 📋 420 - 31% open · ⏱️ 11.02.2023):

	```
	git clone https://github.com/jupyter-incubator/sparkmagic
	```
- [PyPi](https://pypi.org/project/sparkmagic) (📥 35K / month):
	```
	pip install sparkmagic
	```
- [Conda](https://anaconda.org/conda-forge/sparkmagic) (📥 69K · ⏱️ 30.01.2023):
	```
	conda install -c conda-forge sparkmagic
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/watermark">watermark</a></b> (🥈22 ·  ⭐ 780) - An IPython magic extension for printing date and time stamps, version.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rasbt/watermark) (👨‍💻 17 · 🔀 82 · 📦 1.8K · 📋 45 - 37% open · ⏱️ 13.09.2022):

	```
	git clone https://github.com/rasbt/watermark
	```
- [PyPi](https://pypi.org/project/watermark) (📥 22K / month):
	```
	pip install watermark
	```
- [Conda](https://anaconda.org/conda-forge/watermark) (📥 250K · ⏱️ 30.05.2022):
	```
	conda install -c conda-forge watermark
	```
</details>
<details><summary><b><a href="https://github.com/csurfer/pyheatmagic">heat</a></b> (🥈16 ·  ⭐ 1K · 💀) - IPython magic command to profile and view your python code as a heat map. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csurfer/pyheatmagic) (👨‍💻 3 · 🔀 23 · 📦 36 · 📋 5 - 40% open · ⏱️ 10.09.2021):

	```
	git clone https://github.com/csurfer/pyheatmagic
	```
- [PyPi](https://pypi.org/project/py-heat-magic) (📥 1.1K / month):
	```
	pip install py-heat-magic
	```
</details>
<details><summary><b><a href="https://github.com/csurfer/blackcellmagic">blackcellmagic</a></b> (🥈16 ·  ⭐ 300 · 💀) - IPython magic command to format python code in cell using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csurfer/blackcellmagic) (👨‍💻 3 · 🔀 12 · 📦 220 · 📋 10 - 50% open · ⏱️ 18.09.2021):

	```
	git clone https://github.com/csurfer/blackcellmagic
	```
- [PyPi](https://pypi.org/project/blackcellmagic) (📥 3.9K / month):
	```
	pip install blackcellmagic
	```
</details>
<details><summary><b><a href="https://github.com/ShopRunner/jupyter-notify">jupyter-notify</a></b> (🥉15 ·  ⭐ 570 · 💀) - A Jupyter Notebook magic for browser notifications of cell.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ShopRunner/jupyter-notify) (👨‍💻 11 · 🔀 34 · 📋 24 - 50% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/ShopRunner/jupyter-notify
	```
- [PyPi](https://pypi.org/project/jupyternotify) (📥 1.7K / month):
	```
	pip install jupyternotify
	```
</details>
<details><summary><b><a href="https://github.com/nteract/pick">pick</a></b> (🥉13 ·  ⭐ 32 · 💀) - Customize your kernels on Launch!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/pick) (👨‍💻 5 · 🔀 7 · 📋 9 - 44% open · ⏱️ 04.11.2020):

	```
	git clone https://github.com/nteract/pick
	```
- [PyPi](https://pypi.org/project/pick) (📥 69K / month):
	```
	pip install pick
	```
</details>
<details><summary><b><a href="https://github.com/ResidentMario/py_d3">py_d3</a></b> (🥉12 ·  ⭐ 450 · 💀) - D3 block magic for Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ResidentMario/py_d3) (👨‍💻 4 · 🔀 39 · 📋 16 - 6% open · ⏱️ 20.02.2022):

	```
	git clone https://github.com/ResidentMario/py_d3
	```
- [PyPi](https://pypi.org/project/py_d3) (📥 92 / month):
	```
	pip install py_d3
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyter-manim">jupyter-manim</a></b> (🥉11 ·  ⭐ 190 · 💀) - manim cell magic for IPython/Jupyter to show the output video. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyter-manim) (👨‍💻 5 · 🔀 11 · 📋 25 - 24% open · ⏱️ 02.01.2022):

	```
	git clone https://github.com/krassowski/jupyter-manim
	```
</details>
<details><summary><b><a href="https://github.com/tmthyjames/SQLCell">SQLCell</a></b> (🥉11 ·  ⭐ 150 · 💀) - SQLCell is a magic function for the Jupyter Notebook that executes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tmthyjames/SQLCell) (👨‍💻 14 · 🔀 10 · 📦 1 · 📋 84 - 71% open · ⏱️ 06.10.2020):

	```
	git clone https://github.com/tmthyjames/SQLCell
	```
- [PyPi](https://pypi.org/project/sqlcell) (📥 56 / month):
	```
	pip install sqlcell
	```
</details>
<br>

## Jupyter Kernels

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Jupyter kernels that run and introspect the user's code in a given language._

<details><summary><b><a href="https://github.com/ipython/ipykernel">IPython Kernel</a></b> (🥇32 ·  ⭐ 540 · 📈) - IPython Kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython/ipykernel) (👨‍💻 170 · 🔀 320 · 📥 1.3K · 📦 240K · 📋 450 - 50% open · ⏱️ 20.03.2023):

	```
	git clone https://github.com/ipython/ipykernel
	```
- [PyPi](https://pypi.org/project/ipykernel) (📥 15M / month):
	```
	pip install ipykernel
	```
- [Conda](https://anaconda.org/anaconda/ipykernel) (📥 640K · ⏱️ 16.03.2023):
	```
	conda install -c anaconda ipykernel
	```
</details>
<details><summary><b><a href="https://github.com/IRkernel/IRkernel">IRkernel</a></b> (🥇23 ·  ⭐ 1.6K) - R kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IRkernel/IRkernel) (👨‍💻 43 · 🔀 280 · 📋 580 - 11% open · ⏱️ 06.03.2023):

	```
	git clone https://github.com/IRkernel/IRkernel
	```
- [Conda](https://anaconda.org/r/r-irkernel) (📥 120K · ⏱️ 31.05.2022):
	```
	conda install -c r r-irkernel
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/r-notebook) (📥 1.6M · ⭐ 53 · ⏱️ 27.03.2023):
	```
	docker pull jupyter/r-notebook
	```
</details>
<details><summary><b><a href="https://github.com/gopherdata/gophernotes">gophernotes</a></b> (🥇22 ·  ⭐ 3.5K) - The Go kernel for Jupyter notebooks and nteract. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gopherdata/gophernotes) (👨‍💻 29 · 🔀 230 · 📥 41 · 📦 10 · 📋 180 - 29% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/gopherdata/gophernotes
	```
- [Docker Hub](https://hub.docker.com/r/gopherdata/gophernotes) (📥 87K · ⭐ 7 · ⏱️ 22.12.2018):
	```
	docker pull gopherdata/gophernotes
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/metakernel">Metakernel</a></b> (🥇22 ·  ⭐ 310) - Jupyter/IPython Kernel Tools. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/metakernel) (👨‍💻 32 · 🔀 81 · 📥 78 · 📦 710 · 📋 140 - 19% open · ⏱️ 12.12.2022):

	```
	git clone https://github.com/Calysto/metakernel
	```
- [PyPi](https://pypi.org/project/metakernel) (📥 23K / month):
	```
	pip install metakernel
	```
- [Conda](https://anaconda.org/conda-forge/metakernel) (📥 680K · ⏱️ 12.12.2022):
	```
	conda install -c conda-forge metakernel
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-toree">Apache Toree</a></b> (🥈20 ·  ⭐ 710) - Jupyter kernel for Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/incubator-toree) (👨‍💻 110 · 🔀 220 · ⏱️ 08.02.2023):

	```
	git clone https://github.com/apache/incubator-toree
	```
- [PyPi](https://pypi.org/project/toree) (📥 12K / month):
	```
	pip install toree
	```
</details>
<details><summary><b><a href="https://github.com/akabe/ocaml-jupyter">OCaml Kernel</a></b> (🥈20 ·  ⭐ 250) - An OCaml kernel for Jupyter (IPython) notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/akabe/ocaml-jupyter) (👨‍💻 22 · 🔀 36 · 📥 84K · 📋 76 - 6% open · ⏱️ 19.02.2023):

	```
	git clone https://github.com/akabe/ocaml-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/JuliaLang/IJulia.jl">IJulia.jl</a></b> (🥈19 ·  ⭐ 2.6K) - Julia kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/JuliaLang/IJulia.jl) (👨‍💻 110 · 🔀 390 · 📋 810 - 13% open · ⏱️ 17.01.2023):

	```
	git clone https://github.com/JuliaLang/IJulia.jl
	```
</details>
<details><summary><b><a href="https://github.com/n-riesco/ijavascript">IJavascript</a></b> (🥈19 ·  ⭐ 2K) - IJavascript is a javascript kernel for the Jupyter notebook. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/n-riesco/ijavascript) (👨‍💻 16 · 🔀 150 · 📦 72 · 📋 230 - 22% open · ⏱️ 28.12.2022):

	```
	git clone https://github.com/n-riesco/ijavascript
	```
- [NPM](https://www.npmjs.com/package/ijavascript) (📥 3.7K / month):
	```
	npm install ijavascript
	```
</details>
<details><summary><b><a href="https://github.com/almond-sh/almond">almond</a></b> (🥈19 ·  ⭐ 1.5K) - A Scala kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/almond-sh/almond) (👨‍💻 39 · 🔀 220 · 📥 1.6K · 📋 300 - 33% open · ⏱️ 10.03.2023):

	```
	git clone https://github.com/almond-sh/almond
	```
- [Docker Hub](https://hub.docker.com/r/almondsh/almond) (📥 17K · ⭐ 6 · ⏱️ 10.03.2023):
	```
	docker pull almondsh/almond
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/kernel_gateway">Kernel Gateway</a></b> (🥈19 ·  ⭐ 430) - Jupyter Kernel Gateway. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter-server/kernel_gateway) (👨‍💻 44 · 🔀 120 · 📥 110 · 📋 180 - 8% open · ⏱️ 02.03.2023):

	```
	git clone https://github.com/jupyter/kernel_gateway
	```
- [PyPi](https://pypi.org/project/jupyter-kernel-gateway) (📥 45K / month):
	```
	pip install jupyter-kernel-gateway
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-cling">xeus-cling</a></b> (🥈18 ·  ⭐ 2.6K) - Jupyter kernel for the C++ programming language. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-cling) (👨‍💻 24 · 🔀 260 · 📋 260 - 54% open · ⏱️ 03.02.2023):

	```
	git clone https://github.com/jupyter-xeus/xeus-cling
	```
- [Conda](https://anaconda.org/conda-forge/xeus-cling) (📥 190K · ⏱️ 31.01.2023):
	```
	conda install -c conda-forge xeus-cling
	```
</details>
<details><summary><b><a href="https://github.com/SciRuby/iruby">IRuby</a></b> (🥈18 ·  ⭐ 760) - Official gem repository: Ruby kernel for Jupyter/IPython Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SciRuby/iruby) (👨‍💻 46 · 🔀 19 · 📥 15 · 📦 170 · 📋 190 - 23% open · ⏱️ 11.01.2023):

	```
	git clone https://github.com/SciRuby/iruby
	```
- [Docker Hub](https://hub.docker.com/r/rubydata/datascience-notebook) (📥 1.8K · ⭐ 5 · ⏱️ 03.02.2023):
	```
	docker pull rubydata/datascience-notebook
	```
</details>
<details><summary><b><a href="https://github.com/Anaconda-Platform/nb_conda_kernels">nb_conda_kernels</a></b> (🥈18 ·  ⭐ 500 · 💀) - Package for managing conda environment-based kernels.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Anaconda-Platform/nb_conda_kernels) (👨‍💻 14 · 🔀 59 · 📋 140 - 28% open · ⏱️ 30.11.2020):

	```
	git clone https://github.com/Anaconda-Platform/nb_conda_kernels
	```
- [Conda](https://anaconda.org/conda-forge/nb_conda_kernels) (📥 1M · ⏱️ 29.10.2022):
	```
	conda install -c conda-forge nb_conda_kernels
	```
</details>
<details><summary><b><a href="https://github.com/vericast/spylon-kernel">Spylon Kernel</a></b> (🥈18 ·  ⭐ 170 · 💀) - Jupyter kernel for scala and spark. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/vericast/spylon-kernel) (👨‍💻 6 · 🔀 31 · 📦 110 · 📋 39 - 48% open · ⏱️ 20.09.2018):

	```
	git clone https://github.com/Valassis-Digital-Media/spylon-kernel
	```
- [PyPi](https://pypi.org/project/spylon-kernel) (📥 6K / month):
	```
	pip install spylon-kernel
	```
- [Conda](https://anaconda.org/conda-forge/spylon-kernel) (📥 110K · ⏱️ 05.10.2018):
	```
	conda install -c conda-forge spylon-kernel
	```
</details>
<details><summary><b><a href="https://github.com/IHaskell/IHaskell">IHaskell</a></b> (🥈17 ·  ⭐ 2.5K) - A Haskell kernel for IPython. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IHaskell/IHaskell) (👨‍💻 110 · 🔀 250 · 📋 770 - 6% open · ⏱️ 03.03.2023):

	```
	git clone https://github.com/gibiansky/IHaskell
	```
- [NPM](https://www.npmjs.com/package/ihaskell_jupyterlab) (📥 16 / month):
	```
	npm install ihaskell_jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/SpencerPark/IJava">IJava</a></b> (🥈17 ·  ⭐ 920 · 💀) - A Jupyter kernel for executing Java code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SpencerPark/IJava) (👨‍💻 4 · 🔀 170 · 📥 120K · 📋 130 - 56% open · ⏱️ 08.12.2019):

	```
	git clone https://github.com/SpencerPark/IJava
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/bash_kernel">Bash Kernel</a></b> (🥈17 ·  ⭐ 630) - A bash kernel for IPython. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/takluyver/bash_kernel) (👨‍💻 16 · 🔀 110 · 📋 98 - 35% open · ⏱️ 18.12.2022):

	```
	git clone https://github.com/takluyver/bash_kernel
	```
- [PyPi](https://pypi.org/project/bash_kernel) (📥 12K / month):
	```
	pip install bash_kernel
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/enterprise_gateway">Enterprise Gateway</a></b> (🥈17 ·  ⭐ 550) - A lightweight, multi-tenant, scalable and secure.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter-server/enterprise_gateway) (👨‍💻 110 · 🔀 190 · 📥 27K · 📋 550 - 11% open · ⏱️ 27.03.2023):

	```
	git clone https://github.com/jupyter/enterprise_gateway
	```
- [PyPi](https://pypi.org/project/jupyter_enterprise_gateway) (📥 2.5K / month):
	```
	pip install jupyter_enterprise_gateway
	```
</details>
<details><summary><b><a href="https://github.com/sassoftware/sas_kernel">SAS Kernel</a></b> (🥈17 ·  ⭐ 190) - A Jupyter kernel for SAS. This opens up all the data manipulation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sassoftware/sas_kernel) (👨‍💻 11 · 🔀 77 · ⏱️ 13.01.2023):

	```
	git clone https://github.com/sassoftware/sas_kernel
	```
- [PyPi](https://pypi.org/project/sas_kernel) (📥 3.6K / month):
	```
	pip install sas_kernel
	```
</details>
<details><summary><b><a href="https://github.com/scijava/scijava-jupyter-kernel">SciJava Kernel</a></b> (🥈17 ·  ⭐ 170 · 💀) - Write SciJava scripts in Jupyter notebook!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/scijava/scijava-jupyter-kernel) (👨‍💻 9 · 🔀 42 · 📥 92 · ⏱️ 03.02.2022):

	```
	git clone https://github.com/scijava/scijava-jupyter-kernel
	```
- [Conda](https://anaconda.org/conda-forge/scijava-jupyter-kernel) (📥 90K · ⏱️ 03.03.2018):
	```
	conda install -c conda-forge scijava-jupyter-kernel
	```
</details>
<details><summary><b><a href="https://github.com/ansible/ansible-jupyter-kernel">Ansible Kernel</a></b> (🥉16 ·  ⭐ 520 · 💀) - Jupyter Notebook Kernel for running Ansible Tasks and.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ansible/ansible-jupyter-kernel) (👨‍💻 10 · 🔀 55 · 📦 10 · 📋 45 - 35% open · ⏱️ 11.02.2022):

	```
	git clone https://github.com/ansible/ansible-jupyter-kernel
	```
- [PyPi](https://pypi.org/project/ansible-kernel) (📥 100 / month):
	```
	pip install ansible-kernel
	```
- [Conda](https://anaconda.org/conda-forge/ansible-kernel) (📥 13K · ⏱️ 12.02.2022):
	```
	conda install -c conda-forge ansible-kernel
	```
- [Docker Hub](https://hub.docker.com/r/benthomasson/ansible-jupyter-kernel) (📥 66K · ⭐ 2 · ⏱️ 12.12.2018):
	```
	docker pull benthomasson/ansible-jupyter-kernel
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/octave_kernel">Octave Kernel</a></b> (🥉16 ·  ⭐ 420 · 📉) - An Octave kernel for IPython. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/octave_kernel) (👨‍💻 20 · 🔀 63 · 📥 100 · 📋 180 - 17% open · ⏱️ 18.12.2022):

	```
	git clone https://github.com/calysto/octave_kernel
	```
- [PyPi](https://pypi.org/project/octave_kernel) (📥 6.4K / month):
	```
	pip install octave_kernel
	```
</details>
<details><summary><b><a href="https://github.com/clojupyter/clojupyter">clojupyter</a></b> (🥉15 ·  ⭐ 780) - a Jupyter kernel for Clojure. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/clojupyter/clojupyter) (👨‍💻 26 · 🔀 75 · 📋 99 - 15% open · ⏱️ 06.11.2022):

	```
	git clone https://github.com/clojupyter/clojupyter
	```
- [Conda](https://anaconda.org/simplect/clojupyter) (📥 3.3K · ⏱️ 02.03.2020):
	```
	conda install -c simplect clojupyter
	```
- [Docker Hub](https://hub.docker.com/r/simplect/clojupyter) (📥 410 · ⏱️ 25.04.2019):
	```
	docker pull simplect/clojupyter
	```
</details>
<details><summary><b><a href="https://github.com/pprzetacznik/IElixir">IElixir</a></b> (🥉15 ·  ⭐ 340 · 💀) - Jupyter's kernel for Elixir programming language. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pprzetacznik/IElixir) (👨‍💻 19 · 🔀 40 · 📋 30 - 33% open · ⏱️ 20.03.2021):

	```
	git clone https://github.com/pprzetacznik/IElixir
	```
- [Docker Hub](https://hub.docker.com/r/pprzetacznik/ielixir) (📥 350 · ⭐ 1 · ⏱️ 20.03.2021):
	```
	docker pull pprzetacznik/ielixir
	```
</details>
<details><summary><b><a href="https://github.com/Cadair/jupyter_environment_kernels">Kernel Detection</a></b> (🥉15 ·  ⭐ 150) - An Jupyter plugin to enable the automatic detection of.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/Cadair/jupyter_environment_kernels) (👨‍💻 8 · 🔀 17 · 📋 29 - 20% open · ⏱️ 23.11.2022):

	```
	git clone https://github.com/Cadair/jupyter_environment_kernels
	```
- [PyPi](https://pypi.org/project/environment_kernels) (📥 4.3K / month):
	```
	pip install environment_kernels
	```
</details>
<details><summary><b><a href="https://github.com/WolframResearch/WolframLanguageForJupyter">Wolfram Kernel</a></b> (🥉14 ·  ⭐ 830 · 💀) - Wolfram Language kernel for Jupyter notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/WolframResearch/WolframLanguageForJupyter) (👨‍💻 7 · 🔀 100 · 📥 7.4K · 📋 100 - 35% open · ⏱️ 19.02.2022):

	```
	git clone https://github.com/WolframResearch/WolframLanguageForJupyter
	```
</details>
<details><summary><b><a href="https://github.com/lfortran/lfortran">LFortran</a></b> (🥉14 ·  ⭐ 570) - Official mirror of https://gitlab.com/lfortran/lfortran. Please.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lfortran/lfortran) (👨‍💻 55 · 🔀 65 · 📋 790 - 76% open · ⏱️ 28.03.2023):

	```
	git clone https://github.com/lfortran/lfortran
	```
- [PyPi](https://pypi.org/project/lfortran) (📥 110 / month):
	```
	pip install lfortran
	```
- [Conda](https://anaconda.org/conda-forge/lfortran) (📥 54K · ⏱️ 18.10.2022):
	```
	conda install -c conda-forge lfortran
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/matlab_kernel">Matlab Kernel</a></b> (🥉14 ·  ⭐ 460 · 💤) - Jupyter Kernel for Matlab. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Calysto/matlab_kernel) (👨‍💻 18 · 🔀 75 · 📋 130 - 19% open · ⏱️ 09.05.2022):

	```
	git clone https://github.com/calysto/matlab_kernel
	```
- [PyPi](https://pypi.org/project/matlab_kernel) (📥 860 / month):
	```
	pip install matlab_kernel
	```
</details>
<details><summary><b><a href="https://github.com/yunabe/lgo">lgo</a></b> (🥉13 ·  ⭐ 2.3K · 💀) - Interactive Go programming with Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/yunabe/lgo) (👨‍💻 9 · 🔀 120 · 📋 76 - 30% open · ⏱️ 09.07.2019):

	```
	git clone https://github.com/yunabe/lgo
	```
</details>
<details><summary><b><a href="https://github.com/fsprojects/IfSharp">F# Kernel</a></b> (🥉12 ·  ⭐ 440 · 💤) - F# for Jupyter Notebooks. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/fsprojects/IfSharp) (👨‍💻 28 · 🔀 65 · 📥 5.5K · 📋 140 - 9% open · ⏱️ 17.03.2022):

	```
	git clone https://github.com/fsprojects/IfSharp
	```
- [Docker Hub](https://hub.docker.com/r/fsprojects/ifsharp) (📥 700 · ⏱️ 26.03.2019):
	```
	docker pull fsprojects/ifsharp
	```
</details>
<details><summary><b><a href="https://github.com/NII-cloud-operation/sshkernel">SSH Kernel</a></b> (🥉12 ·  ⭐ 57 · 💀) - SSH Kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/NII-cloud-operation/sshkernel) (👨‍💻 4 · 🔀 13 · 📦 7 · 📋 9 - 22% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/NII-cloud-operation/sshkernel
	```
- [PyPi](https://pypi.org/project/sshkernel) (📥 100 / month):
	```
	pip install sshkernel
	```
</details>
<details><summary><b><a href="https://github.com/zabirauf/icsharp">ICSharp</a></b> (🥉11 ·  ⭐ 270 · 💀) - C# kernel for Jupyter. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/zabirauf/icsharp) (👨‍💻 10 · 🔀 58 · 📋 46 - 71% open · ⏱️ 23.09.2018):

	```
	git clone https://github.com/zabirauf/icsharp
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-sqlite">xeus-sqlite</a></b> (🥉10 ·  ⭐ 150) - Jupyter kernel for SQLite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-sqlite) (👨‍💻 12 · 🔀 22 · 📋 44 - 29% open · ⏱️ 16.03.2023):

	```
	git clone https://github.com/jupyter-xeus/xeus-sqlite
	```
</details>
<details><summary><b><a href="https://github.com/tdaff/remote_ikernel">remote_ikernel</a></b> (🥉10 ·  ⭐ 13 · 💀) - All your Jupyter kernels, on all your machines, in one place. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/tdaff/remote_ikernel) (👨‍💻 7 · 🔀 11 · 📋 28 - 35% open · ⏱️ 08.11.2020):

	```
	git clone https://github.com/tdaff/remote_ikernel
	```
- [PyPi](https://pypi.org/project/remote_ikernel) (📥 370 / month):
	```
	pip install remote_ikernel
	```
</details>
<details><summary><b><a href="https://github.com/bernhard-42/ssh_ipykernel">ssh_ipykernel</a></b> (🥉7 ·  ⭐ 9 · 💀) - A remote jupyter kernel via ssh. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bernhard-42/ssh_ipykernel) (👨‍💻 2 · 🔀 1 · 📦 2 · ⏱️ 28.06.2021):

	```
	git clone https://github.com/bernhard-42/ssh_ipykernel
	```
</details>
<details><summary><b><a href="https://github.com/nteract/kernel-relay">kernel-relay</a></b> (🥉6 ·  ⭐ 12 · 💀) - kernel-relay is a GraphQL service for interfacing with.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nteract/kernel-relay) (👨‍💻 3 · 🔀 5 · 📦 2 · 📋 12 - 83% open · ⏱️ 10.07.2019):

	```
	git clone https://github.com/nteract/kernel-relay
	```
</details>
<br>

## Notebook Sharing & Conversion

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Tools to share, convert and simplify collaboration (e.g., via git) with notebook files._

<details><summary><b><a href="https://github.com/jupyter/nbconvert">nbconvert</a></b> (🥇33 ·  ⭐ 1.5K) - Jupyter Notebook Conversion. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbconvert) (👨‍💻 260 · 🔀 500 · 📥 320 · 📦 200K · 📋 1.1K - 44% open · ⏱️ 16.03.2023):

	```
	git clone https://github.com/jupyter/nbconvert
	```
- [PyPi](https://pypi.org/project/nbconvert) (📥 16M / month):
	```
	pip install nbconvert
	```
- [Conda](https://anaconda.org/conda-forge/nbconvert) (📥 11M · ⏱️ 28.03.2023):
	```
	conda install -c conda-forge nbconvert
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/jupyter-book">Jupyter Book</a></b> (🥇31 ·  ⭐ 3.3K · 📈) - Build interactive, publication-quality documents from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/executablebooks/jupyter-book) (👨‍💻 120 · 🔀 570 · 📦 9.1K · 📋 1.2K - 42% open · ⏱️ 14.03.2023):

	```
	git clone https://github.com/executablebooks/jupyter-book
	```
- [PyPi](https://pypi.org/project/jupyter-book) (📥 87K / month):
	```
	pip install jupyter-book
	```
</details>
<details><summary><b><a href="https://github.com/mwouts/jupytext">Jupytext</a></b> (🥇29 ·  ⭐ 5.9K) - Jupyter Notebooks as Markdown Documents, Julia, Python or R scripts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/jupytext) (👨‍💻 78 · 🔀 370 · 📦 4.8K · 📋 570 - 15% open · ⏱️ 27.03.2023):

	```
	git clone https://github.com/mwouts/jupytext
	```
- [PyPi](https://pypi.org/project/jupytext) (📥 430K / month):
	```
	pip install jupytext
	```
- [Conda](https://anaconda.org/conda-forge/jupytext) (📥 530K · ⏱️ 25.02.2023):
	```
	conda install -c conda-forge jupytext
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-jupytext) (📥 8.2K / month):
	```
	npm install jupyterlab-jupytext
	```
</details>
<details><summary><b><a href="https://github.com/getnikola/nikola">nikola</a></b> (🥈28 ·  ⭐ 2.4K) - A static website and blog generator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/getnikola/nikola) (👨‍💻 230 · 🔀 360 · 📦 470 · 📋 2.1K - 2% open · ⏱️ 26.03.2023):

	```
	git clone https://github.com/getnikola/nikola
	```
- [PyPi](https://pypi.org/project/nikola) (📥 1.2K / month):
	```
	pip install nikola
	```
</details>
<details><summary><b><a href="https://github.com/voila-dashboards/voila">Voila</a></b> (🥈26 ·  ⭐ 4.6K) - Voil turns Jupyter notebooks into standalone web applications. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/voila-dashboards/voila) (👨‍💻 64 · 🔀 450 · 📥 560 · 📦 9.5K · 📋 650 - 41% open · ⏱️ 27.03.2023):

	```
	git clone https://github.com/voila-dashboards/voila
	```
- [PyPi](https://pypi.org/project/voila) (📥 170K / month):
	```
	pip install voila
	```
- [Conda](https://anaconda.org/conda-forge/voila) (📥 250K · ⏱️ 27.10.2022):
	```
	conda install -c conda-forge voila
	```
- [NPM](https://www.npmjs.com/package/@jupyter-voila/jupyterlab-preview) (📥 900 / month):
	```
	npm install @jupyter-voila/jupyterlab-preview
	```
</details>
<details><summary><b><a href="https://github.com/damianavila/RISE">RISE</a></b> (🥈24 ·  ⭐ 3.5K) - RISE: Live Reveal.js Jupyter/IPython Slideshow Extension. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/damianavila/RISE) (👨‍💻 44 · 🔀 390 · 📦 2.4K · 📋 440 - 34% open · ⏱️ 16.01.2023):

	```
	git clone https://github.com/damianavila/RISE
	```
- [PyPi](https://pypi.org/project/RISE) (📥 7.9K / month):
	```
	pip install RISE
	```
- [Conda](https://anaconda.org/conda-forge/rise) (📥 260K · ⏱️ 03.11.2022):
	```
	conda install -c conda-forge rise
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbdime">nbdime</a></b> (🥈23 ·  ⭐ 2.4K) - Tools for diffing and merging of Jupyter notebooks. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/nbdime) (👨‍💻 45 · 🔀 140 · 📦 110 · 📋 300 - 24% open · ⏱️ 24.03.2023):

	```
	git clone https://github.com/jupyter/nbdime
	```
- [PyPi](https://pypi.org/project/nbdime) (📥 200K / month):
	```
	pip install nbdime
	```
- [Conda](https://anaconda.org/conda-forge/nbdime) (📥 800K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge nbdime
	```
- [NPM](https://www.npmjs.com/package/nbdime-jupyterlab) (📥 43K / month):
	```
	npm install nbdime-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/airbnb/knowledge-repo">Knowledge Repo</a></b> (🥈22 ·  ⭐ 5.3K) - A next-generation curated knowledge sharing platform for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airbnb/knowledge-repo) (👨‍💻 73 · 🔀 660 · 📋 290 - 42% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/airbnb/knowledge-repo
	```
- [PyPi](https://pypi.org/project/knowledge-repo) (📥 480 / month):
	```
	pip install knowledge-repo
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbviewer">nbviewer</a></b> (🥈20 ·  ⭐ 2.1K) - nbconvert as a web service: Render Jupyter Notebooks as static web.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbviewer) (👨‍💻 95 · 🔀 510 · 📦 10 · 📋 580 - 29% open · ⏱️ 27.01.2023):

	```
	git clone https://github.com/jupyter/nbviewer
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/nbviewer) (📥 2.8M · ⭐ 32 · ⏱️ 27.01.2023):
	```
	docker pull jupyter/nbviewer
	```
</details>
<details><summary><b><a href="https://github.com/danielfrg/mkdocs-jupyter">mkdocs-jupyter</a></b> (🥈20 ·  ⭐ 210 · 📈) - Use Jupyter Notebook in mkdocs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/mkdocs-jupyter) (👨‍💻 18 · 🔀 35 · 📦 1.1K · 📋 81 - 16% open · ⏱️ 28.03.2023):

	```
	git clone https://github.com/danielfrg/mkdocs-jupyter
	```
- [PyPi](https://pypi.org/project/mkdocs-jupyter) (📥 41K / month):
	```
	pip install mkdocs-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/aaren/notedown">notedown</a></b> (🥉19 ·  ⭐ 840 · 💀) - Markdown = IPython Notebook. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/aaren/notedown) (👨‍💻 7 · 🔀 92 · 📦 220 · 📋 68 - 57% open · ⏱️ 16.11.2017):

	```
	git clone https://github.com/aaren/notedown
	```
- [PyPi](https://pypi.org/project/notedown) (📥 5.2K / month):
	```
	pip install notedown
	```
- [Conda](https://anaconda.org/conda-forge/notedown) (📥 35K · ⏱️ 07.06.2018):
	```
	conda install -c conda-forge notedown
	```
</details>
<details><summary><b><a href="https://github.com/nteract/bookstore">bookstore</a></b> (🥉19 ·  ⭐ 190 · 💀) - Notebook storage and publishing workflows for the masses. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/bookstore) (👨‍💻 7 · 🔀 20 · 📦 13 · 📋 73 - 46% open · ⏱️ 09.12.2019):

	```
	git clone https://github.com/nteract/bookstore
	```
- [PyPi](https://pypi.org/project/bookstore) (📥 49K / month):
	```
	pip install bookstore
	```
</details>
<details><summary><b><a href="https://github.com/stencila/stencila">Stencila</a></b> (🥉18 ·  ⭐ 670 · 📉) - Living documents for reproducible research. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/stencila/stencila) (👨‍💻 35 · 🔀 37 · 📥 3.5K · 📦 19 · 📋 560 - 11% open · ⏱️ 31.01.2023):

	```
	git clone https://github.com/stencila/stencila
	```
- [NPM](https://www.npmjs.com/package/stencila) (📥 140 / month):
	```
	npm install stencila
	```
- [Docker Hub](https://hub.docker.com/r/stencila/cloud) (📥 16K · ⏱️ 08.04.2019):
	```
	docker pull stencila/cloud
	```
</details>
<details><summary><b><a href="https://github.com/nteract/scrapbook">scrapbook</a></b> (🥉18 ·  ⭐ 260 · 💤) - A library for recording and reading data in notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/scrapbook) (👨‍💻 11 · 🔀 27 · 📦 220 · 📋 49 - 48% open · ⏱️ 13.04.2022):

	```
	git clone https://github.com/nteract/scrapbook
	```
- [PyPi](https://pypi.org/project/nteract-scrapbook) (📥 34K / month):
	```
	pip install nteract-scrapbook
	```
</details>
<details><summary><b><a href="https://github.com/nteract/commuter">commuter</a></b> (🥉17 ·  ⭐ 460 · 💤) - Notebook sharing hub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/commuter) (👨‍💻 27 · 🔀 63 · 📦 5 · 📋 91 - 57% open · ⏱️ 28.04.2022):

	```
	git clone https://github.com/nteract/commuter
	```
- [NPM](https://www.npmjs.com/package/@nteract/commuter) (📥 250 / month):
	```
	npm install @nteract/commuter
	```
</details>
<details><summary><b><a href="https://github.com/SamLau95/nbinteract">nbinteract</a></b> (🥉17 ·  ⭐ 220 · 💀) - Create interactive webpages from Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/SamLau95/nbinteract) (👨‍💻 8 · 🔀 21 · 📦 3 · 📋 70 - 41% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/SamLau95/nbinteract
	```
- [PyPi](https://pypi.org/project/nbinteract) (📥 3.3K / month):
	```
	pip install nbinteract
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/binderhub">BinderHub</a></b> (🥉15 ·  ⭐ 2.3K) - Run your code in the cloud, with technology so advanced, it feels.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/binderhub) (👨‍💻 93 · 🔀 350 · 📦 8 · 📋 660 - 29% open · ⏱️ 27.03.2023):

	```
	git clone https://github.com/jupyterhub/binderhub
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/thebe">ThebeLab</a></b> (🥉15 ·  ⭐ 310) - ThebeLab: turning static HTML pages into live documents. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/executablebooks/thebe) (👨‍💻 26 · 🔀 57 · 📦 6 · 📋 170 - 45% open · ⏱️ 14.03.2023):

	```
	git clone https://github.com/executablebooks/thebe
	```
</details>
<details><summary><b><a href="https://github.com/ideonate/cdsdashboards">cdsdashboards</a></b> (🥉14 ·  ⭐ 180) - JupyterHub extension for ContainDS Dashboards. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ideonate/cdsdashboards) (👨‍💻 14 · 🔀 37 · 📋 91 - 35% open · ⏱️ 12.09.2022):

	```
	git clone https://github.com/ideonate/cdsdashboards
	```
- [PyPi](https://pypi.org/project/cdsdashboards) (📥 340 / month):
	```
	pip install cdsdashboards
	```
- [Conda](https://anaconda.org/conda-forge/cdsdashboards) (📥 42K · ⏱️ 12.09.2022):
	```
	conda install -c conda-forge cdsdashboards
	```
</details>
<details><summary><b><a href="https://github.com/danielfrg/jupyter-flex">jupyter-flex</a></b> (🥉13 ·  ⭐ 280) - Build dashboards using Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/jupyter-flex) (👨‍💻 4 · 🔀 53 · 📦 41 · 📋 58 - 15% open · ⏱️ 28.03.2023):

	```
	git clone https://github.com/danielfrg/jupyter-flex
	```
</details>
<details><summary><b><a href="https://github.com/elehcimd/pynb">pynb</a></b> (🥉13 ·  ⭐ 240 · 💀) - Jupyter Notebooks as plain Python code with embedded Markdown text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/elehcimd/pynb) (👨‍💻 8 · 🔀 6 · 📦 21 · ⏱️ 07.07.2020):

	```
	git clone https://github.com/elehcimd/pynb
	```
</details>
<details><summary><b><a href="https://github.com/nbgallery/nbgallery">nbgallery</a></b> (🥉13 ·  ⭐ 150) - Enterprise Jupyter notebook sharing and collaboration app. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbgallery/nbgallery) (👨‍💻 20 · 🔀 25 · 📋 430 - 11% open · ⏱️ 20.03.2023):

	```
	git clone https://github.com/nbgallery/nbgallery
	```
- [Docker Hub](https://hub.docker.com/r/nbgallery/nbgallery) (📥 170K · ⭐ 3 · ⏱️ 14.03.2023):
	```
	docker pull nbgallery/nbgallery
	```
</details>
<details><summary><b><a href="https://github.com/line/jnotebook_reader">jnotebook-reader</a></b> (🥉10 ·  ⭐ 100) - An awesome viewer to browse and render Jupyter.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/line/jnotebook_reader) (👨‍💻 7 · 🔀 16 · 📋 5 - 20% open · ⏱️ 06.12.2022):

	```
	git clone https://github.com/line/jnotebook_reader
	```
</details>
<br>

## Notebook Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries and tools that work with or can be used within notebook files._

<details><summary><b><a href="https://github.com/jupyter/nbformat">nbformat</a></b> (🥇30 ·  ⭐ 200 · 📈) - Reference implementation of the Jupyter Notebook format. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbformat) (👨‍💻 75 · 🔀 140 · 📥 110 · 📦 200K · 📋 130 - 41% open · ⏱️ 20.03.2023):

	```
	git clone https://github.com/jupyter/nbformat
	```
- [PyPi](https://pypi.org/project/nbformat) (📥 14M / month):
	```
	pip install nbformat
	```
- [Conda](https://anaconda.org/conda-forge/nbformat) (📥 14M · ⏱️ 20.03.2023):
	```
	conda install -c conda-forge nbformat
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbclient">nbclient</a></b> (🥇29 ·  ⭐ 120) - A client library for executing notebooks. Formally nbconvert's.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbclient) (👨‍💻 34 · 🔀 46 · 📥 210 · 📦 95K · 📋 100 - 34% open · ⏱️ 11.03.2023):

	```
	git clone https://github.com/jupyter/nbclient
	```
- [PyPi](https://pypi.org/project/nbclient) (📥 10M / month):
	```
	pip install nbclient
	```
- [Conda](https://anaconda.org/conda-forge/nbclient) (📥 8.2M · ⏱️ 30.11.2022):
	```
	conda install -c conda-forge nbclient
	```
</details>
<details><summary><b><a href="https://github.com/fastai/nbdev">nbdev</a></b> (🥇25 ·  ⭐ 4.1K) - Create delightful python projects using Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastai/nbdev) (👨‍💻 38 · 🔀 420 · 📋 800 - 13% open · ⏱️ 24.03.2023):

	```
	git clone https://github.com/fastai/nbdev
	```
- [PyPi](https://pypi.org/project/nbdev) (📥 66K / month):
	```
	pip install nbdev
	```
</details>
<details><summary><b><a href="https://github.com/pixiedust/pixiedust">PixieDust</a></b> (🥇25 ·  ⭐ 1K · 💀) - Python Helper library for Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pixiedust/pixiedust) (👨‍💻 33 · 🔀 160 · 📦 250 · 📋 420 - 38% open · ⏱️ 16.02.2021):

	```
	git clone https://github.com/pixiedust/pixiedust
	```
- [PyPi](https://pypi.org/project/pixiedust) (📥 17K / month):
	```
	pip install pixiedust
	```
- [Conda](https://anaconda.org/conda-forge/pixiedust) (📥 44K · ⏱️ 06.02.2021):
	```
	conda install -c conda-forge pixiedust
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/repo2docker">repo2docker</a></b> (🥈23 ·  ⭐ 1.5K) - Turn repositories into Jupyter-enabled Docker images. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/repo2docker) (👨‍💻 120 · 🔀 310 · 📦 180 · 📋 500 - 30% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/jupyterhub/repo2docker
	```
- [PyPi](https://pypi.org/project/jupyter-repo2docker) (📥 2.8K / month):
	```
	pip install jupyter-repo2docker
	```
</details>
<details><summary><b><a href="https://github.com/computationalmodelling/nbval">nbval</a></b> (🥈23 ·  ⭐ 400) - A py.test plugin to validate Jupyter notebooks. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/computationalmodelling/nbval) (👨‍💻 33 · 🔀 46 · 📦 2.2K · 📋 100 - 36% open · ⏱️ 11.01.2023):

	```
	git clone https://github.com/computationalmodelling/nbval
	```
- [PyPi](https://pypi.org/project/nbval) (📥 130K / month):
	```
	pip install nbval
	```
- [Conda](https://anaconda.org/conda-forge/nbval) (📥 310K · ⏱️ 31.07.2020):
	```
	conda install -c conda-forge nbval
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter_client">Jupyter Client</a></b> (🥈23 ·  ⭐ 310) - Jupyter protocol client APIs. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter_client) (👨‍💻 130 · 🔀 250 · 📥 900 · 📋 350 - 44% open · ⏱️ 20.03.2023):

	```
	git clone https://github.com/jupyter/jupyter_client
	```
- [PyPi](https://pypi.org/project/jupyter-client) (📥 20M / month):
	```
	pip install jupyter-client
	```
</details>
<details><summary><b><a href="https://github.com/twosigma/beakerx">BeakerX</a></b> (🥈22 ·  ⭐ 2.7K · 💀) - Beaker Extensions for Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/twosigma/beakerx) (👨‍💻 43 · 🔀 370 · 📥 31 · 📋 4.5K - 7% open · ⏱️ 21.01.2021):

	```
	git clone https://github.com/twosigma/beakerx
	```
- [PyPi](https://pypi.org/project/beakerx) (📥 4.8K / month):
	```
	pip install beakerx
	```
- [Conda](https://anaconda.org/conda-forge/beakerx) (📥 580K · ⏱️ 03.11.2022):
	```
	conda install -c conda-forge beakerx
	```
- [NPM](https://www.npmjs.com/package/beakerx) (📥 260 / month):
	```
	npm install beakerx
	```
- [Docker Hub](https://hub.docker.com/r/beakerx/beakerx) (📥 250K · ⭐ 23 · ⏱️ 02.12.2018):
	```
	docker pull beakerx/beakerx
	```
</details>
<details><summary><b><a href="https://github.com/chmp/ipytest">ipytest</a></b> (🥈21 ·  ⭐ 250) - Pytest in IPython notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chmp/ipytest) (👨‍💻 5 · 🔀 19 · 📦 260 · 📋 55 - 3% open · ⏱️ 11.01.2023):

	```
	git clone https://github.com/chmp/ipytest
	```
- [PyPi](https://pypi.org/project/ipytest) (📥 13K / month):
	```
	pip install ipytest
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-sphinx">Jupyter Sphinx</a></b> (🥈20 ·  ⭐ 160 · 💤) - Sphinx extension for rendering of Jupyter interactive.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-sphinx) (👨‍💻 25 · 🔀 54 · 📋 140 - 37% open · ⏱️ 25.06.2022):

	```
	git clone https://github.com/jupyter/jupyter-sphinx
	```
- [PyPi](https://pypi.org/project/jupyter_sphinx) (📥 110K / month):
	```
	pip install jupyter_sphinx
	```
</details>
<details><summary><b><a href="https://github.com/nbQA-dev/nbQA">nbQA</a></b> (🥉19 ·  ⭐ 730) - Run any standard Python code quality tool on a Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbQA-dev/nbQA) (👨‍💻 23 · 🔀 35 · 📋 280 - 1% open · ⏱️ 30.03.2023):

	```
	git clone https://github.com/nbQA-dev/nbQA
	```
- [PyPi](https://pypi.org/project/nbqa) (📥 99K / month):
	```
	pip install nbqa
	```
</details>
<details><summary><b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥉18 ·  ⭐ 2.4K) - Interactive Parallel Computing in Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipython/ipyparallel) (👨‍💻 110 · 🔀 920 · 📋 340 - 15% open · ⏱️ 30.03.2023):

	```
	git clone https://github.com/ipython/ipyparallel
	```
- [PyPi](https://pypi.org/project/ipyparallel) (📥 190K / month):
	```
	pip install ipyparallel
	```
- [Conda](https://anaconda.org/conda-forge/ipyparallel) (📥 800K · ⏱️ 28.03.2023):
	```
	conda install -c conda-forge ipyparallel
	```
</details>
<details><summary><b><a href="https://github.com/ReviewNB/treon">treon</a></b> (🥉17 ·  ⭐ 280 · 💤) - Easy to use test framework for Jupyter Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ReviewNB/treon) (👨‍💻 5 · 🔀 22 · 📦 67 · 📋 13 - 23% open · ⏱️ 04.08.2022):

	```
	git clone https://github.com/ReviewNB/treon
	```
- [PyPi](https://pypi.org/project/treon) (📥 2.8K / month):
	```
	pip install treon
	```
</details>
<details><summary><b><a href="https://github.com/QuantEcon/sphinxcontrib-jupyter">sphinxcontrib.jupyter</a></b> (🥉17 ·  ⭐ 72 · 💀) - A Sphinx Extension for Generating Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/QuantEcon/sphinxcontrib-jupyter) (👨‍💻 13 · 🔀 23 · 📦 27 · 📋 180 - 48% open · ⏱️ 18.06.2020):

	```
	git clone https://github.com/QuantEcon/sphinxcontrib-jupyter
	```
- [PyPi](https://pypi.org/project/sphinxcontrib-jupyter) (📥 740 / month):
	```
	pip install sphinxcontrib-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/nteract/testbook">testbook</a></b> (🥉15 ·  ⭐ 350) - Unit test your Jupyter Notebooks the right way. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/testbook) (👨‍💻 15 · 🔀 36 · 📦 210 · 📋 91 - 48% open · ⏱️ 29.11.2022):

	```
	git clone https://github.com/nteract/testbook
	```
</details>
<details><summary><b><a href="https://github.com/tweag/jupyenv">JupyterWith</a></b> (🥉14 ·  ⭐ 440) - declarative and reproducible Jupyter environments - powered by Nix. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tweag/jupyenv) (👨‍💻 36 · 🔀 93 · 📋 170 - 14% open · ⏱️ 17.03.2023):

	```
	git clone https://github.com/tweag/jupyterWith
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-naas/naas">naas</a></b> (🥉14 ·  ⭐ 240) - Schedule notebooks, run them like APIs, expose securely your assets:.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/jupyter-naas/naas) (👨‍💻 18 · 🔀 22 · 📦 3 · 📋 160 - 22% open · ⏱️ 02.03.2023):

	```
	git clone https://github.com/jupyter-naas/naas
	```
- [PyPi](https://pypi.org/project/naas) (📥 2.5K / month):
	```
	pip install naas
	```
</details>
<details><summary><b><a href="https://github.com/treebeardtech/nbmake-action">nbmake-action</a></b> (🥉14 ·  ⭐ 150 · 💀) - GitHub Action for testing notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/treebeardtech/nbmake-action) (👨‍💻 2 · 🔀 6 · 📦 30 · ⏱️ 21.09.2021):

	```
	git clone https://github.com/treebeardtech/nbmake-action
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/nbopen">nbopen</a></b> (🥉13 ·  ⭐ 290) - Open a Jupyter notebook in the best available server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/takluyver/nbopen) (👨‍💻 11 · 🔀 55 · 📋 63 - 58% open · ⏱️ 15.09.2022):

	```
	git clone https://github.com/takluyver/nbopen
	```
- [PyPi](https://pypi.org/project/nbopen) (📥 820 / month):
	```
	pip install nbopen
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/jupyter_kernel_mgmt">Kernel Management</a></b> (🥉12 ·  ⭐ 14 · 💀) - Experimental new kernel management framework for.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/takluyver/jupyter_kernel_mgmt) (👨‍💻 74 · 🔀 8 · 📥 17 · 📋 25 - 44% open · ⏱️ 29.01.2020):

	```
	git clone https://github.com/takluyver/jupyter_kernel_mgmt
	```
- [PyPi](https://pypi.org/project/jupyter-kernel-mgmt) (📥 28 / month):
	```
	pip install jupyter-kernel-mgmt
	```
</details>
<details><summary><b><a href="https://github.com/datitran/jupyter2slides">jupyter2slides</a></b> (🥉11 ·  ⭐ 780 · 💀) - Cloud Native Presentation Slides with Jupyter Notebook +.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/datitran/jupyter2slides) (🔀 170 · 📋 15 - 73% open · ⏱️ 28.12.2018):

	```
	git clone https://github.com/datitran/jupyter2slides
	```
</details>
<details><summary><b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉11 ·  ⭐ 160 · 💀) - jupyter/ipython experiment containers for GPU and.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/stas00/ipyexperiments) (👨‍💻 3 · 🔀 11 · 📦 8 · ⏱️ 07.12.2021):

	```
	git clone https://github.com/stas00/ipyexperiments
	```
- [PyPi](https://pypi.org/project/ipyexperiments) (📥 130 / month):
	```
	pip install ipyexperiments
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyter-helpers">Jupyter Helpers</a></b> (🥉11 ·  ⭐ 45 · 💀) - A collection of helpers for Jupyter/IPython. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyter-helpers) (👨‍💻 2 · 🔀 3 · 📋 5 - 60% open · ⏱️ 31.07.2021):

	```
	git clone https://github.com/krassowski/jupyter-helpers
	```
- [PyPi](https://pypi.org/project/jupyter_helpers) (📥 140 / month):
	```
	pip install jupyter_helpers
	```
</details>
<details><summary><b><a href="https://github.com/Invictify/Jupter-Notebook-REST-API">Jupter-Notebook-REST-API</a></b> (🥉6 ·  ⭐ 66 · 💀) - Run your jupyter notebooks as a REST API endpoint... <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Invictify/Jupter-Notebook-REST-API) (👨‍💻 2 · 🔀 8 · ⏱️ 31.03.2020):

	```
	git clone https://github.com/Invictify/Jupter-Notebook-REST-API
	```
</details>
<br>

## JupyterLab Renderer

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that can render and display files of specific MIME types._

<details><summary><b><a href="https://github.com/plotly/jupyterlab-dash">JupyterLab Dash</a></b> (🥇20 ·  ⭐ 360 · 💀) - An Extension for the Interactive development of Dash apps in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/jupyterlab-dash) (👨‍💻 7 · 🔀 55 · 📦 350 · 📋 28 - 71% open · ⏱️ 19.05.2020):

	```
	git clone https://github.com/plotly/jupyterlab-dash
	```
- [PyPi](https://pypi.org/project/jupyterlab-dash) (📥 1.7K / month):
	```
	pip install jupyterlab-dash
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-dash) (📥 12K / month):
	```
	npm install jupyterlab-dash
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-latex">JupyterLab Latex</a></b> (🥈19 ·  ⭐ 540) - JupyterLab extension for live editing of LaTeX documents. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-latex) (👨‍💻 22 · 🔀 61 · 📦 5 · 📋 86 - 36% open · ⏱️ 18.11.2022):

	```
	git clone https://github.com/jupyterlab/jupyterlab-latex
	```
- [PyPi](https://pypi.org/project/jupyterlab_latex) (📥 3.2K / month):
	```
	pip install jupyterlab_latex
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/latex) (📥 1.1K / month):
	```
	npm install @jupyterlab/latex
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyter-renderers">JupyterLab Renderers</a></b> (🥈18 ·  ⭐ 460) - Renderers and renderer extensions for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyter-renderers) (👨‍💻 29 · 🔀 69 · 📦 3 · 📋 100 - 31% open · ⏱️ 16.03.2023):

	```
	git clone https://github.com/jupyterlab/jupyter-renderers
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/geojson-extension) (📥 1.9K / month):
	```
	npm install @jupyterlab/geojson-extension
	```
</details>
<details><summary><b><a href="https://github.com/QuantStack/jupyterlab-drawio">JupyterLab Drawio</a></b> (🥉17 ·  ⭐ 560 · 💀) - A standalone embedding of the FOSS drawio / mxgraph.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/QuantStack/jupyterlab-drawio) (👨‍💻 15 · 🔀 65 · 📦 13 · 📋 66 - 62% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/QuantStack/jupyterlab-drawio
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-drawio) (📥 3.5K / month):
	```
	npm install jupyterlab-drawio
	```
</details>
<details><summary><b><a href="https://github.com/quigleyj97/jupyterlab-spreadsheet">JupyterLab Spreadsheet</a></b> (🥉16 ·  ⭐ 180 · 💤) - JupyterLab plugin for viewing spreadsheets, such as.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/quigleyj97/jupyterlab-spreadsheet) (👨‍💻 4 · 🔀 14 · 📦 5 · 📋 23 - 21% open · ⏱️ 18.07.2022):

	```
	git clone https://github.com/quigleyj97/jupyterlab-spreadsheet
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-spreadsheet) (📥 2.2K / month):
	```
	npm install jupyterlab-spreadsheet
	```
</details>
<details><summary><b><a href="https://github.com/plotly/jupyterlab-chart-editor">JupyterLab Chart Editor</a></b> (🥉15 ·  ⭐ 210 · 💀) - JupyterLab extension for Plotly's react-chart-editor. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/plotly/jupyterlab-chart-editor) (👨‍💻 5 · 🔀 24 · 📦 6 · 📋 31 - 38% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/plotly/jupyterlab-chart-editor
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-chart-editor) (📥 1K / month):
	```
	npm install jupyterlab-chart-editor
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/jupyterlab_voyager">JupyterLab Voyager</a></b> (🥉12 ·  ⭐ 280 · 💀) - JupyterLab extension visualize data with Voyager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/jupyterlab_voyager) (👨‍💻 6 · 🔀 34 · 📦 2 · 📋 60 - 66% open · ⏱️ 14.08.2019):

	```
	git clone https://github.com/altair-viz/jupyterlab_voyager
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_voyager) (📥 83 / month):
	```
	npm install jupyterlab_voyager
	```
</details>
<br>

## JupyterLab Themes

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that can customize the appearance of JupyterLab._

<details><summary><b><a href="https://github.com/telamonian/theme-darcula">Darcula Theme</a></b> (🥇19 ·  ⭐ 180 · 💤) - A handsome Darcula theme for Jupyterlab. The first jlab.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/telamonian/theme-darcula) (👨‍💻 7 · 🔀 26 · 📦 1.2K · 📋 24 - 33% open · ⏱️ 20.07.2022):

	```
	git clone https://github.com/telamonian/theme-darcula
	```
- [NPM](https://www.npmjs.com/package/@telamonian/theme-darcula) (📥 580 / month):
	```
	npm install @telamonian/theme-darcula
	```
</details>
<details><summary><b><a href="https://github.com/AllanChain/jupyterlab-theme-solarized-dark">jupyterlab-theme-solarized-dark</a></b> (🥈14 ·  ⭐ 77) - JupyterLab 2.x Solarized Dark extension. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/AllanChain/jupyterlab-theme-solarized-dark) (👨‍💻 2 · 🔀 9 · 📦 2 · 📋 4 - 50% open · ⏱️ 04.02.2023):

	```
	git clone https://github.com/AllanChain/jupyterlab-theme-solarized-dark
	```
- [PyPi](https://pypi.org/project/jupyterlab_theme_solarized_dark) (📥 9.3K / month):
	```
	pip install jupyterlab_theme_solarized_dark
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-theme-solarized-dark) (📥 3K / month):
	```
	npm install jupyterlab-theme-solarized-dark
	```
</details>
<details><summary><b><a href="https://github.com/yeebc/jupyterlab-neon-theme">Neon Theme</a></b> (🥈13 ·  ⭐ 130 · 💤) - A flat, 80's neon inspired theme for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/yeebc/jupyterlab-neon-theme) (👨‍💻 4 · 🔀 8 · 📦 3 · 📋 13 - 15% open · ⏱️ 28.08.2022):

	```
	git clone https://github.com/yeebc/jupyterlab-neon-theme
	```
- [NPM](https://www.npmjs.com/package/@yeebc/jupyterlab_neon_theme) (📥 940 / month):
	```
	npm install @yeebc/jupyterlab_neon_theme
	```
</details>
<details><summary><b><a href="https://github.com/mohirio/jupyterlab-horizon-theme">Horizon Theme</a></b> (🥈13 ·  ⭐ 64) - VSCode Horizon Theme port for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mohirio/jupyterlab-horizon-theme) (👨‍💻 3 · 🔀 3 · 📦 2 · ⏱️ 05.12.2022):

	```
	git clone https://github.com/mohirio/jupyterlab-horizon-theme
	```
- [NPM](https://www.npmjs.com/package/@mohirio/jupyterlab-horizon-theme) (📥 2.1K / month):
	```
	npm install @mohirio/jupyterlab-horizon-theme
	```
</details>
<details><summary><b><a href="https://github.com/oriolmirosa/jupyterlab_materialdarker">Material Darker Theme</a></b> (🥉12 ·  ⭐ 140) - The Material Darker theme for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/oriolmirosa/jupyterlab_materialdarker) (👨‍💻 2 · 🔀 16 · 📦 7 · 📋 17 - 11% open · ⏱️ 16.12.2022):

	```
	git clone https://github.com/oriolmirosa/jupyterlab_materialdarker
	```
- [NPM](https://www.npmjs.com/package/@oriolmirosa/jupyterlab_materialdarker) (📥 440 / month):
	```
	npm install @oriolmirosa/jupyterlab_materialdarker
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-theme-toggle">Theme Toggle</a></b> (🥉10 ·  ⭐ 11 · 💀) - JupyterLab extension to toggle the theme in the Top Bar area. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-theme-toggle) (👨‍💻 2 · 🔀 3 · 📦 4 · 📋 3 - 66% open · ⏱️ 16.06.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-theme-toggle
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-theme-toggle) (📥 900 / month):
	```
	npm install jupyterlab-theme-toggle
	```
</details>
<details><summary><b><a href="https://github.com/Rahlir/theme-gruvbox">Gruvbox Theme</a></b> (🥉8 ·  ⭐ 48 · 💀) - Gruvbox dark theme for Jupyter Lab. Modeled on classic.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Rahlir/theme-gruvbox) (👨‍💻 3 · 🔀 9 · ⏱️ 12.04.2020):

	```
	git clone https://github.com/Rahlir/theme-gruvbox
	```
- [NPM](https://www.npmjs.com/package/@rahlir/theme-gruvbox) (📥 110 / month):
	```
	npm install @rahlir/theme-gruvbox
	```
</details>
<details><summary><b><a href="https://github.com/kenshohara/theme-nord-extension">Nord Theme</a></b> (🥉6 ·  ⭐ 24 · 💀) - JupyterLab - Nord Theme. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/kenshohara/theme-nord-extension) (🔀 1 · 📦 2 · 📋 5 - 20% open · ⏱️ 20.09.2020):

	```
	git clone https://github.com/kenshohara/theme-nord-extension
	```
- [NPM](https://www.npmjs.com/package/@kenshohara/theme-nord-extension) (📥 31 / month):
	```
	npm install @kenshohara/theme-nord-extension
	```
</details>
<br>

## JupyterLab Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of JupyterLab itself._

<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-git">JupyterLab Git</a></b> (🥇27 ·  ⭐ 1.2K) - A Git extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-git) (👨‍💻 86 · 🔀 260 · 📦 21 · 📋 550 - 16% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/jupyterlab/jupyterlab-git
	```
- [PyPi](https://pypi.org/project/jupyterlab-git) (📥 95K / month):
	```
	pip install jupyterlab-git
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-git) (📥 390K · ⏱️ 16.12.2022):
	```
	conda install -c conda-forge jupyterlab-git
	```
</details>
<details><summary><b><a href="https://github.com/elyra-ai/elyra">elyra</a></b> (🥇23 ·  ⭐ 1.6K) - Elyra extends JupyterLab Notebooks with an AI centric approach. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/elyra-ai/elyra) (👨‍💻 57 · 🔀 280 · 📦 45 · 📋 1.6K - 15% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/elyra-ai/elyra
	```
- [PyPi](https://pypi.org/project/elyra) (📥 2.4K / month):
	```
	pip install elyra
	```
- [Conda](https://anaconda.org/conda-forge/elyra) (📥 29K · ⏱️ 29.03.2023):
	```
	conda install -c conda-forge elyra
	```
</details>
<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥇21 ·  ⭐ 5.3K) - Streaming pivot visualization via WebAssembly. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 83 · 🔀 610 · 📦 8 · 📋 610 - 14% open · ⏱️ 25.03.2023):

	```
	git clone https://github.com/finos/perspective
	```
- [PyPi](https://pypi.org/project/perspective-python) (📥 3.3K / month):
	```
	pip install perspective-python
	```
- [NPM](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 1.3K / month):
	```
	npm install @finos/perspective-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/debugger">JupyterLab Debugger</a></b> (🥇20 ·  ⭐ 550 · 💀) - A visual debugger for Jupyter notebooks, consoles,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/debugger) (👨‍💻 11 · 🔀 38 · 📋 260 - 6% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/jupyterlab/debugger
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/debugger) (📥 97K / month):
	```
	npm install @jupyterlab/debugger
	```
</details>
<details><summary><b><a href="https://github.com/lckr/jupyterlab-variableInspector">Variable Inspector</a></b> (🥇19 ·  ⭐ 960) - Variable Inspector extension for Jupyterlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lckr/jupyterlab-variableInspector) (👨‍💻 19 · 🔀 83 · 📦 5 · 📋 160 - 24% open · ⏱️ 10.01.2023):

	```
	git clone https://github.com/lckr/jupyterlab-variableInspector
	```
- [NPM](https://www.npmjs.com/package/@lckr/jupyterlab_variableinspector) (📥 4.1K / month):
	```
	npm install @lckr/jupyterlab_variableinspector
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-github">JupyterLab GitHub</a></b> (🥇19 ·  ⭐ 350) - GitHub integration for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-github) (👨‍💻 16 · 🔀 91 · 📦 5 · 📋 58 - 36% open · ⏱️ 05.09.2022):

	```
	git clone https://github.com/jupyterlab/jupyterlab-github
	```
- [PyPi](https://pypi.org/project/jupyterlab-github) (📥 1.6K / month):
	```
	pip install jupyterlab-github
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/github) (📥 6.4K / month):
	```
	npm install @jupyterlab/github
	```
</details>
<details><summary><b><a href="https://github.com/finos/jupyterlab_templates">JupyterLab Templates</a></b> (🥇19 ·  ⭐ 320) - Support for jupyter notebook templates in jupyterlab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/jupyterlab_templates) (👨‍💻 17 · 🔀 59 · 📦 7 · 📋 85 - 7% open · ⏱️ 28.03.2023):

	```
	git clone https://github.com/jpmorganchase/jupyterlab_templates
	```
- [PyPi](https://pypi.org/project/jupyterlab_templates) (📥 7.9K / month):
	```
	pip install jupyterlab_templates
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_templates) (📥 4.2K / month):
	```
	npm install jupyterlab_templates
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask-labextension">dask-labextension</a></b> (🥇19 ·  ⭐ 290) - JupyterLab extension for Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-labextension) (👨‍💻 23 · 🔀 54 · 📦 2 · 📋 140 - 30% open · ⏱️ 19.02.2023):

	```
	git clone https://github.com/dask/dask-labextension
	```
- [PyPi](https://pypi.org/project/dask-labextension) (📥 8.1K / month):
	```
	pip install dask-labextension
	```
- [Conda](https://anaconda.org/conda-forge/dask-labextension) (📥 850K · ⏱️ 19.02.2023):
	```
	conda install -c conda-forge dask-labextension
	```
- [NPM](https://www.npmjs.com/package/dask-labextension) (📥 1.3K / month):
	```
	npm install dask-labextension
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/jupyterlab-sidecar">JupyterLab SideCar</a></b> (🥇19 ·  ⭐ 220) - A sidecar output widget for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/jupyterlab-sidecar) (👨‍💻 14 · 🔀 39 · 📦 6 · 📋 32 - 65% open · ⏱️ 10.12.2022):

	```
	git clone https://github.com/jupyter-widgets/jupyterlab-sidecar
	```
- [PyPi](https://pypi.org/project/sidecar) (📥 3.3K / month):
	```
	pip install sidecar
	```
- [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-sidecar) (📥 330 / month):
	```
	npm install @jupyter-widgets/jupyterlab-sidecar
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/spellchecker">JupyterLab Spellchecker</a></b> (🥇19 ·  ⭐ 170) - Spellchecker for JupyterLab notebook markdown cells.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/spellchecker) (👨‍💻 6 · 🔀 17 · 📦 3 · 📋 51 - 29% open · ⏱️ 08.02.2023):

	```
	git clone https://github.com/ijmbarr/jupyterlab_spellchecker
	```
- [NPM](https://www.npmjs.com/package/@ijmbarr/jupyterlab_spellchecker) (📥 1.4K / month):
	```
	npm install @ijmbarr/jupyterlab_spellchecker
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-toc">JupyterLab TOC</a></b> (🥈18 ·  ⭐ 730 · 💀) - Table of Contents extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-toc) (👨‍💻 14 · 🔀 100 · 📋 120 - 55% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-toc
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/toc) (📥 97K / month):
	```
	npm install @jupyterlab/toc
	```
</details>
<details><summary><b><a href="https://github.com/ryantam626/jupyterlab_code_formatter">Code Formatter</a></b> (🥈18 ·  ⭐ 670) - A universal code formatter for JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ryantam626/jupyterlab_code_formatter) (👨‍💻 39 · 🔀 50 · 📦 2 · 📋 170 - 19% open · ⏱️ 22.03.2023):

	```
	git clone https://github.com/ryantam626/jupyterlab_code_formatter
	```
- [PyPi](https://pypi.org/project/jupyterlab_code_formatter) (📥 52K / month):
	```
	pip install jupyterlab_code_formatter
	```
- [NPM](https://www.npmjs.com/package/@ryantam626/jupyterlab_code_formatter) (📥 3.2K / month):
	```
	npm install @ryantam626/jupyterlab_code_formatter
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/jupyterlab-nvdashboard">GPU Dashboards</a></b> (🥈18 ·  ⭐ 490) - A JupyterLab extension for displaying dashboards of GPU.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rapidsai/jupyterlab-nvdashboard) (👨‍💻 18 · 🔀 64 · 📦 2 · 📋 64 - 40% open · ⏱️ 15.02.2023):

	```
	git clone https://github.com/rapidsai/jupyterlab-nvdashboard
	```
- [PyPi](https://pypi.org/project/jupyterlab-nvdashboard) (📥 66K / month):
	```
	pip install jupyterlab-nvdashboard
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-nvdashboard) (📥 900 / month):
	```
	npm install jupyterlab-nvdashboard
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-google-drive">JupyterLab Google Drive</a></b> (🥈18 ·  ⭐ 390 · 💤) - Cloud storage for JupyterLab using Google Drive. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-google-drive) (👨‍💻 16 · 🔀 73 · 📦 4 · 📋 98 - 33% open · ⏱️ 28.04.2022):

	```
	git clone https://github.com/jupyterlab/jupyterlab-google-drive
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/google-drive) (📥 890 / month):
	```
	npm install @jupyterlab/google-drive
	```
</details>
<details><summary><b><a href="https://github.com/jwkvam/jupyterlab-vim">JupyterLab Vim</a></b> (🥈17 ·  ⭐ 940 · 💀) - Vim notebook cell bindings for JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jwkvam/jupyterlab-vim) (👨‍💻 8 · 🔀 72 · 📦 5 · 📋 100 - 57% open · ⏱️ 16.07.2019):

	```
	git clone https://github.com/jwkvam/jupyterlab-vim
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_vim) (📥 400 / month):
	```
	npm install jupyterlab_vim
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-system-monitor">JupyterLab System Monitor</a></b> (🥈16 ·  ⭐ 280 · 💀) - JupyterLab extension to display system metrics. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-system-monitor) (👨‍💻 7 · 🔀 29 · 📦 2 · 📋 44 - 52% open · ⏱️ 15.02.2022):

	```
	git clone https://github.com/jtpio/jupyterlab-system-monitor
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-system-monitor) (📥 4.1K / month):
	```
	npm install jupyterlab-system-monitor
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyterlab-go-to-definition">JupyterLab Go-To-Definition</a></b> (🥈16 ·  ⭐ 210 · 💀) - Navigate to variable's definition with a click in.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyterlab-go-to-definition) (👨‍💻 2 · 🔀 8 · 📦 15 · 📋 23 - 43% open · ⏱️ 28.07.2021):

	```
	git clone https://github.com/krassowski/jupyterlab-go-to-definition
	```
- [NPM](https://www.npmjs.com/package/@krassowski/jupyterlab_go_to_definition) (📥 6.8K / month):
	```
	npm install @krassowski/jupyterlab_go_to_definition
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-data-explorer">JupyterLab Data Explorer</a></b> (🥈16 ·  ⭐ 170 · 💀) - First class datasets in JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-data-explorer) (👨‍💻 9 · 🔀 34 · 📦 12 · 📋 92 - 63% open · ⏱️ 24.05.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-data-explorer
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/dataregistry-extension) (📥 160 / month):
	```
	npm install @jupyterlab/dataregistry-extension
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/ipylab">ipylab</a></b> (🥈16 ·  ⭐ 140) - Control JupyterLab from Python Notebooks with Jupyter Widgets. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/ipylab) (👨‍💻 7 · 🔀 11 · 📥 65 · 📦 2 · 📋 36 - 44% open · ⏱️ 30.03.2023):

	```
	git clone https://github.com/jtpio/ipylab
	```
- [PyPi](https://pypi.org/project/ipylab) (📥 22K / month):
	```
	pip install ipylab
	```
- [Conda](https://anaconda.org/conda-forge/ipylab) (📥 19K · ⏱️ 29.03.2023):
	```
	conda install -c conda-forge ipylab
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyterlab-lsp">JupyterLab LSP</a></b> (🥈16 ·  ⭐ 34) - Coding assistance for JupyterLab (code navigation + hover.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyterlab-lsp) (👨‍💻 46 · ⏱️ 02.01.2023):

	```
	git clone https://github.com/krassowski/jupyterlab-lsp
	```
- [NPM](https://www.npmjs.com/package/@krassowski/jupyterlab-lsp) (📥 9.2K / month):
	```
	npm install @krassowski/jupyterlab-lsp
	```
</details>
<details><summary><b><a href="https://github.com/chaoleili/jupyterlab_tensorboard">JupyterLab Tensorboard</a></b> (🥉15 ·  ⭐ 300 · 💤) - Tensorboard extension for jupyterlab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chaoleili/jupyterlab_tensorboard) (👨‍💻 7 · 🔀 33 · 📦 4 · 📋 28 - 64% open · ⏱️ 18.07.2022):

	```
	git clone https://github.com/chaoleili/jupyterlab_tensorboard
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_tensorboard) (📥 7.3K / month):
	```
	npm install jupyterlab_tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/deshaw/jupyterlab-execute-time">jupyterlab-execute-time</a></b> (🥉15 ·  ⭐ 260) - Execute Time Plugin for Jupyter Lab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/deshaw/jupyterlab-execute-time) (👨‍💻 13 · 🔀 36 · 📦 2 · 📋 44 - 15% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/deshaw/jupyterlab-execute-time
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-execute-time) (📥 2K / month):
	```
	npm install jupyterlab-execute-time
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/jupyter_bokeh">Jupyter Bokeh</a></b> (🥉15 ·  ⭐ 210) - An extension for rendering Bokeh content in JupyterLab notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/jupyter_bokeh) (👨‍💻 18 · 🔀 42 · 📦 2 · 📋 96 - 15% open · ⏱️ 14.03.2023):

	```
	git clone https://github.com/bokeh/jupyter_bokeh
	```
- [PyPi](https://pypi.org/project/jupyter-bokeh) (📥 41K / month):
	```
	pip install jupyter-bokeh
	```
- [NPM](https://www.npmjs.com/package/@bokeh/jupyter_bokeh) (📥 12K / month):
	```
	npm install @bokeh/jupyter_bokeh
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-celltags">jupyterlab-celltags</a></b> (🥉15 ·  ⭐ 110 · 💀) - A JupyterLab extension for notebook cell tags. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-celltags) (👨‍💻 10 · 🔀 26 · 📦 730 · 📋 18 - 61% open · ⏱️ 29.04.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-celltags
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-hdf5">JupyterLab HDF5</a></b> (🥉15 ·  ⭐ 100) - Open and explore HDF5 files in JupyterLab. Can handle very.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-hdf5) (👨‍💻 7 · 🔀 21 · 📦 2 · 📋 48 - 25% open · ⏱️ 22.03.2023):

	```
	git clone https://github.com/jupyterlab/jupyterlab-hdf5
	```
- [PyPi](https://pypi.org/project/jupyterlab_hdf) (📥 1K / month):
	```
	pip install jupyterlab_hdf
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/hdf5) (📥 960 / month):
	```
	npm install @jupyterlab/hdf5
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_iframe">JupyterLab IFrame</a></b> (🥉15 ·  ⭐ 91) - JupyterLab iframe widget. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_iframe) (👨‍💻 5 · 🔀 16 · 📦 6 · 📋 66 - 6% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/timkpaine/jupyterlab_iframe
	```
- [PyPi](https://pypi.org/project/jupyterlab_iframe) (📥 840 / month):
	```
	pip install jupyterlab_iframe
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_iframe) (📥 530 / month):
	```
	npm install jupyterlab_iframe
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/gather">nbgather</a></b> (🥉14 ·  ⭐ 470) - Spit shine for Jupyter notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/gather) (👨‍💻 13 · 🔀 31 · 📦 2 · 📋 27 - 37% open · ⏱️ 28.11.2022):

	```
	git clone https://github.com/microsoft/gather
	```
- [NPM](https://www.npmjs.com/package/nbgather) (📥 62 / month):
	```
	npm install nbgather
	```
</details>
<details><summary><b><a href="https://github.com/pbugnion/jupyterlab-sql">JupyterLab SQL</a></b> (🥉14 ·  ⭐ 390 · 💀) - SQL GUI for JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pbugnion/jupyterlab-sql) (👨‍💻 2 · 🔀 46 · 📋 75 - 50% open · ⏱️ 04.01.2020):

	```
	git clone https://github.com/pbugnion/jupyterlab-sql
	```
- [PyPi](https://pypi.org/project/jupyterlab_sql) (📥 500 / month):
	```
	pip install jupyterlab_sql
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/lantern">Lantern</a></b> (🥉14 ·  ⭐ 330) - Data exploration glue. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/lantern) (👨‍💻 3 · 🔀 20 · 📦 18 · 📋 200 - 5% open · ⏱️ 22.11.2022):

	```
	git clone https://github.com/timkpaine/lantern
	```
- [PyPi](https://pypi.org/project/pylantern) (📥 54 / month):
	```
	pip install pylantern
	```
</details>
<details><summary><b><a href="https://github.com/parente/jupyterlab-quickopen">JupyterLab Quickopen</a></b> (🥉14 ·  ⭐ 74 · 💀) - Quickly open a file in JupyterLab by typing part of.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/parente/jupyterlab-quickopen) (👨‍💻 5 · 🔀 8 · 📦 2 · ⏱️ 12.12.2021):

	```
	git clone https://github.com/parente/jupyterlab-quickopen
	```
- [PyPi](https://pypi.org/project/jupyterlab-quickopen) (📥 430 / month):
	```
	pip install jupyterlab-quickopen
	```
- [NPM](https://www.npmjs.com/package/@parente/jupyterlab-quickopen) (📥 76 / month):
	```
	npm install @parente/jupyterlab-quickopen
	```
</details>
<details><summary><b><a href="https://github.com/vatlab/jupyterlab-sos">jupyterlab-sos</a></b> (🥉14 ·  ⭐ 62) - Jupyterlab extension for SoS Polyglot Notebook and Workflow.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/jupyterlab-sos) (👨‍💻 4 · 🔀 4 · 📦 2 · 📋 59 - 13% open · ⏱️ 06.12.2022):

	```
	git clone https://github.com/vatlab/jupyterlab-sos
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-sos) (📥 25K · ⏱️ 07.12.2022):
	```
	conda install -c conda-forge jupyterlab-sos
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-sos) (📥 90 / month):
	```
	npm install jupyterlab-sos
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-shortcutui">JupyterLab Shortcutui</a></b> (🥉14 ·  ⭐ 54 · 💀) - A JupyterLab extension for managing keyboard shortcuts. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-shortcutui) (👨‍💻 8 · 🔀 14 · 📦 2 · 📋 13 - 53% open · ⏱️ 17.01.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-shortcutui
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/shortcutui) (📥 290 / month):
	```
	npm install @jupyterlab/shortcutui
	```
</details>
<details><summary><b><a href="https://github.com/aquirdTurtle/Collapsible_Headings">Collapsible Headings</a></b> (🥉13 ·  ⭐ 170 · 💀) - Implements Collapsible Headers for Jupyter Lab.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/aquirdTurtle/Collapsible_Headings) (👨‍💻 6 · 🔀 8 · 📦 2 · 📋 31 - 29% open · ⏱️ 22.05.2021):

	```
	git clone https://github.com/aquirdTurtle/Collapsible_Headings
	```
- [NPM](https://www.npmjs.com/package/@aquirdturtle/collapsible_headings) (📥 1K / month):
	```
	npm install @aquirdturtle/collapsible_headings
	```
</details>
<details><summary><b><a href="https://github.com/itsjafer/jupyterlab-sparkmonitor">jupyterlab-sparkmonitor</a></b> (🥉13 ·  ⭐ 91 · 💤) - JupyterLab extension that enables monitoring launched.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/itsjafer/jupyterlab-sparkmonitor) (👨‍💻 10 · 🔀 20 · 📋 16 - 50% open · ⏱️ 01.04.2022):

	```
	git clone https://github.com/itsjafer/jupyterlab-sparkmonitor
	```
- [PyPi](https://pypi.org/project/jupyterlab-sparkmonitor) (📥 6.5K / month):
	```
	pip install jupyterlab-sparkmonitor
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_sparkmonitor) (📥 49 / month):
	```
	npm install jupyterlab_sparkmonitor
	```
- [Docker Hub](https://hub.docker.com/r/itsjafer/sparkmonitor) (📥 320 · ⏱️ 02.06.2021):
	```
	docker pull itsjafer/sparkmonitor
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyterlab-kernelspy">JupyterLab Kernelspy</a></b> (🥉13 ·  ⭐ 68) - A Jupyter Lab extension for inspecting messages.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyterlab-kernelspy) (👨‍💻 4 · 🔀 9 · 📦 6 · 📋 13 - 15% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/jupyterlab-contrib/jupyterlab-kernelspy
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-kernelspy) (📥 360 / month):
	```
	npm install jupyterlab-kernelspy
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/jupyter-fs">jupyter-fs</a></b> (🥉12 ·  ⭐ 140) - A filesystem-like contents manager for multiple backends in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/jupyter-fs) (👨‍💻 10 · 🔀 26 · 📦 2 · 📋 60 - 26% open · ⏱️ 08.01.2023):

	```
	git clone https://github.com/jpmorganchase/jupyter-fs
	```
- [PyPi](https://pypi.org/project/jupyter-fs) (📥 280 / month):
	```
	pip install jupyter-fs
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-commenting">JupyterLab Commenting</a></b> (🥉12 ·  ⭐ 95 · 💀) - Commenting and annotation for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-commenting) (👨‍💻 10 · 🔀 23 · 📦 2 · 📋 34 - 70% open · ⏱️ 01.05.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-commenting
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/commenting-extension) (📥 78 / month):
	```
	npm install @jupyterlab/commenting-extension
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/nbcelltests">nbcelltests</a></b> (🥉12 ·  ⭐ 71) - Cell-by-cell testing for production Jupyter notebooks in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/nbcelltests) (👨‍💻 7 · 🔀 15 · 📋 120 - 26% open · ⏱️ 07.12.2022):

	```
	git clone https://github.com/jpmorganchase/nbcelltests
	```
- [PyPi](https://pypi.org/project/nbcelltests) (📥 37 / month):
	```
	pip install nbcelltests
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_celltests) (📥 33 / month):
	```
	npm install jupyterlab_celltests
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_autoversion">JupyterLab Autoversion</a></b> (🥉12 ·  ⭐ 62) - Automatically version jupyter notebooks in JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_autoversion) (👨‍💻 5 · 🔀 9 · 📋 33 - 12% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/timkpaine/jupyterlab_autoversion
	```
- [PyPi](https://pypi.org/project/jupyterlab_autoversion) (📥 83 / month):
	```
	pip install jupyterlab_autoversion
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_autoversion) (📥 37 / month):
	```
	npm install jupyterlab_autoversion
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-python-file">JupyterLab Python Files</a></b> (🥉12 ·  ⭐ 53 · 💀) - JupyterLab extension to create Python files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-python-file) (👨‍💻 4 · 🔀 11 · 📥 81 · 📦 2 · 📋 9 - 11% open · ⏱️ 27.08.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-python-file
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-python-file) (📥 280 / month):
	```
	npm install jupyterlab-python-file
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/knowledgelab">KnowledgeLab</a></b> (🥉12 ·  ⭐ 47) - KnowledgeRepo + JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/knowledgelab) (👨‍💻 3 · 🔀 6 · 📦 5 · 📋 27 - 11% open · ⏱️ 04.03.2023):

	```
	git clone https://github.com/timkpaine/knowledgelab
	```
- [PyPi](https://pypi.org/project/knowledgelab) (📥 8 / month):
	```
	pip install knowledgelab
	```
- [NPM](https://www.npmjs.com/package/knowledgelab) (📥 11 / month):
	```
	npm install knowledgelab
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Flake8</a></b> (🥉11 ·  ⭐ 53) - A jupyterlab extension to email notebooks directly from.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (👨‍💻 2 · 🔀 2 · 📋 36 - 11% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/timkpaine/jupyterlab_email
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-flake8) (📥 170 / month):
	```
	npm install jupyterlab-flake8
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_commands">jupyterlab_commands</a></b> (🥉11 ·  ⭐ 44) - Add arbitrary python commands to the jupyterlab.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_commands) (👨‍💻 2 · 🔀 5 · 📦 6 · 📋 24 - 8% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/timkpaine/jupyterlab_commands
	```
</details>
<details><summary><b><a href="https://github.com/mlshapiro/jupyterlab-flake8">jupyterlab-flake8</a></b> (🥉10 ·  ⭐ 110 · 💀) - Jupyterlab python linter for notebooks and text files.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mlshapiro/jupyterlab-flake8) (👨‍💻 5 · 🔀 9 · 📦 2 · 📋 39 - 15% open · ⏱️ 16.09.2021):

	```
	git clone https://github.com/mlshapiro/jupyterlab-flake8
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-flake8) (📥 170 / month):
	```
	npm install jupyterlab-flake8
	```
</details>
<details><summary><b><a href="https://github.com/ReviewNB/jupyterlab-gitplus">jupyterlab-gitplus</a></b> (🥉10 ·  ⭐ 100) - JupyterLab extension to create GitHub commits & pull.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/ReviewNB/jupyterlab-gitplus) (👨‍💻 2 · 🔀 7 · 📦 2 · 📋 11 - 18% open · ⏱️ 28.02.2023):

	```
	git clone https://github.com/ReviewNB/jupyterlab-gitplus
	```
- [PyPi](https://pypi.org/project/jupyterlab_gitplus) (📥 430 / month):
	```
	pip install jupyterlab_gitplus
	```
- [NPM](https://www.npmjs.com/package/@reviewnb/jupyterlab_gitplus) (📥 140 / month):
	```
	npm install @reviewnb/jupyterlab_gitplus
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-python-bytecode">JupyterLab Bytecode</a></b> (🥉10 ·  ⭐ 60 · 💀) - JupyterLab extension to explore CPython Bytecode. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-python-bytecode) (👨‍💻 2 · 🔀 6 · 📦 2 · 📋 5 - 40% open · ⏱️ 16.10.2020):

	```
	git clone https://github.com/jtpio/jupyterlab-python-bytecode
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-python-bytecode) (📥 21 / month):
	```
	npm install jupyterlab-python-bytecode
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Email</a></b> (🥉10 ·  ⭐ 53) - A jupyterlab extension to email notebooks directly from.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (👨‍💻 2 · 🔀 2 · 📋 36 - 11% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/timkpaine/jupyterlab_email
	```
- [PyPi](https://pypi.org/project/jupyterlab_email) (📥 74 / month):
	```
	pip install jupyterlab_email
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_email) (📥 24 / month):
	```
	npm install jupyterlab_email
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-topbar">JupyterLab Top Bar</a></b> (🥉10 ·  ⭐ 4 · 💀) - JupyterLab Top Bar extension. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-topbar) (👨‍💻 4 · 🔀 2 · ⏱️ 07.12.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-topbar
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-topbar-extension) (📥 4K / month):
	```
	npm install jupyterlab-topbar-extension
	```
</details>
<details><summary><b><a href="https://github.com/manuzhang/jupyterlab_spark">JupyterLab Spark</a></b> (🥉9 ·  ⭐ 9 · 💀) - Spark Application UI extension for JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/manuzhang/jupyterlab_spark) (👨‍💻 2 · 🔀 2 · 📦 2 · 📋 5 - 40% open · ⏱️ 05.09.2021):

	```
	git clone https://github.com/manuzhang/jupyterlab_spark
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_spark) (📥 50 / month):
	```
	npm install jupyterlab_spark
	```
</details>
<details><summary><b><a href="https://github.com/gavincyi/jupyterlab-executor">jupyterlab-executor</a></b> (🥉8 ·  ⭐ 6 · 💀) - JupyterLab extension to execute the scripts from the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gavincyi/jupyterlab-executor) (👨‍💻 2 · 📥 3 · 📦 2 · ⏱️ 24.03.2021):

	```
	git clone https://github.com/gavincyi/jupyterlab-executor
	```
- [PyPi](https://pypi.org/project/jupyterlab-executor) (📥 51 / month):
	```
	pip install jupyterlab-executor
	```
- [NPM](https://www.npmjs.com/package/@gavincyi/jupyterlab-executor) (📥 18 / month):
	```
	npm install @gavincyi/jupyterlab-executor
	```
</details>
<br>

## JupyterHub Authenticators

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Authentication modules that manage and control how users can access the JupyterHub deployment._

<details><summary><b><a href="https://github.com/jupyterhub/ldapauthenticator">LDAP Authenticator</a></b> (🥇24 ·  ⭐ 190 · 💀) - LDAP Authenticator Plugin for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ldapauthenticator) (👨‍💻 31 · 🔀 160 · 📦 110 · 📋 140 - 41% open · ⏱️ 27.06.2021):

	```
	git clone https://github.com/jupyterhub/ldapauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-ldapauthenticator) (📥 8.2K / month):
	```
	pip install jupyterhub-ldapauthenticator
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-ldapauthenticator) (📥 30K · ⏱️ 28.08.2020):
	```
	conda install -c conda-forge jupyterhub-ldapauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/oauthenticator">OAuthenticator</a></b> (🥇22 ·  ⭐ 360) - OAuth + JupyterHub Authenticator = OAuthenticator. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/oauthenticator) (👨‍💻 110 · 🔀 320 · 📦 330 · 📋 240 - 13% open · ⏱️ 14.03.2023):

	```
	git clone https://github.com/jupyterhub/oauthenticator
	```
- [PyPi](https://pypi.org/project/oauthenticator) (📥 19K / month):
	```
	pip install oauthenticator
	```
- [Conda](https://anaconda.org/conda-forge/oauthenticator) (📥 34K · ⏱️ 08.09.2022):
	```
	conda install -c conda-forge oauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nativeauthenticator">Native Authenticator</a></b> (🥈19 ·  ⭐ 61) - JupyterHub-native user authenticator. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nativeauthenticator) (👨‍💻 21 · 🔀 58 · 📦 51 · 📋 96 - 27% open · ⏱️ 20.03.2023):

	```
	git clone https://github.com/jupyterhub/nativeauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-nativeauthenticator) (📥 5.7K / month):
	```
	pip install jupyterhub-nativeauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/ltiauthenticator">LTI Authenticator</a></b> (🥈19 ·  ⭐ 57) - A JupyterHub authenticator for LTI. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ltiauthenticator) (👨‍💻 15 · 🔀 42 · 📦 89 · 📋 41 - 4% open · ⏱️ 30.03.2023):

	```
	git clone https://github.com/jupyterhub/ltiauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-ltiauthenticator) (📥 1.8K / month):
	```
	pip install jupyterhub-ltiauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/firstuseauthenticator">First Use Authenticator</a></b> (🥈16 ·  ⭐ 45 · 💀) - JupyterHub Authenticator that lets users set.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/firstuseauthenticator) (👨‍💻 12 · 🔀 26 · 📦 75 · 📋 23 - 26% open · ⏱️ 28.10.2021):

	```
	git clone https://github.com/jupyterhub/firstuseauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-firstuseauthenticator) (📥 4.2K / month):
	```
	pip install jupyterhub-firstuseauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/mogthesprog/jwtauthenticator">JWT Authenticator</a></b> (🥈14 ·  ⭐ 46 · 💀) - A Token Authenticator for JupyterHub. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mogthesprog/jwtauthenticator) (👨‍💻 7 · 🔀 38 · 📦 12 · 📋 17 - 52% open · ⏱️ 13.02.2019):

	```
	git clone https://github.com/mogthesprog/jwtauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-jwtauthenticator) (📥 320 / month):
	```
	pip install jupyterhub-jwtauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/dummyauthenticator">dummyauthenticator</a></b> (🥈14 ·  ⭐ 28 · 💀) - A Dummy JupyterHub Authenticator to make testing easy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/dummyauthenticator) (🔀 14 · 📦 110 · 📋 7 - 71% open · ⏱️ 12.02.2021):

	```
	git clone https://github.com/jupyterhub/dummyauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-dummyauthenticator) (📥 3.8K / month):
	```
	pip install jupyterhub-dummyauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/HewlettPackard/jupyterhub-samlauthenticator">SAML Authenticator</a></b> (🥉13 ·  ⭐ 34 · 💤) - jupyterhub-samlauthenticator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HewlettPackard/jupyterhub-samlauthenticator) (👨‍💻 7 · 🔀 21 · 📥 13 · 📋 30 - 53% open · ⏱️ 21.03.2022):

	```
	git clone https://github.com/HewlettPackard/jupyterhub-samlauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-samlauthenticator) (📥 360 / month):
	```
	pip install jupyterhub-samlauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nullauthenticator">Null Authenticator</a></b> (🥉13 ·  ⭐ 8 · 💤) - Null Authenticator for JupyterHub instances that should.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nullauthenticator) (👨‍💻 7 · 🔀 9 · 📦 93 · ⏱️ 17.05.2022):

	```
	git clone https://github.com/jupyterhub/nullauthenticator
	```
- [PyPi](https://pypi.org/project/nullauthenticator) (📥 1.7K / month):
	```
	pip install nullauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/cwaldbieser/jhub_remote_user_authenticator">Remote User Auth</a></b> (🥉11 ·  ⭐ 37 · 💀) - REMOTE_USER authenticator for Jupyterhub. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/cwaldbieser/jhub_remote_user_authenticator) (👨‍💻 5 · 🔀 27 · 📋 19 - 42% open · ⏱️ 16.04.2019):

	```
	git clone https://github.com/cwaldbieser/jhub_remote_user_authenticator
	```
- [PyPi](https://pypi.org/project/jhub_remote_user_authenticator) (📥 280 / month):
	```
	pip install jhub_remote_user_authenticator
	```
</details>
<details><summary><b><a href="https://github.com/cwaldbieser/jhub_cas_authenticator">CAS Authenticator</a></b> (🥉11 ·  ⭐ 21) - CAS authenticator for Jupyterhub. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/cwaldbieser/jhub_cas_authenticator) (👨‍💻 4 · 🔀 11 · 📋 13 - 7% open · ⏱️ 17.03.2023):

	```
	git clone https://github.com/cwaldbieser/jhub_cas_authenticator
	```
- [PyPi](https://pypi.org/project/jhub_cas_authenticator) (📥 300 / month):
	```
	pip install jhub_cas_authenticator
	```
</details>
<details><summary><b><a href="https://github.com/ucphhpc/jhub-authenticators">Remote Authenticator</a></b> (🥉11 ·  ⭐ 1) - A collection of JupyterHub Authenticators, including.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ucphhpc/jhub-authenticators) (👨‍💻 5 · 🔀 1 · 📦 1 · ⏱️ 08.03.2023):

	```
	git clone https://github.com/rasmunk/jhub-authenticators
	```
- [PyPi](https://pypi.org/project/jhub-authenticators) (📥 480 / month):
	```
	pip install jhub-authenticators
	```
</details>
<details><summary><b><a href="https://github.com/thedataincubator/jupyterhub-hashauthenticator">Hash Authenticator</a></b> (🥉10 ·  ⭐ 4) - Authenticate users with passwords generated from their.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/thedataincubator/jupyterhub-hashauthenticator) (👨‍💻 3 · 🔀 3 · ⏱️ 06.01.2023):

	```
	git clone https://github.com/thedataincubator/jupyterhub-hashauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-hashauthenticator) (📥 32 / month):
	```
	pip install jupyterhub-hashauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/kerberosauthenticator">Keberos Authenticator</a></b> (🥉8 ·  ⭐ 10 · 💀) - A JupyterHub authenticator using Kerberos. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/kerberosauthenticator) (👨‍💻 2 · 🔀 5 · 📋 5 - 60% open · ⏱️ 16.07.2019):

	```
	git clone https://github.com/jupyterhub/kerberosauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-kerberosauthenticator) (📥 140 / month):
	```
	pip install jupyterhub-kerberosauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/andreas-h/sshauthenticator">SSH Authenticator</a></b> (🥉6 ·  ⭐ 6 · 💀) - A simple SSH authenticator for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/andreas-h/sshauthenticator) (🔀 1 · ⏱️ 03.09.2019):

	```
	git clone https://github.com/andreas-h/sshauthenticator
	```
</details>
<br>

## JupyterHub Spawners

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Spawner modules that start, monitor, and stop single-user notebook servers._

<details><summary><b><a href="https://github.com/jupyterhub/batchspawner">BatchSpawner</a></b> (🥇22 ·  ⭐ 150) - Custom Spawner for Jupyterhub to start servers in batch scheduled.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/batchspawner) (👨‍💻 42 · 🔀 110 · 📦 25 · 📋 130 - 40% open · ⏱️ 01.03.2023):

	```
	git clone https://github.com/jupyterhub/batchspawner
	```
- [PyPi](https://pypi.org/project/batchspawner) (📥 3.4K / month):
	```
	pip install batchspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/dockerspawner">DockerSpawner</a></b> (🥈21 ·  ⭐ 440) - Spawns JupyterHub single user servers in Docker containers. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/dockerspawner) (👨‍💻 66 · 🔀 290 · 📦 150 · 📋 260 - 8% open · ⏱️ 15.03.2023):

	```
	git clone https://github.com/jupyterhub/dockerspawner
	```
- [PyPi](https://pypi.org/project/dockerspawner) (📥 11K / month):
	```
	pip install dockerspawner
	```
- [Conda](https://anaconda.org/conda-forge/dockerspawner) (📥 16K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge dockerspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/kubespawner">KubeSpawner</a></b> (🥈20 ·  ⭐ 450) - Kubernetes spawner for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/kubespawner) (👨‍💻 78 · 🔀 270 · 📦 130 · 📋 310 - 19% open · ⏱️ 23.03.2023):

	```
	git clone https://github.com/jupyterhub/kubespawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-kubespawner) (📥 57K / month):
	```
	pip install jupyterhub-kubespawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/systemdspawner">SystemdSpawner</a></b> (🥉17 ·  ⭐ 87) - Spawn JupyterHub single-user notebook servers with systemd. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/systemdspawner) (👨‍💻 18 · 🔀 42 · 📦 23 · 📋 61 - 47% open · ⏱️ 11.01.2023):

	```
	git clone https://github.com/jupyterhub/systemdspawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-systemdspawner) (📥 2.9K / month):
	```
	pip install jupyterhub-systemdspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/wrapspawner">WrapSpawner</a></b> (🥉14 ·  ⭐ 56 · 💤) - Mechanism for runtime configuration of spawners for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/wrapspawner) (👨‍💻 16 · 🔀 51 · 📦 9 · 📋 32 - 56% open · ⏱️ 04.03.2022):

	```
	git clone https://github.com/jupyterhub/wrapspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/sudospawner">SudoSpawner</a></b> (🥉14 ·  ⭐ 45 · 💀) - Spawn JupyterHub single-user servers with sudo. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/sudospawner) (👨‍💻 14 · 🔀 38 · 📦 52 · 📋 38 - 44% open · ⏱️ 10.09.2021):

	```
	git clone https://github.com/jupyterhub/sudospawner
	```
- [PyPi](https://pypi.org/project/sudospawner) (📥 1.1K / month):
	```
	pip install sudospawner
	```
</details>
<details><summary><b><a href="https://github.com/uktrade/fargatespawner">FargateSpawner</a></b> (🥉13 ·  ⭐ 38 · 💀) - Spawns JupyterHub single user servers in Docker containers.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/uktrade/fargatespawner) (👨‍💻 3 · 🔀 21 · 📦 4 · 📋 11 - 54% open · ⏱️ 28.06.2020):

	```
	git clone https://github.com/uktrade/fargatespawner
	```
- [PyPi](https://pypi.org/project/fargatespawner) (📥 200 / month):
	```
	pip install fargatespawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/yarnspawner">YarnSpawner</a></b> (🥉10 ·  ⭐ 19 · 💀) - Spawn JupyterHub single user notebook servers in Hadoop/YARN.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/yarnspawner) (👨‍💻 2 · 🔀 12 · 📋 10 - 60% open · ⏱️ 16.07.2019):

	```
	git clone https://github.com/jupyterhub/yarnspawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-yarnspawner) (📥 38 / month):
	```
	pip install jupyterhub-yarnspawner
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-yarnspawner) (📥 33K · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge jupyterhub-yarnspawner
	```
</details>
<br>

## Jupyter Components

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Core components of the Jupyter architecture._

<details><summary><b><a href="https://github.com/ipython/ipython">ipython</a></b> (🥇35 ·  ⭐ 16K) - Official repository for IPython itself. Other repos in the IPython.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython/ipython) (👨‍💻 940 · 🔀 4.2K · 📥 320K · 📦 380K · 📋 7.1K - 21% open · ⏱️ 30.03.2023):

	```
	git clone https://github.com/ipython/ipython
	```
- [PyPi](https://pypi.org/project/ipython) (📥 22M / month):
	```
	pip install ipython
	```
- [Conda](https://anaconda.org/conda-forge/ipython) (📥 18M · ⏱️ 30.03.2023):
	```
	conda install -c conda-forge ipython
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter_server">jupyter_server</a></b> (🥉24 ·  ⭐ 380) - The backendi.e. core services, APIs, and REST endpointsto.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter_server) (👨‍💻 500 · 🔀 210 · 📥 1.3K · 📋 380 - 32% open · ⏱️ 27.03.2023):

	```
	git clone https://github.com/jupyter-server/jupyter_server
	```
- [PyPi](https://pypi.org/project/jupyter_server) (📥 14M / month):
	```
	pip install jupyter_server
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_server) (📥 4.5M · ⏱️ 17.03.2023):
	```
	conda install -c conda-forge jupyter_server
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-packaging">jupyter-packaging</a></b> (🥉18 ·  ⭐ 60) - Tools to help build and install Jupyter Python packages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-packaging) (👨‍💻 30 · 🔀 45 · 📥 50 · 📋 40 - 25% open · ⏱️ 07.03.2023):

	```
	git clone https://github.com/jupyter/jupyter-packaging
	```
- [PyPi](https://pypi.org/project/jupyter-packaging) (📥 360K / month):
	```
	pip install jupyter-packaging
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-packaging) (📥 450K · ⏱️ 25.08.2022):
	```
	conda install -c conda-forge jupyter-packaging
	```
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jupyter/qtconsole">qtconsole</a></b> (🥇32 ·  ⭐ 360) - Jupyter Qt Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/qtconsole) (👨‍💻 120 · 🔀 180 · 📦 130K · 📋 320 - 31% open · ⏱️ 28.03.2023):

	```
	git clone https://github.com/jupyter/qtconsole
	```
- [PyPi](https://pypi.org/project/qtconsole) (📥 3.5M / month):
	```
	pip install qtconsole
	```
- [Conda](https://anaconda.org/conda-forge/qtconsole) (📥 3.7M · ⏱️ 13.03.2023):
	```
	conda install -c conda-forge qtconsole
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/panel">panel</a></b> (🥈29 ·  ⭐ 2.7K) - A high-level app and dashboarding solution for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/panel) (👨‍💻 120 · 🔀 320 · 📦 6.2K · 📋 2.3K - 28% open · ⏱️ 27.03.2023):

	```
	git clone https://github.com/holoviz/panel
	```
- [PyPi](https://pypi.org/project/panel) (📥 440K / month):
	```
	pip install panel
	```
- [Conda](https://anaconda.org/conda-forge/panel) (📥 910K · ⏱️ 04.03.2023):
	```
	conda install -c conda-forge panel
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter_console">jupyter-console</a></b> (🥉22 ·  ⭐ 220) - Jupyter Terminal Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter_console) (👨‍💻 60 · 🔀 140 · 📥 190 · 📋 150 - 40% open · ⏱️ 06.03.2023):

	```
	git clone https://github.com/jupyter/jupyter_console
	```
- [PyPi](https://pypi.org/project/jupyter-console) (📥 5.1M / month):
	```
	pip install jupyter-console
	```
</details>
<details><summary><b><a href="https://github.com/abhishekkrthakur/colabcode">colabcode</a></b> (🥉19 ·  ⭐ 1.9K · 💀) - Run VSCode (codeserver) on Google Colab or Kaggle Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/abhishekkrthakur/colabcode) (👨‍💻 8 · 🔀 250 · 📦 99 · 📋 77 - 57% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/abhishekkrthakur/colabcode
	```
- [PyPi](https://pypi.org/project/colabcode) (📥 4K / month):
	```
	pip install colabcode
	```
</details>

---

## 相关资源

- [**Python资源汇集列表**](https://github.com/HanXinzi-AI/awesome-python-resources): 周更新的各种应用方向与主题的资源汇集列表
- [**python机器学习资源大全**](https://github.com/HanXinzi-AI/awesome-python-machine-learning-resources): 周更新的各种python机器学习资源汇集列表
- [**Jupyter及相关工具资源大全**](https://github.com/HanXinzi-AI/awesome-jupyter-resources): 周更新的各种Jupyter及相关工具资源汇集列表
- [**NLP项目和资源大全**](https://github.com/HanXinzi-AI/awesome-NLP-resources): 周更新的各种NLP板块涉及的项目和工具资源汇集列表
- [**CV项目和资源大全**](https://github.com/HanXinzi-AI/awesome-computer-vision-resources): 周更新的各种CV板块涉及的项目和工具资源汇集列表