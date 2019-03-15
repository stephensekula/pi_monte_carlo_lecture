[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/stephensekula/pi_monte_carlo_lecture/master?filepath=pi_lecture.ipynb)

# Running

* Click the badge above to launch this notebook on Binder, or...
* See the instructions below for running in your own python environment on your own Jupyter instance


## Instructions on Running this Slide Deck in a Local/Personal Jupyter Instance

I recommend the Anaconda-based approach:
 
* [Install Anaconda (Python 3.X) from the Continuum.io Website](https://www.anaconda.com/distribution/)
* Enable your Anaconda environment
* Install some other packages:
   * Jupyter: ```conda install jupyter```
   * [Notebook extensions](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html): ```conda install -c conda-forge jupyter_contrib_nbextensions```
   * [RISE](https://damianavila.github.io/RISE/index.html): ```conda install -c damianavila82 rise```
* Launch the slides:
   * ```jupyter-notebook <SLIDES.ipynb>```
   * Set the notebook to be "Trusted" by your server/browser (button in the upper-right portion of user interface)
   * Use \"Alt-r\" to go to slideshow mode and Spacebar (SHIFT+Spacebar) to go forward (backward) through the slideshow. [More info is available in the RISE documentation](https://damianavila.github.io/RISE/usage.html).
   
