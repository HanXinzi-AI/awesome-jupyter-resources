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

本资源清单包含270个jupyter相关的开源工具资源，这些热门工具总共分成13个不同的子板块，这些项目目前在github上已经收到240K个点赞。所有的工具资源每周会自动从GitHub和工具维护平台采集信息，并更新排行展示。本清单参考[best-of模板](https://github.com/best-of-lists/best-of)完成，内容参考了[awesome-jupyter](https://github.com/markusschanta/awesome-jupyter)，欢迎大家提PR丰富本清单。
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

<details><summary><b><a href="https://github.com/jupyter/notebook">Jupyter</a></b> (🥇37 ·  ⭐ 9.3K) - Jupyter Interactive Notebook. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/notebook) (👨‍💻 560 · 🔀 3.4K · 📥 540 · 📦 110K · 📋 4.3K - 46% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/jupyter/notebook
	```
- [PyPi](https://pypi.org/project/notebook) (📥 12M / month):
	```
	pip install notebook
	```
- [Conda](https://anaconda.org/conda-forge/jupyter) (📥 1.5M · ⏱️ 28.01.2021):
	```
	conda install -c conda-forge jupyter
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/datascience-notebook) (📥 22M · ⭐ 850 · ⏱️ 09.08.2021):
	```
	docker pull jupyter/datascience-notebook
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab">JupyterLab</a></b> (🥇35 ·  ⭐ 11K) - JupyterLab计算环境。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab) (👨‍💻 440 · 🔀 2K · 📥 630 · 📦 46K · 📋 5.9K - 30% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab
	```
- [PyPi](https://pypi.org/project/jupyterlab) (📥 1M / month):
	```
	pip install jupyterlab
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab) (📥 4.3M · ⏱️ 12.08.2021):
	```
	conda install -c conda-forge jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyterhub">JupyterHub</a></b> (🥈25 ·  ⭐ 6.6K) - Jupyter笔记本电脑的多用户服务器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyterhub/jupyterhub) (👨‍💻 250 · 🔀 1.5K · 📦 1.4K · 📋 2K - 7% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/jupyterhub/jupyterhub
	```
- [PyPi](https://pypi.org/project/jupyterhub) (📥 130K / month):
	```
	pip install jupyterhub
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub) (📥 430K · ⏱️ 16.07.2021):
	```
	conda install -c conda-forge jupyterhub
	```
- [Docker Hub](https://hub.docker.com/r/jupyterhub/jupyterhub) (📥 2.3M · ⭐ 290 · ⏱️ 16.07.2021):
	```
	docker pull jupyterhub/jupyterhub
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/docker-stacks">Docker Stacks</a></b> (🥈25 ·  ⭐ 6.4K) - 包含Jupyter应用程序的即可运行的Docker映像。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/docker-stacks) (👨‍💻 200 · 🔀 2.3K · 📋 660 - 8% open · ⏱️ 12.08.2021):

	```
	git clone https://github.com/jupyter/docker-stacks
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/scipy-notebook) (📥 43M · ⭐ 310 · ⏱️ 09.08.2021):
	```
	docker pull jupyter/scipy-notebook
	```
</details>
<details><summary><b><a href="https://github.com/nteract/nteract">nteract</a></b> (🥈25 ·  ⭐ 5.6K) - 交互式计算套件<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/nteract) (👨‍💻 170 · 🔀 510 · 📥 1.2M · 📋 1.7K - 8% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/nteract/nteract
	```
- [PyPi](https://pypi.org/project/nteract_on_jupyter) (📥 3.2K / month):
	```
	pip install nteract_on_jupyter
	```
</details>
<details><summary><b><a href="https://github.com/googledatalab/datalab">DataLab</a></b> (🥈23 ·  ⭐ 960 · 💤) - 面向大数据的交互式工具和开发人员经验。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/googledatalab/datalab) (👨‍💻 51 · 🔀 240 · 📋 890 - 25% open · ⏱️ 09.09.2020):

	```
	git clone https://github.com/googledatalab/datalab
	```
- [PyPi](https://pypi.org/project/datalab) (📥 83K / month):
	```
	pip install datalab
	```
</details>
<details><summary><b><a href="https://github.com/vatlab/sos">sos</a></b> (🥉22 ·  ⭐ 200) - 用于日常数据分析的SoS工作流系统。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/sos) (👨‍💻 33 · 🔀 27 · 📦 980 · 📋 1.4K - 3% open · ⏱️ 24.05.2021):

	```
	git clone https://github.com/vatlab/SOS
	```
</details>
<details><summary><b><a href="https://github.com/nteract/hydrogen">Hydrogen</a></b> (🥉20 ·  ⭐ 3.7K) - 交互运行代码，检查数据并作图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nteract/hydrogen) (👨‍💻 87 · 🔀 300 · 📋 1.2K - 11% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/nteract/hydrogen
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/ml-workspace">ML Workspace</a></b> (🥉20 ·  ⭐ 2.1K) - 基于Web的多合一IDE，专门用于机器学习和数据任务。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ml-tooling/ml-workspace) (👨‍💻 9 · 🔀 260 · 📋 70 - 11% open · ⏱️ 13.07.2021):

	```
	git clone https://github.com/ml-tooling/ml-workspace
	```
- [Docker Hub](https://hub.docker.com/r/mltooling/ml-workspace) (📥 470K · ⭐ 20 · ⏱️ 13.07.2021):
	```
	docker pull mltooling/ml-workspace
	```
</details>
<details><summary><b><a href="https://github.com/Kaggle/docker-python">docker-python</a></b> (🥉19 ·  ⭐ 1.9K) - Kaggle Python Docker映像。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Kaggle/docker-python) (👨‍💻 140 · 🔀 740 · 📋 270 - 4% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/kaggle/docker-python
	```
- [Docker Hub](https://hub.docker.com/r/kaggle/python) (📥 190K · ⭐ 160 · ⏱️ 11.08.2021):
	```
	docker pull kaggle/python
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/retrolab">jupyterlab-classic</a></b> (🥉18 ·  ⭐ 170 · 📈) - 下一代老式笔记本用户UI界面。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/retrolab) (👨‍💻 8 · 🔀 24 · 📦 19 · 📋 79 - 36% open · ⏱️ 23.07.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-classic
	```
- [PyPi](https://pypi.org/project/jupyterlab-classic) (📥 190 / month):
	```
	pip install jupyterlab-classic
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/ml-hub">ML Hub</a></b> (🥉17 ·  ⭐ 180 · 💤) - 机器学习团队的多用户开发平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ml-tooling/ml-hub) (👨‍💻 5 · 🔀 40 · 📥 1.4K · 📋 19 - 57% open · ⏱️ 02.10.2020):

	```
	git clone https://github.com/ml-tooling/ml-hub
	```
- [Docker Hub](https://hub.docker.com/r/mltooling/ml-hub) (📥 42K · ⭐ 5 · ⏱️ 18.02.2020):
	```
	docker pull mltooling/ml-hub
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/vscode-jupyter">VSCode Jupyter</a></b> (🥉16 ·  ⭐ 380) - VS Code Jupyter extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/vscode-jupyter) (👨‍💻 240 · 🔀 73 · 📋 5.7K - 15% open · ⏱️ 12.08.2021):

	```
	git clone https://github.com/microsoft/vscode-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/iot-salzburg/gpu-jupyter">gpu-jupyter</a></b> (🥉15 ·  ⭐ 240) - 充分利用Jupyterlab的灵活性。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iot-salzburg/gpu-jupyter) (👨‍💻 9 · 🔀 85 · 📋 43 - 9% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/iot-salzburg/gpu-jupyter
	```
</details>
<br>

## 交互式小部件和可视化

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_提供交互式UI小部件和可视化工具的扩展。_

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-ml-python#data-visualization">best-of-ml-python - Data Visualization</a></b>  - Python-based data visualization libraries.

<details><summary><b><a href="https://github.com/pandas-profiling/pandas-profiling">pandas-profiling</a></b> (🥇32 ·  ⭐ 7.8K) - 从pandas DataFrame创建HTML分析报告。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pandas-profiling/pandas-profiling) (👨‍💻 79 · 🔀 1.1K · 📦 4.9K · 📋 480 - 16% open · ⏱️ 27.06.2021):

	```
	git clone https://github.com/pandas-profiling/pandas-profiling
	```
- [PyPi](https://pypi.org/project/pandas-profiling) (📥 560K / month):
	```
	pip install pandas-profiling
	```
- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 150K · ⏱️ 12.05.2021):
	```
	conda install -c conda-forge pandas-profiling
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipywidgets">ipywidgets</a></b> (🥇32 ·  ⭐ 2.3K) - Interactive Widgets for the Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipywidgets) (👨‍💻 180 · 🔀 740 · 📦 2.1K · 📋 1.7K - 31% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/jupyter-widgets/ipywidgets
	```
- [PyPi](https://pypi.org/project/ipywidgets) (📥 11M / month):
	```
	pip install ipywidgets
	```
- [Conda](https://anaconda.org/conda-forge/ipywidgets) (📥 3.5M · ⏱️ 07.01.2021):
	```
	conda install -c conda-forge ipywidgets
	```
- [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 110K / month):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/bokeh">bokeh</a></b> (🥇31 ·  ⭐ 15K) - 浏览器中的Python交互式数据可视化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 560 · 🔀 3.7K · 📦 37K · 📋 6.6K - 10% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh) (📥 1.6M / month):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 5.1M · ⏱️ 08.07.2021):
	```
	conda install -c conda-forge bokeh
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥇29 ·  ⭐ 1.2K) - Jupyter-Leaflet.js桥接。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 68 · 🔀 280 · 📦 1K · 📋 430 - 37% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/jupyter-widgets/ipyleaflet
	```
- [PyPi](https://pypi.org/project/ipyleaflet) (📥 60K / month):
	```
	pip install ipyleaflet
	```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 730K · ⏱️ 17.06.2021):
	```
	conda install -c conda-forge ipyleaflet
	```
- [NPM](https://www.npmjs.com/package/jupyter-leaflet) (📥 23K / month):
	```
	npm install jupyter-leaflet
	```
</details>
<details><summary><b><a href="https://github.com/matplotlib/ipympl">jupyter-matplotlib</a></b> (🥇29 ·  ⭐ 1.1K · 📈) - Matplotlib Jupyter集成。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/matplotlib/ipympl) (👨‍💻 23 · 🔀 160 · 📦 1.7K · 📋 200 - 51% open · ⏱️ 07.05.2021):

	```
	git clone https://github.com/matplotlib/ipympl
	```
- [PyPi](https://pypi.org/project/ipympl) (📥 72K / month):
	```
	pip install ipympl
	```
- [NPM](https://www.npmjs.com/package/jupyter-matplotlib) (📥 45K / month):
	```
	npm install jupyter-matplotlib
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈27 ·  ⭐ 3.1K) - 用于IPython / Jupyter笔记本的绘图库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 53 · 🔀 410 · 📦 27 · 📋 540 - 35% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/bqplot/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot) (📥 66K / month):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 730K · ⏱️ 16.07.2021):
	```
	conda install -c conda-forge bqplot
	```
- [NPM](https://www.npmjs.com/package/bqplot) (📥 14K / month):
	```
	npm install bqplot
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/facets">facets-overview</a></b> (🥈26 ·  ⭐ 6.7K) - 机器学习数据集的可视化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/facets) (👨‍💻 28 · 🔀 810 · 📦 60 · 📋 150 - 49% open · ⏱️ 06.05.2021):

	```
	git clone https://github.com/pair-code/facets
	```
- [PyPi](https://pypi.org/project/facets-overview) (📥 83K / month):
	```
	pip install facets-overview
	```
</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipyvolume">ipyvolume</a></b> (🥈26 ·  ⭐ 1.7K) - 基于IPython的Jupyter笔记本中用于Python的3d绘图<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maartenbreddels/ipyvolume) (👨‍💻 39 · 🔀 200 · 📦 550 · 📋 280 - 56% open · ⏱️ 18.06.2021):

	```
	git clone https://github.com/maartenbreddels/ipyvolume
	```
- [PyPi](https://pypi.org/project/ipyvolume) (📥 29K / month):
	```
	pip install ipyvolume
	```
- [Conda](https://anaconda.org/conda-forge/ipyvolume) (📥 310K · ⏱️ 20.04.2021):
	```
	conda install -c conda-forge ipyvolume
	```
- [NPM](https://www.npmjs.com/package/ipyvolume) (📥 3.2K / month):
	```
	npm install ipyvolume
	```
</details>
<details><summary><b><a href="https://github.com/nteract/papermill">papermill</a></b> (🥈25 ·  ⭐ 4.3K) - 参数化，执行和分析笔记本。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/papermill) (👨‍💻 92 · 🔀 320 · 📦 1.5K · 📋 320 - 29% open · ⏱️ 27.07.2021):

	```
	git clone https://github.com/nteract/papermill
	```
- [PyPi](https://pypi.org/project/papermill) (📥 370K / month):
	```
	pip install papermill
	```
- [Conda](https://anaconda.org/conda-forge/papermill) (📥 180K · ⏱️ 11.03.2021):
	```
	conda install -c conda-forge papermill
	```
</details>
<details><summary><b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥈25 ·  ⭐ 2.6K) - Visualizer for Pandas Data Structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/man-group/dtale) (👨‍💻 17 · 🔀 200 · 📦 210 · 📋 390 - 8% open · ⏱️ 12.08.2021):

	```
	git clone https://github.com/man-group/dtale
	```
- [PyPi](https://pypi.org/project/dtale) (📥 14K / month):
	```
	pip install dtale
	```
- [Conda](https://anaconda.org/conda-forge/dtale) (📥 75K · ⏱️ 12.08.2021):
	```
	conda install -c conda-forge dtale
	```
</details>
<details><summary><b><a href="https://github.com/quantopian/qgrid">qgrid</a></b> (🥈23 ·  ⭐ 2.7K · 💀) - 用于排序，过滤和编辑DataFrame的交互式工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/quantopian/qgrid) (👨‍💻 30 · 🔀 360 · 📦 1 · 📋 270 - 53% open · ⏱️ 07.04.2020):

	```
	git clone https://github.com/quantopian/qgrid
	```
- [PyPi](https://pypi.org/project/qgrid) (📥 53K / month):
	```
	pip install qgrid
	```
- [Conda](https://anaconda.org/conda-forge/qgrid) (📥 320K · ⏱️ 04.03.2021):
	```
	conda install -c conda-forge qgrid
	```
- [NPM](https://www.npmjs.com/package/qgrid) (📥 2.8K / month):
	```
	npm install qgrid
	```
</details>
<details><summary><b><a href="https://github.com/plotly/jupyter-dash">jupyter-dash</a></b> (🥈23 ·  ⭐ 550 · 💤) - 在Jupyter Notebook和JupyterLab中开发Dash应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/jupyter-dash) (👨‍💻 3 · 🔀 150 · 📥 65 · 📦 790 · 📋 43 - 67% open · ⏱️ 22.01.2021):

	```
	git clone https://github.com/plotly/jupyter-dash
	```
- [PyPi](https://pypi.org/project/jupyter-dash) (📥 35K / month):
	```
	pip install jupyter-dash
	```
</details>
<details><summary><b><a href="https://github.com/martinRenou/ipycanvas">ipycanvas</a></b> (🥈23 ·  ⭐ 460) - Jupyter中的交互式画布。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/martinRenou/ipycanvas) (👨‍💻 13 · 🔀 36 · 📦 180 · 📋 90 - 34% open · ⏱️ 18.06.2021):

	```
	git clone https://github.com/martinRenou/ipycanvas
	```
- [PyPi](https://pypi.org/project/ipycanvas) (📥 14K / month):
	```
	pip install ipycanvas
	```
- [Conda](https://anaconda.org/conda-forge/ipycanvas) (📥 27K · ⏱️ 18.06.2021):
	```
	conda install -c conda-forge ipycanvas
	```
</details>
<details><summary><b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥈22 ·  ⭐ 580) - 使用Mapbox GL JS可视化Python Jupyter笔记本中的数据。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mapbox/mapboxgl-jupyter) (👨‍💻 21 · 🔀 120 · 📦 110 · 📋 97 - 30% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/mapbox/mapboxgl-jupyter
	```
- [PyPi](https://pypi.org/project/mapboxgl) (📥 14K / month):
	```
	pip install mapboxgl
	```
</details>
<details><summary><b><a href="https://github.com/cytoscape/ipycytoscape">ipycytoscape</a></b> (🥈22 ·  ⭐ 160) - Cytoscape Jupyter小部件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/cytoscape/ipycytoscape) (👨‍💻 26 · 🔀 43 · 📥 3 · 📦 39 · 📋 130 - 34% open · ⏱️ 27.07.2021):

	```
	git clone https://github.com/QuantStack/ipycytoscape
	```
- [Conda](https://anaconda.org/conda-forge/ipycytoscape) (📥 21K · ⏱️ 10.05.2021):
	```
	conda install -c conda-forge ipycytoscape
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥈21 ·  ⭐ 750) - Jupyter-Three.js桥接。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter-widgets/pythreejs) (👨‍💻 27 · 🔀 160 · 📦 17 · 📋 200 - 30% open · ⏱️ 26.02.2021):

	```
	git clone https://github.com/jupyter-widgets/pythreejs
	```
- [PyPi](https://pypi.org/project/pythreejs) (📥 43K / month):
	```
	pip install pythreejs
	```
- [Conda](https://anaconda.org/conda-forge/pythreejs) (📥 330K · ⏱️ 02.03.2021):
	```
	conda install -c conda-forge pythreejs
	```
- [NPM](https://www.npmjs.com/package/jupyter-threejs) (📥 7.1K / month):
	```
	npm install jupyter-threejs
	```
</details>
<details><summary><b><a href="https://github.com/mariobuikhuizen/ipyvuetify">ipyvuetify</a></b> (🥈21 ·  ⭐ 220) - 基于vuetify UI组件的Jupyter小部件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mariobuikhuizen/ipyvuetify) (👨‍💻 10 · 🔀 37 · 📦 4 · 📋 120 - 42% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/mariobuikhuizen/ipyvuetify
	```
- [PyPi](https://pypi.org/project/ipyvuetify) (📥 42K / month):
	```
	pip install ipyvuetify
	```
- [Conda](https://anaconda.org/conda-forge/ipyvuetify) (📥 54K · ⏱️ 06.08.2021):
	```
	conda install -c conda-forge ipyvuetify
	```
</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipywebrtc">ipywebrtc</a></b> (🥈21 ·  ⭐ 190) - 适用于Jupyter笔记本/实验室的WebRTC。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maartenbreddels/ipywebrtc) (👨‍💻 9 · 🔀 30 · 📦 330 · 📋 47 - 57% open · ⏱️ 29.03.2021):

	```
	git clone https://github.com/maartenbreddels/ipywebrtc
	```
- [PyPi](https://pypi.org/project/ipywebrtc) (📥 35K / month):
	```
	pip install ipywebrtc
	```
- [Conda](https://anaconda.org/conda-forge/ipywebrtc) (📥 210K · ⏱️ 29.03.2021):
	```
	conda install -c conda-forge ipywebrtc
	```
- [NPM](https://www.npmjs.com/package/jupyter-webrtc) (📥 490 / month):
	```
	npm install jupyter-webrtc
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥈19 ·  ⭐ 560) - What-If工具的源代码/网页/演示。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/what-if-tool) (👨‍💻 19 · 🔀 110 · 📋 82 - 48% open · ⏱️ 17.03.2021):

	```
	git clone https://github.com/PAIR-code/what-if-tool
	```
- [PyPi](https://pypi.org/project/witwidget) (📥 10K / month):
	```
	pip install witwidget
	```
- [NPM](https://www.npmjs.com/package/wit-widget) (📥 2K / month):
	```
	npm install wit-widget
	```
</details>
<details><summary><b><a href="https://github.com/QuantStack/ipysheet">ipysheet</a></b> (🥈19 ·  ⭐ 430) - Jupyter Handsontable集成。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QuantStack/ipysheet) (👨‍💻 9 · 🔀 55 · 📦 3 · 📋 110 - 51% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/QuantStack/ipysheet
	```
- [PyPi](https://pypi.org/project/ipysheet) (📥 11K / month):
	```
	pip install ipysheet
	```
- [Conda](https://anaconda.org/conda-forge/ipysheet) (📥 36K · ⏱️ 11.08.2021):
	```
	conda install -c conda-forge ipysheet
	```
- [NPM](https://www.npmjs.com/package/ipysheet) (📥 3.7K / month):
	```
	npm install ipysheet
	```
</details>
<details><summary><b><a href="https://github.com/InsightSoftwareConsortium/itkwidgets">itkwidgets</a></b> (🥈19 ·  ⭐ 380) - 交互式Jupyter小部件，以可视化图像，点集等。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/InsightSoftwareConsortium/itkwidgets) (👨‍💻 19 · 🔀 48 · 📥 64 · 📋 160 - 41% open · ⏱️ 16.07.2021):

	```
	git clone https://github.com/InsightSoftwareConsortium/itkwidgets
	```
- [PyPi](https://pypi.org/project/itkwidgets) (📥 4.8K / month):
	```
	pip install itkwidgets
	```
- [NPM](https://www.npmjs.com/package/itkwidgets) (📥 1.7K / month):
	```
	npm install itkwidgets
	```
</details>
<details><summary><b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉18 ·  ⭐ 720 · 💀) - Jupyter中的Google地图。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pbugnion/gmaps) (👨‍💻 16 · 🔀 140 · 📦 1 · 📋 200 - 31% open · ⏱️ 22.07.2019):

	```
	git clone https://github.com/pbugnion/gmaps
	```
- [PyPi](https://pypi.org/project/gmaps) (📥 15K / month):
	```
	pip install gmaps
	```
- [Conda](https://anaconda.org/conda-forge/gmaps) (📥 240K · ⏱️ 02.08.2019):
	```
	conda install -c conda-forge gmaps
	```
- [NPM](https://www.npmjs.com/package/jupyter-gmaps) (📥 1.9K / month):
	```
	npm install jupyter-gmaps
	```
</details>
<details><summary><b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉18 ·  ⭐ 440 · 💀) - Jupyter / IPython Notebook的Dragndrop数据透视表和图表。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nicolaskruchten/jupyter_pivottablejs) (👨‍💻 3 · 🔀 59 · 📦 180 · 📋 53 - 30% open · ⏱️ 04.12.2018):

	```
	git clone https://github.com/nicolaskruchten/jupyter_pivottablejs
	```
- [PyPi](https://pypi.org/project/pivottablejs) (📥 13K / month):
	```
	pip install pivottablejs
	```
</details>
<details><summary><b><a href="https://github.com/lgpage/nbtutor">nbtutor</a></b> (🥉18 ·  ⭐ 390) - 可视化Jupyter Notebook单元中的Python代码执行（逐行）。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lgpage/nbtutor) (👨‍💻 3 · 🔀 32 · 📦 21 · 📋 29 - 55% open · ⏱️ 29.07.2021):

	```
	git clone https://github.com/lgpage/nbtutor
	```
- [Conda](https://anaconda.org/conda-forge/nbtutor) (📥 86K · ⏱️ 15.10.2020):
	```
	conda install -c conda-forge nbtutor
	```
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉18 ·  ⭐ 310) - 适用于Vega和Vega-Lite的IPython / Jupyter笔记本模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 10 · 🔀 46 · 📋 91 - 12% open · ⏱️ 02.08.2021):

	```
	git clone https://github.com/vega/ipyvega
	```
- [PyPi](https://pypi.org/project/vega) (📥 27K / month):
	```
	pip install vega
	```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 450K · ⏱️ 11.08.2021):
	```
	conda install -c conda-forge vega
	```
</details>
<details><summary><b><a href="https://github.com/mwouts/itables">itables</a></b> (🥉18 ·  ⭐ 180) - Jupyter中的交互式表格。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/itables) (👨‍💻 3 · 🔀 15 · 📦 60 · 📋 17 - 52% open · ⏱️ 04.02.2021):

	```
	git clone https://github.com/mwouts/itables
	```
- [PyPi](https://pypi.org/project/itables) (📥 2.3K / month):
	```
	pip install itables
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/tributary">tributary</a></b> (🥉17 ·  ⭐ 270) - 在Python中流式反应图和数据流图。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/tributary) (👨‍💻 6 · 🔀 24 · 📦 15 · 📋 76 - 13% open · ⏱️ 23.03.2021):

	```
	git clone https://github.com/timkpaine/tributary
	```
- [PyPi](https://pypi.org/project/tributary) (📥 220 / month):
	```
	pip install tributary
	```
- [Conda](https://anaconda.org/conda-forge/tributary) (📥 13K · ⏱️ 15.10.2020):
	```
	conda install -c conda-forge tributary
	```
</details>
<details><summary><b><a href="https://github.com/mariobuikhuizen/ipyvue">ipyvue</a></b> (🥉17 ·  ⭐ 32) - Vue库的Jupyter小部件基础。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mariobuikhuizen/ipyvue) (👨‍💻 2 · 🔀 8 · 📦 16 · 📋 3 - 66% open · ⏱️ 22.06.2021):

	```
	git clone https://github.com/mariobuikhuizen/ipyvue
	```
- [PyPi](https://pypi.org/project/ipyvue) (📥 41K / month):
	```
	pip install ipyvue
	```
- [Conda](https://anaconda.org/conda-forge/ipyvue) (📥 31K · ⏱️ 13.01.2021):
	```
	conda install -c conda-forge ipyvue
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/ipydagred3">ipydagred3</a></b> (🥉17 ·  ⭐ 26) - ipywidgets库，用于在其中绘制有向无环图。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/ipydagred3) (👨‍💻 3 · 🔀 5 · 📦 8 · 📋 18 - 27% open · ⏱️ 27.06.2021):

	```
	git clone https://github.com/timkpaine/ipydagred3
	```
- [PyPi](https://pypi.org/project/ipydagred3) (📥 310 / month):
	```
	pip install ipydagred3
	```
- [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 110K / month):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/vidartf/ipydatawidgets">ipydatawidgets</a></b> (🥉17 ·  ⭐ 25 · 💤) - 一组小部件，以帮助促进大型数据集的重用。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/vidartf/ipydatawidgets) (👨‍💻 5 · 🔀 7 · 📦 350 · 📋 8 - 37% open · ⏱️ 04.01.2021):

	```
	git clone https://github.com/vidartf/ipydatawidgets
	```
- [PyPi](https://pypi.org/project/ipydatawidgets) (📥 43K / month):
	```
	pip install ipydatawidgets
	```
- [Conda](https://anaconda.org/conda-forge/ipydatawidgets) (📥 99K · ⏱️ 06.01.2021):
	```
	conda install -c conda-forge ipydatawidgets
	```
</details>
<details><summary><b><a href="https://github.com/igvteam/igv-jupyter">igv.js widget</a></b> (🥉16 ·  ⭐ 130) - 集成了igv.js的Jupyter Notebook扩展。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/igvteam/igv-jupyter) (👨‍💻 4 · 🔀 14 · 📦 5 · ⏱️ 16.07.2021):

	```
	git clone https://github.com/igvteam/igv-jupyter
	```
- [PyPi](https://pypi.org/project/igv-jupyter) (📥 290 / month):
	```
	pip install igv-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/nipy/niwidgets">niwidgets</a></b> (🥉16 ·  ⭐ 67 · 💀) - 适用于Jupyter笔记本的Neuroimaging小部件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nipy/niwidgets) (👨‍💻 16 · 🔀 32 · 📦 25 · 📋 34 - 50% open · ⏱️ 24.03.2020):

	```
	git clone https://github.com/nipy/niwidgets
	```
- [PyPi](https://pypi.org/project/niwidgets) (📥 160 / month):
	```
	pip install niwidgets
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair_viewer">Altair Viewer</a></b> (🥉16 ·  ⭐ 46 · 💀) - 用于Altair和Vega-Lite可视化的查看器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair_viewer) (👨‍💻 2 · 🔀 5 · 📋 5 - 40% open · ⏱️ 01.04.2020):

	```
	git clone https://github.com/altair-viz/altair_viewer
	```
- [PyPi](https://pypi.org/project/altair_viewer) (📥 130K / month):
	```
	pip install altair_viewer
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/ipyregulartable">ipyregulartable</a></b> (🥉16 ·  ⭐ 43) - Jupyter中的高性能，可编辑，可样式化的数据表。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/ipyregulartable) (👨‍💻 4 · 🔀 9 · 📦 8 · 📋 21 - 38% open · ⏱️ 16.07.2021):

	```
	git clone https://github.com/jpmorganchase/ipyregulartable
	```
- [PyPi](https://pypi.org/project/ipyregulartable) (📥 130 / month):
	```
	pip install ipyregulartable
	```
- [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 110K / month):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/vidartf/ipyscales">ipyscales</a></b> (🥉16 ·  ⭐ 13 · 💤) - 用于度量的小部件库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vidartf/ipyscales) (👨‍💻 4 · 🔀 3 · 📦 46 · 📋 6 - 33% open · ⏱️ 05.01.2021):

	```
	git clone https://github.com/vidartf/ipyscales
	```
- [PyPi](https://pypi.org/project/ipyscales) (📥 110 / month):
	```
	pip install ipyscales
	```
- [Conda](https://anaconda.org/conda-forge/ipyscales) (📥 49K · ⏱️ 06.01.2021):
	```
	conda install -c conda-forge ipyscales
	```
</details>
<details><summary><b><a href="https://github.com/evidentlyai/evidently">evidently</a></b> (🥉15 ·  ⭐ 1.2K · 📈) - 交互式报告，可在分析过程中分析机器学习模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/evidentlyai/evidently) (👨‍💻 4 · 🔀 94 · 📦 11 · 📋 32 - 68% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/evidentlyai/evidently
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
<details><summary><b><a href="https://github.com/QuantStack/ipytree">ipytree</a></b> (🥉15 ·  ⭐ 83) - 使用Jupyter-widgets协议和jsTree的Tree Widget。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QuantStack/ipytree) (👨‍💻 8 · 🔀 20 · 📋 23 - 47% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/QuantStack/ipytree
	```
- [PyPi](https://pypi.org/project/ipytree) (📥 7.6K / month):
	```
	pip install ipytree
	```
- [Conda](https://anaconda.org/conda-forge/ipytree) (📥 22K · ⏱️ 03.03.2021):
	```
	conda install -c conda-forge ipytree
	```
</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipymaterialui">ipymaterialui</a></b> (🥉14 ·  ⭐ 72 · 💀) - 基于React Material UI组件的Jupyter小部件。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maartenbreddels/ipymaterialui) (👨‍💻 3 · 🔀 13 · 📦 4 · 📋 9 - 66% open · ⏱️ 29.10.2019):

	```
	git clone https://github.com/maartenbreddels/ipymaterialui
	```
- [PyPi](https://pypi.org/project/ipymaterialui) (📥 82 / month):
	```
	pip install ipymaterialui
	```
- [NPM](https://www.npmjs.com/package/jupyter-materialui) (📥 120 / month):
	```
	npm install jupyter-materialui
	```
</details>
<details><summary><b><a href="https://github.com/spacetelescope/jdaviz">jdaviz</a></b> (🥉13 ·  ⭐ 21) - Jupyter平台中的JWST天文数据分析工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/spacetelescope/jdaviz) (👨‍💻 22 · 🔀 22 · 📋 390 - 53% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/spacetelescope/jdaviz
	```
- [PyPi](https://pypi.org/project/jdaviz) (📥 190 / month):
	```
	pip install jdaviz
	```
</details>
<details><summary><b><a href="https://github.com/CermakM/jupyter-datatables">Jupyter DataTables</a></b> (🥉11 ·  ⭐ 130 · 💀) - 利用pandas DataFrames的Jupyter Notebook扩展。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CermakM/jupyter-datatables) (👨‍💻 4 · 🔀 13 · 📋 28 - 46% open · ⏱️ 11.12.2019):

	```
	git clone https://github.com/CermakM/jupyter-datatables
	```
- [PyPi](https://pypi.org/project/jupyter-datatables) (📥 410 / month):
	```
	pip install jupyter-datatables
	```
</details>
<details><summary><b><a href="https://github.com/leifwalsh/perfume">perfume</a></b> (🥉11 ·  ⭐ 31 · 💤) - Jupyter中的交互式性能基准测试。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/leifwalsh/perfume) (👨‍💻 3 · 🔀 3 · 📋 6 - 33% open · ⏱️ 31.10.2020):

	```
	git clone https://github.com/leifwalsh/perfume
	```
- [PyPi](https://pypi.org/project/perfume-bench) (📥 110 / month):
	```
	pip install perfume-bench
	```
</details>
<details><summary><b><a href="https://github.com/Yomguithereal/ipysigma">ipysigma</a></b> (🥉10 ·  ⭐ 28 · 💀) - 一个自定义的Jupyter小部件库，用于使用sigma.js显示图形。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Yomguithereal/ipysigma) (👨‍💻 3 · 🔀 4 · 📋 4 - 50% open · ⏱️ 30.06.2020):

	```
	git clone https://github.com/Yomguithereal/ipysigma
	```
- [PyPi](https://pypi.org/project/ipysigma) (📥 95 / month):
	```
	pip install ipysigma
	```
- [NPM](https://www.npmjs.com/package/ipysigma) (📥 26 / month):
	```
	npm install ipysigma
	```
</details>
<details><summary><b><a href="https://github.com/GianniBalistreri/easyexplore">easyexplore</a></b> (🥉10 ·  ⭐ 3) - 用于在Python中轻松有效地进行数据探索的工具箱。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/GianniBalistreri/easyexplore) (👨‍💻 3 · 🔀 2 · 📦 1 · ⏱️ 04.06.2021):

	```
	git clone https://github.com/GianniBalistreri/easyexplore
	```
- [PyPi](https://pypi.org/project/easyexplore) (📥 700 / month):
	```
	pip install easyexplore
	```
</details>
<details><summary><b><a href="https://github.com/asvcode/Vision_UI">Vision UI</a></b> (🥉9 ·  ⭐ 250 · 💀) - Fastai的UI视觉界面-现在与Google兼容。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/asvcode/Vision_UI) (👨‍💻 3 · 🔀 32 · 📋 3 - 33% open · ⏱️ 05.07.2020):

	```
	git clone https://github.com/asvcode/Vision_UI
	```
</details>
<details><summary><b><a href="https://github.com/ipyannotate/ipyannotate">ipyannotate</a></b> (🥉9 ·  ⭐ 120 · 💤) - Jupyter Widget，用于数据标注。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipyannotate/ipyannotate) (👨‍💻 3 · 🔀 9 · ⏱️ 20.09.2020):

	```
	git clone https://github.com/ipyannotate/ipyannotate
	```
- [PyPi](https://pypi.org/project/ipyannotate) (📥 31 / month):
	```
	pip install ipyannotate
	```
- [NPM](https://www.npmjs.com/package/ipyannotate) (📥 13 / month):
	```
	npm install ipyannotate
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/ipyp5">ipyp5</a></b> (🥉9 ·  ⭐ 29 · 💤) - p5.j​​s Jupyter小部件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/ipyp5) (👨‍💻 2 · 🔀 4 · ⏱️ 16.10.2020):

	```
	git clone https://github.com/jtpio/ipyp5
	```
- [PyPi](https://pypi.org/project/ipyp5) (📥 48 / month):
	```
	pip install ipyp5
	```
</details>
<details><summary><b><a href="https://github.com/DGothrek/ipyaggrid">ipyaggrid</a></b> (🥉9 ·  ⭐ 6 · 💀) - Jupyter小部件-Notebook中的Ag-grid。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/DGothrek/ipyaggrid) (👨‍💻 2 · ⏱️ 06.05.2019):

	```
	git clone https://github.com/DGothrek/ipyaggrid
	```
- [PyPi](https://pypi.org/project/ipyaggrid) (📥 3.2K / month):
	```
	pip install ipyaggrid
	```
- [NPM](https://www.npmjs.com/package/ipyaggrid) (📥 750 / month):
	```
	npm install ipyaggrid
	```
</details>
<br>

## Jupyter拓展

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_扩展Jupyter自身功能的应用程序插件。_

<details><summary><b><a href="https://github.com/jupyter-server/jupyter-resource-usage">Resource Usage</a></b> (🥇23 ·  ⭐ 250) - Jupyter Notebook Extension，用于监视您自己的资源。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter-resource-usage) (👨‍💻 16 · 🔀 58 · 📦 55 · 📋 52 - 51% open · ⏱️ 23.07.2021):

	```
	git clone https://github.com/jupyter-server/jupyter-resource-usage
	```
- [PyPi](https://pypi.org/project/jupyter-resource-usage) (📥 14K / month):
	```
	pip install jupyter-resource-usage
	```
- [Conda](https://anaconda.org/conda-forge/nbresuse) (📥 340K · ⏱️ 23.11.2020):
	```
	conda install -c conda-forge nbresuse
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbgrader">nbgrader</a></b> (🥇22 ·  ⭐ 1K) - 用于在Notebook分配(任务/作业)和评分的系统。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbgrader) (👨‍💻 83 · 🔀 250 · 📋 770 - 24% open · ⏱️ 12.08.2021):

	```
	git clone https://github.com/jupyter/nbgrader
	```
- [PyPi](https://pypi.org/project/nbgrader) (📥 3K / month):
	```
	pip install nbgrader
	```
- [Conda](https://anaconda.org/conda-forge/nbgrader) (📥 96K · ⏱️ 10.03.2021):
	```
	conda install -c conda-forge nbgrader
	```
</details>
<details><summary><b><a href="https://github.com/dunovank/jupyter-themes">Jupyter Themes</a></b> (🥇21 ·  ⭐ 8.6K · 📉) - Custom Jupyter Notebook Themes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dunovank/jupyter-themes) (👨‍💻 42 · 🔀 960 · 📋 380 - 48% open · ⏱️ 08.08.2021):

	```
	git clone https://github.com/dunovank/jupyter-themes
	```
- [PyPi](https://pypi.org/project/jupyterthemes) (📥 33K / month):
	```
	pip install jupyterthemes
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nbgitpuller">nbgitpuller</a></b> (🥇21 ·  ⭐ 140) - Jupyter服务器扩展，可将git存储库单向同步。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nbgitpuller) (👨‍💻 21 · 🔀 49 · 📦 350 · 📋 93 - 35% open · ⏱️ 14.07.2021):

	```
	git clone https://github.com/jupyterhub/nbgitpuller
	```
- [PyPi](https://pypi.org/project/nbgitpuller) (📥 72K / month):
	```
	pip install nbgitpuller
	```
- [Conda](https://anaconda.org/conda-forge/nbgitpuller) (📥 21K · ⏱️ 24.06.2021):
	```
	conda install -c conda-forge nbgitpuller
	```
</details>
<details><summary><b><a href="https://github.com/ipython-contrib/jupyter_contrib_nbextensions">Contrib NBextensions</a></b> (🥈20 ·  ⭐ 4.6K) - Jupyter的各种笔记本扩展的集合。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) (👨‍💻 130 · 🔀 720 · 📋 760 - 40% open · ⏱️ 06.04.2021):

	```
	git clone https://github.com/ipython-contrib/jupyter_contrib_nbextensions
	```
- [PyPi](https://pypi.org/project/jupyter_contrib_nbextensions) (📥 230K / month):
	```
	pip install jupyter_contrib_nbextensions
	```
</details>
<details><summary><b><a href="https://github.com/oschuett/appmode">Appmode</a></b> (🥈20 ·  ⭐ 370) - Jupyter扩展，可将笔记本变成Web应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oschuett/appmode) (👨‍💻 8 · 🔀 63 · 📦 270 · 📋 52 - 5% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/oschuett/appmode
	```
- [PyPi](https://pypi.org/project/appmode) (📥 3.2K / month):
	```
	pip install appmode
	```
- [Conda](https://anaconda.org/conda-forge/appmode) (📥 130K · ⏱️ 24.01.2021):
	```
	conda install -c conda-forge appmode
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-server-proxy">jupyter-server-proxy</a></b> (🥈20 ·  ⭐ 170) - Jupyter笔记本服务器扩展到代理Web服务。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-server-proxy) (👨‍💻 53 · 🔀 91 · 📦 1 · 📋 140 - 41% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/jupyterhub/jupyter-server-proxy
	```
- [PyPi](https://pypi.org/project/jupyter-server-proxy) (📥 45K / month):
	```
	pip install jupyter-server-proxy
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-server-proxy) (📥 420K · ⏱️ 04.07.2021):
	```
	conda install -c conda-forge jupyter-server-proxy
	```
</details>
<details><summary><b><a href="https://github.com/8080labs/pyforest">pyforest</a></b> (🥈18 ·  ⭐ 910) - pyforest-自动化导入工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/8080labs/pyforest) (👨‍💻 13 · 🔀 180 · 📋 21 - 38% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/8080labs/pyforest
	```
- [PyPi](https://pypi.org/project/pyforest) (📥 4.7K / month):
	```
	pip install pyforest
	```
</details>
<details><summary><b><a href="https://github.com/mamba-org/gator">gator</a></b> (🥈18 ·  ⭐ 170) - Jupyter内部的Conda环境和包管理扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/gator) (👨‍💻 24 · 🔀 20 · 📥 2 · 📦 1 · 📋 47 - 25% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/mamba-org/gator
	```
- [Conda](https://anaconda.org/conda-forge/mamba_gator) (📥 7.7K · ⏱️ 24.04.2021):
	```
	conda install -c conda-forge mamba_gator
	```
- [NPM](https://www.npmjs.com/package/@mamba-org/gator-lab) (📥 240 / month):
	```
	npm install @mamba-org/gator-lab
	```
</details>
<details><summary><b><a href="https://github.com/krishnan-r/sparkmonitor">Spark Monitor</a></b> (🥉17 ·  ⭐ 160) - 从Jupyter Notebook监控Apache Spark。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/krishnan-r/sparkmonitor) (👨‍💻 3 · 🔀 47 · 📥 2.4K · 📋 22 - 68% open · ⏱️ 03.02.2021):

	```
	git clone https://github.com/krishnan-r/sparkmonitor
	```
- [PyPi](https://pypi.org/project/sparkmonitor) (📥 1.6K / month):
	```
	pip install sparkmonitor
	```
- [Docker Hub](https://hub.docker.com/r/krishnanr/sparkmonitor) (📥 880 · ⏱️ 04.10.2019):
	```
	docker pull krishnanr/sparkmonitor
	```
</details>
<details><summary><b><a href="https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator">NBextensions Configurator</a></b> (🥉16 ·  ⭐ 850 · 💀) - A jupyter notebook serverextension providing config.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator) (👨‍💻 17 · 🔀 95 · 📋 79 - 59% open · ⏱️ 01.03.2020):

	```
	git clone https://github.com/jupyter-contrib/jupyter_nbextensions_configurator
	```
- [PyPi](https://pypi.org/project/jupyter_nbextensions_configurator) (📥 230K / month):
	```
	pip install jupyter_nbextensions_configurator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-rsession-proxy">Rsession Proxy</a></b> (🥉16 ·  ⭐ 78) - 用于运行RStudio rsession代理的Jupyter扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-rsession-proxy) (👨‍💻 16 · 🔀 51 · 📦 26 · 📋 60 - 40% open · ⏱️ 03.07.2021):

	```
	git clone https://github.com/jupyterhub/jupyter-rsession-proxy
	```
- [PyPi](https://pypi.org/project/jupyter-rsession-proxy) (📥 950 / month):
	```
	pip install jupyter-rsession-proxy
	```
</details>
<details><summary><b><a href="https://github.com/data-8/nbzip">nbzip</a></b> (🥉16 ·  ⭐ 71 · 💀) - 压缩并下载jupyter笔记本的所有内容。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/data-8/nbzip) (👨‍💻 6 · 🔀 15 · 📦 210 · 📋 14 - 64% open · ⏱️ 22.11.2019):

	```
	git clone https://github.com/data-8/nbzip
	```
- [PyPi](https://pypi.org/project/nbzip) (📥 1.2K / month):
	```
	pip install nbzip
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyter-archive">jupyter-archive</a></b> (🥉16 ·  ⭐ 41) - Jupyter / Jupyterlab扩展，用于制作，下载和提取。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyter-archive) (👨‍💻 7 · 🔀 6 · 📥 3.3K · 📋 25 - 4% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/jupyterlab-contrib/jupyter-archive
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-archive) (📥 15K · ⏱️ 17.05.2021):
	```
	conda install -c conda-forge jupyter-archive
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/jupyter-spark">Jupyter Spark</a></b> (🥉15 ·  ⭐ 190 · 💤) - 利用pandas DataFrames的Jupyter Notebook扩展。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/mozilla/jupyter-spark) (👨‍💻 12 · 🔀 30 · 📦 14 · 📋 27 - 48% open · ⏱️ 01.12.2020):

	```
	git clone https://github.com/mozilla/jupyter-spark
	```
- [PyPi](https://pypi.org/project/jupyter-spark) (📥 1.1K / month):
	```
	pip install jupyter-spark
	```
</details>
<details><summary><b><a href="https://github.com/googlecolab/jupyter_http_over_ws">HTTP-over-WebSocket</a></b> (🥉15 ·  ⭐ 180 · 💤) - Jupyter对ws-over-ws的支持。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/googlecolab/jupyter_http_over_ws) (👨‍💻 3 · 🔀 32 · 📋 25 - 72% open · ⏱️ 08.01.2021):

	```
	git clone https://github.com/googlecolab/jupyter_http_over_ws
	```
- [PyPi](https://pypi.org/project/jupyter_http_over_ws) (📥 12K / month):
	```
	pip install jupyter_http_over_ws
	```
</details>
<details><summary><b><a href="https://github.com/Anaconda-Platform/nb_conda">nb_conda</a></b> (🥉15 ·  ⭐ 120 · 💤) - Jupyter内部的Conda环境和包管理扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Anaconda-Platform/nb_conda) (👨‍💻 14 · 🔀 25 · 📋 61 - 54% open · ⏱️ 11.09.2020):

	```
	git clone https://github.com/Anaconda-Platform/nb_conda
	```
- [Conda](https://anaconda.org/conda-forge/nb_conda) (📥 290K · ⏱️ 08.02.2021):
	```
	conda install -c conda-forge nb_conda
	```
</details>
<details><summary><b><a href="https://github.com/lspvic/jupyter_tensorboard">jupyter-tensorboard</a></b> (🥉14 ·  ⭐ 450 · 💀) - 在Jupyter Notebook中启动Tensorboard。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lspvic/jupyter_tensorboard) (👨‍💻 4 · 🔀 66 · 📋 66 - 57% open · ⏱️ 16.02.2020):

	```
	git clone https://github.com/lspvic/jupyter_tensorboard
	```
- [PyPi](https://pypi.org/project/jupyter-tensorboard) (📥 2.8K / month):
	```
	pip install jupyter-tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-incubator/contentmanagement">Content Management</a></b> (🥉14 ·  ⭐ 75 · 💀) - Jupyter内容管理扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-incubator/contentmanagement) (👨‍💻 8 · 🔀 25 · 📋 27 - 25% open · ⏱️ 11.06.2018):

	```
	git clone https://github.com/jupyter-incubator/contentmanagement
	```
- [PyPi](https://pypi.org/project/jupyter_cms) (📥 210 / month):
	```
	pip install jupyter_cms
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_cms) (📥 66K · ⏱️ 15.10.2020):
	```
	conda install -c conda-forge jupyter_cms
	```
</details>
<details><summary><b><a href="https://github.com/thoth-station/jupyter-nbrequirements">jupyter-nbrequirements</a></b> (🥉12 ·  ⭐ 12) - Jupyter中的依赖关系管理和优化。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thoth-station/jupyter-nbrequirements) (👨‍💻 12 · 🔀 4 · 📋 29 - 3% open · ⏱️ 06.07.2021):

	```
	git clone https://github.com/thoth-station/jupyter-nbrequirements
	```
</details>
<details><summary><b><a href="https://github.com/paypal/PPExtensions">PPExtensions</a></b> (🥉9 ·  ⭐ 47 · 💀) - 一组iPython和Jupyter扩展。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/paypal/PPExtensions) (👨‍💻 9 · 🔀 25 · 📦 1 · 📋 38 - 42% open · ⏱️ 07.12.2018):

	```
	git clone https://github.com/paypal/PPExtensions
	```
- [PyPi](https://pypi.org/project/ppextensions) (📥 86 / month):
	```
	pip install ppextensions
	```
</details>
<details><summary><b><a href="https://github.com/drillan/jupyter-black">Jupyter Black</a></b> (🥉8 ·  ⭐ 360 · 💀) - Jupyter Notebook的黑色格式化程序。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/drillan/jupyter-black) (👨‍💻 2 · 🔀 15 · 📋 19 - 42% open · ⏱️ 01.02.2020):

	```
	git clone https://github.com/drillan/jupyter-black
	```
</details>
<details><summary><b><a href="https://github.com/willkessler/jupyterterminals">jupyterterminals</a></b> (🥉7 ·  ⭐ 7) - Jupyter插件可支持嵌入式终端外壳。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/willkessler/jupyterterminals) (👨‍💻 2 · 🔀 2 · 📦 1 · ⏱️ 17.05.2021):

	```
	git clone https://github.com/willkessler/jupyterterminals
	```
</details>
<br>

## Jupyter-magic拓展

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_提供magic命令以访问笔记本中方便功能的扩展。_

<details><summary><b><a href="https://github.com/catherinedevlin/ipython-sql">ipython-sql</a></b> (🥇27 ·  ⭐ 1.4K) - %%sql magic for IPython, hopefully evolving into full SQL client. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/catherinedevlin/ipython-sql) (👨‍💻 44 · 🔀 220 · 📦 2.1K · 📋 130 - 71% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/catherinedevlin/ipython-sql
	```
- [PyPi](https://pypi.org/project/ipython-sql) (📥 87K / month):
	```
	pip install ipython-sql
	```
- [Conda](https://anaconda.org/conda-forge/ipython-sql) (📥 120K · ⏱️ 14.10.2020):
	```
	conda install -c conda-forge ipython-sql
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-incubator/sparkmagic">sparkmagic</a></b> (🥇25 ·  ⭐ 1K) - Jupyter魔术和内核，可用于远程Spark集群。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter-incubator/sparkmagic) (👨‍💻 53 · 🔀 350 · 📦 200 · 📋 370 - 32% open · ⏱️ 08.06.2021):

	```
	git clone https://github.com/jupyter-incubator/sparkmagic
	```
- [PyPi](https://pypi.org/project/sparkmagic) (📥 44K / month):
	```
	pip install sparkmagic
	```
- [Conda](https://anaconda.org/conda-forge/sparkmagic) (📥 34K · ⏱️ 09.06.2021):
	```
	conda install -c conda-forge sparkmagic
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/watermark">watermark</a></b> (🥈22 ·  ⭐ 550 · 📉) - 一个IPython魔术扩展，用于打印日期和时间戳版本。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rasbt/watermark) (👨‍💻 15 · 🔀 66 · 📦 1.1K · 📋 40 - 35% open · ⏱️ 18.02.2021):

	```
	git clone https://github.com/rasbt/watermark
	```
- [PyPi](https://pypi.org/project/watermark) (📥 37K / month):
	```
	pip install watermark
	```
- [Conda](https://anaconda.org/conda-forge/watermark) (📥 180K · ⏱️ 18.02.2021):
	```
	conda install -c conda-forge watermark
	```
</details>
<details><summary><b><a href="https://github.com/ShopRunner/jupyter-notify">jupyter-notify</a></b> (🥈18 ·  ⭐ 530) - A Jupyter Notebook magic for browser notifications of cell.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ShopRunner/jupyter-notify) (👨‍💻 11 · 🔀 33 · 📦 68 · 📋 21 - 47% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/ShopRunner/jupyter-notify
	```
- [PyPi](https://pypi.org/project/jupyternotify) (📥 1.3K / month):
	```
	pip install jupyternotify
	```
</details>
<details><summary><b><a href="https://github.com/csurfer/blackcellmagic">blackcellmagic</a></b> (🥈15 ·  ⭐ 260 · 💀) - IPython魔术命令：格式化单元格中的python代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csurfer/blackcellmagic) (👨‍💻 3 · 🔀 8 · 📦 110 · 📋 8 - 37% open · ⏱️ 11.04.2019):

	```
	git clone https://github.com/csurfer/blackcellmagic
	```
- [PyPi](https://pypi.org/project/blackcellmagic) (📥 4.3K / month):
	```
	pip install blackcellmagic
	```
</details>
<details><summary><b><a href="https://github.com/csurfer/pyheatmagic">heat</a></b> (🥉14 ·  ⭐ 730 · 💀) - IPython魔术命令：格式化单元格中的python代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csurfer/pyheatmagic) (👨‍💻 3 · 🔀 18 · 📦 24 · 📋 5 - 40% open · ⏱️ 21.04.2018):

	```
	git clone https://github.com/csurfer/pyheatmagic
	```
- [PyPi](https://pypi.org/project/py-heat-magic) (📥 910 / month):
	```
	pip install py-heat-magic
	```
</details>
<details><summary><b><a href="https://github.com/ResidentMario/py_d3">py_d3</a></b> (🥉13 ·  ⭐ 430 · 💀) - D3 block magic for Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ResidentMario/py_d3) (👨‍💻 3 · 🔀 35 · 📋 16 - 12% open · ⏱️ 17.03.2019):

	```
	git clone https://github.com/ResidentMario/py_d3
	```
- [PyPi](https://pypi.org/project/py_d3) (📥 1K / month):
	```
	pip install py_d3
	```
</details>
<details><summary><b><a href="https://github.com/nteract/pick">pick</a></b> (🥉13 ·  ⭐ 26 · 💤) - 在启动时自定义您的内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/pick) (👨‍💻 5 · 🔀 6 · 📋 9 - 44% open · ⏱️ 04.11.2020):

	```
	git clone https://github.com/nteract/pick
	```
- [PyPi](https://pypi.org/project/pick) (📥 38K / month):
	```
	pip install pick
	```
</details>
<details><summary><b><a href="https://github.com/tmthyjames/SQLCell">SQLCell</a></b> (🥉11 ·  ⭐ 140 · 💤) - SQLCell：Jupyter Notebook的魔术函数。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tmthyjames/SQLCell) (👨‍💻 14 · 🔀 9 · 📦 1 · 📋 84 - 71% open · ⏱️ 06.10.2020):

	```
	git clone https://github.com/tmthyjames/SQLCell
	```
- [PyPi](https://pypi.org/project/sqlcell) (📥 93 / month):
	```
	pip install sqlcell
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyter-manim">jupyter-manim</a></b> (🥉10 ·  ⭐ 150) - manim单元魔术，用于IPython / Jupyter显示输出视频。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyter-manim) (👨‍💻 4 · 🔀 11 · 📋 21 - 28% open · ⏱️ 05.02.2021):

	```
	git clone https://github.com/krassowski/jupyter-manim
	```
</details>
<br>

## Jupyter内核

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Jupyter内核以给定的语言运行和内省用户的代码。_

<details><summary><b><a href="https://github.com/ipython/ipykernel">IPython Kernel</a></b> (🥇32 ·  ⭐ 410) - IPython Kernel for Jupyter. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipython/ipykernel) (👨‍💻 130 · 🔀 260 · 📦 130K · 📋 330 - 52% open · ⏱️ 12.08.2021):

	```
	git clone https://github.com/ipython/ipykernel
	```
- [PyPi](https://pypi.org/project/ipykernel) (📥 16M / month):
	```
	pip install ipykernel
	```
- [Conda](https://anaconda.org/anaconda/ipykernel) (📥 190K · ⏱️ 08.12.2020):
	```
	conda install -c anaconda ipykernel
	```
</details>
<details><summary><b><a href="https://github.com/gopherdata/gophernotes">gophernotes</a></b> (🥇23 ·  ⭐ 3K) - 适用于Jupyter笔记本电脑和nteract的Go内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gopherdata/gophernotes) (👨‍💻 28 · 🔀 200 · 📥 40 · 📦 5 · 📋 160 - 25% open · ⏱️ 24.06.2021):

	```
	git clone https://github.com/gopherdata/gophernotes
	```
- [Docker Hub](https://hub.docker.com/r/gopherdata/gophernotes) (📥 83K · ⭐ 6 · ⏱️ 22.12.2018):
	```
	docker pull gopherdata/gophernotes
	```
</details>
<details><summary><b><a href="https://github.com/IRkernel/IRkernel">IRkernel</a></b> (🥇22 ·  ⭐ 1.5K) - Jupyter的R内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IRkernel/IRkernel) (👨‍💻 40 · 🔀 280 · 📋 550 - 8% open · ⏱️ 02.08.2021):

	```
	git clone https://github.com/IRkernel/IRkernel
	```
- [Conda](https://anaconda.org/r/r-irkernel) (📥 42K · ⏱️ 10.03.2020):
	```
	conda install -c r r-irkernel
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/r-notebook) (📥 940K · ⭐ 39 · ⏱️ 09.08.2021):
	```
	docker pull jupyter/r-notebook
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/metakernel">Metakernel</a></b> (🥇22 ·  ⭐ 250) - Jupyter/IPython内核工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/metakernel) (👨‍💻 28 · 🔀 70 · 📦 470 · 📋 140 - 17% open · ⏱️ 10.05.2021):

	```
	git clone https://github.com/Calysto/metakernel
	```
- [PyPi](https://pypi.org/project/metakernel) (📥 31K / month):
	```
	pip install metakernel
	```
- [Conda](https://anaconda.org/conda-forge/metakernel) (📥 490K · ⏱️ 11.11.2020):
	```
	conda install -c conda-forge metakernel
	```
</details>
<details><summary><b><a href="https://github.com/n-riesco/ijavascript">IJavascript</a></b> (🥈20 ·  ⭐ 1.6K) - Jupyter笔记本的JavaScript内核。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/n-riesco/ijavascript) (👨‍💻 14 · 🔀 130 · 📦 51 · 📋 210 - 27% open · ⏱️ 16.06.2021):

	```
	git clone https://github.com/n-riesco/ijavascript
	```
- [NPM](https://www.npmjs.com/package/ijavascript) (📥 2.1K / month):
	```
	npm install ijavascript
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-toree">Apache Toree</a></b> (🥈20 ·  ⭐ 680) - 适用于Apache Spark的Jupyter内核。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/incubator-toree) (👨‍💻 100 · 🔀 210 · ⏱️ 09.06.2021):

	```
	git clone https://github.com/apache/incubator-toree
	```
- [PyPi](https://pypi.org/project/toree) (📥 8.4K / month):
	```
	pip install toree
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-cling">xeus-cling</a></b> (🥈19 ·  ⭐ 1.9K) - 适用于C++编程语言的Jupyter内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-cling) (👨‍💻 19 · 🔀 200 · 📋 230 - 51% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/jupyter-xeus/xeus-cling
	```
- [Conda](https://anaconda.org/conda-forge/xeus-cling) (📥 110K · ⏱️ 16.03.2021):
	```
	conda install -c conda-forge xeus-cling
	```
</details>
<details><summary><b><a href="https://github.com/almond-sh/almond">almond</a></b> (🥈19 ·  ⭐ 1.4K) - Jupyter的Scala内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/almond-sh/almond) (👨‍💻 34 · 🔀 200 · 📥 1.1K · 📋 280 - 33% open · ⏱️ 01.08.2021):

	```
	git clone https://github.com/almond-sh/almond
	```
- [Docker Hub](https://hub.docker.com/r/almondsh/almond) (📥 9.7K · ⭐ 6 · ⏱️ 01.04.2021):
	```
	docker pull almondsh/almond
	```
</details>
<details><summary><b><a href="https://github.com/SciRuby/iruby">IRuby</a></b> (🥈19 ·  ⭐ 640) - 官方gem仓库：Jupyter/IPython Notebook的Ruby内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SciRuby/iruby) (👨‍💻 44 · 🔀 7 · 📥 15 · 📦 150 · 📋 180 - 22% open · ⏱️ 20.07.2021):

	```
	git clone https://github.com/SciRuby/iruby
	```
- [Docker Hub](https://hub.docker.com/r/rubydata/datascience-notebook) (📥 1.2K · ⭐ 3 · ⏱️ 28.05.2021):
	```
	docker pull rubydata/datascience-notebook
	```
</details>
<details><summary><b><a href="https://github.com/JuliaLang/IJulia.jl">IJulia.jl</a></b> (🥈18 ·  ⭐ 2.3K) - Jupyter的Julia内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/JuliaLang/IJulia.jl) (👨‍💻 100 · 🔀 360 · 📋 770 - 12% open · ⏱️ 10.06.2021):

	```
	git clone https://github.com/JuliaLang/IJulia.jl
	```
</details>
<details><summary><b><a href="https://github.com/gibiansky/IHaskell">IHaskell</a></b> (🥈18 ·  ⭐ 2.3K) - 用于IPython的Haskell内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gibiansky/IHaskell) (👨‍💻 100 · 🔀 230 · 📋 710 - 5% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/gibiansky/IHaskell
	```
- [NPM](https://www.npmjs.com/package/ihaskell_jupyterlab) (📥 33 / month):
	```
	npm install ihaskell_jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/octave_kernel">Octave Kernel</a></b> (🥈18 ·  ⭐ 380 · 💀) - 用于IPython的Octave内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/octave_kernel) (👨‍💻 16 · 🔀 54 · 📋 160 - 19% open · ⏱️ 23.05.2020):

	```
	git clone https://github.com/calysto/octave_kernel
	```
- [PyPi](https://pypi.org/project/octave_kernel) (📥 21K / month):
	```
	pip install octave_kernel
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/kernel_gateway">Kernel Gateway</a></b> (🥈18 ·  ⭐ 360) - Jupyter内核网关。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/kernel_gateway) (👨‍💻 42 · 🔀 100 · 📥 100 · 📋 170 - 7% open · ⏱️ 08.06.2021):

	```
	git clone https://github.com/jupyter/kernel_gateway
	```
- [PyPi](https://pypi.org/project/jupyter-kernel-gateway) (📥 5K / month):
	```
	pip install jupyter-kernel-gateway
	```
</details>
<details><summary><b><a href="https://github.com/akabe/ocaml-jupyter">OCaml Kernel</a></b> (🥈18 ·  ⭐ 190) - Jupyter（IPython）笔记本的OCaml内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/akabe/ocaml-jupyter) (👨‍💻 17 · 🔀 25 · 📥 49K · 📋 66 - 4% open · ⏱️ 07.08.2021):

	```
	git clone https://github.com/akabe/ocaml-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/sassoftware/sas_kernel">SAS Kernel</a></b> (🥈18 ·  ⭐ 180) - 用于SAS的Jupyter内核。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sassoftware/sas_kernel) (👨‍💻 7 · 🔀 69 · 📋 54 - 5% open · ⏱️ 21.07.2021):

	```
	git clone https://github.com/sassoftware/sas_kernel
	```
- [PyPi](https://pypi.org/project/sas_kernel) (📥 820 / month):
	```
	pip install sas_kernel
	```
</details>
<details><summary><b><a href="https://github.com/scijava/scijava-jupyter-kernel">SciJava Kernel</a></b> (🥈18 ·  ⭐ 170) - 在Jupyter笔记本中编写SciJava脚本。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/scijava/scijava-jupyter-kernel) (👨‍💻 9 · 🔀 43 · 📥 74 · 📋 80 - 12% open · ⏱️ 09.07.2021):

	```
	git clone https://github.com/scijava/scijava-jupyter-kernel
	```
- [Conda](https://anaconda.org/conda-forge/scijava-jupyter-kernel) (📥 72K · ⏱️ 03.03.2018):
	```
	conda install -c conda-forge scijava-jupyter-kernel
	```
</details>
<details><summary><b><a href="https://github.com/vericast/spylon-kernel">Spylon Kernel</a></b> (🥈18 ·  ⭐ 140 · 💀) - Jupyter kernel for scala and spark. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/vericast/spylon-kernel) (👨‍💻 6 · 🔀 23 · 📦 63 · 📋 34 - 47% open · ⏱️ 20.09.2018):

	```
	git clone https://github.com/Valassis-Digital-Media/spylon-kernel
	```
- [PyPi](https://pypi.org/project/spylon-kernel) (📥 4.6K / month):
	```
	pip install spylon-kernel
	```
- [Conda](https://anaconda.org/conda-forge/spylon-kernel) (📥 72K · ⏱️ 05.10.2018):
	```
	conda install -c conda-forge spylon-kernel
	```
</details>
<details><summary><b><a href="https://github.com/Anaconda-Platform/nb_conda_kernels">nb_conda_kernels</a></b> (🥉17 ·  ⭐ 380 · 💤) - Package for managing conda environment-based kernels.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Anaconda-Platform/nb_conda_kernels) (👨‍💻 14 · 🔀 51 · 📋 120 - 21% open · ⏱️ 30.11.2020):

	```
	git clone https://github.com/Anaconda-Platform/nb_conda_kernels
	```
- [Conda](https://anaconda.org/conda-forge/nb_conda_kernels) (📥 460K · ⏱️ 30.01.2021):
	```
	conda install -c conda-forge nb_conda_kernels
	```
</details>
<details><summary><b><a href="https://github.com/clojupyter/clojupyter">clojupyter</a></b> (🥉16 ·  ⭐ 700 · 💤) - 用于Clojure的Jupyter内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/clojupyter/clojupyter) (👨‍💻 23 · 🔀 73 · 📋 85 - 20% open · ⏱️ 25.01.2021):

	```
	git clone https://github.com/clojupyter/clojupyter
	```
- [Conda](https://anaconda.org/simplect/clojupyter) (📥 2.3K · ⏱️ 02.03.2020):
	```
	conda install -c simplect clojupyter
	```
- [Docker Hub](https://hub.docker.com/r/simplect/clojupyter) (📥 300 · ⏱️ 25.04.2019):
	```
	docker pull simplect/clojupyter
	```
</details>
<details><summary><b><a href="https://github.com/SpencerPark/IJava">IJava</a></b> (🥉16 ·  ⭐ 680 · 💀) - 用于执行Java代码的Jupyter内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SpencerPark/IJava) (👨‍💻 4 · 🔀 130 · 📥 56K · 📋 110 - 50% open · ⏱️ 08.12.2019):

	```
	git clone https://github.com/SpencerPark/IJava
	```
</details>
<details><summary><b><a href="https://github.com/ansible/ansible-jupyter-kernel">Ansible Kernel</a></b> (🥉16 ·  ⭐ 470) - Jupyter笔记本内核，用于运行Ansible任务。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ansible/ansible-jupyter-kernel) (👨‍💻 9 · 🔀 44 · 📦 8 · 📋 41 - 29% open · ⏱️ 05.03.2021):

	```
	git clone https://github.com/ansible/ansible-jupyter-kernel
	```
- [PyPi](https://pypi.org/project/ansible-kernel) (📥 240 / month):
	```
	pip install ansible-kernel
	```
- [Conda](https://anaconda.org/conda-forge/ansible-kernel) (📥 7.8K · ⏱️ 14.01.2020):
	```
	conda install -c conda-forge ansible-kernel
	```
- [Docker Hub](https://hub.docker.com/r/benthomasson/ansible-jupyter-kernel) (📥 66K · ⭐ 2 · ⏱️ 12.12.2018):
	```
	docker pull benthomasson/ansible-jupyter-kernel
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/enterprise_gateway">Enterprise Gateway</a></b> (🥉16 ·  ⭐ 450 · 📉) - 轻量级，多租户，可扩展和安全的网关。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/enterprise_gateway) (👨‍💻 82 · 🔀 140 · 📥 10K · 📋 480 - 18% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/jupyter/enterprise_gateway
	```
- [PyPi](https://pypi.org/project/jupyter_enterprise_gateway) (📥 700 / month):
	```
	pip install jupyter_enterprise_gateway
	```
</details>
<details><summary><b><a href="https://github.com/fsprojects/IfSharp">F# Kernel</a></b> (🥉16 ·  ⭐ 430 · 💤) - F# for Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/fsprojects/IfSharp) (👨‍💻 27 · 🔀 69 · 📥 5.2K · 📋 140 - 9% open · ⏱️ 10.09.2020):

	```
	git clone https://github.com/fsprojects/IfSharp
	```
- [Docker Hub](https://hub.docker.com/r/fsprojects/ifsharp) (📥 620 · ⏱️ 26.03.2019):
	```
	docker pull fsprojects/ifsharp
	```
</details>
<details><summary><b><a href="https://github.com/WolframResearch/WolframLanguageForJupyter">Wolfram Kernel</a></b> (🥉15 ·  ⭐ 590 · 💤) - 适用于Jupyter的Wolfram语言内核。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/WolframResearch/WolframLanguageForJupyter) (👨‍💻 6 · 🔀 74 · 📥 4K · 📋 79 - 22% open · ⏱️ 15.12.2020):

	```
	git clone https://github.com/WolframResearch/WolframLanguageForJupyter
	```
</details>
<details><summary><b><a href="https://github.com/lfortran/lfortran">LFortran</a></b> (🥉15 ·  ⭐ 260) - https://gitlab.com/lfortran/lfortran的官方镜像。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/lfortran/lfortran) (👨‍💻 16 · 🔀 13 · ⏱️ 12.08.2021):

	```
	git clone https://github.com/lfortran/lfortran
	```
- [PyPi](https://pypi.org/project/lfortran) (📥 72 / month):
	```
	pip install lfortran
	```
- [Conda](https://anaconda.org/conda-forge/lfortran) (📥 26K · ⏱️ 14.07.2021):
	```
	conda install -c conda-forge lfortran
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/matlab_kernel">Matlab Kernel</a></b> (🥉14 ·  ⭐ 400 · 💤) - Jupyter的Matlab内核。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Calysto/matlab_kernel) (👨‍💻 17 · 🔀 70 · 📋 120 - 20% open · ⏱️ 09.11.2020):

	```
	git clone https://github.com/calysto/matlab_kernel
	```
- [PyPi](https://pypi.org/project/matlab_kernel) (📥 1.4K / month):
	```
	pip install matlab_kernel
	```
</details>
<details><summary><b><a href="https://github.com/pprzetacznik/IElixir">IElixir</a></b> (🥉14 ·  ⭐ 320) - Jupyter的Elixir编程语言内核。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pprzetacznik/IElixir) (👨‍💻 18 · 🔀 37 · 📋 30 - 33% open · ⏱️ 20.03.2021):

	```
	git clone https://github.com/pprzetacznik/IElixir
	```
- [Docker Hub](https://hub.docker.com/r/pprzetacznik/ielixir) (📥 290 · ⭐ 1 · ⏱️ 20.03.2021):
	```
	docker pull pprzetacznik/ielixir
	```
</details>
<details><summary><b><a href="https://github.com/Cadair/jupyter_environment_kernels">Kernel Detection</a></b> (🥉14 ·  ⭐ 140 · 💀) - 一个Jupyter插件，用于自动检测。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/Cadair/jupyter_environment_kernels) (👨‍💻 7 · 🔀 15 · 📋 28 - 21% open · ⏱️ 12.02.2018):

	```
	git clone https://github.com/Cadair/jupyter_environment_kernels
	```
- [PyPi](https://pypi.org/project/environment_kernels) (📥 5.5K / month):
	```
	pip install environment_kernels
	```
</details>
<details><summary><b><a href="https://github.com/yunabe/lgo">lgo</a></b> (🥉13 ·  ⭐ 2.2K · 💀) - 使用Jupyter进行交互式Go编程。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/yunabe/lgo) (👨‍💻 9 · 🔀 100 · 📋 75 - 29% open · ⏱️ 09.07.2019):

	```
	git clone https://github.com/yunabe/lgo
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/bash_kernel">Bash Kernel</a></b> (🥉13 ·  ⭐ 560 · 💀) - IPython的bash内核。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/takluyver/bash_kernel) (👨‍💻 13 · 🔀 99 · 📥 2.8K · 📋 89 - 40% open · ⏱️ 22.07.2019):

	```
	git clone https://github.com/takluyver/bash_kernel
	```
- [PyPi](https://pypi.org/project/bash_kernel) (📥 4.7K / month):
	```
	pip install bash_kernel
	```
</details>
<details><summary><b><a href="https://github.com/NII-cloud-operation/sshkernel">SSH Kernel</a></b> (🥉13 ·  ⭐ 44 · 💤) - Jupyter的SSH内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/NII-cloud-operation/sshkernel) (👨‍💻 4 · 🔀 9 · 📦 5 · 📋 7 - 14% open · ⏱️ 28.09.2020):

	```
	git clone https://github.com/NII-cloud-operation/sshkernel
	```
- [PyPi](https://pypi.org/project/sshkernel) (📥 190 / month):
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
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-sqlite">xeus-sqlite</a></b> (🥉10 ·  ⭐ 120) - 适用于SQLite的Jupyter内核。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-sqlite) (👨‍💻 11 · 🔀 19 · 📋 36 - 44% open · ⏱️ 13.04.2021):

	```
	git clone https://github.com/jupyter-xeus/xeus-sqlite
	```
</details>
<details><summary><b><a href="https://github.com/tdaff/remote_ikernel">remote_ikernel</a></b> (🥉10 ·  ⭐ 6 · 💤) - All your Jupyter kernels, on all your machines, in one place. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/tdaff/remote_ikernel) (👨‍💻 7 · 🔀 7 · 📋 26 - 30% open · ⏱️ 08.11.2020):

	```
	git clone https://github.com/tdaff/remote_ikernel
	```
- [PyPi](https://pypi.org/project/remote_ikernel) (📥 540 / month):
	```
	pip install remote_ikernel
	```
</details>
<details><summary><b><a href="https://github.com/bernhard-42/ssh_ipykernel">ssh_ipykernel</a></b> (🥉7 ·  ⭐ 4) - A remote jupyter kernel via ssh. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bernhard-42/ssh_ipykernel) (👨‍💻 2 · 🔀 1 · ⏱️ 28.06.2021):

	```
	git clone https://github.com/bernhard-42/ssh_ipykernel
	```
</details>
<details><summary><b><a href="https://github.com/nteract/kernel-relay">kernel-relay</a></b> (🥉6 ·  ⭐ 10 · 💀) - kernel-relay是与之接口的GraphQL服务。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/nteract/kernel-relay) (👨‍💻 3 · 🔀 5 · 📋 12 - 83% open · ⏱️ 10.07.2019):

	```
	git clone https://github.com/nteract/kernel-relay
	```
</details>
<br>

## Jupyter-Notebook分享与格式转换

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_与笔记本文件共享、转换和简化协作的工具（例如，通过git）。_

<details><summary><b><a href="https://github.com/mwouts/jupytext">Jupytext</a></b> (🥇30 ·  ⭐ 4.8K) - Jupyter Notebooks作为Markdown文档，Julia，Python或R脚本的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/jupytext) (👨‍💻 63 · 🔀 290 · 📦 1.8K · 📋 460 - 16% open · ⏱️ 31.07.2021):

	```
	git clone https://github.com/mwouts/jupytext
	```
- [PyPi](https://pypi.org/project/jupytext) (📥 250K / month):
	```
	pip install jupytext
	```
- [Conda](https://anaconda.org/conda-forge/jupytext) (📥 210K · ⏱️ 15.07.2021):
	```
	conda install -c conda-forge jupytext
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-jupytext) (📥 16K / month):
	```
	npm install jupyterlab-jupytext
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbconvert">nbconvert</a></b> (🥇30 ·  ⭐ 1.2K) - Jupyter Notebook Conversion. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/nbconvert) (👨‍💻 220 · 🔀 420 · 📦 110K · 📋 900 - 41% open · ⏱️ 19.07.2021):

	```
	git clone https://github.com/jupyter/nbconvert
	```
- [PyPi](https://pypi.org/project/nbconvert) (📥 13M / month):
	```
	pip install nbconvert
	```
- [Conda](https://anaconda.org/conda-forge/nbconvert) (📥 4.4M · ⏱️ 23.06.2021):
	```
	conda install -c conda-forge nbconvert
	```
</details>
<details><summary><b><a href="https://github.com/getnikola/nikola">nikola</a></b> (🥇28 ·  ⭐ 2.2K) - 静态网站和博客生成器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/getnikola/nikola) (👨‍💻 220 · 🔀 330 · 📦 380 · 📋 2.1K - 1% open · ⏱️ 13.07.2021):

	```
	git clone https://github.com/getnikola/nikola
	```
- [PyPi](https://pypi.org/project/nikola) (📥 2.5K / month):
	```
	pip install nikola
	```
</details>
<details><summary><b><a href="https://github.com/voila-dashboards/voila">Voila</a></b> (🥈25 ·  ⭐ 3.4K) - Voil将Jupyter笔记本变成独立的Web应用程序。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/voila-dashboards/voila) (👨‍💻 50 · 🔀 330 · 📦 4.5K · 📋 510 - 42% open · ⏱️ 01.07.2021):

	```
	git clone https://github.com/voila-dashboards/voila
	```
- [PyPi](https://pypi.org/project/voila) (📥 32K / month):
	```
	pip install voila
	```
- [Conda](https://anaconda.org/conda-forge/voila) (📥 140K · ⏱️ 28.04.2021):
	```
	conda install -c conda-forge voila
	```
- [NPM](https://www.npmjs.com/package/@jupyter-voila/jupyterlab-preview) (📥 3.6K / month):
	```
	npm install @jupyter-voila/jupyterlab-preview
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/jupyter-book">Jupyter Book</a></b> (🥈24 ·  ⭐ 2.3K) - 从Jupyter构建交互式的，具有出版质量的文档。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/executablebooks/jupyter-book) (👨‍💻 82 · 🔀 340 · 📋 850 - 37% open · ⏱️ 24.07.2021):

	```
	git clone https://github.com/executablebooks/jupyter-book
	```
- [PyPi](https://pypi.org/project/jupyter-book) (📥 20K / month):
	```
	pip install jupyter-book
	```
</details>
<details><summary><b><a href="https://github.com/damianavila/RISE">RISE</a></b> (🥈23 ·  ⭐ 3.1K) - 实时Reveal.js Jupyter/IPython幻灯片扩展。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/damianavila/RISE) (👨‍💻 39 · 🔀 350 · 📦 1.6K · 📋 410 - 31% open · ⏱️ 29.04.2021):

	```
	git clone https://github.com/damianavila/RISE
	```
- [PyPi](https://pypi.org/project/RISE) (📥 7.9K / month):
	```
	pip install RISE
	```
- [Conda](https://anaconda.org/conda-forge/rise) (📥 170K · ⏱️ 11.03.2021):
	```
	conda install -c conda-forge rise
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbdime">nbdime</a></b> (🥈23 ·  ⭐ 2.1K) - 区分和合并Jupyter笔记本的工具。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/nbdime) (👨‍💻 32 · 🔀 120 · 📦 51 · 📋 270 - 19% open · ⏱️ 24.06.2021):

	```
	git clone https://github.com/jupyter/nbdime
	```
- [PyPi](https://pypi.org/project/nbdime) (📥 190K / month):
	```
	pip install nbdime
	```
- [Conda](https://anaconda.org/conda-forge/nbdime) (📥 360K · ⏱️ 25.05.2021):
	```
	conda install -c conda-forge nbdime
	```
- [NPM](https://www.npmjs.com/package/nbdime-jupyterlab) (📥 67K / month):
	```
	npm install nbdime-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbviewer">nbviewer</a></b> (🥈22 ·  ⭐ 1.9K · 💤) - nbconvert作为Web服务：将Jupyter Notebooks渲染为静态Web。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbviewer) (👨‍💻 83 · 🔀 460 · 📦 6 · 📋 550 - 27% open · ⏱️ 02.12.2020):

	```
	git clone https://github.com/jupyter/nbviewer
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/nbviewer) (📥 1.9M · ⭐ 26 · ⏱️ 02.12.2020):
	```
	docker pull jupyter/nbviewer
	```
</details>
<details><summary><b><a href="https://github.com/stencila/stencila">Stencila</a></b> (🥈22 ·  ⭐ 600) - 用于可复制研究的在线文档。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/stencila/stencila) (👨‍💻 22 · 🔀 32 · 📥 970 · 📦 16 · 📋 480 - 4% open · ⏱️ 08.08.2021):

	```
	git clone https://github.com/stencila/stencila
	```
- [NPM](https://www.npmjs.com/package/stencila) (📥 130 / month):
	```
	npm install stencila
	```
- [Docker Hub](https://hub.docker.com/r/stencila/cloud) (📥 16K · ⏱️ 08.04.2019):
	```
	docker pull stencila/cloud
	```
</details>
<details><summary><b><a href="https://github.com/airbnb/knowledge-repo">Knowledge Repo</a></b> (🥉21 ·  ⭐ 4.8K) - 下一代知识共享平台<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airbnb/knowledge-repo) (👨‍💻 60 · 🔀 620 · 📋 280 - 41% open · ⏱️ 03.08.2021):

	```
	git clone https://github.com/airbnb/knowledge-repo
	```
- [PyPi](https://pypi.org/project/knowledge-repo) (📥 2.9K / month):
	```
	pip install knowledge-repo
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/binderhub">BinderHub</a></b> (🥉18 ·  ⭐ 2K) - 在云端运行您的代码。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/binderhub) (👨‍💻 77 · 🔀 290 · 📦 5 · 📋 590 - 41% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/jupyterhub/binderhub
	```
</details>
<details><summary><b><a href="https://github.com/aaren/notedown">notedown</a></b> (🥉18 ·  ⭐ 770 · 💀) - Markdown = IPython Notebook. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/aaren/notedown) (👨‍💻 7 · 🔀 87 · 📦 130 · 📋 68 - 57% open · ⏱️ 16.11.2017):

	```
	git clone https://github.com/aaren/notedown
	```
- [PyPi](https://pypi.org/project/notedown) (📥 4.5K / month):
	```
	pip install notedown
	```
- [Conda](https://anaconda.org/conda-forge/notedown) (📥 32K · ⏱️ 07.06.2018):
	```
	conda install -c conda-forge notedown
	```
</details>
<details><summary><b><a href="https://github.com/nteract/commuter">commuter</a></b> (🥉17 ·  ⭐ 380) - 笔记本共享中心。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/commuter) (👨‍💻 27 · 🔀 61 · 📦 3 · 📋 88 - 55% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/nteract/commuter
	```
- [NPM](https://www.npmjs.com/package/@nteract/commuter) (📥 320 / month):
	```
	npm install @nteract/commuter
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/thebe">ThebeLab</a></b> (🥉17 ·  ⭐ 220) - ThebeLab：将静态HTML页面转换为实时文档。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/executablebooks/thebe) (👨‍💻 24 · 🔀 48 · 📦 2 · 📋 120 - 49% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/executablebooks/thebe
	```
</details>
<details><summary><b><a href="https://github.com/nteract/scrapbook">scrapbook</a></b> (🥉17 ·  ⭐ 220) - 一个用于在笔记本中记录和读取数据的库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/scrapbook) (👨‍💻 11 · 🔀 23 · 📦 52 · 📋 47 - 46% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/nteract/scrapbook
	```
- [PyPi](https://pypi.org/project/nteract-scrapbook) (📥 34K / month):
	```
	pip install nteract-scrapbook
	```
</details>
<details><summary><b><a href="https://github.com/nteract/bookstore">bookstore</a></b> (🥉17 ·  ⭐ 170 · 💀) - 面向大众的笔记本存储和发布工作流程。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/bookstore) (👨‍💻 7 · 🔀 17 · 📦 4 · 📋 73 - 46% open · ⏱️ 09.12.2019):

	```
	git clone https://github.com/nteract/bookstore
	```
- [PyPi](https://pypi.org/project/bookstore) (📥 1.8K / month):
	```
	pip install bookstore
	```
</details>
<details><summary><b><a href="https://github.com/SamLau95/nbinteract">nbinteract</a></b> (🥉16 ·  ⭐ 200) - 从Jupyter Notebooks创建交互式网页。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/SamLau95/nbinteract) (👨‍💻 8 · 🔀 21 · 📦 1 · 📋 70 - 41% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/SamLau95/nbinteract
	```
- [PyPi](https://pypi.org/project/nbinteract) (📥 1.5K / month):
	```
	pip install nbinteract
	```
</details>
<details><summary><b><a href="https://github.com/ideonate/cdsdashboards">cdsdashboards</a></b> (🥉14 ·  ⭐ 120) - 用于ContainDS仪表板的JupyterHub扩展。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ideonate/cdsdashboards) (👨‍💻 10 · 🔀 23 · 📋 70 - 35% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/ideonate/cdsdashboards
	```
- [PyPi](https://pypi.org/project/cdsdashboards) (📥 480 / month):
	```
	pip install cdsdashboards
	```
- [Conda](https://anaconda.org/conda-forge/cdsdashboards) (📥 12K · ⏱️ 26.05.2021):
	```
	conda install -c conda-forge cdsdashboards
	```
</details>
<details><summary><b><a href="https://github.com/danielfrg/mkdocs-jupyter">mkdocs-jupyter</a></b> (🥉14 ·  ⭐ 72) - 在mkdocs中使用Jupyter Notebook。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/mkdocs-jupyter) (👨‍💻 7 · 🔀 9 · 📦 140 · 📋 25 - 16% open · ⏱️ 07.05.2021):

	```
	git clone https://github.com/danielfrg/mkdocs-jupyter
	```
- [PyPi](https://pypi.org/project/mkdocs-jupyter) (📥 7.1K / month):
	```
	pip install mkdocs-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/elehcimd/pynb">pynb</a></b> (🥉13 ·  ⭐ 230 · 💀) - Jupyter Notebooks是带有嵌入式Markdown文本的纯Python代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/elehcimd/pynb) (👨‍💻 8 · 🔀 5 · 📦 17 · ⏱️ 07.07.2020):

	```
	git clone https://github.com/elehcimd/pynb
	```
</details>
<details><summary><b><a href="https://github.com/nbgallery/nbgallery">nbgallery</a></b> (🥉13 ·  ⭐ 140) - 企业Jupyter笔记本共享和协作应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbgallery/nbgallery) (👨‍💻 18 · 🔀 21 · 📋 320 - 25% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/nbgallery/nbgallery
	```
- [Docker Hub](https://hub.docker.com/r/nbgallery/nbgallery) (📥 120K · ⭐ 3 · ⏱️ 02.08.2021):
	```
	docker pull nbgallery/nbgallery
	```
</details>
<details><summary><b><a href="https://github.com/danielfrg/jupyter-flex">jupyter-flex</a></b> (🥉12 ·  ⭐ 200) - 使用Jupyter Notebook构建仪表板。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/jupyter-flex) (👨‍💻 2 · 🔀 34 · 📦 29 · 📋 39 - 15% open · ⏱️ 12.08.2021):

	```
	git clone https://github.com/danielfrg/jupyter-flex
	```
</details>
<details><summary><b><a href="https://github.com/line/jnotebook_reader">jnotebook-reader</a></b> (🥉10 ·  ⭐ 83) - 一款很棒的查看器，用于浏览和渲染Jupyter。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/line/jnotebook_reader) (👨‍💻 4 · 🔀 11 · ⏱️ 10.02.2021):

	```
	git clone https://github.com/line/jnotebook_reader
	```
</details>
<br>

## Jupyter-Notebook工具

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_与笔记本文件一起工作或可以在笔记本文件中使用的库和工具。_

<details><summary><b><a href="https://github.com/jupyter/nbformat">nbformat</a></b> (🥇29 ·  ⭐ 140) - Jupyter Notebook格式的参考实现。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/nbformat) (👨‍💻 58 · 🔀 110 · 📦 120K · 📋 100 - 38% open · ⏱️ 10.06.2021):

	```
	git clone https://github.com/jupyter/nbformat
	```
- [PyPi](https://pypi.org/project/nbformat) (📥 13M / month):
	```
	pip install nbformat
	```
- [Conda](https://anaconda.org/conda-forge/nbformat) (📥 5.6M · ⏱️ 02.04.2021):
	```
	conda install -c conda-forge nbformat
	```
</details>
<details><summary><b><a href="https://github.com/pixiedust/pixiedust">PixieDust</a></b> (🥇25 ·  ⭐ 1K) - 适用于Jupyter Notebook的Python Helper库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pixiedust/pixiedust) (👨‍💻 33 · 🔀 160 · 📦 210 · 📋 420 - 38% open · ⏱️ 16.02.2021):

	```
	git clone https://github.com/pixiedust/pixiedust
	```
- [PyPi](https://pypi.org/project/pixiedust) (📥 11K / month):
	```
	pip install pixiedust
	```
- [Conda](https://anaconda.org/conda-forge/pixiedust) (📥 31K · ⏱️ 06.02.2021):
	```
	conda install -c conda-forge pixiedust
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbclient">nbclient</a></b> (🥇25 ·  ⭐ 68) - 用于执行笔记本的客户端库。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/nbclient) (👨‍💻 20 · 🔀 29 · 📦 25K · 📋 67 - 29% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/jupyter/nbclient
	```
- [PyPi](https://pypi.org/project/nbclient) (📥 12M / month):
	```
	pip install nbclient
	```
- [Conda](https://anaconda.org/conda-forge/nbclient) (📥 1.6M · ⏱️ 26.02.2021):
	```
	conda install -c conda-forge nbclient
	```
</details>
<details><summary><b><a href="https://github.com/fastai/nbdev">nbdev</a></b> (🥈24 ·  ⭐ 2.9K) - 使用Jupyter Notebook创建python项目。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastai/nbdev) (👨‍💻 61 · 🔀 290 · 📋 300 - 16% open · ⏱️ 10.08.2021):

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
- [PyPi](https://pypi.org/project/beakerx) (📥 11K / month):
	```
	pip install beakerx
	```
- [Conda](https://anaconda.org/conda-forge/beakerx) (📥 450K · ⏱️ 20.07.2021):
	```
	conda install -c conda-forge beakerx
	```
- [NPM](https://www.npmjs.com/package/beakerx) (📥 1.1K / month):
	```
	npm install beakerx
	```
- [Docker Hub](https://hub.docker.com/r/beakerx/beakerx) (📥 240K · ⭐ 22 · ⏱️ 02.12.2018):
	```
	docker pull beakerx/beakerx
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter_client">Jupyter Client</a></b> (🥈23 ·  ⭐ 240) - Jupyter protocol client APIs. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter_client) (👨‍💻 100 · 🔀 210 · 📥 2 · 📋 280 - 42% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/jupyter/jupyter_client
	```
- [PyPi](https://pypi.org/project/jupyter-client) (📥 13M / month):
	```
	pip install jupyter-client
	```
</details>
<details><summary><b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥈22 ·  ⭐ 2K) - Python中的交互式并行计算。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipython/ipyparallel) (👨‍💻 100 · 🔀 780 · 📦 1.6K · 📋 290 - 20% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/ipython/ipyparallel
	```
- [PyPi](https://pypi.org/project/ipyparallel) (📥 46K / month):
	```
	pip install ipyparallel
	```
- [Conda](https://anaconda.org/conda-forge/ipyparallel) (📥 490K · ⏱️ 05.08.2021):
	```
	conda install -c conda-forge ipyparallel
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/repo2docker">repo2docker</a></b> (🥈22 ·  ⭐ 1.2K · 📉) - 将存储库转换为支持Jupyter的Docker映像。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/repo2docker) (👨‍💻 98 · 🔀 260 · 📦 120 · 📋 430 - 30% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/jupyterhub/repo2docker
	```
- [PyPi](https://pypi.org/project/jupyter-repo2docker) (📥 3.6K / month):
	```
	pip install jupyter-repo2docker
	```
</details>
<details><summary><b><a href="https://github.com/computationalmodelling/nbval">nbval</a></b> (🥈22 ·  ⭐ 360 · 💤) - 一个py.test插件，用于验证Jupyter笔记本。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/computationalmodelling/nbval) (👨‍💻 26 · 🔀 36 · 📦 1.1K · 📋 91 - 34% open · ⏱️ 27.01.2021):

	```
	git clone https://github.com/computationalmodelling/nbval
	```
- [PyPi](https://pypi.org/project/nbval) (📥 79K / month):
	```
	pip install nbval
	```
- [Conda](https://anaconda.org/conda-forge/nbval) (📥 150K · ⏱️ 31.07.2020):
	```
	conda install -c conda-forge nbval
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-sphinx">Jupyter Sphinx</a></b> (🥈19 ·  ⭐ 130) - Sphinx扩展，用于呈现Jupyter交互式小部件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-sphinx) (👨‍💻 23 · 🔀 42 · 📋 100 - 30% open · ⏱️ 29.04.2021):

	```
	git clone https://github.com/jupyter/jupyter-sphinx
	```
- [PyPi](https://pypi.org/project/jupyter_sphinx) (📥 63K / month):
	```
	pip install jupyter_sphinx
	```
</details>
<details><summary><b><a href="https://github.com/chmp/ipytest">ipytest</a></b> (🥉17 ·  ⭐ 160) - IPython笔记本中的Pytest。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chmp/ipytest) (👨‍💻 4 · 🔀 14 · 📦 100 · 📋 43 - 4% open · ⏱️ 28.07.2021):

	```
	git clone https://github.com/chmp/ipytest
	```
- [PyPi](https://pypi.org/project/ipytest) (📥 14K / month):
	```
	pip install ipytest
	```
</details>
<details><summary><b><a href="https://github.com/QuantEcon/sphinxcontrib-jupyter">sphinxcontrib.jupyter</a></b> (🥉17 ·  ⭐ 67 · 💀) - 用于生成Jupyter笔记本的Sphinx扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/QuantEcon/sphinxcontrib-jupyter) (👨‍💻 13 · 🔀 23 · 📦 23 · 📋 180 - 48% open · ⏱️ 18.06.2020):

	```
	git clone https://github.com/QuantEcon/sphinxcontrib-jupyter
	```
- [PyPi](https://pypi.org/project/sphinxcontrib-jupyter) (📥 420 / month):
	```
	pip install sphinxcontrib-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/nbQA-dev/nbQA">nbQA</a></b> (🥉16 ·  ⭐ 270) - 在Jupyter Notebook上运行任何标准的Python代码质量工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbQA-dev/nbQA) (👨‍💻 14 · 🔀 17 · 📋 230 - 1% open · ⏱️ 09.08.2021):

	```
	git clone https://github.com/nbQA-dev/nbQA
	```
- [PyPi](https://pypi.org/project/nbqa) (📥 13K / month):
	```
	pip install nbqa
	```
</details>
<details><summary><b><a href="https://github.com/ReviewNB/treon">treon</a></b> (🥉15 ·  ⭐ 270 · 💤) - Jupyter Notebooks易于使用的测试框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ReviewNB/treon) (👨‍💻 4 · 🔀 18 · 📦 34 · 📋 11 - 18% open · ⏱️ 08.10.2020):

	```
	git clone https://github.com/ReviewNB/treon
	```
- [PyPi](https://pypi.org/project/treon) (📥 2.5K / month):
	```
	pip install treon
	```
</details>
<details><summary><b><a href="https://github.com/treebeardtech/nbmake-action">nbmake-action</a></b> (🥉15 ·  ⭐ 150) - GitHub用于测试笔记本的动作。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/treebeardtech/nbmake-action) (👨‍💻 2 · 🔀 6 · 📦 60 · ⏱️ 09.04.2021):

	```
	git clone https://github.com/treebeardtech/nbmake-action
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/nbopen">nbopen</a></b> (🥉14 ·  ⭐ 260 · 💀) - Open a Jupyter notebook in the best available server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/takluyver/nbopen) (👨‍💻 10 · 🔀 49 · 📋 59 - 57% open · ⏱️ 25.04.2018):

	```
	git clone https://github.com/takluyver/nbopen
	```
- [PyPi](https://pypi.org/project/nbopen) (📥 2.2K / month):
	```
	pip install nbopen
	```
</details>
<details><summary><b><a href="https://github.com/nteract/testbook">testbook</a></b> (🥉14 ·  ⭐ 250) - 以正确的方式对Jupyter笔记本进行单元测试。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/testbook) (👨‍💻 13 · 🔀 25 · 📦 49 · 📋 76 - 42% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/nteract/testbook
	```
</details>
<details><summary><b><a href="https://github.com/tweag/jupyterWith">JupyterWith</a></b> (🥉13 ·  ⭐ 280) - 声明性和可复制的Jupyter环境-由Nix提供支持。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tweag/jupyterWith) (👨‍💻 18 · 🔀 62 · 📋 77 - 50% open · ⏱️ 29.07.2021):

	```
	git clone https://github.com/tweag/jupyterWith
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyter-helpers">Jupyter Helpers</a></b> (🥉13 ·  ⭐ 41) - Jupyter/IPython的帮助程序集合。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyter-helpers) (👨‍💻 2 · 🔀 3 · 📋 5 - 60% open · ⏱️ 31.07.2021):

	```
	git clone https://github.com/krassowski/jupyter-helpers
	```
- [PyPi](https://pypi.org/project/jupyter_helpers) (📥 220 / month):
	```
	pip install jupyter_helpers
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-naas/naas">naas</a></b> (🥉12 ·  ⭐ 98) - Notebook调度工具，像API一样运行它们。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/jupyter-naas/naas) (👨‍💻 13 · 🔀 10 · 📦 1 · 📋 96 - 80% open · ⏱️ 12.08.2021):

	```
	git clone https://github.com/jupyter-naas/naas
	```
- [PyPi](https://pypi.org/project/naas) (📥 8.1K / month):
	```
	pip install naas
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/jupyter_kernel_mgmt">Kernel Management</a></b> (🥉12 ·  ⭐ 13 · 💀) - 针对Jupyter的实验性新内核管理框架。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/takluyver/jupyter_kernel_mgmt) (👨‍💻 74 · 🔀 7 · 📥 15 · 📋 24 - 41% open · ⏱️ 29.01.2020):

	```
	git clone https://github.com/takluyver/jupyter_kernel_mgmt
	```
- [PyPi](https://pypi.org/project/jupyter-kernel-mgmt) (📥 80 / month):
	```
	pip install jupyter-kernel-mgmt
	```
</details>
<details><summary><b><a href="https://github.com/datitran/jupyter2slides">jupyter2slides</a></b> (🥉11 ·  ⭐ 770 · 💀) - 使用Jupyter Notebook的Cloud Native演示幻灯片<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/datitran/jupyter2slides) (🔀 160 · 📋 15 - 73% open · ⏱️ 28.12.2018):

	```
	git clone https://github.com/datitran/jupyter2slides
	```
</details>
<details><summary><b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉11 ·  ⭐ 140) - 适用于GPU和一般设备的jupyter / ipython实验容器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/stas00/ipyexperiments) (👨‍💻 3 · 🔀 10 · 📦 5 · ⏱️ 28.03.2021):

	```
	git clone https://github.com/stas00/ipyexperiments
	```
- [PyPi](https://pypi.org/project/ipyexperiments) (📥 240 / month):
	```
	pip install ipyexperiments
	```
</details>
<details><summary><b><a href="https://github.com/Invictify/Jupter-Notebook-REST-API">Jupter-Notebook-REST-API</a></b> (🥉7 ·  ⭐ 30 · 💀) - 将jupyter笔记本作为REST API端点运行。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Invictify/Jupter-Notebook-REST-API) (👨‍💻 2 · 🔀 3 · ⏱️ 31.03.2020):

	```
	git clone https://github.com/Invictify/Jupter-Notebook-REST-API
	```
</details>
<br>

## JupyterLab渲染器

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_可以呈现和显示特定MIME类型文件的扩展名。_

<details><summary><b><a href="https://github.com/jupyterlab/jupyter-renderers">JupyterLab Renderers</a></b> (🥇19 ·  ⭐ 400) - JupyterLab的渲染器和渲染器扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyter-renderers) (👨‍💻 22 · 🔀 60 · 📦 1 · 📋 98 - 29% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyter-renderers
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/geojson-extension) (📥 81K / month):
	```
	npm install @jupyterlab/geojson-extension
	```
</details>
<details><summary><b><a href="https://github.com/plotly/jupyterlab-dash">JupyterLab Dash</a></b> (🥇19 ·  ⭐ 350 · 💀) - An Extension for the Interactive development of Dash apps in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/jupyterlab-dash) (👨‍💻 7 · 🔀 51 · 📦 130 · 📋 28 - 71% open · ⏱️ 19.05.2020):

	```
	git clone https://github.com/plotly/jupyterlab-dash
	```
- [PyPi](https://pypi.org/project/jupyterlab-dash) (📥 1.5K / month):
	```
	pip install jupyterlab-dash
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-dash) (📥 13K / month):
	```
	npm install jupyterlab-dash
	```
</details>
<details><summary><b><a href="https://github.com/QuantStack/jupyterlab-drawio">JupyterLab Drawio</a></b> (🥈18 ·  ⭐ 490) - FOSS drawio/mxgraph程序包的独立嵌入。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/QuantStack/jupyterlab-drawio) (👨‍💻 15 · 🔀 56 · 📦 84 · 📋 62 - 59% open · ⏱️ 29.06.2021):

	```
	git clone https://github.com/QuantStack/jupyterlab-drawio
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-drawio) (📥 5.6K / month):
	```
	npm install jupyterlab-drawio
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-latex">JupyterLab Latex</a></b> (🥉16 ·  ⭐ 490) - JupyterLab扩展，用于实时编辑LaTeX文档。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-latex) (👨‍💻 20 · 🔀 54 · 📦 2 · 📋 79 - 62% open · ⏱️ 14.07.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-latex
	```
- [PyPi](https://pypi.org/project/jupyterlab_latex) (📥 950 / month):
	```
	pip install jupyterlab_latex
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/latex) (📥 2.4K / month):
	```
	npm install @jupyterlab/latex
	```
</details>
<details><summary><b><a href="https://github.com/plotly/jupyterlab-chart-editor">JupyterLab Chart Editor</a></b> (🥉16 ·  ⭐ 200) - JupyterLab扩展，用于实时编辑LaTeX文档。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/plotly/jupyterlab-chart-editor) (👨‍💻 5 · 🔀 19 · 📦 3 · 📋 31 - 38% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/plotly/jupyterlab-chart-editor
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-chart-editor) (📥 2.3K / month):
	```
	npm install jupyterlab-chart-editor
	```
</details>
<details><summary><b><a href="https://github.com/quigleyj97/jupyterlab-spreadsheet">JupyterLab Spreadsheet</a></b> (🥉15 ·  ⭐ 120) - JupyterLab插件，用于查看电子表格。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/quigleyj97/jupyterlab-spreadsheet) (👨‍💻 4 · 🔀 9 · 📋 22 - 27% open · ⏱️ 17.07.2021):

	```
	git clone https://github.com/quigleyj97/jupyterlab-spreadsheet
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-spreadsheet) (📥 6K / month):
	```
	npm install jupyterlab-spreadsheet
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/jupyterlab_voyager">JupyterLab Voyager</a></b> (🥉13 ·  ⭐ 260 · 💀) - JupyterLab extension visualize data with Voyager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/jupyterlab_voyager) (👨‍💻 6 · 🔀 31 · 📋 60 - 66% open · ⏱️ 14.08.2019):

	```
	git clone https://github.com/altair-viz/jupyterlab_voyager
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_voyager) (📥 100 / month):
	```
	npm install jupyterlab_voyager
	```
</details>
<br>

## JupyterLab主题

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_可以自定义JupyterLab外观的扩展。_

<details><summary><b><a href="https://github.com/telamonian/theme-darcula">Darcula Theme</a></b> (🥇16 ·  ⭐ 110) - A handsome Darcula theme for Jupyterlab. The first jlab theme to.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/telamonian/theme-darcula) (👨‍💻 7 · 🔀 13 · 📦 73 · 📋 19 - 26% open · ⏱️ 19.07.2021):

	```
	git clone https://github.com/telamonian/theme-darcula
	```
- [NPM](https://www.npmjs.com/package/@telamonian/theme-darcula) (📥 3.9K / month):
	```
	npm install @telamonian/theme-darcula
	```
</details>
<details><summary><b><a href="https://github.com/AllanChain/jupyterlab-theme-solarized-dark">jupyterlab-theme-solarized-dark</a></b> (🥈14 ·  ⭐ 41) - JupyterLab 2.x Solarized Dark扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/AllanChain/jupyterlab-theme-solarized-dark) (👨‍💻 2 · 🔀 3 · 📋 2 - 50% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/AllanChain/jupyterlab-theme-solarized-dark
	```
- [PyPi](https://pypi.org/project/jupyterlab_theme_solarized_dark) (📥 280 / month):
	```
	pip install jupyterlab_theme_solarized_dark
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-theme-solarized-dark) (📥 4.4K / month):
	```
	npm install jupyterlab-theme-solarized-dark
	```
</details>
<details><summary><b><a href="https://github.com/yeebc/jupyterlab-neon-theme">Neon Theme</a></b> (🥈12 ·  ⭐ 99) - JupyterLab的扁平，80年代霓虹灯启发主题。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/yeebc/jupyterlab-neon-theme) (👨‍💻 3 · 🔀 5 · 📦 1 · 📋 12 - 16% open · ⏱️ 07.03.2021):

	```
	git clone https://github.com/yeebc/jupyterlab-neon-theme
	```
- [NPM](https://www.npmjs.com/package/@yeebc/jupyterlab_neon_theme) (📥 1.4K / month):
	```
	npm install @yeebc/jupyterlab_neon_theme
	```
</details>
<details><summary><b><a href="https://github.com/mohirio/jupyterlab-horizon-theme">Horizon Theme</a></b> (🥈12 ·  ⭐ 35) - JupyterLab的VSCode Horizo​​n主题端口。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mohirio/jupyterlab-horizon-theme) (🔀 1 · ⏱️ 11.04.2021):

	```
	git clone https://github.com/mohirio/jupyterlab-horizon-theme
	```
- [NPM](https://www.npmjs.com/package/@mohirio/jupyterlab-horizon-theme) (📥 2.8K / month):
	```
	npm install @mohirio/jupyterlab-horizon-theme
	```
</details>
<details><summary><b><a href="https://github.com/oriolmirosa/jupyterlab_materialdarker">Material Darker Theme</a></b> (🥉9 ·  ⭐ 130 · 💀) - JupyterLab的Material Darker主题。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/oriolmirosa/jupyterlab_materialdarker) (👨‍💻 2 · 🔀 12 · 📦 4 · 📋 16 - 25% open · ⏱️ 09.05.2020):

	```
	git clone https://github.com/oriolmirosa/jupyterlab_materialdarker
	```
- [NPM](https://www.npmjs.com/package/@oriolmirosa/jupyterlab_materialdarker) (📥 990 / month):
	```
	npm install @oriolmirosa/jupyterlab_materialdarker
	```
</details>
<details><summary><b><a href="https://github.com/Rahlir/theme-gruvbox">Gruvbox Theme</a></b> (🥉9 ·  ⭐ 39 · 💀) - Jupyter Lab的Gruvbox黑暗主题。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/Rahlir/theme-gruvbox) (👨‍💻 3 · 🔀 9 · ⏱️ 12.04.2020):

	```
	git clone https://github.com/Rahlir/theme-gruvbox
	```
- [NPM](https://www.npmjs.com/package/@rahlir/theme-gruvbox) (📥 160 / month):
	```
	npm install @rahlir/theme-gruvbox
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-theme-toggle">Theme Toggle</a></b> (🥉9 ·  ⭐ 9) - JupyterLab extension to toggle the theme in the Top Bar area. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-theme-toggle) (👨‍💻 2 · 🔀 1 · 📦 2 · 📋 3 - 66% open · ⏱️ 16.06.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-theme-toggle
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-theme-toggle) (📥 2.6K / month):
	```
	npm install jupyterlab-theme-toggle
	```
</details>
<details><summary><b><a href="https://github.com/kenshohara/theme-nord-extension">Nord Theme</a></b> (🥉6 ·  ⭐ 24 · 💤) - JupyterLab-Nord主题。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/kenshohara/theme-nord-extension) (🔀 1 · 📋 5 - 20% open · ⏱️ 20.09.2020):

	```
	git clone https://github.com/kenshohara/theme-nord-extension
	```
- [NPM](https://www.npmjs.com/package/@kenshohara/theme-nord-extension) (📥 50 / month):
	```
	npm install @kenshohara/theme-nord-extension
	```
</details>
<br>

## JupyterLab扩展

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_扩展JupyterLab自身功能的应用程序插件。_

<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-git">JupyterLab Git</a></b> (🥇26 ·  ⭐ 930) - JupyterLab的Git扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-git) (👨‍💻 64 · 🔀 180 · 📦 13 · 📋 480 - 17% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-git
	```
- [PyPi](https://pypi.org/project/jupyterlab-git) (📥 120K / month):
	```
	pip install jupyterlab-git
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-git) (📥 85K · ⏱️ 04.08.2021):
	```
	conda install -c conda-forge jupyterlab-git
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyterlab-lsp">JupyterLab LSP</a></b> (🥇25 ·  ⭐ 990 · 📈) - JupyterLab的编码帮助（代码导航+悬停）。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyterlab-lsp) (👨‍💻 33 · 🔀 77 · 📦 49 · 📋 340 - 32% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/krassowski/jupyterlab-lsp
	```
- [NPM](https://www.npmjs.com/package/@krassowski/jupyterlab-lsp) (📥 12K / month):
	```
	npm install @krassowski/jupyterlab-lsp
	```
</details>
<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥇24 ·  ⭐ 3.5K) - 通过WebAssembly进行流式透视显示。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 64 · 🔀 380 · 📦 200 · 📋 430 - 14% open · ⏱️ 12.08.2021):

	```
	git clone https://github.com/finos/perspective
	```
- [PyPi](https://pypi.org/project/perspective-python) (📥 2.3K / month):
	```
	pip install perspective-python
	```
- [NPM](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 2.2K / month):
	```
	npm install @finos/perspective-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/debugger">JupyterLab Debugger</a></b> (🥇24 ·  ⭐ 510) - 适用于Jupyter笔记本电脑，控制台等的可视调试器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/debugger) (👨‍💻 11 · 🔀 34 · 📦 92 · 📋 260 - 6% open · ⏱️ 31.03.2021):

	```
	git clone https://github.com/jupyterlab/debugger
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/debugger) (📥 66K / month):
	```
	npm install @jupyterlab/debugger
	```
</details>
<details><summary><b><a href="https://github.com/elyra-ai/elyra">elyra</a></b> (🥇22 ·  ⭐ 1K) - Elyra以AI为中心的方法对JupyterLab笔记本进行拓展。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/elyra-ai/elyra) (👨‍💻 29 · 🔀 160 · 📦 20 · 📋 1.1K - 19% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/elyra-ai/elyra
	```
- [PyPi](https://pypi.org/project/elyra) (📥 1.7K / month):
	```
	pip install elyra
	```
- [Conda](https://anaconda.org/conda-forge/elyra) (📥 6.3K · ⏱️ 27.04.2021):
	```
	conda install -c conda-forge elyra
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-toc">JupyterLab TOC</a></b> (🥇22 ·  ⭐ 690) - Table of Contents extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-toc) (👨‍💻 13 · 🔀 98 · 📦 110 · 📋 110 - 57% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-toc
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/toc) (📥 92K / month):
	```
	npm install @jupyterlab/toc
	```
</details>
<details><summary><b><a href="https://github.com/lckr/jupyterlab-variableInspector">Variable Inspector</a></b> (🥈21 ·  ⭐ 820) - Jupyterlab的变量查看器扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lckr/jupyterlab-variableInspector) (👨‍💻 16 · 🔀 75 · 📦 3 · 📋 140 - 20% open · ⏱️ 10.04.2021):

	```
	git clone https://github.com/lckr/jupyterlab-variableInspector
	```
- [NPM](https://www.npmjs.com/package/@lckr/jupyterlab_variableinspector) (📥 10K / month):
	```
	npm install @lckr/jupyterlab_variableinspector
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-system-monitor">JupyterLab System Monitor</a></b> (🥈19 ·  ⭐ 190) - JupyterLab扩展以显示系统指标。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-system-monitor) (👨‍💻 5 · 🔀 22 · 📦 16 · 📋 29 - 44% open · ⏱️ 17.06.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-system-monitor
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-system-monitor) (📥 9.8K / month):
	```
	npm install jupyterlab-system-monitor
	```
</details>
<details><summary><b><a href="https://github.com/ryantam626/jupyterlab_code_formatter">Code Formatter</a></b> (🥈18 ·  ⭐ 460) - JupyterLab的通用代码格式化工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ryantam626/jupyterlab_code_formatter) (👨‍💻 30 · 🔀 37 · 📋 130 - 14% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/ryantam626/jupyterlab_code_formatter
	```
- [PyPi](https://pypi.org/project/jupyterlab_code_formatter) (📥 15K / month):
	```
	pip install jupyterlab_code_formatter
	```
- [NPM](https://www.npmjs.com/package/@ryantam626/jupyterlab_code_formatter) (📥 9.3K / month):
	```
	npm install @ryantam626/jupyterlab_code_formatter
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/jupyterlab-nvdashboard">GPU Dashboards</a></b> (🥈18 ·  ⭐ 410) - 一个JupyterLab扩展，用于显示GPU的仪表板。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rapidsai/jupyterlab-nvdashboard) (👨‍💻 15 · 🔀 46 · 📋 50 - 44% open · ⏱️ 06.07.2021):

	```
	git clone https://github.com/rapidsai/jupyterlab-nvdashboard
	```
- [PyPi](https://pypi.org/project/jupyterlab-nvdashboard) (📥 2.9K / month):
	```
	pip install jupyterlab-nvdashboard
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-nvdashboard) (📥 8.3K / month):
	```
	npm install jupyterlab-nvdashboard
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-google-drive">JupyterLab Google Drive</a></b> (🥈18 ·  ⭐ 340) - 使用Google云端硬盘的JupyterLab的云存储。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-google-drive) (👨‍💻 14 · 🔀 66 · 📦 2 · 📋 94 - 30% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-google-drive
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/google-drive) (📥 1.4K / month):
	```
	npm install @jupyterlab/google-drive
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-github">JupyterLab GitHub</a></b> (🥈18 ·  ⭐ 290 · 💀) - GitHub integration for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-github) (👨‍💻 12 · 🔀 72 · 📦 2 · 📋 57 - 40% open · ⏱️ 04.03.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-github
	```
- [PyPi](https://pypi.org/project/jupyterlab-github) (📥 510 / month):
	```
	pip install jupyterlab-github
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/github) (📥 1.9K / month):
	```
	npm install @jupyterlab/github
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/jupyterlab_templates">JupyterLab Templates</a></b> (🥈18 ·  ⭐ 260) - 在jupyterlab的jupyter-Notebook各种模板。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/jupyterlab_templates) (👨‍💻 13 · 🔀 42 · 📦 4 · 📋 74 - 9% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/jpmorganchase/jupyterlab_templates
	```
- [PyPi](https://pypi.org/project/jupyterlab_templates) (📥 4.2K / month):
	```
	pip install jupyterlab_templates
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_templates) (📥 3.4K / month):
	```
	npm install jupyterlab_templates
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask-labextension">dask-labextension</a></b> (🥈18 ·  ⭐ 230) - JupyterLab扩展，用于实时编辑LaTeX文档。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-labextension) (👨‍💻 18 · 🔀 39 · 📋 110 - 28% open · ⏱️ 05.08.2021):

	```
	git clone https://github.com/dask/dask-labextension
	```
- [PyPi](https://pypi.org/project/dask-labextension) (📥 5.6K / month):
	```
	pip install dask-labextension
	```
- [Conda](https://anaconda.org/conda-forge/dask-labextension) (📥 350K · ⏱️ 30.07.2021):
	```
	conda install -c conda-forge dask-labextension
	```
- [NPM](https://www.npmjs.com/package/dask-labextension) (📥 7.7K / month):
	```
	npm install dask-labextension
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/jupyterlab-sidecar">JupyterLab SideCar</a></b> (🥈18 ·  ⭐ 180) - JupyterLab的sidecar输出小部件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/jupyterlab-sidecar) (👨‍💻 13 · 🔀 34 · 📦 3 · 📋 29 - 65% open · ⏱️ 04.07.2021):

	```
	git clone https://github.com/jupyter-widgets/jupyterlab-sidecar
	```
- [PyPi](https://pypi.org/project/sidecar) (📥 1.7K / month):
	```
	pip install sidecar
	```
- [NPM](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-sidecar) (📥 1.3K / month):
	```
	npm install @jupyter-widgets/jupyterlab-sidecar
	```
</details>
<details><summary><b><a href="https://github.com/jwkvam/jupyterlab-vim">JupyterLab Vim</a></b> (🥈17 ·  ⭐ 870 · 💀) - 用于JupyterLab的Vim笔记本cell绑定。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jwkvam/jupyterlab-vim) (👨‍💻 8 · 🔀 70 · 📦 3 · 📋 94 - 55% open · ⏱️ 16.07.2019):

	```
	git clone https://github.com/jwkvam/jupyterlab-vim
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_vim) (📥 710 / month):
	```
	npm install jupyterlab_vim
	```
</details>
<details><summary><b><a href="https://github.com/krassowski/jupyterlab-go-to-definition">JupyterLab Go-To-Definition</a></b> (🥈17 ·  ⭐ 200) - 变量的定义查看器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/krassowski/jupyterlab-go-to-definition) (👨‍💻 2 · 🔀 8 · 📦 10 · 📋 23 - 43% open · ⏱️ 28.07.2021):

	```
	git clone https://github.com/krassowski/jupyterlab-go-to-definition
	```
- [NPM](https://www.npmjs.com/package/@krassowski/jupyterlab_go_to_definition) (📥 4.2K / month):
	```
	npm install @krassowski/jupyterlab_go_to_definition
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/lantern">Lantern</a></b> (🥈16 ·  ⭐ 300) - 数据探索工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/lantern) (👨‍💻 2 · 🔀 19 · 📦 14 · 📋 200 - 5% open · ⏱️ 27.02.2021):

	```
	git clone https://github.com/timkpaine/lantern
	```
- [PyPi](https://pypi.org/project/pylantern) (📥 160 / month):
	```
	pip install pylantern
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/spellchecker">JupyterLab Spellchecker</a></b> (🥈16 ·  ⭐ 120) - JupyterLab笔记本降价单元的拼写检查器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/spellchecker) (👨‍💻 6 · 🔀 16 · 📦 1 · 📋 40 - 20% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/ijmbarr/jupyterlab_spellchecker
	```
- [NPM](https://www.npmjs.com/package/@ijmbarr/jupyterlab_spellchecker) (📥 3.7K / month):
	```
	npm install @ijmbarr/jupyterlab_spellchecker
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_iframe">JupyterLab IFrame</a></b> (🥈16 ·  ⭐ 75) - JupyterLab iframe小部件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_iframe) (👨‍💻 4 · 🔀 14 · 📦 3 · 📋 61 - 8% open · ⏱️ 18.06.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_iframe
	```
- [PyPi](https://pypi.org/project/jupyterlab_iframe) (📥 760 / month):
	```
	pip install jupyterlab_iframe
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_iframe) (📥 1.4K / month):
	```
	npm install jupyterlab_iframe
	```
</details>
<details><summary><b><a href="https://github.com/chaoleili/jupyterlab_tensorboard">JupyterLab Tensorboard</a></b> (🥉15 ·  ⭐ 270) - Jupyterlab的Tensorboard扩展。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chaoleili/jupyterlab_tensorboard) (👨‍💻 6 · 🔀 26 · 📦 2 · 📋 26 - 65% open · ⏱️ 24.02.2021):

	```
	git clone https://github.com/chaoleili/jupyterlab_tensorboard
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_tensorboard) (📥 6K / month):
	```
	npm install jupyterlab_tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/jupyter_bokeh">Jupyter Bokeh</a></b> (🥉15 ·  ⭐ 180) - 用于在JupyterLab笔记本中呈现Bokeh内容的扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/jupyter_bokeh) (👨‍💻 15 · 🔀 31 · 📋 76 - 7% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/bokeh/jupyter_bokeh
	```
- [PyPi](https://pypi.org/project/jupyter-bokeh) (📥 13K / month):
	```
	pip install jupyter-bokeh
	```
- [NPM](https://www.npmjs.com/package/@bokeh/jupyter_bokeh) (📥 31K / month):
	```
	npm install @bokeh/jupyter_bokeh
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-data-explorer">JupyterLab Data Explorer</a></b> (🥉15 ·  ⭐ 160 · 💀) - JupyterLab中的一流数据集。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-data-explorer) (👨‍💻 9 · 🔀 29 · 📦 10 · 📋 88 - 61% open · ⏱️ 24.05.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-data-explorer
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/dataregistry-extension) (📥 140 / month):
	```
	npm install @jupyterlab/dataregistry-extension
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-celltags">jupyterlab-celltags</a></b> (🥉15 ·  ⭐ 110 · 💀) - 一个JupyterLab扩展，用于显示GPU的仪表板。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-celltags) (👨‍💻 10 · 🔀 24 · 📦 270 · 📋 18 - 61% open · ⏱️ 29.04.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-celltags
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-python-file">JupyterLab Python Files</a></b> (🥉15 ·  ⭐ 48) - JupyterLab扩展来创建Python文件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-python-file) (👨‍💻 4 · 🔀 7 · 📥 74 · 📋 9 - 22% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-python-file
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-python-file) (📥 3.3K / month):
	```
	npm install jupyterlab-python-file
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/gather">nbgather</a></b> (🥉14 ·  ⭐ 400 · 💀) - Jupyter笔记本分割工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/gather) (👨‍💻 12 · 🔀 28 · 📋 26 - 38% open · ⏱️ 14.02.2020):

	```
	git clone https://github.com/microsoft/gather
	```
- [NPM](https://www.npmjs.com/package/nbgather) (📥 100 / month):
	```
	npm install nbgather
	```
</details>
<details><summary><b><a href="https://github.com/pbugnion/jupyterlab-sql">JupyterLab SQL</a></b> (🥉14 ·  ⭐ 350 · 💀) - JupyterLab的SQL GUI。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pbugnion/jupyterlab-sql) (👨‍💻 2 · 🔀 39 · 📋 74 - 50% open · ⏱️ 04.01.2020):

	```
	git clone https://github.com/pbugnion/jupyterlab-sql
	```
- [PyPi](https://pypi.org/project/jupyterlab_sql) (📥 890 / month):
	```
	pip install jupyterlab_sql
	```
</details>
<details><summary><b><a href="https://github.com/deshaw/jupyterlab-execute-time">jupyterlab-execute-time</a></b> (🥉14 ·  ⭐ 160) - 为Jupyter Lab执行时间插件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/deshaw/jupyterlab-execute-time) (👨‍💻 9 · 🔀 16 · 📋 22 - 4% open · ⏱️ 12.07.2021):

	```
	git clone https://github.com/deshaw/jupyterlab-execute-time
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-execute-time) (📥 6.2K / month):
	```
	npm install jupyterlab-execute-time
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyterlab-kernelspy">JupyterLab Kernelspy</a></b> (🥉14 ·  ⭐ 58 · 📈) - Jupyter Lab扩展，用于检查往返于邮件的信息。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyterlab-kernelspy) (👨‍💻 4 · 🔀 7 · 📦 3 · 📋 13 - 15% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/jupyterlab-contrib/jupyterlab-kernelspy
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-kernelspy) (📥 360 / month):
	```
	npm install jupyterlab-kernelspy
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-shortcutui">JupyterLab Shortcutui</a></b> (🥉14 ·  ⭐ 55 · 💀) - 一个JupyterLab扩展，用于显示GPU的仪表板。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-shortcutui) (👨‍💻 8 · 🔀 14 · 📋 13 - 53% open · ⏱️ 17.01.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-shortcutui
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/shortcutui) (📥 610 / month):
	```
	npm install @jupyterlab/shortcutui
	```
</details>
<details><summary><b><a href="https://github.com/vatlab/jupyterlab-sos">jupyterlab-sos</a></b> (🥉14 ·  ⭐ 47) - 适用于SoS Polyglot笔记本和工作流程的Jupyterlab扩展<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/jupyterlab-sos) (👨‍💻 3 · 📦 4 · 📋 57 - 17% open · ⏱️ 14.04.2021):

	```
	git clone https://github.com/vatlab/jupyterlab-sos
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-sos) (📥 11K · ⏱️ 16.04.2021):
	```
	conda install -c conda-forge jupyterlab-sos
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-sos) (📥 320 / month):
	```
	npm install jupyterlab-sos
	```
</details>
<details><summary><b><a href="https://github.com/aquirdTurtle/Collapsible_Headings">Collapsible Headings</a></b> (🥉13 ·  ⭐ 140) - 为Jupyter实验室笔记本实现可折叠页眉。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/aquirdTurtle/Collapsible_Headings) (👨‍💻 6 · 🔀 6 · 📋 27 - 22% open · ⏱️ 22.05.2021):

	```
	git clone https://github.com/aquirdTurtle/Collapsible_Headings
	```
- [NPM](https://www.npmjs.com/package/@aquirdturtle/collapsible_headings) (📥 3.5K / month):
	```
	npm install @aquirdturtle/collapsible_headings
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-commenting">JupyterLab Commenting</a></b> (🥉13 ·  ⭐ 82 · 💀) - JupyterLab的注释和注释。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-commenting) (👨‍💻 10 · 🔀 21 · 📋 34 - 70% open · ⏱️ 01.05.2020):

	```
	git clone https://github.com/jupyterlab/jupyterlab-commenting
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/commenting-extension) (📥 150 / month):
	```
	npm install @jupyterlab/commenting-extension
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-hdf5">JupyterLab HDF5</a></b> (🥉13 ·  ⭐ 76) - 在JupyterLab中打开和浏览HDF5文件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-hdf5) (👨‍💻 6 · 🔀 15 · 📋 42 - 28% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/jupyterlab/jupyterlab-hdf5
	```
- [PyPi](https://pypi.org/project/jupyterlab_hdf) (📥 480 / month):
	```
	pip install jupyterlab_hdf
	```
- [NPM](https://www.npmjs.com/package/@jupyterlab/hdf5) (📥 560 / month):
	```
	npm install @jupyterlab/hdf5
	```
</details>
<details><summary><b><a href="https://github.com/parente/jupyterlab-quickopen">JupyterLab Quickopen</a></b> (🥉13 ·  ⭐ 69) - 通过在JupyterLab中键入文件的一部分来快速打开文件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/parente/jupyterlab-quickopen) (👨‍💻 5 · 🔀 6 · ⏱️ 12.06.2021):

	```
	git clone https://github.com/parente/jupyterlab-quickopen
	```
- [PyPi](https://pypi.org/project/jupyterlab-quickopen) (📥 580 / month):
	```
	pip install jupyterlab-quickopen
	```
- [NPM](https://www.npmjs.com/package/@parente/jupyterlab-quickopen) (📥 360 / month):
	```
	npm install @parente/jupyterlab-quickopen
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/ipylab">ipylab</a></b> (🥉13 ·  ⭐ 65) - 使用Jupyter小部件从Python笔记本控制JupyterLab。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/ipylab) (👨‍💻 4 · 🔀 4 · 📋 24 - 45% open · ⏱️ 17.06.2021):

	```
	git clone https://github.com/jtpio/ipylab
	```
- [PyPi](https://pypi.org/project/ipylab) (📥 170 / month):
	```
	pip install ipylab
	```
- [Conda](https://anaconda.org/conda-forge/ipylab) (📥 6.1K · ⏱️ 12.01.2021):
	```
	conda install -c conda-forge ipylab
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/nbcelltests">nbcelltests</a></b> (🥉13 ·  ⭐ 60) - 用于Jupyter笔记本的逐个cell测试工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/nbcelltests) (👨‍💻 7 · 🔀 16 · 📋 110 - 26% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/jpmorganchase/nbcelltests
	```
- [PyPi](https://pypi.org/project/nbcelltests) (📥 94 / month):
	```
	pip install nbcelltests
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_celltests) (📥 88 / month):
	```
	npm install jupyterlab_celltests
	```
</details>
<details><summary><b><a href="https://github.com/itsjafer/jupyterlab-sparkmonitor">jupyterlab-sparkmonitor</a></b> (🥉13 ·  ⭐ 56) - JupyterLab扩展，可启动监控。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/itsjafer/jupyterlab-sparkmonitor) (👨‍💻 9 · 🔀 13 · 📋 11 - 36% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/itsjafer/jupyterlab-sparkmonitor
	```
- [PyPi](https://pypi.org/project/jupyterlab-sparkmonitor) (📥 360 / month):
	```
	pip install jupyterlab-sparkmonitor
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_sparkmonitor) (📥 200 / month):
	```
	npm install jupyterlab_sparkmonitor
	```
- [Docker Hub](https://hub.docker.com/r/itsjafer/sparkmonitor) (📥 190 · ⏱️ 02.06.2021):
	```
	docker pull itsjafer/sparkmonitor
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_autoversion">JupyterLab Autoversion</a></b> (🥉13 ·  ⭐ 54) - 在JupyterLab中Jupyter笔记本的自动版本控制。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_autoversion) (👨‍💻 4 · 🔀 5 · 📋 28 - 17% open · ⏱️ 27.06.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_autoversion
	```
- [PyPi](https://pypi.org/project/jupyterlab_autoversion) (📥 140 / month):
	```
	pip install jupyterlab_autoversion
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_autoversion) (📥 74 / month):
	```
	npm install jupyterlab_autoversion
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/jupyter-fs">jupyter-fs</a></b> (🥉12 ·  ⭐ 96) - 类似文件系统的内容管理器，用于Jupyter中的多个后端。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/jupyter-fs) (👨‍💻 8 · 🔀 21 · 📋 46 - 26% open · ⏱️ 04.06.2021):

	```
	git clone https://github.com/jpmorganchase/jupyter-fs
	```
- [PyPi](https://pypi.org/project/jupyter-fs) (📥 230 / month):
	```
	pip install jupyter-fs
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Email</a></b> (🥉11 ·  ⭐ 50 · 💤) - 一个jupyterlab扩展，可以直接从中发送电子邮件笔记本。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (🔀 2 · 📋 35 - 14% open · ⏱️ 31.01.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_email
	```
- [PyPi](https://pypi.org/project/jupyterlab_email) (📥 120 / month):
	```
	pip install jupyterlab_email
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_email) (📥 500 / month):
	```
	npm install jupyterlab_email
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Flake8</a></b> (🥉11 ·  ⭐ 50 · 💤) - 一个jupyterlab扩展，可以直接从中发送电子邮件笔记本。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (🔀 2 · 📋 35 - 14% open · ⏱️ 31.01.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_email
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-flake8) (📥 430 / month):
	```
	npm install jupyterlab-flake8
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/knowledgelab">KnowledgeLab</a></b> (🥉11 ·  ⭐ 42) - KnowledgeRepo + JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/knowledgelab) (👨‍💻 3 · 🔀 6 · 📦 2 · 📋 26 - 11% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/timkpaine/knowledgelab
	```
- [PyPi](https://pypi.org/project/knowledgelab) (📥 13 / month):
	```
	pip install knowledgelab
	```
- [NPM](https://www.npmjs.com/package/knowledgelab) (📥 22 / month):
	```
	npm install knowledgelab
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_commands">jupyterlab_commands</a></b> (🥉11 ·  ⭐ 36 · 💤) - Add arbitrary python commands to the jupyterlab.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_commands) (🔀 5 · 📦 3 · 📋 21 - 9% open · ⏱️ 31.01.2021):

	```
	git clone https://github.com/timkpaine/jupyterlab_commands
	```
</details>
<details><summary><b><a href="https://github.com/mlshapiro/jupyterlab-flake8">jupyterlab-flake8</a></b> (🥉10 ·  ⭐ 100 · 💀) - Jupyterlab用于笔记本和文本文件的python连接器。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/mlshapiro/jupyterlab-flake8) (👨‍💻 5 · 🔀 9 · 📋 36 - 16% open · ⏱️ 21.04.2020):

	```
	git clone https://github.com/mlshapiro/jupyterlab-flake8
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-flake8) (📥 430 / month):
	```
	npm install jupyterlab-flake8
	```
</details>
<details><summary><b><a href="https://github.com/ReviewNB/jupyterlab-gitplus">jupyterlab-gitplus</a></b> (🥉10 ·  ⭐ 82) - JupyterLab扩展来创建Python文件。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/ReviewNB/jupyterlab-gitplus) (👨‍💻 2 · 🔀 8 · 📋 10 - 20% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/ReviewNB/jupyterlab-gitplus
	```
- [PyPi](https://pypi.org/project/jupyterlab_gitplus) (📥 260 / month):
	```
	pip install jupyterlab_gitplus
	```
- [NPM](https://www.npmjs.com/package/@reviewnb/jupyterlab_gitplus) (📥 310 / month):
	```
	npm install @reviewnb/jupyterlab_gitplus
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-python-bytecode">JupyterLab Bytecode</a></b> (🥉10 ·  ⭐ 57 · 💤) - JupyterLab扩展，以探索CPython字节码。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-python-bytecode) (👨‍💻 2 · 🔀 5 · 📋 5 - 40% open · ⏱️ 16.10.2020):

	```
	git clone https://github.com/jtpio/jupyterlab-python-bytecode
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-python-bytecode) (📥 64 / month):
	```
	npm install jupyterlab-python-bytecode
	```
</details>
<details><summary><b><a href="https://github.com/gavincyi/jupyterlab-executor">jupyterlab-executor</a></b> (🥉10 ·  ⭐ 4) - JupyterLab扩展，以探索CPython字节码。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gavincyi/jupyterlab-executor) (👨‍💻 2 · 📥 2 · ⏱️ 24.03.2021):

	```
	git clone https://github.com/gavincyi/jupyterlab-executor
	```
- [PyPi](https://pypi.org/project/jupyterlab-executor) (📥 240 / month):
	```
	pip install jupyterlab-executor
	```
- [NPM](https://www.npmjs.com/package/@gavincyi/jupyterlab-executor) (📥 47 / month):
	```
	npm install @gavincyi/jupyterlab-executor
	```
</details>
<details><summary><b><a href="https://github.com/manuzhang/jupyterlab_spark">JupyterLab Spark</a></b> (🥉9 ·  ⭐ 7 · 💤) - JupyterLab的Spark应用程序UI扩展。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/manuzhang/jupyterlab_spark) (👨‍💻 2 · 🔀 2 · 📋 4 - 25% open · ⏱️ 11.09.2020):

	```
	git clone https://github.com/manuzhang/jupyterlab_spark
	```
- [NPM](https://www.npmjs.com/package/jupyterlab_spark) (📥 31 / month):
	```
	npm install jupyterlab_spark
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-topbar">JupyterLab Top Bar</a></b> (🥉8 · 🐣) - JupyterLab顶部栏扩展。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-topbar) (👨‍💻 3 · ⏱️ 31.05.2021):

	```
	git clone https://github.com/jtpio/jupyterlab-topbar
	```
- [NPM](https://www.npmjs.com/package/jupyterlab-topbar-extension) (📥 10K / month):
	```
	npm install jupyterlab-topbar-extension
	```
</details>
<br>

## JupyterHub认证

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_管理和控制用户如何访问JupyterHub部署的身份验证模块。_

<details><summary><b><a href="https://github.com/jupyterhub/oauthenticator">OAuthenticator</a></b> (🥇24 ·  ⭐ 310) - OAuth + JupyterHub Authenticator = OAuthenticator. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/oauthenticator) (👨‍💻 100 · 🔀 280 · 📦 220 · 📋 200 - 10% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/jupyterhub/oauthenticator
	```
- [PyPi](https://pypi.org/project/oauthenticator) (📥 42K / month):
	```
	pip install oauthenticator
	```
- [Conda](https://anaconda.org/conda-forge/oauthenticator) (📥 16K · ⏱️ 19.07.2021):
	```
	conda install -c conda-forge oauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/ldapauthenticator">LDAP Authenticator</a></b> (🥇23 ·  ⭐ 150) - 用于Jupyter的LDAP Authenticator插件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ldapauthenticator) (👨‍💻 30 · 🔀 140 · 📦 75 · 📋 130 - 39% open · ⏱️ 27.06.2021):

	```
	git clone https://github.com/jupyterhub/ldapauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-ldapauthenticator) (📥 7.6K / month):
	```
	pip install jupyterhub-ldapauthenticator
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-ldapauthenticator) (📥 21K · ⏱️ 28.08.2020):
	```
	conda install -c conda-forge jupyterhub-ldapauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/ltiauthenticator">LTI Authenticator</a></b> (🥈16 ·  ⭐ 47) - 用于LTI的JupyterHub身份验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ltiauthenticator) (👨‍💻 10 · 🔀 34 · 📦 61 · 📋 28 - 28% open · ⏱️ 12.08.2021):

	```
	git clone https://github.com/jupyterhub/ltiauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-ltiauthenticator) (📥 3.1K / month):
	```
	pip install jupyterhub-ltiauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nativeauthenticator">Native Authenticator</a></b> (🥈16 ·  ⭐ 42) - JupyterHub本地用户身份验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nativeauthenticator) (👨‍💻 16 · 🔀 44 · 📦 28 · 📋 63 - 26% open · ⏱️ 10.05.2021):

	```
	git clone https://github.com/jupyterhub/nativeauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-nativeauthenticator) (📥 5K / month):
	```
	pip install jupyterhub-nativeauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/firstuseauthenticator">First Use Authenticator</a></b> (🥈16 ·  ⭐ 35 · 💤) - JupyterHub Authenticator，可以让用户进行设置。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/firstuseauthenticator) (👨‍💻 11 · 🔀 19 · 📦 49 · 📋 18 - 22% open · ⏱️ 28.10.2020):

	```
	git clone https://github.com/jupyterhub/firstuseauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-firstuseauthenticator) (📥 4.8K / month):
	```
	pip install jupyterhub-firstuseauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/dummyauthenticator">dummyauthenticator</a></b> (🥈14 ·  ⭐ 27) - 虚拟的JupyterHub Authenticator使测试变得容易。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/dummyauthenticator) (🔀 14 · 📦 85 · 📋 7 - 71% open · ⏱️ 12.02.2021):

	```
	git clone https://github.com/jupyterhub/dummyauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-dummyauthenticator) (📥 3.7K / month):
	```
	pip install jupyterhub-dummyauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/mogthesprog/jwtauthenticator">JWT Authenticator</a></b> (🥉13 ·  ⭐ 35 · 💀) - JupyterHub的令牌验证器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mogthesprog/jwtauthenticator) (👨‍💻 7 · 🔀 33 · 📦 7 · 📋 16 - 50% open · ⏱️ 13.02.2019):

	```
	git clone https://github.com/mogthesprog/jwtauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-jwtauthenticator) (📥 230 / month):
	```
	pip install jupyterhub-jwtauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nullauthenticator">Null Authenticator</a></b> (🥉13 ·  ⭐ 6) - Null Authenticator for JupyterHub instances that should have.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nullauthenticator) (👨‍💻 5 · 🔀 8 · 📦 63 · ⏱️ 09.02.2021):

	```
	git clone https://github.com/jupyterhub/nullauthenticator
	```
- [PyPi](https://pypi.org/project/nullauthenticator) (📥 3.1K / month):
	```
	pip install nullauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/HewlettPackard/jupyterhub-samlauthenticator">SAML Authenticator</a></b> (🥉12 ·  ⭐ 29 · 💀) - jupyterhub-samlauthenticator。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HewlettPackard/jupyterhub-samlauthenticator) (👨‍💻 6 · 🔀 16 · 📥 13 · 📋 26 - 46% open · ⏱️ 13.07.2020):

	```
	git clone https://github.com/HewlettPackard/jupyterhub-samlauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-samlauthenticator) (📥 390 / month):
	```
	pip install jupyterhub-samlauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/cwaldbieser/jhub_remote_user_authenticator">Remote User Auth</a></b> (🥉11 ·  ⭐ 28 · 💀) - Jupyterhub的REMOTE_USER身份验证器。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/cwaldbieser/jhub_remote_user_authenticator) (👨‍💻 5 · 🔀 27 · 📋 16 - 43% open · ⏱️ 16.04.2019):

	```
	git clone https://github.com/cwaldbieser/jhub_remote_user_authenticator
	```
- [PyPi](https://pypi.org/project/jhub_remote_user_authenticator) (📥 350 / month):
	```
	pip install jhub_remote_user_authenticator
	```
</details>
<details><summary><b><a href="https://github.com/ucphhpc/jhub-authenticators">Remote Authenticator</a></b> (🥉11 ·  ⭐ 1) - JupyterHub Authenticators的集合。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ucphhpc/jhub-authenticators) (👨‍💻 5 · 🔀 1 · ⏱️ 02.06.2021):

	```
	git clone https://github.com/rasmunk/jhub-authenticators
	```
- [PyPi](https://pypi.org/project/jhub-authenticators) (📥 330 / month):
	```
	pip install jhub-authenticators
	```
</details>
<details><summary><b><a href="https://github.com/cwaldbieser/jhub_cas_authenticator">CAS Authenticator</a></b> (🥉9 ·  ⭐ 16 · 💀) - Jupyterhub的CAS验证器。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/cwaldbieser/jhub_cas_authenticator) (👨‍💻 4 · 🔀 10 · 📋 11 - 9% open · ⏱️ 27.03.2020):

	```
	git clone https://github.com/cwaldbieser/jhub_cas_authenticator
	```
- [PyPi](https://pypi.org/project/jhub_cas_authenticator) (📥 200 / month):
	```
	pip install jhub_cas_authenticator
	```
</details>
<details><summary><b><a href="https://github.com/thedataincubator/jupyterhub-hashauthenticator">Hash Authenticator</a></b> (🥉9 ·  ⭐ 3) - 使用从其生成的密码对用户进行身份验证。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/thedataincubator/jupyterhub-hashauthenticator) (👨‍💻 3 · 🔀 3 · ⏱️ 09.03.2021):

	```
	git clone https://github.com/thedataincubator/jupyterhub-hashauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-hashauthenticator) (📥 75 / month):
	```
	pip install jupyterhub-hashauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/kerberosauthenticator">Keberos Authenticator</a></b> (🥉8 ·  ⭐ 9 · 💀) - 用于LTI的JupyterHub身份验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/kerberosauthenticator) (👨‍💻 2 · 🔀 4 · 📋 5 - 60% open · ⏱️ 16.07.2019):

	```
	git clone https://github.com/jupyterhub/kerberosauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-kerberosauthenticator) (📥 64 / month):
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

<details><summary><b><a href="https://github.com/jupyterhub/kubespawner">KubeSpawner</a></b> (🥇22 ·  ⭐ 370) - Kubernetes spawner for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/kubespawner) (👨‍💻 64 · 🔀 220 · 📦 91 · 📋 250 - 17% open · ⏱️ 21.07.2021):

	```
	git clone https://github.com/jupyterhub/kubespawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-kubespawner) (📥 15K / month):
	```
	pip install jupyterhub-kubespawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/dockerspawner">DockerSpawner</a></b> (🥈20 ·  ⭐ 390 · 📉) - 在Docker容器中生成JupyterHub单用户服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/dockerspawner) (👨‍💻 62 · 🔀 260 · 📦 98 · 📋 240 - 6% open · ⏱️ 22.07.2021):

	```
	git clone https://github.com/jupyterhub/dockerspawner
	```
- [PyPi](https://pypi.org/project/dockerspawner) (📥 6.8K / month):
	```
	pip install dockerspawner
	```
- [Conda](https://anaconda.org/conda-forge/dockerspawner) (📥 8.5K · ⏱️ 26.04.2019):
	```
	conda install -c conda-forge dockerspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/batchspawner">BatchSpawner</a></b> (🥈20 ·  ⭐ 120) - 用于Jupyterhub的自定义Spawner，可按计划批量启动服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/batchspawner) (👨‍💻 38 · 🔀 89 · 📦 10 · 📋 110 - 37% open · ⏱️ 05.05.2021):

	```
	git clone https://github.com/jupyterhub/batchspawner
	```
- [PyPi](https://pypi.org/project/batchspawner) (📥 530 / month):
	```
	pip install batchspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/systemdspawner">SystemdSpawner</a></b> (🥉16 ·  ⭐ 69) - 使用Systemd生成JupyterHub单用户笔记本服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/systemdspawner) (👨‍💻 16 · 🔀 36 · 📦 16 · 📋 48 - 47% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/jupyterhub/systemdspawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-systemdspawner) (📥 1.5K / month):
	```
	pip install jupyterhub-systemdspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/sudospawner">SudoSpawner</a></b> (🥉16 ·  ⭐ 37) - 使用Systemd生成JupyterHub单用户笔记本服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/sudospawner) (👨‍💻 14 · 🔀 32 · 📦 33 · 📋 34 - 44% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/jupyterhub/sudospawner
	```
- [PyPi](https://pypi.org/project/sudospawner) (📥 1.1K / month):
	```
	pip install sudospawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/wrapspawner">WrapSpawner</a></b> (🥉14 ·  ⭐ 44) - JupyterHub的生成器的运行时配置机制。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/wrapspawner) (👨‍💻 16 · 🔀 41 · 📦 4 · 📋 28 - 53% open · ⏱️ 07.07.2021):

	```
	git clone https://github.com/jupyterhub/wrapspawner
	```
</details>
<details><summary><b><a href="https://github.com/uktrade/fargatespawner">FargateSpawner</a></b> (🥉11 ·  ⭐ 27 · 💀) - 在Docker容器中生成JupyterHub单用户服务器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/uktrade/fargatespawner) (👨‍💻 3 · 🔀 18 · 📦 1 · 📋 9 - 55% open · ⏱️ 28.06.2020):

	```
	git clone https://github.com/uktrade/fargatespawner
	```
- [PyPi](https://pypi.org/project/fargatespawner) (📥 260 / month):
	```
	pip install fargatespawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/yarnspawner">YarnSpawner</a></b> (🥉10 ·  ⭐ 18 · 💀) - 在Hadoop/YARN中生成JupyterHub单用户笔记本服务器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/yarnspawner) (👨‍💻 2 · 🔀 8 · 📋 9 - 55% open · ⏱️ 16.07.2019):

	```
	git clone https://github.com/jupyterhub/yarnspawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-yarnspawner) (📥 93 / month):
	```
	pip install jupyterhub-yarnspawner
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-yarnspawner) (📥 22K · ⏱️ 08.10.2020):
	```
	conda install -c conda-forge jupyterhub-yarnspawner
	```
</details>
<br>

## Jupyter组件

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Jupyter架构的核心组件。_

<details><summary><b><a href="https://github.com/ipython/ipython">ipython</a></b> (🥇36 ·  ⭐ 15K) - Official repository for IPython itself. Other repos in the.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/ipython/ipython) (👨‍💻 820 · 🔀 4K · 📥 320K · 📦 210K · 📋 6.7K - 21% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/ipython/ipython
	```
- [PyPi](https://pypi.org/project/ipython) (📥 20M / month):
	```
	pip install ipython
	```
- [Conda](https://anaconda.org/conda-forge/ipython) (📥 7.4M · ⏱️ 02.08.2021):
	```
	conda install -c conda-forge ipython
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter_server">jupyter_server</a></b> (🥉24 ·  ⭐ 250) - The backendi.e. core services, APIs, and REST.. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter_server) (👨‍💻 440 · 🔀 120 · 📥 99 · 📋 200 - 31% open · ⏱️ 11.08.2021):

	```
	git clone https://github.com/jupyter-server/jupyter_server
	```
- [PyPi](https://pypi.org/project/jupyter_server) (📥 870K / month):
	```
	pip install jupyter_server
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_server) (📥 650K · ⏱️ 03.08.2021):
	```
	conda install -c conda-forge jupyter_server
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-packaging">jupyter-packaging</a></b> (🥉20 ·  ⭐ 33) - 帮助构建和安装Jupyter Python软件包的工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-packaging) (👨‍💻 18 · 🔀 33 · 📋 25 - 28% open · ⏱️ 30.07.2021):

	```
	git clone https://github.com/jupyter/jupyter-packaging
	```
- [PyPi](https://pypi.org/project/jupyter-packaging) (📥 250K / month):
	```
	pip install jupyter-packaging
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-packaging) (📥 170K · ⏱️ 06.07.2021):
	```
	conda install -c conda-forge jupyter-packaging
	```
</details>
<br>

## Others

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jupyter/qtconsole">qtconsole</a></b> (🥇32 ·  ⭐ 270) - Jupyter Qt Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/qtconsole) (👨‍💻 110 · 🔀 160 · 📦 82K · 📋 280 - 32% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/jupyter/qtconsole
	```
- [PyPi](https://pypi.org/project/qtconsole) (📥 6.7M / month):
	```
	pip install qtconsole
	```
- [Conda](https://anaconda.org/conda-forge/qtconsole) (📥 2M · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge qtconsole
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/panel">panel</a></b> (🥈30 ·  ⭐ 1.3K) - 适用于Python的高级应用程序和仪表板解决方案。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/panel) (👨‍💻 72 · 🔀 190 · 📦 1.9K · 📋 1.3K - 27% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/holoviz/panel
	```
- [PyPi](https://pypi.org/project/panel) (📥 160K / month):
	```
	pip install panel
	```
- [Conda](https://anaconda.org/conda-forge/panel) (📥 270K · ⏱️ 20.07.2021):
	```
	conda install -c conda-forge panel
	```
</details>
<details><summary><b><a href="https://github.com/abhishekkrthakur/colabcode">colabcode</a></b> (🥉20 ·  ⭐ 1.5K) - 在Google Colab或Kaggle笔记本上运行VSCode（代码服务器）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/abhishekkrthakur/colabcode) (👨‍💻 8 · 🔀 200 · 📦 34 · 📋 50 - 54% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/abhishekkrthakur/colabcode
	```
- [PyPi](https://pypi.org/project/colabcode) (📥 29K / month):
	```
	pip install colabcode
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter_console">jupyter-console</a></b> (🥉19 ·  ⭐ 180) - Jupyter终端控制台。<code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/jupyter/jupyter_console) (👨‍💻 54 · 🔀 120 · 📋 130 - 39% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/jupyter/jupyter_console
	```
- [PyPi](https://pypi.org/project/jupyter-console) (📥 6.8M / month):
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