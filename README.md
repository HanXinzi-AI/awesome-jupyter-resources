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

本资源清单包含270个jupyter相关的开源工具资源，这些热门工具总共分成13个不同的子板块，这些项目目前在github上已经收到250K个点赞。所有的工具资源每周会自动从GitHub和工具维护平台采集信息，并更新排行展示。本清单参考[best-of模板](https://github.com/best-of-lists/best-of)完成，内容参考了[awesome-jupyter](https://github.com/markusschanta/awesome-jupyter)，欢迎大家提PR丰富本清单。
## 目录

- [Notebook环境](#Notebook环境) _14 个项目_
- [交互式小部件和可视化](#交互式小部件和可视化) _49 个项目_
- [Jupyter拓展](#Jupyter拓展) _23 个项目_
- [Jupyter-magic拓展](#Jupyter-magic拓展) _10 个项目_
- [Jupyter内核](#Jupyter内核) _36 个项目_
- [Jupyter-Notebook分享与格式转换](#Jupyter-Notebook分享与格式转换) _23 个项目_
- [Jupyter-Notebook工具](#Jupyter-Notebook工具) _24 个项目_
- [JupyterLab渲染器](#JupyterLab渲染器) _7 个项目_
- [JupyterLab主题](#JupyterLab主题) _8 个项目_
- [JupyterLab扩展](#JupyterLab扩展) _50 个项目_
- [JupyterHub认证](#JupyterHub认证) _15 个项目_
- [JupyterHub容器等](#JupyterHub容器等) _8 个项目_
- [Jupyter组件](#Jupyter组件) _3 个项目_
- [Others](#Others) _4 个项目_

## 图标解释
- 🥇🥈🥉&nbsp; 综合项目质量分
- ⭐️&nbsp; github上star的数量
- 🐣&nbsp; 小于6个月的新项目
- 💤&nbsp; 非活跃项目(6个月未更新)
- 💀&nbsp; 沉寂项目(12个月未更新)
- 📈📉&nbsp; 项目趋势(向上or向下)
- ➕&nbsp; 最近添加的项目
- ❗️&nbsp; 警告(例如 项目没有license)
- 👨‍💻&nbsp; 项目的开发贡献者数量
- 🔀&nbsp; 项目被fork的数量
- 📋&nbsp; 项目issue的数量
- ⏱️&nbsp; 项目包上次更新时间
- 📥&nbsp; 工具库被下载次数
- 📦&nbsp; 项目依赖的工具库数量

<br>

## Notebook环境

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_支持Jupyter笔记本的开发环境。_

<details><summary><b><a href="https://github.com/jupyter/notebook">Jupyter</a></b> (🥇37 ·  ⭐ 9.6K) - Jupyter Interactive Notebook. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/notebook) (👨‍💻 570 · 🔀 3.5K · 📥 3.6K · 📦 130K · 📋 4.3K - 46% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/jupyter/notebook
	```
- [PyPi](https://pypi.org/project/notebook) (📥 14M / month):
	```
	pip install notebook
	```
- [Conda](https://anaconda.org/conda-forge/jupyter) (📥 1.7M · ⏱️ 18.11.2021):
	```
	conda install -c conda-forge jupyter
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/datascience-notebook) (📥 26M · ⭐ 890 · ⏱️ 21.12.2021):
	```
	docker pull jupyter/datascience-notebook
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab">JupyterLab</a></b> (🥇35 ·  ⭐ 12K) - JupyterLab计算环境。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab) (👨‍💻 460 · 🔀 2.1K · 📥 21K · 📦 54K · 📋 6.3K - 30% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab
	```
- [PyPi](https://pypi.org/project/jupyterlab) (📥 1.3M / month):
	```
	pip install jupyterlab
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab) (📥 5M · ⏱️ 10.12.2021):
	```
	conda install -c conda-forge jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyterhub">JupyterHub</a></b> (🥈25 ·  ⭐ 6.8K) - Jupyter笔记本电脑的多用户服务器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyterhub/jupyterhub) (👨‍💻 260 · 🔀 1.6K · 📦 1.6K · 📋 2K - 8% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/jupyterhub/jupyterhub
	```
- [PyPi](https://pypi.org/project/jupyterhub) (📥 230K / month):
	```
	pip install jupyterhub
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub) (📥 480K · ⏱️ 22.12.2021):
	```
	conda install -c conda-forge jupyterhub
	```
- [Docker Hub](https://hub.docker.com/r/jupyterhub/jupyterhub) (📥 2.4M · ⭐ 300 · ⏱️ 22.12.2021):
	```
	docker pull jupyterhub/jupyterhub
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/docker-stacks">Docker Stacks</a></b> (🥈25 ·  ⭐ 6.7K) - 包含Jupyter应用程序的即可运行的Docker映像。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/docker-stacks) (👨‍💻 210 · 🔀 2.4K · 📋 710 - 10% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/jupyter/docker-stacks
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/scipy-notebook) (📥 78M · ⭐ 330 · ⏱️ 21.12.2021):
	```
	docker pull jupyter/scipy-notebook
	```
</details>
<details><summary><b><a href="https://github.com/nteract/nteract">nteract</a></b> (🥈25 ·  ⭐ 5.7K) - 交互式计算套件<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/nteract) (👨‍💻 170 · 🔀 520 · 📥 1.3M · 📋 1.7K - 9% open · ⏱️ 03.11.2021):

	```
	git clone https://github.com/nteract/nteract
	```
- [PyPi](https://pypi.org/project/nteract_on_jupyter) (📥 3.2K / month):
	```
	pip install nteract_on_jupyter
	```
</details>
<details><summary><b><a href="https://github.com/googledatalab/datalab">DataLab</a></b> (🥈24 ·  ⭐ 970) - 面向大数据的交互式工具和开发人员经验。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/googledatalab/datalab) (👨‍💻 52 · 🔀 240 · 📋 890 - 25% open · ⏱️ 16.08.2021):

	```
	git clone https://github.com/googledatalab/datalab
	```
- [PyPi](https://pypi.org/project/datalab) (📥 1.3M / month):
	```
	pip install datalab
	```
</details>
<details><summary><b><a href="https://github.com/vatlab/sos">sos</a></b> (🥉21 ·  ⭐ 210 · 💤) - 用于日常数据分析的SoS工作流系统。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/sos) (👨‍💻 33 · 🔀 28 · 📦 1.5K · 📋 1.4K - 4% open · ⏱️ 24.05.2021):

	```
	git clone https://github.com/vatlab/SOS
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/ml-workspace">ML Workspace</a></b> (🥉20 ·  ⭐ 2.4K) - 基于Web的多合一IDE，专门用于机器学习和数据任务。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ml-tooling/ml-workspace) (👨‍💻 10 · 🔀 300 · 📋 74 - 5% open · ⏱️ 22.11.2021):

	```
	git clone https://github.com/ml-tooling/ml-workspace
	```
- [Docker Hub](https://hub.docker.com/r/mltooling/ml-workspace) (📥 500K · ⭐ 20 · ⏱️ 13.07.2021):
	```
	docker pull mltooling/ml-workspace
	```
</details>
<details><summary><b><a href="https://github.com/nteract/hydrogen">Hydrogen</a></b> (🥉19 ·  ⭐ 3.8K) - 交互运行代码，检查数据并作图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nteract/hydrogen) (👨‍💻 88 · 🔀 300 · 📋 1.2K - 12% open · ⏱️ 16.10.2021):

	```
	git clone https://github.com/nteract/hydrogen
	```
</details>
<details><summary><b><a href="https://github.com/Kaggle/docker-python">docker-python</a></b> (🥉19 ·  ⭐ 2K) - Kaggle Python Docker映像。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Kaggle/docker-python) (👨‍💻 140 · 🔀 760 · 📋 280 - 3% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/kaggle/docker-python
	```
- [Docker Hub](https://hub.docker.com/r/kaggle/python) (📥 190K · ⭐ 160 · ⏱️ 29.11.2021):
	```
	docker pull kaggle/python
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/ml-hub">ML Hub</a></b> (🥉18 ·  ⭐ 200) - 机器学习团队的多用户开发平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ml-tooling/ml-hub) (👨‍💻 7 · 🔀 46 · 📥 1.7K · 📋 26 - 57% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/ml-tooling/ml-hub
	```
- [Docker Hub](https://hub.docker.com/r/mltooling/ml-hub) (📥 44K · ⭐ 5 · ⏱️ 18.02.2020):
	```
	docker pull mltooling/ml-hub
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/retrolab">jupyterlab-classic</a></b> (🥉17 ·  ⭐ 220) - 下一代老式笔记本用户UI界面。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/retrolab) (👨‍💻 14 · 🔀 35 · 📥 300 · 📦 42 · 📋 120 - 35% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-classic
	```
- [PyPi](https://pypi.org/project/jupyterlab-classic):
	```
	pip install jupyterlab-classic
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/vscode-jupyter">VSCode Jupyter</a></b> (🥉16 ·  ⭐ 500) - VS Code Jupyter extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/vscode-jupyter) (👨‍💻 240 · 🔀 96 · 📋 6.6K - 9% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/microsoft/vscode-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/iot-salzburg/gpu-jupyter">gpu-jupyter</a></b> (🥉14 ·  ⭐ 290) - 充分利用Jupyterlab的灵活性。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iot-salzburg/gpu-jupyter) (👨‍💻 10 · 🔀 100 · 📋 45 - 13% open · ⏱️ 22.11.2021):

	```
	git clone https://github.com/iot-salzburg/gpu-jupyter
	```
</details>
<br>

## 交互式小部件和可视化

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_提供交互式UI小部件和可视化工具的扩展。_

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-ml-python#data-visualization">best-of-ml-python - Data Visualization</a></b>  - Python-based data visualization libraries.

<details><summary><b><a href="https://github.com/bokeh/bokeh">bokeh</a></b> (🥇31 ·  ⭐ 16K) - 浏览器中的Python交互式数据可视化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 590 · 🔀 3.8K · 📦 42K · 📋 6.8K - 10% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh) (📥 2.1M / month):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 6.3M · ⏱️ 22.11.2021):
	```
	conda install -c conda-forge bokeh
	```
</details>
<details><summary><b><a href="https://github.com/pandas-profiling/pandas-profiling">pandas-profiling</a></b> (🥇30 ·  ⭐ 8.3K) - 从pandas DataFrame创建HTML分析报告。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pandas-profiling/pandas-profiling) (👨‍💻 83 · 🔀 1.2K · 📦 6.2K · 📋 530 - 18% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/pandas-profiling/pandas-profiling
	```
- [PyPi](https://pypi.org/project/pandas-profiling):
	```
	pip install pandas-profiling
	```
- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 180K · ⏱️ 28.09.2021):
	```
	conda install -c conda-forge pandas-profiling
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipywidgets">ipywidgets</a></b> (🥇30 ·  ⭐ 2.4K) - Interactive Widgets for the Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipywidgets) (👨‍💻 190 · 🔀 760 · 📦 2.9K · 📋 1.7K - 31% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/jupyter-widgets/ipywidgets
	```
- [PyPi](https://pypi.org/project/ipywidgets):
	```
	pip install ipywidgets
	```
- [Conda](https://anaconda.org/conda-forge/ipywidgets) (📥 4.2M · ⏱️ 04.11.2021):
	```
	conda install -c conda-forge ipywidgets
	```
- [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 130K / month):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥇29 ·  ⭐ 1.2K) - Jupyter-Leaflet.js桥接。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 73 · 🔀 300 · 📦 1.3K · 📋 460 - 37% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/jupyter-widgets/ipyleaflet
	```
- [PyPi](https://pypi.org/project/ipyleaflet) (📥 57K / month):
	```
	pip install ipyleaflet
	```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 780K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge ipyleaflet
	```
- [NPM](https://www.npmjs.com/package/jupyter-leaflet) (📥 47K / month):
	```
	npm install jupyter-leaflet
	```
</details>
<details><summary><b><a href="https://github.com/matplotlib/ipympl">jupyter-matplotlib</a></b> (🥇28 ·  ⭐ 1.2K) - Matplotlib Jupyter集成。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/matplotlib/ipympl) (👨‍💻 25 · 🔀 170 · 📦 2.3K · 📋 220 - 42% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/matplotlib/ipympl
	```
- [PyPi](https://pypi.org/project/ipympl):
	```
	pip install ipympl
	```
- [NPM](https://www.npmjs.com/package/jupyter-matplotlib) (📥 53K / month):
	```
	npm install jupyter-matplotlib
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈26 ·  ⭐ 3.2K) - 用于IPython / Jupyter笔记本的绘图库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 55 · 🔀 430 · 📦 28 · 📋 550 - 35% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/bqplot/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 910K · ⏱️ 01.10.2021):
	```
	conda install -c conda-forge bqplot
	```
- [NPM](https://www.npmjs.com/package/bqplot) (📥 26K / month):
	```
	npm install bqplot
	```
</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipyvolume">ipyvolume</a></b> (🥈26 ·  ⭐ 1.7K) - 基于IPython的Jupyter笔记本中用于Python的3d绘图<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maartenbreddels/ipyvolume) (👨‍💻 39 · 🔀 210 · 📦 640 · 📋 290 - 55% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/maartenbreddels/ipyvolume
	```
- [PyPi](https://pypi.org/project/ipyvolume) (📥 28K / month):
	```
	pip install ipyvolume
	```
- [Conda](https://anaconda.org/conda-forge/ipyvolume) (📥 330K · ⏱️ 20.04.2021):
	```
	conda install -c conda-forge ipyvolume
	```
- [NPM](https://www.npmjs.com/package/ipyvolume) (📥 3.1K / month):
	```
	npm install ipyvolume
	```
</details>
<details><summary><b><a href="https://github.com/nteract/papermill">papermill</a></b> (🥈25 ·  ⭐ 4.5K) - 参数化，执行和分析笔记本。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/papermill) (👨‍💻 96 · 🔀 340 · 📦 1.8K · 📋 330 - 30% open · ⏱️ 11.12.2021):

	```
	git clone https://github.com/nteract/papermill
	```
- [PyPi](https://pypi.org/project/papermill) (📥 380K / month):
	```
	pip install papermill
	```
- [Conda](https://anaconda.org/conda-forge/papermill) (📥 210K · ⏱️ 21.10.2021):
	```
	conda install -c conda-forge papermill
	```
</details>
<details><summary><b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥈25 ·  ⭐ 2.9K) - Visualizer for Pandas Data Structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/man-group/dtale) (👨‍💻 19 · 🔀 220 · 📦 270 · 📋 440 - 8% open · ⏱️ 18.12.2021):

	```
	git clone https://github.com/man-group/dtale
	```
- [PyPi](https://pypi.org/project/dtale) (📥 49K / month):
	```
	pip install dtale
	```
- [Conda](https://anaconda.org/conda-forge/dtale) (📥 100K · ⏱️ 18.11.2021):
	```
	conda install -c conda-forge dtale
	```
</details>
<details><summary><b><a href="https://github.com/plotly/jupyter-dash">jupyter-dash</a></b> (🥈24 ·  ⭐ 630 · 💤) - 在Jupyter Notebook和JupyterLab中开发Dash应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/jupyter-dash) (👨‍💻 3 · 🔀 170 · 📥 65 · 📦 1.1K · 📋 47 - 68% open · ⏱️ 22.01.2021):

	```
	git clone https://github.com/plotly/jupyter-dash
	```
- [PyPi](https://pypi.org/project/jupyter-dash) (📥 43K / month):
	```
	pip install jupyter-dash
	```
</details>
<details><summary><b><a href="https://github.com/martinRenou/ipycanvas">ipycanvas</a></b> (🥈24 ·  ⭐ 510) - Jupyter中的交互式画布。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/martinRenou/ipycanvas) (👨‍💻 14 · 🔀 40 · 📦 330 · 📋 97 - 35% open · ⏱️ 01.12.2021):

	```
	git clone https://github.com/martinRenou/ipycanvas
	```
- [PyPi](https://pypi.org/project/ipycanvas) (📥 11K / month):
	```
	pip install ipycanvas
	```
- [Conda](https://anaconda.org/conda-forge/ipycanvas) (📥 35K · ⏱️ 01.12.2021):
	```
	conda install -c conda-forge ipycanvas
	```
</details>
<details><summary><b><a href="https://github.com/cytoscape/ipycytoscape">ipycytoscape</a></b> (🥈23 ·  ⭐ 170) - Cytoscape Jupyter小部件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/cytoscape/ipycytoscape) (👨‍💻 29 · 🔀 46 · 📥 3 · 📦 55 · 📋 140 - 38% open · ⏱️ 01.12.2021):

	```
	git clone https://github.com/QuantStack/ipycytoscape
	```
- [Conda](https://anaconda.org/conda-forge/ipycytoscape) (📥 26K · ⏱️ 10.05.2021):
	```
	conda install -c conda-forge ipycytoscape
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/facets">facets-overview</a></b> (🥈21 ·  ⭐ 6.7K · 💤) - 机器学习数据集的可视化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/facets) (👨‍💻 28 · 🔀 820 · 📦 92 · 📋 150 - 50% open · ⏱️ 06.05.2021):

	```
	git clone https://github.com/pair-code/facets
	```
- [PyPi](https://pypi.org/project/facets-overview):
	```
	pip install facets-overview
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥈21 ·  ⭐ 780) - Jupyter-Three.js桥接。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter-widgets/pythreejs) (👨‍💻 29 · 🔀 160 · 📦 19 · 📋 210 - 31% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/jupyter-widgets/pythreejs
	```
- [PyPi](https://pypi.org/project/pythreejs):
	```
	pip install pythreejs
	```
- [Conda](https://anaconda.org/conda-forge/pythreejs) (📥 360K · ⏱️ 02.03.2021):
	```
	conda install -c conda-forge pythreejs
	```
- [NPM](https://www.npmjs.com/package/jupyter-threejs) (📥 5.9K / month):
	```
	npm install jupyter-threejs
	```
</details>
<details><summary><b><a href="https://github.com/quantopian/qgrid">qgrid</a></b> (🥈20 ·  ⭐ 2.8K · 💀) - 用于排序，过滤和编辑DataFrame的交互式工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/qgrid) (👨‍💻 30 · 🔀 370 · 📦 1 · 📋 270 - 54% open · ⏱️ 07.04.2020):

	```
	git clone https://github.com/quantopian/qgrid
	```
- [PyPi](https://pypi.org/project/qgrid):
	```
	pip install qgrid
	```
- [Conda](https://anaconda.org/conda-forge/qgrid) (📥 330K · ⏱️ 04.03.2021):
	```
	conda install -c conda-forge qgrid
	```
- [NPM](https://www.npmjs.com/package/qgrid) (📥 760 / month):
	```
	npm install qgrid
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥈20 ·  ⭐ 620) - What-If工具的源代码/网页/演示。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/what-if-tool) (👨‍💻 20 · 🔀 120 · 📋 94 - 51% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/PAIR-code/what-if-tool
	```
- [PyPi](https://pypi.org/project/witwidget) (📥 7.2K / month):
	```
	pip install witwidget
	```
- [NPM](https://www.npmjs.com/package/wit-widget) (📥 4K / month):
	```
	npm install wit-widget
	```
</details>
<details><summary><b><a href="https://github.com/mariobuikhuizen/ipyvuetify">ipyvuetify</a></b> (🥈20 ·  ⭐ 240) - 基于vuetify UI组件的Jupyter小部件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mariobuikhuizen/ipyvuetify) (👨‍💻 10 · 🔀 37 · 📦 4 · 📋 150 - 24% open · ⏱️ 16.12.2021):

	```
	git clone https://github.com/mariobuikhuizen/ipyvuetify
	```
- [PyPi](https://pypi.org/project/ipyvuetify) (📥 42K / month):
	```
	pip install ipyvuetify
	```
- [Conda](https://anaconda.org/conda-forge/ipyvuetify) (📥 67K · ⏱️ 06.08.2021):
	```
	conda install -c conda-forge ipyvuetify
	```
</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipywebrtc">ipywebrtc</a></b> (🥈20 ·  ⭐ 200 · 💤) - 适用于Jupyter笔记本/实验室的WebRTC。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maartenbreddels/ipywebrtc) (👨‍💻 9 · 🔀 30 · 📦 400 · 📋 48 - 58% open · ⏱️ 29.03.2021):

	```
	git clone https://github.com/maartenbreddels/ipywebrtc
	```
- [PyPi](https://pypi.org/project/ipywebrtc):
	```
	pip install ipywebrtc
	```
- [Conda](https://anaconda.org/conda-forge/ipywebrtc) (📥 230K · ⏱️ 29.03.2021):
	```
	conda install -c conda-forge ipywebrtc
	```
- [NPM](https://www.npmjs.com/package/jupyter-webrtc) (📥 310 / month):
	```
	npm install jupyter-webrtc
	```
</details>
<details><summary><b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥈19 ·  ⭐ 590 · 💤) - 使用Mapbox GL JS可视化Python Jupyter笔记本中的数据。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mapbox/mapboxgl-jupyter) (👨‍💻 21 · 🔀 120 · 📦 120 · 📋 98 - 31% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/mapbox/mapboxgl-jupyter
	```
- [PyPi](https://pypi.org/project/mapboxgl):
	```
	pip install mapboxgl
	```
</details>
<details><summary><b><a href="https://github.com/mariobuikhuizen/ipyvue">ipyvue</a></b> (🥈19 ·  ⭐ 36) - Vue库的Jupyter小部件基础。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mariobuikhuizen/ipyvue) (👨‍💻 3 · 🔀 10 · 📦 16 · 📋 6 - 33% open · ⏱️ 10.12.2021):

	```
	git clone https://github.com/mariobuikhuizen/ipyvue
	```
- [PyPi](https://pypi.org/project/ipyvue) (📥 42K / month):
	```
	pip install ipyvue
	```
- [Conda](https://anaconda.org/conda-forge/ipyvue) (📥 40K · ⏱️ 28.10.2021):
	```
	conda install -c conda-forge ipyvue
	```
</details>
<details><summary><b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉18 ·  ⭐ 730 · 💀) - Jupyter中的Google地图。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pbugnion/gmaps) (👨‍💻 16 · 🔀 140 · 📦 1 · 📋 200 - 31% open · ⏱️ 22.07.2019):

	```
	git clone https://github.com/pbugnion/gmaps
	```
- [PyPi](https://pypi.org/project/gmaps) (📥 11K / month):
	```
	pip install gmaps
	```
- [Conda](https://anaconda.org/conda-forge/gmaps) (📥 250K · ⏱️ 02.08.2019):
	```
	conda install -c conda-forge gmaps
	```
- [NPM](https://www.npmjs.com/package/jupyter-gmaps) (📥 1.9K / month):
	```
	npm install jupyter-gmaps
	```
</details>
<details><summary><b><a href="https://github.com/QuantStack/ipysheet">ipysheet</a></b> (🥉18 ·  ⭐ 460) - Jupyter Handsontable集成。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QuantStack/ipysheet) (👨‍💻 10 · 🔀 57 · 📦 3 · 📋 110 - 50% open · ⏱️ 14.12.2021):

	```
	git clone https://github.com/QuantStack/ipysheet
	```
- [PyPi](https://pypi.org/project/ipysheet):
	```
	pip install ipysheet
	```
- [Conda](https://anaconda.org/conda-forge/ipysheet) (📥 41K · ⏱️ 11.08.2021):
	```
	conda install -c conda-forge ipysheet
	```
- [NPM](https://www.npmjs.com/package/ipysheet) (📥 3.1K / month):
	```
	npm install ipysheet
	```
</details>
<details><summary><b><a href="https://github.com/lgpage/nbtutor">nbtutor</a></b> (🥉18 ·  ⭐ 390) - 可视化Jupyter Notebook单元中的Python代码执行（逐行）。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lgpage/nbtutor) (👨‍💻 3 · 🔀 35 · 📦 23 · 📋 31 - 58% open · ⏱️ 29.07.2021):

	```
	git clone https://github.com/lgpage/nbtutor
	```
- [Conda](https://anaconda.org/conda-forge/nbtutor) (📥 94K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge nbtutor
	```
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉18 ·  ⭐ 320) - 适用于Vega和Vega-Lite的IPython / Jupyter笔记本模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 10 · 🔀 52 · 📋 92 - 11% open · ⏱️ 02.12.2021):

	```
	git clone https://github.com/vega/ipyvega
	```
- [PyPi](https://pypi.org/project/vega) (📥 20K / month):
	```
	pip install vega
	```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 470K · ⏱️ 18.11.2021):
	```
	conda install -c conda-forge vega
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair_viewer">Altair Viewer</a></b> (🥉18 ·  ⭐ 49) - 用于Altair和Vega-Lite可视化的查看器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair_viewer) (👨‍💻 3 · 🔀 7 · 📋 6 - 33% open · ⏱️ 19.12.2021):

	```
	git clone https://github.com/altair-viz/altair_viewer
	```
- [PyPi](https://pypi.org/project/altair_viewer) (📥 160K / month):
	```
	pip install altair_viewer
	```
</details>
<details><summary><b><a href="https://github.com/InsightSoftwareConsortium/itkwidgets">itkwidgets</a></b> (🥉17 ·  ⭐ 400) - 交互式Jupyter小部件，以可视化图像，点集等。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/InsightSoftwareConsortium/itkwidgets) (👨‍💻 20 · 🔀 48 · 📥 64 · 📋 170 - 41% open · ⏱️ 17.09.2021):

	```
	git clone https://github.com/InsightSoftwareConsortium/itkwidgets
	```
- [PyPi](https://pypi.org/project/itkwidgets) (📥 4.9K / month):
	```
	pip install itkwidgets
	```
- [NPM](https://www.npmjs.com/package/itkwidgets) (📥 2K / month):
	```
	npm install itkwidgets
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/tributary">tributary</a></b> (🥉17 ·  ⭐ 290) - 在Python中流式反应图和数据流图。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/tributary) (👨‍💻 7 · 🔀 25 · 📦 15 · 📋 80 - 12% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/timkpaine/tributary
	```
- [PyPi](https://pypi.org/project/tributary):
	```
	pip install tributary
	```
- [Conda](https://anaconda.org/conda-forge/tributary) (📥 15K · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge tributary
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/ipydagred3">ipydagred3</a></b> (🥉17 ·  ⭐ 28) - ipywidgets库，用于在其中绘制有向无环图。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/ipydagred3) (👨‍💻 3 · 🔀 5 · 📦 8 · 📋 19 - 26% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/timkpaine/ipydagred3
	```
- [PyPi](https://pypi.org/project/ipydagred3):
	```
	pip install ipydagred3
	```
- [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 130K / month):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/vidartf/ipydatawidgets">ipydatawidgets</a></b> (🥉17 ·  ⭐ 25 · 💤) - 一组小部件，以帮助促进大型数据集的重用。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/vidartf/ipydatawidgets) (👨‍💻 5 · 🔀 7 · 📦 410 · 📋 9 - 44% open · ⏱️ 04.01.2021):

	```
	git clone https://github.com/vidartf/ipydatawidgets
	```
- [PyPi](https://pypi.org/project/ipydatawidgets) (📥 42K / month):
	```
	pip install ipydatawidgets
	```
- [Conda](https://anaconda.org/conda-forge/ipydatawidgets) (📥 120K · ⏱️ 06.01.2021):
	```
	conda install -c conda-forge ipydatawidgets
	```
</details>
<details><summary><b><a href="https://github.com/mwouts/itables">itables</a></b> (🥉16 ·  ⭐ 220 · 💤) - Jupyter中的交互式表格。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/itables) (👨‍💻 3 · 🔀 20 · 📦 85 · 📋 23 - 47% open · ⏱️ 04.02.2021):

	```
	git clone https://github.com/mwouts/itables
	```
- [PyPi](https://pypi.org/project/itables):
	```
	pip install itables
	```
</details>
<details><summary><b><a href="https://github.com/igvteam/igv-jupyter">igv.js widget</a></b> (🥉16 ·  ⭐ 140) - 集成了igv.js的Jupyter Notebook扩展。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/igvteam/igv-jupyter) (👨‍💻 4 · 🔀 14 · 📦 6 · ⏱️ 22.11.2021):

	```
	git clone https://github.com/igvteam/igv-jupyter
	```
- [PyPi](https://pypi.org/project/igv-jupyter) (📥 180 / month):
	```
	pip install igv-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/ipyregulartable">ipyregulartable</a></b> (🥉16 ·  ⭐ 53) - Jupyter中的高性能，可编辑，可样式化的数据表。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/ipyregulartable) (👨‍💻 4 · 🔀 9 · 📦 8 · 📋 24 - 37% open · ⏱️ 11.12.2021):

	```
	git clone https://github.com/jpmorganchase/ipyregulartable
	```
- [PyPi](https://pypi.org/project/ipyregulartable):
	```
	pip install ipyregulartable
	```
- [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 130K / month):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/vidartf/ipyscales">ipyscales</a></b> (🥉16 ·  ⭐ 13 · 💤) - 用于度量的小部件库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vidartf/ipyscales) (👨‍💻 4 · 🔀 3 · 📦 49 · 📋 6 - 33% open · ⏱️ 05.01.2021):

	```
	git clone https://github.com/vidartf/ipyscales
	```
- [PyPi](https://pypi.org/project/ipyscales) (📥 46 / month):
	```
	pip install ipyscales
	```
- [Conda](https://anaconda.org/conda-forge/ipyscales) (📥 51K · ⏱️ 06.01.2021):
	```
	conda install -c conda-forge ipyscales
	```
</details>
<details><summary><b><a href="https://github.com/OpenGeoscience/geonotebook">geonotebook</a></b> (🥉15 ·  ⭐ 1K · 💀) - Jupyter笔记本扩展，用于地理空间可视化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/OpenGeoscience/geonotebook) (👨‍💻 9 · 🔀 140 · 📋 83 - 44% open · ⏱️ 21.01.2019):

	```
	git clone https://github.com/OpenGeoscience/geonotebook
	```
- [Docker Hub](https://hub.docker.com/r/geonotebook/geonotebook) (📥 130K · ⭐ 6 · ⏱️ 21.01.2019):
	```
	docker pull geonotebook/geonotebook
	```
</details>
<details><summary><b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉15 ·  ⭐ 450 · 💀) - Jupyter / IPython Notebook的Dragndrop数据透视表和图表。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nicolaskruchten/jupyter_pivottablejs) (👨‍💻 3 · 🔀 61 · 📦 210 · 📋 56 - 28% open · ⏱️ 04.12.2018):

	```
	git clone https://github.com/nicolaskruchten/jupyter_pivottablejs
	```
- [PyPi](https://pypi.org/project/pivottablejs):
	```
	pip install pivottablejs
	```
</details>
<details><summary><b><a href="https://github.com/evidentlyai/evidently">evidently</a></b> (🥉14 ·  ⭐ 1.8K) - 交互式报告，可在分析过程中分析机器学习模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/evidentlyai/evidently) (👨‍💻 10 · 🔀 150 · 📋 62 - 56% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/evidentlyai/evidently
	```
</details>
<details><summary><b><a href="https://github.com/QuantStack/ipytree">ipytree</a></b> (🥉14 ·  ⭐ 87) - 使用Jupyter-widgets协议和jsTree的Tree Widget。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QuantStack/ipytree) (👨‍💻 8 · 🔀 23 · 📋 29 - 55% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/QuantStack/ipytree
	```
- [PyPi](https://pypi.org/project/ipytree):
	```
	pip install ipytree
	```
- [Conda](https://anaconda.org/conda-forge/ipytree) (📥 28K · ⏱️ 03.03.2021):
	```
	conda install -c conda-forge ipytree
	```
</details>
<details><summary><b><a href="https://github.com/nipy/niwidgets">niwidgets</a></b> (🥉14 ·  ⭐ 70 · 💀) - 适用于Jupyter笔记本的Neuroimaging小部件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nipy/niwidgets) (👨‍💻 16 · 🔀 33 · 📦 27 · 📋 34 - 50% open · ⏱️ 24.03.2020):

	```
	git clone https://github.com/nipy/niwidgets
	```
- [PyPi](https://pypi.org/project/niwidgets):
	```
	pip install niwidgets
	```
</details>
<details><summary><b><a href="https://github.com/spacetelescope/jdaviz">jdaviz</a></b> (🥉14 ·  ⭐ 33) - Jupyter平台中的JWST天文数据分析工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/spacetelescope/jdaviz) (👨‍💻 24 · 🔀 25 · 📋 480 - 44% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/spacetelescope/jdaviz
	```
- [PyPi](https://pypi.org/project/jdaviz):
	```
	pip install jdaviz
	```
</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipymaterialui">ipymaterialui</a></b> (🥉13 ·  ⭐ 74 · 💀) - 基于React Material UI组件的Jupyter小部件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maartenbreddels/ipymaterialui) (👨‍💻 3 · 🔀 14 · 📦 4 · 📋 10 - 70% open · ⏱️ 29.10.2019):

	```
	git clone https://github.com/maartenbreddels/ipymaterialui
	```
- [PyPi](https://pypi.org/project/ipymaterialui) (📥 55 / month):
	```
	pip install ipymaterialui
	```
- [NPM](https://www.npmjs.com/package/jupyter-materialui) (📥 120 / month):
	```
	npm install jupyter-materialui
	```
</details>
<details><summary><b><a href="https://github.com/CermakM/jupyter-datatables">Jupyter DataTables</a></b> (🥉11 ·  ⭐ 140 · 💀) - 利用pandas DataFrames的Jupyter Notebook扩展。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CermakM/jupyter-datatables) (👨‍💻 4 · 🔀 14 · 📋 28 - 46% open · ⏱️ 11.12.2019):

	```
	git clone https://github.com/CermakM/jupyter-datatables
	```
- [PyPi](https://pypi.org/project/jupyter-datatables) (📥 360 / month):
	```
	pip install jupyter-datatables
	```
</details>
<details><summary><b><a href="https://github.com/leifwalsh/perfume">perfume</a></b> (🥉10 ·  ⭐ 33 · 💀) - Jupyter中的交互式性能基准测试。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/leifwalsh/perfume) (👨‍💻 3 · 🔀 3 · 📋 6 - 33% open · ⏱️ 31.10.2020):

	```
	git clone https://github.com/leifwalsh/perfume
	```
- [PyPi](https://pypi.org/project/perfume-bench) (📥 18 / month):
	```
	pip install perfume-bench
	```
</details>
<details><summary><b><a href="https://github.com/asvcode/Vision_UI">Vision UI</a></b> (🥉9 ·  ⭐ 250 · 💀) - Fastai的UI视觉界面-现在与Google兼容。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/asvcode/Vision_UI) (👨‍💻 3 · 🔀 32 · 📋 3 - 33% open · ⏱️ 05.07.2020):

	```
	git clone https://github.com/asvcode/Vision_UI
	```
</details>
<details><summary><b><a href="https://github.com/Yomguithereal/ipysigma">ipysigma</a></b> (🥉9 ·  ⭐ 31 · 💀) - 一个自定义的Jupyter小部件库，用于使用sigma.js显示图形。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Yomguithereal/ipysigma) (👨‍💻 3 · 🔀 4 · 📋 5 - 60% open · ⏱️ 30.06.2020):

	```
	git clone https://github.com/Yomguithereal/ipysigma
	```
- [PyPi](https://pypi.org/project/ipysigma) (📥 13 / month):
	```
	pip install ipysigma
	```
- [NPM](https://www.npmjs.com/package/ipysigma) (📥 7 / month):
	```
	npm install ipysigma
	```
</details>
<details><summary><b><a href="https://github.com/GianniBalistreri/easyexplore">easyexplore</a></b> (🥉9 ·  ⭐ 3) - 用于在Python中轻松有效地进行数据探索的工具箱。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/GianniBalistreri/easyexplore) (👨‍💻 3 · 🔀 2 · 📦 1 · ⏱️ 04.06.2021):

	```
	git clone https://github.com/GianniBalistreri/easyexplore
	```
- [PyPi](https://pypi.org/project/easyexplore) (📥 55 / month):
	```
	pip install easyexplore
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/ipyp5">ipyp5</a></b> (🥉8 ·  ⭐ 30 · 💀) - p5.j​​s Jupyter小部件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/ipyp5) (👨‍💻 2 · 🔀 4 · ⏱️ 16.10.2020):

	```
	git clone https://github.com/jtpio/ipyp5
	```
- [PyPi](https://pypi.org/project/ipyp5):
	```
	pip install ipyp5
	```
</details>
<details><summary><b><a href="https://github.com/DGothrek/ipyaggrid">ipyaggrid</a></b> (🥉8 ·  ⭐ 8 · 💀) - Jupyter小部件-Notebook中的Ag-grid。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/DGothrek/ipyaggrid) (👨‍💻 2 · ⏱️ 06.05.2019):

	```
	git clone https://github.com/DGothrek/ipyaggrid
	```
- [PyPi](https://pypi.org/project/ipyaggrid):
	```
	pip install ipyaggrid
	```
- [NPM](https://www.npmjs.com/package/ipyaggrid) (📥 840 / month):
	```
	npm install ipyaggrid
	```
</details>
<details><summary><b><a href="https://github.com/ipyannotate/ipyannotate">ipyannotate</a></b> (🥉7 ·  ⭐ 120 · 💀) - Jupyter Widget，用于数据标注。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipyannotate/ipyannotate) (👨‍💻 3 · 🔀 10 · ⏱️ 20.09.2020):

	```
	git clone https://github.com/ipyannotate/ipyannotate
	```
- [PyPi](https://pypi.org/project/ipyannotate):
	```
	pip install ipyannotate
	```
- [NPM](https://www.npmjs.com/package/ipyannotate) (📥 4 / month):
	```
	npm install ipyannotate
	```
</details>
<br>

## Jupyter拓展

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_扩展Jupyter自身功能的应用程序插件。_

<details><summary><b><a href="https://github.com/dunovank/jupyter-themes">Jupyter Themes</a></b> (🥇21 ·  ⭐ 8.9K · 📈) - Custom Jupyter Notebook Themes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dunovank/jupyter-themes) (👨‍💻 42 · 🔀 980 · 📋 380 - 48% open · ⏱️ 23.08.2021):

	```
	git clone https://github.com/dunovank/jupyter-themes
	```
- [PyPi](https://pypi.org/project/jupyterthemes) (📥 37K / month):
	```
	pip install jupyterthemes
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbgrader">nbgrader</a></b> (🥇21 ·  ⭐ 1K) - 用于在Notebook分配(任务/作业)和评分的系统。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbgrader) (👨‍💻 84 · 🔀 260 · 📋 780 - 25% open · ⏱️ 03.10.2021):

	```
	git clone https://github.com/jupyter/nbgrader
	```
- [PyPi](https://pypi.org/project/nbgrader) (📥 2.3K / month):
	```
	pip install nbgrader
	```
- [Conda](https://anaconda.org/conda-forge/nbgrader) (📥 100K · ⏱️ 25.09.2021):
	```
	conda install -c conda-forge nbgrader
	```
</details>
<details><summary><b><a href="https://github.com/oschuett/appmode">Appmode</a></b> (🥇21 ·  ⭐ 380 · 💤) - Jupyter扩展，可将笔记本变成Web应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oschuett/appmode) (👨‍💻 8 · 🔀 65 · 📦 290 · 📋 52 - 5% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/oschuett/appmode
	```
- [PyPi](https://pypi.org/project/appmode):
	```
	pip install appmode
	```
- [Conda](https://anaconda.org/conda-forge/appmode) (📥 140K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge appmode
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter-resource-usage">Resource Usage</a></b> (🥈20 ·  ⭐ 280) - Jupyter Notebook Extension，用于监视您自己的资源。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter-resource-usage) (👨‍💻 20 · 🔀 65 · 📥 4 · 📋 55 - 50% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/jupyter-server/jupyter-resource-usage
	```
- [PyPi](https://pypi.org/project/jupyter-resource-usage) (📥 15K / month):
	```
	pip install jupyter-resource-usage
	```
- [Conda](https://anaconda.org/conda-forge/nbresuse) (📥 470K · ⏱️ 23.11.2020):
	```
	conda install -c conda-forge nbresuse
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nbgitpuller">nbgitpuller</a></b> (🥈20 ·  ⭐ 150) - Jupyter服务器扩展，可将git存储库单向同步。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nbgitpuller) (👨‍💻 23 · 🔀 51 · 📦 400 · 📋 110 - 38% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/jupyterhub/nbgitpuller
	```
- [PyPi](https://pypi.org/project/nbgitpuller) (📥 5.8K / month):
	```
	pip install nbgitpuller
	```
- [Conda](https://anaconda.org/conda-forge/nbgitpuller) (📥 27K · ⏱️ 03.09.2021):
	```
	conda install -c conda-forge nbgitpuller
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-server-proxy">jupyter-server-proxy</a></b> (🥈19 ·  ⭐ 200) - Jupyter笔记本服务器扩展到代理Web服务。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-server-proxy) (👨‍💻 60 · 🔀 97 · 📦 1 · 📋 150 - 37% open · ⏱️ 16.12.2021):

	```
	git clone https://github.com/jupyterhub/jupyter-server-proxy
	```
- [PyPi](https://pypi.org/project/jupyter-server-proxy) (📥 52K / month):
	```
	pip install jupyter-server-proxy
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-server-proxy) (📥 580K · ⏱️ 30.11.2021):
	```
	conda install -c conda-forge jupyter-server-proxy
	```
</details>
<details><summary><b><a href="https://github.com/8080labs/pyforest">pyforest</a></b> (🥈17 ·  ⭐ 940) - pyforest-自动化导入工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/8080labs/pyforest) (👨‍💻 13 · 🔀 170 · 📋 22 - 36% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/8080labs/pyforest
	```
- [PyPi](https://pypi.org/project/pyforest) (📥 6.4K / month):
	```
	pip install pyforest
	```
</details>
<details><summary><b><a href="https://github.com/mamba-org/gator">gator</a></b> (🥈17 ·  ⭐ 200) - Jupyter内部的Conda环境和包管理扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/gator) (👨‍💻 24 · 🔀 19 · 📥 2 · 📦 1 · 📋 50 - 26% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/mamba-org/gator
	```
- [Conda](https://anaconda.org/conda-forge/mamba_gator) (📥 11K · ⏱️ 03.09.2021):
	```
	conda install -c conda-forge mamba_gator
	```
- [NPM](https://www.npmjs.com/package/@mamba-org/gator-lab) (📥 140 / month):
	```
	npm install @mamba-org/gator-lab
	```
</details>
<details><summary><b><a href="https://github.com/ipython-contrib/jupyter_contrib_nbextensions">Contrib NBextensions</a></b> (🥈16 ·  ⭐ 4.7K · 💤) - Jupyter的各种笔记本扩展的集合。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) (👨‍💻 130 · 🔀 740 · 📋 760 - 41% open · ⏱️ 06.04.2021):

	```
	git clone https://github.com/ipython-contrib/jupyter_contrib_nbextensions
	```
- [PyPi](https://pypi.org/project/jupyter_contrib_nbextensions):
	```
	pip install jupyter_contrib_nbextensions
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/jupyter-spark">Jupyter Spark</a></b> (🥈16 ·  ⭐ 190 · 💤) - 利用pandas DataFrames的Jupyter Notebook扩展。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/mozilla/jupyter-spark) (👨‍💻 12 · 🔀 30 · 📦 15 · 📋 27 - 48% open · ⏱️ 01.12.2020):

	```
	git clone https://github.com/mozilla/jupyter-spark
	```
- [PyPi](https://pypi.org/project/jupyter-spark) (📥 2.5K / month):
	```
	pip install jupyter-spark
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyter-archive">jupyter-archive</a></b> (🥈16 ·  ⭐ 50) - Jupyter / Jupyterlab扩展，用于制作，下载和提取。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyter-archive) (👨‍💻 8 · 🔀 7 · 📥 3.3K · 📋 30 - 3% open · ⏱️ 14.10.2021):

	```
	git clone https://github.com/jupyterlab-contrib/jupyter-archive
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-archive) (📥 19K · ⏱️ 13.10.2021):
	```
	conda install -c conda-forge jupyter-archive
	```
</details>
<details><summary><b><a href="https://github.com/googlecolab/jupyter_http_over_ws">HTTP-over-WebSocket</a></b> (🥉15 ·  ⭐ 200) - Jupyter对ws-over-ws的支持。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/googlecolab/jupyter_http_over_ws) (👨‍💻 3 · 🔀 34 · 📋 26 - 73% open · ⏱️ 30.08.2021):

	```
	git clone https://github.com/googlecolab/jupyter_http_over_ws
	```
- [PyPi](https://pypi.org/project/jupyter_http_over_ws) (📥 28K / month):
	```
	pip install jupyter_http_over_ws
	```
</details>
<details><summary><b><a href="https://github.com/krishnan-r/sparkmonitor">Spark Monitor</a></b> (🥉15 ·  ⭐ 160 · 💤) - 从Jupyter Notebook监控Apache Spark。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/krishnan-r/sparkmonitor) (👨‍💻 3 · 🔀 47 · 📥 2.4K · 📋 22 - 68% open · ⏱️ 03.02.2021):

	```
	git clone https://github.com/krishnan-r/sparkmonitor
	```
- [PyPi](https://pypi.org/project/sparkmonitor):
	```
	pip install sparkmonitor
	```
- [Docker Hub](https://hub.docker.com/r/krishnanr/sparkmonitor) (📥 900 · ⏱️ 04.10.2019):
	```
	docker pull krishnanr/sparkmonitor
	```
</details>
<details><summary><b><a href="https://github.com/Anaconda-Platform/nb_conda">nb_conda</a></b> (🥉15 ·  ⭐ 130 · 💀) - Jupyter内部的Conda环境和包管理扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Anaconda-Platform/nb_conda) (👨‍💻 14 · 🔀 28 · 📋 61 - 54% open · ⏱️ 11.09.2020):

	```
	git clone https://github.com/Anaconda-Platform/nb_conda
	```
- [Conda](https://anaconda.org/conda-forge/nb_conda) (📥 320K · ⏱️ 08.02.2021):
	```
	conda install -c conda-forge nb_conda
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-incubator/contentmanagement">Content Management</a></b> (🥉15 ·  ⭐ 76 · 💀) - Jupyter内容管理扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-incubator/contentmanagement) (👨‍💻 8 · 🔀 25 · 📋 27 - 25% open · ⏱️ 11.06.2018):

	```
	git clone https://github.com/jupyter-incubator/contentmanagement
	```
- [PyPi](https://pypi.org/project/jupyter_cms):
	```
	pip install jupyter_cms
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_cms) (📥 70K · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge jupyter_cms
	```
</details>
<details><summary><b><a href="https://github.com/data-8/nbzip">nbzip</a></b> (🥉15 ·  ⭐ 74 · 💀) - 压缩并下载jupyter笔记本的所有内容。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/data-8/nbzip) (👨‍💻 6 · 🔀 15 · 📦 240 · 📋 14 - 64% open · ⏱️ 22.11.2019):

	```
	git clone https://github.com/data-8/nbzip
	```
- [PyPi](https://pypi.org/project/nbzip) (📥 680 / month):
	```
	pip install nbzip
	```
</details>
<details><summary><b><a href="https://github.com/lspvic/jupyter_tensorboard">jupyter-tensorboard</a></b> (🥉14 ·  ⭐ 450 · 💀) - 在Jupyter Notebook中启动Tensorboard。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lspvic/jupyter_tensorboard) (👨‍💻 4 · 🔀 68 · 📋 68 - 57% open · ⏱️ 16.02.2020):

	```
	git clone https://github.com/lspvic/jupyter_tensorboard
	```
- [PyPi](https://pypi.org/project/jupyter-tensorboard) (📥 4.7K / month):
	```
	pip install jupyter-tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-rsession-proxy">Rsession Proxy</a></b> (🥉14 ·  ⭐ 83) - 用于运行RStudio rsession代理的Jupyter扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-rsession-proxy) (👨‍💻 19 · 🔀 59 · 📦 31 · 📋 66 - 36% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/jupyterhub/jupyter-rsession-proxy
	```
- [PyPi](https://pypi.org/project/jupyter-rsession-proxy):
	```
	pip install jupyter-rsession-proxy
	```
</details>
<details><summary><b><a href="https://github.com/thoth-station/jupyter-nbrequirements">jupyter-nbrequirements</a></b> (🥉12 ·  ⭐ 14) - Jupyter中的依赖关系管理和优化。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thoth-station/jupyter-nbrequirements) (👨‍💻 12 · 🔀 4 · 📋 32 - 6% open · ⏱️ 21.10.2021):

	```
	git clone https://github.com/thoth-station/jupyter-nbrequirements
	```
</details>
<details><summary><b><a href="https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator">NBextensions Configurator</a></b> (🥉11 ·  ⭐ 860 · 💀) - A jupyter notebook serverextension providing config.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator) (👨‍💻 17 · 🔀 98 · 📋 79 - 59% open · ⏱️ 01.03.2020):

	```
	git clone https://github.com/jupyter-contrib/jupyter_nbextensions_configurator
	```
- [PyPi](https://pypi.org/project/jupyter_nbextensions_configurator):
	```
	pip install jupyter_nbextensions_configurator
	```
</details>
<details><summary><b><a href="https://github.com/paypal/PPExtensions">PPExtensions</a></b> (🥉9 ·  ⭐ 48 · 💀) - 一组iPython和Jupyter扩展。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/paypal/PPExtensions) (👨‍💻 9 · 🔀 26 · 📦 1 · 📋 38 - 42% open · ⏱️ 07.12.2018):

	```
	git clone https://github.com/paypal/PPExtensions
	```
- [PyPi](https://pypi.org/project/ppextensions) (📥 39 / month):
	```
	pip install ppextensions
	```
</details>
<details><summary><b><a href="https://github.com/drillan/jupyter-black">Jupyter Black</a></b> (🥉8 ·  ⭐ 370 · 💀) - Jupyter Notebook的黑色格式化程序。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/drillan/jupyter-black) (👨‍💻 2 · 🔀 17 · 📋 20 - 40% open · ⏱️ 01.02.2020):

	```
	git clone https://github.com/drillan/jupyter-black
	```
</details>
<details><summary><b><a href="https://github.com/willkessler/jupyterterminals">jupyterterminals</a></b> (🥉6 ·  ⭐ 8 · 💤) - Jupyter插件可支持嵌入式终端外壳。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/willkessler/jupyterterminals) (👨‍💻 2 · 🔀 2 · 📦 1 · ⏱️ 17.05.2021):

	```
	git clone https://github.com/willkessler/jupyterterminals
	```
</details>
<br>

## Jupyter-magic拓展

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_提供magic命令以访问笔记本中方便功能的扩展。_

<details><summary><b><a href="https://github.com/catherinedevlin/ipython-sql">ipython-sql</a></b> (🥇27 ·  ⭐ 1.5K) - %%sql magic for IPython, hopefully evolving into full SQL client. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/catherinedevlin/ipython-sql) (👨‍💻 44 · 🔀 230 · 📦 2.5K · 📋 130 - 72% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/catherinedevlin/ipython-sql
	```
- [PyPi](https://pypi.org/project/ipython-sql) (📥 90K / month):
	```
	pip install ipython-sql
	```
- [Conda](https://anaconda.org/conda-forge/ipython-sql) (📥 130K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge ipython-sql
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-incubator/sparkmagic">sparkmagic</a></b> (🥇25 ·  ⭐ 1.1K) - Jupyter魔术和内核，可用于远程Spark集群。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter-incubator/sparkmagic) (👨‍💻 54 · 🔀 370 · 📦 220 · 📋 380 - 32% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/jupyter-incubator/sparkmagic
	```
- [PyPi](https://pypi.org/project/sparkmagic) (📥 52K / month):
	```
	pip install sparkmagic
	```
- [Conda](https://anaconda.org/conda-forge/sparkmagic) (📥 38K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge sparkmagic
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/watermark">watermark</a></b> (🥈23 ·  ⭐ 570 · 💤) - 一个IPython魔术扩展，用于打印日期和时间戳版本。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rasbt/watermark) (👨‍💻 15 · 🔀 72 · 📦 1.3K · 📋 42 - 35% open · ⏱️ 18.02.2021):

	```
	git clone https://github.com/rasbt/watermark
	```
- [PyPi](https://pypi.org/project/watermark) (📥 24K / month):
	```
	pip install watermark
	```
- [Conda](https://anaconda.org/conda-forge/watermark) (📥 190K · ⏱️ 18.02.2021):
	```
	conda install -c conda-forge watermark
	```
</details>
<details><summary><b><a href="https://github.com/csurfer/pyheatmagic">heat</a></b> (🥈16 ·  ⭐ 970) - IPython魔术命令：格式化单元格中的python代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csurfer/pyheatmagic) (👨‍💻 3 · 🔀 21 · 📦 24 · 📋 5 - 40% open · ⏱️ 10.09.2021):

	```
	git clone https://github.com/csurfer/pyheatmagic
	```
- [PyPi](https://pypi.org/project/py-heat-magic) (📥 1.7K / month):
	```
	pip install py-heat-magic
	```
</details>
<details><summary><b><a href="https://github.com/ShopRunner/jupyter-notify">jupyter-notify</a></b> (🥈15 ·  ⭐ 550 · 💤) - A Jupyter Notebook magic for browser notifications of cell.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ShopRunner/jupyter-notify) (👨‍💻 11 · 🔀 30 · 📋 22 - 50% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/ShopRunner/jupyter-notify
	```
- [PyPi](https://pypi.org/project/jupyternotify) (📥 1.4K / month):
	```
	pip install jupyternotify
	```
</details>
<details><summary><b><a href="https://github.com/ResidentMario/py_d3">py_d3</a></b> (🥉13 ·  ⭐ 440 · 💀) - D3 block magic for Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ResidentMario/py_d3) (👨‍💻 3 · 🔀 36 · 📋 16 - 12% open · ⏱️ 17.03.2019):

	```
	git clone https://github.com/ResidentMario/py_d3
	```
- [PyPi](https://pypi.org/project/py_d3) (📥 310 / month):
	```
	pip install py_d3
	```
</details>
<details><summary><b><a href="https://github.com/csurfer/blackcellmagic">blackcellmagic</a></b> (🥉12 ·  ⭐ 280 · 📉) - IPython魔术命令：格式化单元格中的python代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csurfer/blackcellmagic) (👨‍💻 3 · 🔀 9 · 📦 130 · 📋 8 - 37% open · ⏱️ 18.09.2021):

	```
	git clone https://github.com/csurfer/blackcellmagic
	```
- [PyPi](https://pypi.org/project/blackcellmagic):
	```
	pip install blackcellmagic
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyter-manim">jupyter-manim</a></b> (🥉12 ·  ⭐ 160 · 💤) - manim单元魔术，用于IPython / Jupyter显示输出视频。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyter-manim) (👨‍💻 4 · 🔀 10 · 📋 22 - 22% open · ⏱️ 05.02.2021):

	```
	git clone https://github.com/krassowski/jupyter-manim
	```
</details>
<details><summary><b><a href="https://github.com/nteract/pick">pick</a></b> (🥉12 ·  ⭐ 28 · 💀) - 在启动时自定义您的内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/pick) (👨‍💻 5 · 🔀 7 · 📋 9 - 44% open · ⏱️ 04.11.2020):

	```
	git clone https://github.com/nteract/pick
	```
- [PyPi](https://pypi.org/project/pick) (📥 40K / month):
	```
	pip install pick
	```
</details>
<details><summary><b><a href="https://github.com/tmthyjames/SQLCell">SQLCell</a></b> (🥉11 ·  ⭐ 140 · 💀) - SQLCell：Jupyter Notebook的魔术函数。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tmthyjames/SQLCell) (👨‍💻 14 · 🔀 9 · 📦 1 · 📋 84 - 71% open · ⏱️ 06.10.2020):

	```
	git clone https://github.com/tmthyjames/SQLCell
	```
- [PyPi](https://pypi.org/project/sqlcell) (📥 41 / month):
	```
	pip install sqlcell
	```
</details>
<br>

## Jupyter内核

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Jupyter内核以给定的语言运行和内省用户的代码。_

<details><summary><b><a href="https://github.com/ipython/ipykernel">IPython Kernel</a></b> (🥇29 ·  ⭐ 440) - IPython Kernel for Jupyter. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipython/ipykernel) (👨‍💻 150 · 🔀 280 · 📥 120 · 📦 150K · 📋 370 - 51% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/ipython/ipykernel
	```
- [PyPi](https://pypi.org/project/ipykernel) (📥 14M / month):
	```
	pip install ipykernel
	```
- [Conda](https://anaconda.org/anaconda/ipykernel) (📥 230K · ⏱️ 07.10.2021):
	```
	conda install -c anaconda ipykernel
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/metakernel">Metakernel</a></b> (🥇22 ·  ⭐ 260) - Jupyter/IPython内核工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/metakernel) (👨‍💻 29 · 🔀 73 · 📥 12 · 📋 140 - 18% open · ⏱️ 02.12.2021):

	```
	git clone https://github.com/Calysto/metakernel
	```
- [PyPi](https://pypi.org/project/metakernel) (📥 24K / month):
	```
	pip install metakernel
	```
- [Conda](https://anaconda.org/conda-forge/metakernel) (📥 530K · ⏱️ 02.12.2021):
	```
	conda install -c conda-forge metakernel
	```
</details>
<details><summary><b><a href="https://github.com/gopherdata/gophernotes">gophernotes</a></b> (🥇21 ·  ⭐ 3.1K) - 适用于Jupyter笔记本电脑和nteract的Go内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gopherdata/gophernotes) (👨‍💻 28 · 🔀 210 · 📥 40 · 📦 7 · 📋 160 - 26% open · ⏱️ 24.06.2021):

	```
	git clone https://github.com/gopherdata/gophernotes
	```
- [Docker Hub](https://hub.docker.com/r/gopherdata/gophernotes) (📥 84K · ⭐ 7 · ⏱️ 22.12.2018):
	```
	docker pull gopherdata/gophernotes
	```
</details>
<details><summary><b><a href="https://github.com/n-riesco/ijavascript">IJavascript</a></b> (🥇21 ·  ⭐ 1.7K) - Jupyter笔记本的JavaScript内核。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/n-riesco/ijavascript) (👨‍💻 14 · 🔀 140 · 📦 54 · 📋 220 - 21% open · ⏱️ 01.12.2021):

	```
	git clone https://github.com/n-riesco/ijavascript
	```
- [NPM](https://www.npmjs.com/package/ijavascript) (📥 2.8K / month):
	```
	npm install ijavascript
	```
</details>
<details><summary><b><a href="https://github.com/IRkernel/IRkernel">IRkernel</a></b> (🥇21 ·  ⭐ 1.5K) - Jupyter的R内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IRkernel/IRkernel) (👨‍💻 40 · 🔀 290 · 📋 560 - 10% open · ⏱️ 02.08.2021):

	```
	git clone https://github.com/IRkernel/IRkernel
	```
- [Conda](https://anaconda.org/r/r-irkernel) (📥 53K · ⏱️ 10.03.2020):
	```
	conda install -c r r-irkernel
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/r-notebook) (📥 1.1M · ⭐ 42 · ⏱️ 21.12.2021):
	```
	docker pull jupyter/r-notebook
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-toree">Apache Toree</a></b> (🥈20 ·  ⭐ 690 · 📈) - 适用于Apache Spark的Jupyter内核。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/incubator-toree) (👨‍💻 100 · 🔀 210 · ⏱️ 07.09.2021):

	```
	git clone https://github.com/apache/incubator-toree
	```
- [PyPi](https://pypi.org/project/toree) (📥 11K / month):
	```
	pip install toree
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/octave_kernel">Octave Kernel</a></b> (🥈20 ·  ⭐ 380) - 用于IPython的Octave内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/octave_kernel) (👨‍💻 17 · 🔀 57 · 📥 7 · 📋 160 - 17% open · ⏱️ 02.12.2021):

	```
	git clone https://github.com/calysto/octave_kernel
	```
- [PyPi](https://pypi.org/project/octave_kernel) (📥 14K / month):
	```
	pip install octave_kernel
	```
</details>
<details><summary><b><a href="https://github.com/almond-sh/almond">almond</a></b> (🥈19 ·  ⭐ 1.4K) - Jupyter的Scala内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/almond-sh/almond) (👨‍💻 35 · 🔀 210 · 📥 1.2K · 📋 290 - 33% open · ⏱️ 01.09.2021):

	```
	git clone https://github.com/almond-sh/almond
	```
- [Docker Hub](https://hub.docker.com/r/almondsh/almond) (📥 13K · ⭐ 6 · ⏱️ 26.08.2021):
	```
	docker pull almondsh/almond
	```
</details>
<details><summary><b><a href="https://github.com/SciRuby/iruby">IRuby</a></b> (🥈19 ·  ⭐ 670) - 官方gem仓库：Jupyter/IPython Notebook的Ruby内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SciRuby/iruby) (👨‍💻 44 · 🔀 9 · 📥 15 · 📦 150 · 📋 180 - 23% open · ⏱️ 12.11.2021):

	```
	git clone https://github.com/SciRuby/iruby
	```
- [Docker Hub](https://hub.docker.com/r/rubydata/datascience-notebook) (📥 1.5K · ⭐ 3 · ⏱️ 28.09.2021):
	```
	docker pull rubydata/datascience-notebook
	```
</details>
<details><summary><b><a href="https://github.com/JuliaLang/IJulia.jl">IJulia.jl</a></b> (🥈18 ·  ⭐ 2.4K) - Jupyter的Julia内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/JuliaLang/IJulia.jl) (👨‍💻 100 · 🔀 370 · 📋 770 - 12% open · ⏱️ 27.10.2021):

	```
	git clone https://github.com/JuliaLang/IJulia.jl
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-cling">xeus-cling</a></b> (🥈18 ·  ⭐ 2K) - 适用于C++编程语言的Jupyter内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-cling) (👨‍💻 20 · 🔀 210 · 📋 230 - 52% open · ⏱️ 27.09.2021):

	```
	git clone https://github.com/jupyter-xeus/xeus-cling
	```
- [Conda](https://anaconda.org/conda-forge/xeus-cling) (📥 130K · ⏱️ 24.09.2021):
	```
	conda install -c conda-forge xeus-cling
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/enterprise_gateway">Enterprise Gateway</a></b> (🥈18 ·  ⭐ 480) - 轻量级，多租户，可扩展和安全的网关。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/enterprise_gateway) (👨‍💻 86 · 🔀 150 · 📥 12K · 📋 490 - 18% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/jupyter/enterprise_gateway
	```
- [PyPi](https://pypi.org/project/jupyter_enterprise_gateway) (📥 700 / month):
	```
	pip install jupyter_enterprise_gateway
	```
</details>
<details><summary><b><a href="https://github.com/Anaconda-Platform/nb_conda_kernels">nb_conda_kernels</a></b> (🥈18 ·  ⭐ 420 · 💀) - Package for managing conda environment-based kernels.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Anaconda-Platform/nb_conda_kernels) (👨‍💻 14 · 🔀 52 · 📋 130 - 24% open · ⏱️ 30.11.2020):

	```
	git clone https://github.com/Anaconda-Platform/nb_conda_kernels
	```
- [Conda](https://anaconda.org/conda-forge/nb_conda_kernels) (📥 520K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge nb_conda_kernels
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/kernel_gateway">Kernel Gateway</a></b> (🥈18 ·  ⭐ 370) - Jupyter内核网关。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/kernel_gateway) (👨‍💻 44 · 🔀 110 · 📥 100 · 📋 180 - 8% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/jupyter/kernel_gateway
	```
- [PyPi](https://pypi.org/project/jupyter-kernel-gateway) (📥 4.7K / month):
	```
	pip install jupyter-kernel-gateway
	```
</details>
<details><summary><b><a href="https://github.com/akabe/ocaml-jupyter">OCaml Kernel</a></b> (🥈18 ·  ⭐ 200) - Jupyter（IPython）笔记本的OCaml内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/akabe/ocaml-jupyter) (👨‍💻 17 · 🔀 29 · 📥 58K · 📋 67 - 4% open · ⏱️ 07.08.2021):

	```
	git clone https://github.com/akabe/ocaml-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/scijava/scijava-jupyter-kernel">SciJava Kernel</a></b> (🥈18 ·  ⭐ 180) - 在Jupyter笔记本中编写SciJava脚本。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/scijava/scijava-jupyter-kernel) (👨‍💻 9 · 🔀 44 · 📥 76 · 📋 80 - 12% open · ⏱️ 08.11.2021):

	```
	git clone https://github.com/scijava/scijava-jupyter-kernel
	```
- [Conda](https://anaconda.org/conda-forge/scijava-jupyter-kernel) (📥 75K · ⏱️ 03.03.2018):
	```
	conda install -c conda-forge scijava-jupyter-kernel
	```
</details>
<details><summary><b><a href="https://github.com/vericast/spylon-kernel">Spylon Kernel</a></b> (🥈18 ·  ⭐ 150 · 💀) - Jupyter kernel for scala and spark. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/vericast/spylon-kernel) (👨‍💻 6 · 🔀 23 · 📦 67 · 📋 34 - 47% open · ⏱️ 20.09.2018):

	```
	git clone https://github.com/Valassis-Digital-Media/spylon-kernel
	```
- [PyPi](https://pypi.org/project/spylon-kernel) (📥 5K / month):
	```
	pip install spylon-kernel
	```
- [Conda](https://anaconda.org/conda-forge/spylon-kernel) (📥 79K · ⏱️ 05.10.2018):
	```
	conda install -c conda-forge spylon-kernel
	```
</details>
<details><summary><b><a href="https://github.com/gibiansky/IHaskell">IHaskell</a></b> (🥉17 ·  ⭐ 2.3K) - 用于IPython的Haskell内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gibiansky/IHaskell) (👨‍💻 100 · 🔀 240 · 📋 720 - 3% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/gibiansky/IHaskell
	```
- [NPM](https://www.npmjs.com/package/ihaskell_jupyterlab) (📥 6 / month):
	```
	npm install ihaskell_jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/sassoftware/sas_kernel">SAS Kernel</a></b> (🥉17 ·  ⭐ 180) - 用于SAS的Jupyter内核。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sassoftware/sas_kernel) (👨‍💻 7 · 🔀 71 · 📋 55 - 5% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/sassoftware/sas_kernel
	```
- [PyPi](https://pypi.org/project/sas_kernel) (📥 620 / month):
	```
	pip install sas_kernel
	```
</details>
<details><summary><b><a href="https://github.com/SpencerPark/IJava">IJava</a></b> (🥉16 ·  ⭐ 720 · 💀) - 用于执行Java代码的Jupyter内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SpencerPark/IJava) (👨‍💻 4 · 🔀 140 · 📥 68K · 📋 120 - 51% open · ⏱️ 08.12.2019):

	```
	git clone https://github.com/SpencerPark/IJava
	```
</details>
<details><summary><b><a href="https://github.com/clojupyter/clojupyter">clojupyter</a></b> (🥉16 ·  ⭐ 720) - 用于Clojure的Jupyter内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/clojupyter/clojupyter) (👨‍💻 26 · 🔀 74 · 📋 92 - 18% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/clojupyter/clojupyter
	```
- [Conda](https://anaconda.org/simplect/clojupyter) (📥 2.7K · ⏱️ 02.03.2020):
	```
	conda install -c simplect clojupyter
	```
- [Docker Hub](https://hub.docker.com/r/simplect/clojupyter) (📥 340 · ⏱️ 25.04.2019):
	```
	docker pull simplect/clojupyter
	```
</details>
<details><summary><b><a href="https://github.com/ansible/ansible-jupyter-kernel">Ansible Kernel</a></b> (🥉16 ·  ⭐ 480 · 💤) - Jupyter笔记本内核，用于运行Ansible任务。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ansible/ansible-jupyter-kernel) (👨‍💻 9 · 🔀 48 · 📦 8 · 📋 41 - 29% open · ⏱️ 05.03.2021):

	```
	git clone https://github.com/ansible/ansible-jupyter-kernel
	```
- [PyPi](https://pypi.org/project/ansible-kernel) (📥 70 / month):
	```
	pip install ansible-kernel
	```
- [Conda](https://anaconda.org/conda-forge/ansible-kernel) (📥 8.6K · ⏱️ 14.01.2020):
	```
	conda install -c conda-forge ansible-kernel
	```
- [Docker Hub](https://hub.docker.com/r/benthomasson/ansible-jupyter-kernel) (📥 66K · ⭐ 2 · ⏱️ 12.12.2018):
	```
	docker pull benthomasson/ansible-jupyter-kernel
	```
</details>
<details><summary><b><a href="https://github.com/fsprojects/IfSharp">F# Kernel</a></b> (🥉16 ·  ⭐ 430 · 💀) - F# for Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/fsprojects/IfSharp) (👨‍💻 27 · 🔀 66 · 📥 5.3K · 📋 140 - 9% open · ⏱️ 10.09.2020):

	```
	git clone https://github.com/fsprojects/IfSharp
	```
- [Docker Hub](https://hub.docker.com/r/fsprojects/ifsharp) (📥 650 · ⏱️ 26.03.2019):
	```
	docker pull fsprojects/ifsharp
	```
</details>
<details><summary><b><a href="https://github.com/lfortran/lfortran">LFortran</a></b> (🥉16 ·  ⭐ 290) - https://gitlab.com/lfortran/lfortran的官方镜像。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lfortran/lfortran) (👨‍💻 20 · 🔀 15 · ⏱️ 22.12.2021):

	```
	git clone https://github.com/lfortran/lfortran
	```
- [PyPi](https://pypi.org/project/lfortran) (📥 120 / month):
	```
	pip install lfortran
	```
- [Conda](https://anaconda.org/conda-forge/lfortran) (📥 31K · ⏱️ 23.09.2021):
	```
	conda install -c conda-forge lfortran
	```
</details>
<details><summary><b><a href="https://github.com/WolframResearch/WolframLanguageForJupyter">Wolfram Kernel</a></b> (🥉15 ·  ⭐ 660) - 适用于Jupyter的Wolfram语言内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/WolframResearch/WolframLanguageForJupyter) (👨‍💻 7 · 🔀 83 · 📥 4.7K · 📋 83 - 24% open · ⏱️ 21.10.2021):

	```
	git clone https://github.com/WolframResearch/WolframLanguageForJupyter
	```
</details>
<details><summary><b><a href="https://github.com/pprzetacznik/IElixir">IElixir</a></b> (🥉15 ·  ⭐ 330 · 💤) - Jupyter的Elixir编程语言内核。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pprzetacznik/IElixir) (👨‍💻 19 · 🔀 38 · 📋 30 - 33% open · ⏱️ 20.03.2021):

	```
	git clone https://github.com/pprzetacznik/IElixir
	```
- [Docker Hub](https://hub.docker.com/r/pprzetacznik/ielixir) (📥 300 · ⭐ 1 · ⏱️ 20.03.2021):
	```
	docker pull pprzetacznik/ielixir
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/matlab_kernel">Matlab Kernel</a></b> (🥉14 ·  ⭐ 410 · 💀) - Jupyter的Matlab内核。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Calysto/matlab_kernel) (👨‍💻 17 · 🔀 72 · 📋 130 - 19% open · ⏱️ 09.11.2020):

	```
	git clone https://github.com/calysto/matlab_kernel
	```
- [PyPi](https://pypi.org/project/matlab_kernel) (📥 1.4K / month):
	```
	pip install matlab_kernel
	```
</details>
<details><summary><b><a href="https://github.com/yunabe/lgo">lgo</a></b> (🥉13 ·  ⭐ 2.2K · 💀) - 使用Jupyter进行交互式Go编程。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/yunabe/lgo) (👨‍💻 9 · 🔀 110 · 📋 76 - 30% open · ⏱️ 09.07.2019):

	```
	git clone https://github.com/yunabe/lgo
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/bash_kernel">Bash Kernel</a></b> (🥉13 ·  ⭐ 560 · 💀) - IPython的bash内核。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/takluyver/bash_kernel) (👨‍💻 13 · 🔀 99 · 📥 2.8K · 📋 90 - 41% open · ⏱️ 22.07.2019):

	```
	git clone https://github.com/takluyver/bash_kernel
	```
- [PyPi](https://pypi.org/project/bash_kernel) (📥 6K / month):
	```
	pip install bash_kernel
	```
</details>
<details><summary><b><a href="https://github.com/NII-cloud-operation/sshkernel">SSH Kernel</a></b> (🥉13 ·  ⭐ 47) - Jupyter的SSH内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/NII-cloud-operation/sshkernel) (👨‍💻 4 · 🔀 10 · 📦 6 · 📋 8 - 25% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/NII-cloud-operation/sshkernel
	```
- [PyPi](https://pypi.org/project/sshkernel) (📥 52 / month):
	```
	pip install sshkernel
	```
</details>
<details><summary><b><a href="https://github.com/zabirauf/icsharp">ICSharp</a></b> (🥉11 ·  ⭐ 260 · 💀) - Jupyter的C＃内核。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/zabirauf/icsharp) (👨‍💻 10 · 🔀 59 · 📋 46 - 71% open · ⏱️ 23.09.2018):

	```
	git clone https://github.com/zabirauf/icsharp
	```
</details>
<details><summary><b><a href="https://github.com/Cadair/jupyter_environment_kernels">Kernel Detection</a></b> (🥉11 ·  ⭐ 140 · 💀) - 一个Jupyter插件，用于自动检测。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/Cadair/jupyter_environment_kernels) (👨‍💻 6 · 🔀 16 · 📋 29 - 24% open · ⏱️ 12.02.2018):

	```
	git clone https://github.com/Cadair/jupyter_environment_kernels
	```
- [PyPi](https://pypi.org/project/environment_kernels):
	```
	pip install environment_kernels
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-sqlite">xeus-sqlite</a></b> (🥉11 ·  ⭐ 130) - 适用于SQLite的Jupyter内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-sqlite) (👨‍💻 12 · 🔀 20 · 📋 39 - 28% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/jupyter-xeus/xeus-sqlite
	```
</details>
<details><summary><b><a href="https://github.com/tdaff/remote_ikernel">remote_ikernel</a></b> (🥉10 ·  ⭐ 8 · 💀) - All your Jupyter kernels, on all your machines, in one place. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/tdaff/remote_ikernel) (👨‍💻 7 · 🔀 9 · 📋 26 - 30% open · ⏱️ 08.11.2020):

	```
	git clone https://github.com/tdaff/remote_ikernel
	```
- [PyPi](https://pypi.org/project/remote_ikernel) (📥 280 / month):
	```
	pip install remote_ikernel
	```
</details>
<details><summary><b><a href="https://github.com/nteract/kernel-relay">kernel-relay</a></b> (🥉6 ·  ⭐ 10 · 💀) - kernel-relay是与之接口的GraphQL服务。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nteract/kernel-relay) (👨‍💻 3 · 🔀 5 · 📋 12 - 83% open · ⏱️ 10.07.2019):

	```
	git clone https://github.com/nteract/kernel-relay
	```
</details>
<details><summary><b><a href="https://github.com/bernhard-42/ssh_ipykernel">ssh_ipykernel</a></b> (🥉6 ·  ⭐ 6) - A remote jupyter kernel via ssh. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bernhard-42/ssh_ipykernel) (👨‍💻 2 · 🔀 1 · ⏱️ 28.06.2021):

	```
	git clone https://github.com/bernhard-42/ssh_ipykernel
	```
</details>
<br>

## Jupyter-Notebook分享与格式转换

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_与笔记本文件共享、转换和简化协作的工具（例如，通过git）。_

<details><summary><b><a href="https://github.com/jupyter/nbconvert">nbconvert</a></b> (🥇30 ·  ⭐ 1.2K) - Jupyter Notebook Conversion. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/nbconvert) (👨‍💻 240 · 🔀 450 · 📦 130K · 📋 950 - 41% open · ⏱️ 10.12.2021):

	```
	git clone https://github.com/jupyter/nbconvert
	```
- [PyPi](https://pypi.org/project/nbconvert) (📥 15M / month):
	```
	pip install nbconvert
	```
- [Conda](https://anaconda.org/conda-forge/nbconvert) (📥 5.4M · ⏱️ 14.11.2021):
	```
	conda install -c conda-forge nbconvert
	```
</details>
<details><summary><b><a href="https://github.com/getnikola/nikola">nikola</a></b> (🥇28 ·  ⭐ 2.2K) - 静态网站和博客生成器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/getnikola/nikola) (👨‍💻 220 · 🔀 330 · 📦 400 · 📋 2.1K - 1% open · ⏱️ 11.12.2021):

	```
	git clone https://github.com/getnikola/nikola
	```
- [PyPi](https://pypi.org/project/nikola) (📥 1.4K / month):
	```
	pip install nikola
	```
</details>
<details><summary><b><a href="https://github.com/mwouts/jupytext">Jupytext</a></b> (🥇27 ·  ⭐ 5K) - Jupyter Notebooks作为Markdown文档，Julia，Python或R脚本的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/jupytext) (👨‍💻 67 · 🔀 310 · 📦 2.2K · 📋 480 - 11% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/mwouts/jupytext
	```
- [PyPi](https://pypi.org/project/jupytext) (📥 150K / month):
	```
	pip install jupytext
	```
- [Conda](https://anaconda.org/conda-forge/jupytext) (📥 250K · ⏱️ 12.12.2021):
	```
	conda install -c conda-forge jupytext
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-jupytext) (📥 15K / month):
	```
	npm install jupyterlab-jupytext
	```
</details>
<details><summary><b><a href="https://github.com/voila-dashboards/voila">Voila</a></b> (🥈25 ·  ⭐ 3.8K) - Voil将Jupyter笔记本变成独立的Web应用程序。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/voila-dashboards/voila) (👨‍💻 56 · 🔀 360 · 📥 110 · 📦 5.5K · 📋 550 - 41% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/voila-dashboards/voila
	```
- [PyPi](https://pypi.org/project/voila) (📥 39K / month):
	```
	pip install voila
	```
- [Conda](https://anaconda.org/conda-forge/voila) (📥 160K · ⏱️ 22.12.2021):
	```
	conda install -c conda-forge voila
	```
- [NPM](https://www.npmjs.com/package/@jupyter-voila/jupyterlab-preview) (📥 3.5K / month):
	```
	npm install @jupyter-voila/jupyterlab-preview
	```
</details>
<details><summary><b><a href="https://github.com/damianavila/RISE">RISE</a></b> (🥈24 ·  ⭐ 3.2K) - 实时Reveal.js Jupyter/IPython幻灯片扩展。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/damianavila/RISE) (👨‍💻 40 · 🔀 370 · 📦 1.7K · 📋 420 - 32% open · ⏱️ 26.11.2021):

	```
	git clone https://github.com/damianavila/RISE
	```
- [PyPi](https://pypi.org/project/RISE) (📥 10K / month):
	```
	pip install RISE
	```
- [Conda](https://anaconda.org/conda-forge/rise) (📥 180K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge rise
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/jupyter-book">Jupyter Book</a></b> (🥈24 ·  ⭐ 2.6K) - 从Jupyter构建交互式的，具有出版质量的文档。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/executablebooks/jupyter-book) (👨‍💻 96 · 🔀 400 · 📋 960 - 38% open · ⏱️ 19.12.2021):

	```
	git clone https://github.com/executablebooks/jupyter-book
	```
- [PyPi](https://pypi.org/project/jupyter-book) (📥 37K / month):
	```
	pip install jupyter-book
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbdime">nbdime</a></b> (🥈23 ·  ⭐ 2.1K) - 区分和合并Jupyter笔记本的工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/nbdime) (👨‍💻 34 · 🔀 120 · 📦 63 · 📋 280 - 21% open · ⏱️ 03.11.2021):

	```
	git clone https://github.com/jupyter/nbdime
	```
- [PyPi](https://pypi.org/project/nbdime) (📥 210K / month):
	```
	pip install nbdime
	```
- [Conda](https://anaconda.org/conda-forge/nbdime) (📥 420K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge nbdime
	```
- [NPM](https://www.npmjs.com/package/nbdime-jupyterlab) (📥 76K / month):
	```
	npm install nbdime-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbviewer">nbviewer</a></b> (🥈22 ·  ⭐ 2K) - nbconvert作为Web服务：将Jupyter Notebooks渲染为静态Web。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbviewer) (👨‍💻 86 · 🔀 480 · 📦 7 · 📋 560 - 28% open · ⏱️ 10.09.2021):

	```
	git clone https://github.com/jupyter/nbviewer
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/nbviewer) (📥 2.3M · ⭐ 26 · ⏱️ 02.12.2020):
	```
	docker pull jupyter/nbviewer
	```
</details>
<details><summary><b><a href="https://github.com/stencila/stencila">Stencila</a></b> (🥈22 ·  ⭐ 620) - 用于可复制研究的在线文档。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/stencila/stencila) (👨‍💻 26 · 🔀 32 · 📥 990 · 📦 16 · 📋 540 - 9% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/stencila/stencila
	```
- [NPM](https://www.npmjs.com/package/stencila) (📥 94 / month):
	```
	npm install stencila
	```
- [Docker Hub](https://hub.docker.com/r/stencila/cloud) (📥 16K · ⏱️ 08.04.2019):
	```
	docker pull stencila/cloud
	```
</details>
<details><summary><b><a href="https://github.com/airbnb/knowledge-repo">Knowledge Repo</a></b> (🥉20 ·  ⭐ 5K) - 下一代知识共享平台<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airbnb/knowledge-repo) (👨‍💻 60 · 🔀 630 · 📋 280 - 41% open · ⏱️ 01.09.2021):

	```
	git clone https://github.com/airbnb/knowledge-repo
	```
- [PyPi](https://pypi.org/project/knowledge-repo) (📥 4.8K / month):
	```
	pip install knowledge-repo
	```
</details>
<details><summary><b><a href="https://github.com/aaren/notedown">notedown</a></b> (🥉19 ·  ⭐ 780 · 💀) - Markdown = IPython Notebook. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/aaren/notedown) (👨‍💻 7 · 🔀 93 · 📦 150 · 📋 68 - 57% open · ⏱️ 16.11.2017):

	```
	git clone https://github.com/aaren/notedown
	```
- [PyPi](https://pypi.org/project/notedown) (📥 4.2K / month):
	```
	pip install notedown
	```
- [Conda](https://anaconda.org/conda-forge/notedown) (📥 33K · ⏱️ 07.06.2018):
	```
	conda install -c conda-forge notedown
	```
</details>
<details><summary><b><a href="https://github.com/nteract/bookstore">bookstore</a></b> (🥉19 ·  ⭐ 180 · 💀) - 面向大众的笔记本存储和发布工作流程。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/bookstore) (👨‍💻 7 · 🔀 18 · 📦 5 · 📋 73 - 46% open · ⏱️ 09.12.2019):

	```
	git clone https://github.com/nteract/bookstore
	```
- [PyPi](https://pypi.org/project/bookstore) (📥 130K / month):
	```
	pip install bookstore
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/binderhub">BinderHub</a></b> (🥉18 ·  ⭐ 2.1K) - 在云端运行您的代码。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/binderhub) (👨‍💻 82 · 🔀 300 · 📦 5 · 📋 610 - 27% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/jupyterhub/binderhub
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/thebe">ThebeLab</a></b> (🥉18 ·  ⭐ 260) - ThebeLab：将静态HTML页面转换为实时文档。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/executablebooks/thebe) (👨‍💻 26 · 🔀 54 · 📦 5 · 📋 140 - 39% open · ⏱️ 19.11.2021):

	```
	git clone https://github.com/executablebooks/thebe
	```
</details>
<details><summary><b><a href="https://github.com/nteract/commuter">commuter</a></b> (🥉17 ·  ⭐ 390) - 笔记本共享中心。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/commuter) (👨‍💻 27 · 🔀 63 · 📦 3 · 📋 90 - 56% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/nteract/commuter
	```
- [NPM](https://www.npmjs.com/package/@nteract/commuter) (📥 400 / month):
	```
	npm install @nteract/commuter
	```
</details>
<details><summary><b><a href="https://github.com/nteract/scrapbook">scrapbook</a></b> (🥉17 ·  ⭐ 230 · 💤) - 一个用于在笔记本中记录和读取数据的库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/scrapbook) (👨‍💻 11 · 🔀 23 · 📦 84 · 📋 48 - 47% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/nteract/scrapbook
	```
- [PyPi](https://pypi.org/project/nteract-scrapbook) (📥 35K / month):
	```
	pip install nteract-scrapbook
	```
</details>
<details><summary><b><a href="https://github.com/SamLau95/nbinteract">nbinteract</a></b> (🥉14 ·  ⭐ 210 · 💤) - 从Jupyter Notebooks创建交互式网页。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/SamLau95/nbinteract) (👨‍💻 8 · 🔀 20 · 📦 1 · 📋 70 - 41% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/SamLau95/nbinteract
	```
- [PyPi](https://pypi.org/project/nbinteract) (📥 750 / month):
	```
	pip install nbinteract
	```
</details>
<details><summary><b><a href="https://github.com/elehcimd/pynb">pynb</a></b> (🥉13 ·  ⭐ 230 · 💀) - Jupyter Notebooks是带有嵌入式Markdown文本的纯Python代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/elehcimd/pynb) (👨‍💻 8 · 🔀 6 · 📦 17 · ⏱️ 07.07.2020):

	```
	git clone https://github.com/elehcimd/pynb
	```
</details>
<details><summary><b><a href="https://github.com/ideonate/cdsdashboards">cdsdashboards</a></b> (🥉13 ·  ⭐ 150) - 用于ContainDS仪表板的JupyterHub扩展。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ideonate/cdsdashboards) (👨‍💻 11 · 🔀 24 · 📋 75 - 33% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/ideonate/cdsdashboards
	```
- [PyPi](https://pypi.org/project/cdsdashboards):
	```
	pip install cdsdashboards
	```
- [Conda](https://anaconda.org/conda-forge/cdsdashboards) (📥 17K · ⏱️ 28.10.2021):
	```
	conda install -c conda-forge cdsdashboards
	```
</details>
<details><summary><b><a href="https://github.com/nbgallery/nbgallery">nbgallery</a></b> (🥉13 ·  ⭐ 140) - 企业Jupyter笔记本共享和协作应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbgallery/nbgallery) (👨‍💻 18 · 🔀 21 · 📋 350 - 25% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/nbgallery/nbgallery
	```
- [Docker Hub](https://hub.docker.com/r/nbgallery/nbgallery) (📥 130K · ⭐ 3 · ⏱️ 12.11.2021):
	```
	docker pull nbgallery/nbgallery
	```
</details>
<details><summary><b><a href="https://github.com/danielfrg/jupyter-flex">jupyter-flex</a></b> (🥉11 ·  ⭐ 230) - 使用Jupyter Notebook构建仪表板。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/jupyter-flex) (👨‍💻 3 · 🔀 39 · 📦 1 · 📋 47 - 12% open · ⏱️ 30.11.2021):

	```
	git clone https://github.com/danielfrg/jupyter-flex
	```
</details>
<details><summary><b><a href="https://github.com/line/jnotebook_reader">jnotebook-reader</a></b> (🥉10 ·  ⭐ 91 · 💤) - 一款很棒的查看器，用于浏览和渲染Jupyter。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/line/jnotebook_reader) (👨‍💻 4 · 🔀 14 · 📋 2 - 50% open · ⏱️ 10.02.2021):

	```
	git clone https://github.com/line/jnotebook_reader
	```
</details>
<details><summary><b><a href="https://github.com/danielfrg/mkdocs-jupyter">mkdocs-jupyter</a></b> (🥉9 ·  ⭐ 94) - 在mkdocs中使用Jupyter Notebook。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/mkdocs-jupyter) (👨‍💻 9 · 🔀 11 · 📋 34 - 2% open · ⏱️ 30.11.2021):

	```
	git clone https://github.com/danielfrg/mkdocs-jupyter
	```
- [PyPi](https://pypi.org/project/mkdocs-jupyter):
	```
	pip install mkdocs-jupyter
	```
</details>
<br>

## Jupyter-Notebook工具

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_与笔记本文件一起工作或可以在笔记本文件中使用的库和工具。_

<details><summary><b><a href="https://github.com/jupyter/nbformat">nbformat</a></b> (🥇27 ·  ⭐ 160) - Jupyter Notebook格式的参考实现。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/nbformat) (👨‍💻 60 · 🔀 120 · 📦 130K · 📋 110 - 41% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/jupyter/nbformat
	```
- [PyPi](https://pypi.org/project/nbformat):
	```
	pip install nbformat
	```
- [Conda](https://anaconda.org/conda-forge/nbformat) (📥 6.8M · ⏱️ 02.04.2021):
	```
	conda install -c conda-forge nbformat
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbclient">nbclient</a></b> (🥇26 ·  ⭐ 83) - 用于执行笔记本的客户端库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/nbclient) (👨‍💻 28 · 🔀 39 · 📥 9 · 📦 38K · 📋 73 - 27% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/jupyter/nbclient
	```
- [PyPi](https://pypi.org/project/nbclient):
	```
	pip install nbclient
	```
- [Conda](https://anaconda.org/conda-forge/nbclient) (📥 2.5M · ⏱️ 19.11.2021):
	```
	conda install -c conda-forge nbclient
	```
</details>
<details><summary><b><a href="https://github.com/pixiedust/pixiedust">PixieDust</a></b> (🥇25 ·  ⭐ 1K · 💤) - 适用于Jupyter Notebook的Python Helper库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pixiedust/pixiedust) (👨‍💻 33 · 🔀 160 · 📦 220 · 📋 420 - 38% open · ⏱️ 16.02.2021):

	```
	git clone https://github.com/pixiedust/pixiedust
	```
- [PyPi](https://pypi.org/project/pixiedust) (📥 17K / month):
	```
	pip install pixiedust
	```
- [Conda](https://anaconda.org/conda-forge/pixiedust) (📥 34K · ⏱️ 06.02.2021):
	```
	conda install -c conda-forge pixiedust
	```
</details>
<details><summary><b><a href="https://github.com/fastai/nbdev">nbdev</a></b> (🥈24 ·  ⭐ 3.1K) - 使用Jupyter Notebook创建python项目。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastai/nbdev) (👨‍💻 61 · 🔀 320 · 📋 340 - 22% open · ⏱️ 08.12.2021):

	```
	git clone https://github.com/fastai/nbdev
	```
- [PyPi](https://pypi.org/project/nbdev) (📥 48K / month):
	```
	pip install nbdev
	```
</details>
<details><summary><b><a href="https://github.com/twosigma/beakerx">BeakerX</a></b> (🥈23 ·  ⭐ 2.6K · 💤) - Jupyter Notebook的Beaker扩展。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/twosigma/beakerx) (👨‍💻 43 · 🔀 370 · 📥 31 · 📋 4.5K - 7% open · ⏱️ 21.01.2021):

	```
	git clone https://github.com/twosigma/beakerx
	```
- [PyPi](https://pypi.org/project/beakerx) (📥 9K / month):
	```
	pip install beakerx
	```
- [Conda](https://anaconda.org/conda-forge/beakerx) (📥 480K · ⏱️ 18.11.2021):
	```
	conda install -c conda-forge beakerx
	```
- [NPM](https://www.npmjs.com/package/beakerx) (📥 1.2K / month):
	```
	npm install beakerx
	```
- [Docker Hub](https://hub.docker.com/r/beakerx/beakerx) (📥 240K · ⭐ 22 · ⏱️ 02.12.2018):
	```
	docker pull beakerx/beakerx
	```
</details>
<details><summary><b><a href="https://github.com/computationalmodelling/nbval">nbval</a></b> (🥈23 ·  ⭐ 360) - 一个py.test插件，用于验证Jupyter笔记本。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/computationalmodelling/nbval) (👨‍💻 28 · 🔀 39 · 📦 1.2K · 📋 95 - 35% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/computationalmodelling/nbval
	```
- [PyPi](https://pypi.org/project/nbval) (📥 80K / month):
	```
	pip install nbval
	```
- [Conda](https://anaconda.org/conda-forge/nbval) (📥 180K · ⏱️ 31.07.2020):
	```
	conda install -c conda-forge nbval
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/repo2docker">repo2docker</a></b> (🥈22 ·  ⭐ 1.3K) - 将存储库转换为支持Jupyter的Docker映像。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/repo2docker) (👨‍💻 100 · 🔀 270 · 📦 130 · 📋 440 - 31% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/jupyterhub/repo2docker
	```
- [PyPi](https://pypi.org/project/jupyter-repo2docker) (📥 4.3K / month):
	```
	pip install jupyter-repo2docker
	```
</details>
<details><summary><b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥈21 ·  ⭐ 2.1K) - Python中的交互式并行计算。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipython/ipyparallel) (👨‍💻 100 · 🔀 810 · 📦 1.8K · 📋 310 - 15% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/ipython/ipyparallel
	```
- [PyPi](https://pypi.org/project/ipyparallel):
	```
	pip install ipyparallel
	```
- [Conda](https://anaconda.org/conda-forge/ipyparallel) (📥 540K · ⏱️ 02.12.2021):
	```
	conda install -c conda-forge ipyparallel
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-sphinx">Jupyter Sphinx</a></b> (🥈20 ·  ⭐ 130) - Sphinx扩展，用于呈现Jupyter交互式小部件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-sphinx) (👨‍💻 24 · 🔀 45 · 📋 110 - 32% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/jupyter/jupyter-sphinx
	```
- [PyPi](https://pypi.org/project/jupyter_sphinx) (📥 75K / month):
	```
	pip install jupyter_sphinx
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter_client">Jupyter Client</a></b> (🥈17 ·  ⭐ 250 · 📉) - Jupyter protocol client APIs. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter_client) (👨‍💻 110 · 🔀 210 · 📥 110 · 📋 290 - 43% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/jupyter/jupyter_client
	```
- [PyPi](https://pypi.org/project/jupyter-client):
	```
	pip install jupyter-client
	```
</details>
<details><summary><b><a href="https://github.com/ReviewNB/treon">treon</a></b> (🥉16 ·  ⭐ 280 · 💀) - Jupyter Notebooks易于使用的测试框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ReviewNB/treon) (👨‍💻 4 · 🔀 19 · 📦 35 · 📋 11 - 18% open · ⏱️ 08.10.2020):

	```
	git clone https://github.com/ReviewNB/treon
	```
- [PyPi](https://pypi.org/project/treon) (📥 3.7K / month):
	```
	pip install treon
	```
</details>
<details><summary><b><a href="https://github.com/QuantEcon/sphinxcontrib-jupyter">sphinxcontrib.jupyter</a></b> (🥉15 ·  ⭐ 73 · 💀) - 用于生成Jupyter笔记本的Sphinx扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/QuantEcon/sphinxcontrib-jupyter) (👨‍💻 13 · 🔀 23 · 📦 24 · 📋 180 - 48% open · ⏱️ 18.06.2020):

	```
	git clone https://github.com/QuantEcon/sphinxcontrib-jupyter
	```
- [PyPi](https://pypi.org/project/sphinxcontrib-jupyter):
	```
	pip install sphinxcontrib-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/tweag/jupyterWith">JupyterWith</a></b> (🥉14 ·  ⭐ 300) - 声明性和可复制的Jupyter环境-由Nix提供支持。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tweag/jupyterWith) (👨‍💻 24 · 🔀 69 · 📋 88 - 53% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/tweag/jupyterWith
	```
</details>
<details><summary><b><a href="https://github.com/nbQA-dev/nbQA">nbQA</a></b> (🥉13 ·  ⭐ 380) - 在Jupyter Notebook上运行任何标准的Python代码质量工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbQA-dev/nbQA) (👨‍💻 17 · 🔀 22 · 📋 240 - 1% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/nbQA-dev/nbQA
	```
- [PyPi](https://pypi.org/project/nbqa):
	```
	pip install nbqa
	```
</details>
<details><summary><b><a href="https://github.com/nteract/testbook">testbook</a></b> (🥉13 ·  ⭐ 270) - 以正确的方式对Jupyter笔记本进行单元测试。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/testbook) (👨‍💻 14 · 🔀 26 · 📦 69 · 📋 79 - 43% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/nteract/testbook
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/nbopen">nbopen</a></b> (🥉13 ·  ⭐ 260 · 💀) - Open a Jupyter notebook in the best available server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/takluyver/nbopen) (👨‍💻 10 · 🔀 50 · 📋 60 - 58% open · ⏱️ 25.04.2018):

	```
	git clone https://github.com/takluyver/nbopen
	```
- [PyPi](https://pypi.org/project/nbopen) (📥 1.1K / month):
	```
	pip install nbopen
	```
</details>
<details><summary><b><a href="https://github.com/chmp/ipytest">ipytest</a></b> (🥉12 ·  ⭐ 180) - IPython笔记本中的Pytest。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chmp/ipytest) (👨‍💻 4 · 🔀 18 · 📦 130 · 📋 43 - 4% open · ⏱️ 28.07.2021):

	```
	git clone https://github.com/chmp/ipytest
	```
- [PyPi](https://pypi.org/project/ipytest):
	```
	pip install ipytest
	```
</details>
<details><summary><b><a href="https://github.com/treebeardtech/nbmake-action">nbmake-action</a></b> (🥉12 ·  ⭐ 150) - GitHub用于测试笔记本的动作。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/treebeardtech/nbmake-action) (👨‍💻 2 · 🔀 6 · ⏱️ 21.09.2021):

	```
	git clone https://github.com/treebeardtech/nbmake-action
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-naas/naas">naas</a></b> (🥉12 ·  ⭐ 150 · 📈) - Notebook调度工具，像API一样运行它们。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/jupyter-naas/naas) (👨‍💻 13 · 🔀 11 · 📦 3 · 📋 120 - 66% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/jupyter-naas/naas
	```
- [PyPi](https://pypi.org/project/naas) (📥 4.6K / month):
	```
	pip install naas
	```
</details>
<details><summary><b><a href="https://github.com/datitran/jupyter2slides">jupyter2slides</a></b> (🥉11 ·  ⭐ 770 · 💀) - 使用Jupyter Notebook的Cloud Native演示幻灯片<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/datitran/jupyter2slides) (🔀 160 · 📋 15 - 73% open · ⏱️ 28.12.2018):

	```
	git clone https://github.com/datitran/jupyter2slides
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/jupyter_kernel_mgmt">Kernel Management</a></b> (🥉11 ·  ⭐ 13 · 💀) - 针对Jupyter的实验性新内核管理框架。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/takluyver/jupyter_kernel_mgmt) (👨‍💻 74 · 🔀 7 · 📥 17 · 📋 24 - 41% open · ⏱️ 29.01.2020):

	```
	git clone https://github.com/takluyver/jupyter_kernel_mgmt
	```
- [PyPi](https://pypi.org/project/jupyter-kernel-mgmt) (📥 19 / month):
	```
	pip install jupyter-kernel-mgmt
	```
</details>
<details><summary><b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉10 ·  ⭐ 140) - 适用于GPU和一般设备的jupyter / ipython实验容器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/stas00/ipyexperiments) (👨‍💻 3 · 🔀 10 · 📦 5 · ⏱️ 07.12.2021):

	```
	git clone https://github.com/stas00/ipyexperiments
	```
- [PyPi](https://pypi.org/project/ipyexperiments):
	```
	pip install ipyexperiments
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyter-helpers">Jupyter Helpers</a></b> (🥉10 ·  ⭐ 40) - Jupyter/IPython的帮助程序集合。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyter-helpers) (👨‍💻 2 · 🔀 3 · 📋 5 - 60% open · ⏱️ 31.07.2021):

	```
	git clone https://github.com/krassowski/jupyter-helpers
	```
- [PyPi](https://pypi.org/project/jupyter_helpers):
	```
	pip install jupyter_helpers
	```
</details>
<details><summary><b><a href="https://github.com/Invictify/Jupter-Notebook-REST-API">Jupter-Notebook-REST-API</a></b> (🥉7 ·  ⭐ 37 · 💀) - 将jupyter笔记本作为REST API端点运行。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Invictify/Jupter-Notebook-REST-API) (👨‍💻 2 · 🔀 4 · ⏱️ 31.03.2020):

	```
	git clone https://github.com/Invictify/Jupter-Notebook-REST-API
	```
</details>
<br>

## JupyterLab渲染器

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_可以呈现和显示特定MIME类型文件的扩展名。_

<details><summary><b><a href="https://github.com/plotly/jupyterlab-dash">JupyterLab Dash</a></b> (🥇19 ·  ⭐ 350 · 💀) - An Extension for the Interactive development of Dash apps in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/jupyterlab-dash) (👨‍💻 7 · 🔀 55 · 📦 170 · 📋 28 - 71% open · ⏱️ 19.05.2020):

	```
	git clone https://github.com/plotly/jupyterlab-dash
	```
- [PyPi](https://pypi.org/project/jupyterlab-dash) (📥 1.5K / month):
	```
	pip install jupyterlab-dash
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-dash) (📥 12K / month):
	```
	npm install jupyterlab-dash
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-latex">JupyterLab Latex</a></b> (🥈18 ·  ⭐ 510) - JupyterLab扩展，用于实时编辑LaTeX文档。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-latex) (👨‍💻 21 · 🔀 55 · 📦 2 · 📋 82 - 34% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-latex
	```
- [PyPi](https://pypi.org/project/jupyterlab_latex) (📥 1.1K / month):
	```
	pip install jupyterlab_latex
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/latex) (📥 1.9K / month):
	```
	npm install @jupyterlab/latex
	```
</details>
<details><summary><b><a href="https://github.com/QuantStack/jupyterlab-drawio">JupyterLab Drawio</a></b> (🥈17 ·  ⭐ 510) - FOSS drawio/mxgraph程序包的独立嵌入。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/QuantStack/jupyterlab-drawio) (👨‍💻 15 · 🔀 56 · 📦 170 · 📋 64 - 60% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/QuantStack/jupyterlab-drawio
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-drawio) (📥 4.7K / month):
	```
	npm install jupyterlab-drawio
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyter-renderers">JupyterLab Renderers</a></b> (🥉16 ·  ⭐ 420) - JupyterLab的渲染器和渲染器扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyter-renderers) (👨‍💻 23 · 🔀 59 · 📦 1 · 📋 100 - 31% open · ⏱️ 31.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyter-renderers
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/geojson-extension) (📥 7.9K / month):
	```
	npm install @jupyterlab/geojson-extension
	```
</details>
<details><summary><b><a href="https://github.com/quigleyj97/jupyterlab-spreadsheet">JupyterLab Spreadsheet</a></b> (🥉15 ·  ⭐ 140) - JupyterLab插件，用于查看电子表格。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/quigleyj97/jupyterlab-spreadsheet) (👨‍💻 4 · 🔀 9 · 📋 23 - 21% open · ⏱️ 20.11.2021):

	```
	git clone https://github.com/quigleyj97/jupyterlab-spreadsheet
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-spreadsheet) (📥 4.9K / month):
	```
	npm install jupyterlab-spreadsheet
	```
</details>
<details><summary><b><a href="https://github.com/plotly/jupyterlab-chart-editor">JupyterLab Chart Editor</a></b> (🥉14 ·  ⭐ 200 · 💤) - JupyterLab扩展，用于实时编辑LaTeX文档。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/plotly/jupyterlab-chart-editor) (👨‍💻 5 · 🔀 20 · 📦 3 · 📋 31 - 38% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/plotly/jupyterlab-chart-editor
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-chart-editor) (📥 1.8K / month):
	```
	npm install jupyterlab-chart-editor
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/jupyterlab_voyager">JupyterLab Voyager</a></b> (🥉12 ·  ⭐ 260 · 💀) - JupyterLab extension visualize data with Voyager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/jupyterlab_voyager) (👨‍💻 6 · 🔀 31 · 📋 60 - 66% open · ⏱️ 14.08.2019):

	```
	git clone https://github.com/altair-viz/jupyterlab_voyager
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_voyager) (📥 65 / month):
	```
	npm install jupyterlab_voyager
	```
</details>
<br>

## JupyterLab主题

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_可以自定义JupyterLab外观的扩展。_

<details><summary><b><a href="https://github.com/telamonian/theme-darcula">Darcula Theme</a></b> (🥇15 ·  ⭐ 120) - A handsome Darcula theme for Jupyterlab. The first jlab theme to.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/telamonian/theme-darcula) (👨‍💻 7 · 🔀 18 · 📦 150 · 📋 21 - 23% open · ⏱️ 26.08.2021):

	```
	git clone https://github.com/telamonian/theme-darcula
	```
- [NPM](https://www.npmjs.com/package/@telamonian/theme-darcula) (📥 2.6K / month):
	```
	npm install @telamonian/theme-darcula
	```
</details>
<details><summary><b><a href="https://github.com/AllanChain/jupyterlab-theme-solarized-dark">jupyterlab-theme-solarized-dark</a></b> (🥇15 ·  ⭐ 50) - JupyterLab 2.x Solarized Dark扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/AllanChain/jupyterlab-theme-solarized-dark) (👨‍💻 2 · 🔀 6 · 📋 2 - 50% open · ⏱️ 16.11.2021):

	```
	git clone https://github.com/AllanChain/jupyterlab-theme-solarized-dark
	```
- [PyPi](https://pypi.org/project/jupyterlab_theme_solarized_dark):
	```
	pip install jupyterlab_theme_solarized_dark
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-theme-solarized-dark) (📥 3.7K / month):
	```
	npm install jupyterlab-theme-solarized-dark
	```
</details>
<details><summary><b><a href="https://github.com/yeebc/jupyterlab-neon-theme">Neon Theme</a></b> (🥈12 ·  ⭐ 110 · 💤) - JupyterLab的扁平，80年代霓虹灯启发主题。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/yeebc/jupyterlab-neon-theme) (👨‍💻 3 · 🔀 5 · 📦 1 · 📋 12 - 16% open · ⏱️ 07.03.2021):

	```
	git clone https://github.com/yeebc/jupyterlab-neon-theme
	```
- [NPM](https://www.npmjs.com/package/@yeebc/jupyterlab_neon_theme) (📥 1.5K / month):
	```
	npm install @yeebc/jupyterlab_neon_theme
	```
</details>
<details><summary><b><a href="https://github.com/oriolmirosa/jupyterlab_materialdarker">Material Darker Theme</a></b> (🥉11 ·  ⭐ 130) - JupyterLab的Material Darker主题。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/oriolmirosa/jupyterlab_materialdarker) (👨‍💻 2 · 🔀 14 · 📦 4 · 📋 16 - 12% open · ⏱️ 31.08.2021):

	```
	git clone https://github.com/oriolmirosa/jupyterlab_materialdarker
	```
- [NPM](https://www.npmjs.com/package/@oriolmirosa/jupyterlab_materialdarker) (📥 850 / month):
	```
	npm install @oriolmirosa/jupyterlab_materialdarker
	```
</details>
<details><summary><b><a href="https://github.com/mohirio/jupyterlab-horizon-theme">Horizon Theme</a></b> (🥉11 ·  ⭐ 44 · 💤) - JupyterLab的VSCode Horizo​​n主题端口。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mohirio/jupyterlab-horizon-theme) (🔀 1 · 📋 5 - 20% open · ⏱️ 11.04.2021):

	```
	git clone https://github.com/mohirio/jupyterlab-horizon-theme
	```
- [NPM](https://www.npmjs.com/package/@mohirio/jupyterlab-horizon-theme) (📥 2.2K / month):
	```
	npm install @mohirio/jupyterlab-horizon-theme
	```
</details>
<details><summary><b><a href="https://github.com/Rahlir/theme-gruvbox">Gruvbox Theme</a></b> (🥉8 ·  ⭐ 40 · 💀) - Jupyter Lab的Gruvbox黑暗主题。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Rahlir/theme-gruvbox) (👨‍💻 3 · 🔀 9 · ⏱️ 12.04.2020):

	```
	git clone https://github.com/Rahlir/theme-gruvbox
	```
- [NPM](https://www.npmjs.com/package/@rahlir/theme-gruvbox) (📥 120 / month):
	```
	npm install @rahlir/theme-gruvbox
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-theme-toggle">Theme Toggle</a></b> (🥉8 ·  ⭐ 10) - JupyterLab extension to toggle the theme in the Top Bar area. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-theme-toggle) (👨‍💻 2 · 🔀 2 · 📦 2 · 📋 3 - 66% open · ⏱️ 16.06.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-theme-toggle
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-theme-toggle) (📥 2.5K / month):
	```
	npm install jupyterlab-theme-toggle
	```
</details>
<details><summary><b><a href="https://github.com/kenshohara/theme-nord-extension">Nord Theme</a></b> (🥉6 ·  ⭐ 23 · 💀) - JupyterLab-Nord主题。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/kenshohara/theme-nord-extension) (🔀 1 · 📋 5 - 20% open · ⏱️ 20.09.2020):

	```
	git clone https://github.com/kenshohara/theme-nord-extension
	```
- [NPM](https://www.npmjs.com/package/@kenshohara/theme-nord-extension) (📥 28 / month):
	```
	npm install @kenshohara/theme-nord-extension
	```
</details>
<br>

## JupyterLab扩展

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_扩展JupyterLab自身功能的应用程序插件。_

<details><summary><b><a href="https://github.com/jupyter-lsp/jupyterlab-lsp">JupyterLab LSP</a></b> (🥇26 ·  ⭐ 1.1K) - JupyterLab的编码帮助（代码导航+悬停）。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-lsp/jupyterlab-lsp) (👨‍💻 38 · 🔀 82 · 📦 100 · 📋 380 - 33% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/krassowski/jupyterlab-lsp
	```
- [NPM](https://www.npmjs.com/package/@krassowski/jupyterlab-lsp) (📥 8.7K / month):
	```
	npm install @krassowski/jupyterlab-lsp
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-git">JupyterLab Git</a></b> (🥇26 ·  ⭐ 1K) - JupyterLab的Git扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-git) (👨‍💻 68 · 🔀 200 · 📦 14 · 📋 500 - 16% open · ⏱️ 13.11.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-git
	```
- [PyPi](https://pypi.org/project/jupyterlab-git) (📥 110K / month):
	```
	pip install jupyterlab-git
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-git) (📥 110K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge jupyterlab-git
	```
</details>
<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥇24 ·  ⭐ 4K) - 通过WebAssembly进行流式透视显示。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 65 · 🔀 410 · 📦 220 · 📋 480 - 12% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/finos/perspective
	```
- [PyPi](https://pypi.org/project/perspective-python) (📥 4.8K / month):
	```
	pip install perspective-python
	```
- [NPM](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 2.1K / month):
	```
	npm install @finos/perspective-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/elyra-ai/elyra">elyra</a></b> (🥇23 ·  ⭐ 1.2K) - Elyra以AI为中心的方法对JupyterLab笔记本进行拓展。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/elyra-ai/elyra) (👨‍💻 38 · 🔀 190 · 📦 28 · 📋 1.3K - 17% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/elyra-ai/elyra
	```
- [PyPi](https://pypi.org/project/elyra) (📥 1.8K / month):
	```
	pip install elyra
	```
- [Conda](https://anaconda.org/conda-forge/elyra) (📥 8.9K · ⏱️ 27.04.2021):
	```
	conda install -c conda-forge elyra
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/debugger">JupyterLab Debugger</a></b> (🥇23 ·  ⭐ 530 · 💤) - 适用于Jupyter笔记本电脑，控制台等的可视调试器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/debugger) (👨‍💻 11 · 🔀 36 · 📦 130 · 📋 260 - 6% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/jupyterlab/debugger
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/debugger) (📥 89K / month):
	```
	npm install @jupyterlab/debugger
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-toc">JupyterLab TOC</a></b> (🥈21 ·  ⭐ 700) - Table of Contents extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-toc) (👨‍💻 14 · 🔀 100 · 📦 150 · 📋 120 - 55% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-toc
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/toc) (📥 110K / month):
	```
	npm install @jupyterlab/toc
	```
</details>
<details><summary><b><a href="https://github.com/lckr/jupyterlab-variableInspector">Variable Inspector</a></b> (🥈20 ·  ⭐ 870) - Jupyterlab的变量查看器扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lckr/jupyterlab-variableInspector) (👨‍💻 17 · 🔀 76 · 📦 3 · 📋 150 - 24% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/lckr/jupyterlab-variableInspector
	```
- [NPM](https://www.npmjs.com/package/@lckr/jupyterlab_variableinspector) (📥 11K / month):
	```
	npm install @lckr/jupyterlab_variableinspector
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-github">JupyterLab GitHub</a></b> (🥈19 ·  ⭐ 310) - GitHub integration for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-github) (👨‍💻 15 · 🔀 78 · 📦 2 · 📋 57 - 36% open · ⏱️ 10.12.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-github
	```
- [PyPi](https://pypi.org/project/jupyterlab-github):
	```
	pip install jupyterlab-github
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/github) (📥 1.3K / month):
	```
	npm install @jupyterlab/github
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-system-monitor">JupyterLab System Monitor</a></b> (🥈19 ·  ⭐ 220) - JupyterLab扩展以显示系统指标。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-system-monitor) (👨‍💻 6 · 🔀 26 · 📦 27 · 📋 35 - 45% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-system-monitor
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-system-monitor) (📥 11K / month):
	```
	npm install jupyterlab-system-monitor
	```
</details>
<details><summary><b><a href="https://github.com/ryantam626/jupyterlab_code_formatter">Code Formatter</a></b> (🥈17 ·  ⭐ 490 · 💤) - JupyterLab的通用代码格式化工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ryantam626/jupyterlab_code_formatter) (👨‍💻 30 · 🔀 39 · 📋 140 - 15% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/ryantam626/jupyterlab_code_formatter
	```
- [PyPi](https://pypi.org/project/jupyterlab_code_formatter) (📥 16K / month):
	```
	pip install jupyterlab_code_formatter
	```
- [NPM](https://www.npmjs.com/package/@ryantam626/jupyterlab_code_formatter) (📥 6.4K / month):
	```
	npm install @ryantam626/jupyterlab_code_formatter
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/jupyterlab-nvdashboard">GPU Dashboards</a></b> (🥈17 ·  ⭐ 440) - 一个JupyterLab扩展，用于显示GPU的仪表板。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rapidsai/jupyterlab-nvdashboard) (👨‍💻 15 · 🔀 52 · 📋 52 - 46% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/rapidsai/jupyterlab-nvdashboard
	```
- [PyPi](https://pypi.org/project/jupyterlab-nvdashboard) (📥 9.3K / month):
	```
	pip install jupyterlab-nvdashboard
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-nvdashboard) (📥 7.3K / month):
	```
	npm install jupyterlab-nvdashboard
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-google-drive">JupyterLab Google Drive</a></b> (🥈17 ·  ⭐ 350) - 使用Google云端硬盘的JupyterLab的云存储。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-google-drive) (👨‍💻 15 · 🔀 68 · 📦 2 · 📋 95 - 31% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-google-drive
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/google-drive) (📥 4.2K / month):
	```
	npm install @jupyterlab/google-drive
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/jupyterlab_templates">JupyterLab Templates</a></b> (🥈17 ·  ⭐ 280) - 在jupyterlab的jupyter-Notebook各种模板。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/jupyterlab_templates) (👨‍💻 14 · 🔀 49 · 📦 4 · 📋 78 - 10% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/jpmorganchase/jupyterlab_templates
	```
- [PyPi](https://pypi.org/project/jupyterlab_templates) (📥 3.4K / month):
	```
	pip install jupyterlab_templates
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_templates) (📥 3.4K / month):
	```
	npm install jupyterlab_templates
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask-labextension">dask-labextension</a></b> (🥈17 ·  ⭐ 240) - JupyterLab扩展，用于实时编辑LaTeX文档。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-labextension) (👨‍💻 18 · 🔀 44 · 📋 120 - 30% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/dask/dask-labextension
	```
- [PyPi](https://pypi.org/project/dask-labextension):
	```
	pip install dask-labextension
	```
- [Conda](https://anaconda.org/conda-forge/dask-labextension) (📥 490K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge dask-labextension
	```
- [NPM](https://www.npmjs.com/package/dask-labextension) (📥 4.4K / month):
	```
	npm install dask-labextension
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/jupyterlab-sidecar">JupyterLab SideCar</a></b> (🥈17 ·  ⭐ 190) - JupyterLab的sidecar输出小部件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/jupyterlab-sidecar) (👨‍💻 13 · 🔀 35 · 📦 3 · 📋 29 - 65% open · ⏱️ 04.07.2021):

	```
	git clone https://github.com/jupyter-widgets/jupyterlab-sidecar
	```
- [PyPi](https://pypi.org/project/sidecar) (📥 2.2K / month):
	```
	pip install sidecar
	```
- [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-sidecar) (📥 790 / month):
	```
	npm install @jupyter-widgets/jupyterlab-sidecar
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/spellchecker">JupyterLab Spellchecker</a></b> (🥈17 ·  ⭐ 140) - JupyterLab笔记本降价单元的拼写检查器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/spellchecker) (👨‍💻 6 · 🔀 16 · 📦 1 · 📋 42 - 21% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/ijmbarr/jupyterlab_spellchecker
	```
- [NPM](https://www.npmjs.com/package/@ijmbarr/jupyterlab_spellchecker) (📥 2.2K / month):
	```
	npm install @ijmbarr/jupyterlab_spellchecker
	```
</details>
<details><summary><b><a href="https://github.com/jwkvam/jupyterlab-vim">JupyterLab Vim</a></b> (🥈16 ·  ⭐ 900 · 💀) - 用于JupyterLab的Vim笔记本cell绑定。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jwkvam/jupyterlab-vim) (👨‍💻 8 · 🔀 71 · 📦 3 · 📋 96 - 56% open · ⏱️ 16.07.2019):

	```
	git clone https://github.com/jwkvam/jupyterlab-vim
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_vim) (📥 540 / month):
	```
	npm install jupyterlab_vim
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyterlab-go-to-definition">JupyterLab Go-To-Definition</a></b> (🥈16 ·  ⭐ 210) - 变量的定义查看器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyterlab-go-to-definition) (👨‍💻 2 · 🔀 9 · 📦 11 · 📋 23 - 43% open · ⏱️ 28.07.2021):

	```
	git clone https://github.com/krassowski/jupyterlab-go-to-definition
	```
- [NPM](https://www.npmjs.com/package/@krassowski/jupyterlab_go_to_definition) (📥 3.6K / month):
	```
	npm install @krassowski/jupyterlab_go_to_definition
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-data-explorer">JupyterLab Data Explorer</a></b> (🥈16 ·  ⭐ 160 · 💀) - JupyterLab中的一流数据集。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-data-explorer) (👨‍💻 9 · 🔀 34 · 📦 10 · 📋 91 - 62% open · ⏱️ 24.05.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-data-explorer
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/dataregistry-extension) (📥 100 / month):
	```
	npm install @jupyterlab/dataregistry-extension
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_iframe">JupyterLab IFrame</a></b> (🥈16 ·  ⭐ 75) - JupyterLab iframe小部件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_iframe) (👨‍💻 5 · 🔀 15 · 📦 3 · 📋 63 - 7% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_iframe
	```
- [PyPi](https://pypi.org/project/jupyterlab_iframe):
	```
	pip install jupyterlab_iframe
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_iframe) (📥 1.2K / month):
	```
	npm install jupyterlab_iframe
	```
</details>
<details><summary><b><a href="https://github.com/vatlab/jupyterlab-sos">jupyterlab-sos</a></b> (🥈16 ·  ⭐ 47) - 适用于SoS Polyglot笔记本和工作流程的Jupyterlab扩展<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/jupyterlab-sos) (👨‍💻 4 · 🔀 3 · 📦 5 · 📋 58 - 17% open · ⏱️ 12.11.2021):

	```
	git clone https://github.com/vatlab/jupyterlab-sos
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-sos) (📥 13K · ⏱️ 16.04.2021):
	```
	conda install -c conda-forge jupyterlab-sos
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-sos) (📥 100 / month):
	```
	npm install jupyterlab-sos
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/lantern">Lantern</a></b> (🥉15 ·  ⭐ 300) - 数据探索工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/lantern) (👨‍💻 2 · 🔀 19 · 📦 14 · 📋 200 - 5% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/timkpaine/lantern
	```
- [PyPi](https://pypi.org/project/pylantern):
	```
	pip install pylantern
	```
</details>
<details><summary><b><a href="https://github.com/deshaw/jupyterlab-execute-time">jupyterlab-execute-time</a></b> (🥉15 ·  ⭐ 190) - 为Jupyter Lab执行时间插件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/deshaw/jupyterlab-execute-time) (👨‍💻 10 · 🔀 25 · 📋 27 - 3% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/deshaw/jupyterlab-execute-time
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-execute-time) (📥 4.1K / month):
	```
	npm install jupyterlab-execute-time
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-celltags">jupyterlab-celltags</a></b> (🥉15 ·  ⭐ 110 · 💀) - 一个JupyterLab扩展，用于显示GPU的仪表板。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-celltags) (👨‍💻 10 · 🔀 25 · 📦 330 · 📋 18 - 61% open · ⏱️ 29.04.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-celltags
	```
</details>
<details><summary><b><a href="https://github.com/pbugnion/jupyterlab-sql">JupyterLab SQL</a></b> (🥉14 ·  ⭐ 360 · 💀) - JupyterLab的SQL GUI。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pbugnion/jupyterlab-sql) (👨‍💻 2 · 🔀 43 · 📋 74 - 50% open · ⏱️ 04.01.2020):

	```
	git clone https://github.com/pbugnion/jupyterlab-sql
	```
- [PyPi](https://pypi.org/project/jupyterlab_sql) (📥 670 / month):
	```
	pip install jupyterlab_sql
	```
</details>
<details><summary><b><a href="https://github.com/chaoleili/jupyterlab_tensorboard">JupyterLab Tensorboard</a></b> (🥉14 ·  ⭐ 280 · 💤) - Jupyterlab的Tensorboard扩展。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chaoleili/jupyterlab_tensorboard) (👨‍💻 6 · 🔀 27 · 📦 2 · 📋 26 - 61% open · ⏱️ 24.02.2021):

	```
	git clone https://github.com/chaoleili/jupyterlab_tensorboard
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_tensorboard) (📥 7.6K / month):
	```
	npm install jupyterlab_tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/jupyter_bokeh">Jupyter Bokeh</a></b> (🥉14 ·  ⭐ 190) - 用于在JupyterLab笔记本中呈现Bokeh内容的扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/jupyter_bokeh) (👨‍💻 16 · 🔀 35 · 📋 79 - 11% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/bokeh/jupyter_bokeh
	```
- [PyPi](https://pypi.org/project/jupyter-bokeh) (📥 5.6K / month):
	```
	pip install jupyter-bokeh
	```
- [NPM](https://www.npmjs.com/package/@bokeh/jupyter_bokeh) (📥 25K / month):
	```
	npm install @bokeh/jupyter_bokeh
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/ipylab">ipylab</a></b> (🥉14 ·  ⭐ 90) - 使用Jupyter小部件从Python笔记本控制JupyterLab。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/ipylab) (👨‍💻 5 · 🔀 4 · 📥 21 · 📋 26 - 34% open · ⏱️ 14.11.2021):

	```
	git clone https://github.com/jtpio/ipylab
	```
- [PyPi](https://pypi.org/project/ipylab):
	```
	pip install ipylab
	```
- [Conda](https://anaconda.org/conda-forge/ipylab) (📥 8K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge ipylab
	```
</details>
<details><summary><b><a href="https://github.com/parente/jupyterlab-quickopen">JupyterLab Quickopen</a></b> (🥉14 ·  ⭐ 70) - 通过在JupyterLab中键入文件的一部分来快速打开文件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/parente/jupyterlab-quickopen) (👨‍💻 5 · 🔀 6 · ⏱️ 12.12.2021):

	```
	git clone https://github.com/parente/jupyterlab-quickopen
	```
- [PyPi](https://pypi.org/project/jupyterlab-quickopen):
	```
	pip install jupyterlab-quickopen
	```
- [NPM](https://www.npmjs.com/package/@parente/jupyterlab-quickopen) (📥 43 / month):
	```
	npm install @parente/jupyterlab-quickopen
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-shortcutui">JupyterLab Shortcutui</a></b> (🥉14 ·  ⭐ 55 · 💀) - 一个JupyterLab扩展，用于显示GPU的仪表板。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-shortcutui) (👨‍💻 8 · 🔀 15 · 📋 13 - 53% open · ⏱️ 17.01.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-shortcutui
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/shortcutui) (📥 330 / month):
	```
	npm install @jupyterlab/shortcutui
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/gather">nbgather</a></b> (🥉13 ·  ⭐ 420 · 💀) - Jupyter笔记本分割工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/gather) (👨‍💻 12 · 🔀 27 · 📋 26 - 38% open · ⏱️ 14.02.2020):

	```
	git clone https://github.com/microsoft/gather
	```
- [NPM](https://www.npmjs.com/package/nbgather) (📥 54 / month):
	```
	npm install nbgather
	```
</details>
<details><summary><b><a href="https://github.com/aquirdTurtle/Collapsible_Headings">Collapsible Headings</a></b> (🥉13 ·  ⭐ 160 · 💤) - 为Jupyter实验室笔记本实现可折叠页眉。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/aquirdTurtle/Collapsible_Headings) (👨‍💻 6 · 🔀 7 · 📋 29 - 24% open · ⏱️ 22.05.2021):

	```
	git clone https://github.com/aquirdTurtle/Collapsible_Headings
	```
- [NPM](https://www.npmjs.com/package/@aquirdturtle/collapsible_headings) (📥 2.4K / month):
	```
	npm install @aquirdturtle/collapsible_headings
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-commenting">JupyterLab Commenting</a></b> (🥉13 ·  ⭐ 86 · 💀) - JupyterLab的注释和注释。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-commenting) (👨‍💻 10 · 🔀 22 · 📋 34 - 70% open · ⏱️ 01.05.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-commenting
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/commenting-extension) (📥 150 / month):
	```
	npm install @jupyterlab/commenting-extension
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-hdf5">JupyterLab HDF5</a></b> (🥉13 ·  ⭐ 81) - 在JupyterLab中打开和浏览HDF5文件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-hdf5) (👨‍💻 6 · 🔀 17 · 📋 42 - 21% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-hdf5
	```
- [PyPi](https://pypi.org/project/jupyterlab_hdf) (📥 520 / month):
	```
	pip install jupyterlab_hdf
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/hdf5) (📥 350 / month):
	```
	npm install @jupyterlab/hdf5
	```
</details>
<details><summary><b><a href="https://github.com/itsjafer/jupyterlab-sparkmonitor">jupyterlab-sparkmonitor</a></b> (🥉13 ·  ⭐ 68) - JupyterLab扩展，可启动监控。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/itsjafer/jupyterlab-sparkmonitor) (👨‍💻 9 · 🔀 15 · 📋 15 - 46% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/itsjafer/jupyterlab-sparkmonitor
	```
- [PyPi](https://pypi.org/project/jupyterlab-sparkmonitor) (📥 330 / month):
	```
	pip install jupyterlab-sparkmonitor
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_sparkmonitor) (📥 96 / month):
	```
	npm install jupyterlab_sparkmonitor
	```
- [Docker Hub](https://hub.docker.com/r/itsjafer/sparkmonitor) (📥 240 · ⏱️ 02.06.2021):
	```
	docker pull itsjafer/sparkmonitor
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyterlab-kernelspy">JupyterLab Kernelspy</a></b> (🥉13 ·  ⭐ 63) - Jupyter Lab扩展，用于检查往返于邮件的信息。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyterlab-kernelspy) (👨‍💻 4 · 🔀 8 · 📦 3 · 📋 13 - 15% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/jupyterlab-contrib/jupyterlab-kernelspy
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-kernelspy) (📥 140 / month):
	```
	npm install jupyterlab-kernelspy
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_autoversion">JupyterLab Autoversion</a></b> (🥉13 ·  ⭐ 54) - 在JupyterLab中Jupyter笔记本的自动版本控制。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_autoversion) (👨‍💻 4 · 🔀 6 · 📋 29 - 17% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_autoversion
	```
- [PyPi](https://pypi.org/project/jupyterlab_autoversion) (📥 120 / month):
	```
	pip install jupyterlab_autoversion
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_autoversion) (📥 36 / month):
	```
	npm install jupyterlab_autoversion
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-python-file">JupyterLab Python Files</a></b> (🥉13 ·  ⭐ 49) - JupyterLab扩展来创建Python文件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-python-file) (👨‍💻 4 · 🔀 7 · 📥 76 · 📋 9 - 11% open · ⏱️ 27.08.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-python-file
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-python-file) (📥 2.5K / month):
	```
	npm install jupyterlab-python-file
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_commands">jupyterlab_commands</a></b> (🥉13 ·  ⭐ 35) - Add arbitrary python commands to the jupyterlab.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_commands) (🔀 6 · 📦 3 · 📋 23 - 4% open · ⏱️ 30.11.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_commands
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/jupyter-fs">jupyter-fs</a></b> (🥉12 ·  ⭐ 100) - 类似文件系统的内容管理器，用于Jupyter中的多个后端。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/jupyter-fs) (👨‍💻 8 · 🔀 21 · 📋 49 - 26% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/jpmorganchase/jupyter-fs
	```
- [PyPi](https://pypi.org/project/jupyter-fs) (📥 430 / month):
	```
	pip install jupyter-fs
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/nbcelltests">nbcelltests</a></b> (🥉12 ·  ⭐ 59) - 用于Jupyter笔记本的逐个cell测试工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/nbcelltests) (👨‍💻 7 · 🔀 16 · 📋 110 - 26% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/jpmorganchase/nbcelltests
	```
- [PyPi](https://pypi.org/project/nbcelltests):
	```
	pip install nbcelltests
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_celltests) (📥 27 / month):
	```
	npm install jupyterlab_celltests
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Email</a></b> (🥉12 ·  ⭐ 50) - 一个jupyterlab扩展，可以直接从中发送电子邮件笔记本。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (🔀 2 · 📋 36 - 16% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_email
	```
- [PyPi](https://pypi.org/project/jupyterlab_email) (📥 73 / month):
	```
	pip install jupyterlab_email
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_email) (📥 240 / month):
	```
	npm install jupyterlab_email
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Flake8</a></b> (🥉12 ·  ⭐ 50) - 一个jupyterlab扩展，可以直接从中发送电子邮件笔记本。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (🔀 2 · 📋 36 - 16% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_email
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-flake8) (📥 290 / month):
	```
	npm install jupyterlab-flake8
	```
</details>
<details><summary><b><a href="https://github.com/mlshapiro/jupyterlab-flake8">jupyterlab-flake8</a></b> (🥉10 ·  ⭐ 100) - Jupyterlab用于笔记本和文本文件的python连接器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mlshapiro/jupyterlab-flake8) (👨‍💻 5 · 🔀 9 · 📋 37 - 10% open · ⏱️ 16.09.2021):

	```
	git clone https://github.com/mlshapiro/jupyterlab-flake8
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-flake8) (📥 290 / month):
	```
	npm install jupyterlab-flake8
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/knowledgelab">KnowledgeLab</a></b> (🥉10 ·  ⭐ 43) - KnowledgeRepo + JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/knowledgelab) (👨‍💻 3 · 🔀 6 · 📦 2 · 📋 27 - 11% open · ⏱️ 12.12.2021):

	```
	git clone https://github.com/timkpaine/knowledgelab
	```
- [PyPi](https://pypi.org/project/knowledgelab) (📥 5 / month):
	```
	pip install knowledgelab
	```
- [NPM](https://www.npmjs.com/package/knowledgelab) (📥 6 / month):
	```
	npm install knowledgelab
	```
</details>
<details><summary><b><a href="https://github.com/manuzhang/jupyterlab_spark">JupyterLab Spark</a></b> (🥉10 ·  ⭐ 7) - JupyterLab的Spark应用程序UI扩展。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/manuzhang/jupyterlab_spark) (👨‍💻 2 · 🔀 2 · 📋 5 - 40% open · ⏱️ 05.09.2021):

	```
	git clone https://github.com/manuzhang/jupyterlab_spark
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_spark) (📥 87 / month):
	```
	npm install jupyterlab_spark
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-topbar">JupyterLab Top Bar</a></b> (🥉10 ·  ⭐ 2) - JupyterLab顶部栏扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-topbar) (👨‍💻 4 · 🔀 1 · ⏱️ 07.12.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-topbar
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-topbar-extension) (📥 11K / month):
	```
	npm install jupyterlab-topbar-extension
	```
</details>
<details><summary><b><a href="https://github.com/ReviewNB/jupyterlab-gitplus">jupyterlab-gitplus</a></b> (🥉9 ·  ⭐ 89) - JupyterLab扩展来创建Python文件。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/ReviewNB/jupyterlab-gitplus) (👨‍💻 2 · 🔀 8 · 📋 10 - 20% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/ReviewNB/jupyterlab-gitplus
	```
- [PyPi](https://pypi.org/project/jupyterlab_gitplus) (📥 41 / month):
	```
	pip install jupyterlab_gitplus
	```
- [NPM](https://www.npmjs.com/package/@reviewnb/jupyterlab_gitplus) (📥 95 / month):
	```
	npm install @reviewnb/jupyterlab_gitplus
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-python-bytecode">JupyterLab Bytecode</a></b> (🥉8 ·  ⭐ 57 · 💀) - JupyterLab扩展，以探索CPython字节码。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-python-bytecode) (👨‍💻 2 · 🔀 5 · 📋 5 - 40% open · ⏱️ 16.10.2020):

	```
	git clone https://github.com/jtpio/jupyterlab-python-bytecode
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-python-bytecode) (📥 17 / month):
	```
	npm install jupyterlab-python-bytecode
	```
</details>
<details><summary><b><a href="https://github.com/gavincyi/jupyterlab-executor">jupyterlab-executor</a></b> (🥉8 ·  ⭐ 4 · 💤) - JupyterLab扩展，以探索CPython字节码。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gavincyi/jupyterlab-executor) (👨‍💻 2 · 📥 2 · ⏱️ 24.03.2021):

	```
	git clone https://github.com/gavincyi/jupyterlab-executor
	```
- [PyPi](https://pypi.org/project/jupyterlab-executor) (📥 50 / month):
	```
	pip install jupyterlab-executor
	```
- [NPM](https://www.npmjs.com/package/@gavincyi/jupyterlab-executor) (📥 10 / month):
	```
	npm install @gavincyi/jupyterlab-executor
	```
</details>
<br>

## JupyterHub认证

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_管理和控制用户如何访问JupyterHub部署的身份验证模块。_

<details><summary><b><a href="https://github.com/jupyterhub/oauthenticator">OAuthenticator</a></b> (🥇24 ·  ⭐ 320) - OAuth + JupyterHub Authenticator = OAuthenticator. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/oauthenticator) (👨‍💻 100 · 🔀 290 · 📦 240 · 📋 210 - 12% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/jupyterhub/oauthenticator
	```
- [PyPi](https://pypi.org/project/oauthenticator) (📥 37K / month):
	```
	pip install oauthenticator
	```
- [Conda](https://anaconda.org/conda-forge/oauthenticator) (📥 19K · ⏱️ 19.07.2021):
	```
	conda install -c conda-forge oauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/ldapauthenticator">LDAP Authenticator</a></b> (🥇21 ·  ⭐ 170) - 用于Jupyter的LDAP Authenticator插件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ldapauthenticator) (👨‍💻 30 · 🔀 150 · 📦 83 · 📋 130 - 40% open · ⏱️ 27.06.2021):

	```
	git clone https://github.com/jupyterhub/ldapauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-ldapauthenticator) (📥 6.2K / month):
	```
	pip install jupyterhub-ldapauthenticator
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-ldapauthenticator) (📥 23K · ⏱️ 28.08.2020):
	```
	conda install -c conda-forge jupyterhub-ldapauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nativeauthenticator">Native Authenticator</a></b> (🥈20 ·  ⭐ 47 · 📈) - JupyterHub本地用户身份验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nativeauthenticator) (👨‍💻 21 · 🔀 50 · 📦 32 · 📋 89 - 23% open · ⏱️ 08.12.2021):

	```
	git clone https://github.com/jupyterhub/nativeauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-nativeauthenticator) (📥 16K / month):
	```
	pip install jupyterhub-nativeauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/ltiauthenticator">LTI Authenticator</a></b> (🥈19 ·  ⭐ 48) - 用于LTI的JupyterHub身份验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ltiauthenticator) (👨‍💻 11 · 🔀 35 · 📦 69 · 📋 31 - 16% open · ⏱️ 09.12.2021):

	```
	git clone https://github.com/jupyterhub/ltiauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-ltiauthenticator) (📥 2.6K / month):
	```
	pip install jupyterhub-ltiauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/firstuseauthenticator">First Use Authenticator</a></b> (🥈16 ·  ⭐ 38) - JupyterHub Authenticator，可以让用户进行设置。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/firstuseauthenticator) (👨‍💻 12 · 🔀 20 · 📦 55 · 📋 22 - 22% open · ⏱️ 28.10.2021):

	```
	git clone https://github.com/jupyterhub/firstuseauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-firstuseauthenticator) (📥 4.3K / month):
	```
	pip install jupyterhub-firstuseauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/dummyauthenticator">dummyauthenticator</a></b> (🥈14 ·  ⭐ 28 · 💤) - 虚拟的JupyterHub Authenticator使测试变得容易。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/dummyauthenticator) (🔀 14 · 📦 92 · 📋 7 - 71% open · ⏱️ 12.02.2021):

	```
	git clone https://github.com/jupyterhub/dummyauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-dummyauthenticator) (📥 2.2K / month):
	```
	pip install jupyterhub-dummyauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/mogthesprog/jwtauthenticator">JWT Authenticator</a></b> (🥉13 ·  ⭐ 38 · 💀) - JupyterHub的令牌验证器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mogthesprog/jwtauthenticator) (👨‍💻 7 · 🔀 36 · 📦 8 · 📋 17 - 52% open · ⏱️ 13.02.2019):

	```
	git clone https://github.com/mogthesprog/jwtauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-jwtauthenticator) (📥 270 / month):
	```
	pip install jupyterhub-jwtauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nullauthenticator">Null Authenticator</a></b> (🥉13 ·  ⭐ 7 · 💤) - Null Authenticator for JupyterHub instances that should.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nullauthenticator) (👨‍💻 5 · 🔀 9 · 📦 70 · ⏱️ 09.02.2021):

	```
	git clone https://github.com/jupyterhub/nullauthenticator
	```
- [PyPi](https://pypi.org/project/nullauthenticator) (📥 2.3K / month):
	```
	pip install nullauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/cwaldbieser/jhub_remote_user_authenticator">Remote User Auth</a></b> (🥉12 ·  ⭐ 32 · 💀) - Jupyterhub的REMOTE_USER身份验证器。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/cwaldbieser/jhub_remote_user_authenticator) (👨‍💻 5 · 🔀 26 · 📋 16 - 43% open · ⏱️ 16.04.2019):

	```
	git clone https://github.com/cwaldbieser/jhub_remote_user_authenticator
	```
- [PyPi](https://pypi.org/project/jhub_remote_user_authenticator) (📥 1.3K / month):
	```
	pip install jhub_remote_user_authenticator
	```
</details>
<details><summary><b><a href="https://github.com/HewlettPackard/jupyterhub-samlauthenticator">SAML Authenticator</a></b> (🥉12 ·  ⭐ 30) - jupyterhub-samlauthenticator。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HewlettPackard/jupyterhub-samlauthenticator) (👨‍💻 6 · 🔀 16 · 📥 13 · 📋 28 - 50% open · ⏱️ 25.08.2021):

	```
	git clone https://github.com/HewlettPackard/jupyterhub-samlauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-samlauthenticator) (📥 380 / month):
	```
	pip install jupyterhub-samlauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/ucphhpc/jhub-authenticators">Remote Authenticator</a></b> (🥉10 ·  ⭐ 1) - JupyterHub Authenticators的集合。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ucphhpc/jhub-authenticators) (👨‍💻 5 · 🔀 1 · ⏱️ 25.10.2021):

	```
	git clone https://github.com/rasmunk/jhub-authenticators
	```
- [PyPi](https://pypi.org/project/jhub-authenticators) (📥 32 / month):
	```
	pip install jhub-authenticators
	```
</details>
<details><summary><b><a href="https://github.com/cwaldbieser/jhub_cas_authenticator">CAS Authenticator</a></b> (🥉9 ·  ⭐ 16 · 💀) - Jupyterhub的CAS验证器。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/cwaldbieser/jhub_cas_authenticator) (👨‍💻 4 · 🔀 10 · 📋 11 - 9% open · ⏱️ 27.03.2020):

	```
	git clone https://github.com/cwaldbieser/jhub_cas_authenticator
	```
- [PyPi](https://pypi.org/project/jhub_cas_authenticator) (📥 160 / month):
	```
	pip install jhub_cas_authenticator
	```
</details>
<details><summary><b><a href="https://github.com/thedataincubator/jupyterhub-hashauthenticator">Hash Authenticator</a></b> (🥉9 ·  ⭐ 4 · 💤) - 使用从其生成的密码对用户进行身份验证。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/thedataincubator/jupyterhub-hashauthenticator) (👨‍💻 3 · 🔀 3 · ⏱️ 09.03.2021):

	```
	git clone https://github.com/thedataincubator/jupyterhub-hashauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-hashauthenticator) (📥 57 / month):
	```
	pip install jupyterhub-hashauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/kerberosauthenticator">Keberos Authenticator</a></b> (🥉8 ·  ⭐ 10 · 💀) - 用于LTI的JupyterHub身份验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/kerberosauthenticator) (👨‍💻 2 · 🔀 4 · 📋 5 - 60% open · ⏱️ 16.07.2019):

	```
	git clone https://github.com/jupyterhub/kerberosauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-kerberosauthenticator) (📥 28 / month):
	```
	pip install jupyterhub-kerberosauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/andreas-h/sshauthenticator">SSH Authenticator</a></b> (🥉6 ·  ⭐ 5 · 💀) - JupyterHub的简单SSH身份验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/andreas-h/sshauthenticator) (🔀 1 · ⏱️ 03.09.2019):

	```
	git clone https://github.com/andreas-h/sshauthenticator
	```
</details>
<br>

## JupyterHub容器等

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_启动、监视和停止单用户笔记本服务器的派生模块。_

<details><summary><b><a href="https://github.com/jupyterhub/kubespawner">KubeSpawner</a></b> (🥇21 ·  ⭐ 390) - Kubernetes spawner for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/kubespawner) (👨‍💻 66 · 🔀 230 · 📦 100 · 📋 270 - 19% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/jupyterhub/kubespawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-kubespawner) (📥 140K / month):
	```
	pip install jupyterhub-kubespawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/dockerspawner">DockerSpawner</a></b> (🥈20 ·  ⭐ 400) - 在Docker容器中生成JupyterHub单用户服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/dockerspawner) (👨‍💻 62 · 🔀 260 · 📦 110 · 📋 250 - 5% open · ⏱️ 27.11.2021):

	```
	git clone https://github.com/jupyterhub/dockerspawner
	```
- [PyPi](https://pypi.org/project/dockerspawner) (📥 6.3K / month):
	```
	pip install dockerspawner
	```
- [Conda](https://anaconda.org/conda-forge/dockerspawner) (📥 9.9K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge dockerspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/batchspawner">BatchSpawner</a></b> (🥈19 ·  ⭐ 130 · 💤) - 用于Jupyterhub的自定义Spawner，可按计划批量启动服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/batchspawner) (👨‍💻 38 · 🔀 91 · 📦 11 · 📋 110 - 37% open · ⏱️ 05.05.2021):

	```
	git clone https://github.com/jupyterhub/batchspawner
	```
- [PyPi](https://pypi.org/project/batchspawner) (📥 760 / month):
	```
	pip install batchspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/systemdspawner">SystemdSpawner</a></b> (🥉16 ·  ⭐ 75) - 使用Systemd生成JupyterHub单用户笔记本服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/systemdspawner) (👨‍💻 17 · 🔀 37 · 📦 19 · 📋 54 - 46% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/jupyterhub/systemdspawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-systemdspawner) (📥 1.9K / month):
	```
	pip install jupyterhub-systemdspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/sudospawner">SudoSpawner</a></b> (🥉14 ·  ⭐ 42) - 使用Systemd生成JupyterHub单用户笔记本服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/sudospawner) (👨‍💻 14 · 🔀 36 · 📦 35 · 📋 37 - 45% open · ⏱️ 10.09.2021):

	```
	git clone https://github.com/jupyterhub/sudospawner
	```
- [PyPi](https://pypi.org/project/sudospawner) (📥 810 / month):
	```
	pip install sudospawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/wrapspawner">WrapSpawner</a></b> (🥉13 ·  ⭐ 49) - JupyterHub的生成器的运行时配置机制。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/wrapspawner) (👨‍💻 16 · 🔀 42 · 📦 5 · 📋 28 - 53% open · ⏱️ 07.07.2021):

	```
	git clone https://github.com/jupyterhub/wrapspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/yarnspawner">YarnSpawner</a></b> (🥉11 ·  ⭐ 19 · 💀) - 在Hadoop/YARN中生成JupyterHub单用户笔记本服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/yarnspawner) (👨‍💻 2 · 🔀 9 · 📋 9 - 55% open · ⏱️ 16.07.2019):

	```
	git clone https://github.com/jupyterhub/yarnspawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-yarnspawner) (📥 65 / month):
	```
	pip install jupyterhub-yarnspawner
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-yarnspawner) (📥 25K · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge jupyterhub-yarnspawner
	```
</details>
<details><summary><b><a href="https://github.com/uktrade/fargatespawner">FargateSpawner</a></b> (🥉10 ·  ⭐ 29 · 💀) - 在Docker容器中生成JupyterHub单用户服务器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/uktrade/fargatespawner) (👨‍💻 3 · 🔀 19 · 📦 1 · 📋 9 - 55% open · ⏱️ 28.06.2020):

	```
	git clone https://github.com/uktrade/fargatespawner
	```
- [PyPi](https://pypi.org/project/fargatespawner) (📥 92 / month):
	```
	pip install fargatespawner
	```
</details>
<br>

## Jupyter组件

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Jupyter架构的核心组件。_

<details><summary><b><a href="https://github.com/ipython/ipython">ipython</a></b> (🥇36 ·  ⭐ 15K) - Official repository for IPython itself. Other repos in the.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipython/ipython) (👨‍💻 850 · 🔀 4.1K · 📥 320K · 📦 240K · 📋 6.8K - 21% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/ipython/ipython
	```
- [PyPi](https://pypi.org/project/ipython) (📥 19M / month):
	```
	pip install ipython
	```
- [Conda](https://anaconda.org/conda-forge/ipython) (📥 9.1M · ⏱️ 02.12.2021):
	```
	conda install -c conda-forge ipython
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter_server">jupyter_server</a></b> (🥉20 ·  ⭐ 280 · 📉) - The backendi.e. core services, APIs, and REST.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter_server) (👨‍💻 450 · 🔀 140 · 📥 190 · 📋 220 - 30% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/jupyter-server/jupyter_server
	```
- [PyPi](https://pypi.org/project/jupyter_server) (📥 2.9M / month):
	```
	pip install jupyter_server
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_server) (📥 1.1M · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge jupyter_server
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-packaging">jupyter-packaging</a></b> (🥉19 ·  ⭐ 42) - 帮助构建和安装Jupyter Python软件包的工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-packaging) (👨‍💻 22 · 🔀 37 · 📋 31 - 32% open · ⏱️ 09.12.2021):

	```
	git clone https://github.com/jupyter/jupyter-packaging
	```
- [PyPi](https://pypi.org/project/jupyter-packaging) (📥 410K / month):
	```
	pip install jupyter-packaging
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-packaging) (📥 190K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge jupyter-packaging
	```
</details>
<br>

## Others

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jupyter/qtconsole">qtconsole</a></b> (🥇32 ·  ⭐ 290) - Jupyter Qt Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/qtconsole) (👨‍💻 110 · 🔀 160 · 📦 90K · 📋 290 - 33% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/jupyter/qtconsole
	```
- [PyPi](https://pypi.org/project/qtconsole) (📥 8.1M / month):
	```
	pip install qtconsole
	```
- [Conda](https://anaconda.org/conda-forge/qtconsole) (📥 2.2M · ⏱️ 13.12.2021):
	```
	conda install -c conda-forge qtconsole
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/panel">panel</a></b> (🥈30 ·  ⭐ 1.5K) - 适用于Python的高级应用程序和仪表板解决方案。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/panel) (👨‍💻 80 · 🔀 210 · 📦 2.5K · 📋 1.5K - 29% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/holoviz/panel
	```
- [PyPi](https://pypi.org/project/panel) (📥 320K / month):
	```
	pip install panel
	```
- [Conda](https://anaconda.org/conda-forge/panel) (📥 350K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge panel
	```
</details>
<details><summary><b><a href="https://github.com/abhishekkrthakur/colabcode">colabcode</a></b> (🥉21 ·  ⭐ 1.7K) - 在Google Colab或Kaggle笔记本上运行VSCode（代码服务器）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/abhishekkrthakur/colabcode) (👨‍💻 8 · 🔀 220 · 📦 50 · 📋 62 - 51% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/abhishekkrthakur/colabcode
	```
- [PyPi](https://pypi.org/project/colabcode) (📥 14K / month):
	```
	pip install colabcode
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter_console">jupyter-console</a></b> (🥉19 ·  ⭐ 190) - Jupyter终端控制台。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/jupyter_console) (👨‍💻 57 · 🔀 120 · 📋 140 - 41% open · ⏱️ 14.11.2021):

	```
	git clone https://github.com/jupyter/jupyter_console
	```
- [PyPi](https://pypi.org/project/jupyter-console) (📥 8.2M / month):
	```
	pip install jupyter-console
	```
</details>

---

## 相关资源

- [**Python资源汇集列表**](https://github.com/HanXinzi-AI/awesome-python-resources): 周更新的各种应用方向与主题的资源汇集列表
- [**python机器学习资源大全**](https://github.com/HanXinzi-AI/awesome-python-machine-learning-resources): 周更新的各种python机器学习资源汇集列表
- [**Jupyter及相关工具资源大全**](https://github.com/HanXinzi-AI/awesome-jupyter-resources): 周更新的各种Jupyter及相关工具资源汇集列表
- [**NLP项目和资源大全**](https://github.com/HanXinzi-AI/awesome-NLP-resources): 周更新的各种NLP板块涉及的项目和工具资源汇集列表
- [**CV项目和资源大全**](https://github.com/HanXinzi-AI/awesome-computer-vision-resources): 周更新的各种CV板块涉及的项目和工具资源汇集列表