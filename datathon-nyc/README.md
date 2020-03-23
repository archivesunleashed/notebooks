# Archives Unleashed NYC Datathon

Welcome to the Archives Unleashed NY Datathon! Below you will find a variety of resources that will be useful throughout our event.

* [Requirements](#requirements)
* [Schedule](#schedule)
* [Team Collaboration Resources](#team-collaboration-resources)
* [Homework Refresher](#homework-refresher)
* [Additional/External Tools for Analysis](#additionalexternal-tools-for-analysis)
* [Analysis Platforms](#analysis-platforms)
* [Inspiration](#inspiration)
* [Virtual Machines](#virtual-machines)
* [Getting Started](#getting-started)
  * [Shell into assigned VM](#shell-into-assigned-vm)
  * [Start Juypter Notebook](#start-juypter-notebook)
  * [Start Spark with AUT](#start-spark-with-aut)
* [Datasets](#datasets)

## Requirements

- **Zoom** (login information will be provided via Slack/email).
- **Slack** (datathon-ny-2020): our team will use Slack to communicate with participants. You can also use this platform to create a team channel (free) to collaborate (text + calls) during the datathon.
- **Wifi + Space**: since we are all working remotely, find yourself a comfortable working space with a reliable internet connection.

## Schedule

The datathon will be held March 26-27th (EST) online via (Zoom). 

The event will start off with introductions and a look at the tools you’ll be using. After a team formation activity, the majority of our time will be dedicated for group work. We will also be doing a few check-ins via Zoom to make sure everyone is doing fine. Final presentations will happen on Friday.

![](../assets/ny-schedule.png)

Unfortunately, because we can’t meet in person we won’t be holding a dinner/social, but feel free to use our hashtag **#hackarchives** in your social media posts. 

## Team Collaboration Resources
  
- **[Team Final Projects Folder](https://drive.google.com/drive/u/1/folders/138xKFQwHrjJEnruZ21lkK5UAxFPU2GLz)**: we have set up a folder where you can directly import/work on your presentations. We ask that you use Google Slides to help us with quick transitions between groups. 
- **Folder on your desktop**: we recommend setting up a dedicated folder on your desktop - it will come in handy when you are using terminal and need to point to a directory (folder). It’s also nice to be able to keep all your work in the same place.
- **Text editor**: Any text editor will do. If you don't have one installed we recommend trying  [Sublime Text](https://www.sublimetext.com) (Mac Users) or [Notepad++](https://notepad-plus-plus.org) (Windows users).
- **Project Examples**: Need a bit more inspiration before starting? Checkout projects from previous datathons: [Toronto](https://archivesunleashed.org/toronto/) |  [Vancouver](https://archivesunleashed.org/vancouver/) | [Washington](https://archivesunleashed.org/washington/)


## Homework Refresher

-  **[Command Line/Terminal Tutorial](https://programminghistorian.org/en/lessons/intro-to-bash)**: For those new to command line, or if you'd like a refresher, check out this tutorial on the Programing Historian Introduction to the Bash Command Line by Ian Milligan and James Baker.
-  **[Archives Unleashed Toolkit Walkthrough](https://github.com/archivesunleashed/aut-docs/blob/master/current/toolkit-walkthrough.md)**: While we’ll be doing a lot of work in the notebooks during the datathon, it is good to have a conceptual understanding around working with data.
-  **Archives Unleashed Notebooks Reading**: Nick Ruest has been working on some new methods of working with derivatives created through the Archives Unleashed Cloud. To learn more about this development, check out our latest Medium post: [Cloud-hosted web archive data: The winding path to web archive collections as data](https://news.archivesunleashed.org/cloud-hosted-web-archive-data-the-winding-path-to-web-archive-collections-as-data-a2b3428701b7).
- **[Notebooks Repository Walkthrough]()**: we suggest that you run through the two created for this event to become familiar with how the environment works and the types of analysis you can run. In each link click the “Open in Colab” button at the top of the page to launch and start exploring.
	-  [parquet_pandas_stonewall.ipynb](https://github.com/archivesunleashed/notebooks/blob/master/parquet_pandas_stonewall.ipynb)
	-  [parquet_text_analyis_popline.ipynb](https://github.com/archivesunleashed/notebooks/blob/master/parquet_text_analyis_popline.ipynb)

## Additional/External Tools for Analysis

- [AUK Tutorials](https://cloud.archivesunleashed.org/derivatives): provide basics on using a variety of external tools to work with dataset derivatives.
  - [An Introduction to Gephi (Beginner)](https://cloud.archivesunleashed.org/derivatives/basic-gephi)
  - [Network Graphing Archived Websites With Gephi (Intermediate)](https://cloud.archivesunleashed.org/derivatives/gephi)
  - [Grep - Filtering the Full-Text Derivative File](https://cloud.archivesunleashed.org/derivatives/text-filtering)
  - [Text Analysis Part One: Beyond the Keyword Search: Using AntConc](https://cloud.archivesunleashed.org/derivatives/text-antconc)
  - [Text Analysis Part Two: Sentiment Analysis With the Natural Language Toolkit](https://cloud.archivesunleashed.org/derivatives/text-sentiment)
- [Voyant](https://voyant-tools.org)

Also don’t forget about Excel (or Google spreadsheets)!

## Analysis Platforms

We have a couple options for analysis platforms ([datasets are listed below](datathon-nyc#datasets)):

- If you'd like to keep things relatively easy, and browser based, you're welcome to use [Google Colaboratory](https://colab.research.google.com). We have a couple options, in addition to the two mentioned above, available in the repo ([parquet_pandas_example.ipynb](https://github.com/archivesunleashed/notebooks/blob/master/parquet_pandas_example.ipynb), [parquet_pyspark_example.ipynb](https://github.com/archivesunleashed/notebooks/blob/master/parquet_pyspark_example.ipynb), and [parquet_text_analyis.ipynb](https://github.com/archivesunleashed/notebooks/blob/master/parquet_text_analyis.ipynb)) that can be used as starting points.
- If you're comfortable with the command line, you're welcome to use one of the virtual machines provided by [Compute Canada](https://www.computecanada.ca/home/). 

The virtual machines, and the machine backing a given Google Colab notebook are roughly similar resource-wise. If you'd like to use a Compute Canada virtual machine, you'll have a bit more storage space, and you'll have much more control. You're welcome to install what you need to on the machines with `apt` to complete your project.

## Inspiration

If you're looking for inspiration, check out the following notebook resources:

- [GLAM Workbench](https://glam-workbench.github.io/)
- [Awesome Jupyter GLAM](https://github.com/LibraryCarpentry/awesome-jupyter-glam)
- [Getting started with ODate](https://o-date.github.io/support/notebooks-toc/)
- [Jupyter notebooks for digital humanities](https://github.com/quinnanya/dh-jupyter)
- [Spark NLP Workshop](https://github.com/JohnSnowLabs/spark-nlp-workshop)
- [UW Interactive Data Lab, Data Visualization Curriculum](https://github.com/uwdata/visualization-curriculum)
- [Sentiment Analysis with Pyspark](https://github.com/tthustla/setiment_analysis_pyspark/blob/master/Sentiment%20Analysis%20with%20PySpark.ipynb)
- [Analysis of Car Accidents in Canada using PySpark](https://github.com/SinghGursimran/Analysis-of-Car-Accidents-in-Canada-using-PySpark/)
- [Save Page Now Analysis](https://github.com/edsu/spn)

If you'd like to add your notebook to the repo at the end of the datathon, we'd love to have it!

## Virtual Machines

**c8-30gb-430gb**

- 8 cores
- 30G RAM
- 11G `/`
- 398G `/mnt`
- Python 3.7.3 ([Anaconda](https://www.anaconda.com/distribution/))
  -  findspark, wordcloud, spacy, pyarrow, jupyter, tldextract, jupyter_contrib_nbextensions, pyspark
  -  feel free to `conda install` or `pip install` whatever else you need
- OpenJDK 8
- Spark 2.4.5
  - `SPARK_HOME=/home/ubuntu/spark`
- jq

Four machines available:

- 206.167.181.146 (datathon1)
- 206.167.182.14 (datathon2)
- 206.167.181.104 (datathon3)
- 206.167.181.105 (datathon4)

**c8-45gb-430gb**

- 8 Cores
- 45G RAM
- 11G `/`
- 398G `/mnt`
- Python 3.7.3 ([Anaconda](https://www.anaconda.com/distribution/))
  - findspark, wordcloud, spacy, pyarrow, jupyter, tldextract, jupyter_contrib_nbextensions, pyspark
  - feel free to `conda install` or `pip install` whatever else you need
- OpenJDK 8
- Spark 2.4.5
  - `SPARK_HOME=/home/ubuntu/spark`
- jq

One machine available:

- 206.167.181.253 (datathon5)

## Getting Started

Please note, the datathon hosts (Ian, Jimmy, Nick, and Sam) all use macOS or Linux   variants. If you are on a Windows machine, things might be a little bit more difficult. If you have the [Windows SubSystem for Linux](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/) installed, you should be in a really good place.

You may want to create a separate folder on your desktop or home directory to keep all of your datathon work in; this will also allow you to point terminal to one directory (folder).

### Shell into assigned VM

Ian or Nick will provide you with key to access a virtual machine via ssh. You'll need to download or copy that key to your own machine, and apply the appropriate permissions to it. The permissions on the key should be `600`. You can do this with the following command on your own laptop before shelling in:

```bash
chmod 600 /path/to/archives-hackathon.key
```

Once you have the permissions set on the key, you can shell into your assigned datathon virtual machine with the provided key, and IP address:

Example:

```bash
ssh -L 8888:localhost:8888 -i ~/.ssh/archives-hackathon.key ubuntu@206.167.181.253
```

### Start Juypter Notebook

```bash
cd /mnt/notebooks/datathon-nyc
jupyter notebook --no-browser
```

Click on the the localhost link to open up Juypter.

![](../assets/jupyter-shell.png)

Select one of the two example notebooks.

![](../assets/juypter.png)


### Start Spark with AUT

If you'd like to use Apache Spark and the Archives Unleashed Toolkit to analyze WARC/ARCs, you can get Spark started with the toolkit with the following command:

```bash
~/spark/bin/spark-shell --packages "io.archivesunleashed:aut:0.50.0"
```

Documentation for the 0.50.0 release is available [here](https://github.com/archivesunleashed/aut-docs/tree/master/aut-0.50.0), and if you need a refresher on the datathon homework, it is available [here](https://github.com/archivesunleashed/aut-docs/blob/master/aut-0.50.0/toolkit-walkthrough.md).

## Datasets

Scholarly derivatives created on cloud.archivesunleashed.org, and Parquet files should be downloaded to `/mnt/data`. If any team would like some WARC/ARC files from a collection, please work with Nick Ruest as soon as possible (`ruebot` in Slack).

**Ivy Plus Libraries Confederation**

- [National Statistical Offices and Central Banks Web Archive](https://zenodo.org/record/3633683)
- [Contemporary Composers Web Archive (CCWA)](https://zenodo.org/record/3692559)
- [#MeToo and the Women's Rights Movement in China Web Archive](https://zenodo.org/record/3633681)
- [Geologic Field Trip Guidebooks Web Archive](https://zenodo.org/record/3666295)
- [Literary Authors from Europe and Eurasia Web Archive](https://zenodo.org/record/3632728)
- [Web Archive of Independent News Sites on Turkish Affairs](https://zenodo.org/record/3633234)
- [State Elections Web Archive](https://zenodo.org/record/3635634)
- [Brazilian Presidential Transition (2018) Web Archive](https://zenodo.org/record/3659692)
- [Collaborative Architecture, Urbanism, and Sustainability Web Archive (CAUSEWAY)](https://zenodo.org/record/3674173)
- [Global Webcomics Web Archive](https://zenodo.org/record/3633737)
- [Queer Japan Web Archive](https://zenodo.org/record/3633284)
- [Extreme Right Movements in Europe](https://zenodo.org/record/3633161)
- [Latin American and Caribbean Contemporary Art Web Archive](https://zenodo.org/record/3633118)
- [Popline and K4Health Web Archive](https://zenodo.org/record/3633022)
- [Eastern Europe and Former Soviet Union Web Archive](https://zenodo.org/record/3633031)
- [Independent Documentary Filmmakers from China, Hong Kong, and Taiwan Web Archive](https://zenodo.org/record/3632912)

**Columbia University Libraries**

- [General](https://zenodo.org/record/3633290)
- [Resistance](https://zenodo.org/record/3660457)
- [Stonewall 50 Commemoration](https://zenodo.org/record/3631347)
- [Freely Accessible eJournals](https://zenodo.org/record/3633671)
- [Avery Library Historic Preservation and Urban Planning](https://doi.org/10.5683/SP2/Z68EVJ)
- [Rare Book and Manuscript Library](https://zenodo.org/record/3701593)
- [Burke Library New York City Religions](https://zenodo.org/record/3701455)

## Sponsors + Special Thanks

This event is possible thanks to the generous support from: 

[Andrew W. Mellon Foundation](https://mellon.org/), [Columbia University Libraries](https://library.columbia.edu), [Ivy Plus Libraries Confederation](https://library.columbia.edu/collections/web-archives/Ivy_Plus_Libraries.html), [Faculty of Arts](https://uwaterloo.ca/arts/) and [David R. Cheriton School of Computer Science](https://cs.uwaterloo.ca/) at the [University of Waterloo](https://uwaterloo.ca/), [York University Libraries](https://www.library.yorku.ca/web/), [Compute Canada](https://www.computecanada.ca/), and [Start Smart Labs](http://www.startsmartlabs.com/).

We'd also like to say a special thanks to Columbia University and Ivy Plus libraries Confederation for for providing access to their collections!
