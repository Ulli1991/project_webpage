---
youtubeId: YFey9a4ZSmI
youtubeId2: cPTjyYlVmD4
---

## Welcome to the Webpage of Dr. Ulrich Philipp Steinwandel!

My Name is Ulrich but I go by Ulli. I am Flatiron Research Fellow at the Center for Computational Astrophysics (CCA) in New York. At CCA I am involved in the CAMELS and SMAUG collaboration. If you are interested to talk to me about my research or collaborating with me, please feel free to contact me at usteinwandel@flatironinstitute.org 

## About me

I am a theoretical astropysicist and I successfully defended my PhD-thesis in October 2020 at the Ludwigs-Maximilian University in Munich, working with Dr. Benjamin P. Moster, Dr. Thorsten Naab and Dr. Klaus Dolag. Currently, I am a Flatiron Research Fellow (FRF) at the Center for Computational Astropysics (CCA) at the Flatiron Institute in New York. I work closely with Dr. Rachel Somerville, Dr. Greg Bryan and Dr. Christopher C. Hayward on numerical simulations ranging from galaxy-clusters and the Intracluster medium (ICM) over Milky Way-like disc galaxies down to resolved star-by-star dwarf galaxy models that can sucessfully resolve the ISM on sub-parsec scales. Hereby, I put a special focus on understanding the origin and emergence of the magnetic field structure in the ICM, the intergalactic medium (IGM) and the ISM. Additionally, to my expertise on magnetic fields on all scale in the Unviverse, I carry out work on simulations with a direct dust component in close collaboration with Dr. Philip Hopkins at Caltech, extending my range down to the smallest scales in the ISM that boarder planet formation. 

{% include lib/mathjax.html %}
## Short CV
Apr. 2021 - Apr. 2024: Flatiron Research Fellow (FRF Prize Fellowship), Center for Computational Astrophysics (CCA), New York, USA <br/>
Feb. 2017 - Oct. 2020: PhD in theoretical and numerical astrophysics (summa cum laude), LMU Munich/MPA Garching, Germany <br/>
Jun. 2018 - Sep. 2018: Fellow in the Kavli Summer Program in Astrophysics at CCA, New York, USA <br/>
Oct. 2014 - Jan. 2017: M.Sc. in Physics (GPA 4.0), University of Konstanz, Konstanz, Germany <br/>
Oct. 2011 - Sep. 2014: B.Sc. in Physics (GPA 3.3), University of Konstanz, Konstanz, Germany <br/>
Sep. 2001 - Jun. 2010: Highschool Diploma (Abitur), Gymnasium Ueberlingen, Ueberlingen, Germany  

You can download my full CV here!

## Research (peer reviewed and submitted)

### Magnetic field amplifcation in Milky Way-like galaxies I: The small-scale-turbulent dynamo

Magnetic field amplification galaxies is a highly complicated topic. However, in recent years direct numerical MHD simulations of galaxies with cooling and star formation have enabled a new way of studying magnetic field amplifcation in the Universe besides the excellent analtyical work provided by classical mean field dynamo theory (e.g. [Ruzmaikin, Sokoloff & Shukurov 1988](https://ui.adsabs.harvard.edu/abs/1988ASSL..133.....R/abstract)). Recent breakthrough in numerical simulations allows for ab-initio models for magnetic field growth in galaxies showing overwhelming evidence by many different groups that magnetic fields in galaxies can be quickly amplified by the small-scale turbulent dynamo on rather short timescale compared to the dynamical time. In [Steinwandel et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019MNRAS.483.1008S/abstract) I studied the magnetic field amplification in Milky Way-like galaxies by means of the small-scale turbulent dynamo in great detail. We evlauted the presence of the small-scale trubulent dynamo by the shape of the magnetic power-spectra that take the predicted slope of $$k^{3/2}$$ of [Kazantsev 1967](https://ui.adsabs.harvard.edu/abs/1968JETP...26.1031K/abstract). Furthermore, we quantified the dynamo for the first time in galaxy simulation by computing the correlation between magnetic field strength and magnetic curvature and find excellent agreement with the high-resolution predcitions of [Schekochihin et al. 2004](https://ui.adsabs.harvard.edu/abs/2004ApJ...612..276S/abstract). I was the first one to point out that specifically the later part could be an excellent prior for identifying the small-scale-turbulent dynamo in complex, multiphysics simualtions of galaxy formation and evolution. Hence, I show the onbtained relations for the power-spectra and the magnetic tension in Figure 1 and Figure 2 respectively and would like to encourage the community to obtain the realtion from Figure 2 for their respective galactic MHD-simualtions as this is a strong additional prior for ongoing dyanmo-action in numerical simulations.  

### Magnetic field amplifcation in Milky Way-like galaxies II: The large-scale dynamo

In [Steinwandel et al. (2020a)](https://ui.adsabs.harvard.edu/abs/2020MNRAS.494.4393S/abstract) we investigated the emergence of the large-scale dynamo after the small-scale turbulent dynamo is saturated in the non-linear regime. That this is actually the case we showed via the change in the magnetic power-spectra at late evolutionary stages of the galactic disc from a Kazantsev $$k^{3/2}$$ spectrum to an [Iroshnikov 1964](https://ui.adsabs.harvard.edu/abs/1964SvA.....7..566I/abstract)-spectrum with $$k^{-3/2}$$ as it is expected in a stronlgy conducting fluid in the presence of magnetic strong fields. In order to study the classic large-scale (mean-field) dynamo I computed a rough estimate of the Dynamo control parameters (e.g. [Ruzmaikin, Sokoloff & Shukurov 1988](https://ui.adsabs.harvard.edu/abs/1988ASSL..133.....R/abstract)) to get an estimate for the strength of the alpha-effect and the the kinetic helicty in my simulations. I was able to show that the dyanmo is supported by large-scsale rotational component that is reordering the field from a dipolar to a quadrupolar structure which I could identify in field reversals at of the radial cimponent and sign changes of the toroidal component above and below the midplane. In combination with my previous owrk I could for the first time deduce the complex interplay between the small-sclae turbulent dynamo and the large dynamo, resulting in an $$\alpha^2$$-$$\Omega$$ dynamo with a complex three dimesnional magnetic field structure as shown in Figure 3. Moreover, we were able to quantify that the simulations follow observed correlations between star formaion surface rate density and magnetic field strength in excellent agreement with the results of [Tabatabaei et al (2013)](https://ui.adsabs.harvard.edu/abs/2013A%26A...557A.129T/abstract) and previously achieved theoretical work by [Schleicher & Beck (2013)](https://ui.adsabs.harvard.edu/abs/2013A%26A...556A.142S/abstract), which I show in Figure 4.

### Magneto-centrifugal outflows in disc galaxies

In [Steinwandel et al. (2020c)](https://ui.adsabs.harvard.edu/abs/2020arXiv201212905S/abstract), I recently proposed a scenario for how magnetic fields could contribute to outflow launching in more massive galaxies based on super-equipartition magnetic fields in the galactic center that are amplified by sheared radial motions in bar formation processes. Therefore, I derived magnetic field growth in galaxies under the assumption of radial flows that originate from dynamical oscillations due to the presence of non-axis symmetric potentials, such as a bar potential. I showed that one can get a zeroth-order net growth of the toroidal component of the central magnetic field by this radial flows. Under the assumption that the $$\alpha^2$$-$$\Omega$$ dynamo already amplified the field to equipartition field strength one can show that the resulting field can reach low Plasma-$$\beta$$ values of around $$0.1$$ in the galactic center. However, a Plasma-$$\beta$$ of $$0.1$$ alone is not enough to generate an outflow based on magnetic fields. The second crucial part is to provide a field structure with a strong component perpendicular to the galactic disc (i.e. an open field geometry). In my simulations I find that this can be provided by the fast grwoing modes of the Parker-Instability and I find that the Parker-Instability can lift magnetic field lines up on the same time-scale as the basr is funneling mass towards the center of the galaxy. In combination these two effects can lead to a relatively weak but strongly magnetetized outflow, that is supported by the magnetic pressure from the low $$\beta$$-regime and the thermal feedback by exploding supernoave. In combination this generates a stronlgly colimated biconal outflow with a mass loading of around $$0.05$$.
Based on my results I suggested that this process might be a mssing link in understanding outflows in larger-scale cosmological volume simulations, epsecially in combination with cosmic-rays (CRs) that are often excluded from galaxy formation recipes. Furthermore, I tested this scenario against the sample of CHANG-ES galaxies as such an outflow process would naturally explanin the X-shaped halo field observed in the sample.
Morevoer, I derived an easy toy-model to evaluate if magnetic-driven outflows could play a role at higher redshift where higher outflow-rates in massive galaxies are very common. Therefore, I assumed simple scaling relations for the magnetic field and the star-formation rate to obtain outflow-rates based on the magnetic field for the star-forming main sequence from Withacker et al. (2014). My easy model predicts that magnetic field could contribute up to $$20$$ per cent to the telat outflow rate in high redhshift galaxies as observed in [Foerster-Schreiber et al. (2019)](https://ui.adsabs.harvard.edu/abs/2019ApJ...875...21F/abstract). 

### Supernova-Driven Outflows and star-by-star simulations of dwarf galaxies

With increasing computing power and further refined models for star formation and stellar-feedback its has become possible to carry out simulations that follow single star formation as well as the all the relevant processes governed by single stellar evolution such as photo-electric heating, photo-ionising radiation as well as individual supernovae of massive stars. In [Steinwandel et al. 2020b](https://ui.adsabs.harvard.edu/abs/2020MNRAS.495.1035S/abstract) I updated the resovled feedback model of [Hu et al. (2017)](https://ui.adsabs.harvard.edu/abs/2017MNRAS.471.2151H/abstract) to use the Riemann based Godunov-mehtod mehsless finite mass (MFM, [Hopkins 2015](https://ui.adsabs.harvard.edu/abs/2015MNRAS.450...53H/abstract)) to more accurately solve for the hydrodynamical fluxes in the multiphase ISM, that we model by including many relevant non-equilibrium cooling and heating processes as well as the relvant thermo-chemistry following [Glover & Mac Low (2007)](https://ui.adsabs.harvard.edu/abs/2007ApJS..169..239G/abstract) where I explicitly include the formation of molecular hydrogen on the surface of dust grains. I presented a detailed study of properties for the feedback by individual supernovae in terms of the momentum and the generation of the hot phase by individual explosion events and developed a simple toy model in which I showed that clustered supernovae will develop a hot volume filling phase already under moderate conditions such as we find them in the solar neighborhood and showed that this provides ideal codnitions for outflow driving. I show a schemtatic sketch of this model in Figure 7. 
In the last part I was able to link this back to resolved simulations of supernova driven turbulence and full galactic disc models that include the complete feedback loop consisting out of photo-electric heating, photo-ionisation and supernovae with my very own implementation of the MFM-method as presented in [Gaburov & Nitadori (2011)](https://ui.adsabs.harvard.edu/abs/2011MNRAS.414..129G/abstract) and [Hopkins 2015](https://ui.adsabs.harvard.edu/abs/2015MNRAS.450...53H/abstract). I show a the full disc model with 4 solar mass resolution and a force-softening of 0.1 pc in Figure 8. A full movie of this simulation can be found in the Gallery. 

### Magnetic field amplification in the Intracluster medium

The small-scale turbulent dyanmo is a powerfull tool to explain magnetic field amplification in a wider variety of astrophysical objects. Due to the sub-sonic nature of ICM-turbulence the basic theory of the small-scale turbulent dynamo can straightforward be applied to the ICM-regime since [Kazantsev 1967](https://ui.adsabs.harvard.edu/abs/1968JETP...26.1031K/abstract) developed the theory under the explicit assumption of sub-sonic turbulence. That this picture works beatifully has previously been investigated by [Vazza, Bonafede & Brueggen 2018](https://ui.adsabs.harvard.edu/abs/2018MNRAS.474.1672V/abstract) for eulerian grid codes with very aggresive refinement of the innermost megaparsec (Mpc). However, as pointed out in a recent review by [Donnert et al.](https://ui.adsabs.harvard.edu/abs/2018SSRv..214..122D/abstract), the reference study for Lagrangian code frameworks is thusfar missing. In [Steinwandel et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021arXiv210807822S/abstract) we bridged this gap by carrying out 
the complementary study with our state-of-the-art SPMHD code Gadget-3 and find excellent agreement with the theroretical predictions from dynamo theory. To that end I carried out a set of galaxy cluster simulations with increasing mass resolution from $$2 \cdot 10^{8}$$ over $$2 \cdot 10^{7}$$ up to $$4 \cdot 10^{6}$$ $$M_{\odot}$$ with magnetic fields and ansisotropic thermal conduction. I find excellent agreement with key predictions from the theory of the small-scale turbulent dynamo based on the shape of the magnetic power-spectra and the magnetic-tension relation from [Schekochihin et al. 2004](https://ui.adsabs.harvard.edu/abs/2004ApJ...612..276S/abstract). Since I use a cleaning scheme to control the $$\nabla \cdot \mathbf{B} = 0$$ constraint, I investigated the contibution to the magnetic field growth by spurious magnetic monopoles and find that it negligible compared to the resolved dynamo action in the two higjest resolution runs. Thus in my paper I showed for the first time that magnetic field amplifcaition can be resolved on galaxy cluster scales with a modern SPMHD framework. This is specifically interesting since this is an extremly hard problem of which the community was convinced that it could not be tackled with SPMHD. 

## Ongoing Projects

## Gallery

Below one can see the cosmological evolution of a massive galaxy cluster ($$2 \cdot 10^{15} M_{\odot}$$) with magnetic fields and anisotropic thermal conduction. The simulation is targeted to model the plasma-astrophysics aspect of the ICM in great detail with a spatial resolution that reaches up to $$0.1$$ kpc and a mass resolution of around $$5 \cdot 10^{5} M_{\odot}$$ per gas cell in the simualtion framework. The total runtime of the simulation from redshift $$z=380$$ down to redshift $$z=0$$ is about $$3.5$$ million core hours and ran on state-of-the-art supercomputer for around $$5$$ weeks.

{% include youtubePlayer.html id=page.youtubeId %}

Below we show a simulation of a galactic disc with a resolved dynamo driven by feedback and accretion.

{% include youtubePlayer.html id=page.youtubeId2 %}

## Scientific Talks and Public outreach

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Ulli1991/project_webpage/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
