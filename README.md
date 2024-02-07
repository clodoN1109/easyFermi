<p align="left" width="100%">
 <img width="100%" height="250" src="https://github.com/clodoN1109/easyFermi/assets/104923248/d1a25a66-0fc6-4484-93fa-aaa8717f4276">
 <h1>easyfermi</h1>
</p> 

The easiest way to analyze Fermi-LAT data.

<div align="center">

![easyfermi-demo-rect-ezgif com-video-to-gif-converter](https://github.com/ranieremenezes/easyFermi/assets/104923248/6657b52f-9538-40ff-86c0-5b742dd6f2b0)

</div>

easyfermi is a solution to facilitate Fermi-LAT data analysis by providing an intuitive graphical interface to interact with the Fermi science tools.



# Compatibilities

- Linux OS / Mac OS / Windows with <a href="https://learn.microsoft.com/en-us/windows/wsl/install">WSL (Windows Subsystem for Linux)</a>

# Installing

Let's start by using <a href="https://github.com/conda-forge/miniforge">mamba</a> to install fermipy and the fermitools.

You can also use conda, although it will take longer to solve the requested environment.

In the terminal, run:

- Creating the virtual environment and installing dependencies:
<pre><code>mamba create --name easyfermi -c conda-forge -c fermi python=3.9 "fermitools>=2.2.0" "healpy=1.16.1" "gammapy=1.1" "fermipy=v1.2" "scipy=1.11.4" "astropy=5.3.3" "pyqt=5.15.9" "astroquery=0.4.6" "psutil=5.9.8" "matplotlib=3.8.2" "emcee=3.1.4" "corner=2.2.2"</code></pre>

- Activating the environment and installing easyfermi:
<pre><code>mamba activate easyfermi</code></pre>
<pre><code>pip install easyfermi</code></pre>


- (ONLY FOR WINDOWS) Installing libgl1 package:
<pre><code>sudo apt-get install libgl1</code></pre>

# Upgrading

To upgrade your easyfermi installation to the latest version, run the following command in the easyfermi environment:

<pre><code>pip install easyfermi --upgrade --no-deps</code></pre>

You can check your currently installed version of easyfermi with _pip show_:

<pre><code>pip show easyfermi</code></pre>


# Uninstalling

In the terminal, run:
<pre><code>mamba deactivate</code></pre>
<pre><code>mamba env remove --name easyfermi</code></pre>

# Running

In the terminal, run:

<pre><code>mamba activate easyfermi</code></pre>
<pre><code>python -c "import easyfermi"</code></pre>

<p align="center" width="100%">
 <img width="100%" height="100%" src="/code/resources/images/easyFermiWindow.png">
</p> 

# Tutorials

Check for tutorials on the easyfermi YouTube channel:

 <a href="https://www.youtube.com/channel/UCeLCfEoWasUKky6CPNN_opQ">

  ![youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)

 </a> 

- Learn how to analyze Fermi-LAT data in 10 min
  
 [![Watch the video](https://img.youtube.com/vi/Ny7aA9EBRUs/hqdefault.jpg)](https://youtu.be/Ny7aA9EBRUs)
- Goodness of fit and advanced configurations
  
 [![Watch the video](https://img.youtube.com/vi/OPMOsheCId8/hqdefault.jpg)](https://youtu.be/OPMOsheCId8)


# Acknowledgements

To acknowledge _easyfermi_ in a publication, please cite  [de Menezes, R (2022)](https://ui.adsabs.harvard.edu/abs/2022arXiv220611272D/abstract).

Since _easyfermi_ relies on _fermipy_, _gammapy_, _astropy_, and _emcee_, please also cite [Wood et al. 2017](https://ui.adsabs.harvard.edu/abs/2017ICRC...35..824W/abstract), [Donath et al. 2023](https://ui.adsabs.harvard.edu/abs/2023A%26A...678A.157D/abstract), [Astropy Collaboration et al. 2018](https://ui.adsabs.harvard.edu/abs/2018AJ....156..123A/abstract), and [Foreman-Mackey et al. 2013](https://ui.adsabs.harvard.edu/abs/2013PASP..125..306F/abstract) 


I want to thank Clodomir Vianna for helping me design easyfermi, for making the easyfermi logo, and for the several hours of discussion about this project. Clodomir is the one responsible for making easyfermi user-friendly. Thanks to Fabio Cafardo, Lucas Costa Campos, and Raí Menezes for their help and strong support in this project. A big thanks to Alessandra Azzollini, Douglas Carlos, Kaori Nakashima, Lucas Siconato, Matt Pui, and Romana Grossova, the first users/testers of easyfermi.

 <br>
<p align="center" width="100%">
 <img height="200" src="https://github.com/clodoN1109/easyFermi/assets/104923248/a5fd6166-4dce-475b-92e6-78cbcbcd36af">
</p> 
