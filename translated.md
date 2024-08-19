
# Lectures on General Astrophysics for Physicists
&nbsp;

&nbsp;

This lecture course serves as an introduction to modern observational and theoretical astrophysics. 
It is designed with the assumption that the reader has knowledge of general physics courses and 
some sections of theoretical physics. However, the first half of the course is quite accessible 
to junior students of natural sciences and well-prepared high school seniors.

This course was delivered from 1998 to 2001 for third-year students of the Physics Department 
at Moscow State University. The version presented here is from 2001. 
You can find versions from previous years and additional materials on the author website 
or on the website of the Physics Department at Moscow State University.

The english version is auto-translated from online russian version available
at [astronet](http://www.astronet.ru/db/msg/1170612/index.html) with the help of ChatGPT using
the following [script](https://github.com/doroshv/llm-examples/blob/main/translate_gpt.ipynb)


# Table of Contents

1. **Introduction: Spacetime Scales in Astrophysics**
   - 1.1 Angular and Photometric Distances
   - 1.2 Times
   - 1.3 Masses
   - 1.4 Solar Units
   - 1.5 Planck Units
   - 1.6 Dimensionless Numbers
2. **Radiation: Fundamentals of Radiative Transfer Theory**
   - 2.1 The Radiative Transfer Equation
     - 2.1.1 Basic Definitions
     - 2.1.2 Macroscopic Characteristics of Radiation
     - 2.1.3 Constancy of Specific Intensity Along a Ray in Empty Space
   - 2.2 The Transfer Equation
     - 2.2.1 Emission Coefficient
     - 2.2.2 Absorption Coefficient
     - 2.2.3 Transfer Equation
     - 2.2.4 Optical Thickness: Connection to Mean Free Path
     - 2.2.5 Source Function
     - 2.2.6 Formal Solution of the Transfer Equation
   - 2.3 Thermal Radiation
     - 2.3.1 Black Body
     - 2.3.2 Planck's Law for Black Bodies
   - 2.4 Characteristic Temperatures of Astrophysical Sources
3. **Features and Physical Limitations of Astrophysical Observations**
   - 3.1 The Main Task of Observational Astronomy
   - 3.2 Telescopes and Radiation Receivers
   - 3.3 Astronomical Intermezzo: Stellar Magnitudes
   - 3.4 Physical Limitations on the Accuracy of Astronomical Observations
   - 3.5 On the Accuracy of Light Flux Measurements
4. **Interstellar Medium**
   - 4.1 Physical Features of Cosmic Plasma State
   - 4.2 21 cm Neutral Hydrogen Line
   - 4.3 Neutral Hydrogen (HI) Clouds and Thermal Instability of the Interstellar Medium
   - 4.4 Ionized Hydrogen and HII Regions
   - 4.5 Molecular Clouds, Star Formation Regions, and Cosmic Masers
   - 4.6 Cosmic Rays and Synchrotron Radiation
   - 4.7 Other Methods of Diagnosing Cosmic Plasma
5. **Stars**
   - 5.1 General Information
   - 5.2 Star Formation
   - 5.3 Protostars
   - 5.4 Stationary Stars
6. **Stars (Continued)**
   - 6.1 Nuclear Reactions in Stars
   - 6.2 Characteristics of Nuclear Reactions in Stars
   - 6.3 M-L and M-R Relations for Main Sequence Stars
7. **Star Evolution**
   - 7.1 Evolution of Stars After the Main Sequence
   - 7.2 Degeneration of Matter
   - 7.3 Chandrasekhar Limit and Fundamental Mass of a Star
   - 7.4 Neutronization of Matter and Loss of Star Stability
   - 7.5 Supernova Explosions
8. **Remnants of Stellar Evolution**
   - 8.1 White Dwarfs
   - 8.2 Neutron Stars
   - 8.3 Black Holes
   - 8.4 Pulsars
9. **Galaxies: General Information and Quasars**
   - 9.1 Galaxies: General Information
   - 9.2 Quasars and Active Galactic Nuclei
   - 9.3 Eddington Limit of Luminosity in Accreting Compact Relativistic Objects
   - 9.4 Black Holes in the Centers of Normal Galaxies and the Relation Between Black Hole Mass and Bulge Mass
10. **Cosmology**
    - 10.1 Friedmann Cosmology
    - 10.2 Friedmann Models with Cosmological Constant
11. **Cosmology (Continued)**
    - 11.1 Light Propagation. Redshift
      - 11.1.1 Horizon
      - 11.1.2 Distances
      - 11.1.3 Surface Brightness and Olbers' Paradox
    - 11.2 Hot Universe
    - 11.3 Primordial Nucleosynthesis ("The First Three Minutes")
      - 11.3.1 Constraints on the Number of Neutrino Species from Primordial Nucleosynthesis
    - 11.4 Cosmic Microwave Background Radiation and the Recombination Era
    - 11.5 Fluctuations in Cosmic Microwave Background Radiation
12. **Cosmology (Continued II)**
    - 12.1 Challenges of Classical Cosmology
      - 12.1.1 Horizon Problem (Causality Problem)
      - 12.1.2 Flatness Problem
    - 12.2 Inflationary Universe Model
    - 12.3 Growth of Small Perturbations
      - 12.3.1 Gravitational (Jeans) Instability
    - 12.4 Formation of Large Scale Structure of the Universe
13. **Dark Matter and Gravitational Lenses**
14. **Gravitational Wave Astronomy**
    - 14.1 Description
    - 14.2 Detection of Gravitational Waves
    - 14.3 Emission of Gravitational Waves
    - 14.4 Astrophysical Sources of Gravitational Waves
      - 14.4.1 Supernova Explosions
      - 14.4.2 Rapidly Rotating Neutron Stars
      - 14.4.3 Binary Stars

--- 

### Figure Captions:
- ![Black hole destroys a star: animation](http://images.astronet.ru/si/apod.gif)
- ![Stars, dust, and nebula in NGC 6559](http://images.astronet.ru/si/apod.gif)
- ![25 brightest stars in the night sky](http://images.astronet.ru/si/apod.gif)
- ![Animation: black hole destroys a star](http://images.astronet.ru/si/apod.gif)
- ![Decomposing distant light](http://images.astronet.ru/si/apod.gif)
- ![Comparison of star sizes](http://images.astronet.ru/si/apod.gif)
- ![The most distant known star?](http://images.astronet.ru/si/apod.gif)## 1. Introduction: Space-Time Scales in Astrophysics

The range of time scales and distances that we encounter in astrophysics is quite broad. Due to the finite speed of light $c$, there exists a fundamental relationship between the characteristic scales $l$ of the phenomenon under consideration and the characteristic minimum time $t_{\text{min}}$ at which, for example, one could expect variability in the electromagnetic radiation generated at that scale, expressed as $t_{\text{min}} = \frac{l}{c}$. Another crucial characteristic of any astrophysical object is its mass $M$. In each specific case (e.g., a star, planet, galaxy), the mass $M$ can be associated with a characteristic scale $l$.

The minimum size $l_{min}$, corresponding to a macroscopic mass $M$, is determined by gravitational interactions and is approximately equal to the gravitational radius:

$$l_{min} \sim R_{g} = \frac{2GM}{c^{2}} \approx (3 \, \text{km}) \left( \frac{M}{M_{\odot}} \right)$$

where $G \approx 6.67 \times 10^{-8} \, \text{cm}^{3}/\text{g} \cdot \text{s}^{2}$ is Newton's gravitational constant.

As long as the size of the object being studied is large compared to its gravitational radius $R_g$, Newtonian physics is sufficient to describe the physical processes involved. Otherwise, relativistic effects, as predicted by General Relativity, become significant and even dominant.

### Examples
- The Sun: $R \approx 700,000 \, \text{km}$, $R_g \approx 3 \, \text{km}$.
- A Jupiter-like planet: $M_{Jp} \sim 10^{-3} M_{\odot}$, $R_g(M_{Jp}) \sim 3 \, \text{km} \ll R_{Jp}$.
- A neutron star: $R \sim 10 \, \text{km}$, which leads to significant relativistic corrections.
- A non-rotating black hole has an event horizon radius equal to the gravitational radius, and thus is entirely a relativistic object.
- The universe as a whole has a gravitational radius 

$$R_g \sim \frac{c}{H_{0}}$$

where $H_{0}$ is the current value of the Hubble constant, and should also be considered within the framework of relativistic theory (General Relativity). 

These examples illustrate the necessity of analyzing the gravitational dynamics of objects in the cosmos through a relativistic lens when their size approaches significant fractions of their associated gravitational radii.# Table of Contents  

1. **Introduction: Spacetime Scales in Astrophysics**  
   1.1 Angular and Photometric Distances  
   1.2 Timescales  
   1.3 Masses  
   1.4 Solar Units  
   1.5 Planck Units  
   1.6 Dimensionless Numbers  
   
2. **Radiation: Basics of Radiative Transfer Theory**  
   2.1 The Radiative Transfer Equation  
      2.1.1 Basic Definitions  
      2.1.2 Macroscopic Characteristics of Radiation  
      2.1.3 Constancy of Specific Intensity Along a Ray in Empty Space  
   2.2 The Transfer Equation  
      2.2.1 Emission Coefficient  
      2.2.2 Absorption Coefficient  
      2.2.3 The Transfer Equation  
      2.2.4 Optical Thickness: Connection to Mean Free Path  
      2.2.5 Source Function  
      2.2.6 Formal Solution of the Transfer Equation  
   2.3 Thermal Radiation  
      2.3.1 Black Body Radiation  
      2.3.2 Planck's Law for Black Bodies  
   2.4 Characteristic Temperatures of Astrophysical Sources  

3. **Features and Physical Limitations of Astrophysical Observations**  
   3.1 The Main Task of Observational Astronomy  
   3.2 Telescopes and Radiation Detectors  
   3.3 Astronomical Intermezzo: Stellar Magnitudes  
   3.4 Physical Limits on the Accuracy of Astronomical Observations  
   3.5 On the Accuracy of Measuring Light Fluxes  
   3.6 Literature  

4. **Interstellar Medium**  
   4.1 Physical Features of Cosmic Plasma States  
   4.2 21 cm Neutral Hydrogen Line  
   4.3 Clouds of Neutral Hydrogen HI and Thermal Instability of the Interstellar Medium  
   4.4 Ionized Hydrogen and HII Regions  
   4.5 Molecular Clouds, Star-Formation Regions, and Cosmic Masers  
   4.6 Cosmic Rays and Synchrotron Radiation  
   4.7 Other Methods for Diagnosing Cosmic Plasma  
   4.8 Literature  

5. **Stars**  
   5.1 General Information  
   5.2 Star Formation  
   5.3 Protostars  
   5.4 Stationary Stars  

6. **Stars (continued)**  
   6.1 Nuclear Reactions in Stars  
   6.2 Features of Nuclear Reactions in Stars  
   6.3 M-L and M-R Relations for Main Sequence Stars  

7. **Star Evolution**  
   7.1 Star Evolution After the Main Sequence  
   7.2 Degeneracy of Matter  
   7.3 Chandrasekhar Limit and Fundamental Mass of a Star  
   7.4 Neutronization of Matter and Loss of Star Stability  
   7.5 Supernova Explosions  

8. **Remnants of Stellar Evolution**  
   8.1 White Dwarfs  
   8.2 Neutron Stars  
   8.3 Black Holes  
   8.4 Pulsars  
   8.5 Literature  

9. **Galaxies: General Information and Quasars**  
   9.1 Galaxies: General Information  
   9.2 Quasars and Active Galactic Nuclei  
   9.3 Eddington Limit for Luminosity During Accretion onto Compact Relativistic Objects  
   9.4 Black Holes in the Centers of Normal Galaxies and the Relation Between Black Hole Mass and Bulge Mass  

10. **Cosmology**  
   10.1 Friedmann Cosmology  
   10.2 Friedmann Models with Cosmological Constant  
   10.3 Literature  

11. **Cosmology (continued)**  
   11.1 Light Propagation: Redshift  
      11.1.1 Horizon  
      11.1.2 Distances  
      11.1.3 Surface Brightness and Olbers' Paradox  
   11.2 Hot Universe  
   11.3 Primordial Nucleosynthesis ("The First Three Minutes")  
      11.3.1 Constraints on the Number of Neutrino Types from Primordial Nucleosynthesis  
   11.4 Cosmic Microwave Background Radiation and the Recombination Era  
   11.5 Fluctuations in Cosmic Microwave Background Radiation  

12. **Cosmology (continued II)**  
   12.1 Challenges of Classical Cosmology  
      12.1.1 The Horizon Problem (Causality Problem)  
      12.1.2 The Flatness Problem  
   12.2 Inflationary Universe Model  
   12.3 Growth of Small Perturbations  
      12.3.1 Gravitational (Jeans) Instability  
   12.4 Formation of Large-Scale Structure of the Universe  

13. **Dark Matter and Gravitational Lenses**  

14. **Gravitational Wave Astronomy**  
   14.1 Description  
   14.2 Detection of Gravitational Waves  
   14.3 Gravitational Wave Emission  
   14.4 Astrophysical Sources of Gravitational Waves  
      14.4.1 Supernova Flares  
      14.4.2 Rapidly Rotating Neutron Stars  
      14.4.3 Binary Stars  

---

**Publications with keywords:**  
- Stars  
- Interstellar Medium  
- Cosmology  
- Theoretical Astrophysics  
- Astrophysics  

**Publications with phrases:**  
- Stars  
- Interstellar Medium  
- Cosmology  
- Theoretical Astrophysics  
- Astrophysics  ## 1. Introduction: Space-Time Scales in Astrophysics

The range of time scales and distances dealt with in astrophysics is quite extensive. Due to the finite speed of light $c$, a fundamental relationship exists between the characteristic scales $l$ of the phenomenon under consideration and the characteristic minimum time $t_{\text{min}}$ on which one can expect variability of electromagnetic radiation generated at this scale: 

$$t_{\text{min}} = \frac{l}{c}$$ 

Another crucial characteristic of any astrophysical object is its mass $M$. In each specific case (for example, a star, planet, or galaxy), a characteristic scale $l$ can be associated with the mass $M$. The minimum size $l_{\text{min}}$ corresponding to a macroscopic mass $M$ is defined by gravitational interaction and is approximately equal to the gravitational radius:

$$l_{\text{min}} \sim R_{g} = \frac{2GM}{c^{2}} \approx (3 \, \text{km}) \left( \frac{M}{M_{\odot}} \right)$$

The gravitational radius $R_g$ is relevant for understanding the structure of astrophysical objects. As long as the size of the object being studied is large compared to its gravitational radius $R_g$, Newtonian physics is sufficient to describe the physical processes. However, when this condition is violated, relativistic effects (effects of General Relativity) become significant if not dominant.

### Examples

- The Sun, with a radius of $R_{\odot} \simeq 700000$ km;
- A Jupiter-type planet, which may have a radius $R \sim 10 R_g(M_p) \sim 3 R_{J_p}$, where $M_{Jp} \sim 10^{-3} M_{\odot}$;
- A neutron star with a radius $R \sim 3$ km; 
- A non-rotating black hole whose event horizon radius equals the gravitational radius (this is a fully relativistic object);
- The Universe as a whole, with a gravitational radius $R_g \sim \frac{c}{H_0}$, where $H_0$ is the current value of the Hubble constant, also needs to be considered within the framework of relativistic theory (General Relativity).

In summary, the appropriate understanding of spatial and temporal scales in astrophysics allows us to classify objects and predict their behaviors under different gravitational regimes.## 1.1 Distances

In modern astrophysics, a variety of non-standard units are used depending on the situation or task at hand. This is due to the fact that the ranges of quantities being considered differ by many orders of magnitude. Let’s briefly enumerate the main units for measuring distances.

1. The natural unit of distance in the Solar System is the **astronomical unit (AU)**. 

One astronomical unit = $1.5 \times 10^{13}$ cm = $\approx 500$ light-seconds, which is the semi-major axis of the Earth's orbit. It is measured using the daily solar parallax. Another method to measure the distance to the Sun, based purely on astronomical measurements, is through the observation of the annual parallax of stars: due to the finiteness of the speed of light, the position of any source (star) as measured by an observer moving with velocity $v$ is shifted by an angle 
$$\tan \theta \simeq \frac{v}{c}$$. Therefore, over the course of one Earth orbit around the Sun (a year), any star in the sky describes an ellipse, the semi-major axis of which in radians is given by 
$$\theta = \frac{v}{c} = 20.\!\!^{\prime\prime} 496 \times \frac{2\pi}{206265}$$. From this, knowing the speed of light, we can determine the speed $v \approx 30 \text{ km/s}$, and assuming a circular Earth orbit (its eccentricity $e = 0.017$), we establish the astronomical unit. Due to the smallness of $v/c$, relativistic corrections are negligible. The key issue is the precision with which we measure the astronomical unit. The modern method is based on radar ranging of solar system bodies with known orbits—asteroids that come close to the Sun, or artificial spacecraft.

The characteristic size of the Solar System is roughly 40 AU. This distance approximately corresponds to the semi-major axis of Pluto's orbit. It is also home to the so-called Kuiper belt—the second asteroid belt. Modern observational capabilities of large telescopes (e.g., the Hubble Space Telescope or the Keck Observatory 10-meter telescope) allow for the detection of sunlight reflected from bodies with sizes of several tens of kilometers at such distances.

2. Moving on to stars within the Galaxy, it becomes more convenient to use another unit—the parsec. A **parsec** is defined as the distance from which the semi-major axis of the Earth's orbit is seen at an angle of $1''$. Due to Earth's annual motion around the Sun, the position of a light source that is 1 parsec away will shift by 1 arcsecond. This phenomenon is known as **annual parallax** in astronomy, hence the name of the distance unit: **parsec = parallax in seconds**. Since the radian measure is given by 
$$1'' \approx \frac{1}{206265}$$, we find 
$$1 \text{ parsec} = 206265 \text{ AU} \approx 3 \times 10^{18} \text{ cm}$$.

Characteristic distances to the nearest stars are a few parsecs (for example, the annual parallax of Proxima Centauri is $\alpha \approx 0.745''$, which corresponds to about 1.34 pc). The distance from the Sun to the center of the Galaxy is estimated to be about 8 kpc. The size of a typical galaxy (specifically, the region of the galaxy where luminous matter—stars and gas—is observed) is around 10-20 kpc. Distances to the nearest galaxies range from hundreds of kiloparsecs to megaparsecs (the Magellanic Clouds, satellites of our Galaxy, are 55 kpc away; the Andromeda Galaxy (M31) is 640 kpc distant). The distance to the center of the Virgo cluster of galaxies, at the edge of which lies our Galaxy, is about 15 Mpc. Another nearby galaxy cluster is located in the constellation of Virgo at a distance of 80 Mpc. The Universe becomes approximately homogeneous and isotropic at characteristic distances of $\sim 100$ Mpc. Homogeneity on scales of about $10 Mpc$ means that the average density of matter in cells with this size (or rather, in volumes of $10 Mpc$) is the same regardless of the randomly chosen region.

The Hubble radius (the event horizon for any observer) is determined by the formula 
$$(\text{current age of the Universe}) \cdot (c / H_0)$$ 
where $H_0$ is the Hubble constant (approximately 50 km/s/Mpc).

3. In astrophysics, we also deal with very small distances. This is because the primary information about astrophysical sources is obtained from measuring the flux of electromagnetic radiation from various objects (we will also consider neutrino and gravitational wave radiation below), and this radiation is generated at the microscopic level during quantum transitions in atoms (bound-bound transitions), during the photoelectric effect (free-bound transitions), and due to the accelerated motion of charged particles in a vacuum (bremsstrahlung, or free-free radiation) or in a magnetic field (cyclotron or, in the case of relativistic particles, synchrotron radiation). Here are some characteristic sizes known from atomic physics that we will occasionally refer to later:

1. **classical radius of the electron**
   
   ![classical radius of the electron](https://images.astronet.ru/pubd/2002/05/14/0001176797/img66.gif)

2. **Compton wavelength of the electron**

   ![Compton wavelength of the electron](https://images.astronet.ru/pubd/2002/05/14/0001176797/img67.gif)

3. **radius of the first Bohr orbit**

   ![radius of the first Bohr orbit](https://images.astronet.ru/pubd/2002/05/14/0001176797/img68.gif)

The characteristic size of an atom is on the order of several sizes of Bohr orbits and is about $1 \text{Å} = 10^{-8}$ cm (for such distances, the non-standard unit of length, 1 angstrom=$10^{-8}$ cm, is commonly used).

Interestingly, the characteristic wavelength of photons emitted by atoms during bound-bound transitions is much greater than the sizes of the atoms themselves. The binding energy of the electron in a hydrogen atom (known as the Rydberg constant) is approximately 
$$E_b = 13.6 \, \text{eV}$$,
and during transitions from the upper level to the lower one, a photon acquires energy on the order of the binding energy of the electron, $\Delta E \sim E_b$, leading to the characteristic wavelength of visible light being approximately 
$$\lambda_{opt} \sim \frac{2 \pi a_0}{\alpha} \sim 1000 a_0$$, 
i.e., hundreds and thousands of angstroms.## 1.2 Times

Let's provide examples of some characteristic times that arise in various astrophysical problems.

1. The lifetime of an atom in an excited state is $\sim 10^{-8}$ seconds.

2. A day (the period of Earth's rotation around its axis) is $86400$ seconds.

3. The period of Earth's orbit around the Sun is approximately 1 year, or about $3.15 \times 10^7$ seconds.

4. The period of the Sun's orbit around the center of the Galaxy is approximately $250$ million years.

5. The characteristic lifetime of a star of the type of the Sun is approximately $10^{10}$ years (where $\eta$ is the efficiency of nuclear reactions turning hydrogen into helium in the center of the Sun, $\Delta M$ is the fraction of the Sun's mass converted from hydrogen to helium, $M_{\odot} = 2 \times 10^{33}$ g, and $L_{\odot} \approx 4 \times 10^{33}$ erg/s is the mass and luminosity of the Sun).

6. The current age of the Universe (Hubble age) is roughly equal to the inverse of the Hubble constant:

$$t_{max} = t_{H} \simeq \frac{1}{H_{0}} \simeq 1.5 \times 10^{10} \text{ years}.$$## 1.3 Masses

The masses involved in astrophysical problems vary by many orders of magnitude.

1. The mass of the proton is approximately $$m_{p} \approx \frac{5}{3} \times 10^{-24} \text{ g} \approx 1 \text{ GeV}$$.

2. The mass of the electron is $$m_e \approx 10^{-27} \text{ g} \approx 511 \text{ keV}$$.

3. The mass of the Sun, which is a typical star, is given by $$M_{\odot} \approx 2 \times 10^{33} \text{ g}$$.

4. The mass of luminous stars in the Milky Way, which is a typical galaxy, can be represented as $$M_G \approx 10^{11} M_\odot$$.

5. The Planck mass, which is the maximum possible mass of an elementary particle, is defined by the equation 
   $$m_{pl} = \sqrt{\frac{c h}{G}} \simeq 10^{-5} \text{ g} \approx 10^{19} \text{ GeV}$$.## 1.4 Solar Units

In the study of stars, it is common practice to use solar units for mass, radius, and luminosity.

The mass of the Sun is approximately $$M_\odot \approx 2 \times 10^{33} \text{ g}$$.

The visible radius of the Sun is about $$R_{\odot} \approx 7 \times 10^{11} \text{ cm}$$.

The luminosity of the Sun, which represents the energy output per second across the entire electromagnetic spectrum, is $$L_{\odot} \approx 4 \times 10^{33} \text{ erg/s}$$.

These units are convenient primarily when examining normal (non-degenerate) stars, where the energy source is nuclear fusion of heavy elements. However, when discussing compact remnants of stellar evolution (such as white dwarfs, neutron stars, or especially black holes), it is often more practical to estimate characteristic sizes using the gravitational radius of the object, which depends solely on its mass: 

$$R_g = \frac{2GM}{c^2} \approx 3 \, \text{km} \left( \frac{M}{M_\odot} \right)$$ 

For example, the typical radius of a neutron star, which is about $\sim 10 - 20$ km, is often expressed in terms of gravitational radii: 

$$R_{NS} \simeq 3 - 4R_g$$ 

Another example is the radius of the last stable circular orbit for a particle around a non-rotating black hole, which is given by 

$$3R_g$$. 

These expressions underscore the significance of gravitational effects in the realm of black holes and neutron stars, where traditional solar units may not adequately convey the underlying physics.## 1.5 Planck Units

Planck units are a set of measurement units for length, mass, time, charge, and their derived values, constructed from fundamental physical constants: the gravitational constant $G$ (which governs gravity), the Planck constant $\hbar$ (which relates to quantum phenomena), and the speed of light $c$ (which underpins electromagnetism and relativity, both special and general).

### Planck Length:

$$l_{Pl} = \sqrt{\frac{G \hbar}{c^3}} \simeq 10^{-33} \text{ cm}$$ 
(This length represents a characteristic scale of the "initial" scale factor of the Universe.)

### Planck Mass:

$$m_{Pl} = \sqrt{\frac{c h}{G}} \simeq 10^{-5} \text{ g} \approx 10^{19} \text{ GeV}$$ 
(This is the maximum mass possible for an elementary particle.)

### Planck Time:

$$t_{min} = t_{Pl} = \sqrt{\frac{G \hbar}{c^5}} \simeq 10^{-44} \text{ s}$$ 
(This corresponds to the initial "age" of the classical Universe.)

It is straightforward to deduce that the "Planck charge" can be expressed as

$$e = \sqrt{\alpha \hbar c},$$ 

the "Planck energy" is 

$$E_{pl} = m_{pl} c^{2} \approx 10^{-5} \times 10^{21} \text{ GeV},\, \epsilon_{pl} \approx 10^{19} \text{ GeV},$$ 

and the energy density is represented as 

$$\frac{E_{pl}}{t_{pl}} = \frac{c^5}{G} \simeq 10^{59}.$$

### Planck Density:

$$\frac{m_{pl}}{l_{pl}^{3}}.$$

These quantities will become significant when we consider physical processes under extreme conditions, such as during the early stages of the Universe's expansion. At distances or times smaller than these Planck scales, our current understanding of physics "breaks down" and necessitates the laws of a yet-to-be-established theory of quantum gravity. We will not delve deeply into these intriguing, but unsolved, issues in our general course.## 1.6 Dimensionless Numbers

In astrophysics, there are several important dimensionless numbers. Here are some of them that we will explore further.

1. The number of baryons in a typical star is given by:

   $$N_* = \left( \frac{m_{Pl}}{m_p} \right)^3 \sim 10^{57}$$

2. The total number of baryons within the causally connected region of the Universe (i.e., within the event horizon $\frac{c}{H_0}$):

   $$\frac{M_U}{m_p} \sim \frac{\rho}{m_p}\left(\frac{c}{H_0}\right)^3$$

   where $\rho \sim \frac{H_0^2}{G}$, we find:

   $$\frac{M_U}{m_p} = \left( \frac{m_{P_I}}{m_p} \right) \left( \frac{m_{P_I} c^2}{\hbar H_0} \right) \sim 10^{80}$$

   The mass of baryonic matter within the current Hubble radius:

   $$M_U \approx 10^{23} M_{\odot}$$
   
   (Note that most baryons are not found in stars, but in the diffuse interstellar medium and hot intergalactic gas).

3. The ratio of the density of relic photon number density to baryon number density:

   $$\frac{n_{\gamma}}{n_{b}} \approx 10^{9}$$

   This number plays a fundamental role in the theory of the hot Universe, and the enormous surplus of photons over baryons is interpreted as evidence of baryon asymmetry in the Universe (the absence of an equal number of antiparticles).

These straightforward estimates and relationships demonstrate a profound physical connection between the micro and macro worlds. The universe is not structured at random; rather, among an infinite number of possibilities, it is precisely the arrangement chosen by fundamental physical interactions that prevails.## 2. Radiation. Basics of Radiation Transfer Theory

The primary source of information about celestial bodies remains electromagnetic radiation. From ancient times until the mid-20th century, observations were conducted in the optical range of the electromagnetic spectrum (wavelength $3200 - 7000 \, \text{Å}$). The Earth's atmosphere does not transmit short-wavelength radiation, which is why ultraviolet, X-ray, and gamma radiation from celestial objects began to be studied only from the 1960s onward, when it became possible to launch detectors for hard radiation into the upper layers of the atmosphere and beyond, using specialized artificial satellites. Radio observations of cosmic sources began shortly after World War II in connection with the development of radar techniques.## 2.1 The Equation of Radiation Transfer

To quantitatively understand the processes occurring in astrophysical sources, we need to familiarize ourselves with the macroscopic theory of electromagnetic radiation transfer in a medium.

## 2.1.1 Basic Definitions

Let us recall some fundamental definitions. In the classical electrodynamic description, radiation is characterized by plane electromagnetic waves propagating in a vacuum at the speed of light 

$$c = 3 \times 10^{10} \text{ cm/s}.$$ 

The frequency $\nu$ of a monochromatic electromagnetic wave is related to its wavelength $\lambda$ by the relation 

$$\lambda \nu = c.$$

From the perspective of quantum physics, radiation can be described as a flow of massless vector particles—photons—traveling in a vacuum at the speed of light. The momentum $\vec{p}$ of a photon is related to its wave vector $\overset{\text{ }}{k}$ (where $\overset{\text{ }}{n}$ is the unit vector tangent to the photon’s trajectory) as 

$$\vec{p} = \hbar \vec{k}.$$

Since the energy of a relativistic massless particle (which is what a photon is) is related to its momentum by the relation 

$$E = pc,$$ 

the energy of a photon can be expressed in terms of the radiation frequency as follows:

$$E = h \nu,$$ 

where 

$$h = 2 \pi \hbar \approx 6.625 \times 10^{-27} \text{ erg s}.$$

For thermal radiation from a medium at temperature $ T $, the characteristic energy of the photons is on the order of 

$$h \nu \sim k_B T,$$

where 

$$k_B \approx 1.38 \times 10^{-16} \text{ erg/K}.$$ 

For example, optical quanta have energies around 1 eV, while X-rays have energies in the range of 1-10 keV. In energy units, a temperature of 1 eV corresponds to a physical temperature of approximately $ \sim 11000 $ K. Conversely, for low-frequency radiation (like in the radio range), it is more convenient to use frequencies expressed in Hz. 

The spectrum of electromagnetic waves is shown in Figure 2.1.

![Figure 2.1: The electromagnetic spectrum](./imgs/7f78858e906e4451b4e2942c19c5746a_img129.png)

A very useful estimate: the characteristic energy of quanta emitted by an optically thick body (for example, the photosphere of a star) with a temperature $ T $ is roughly equal to that temperature expressed in energy units. However, the reverse statement is not necessarily true: the energy of photons (without knowing the shape of the spectrum) does not always allow for an accurate conclusion about the temperature of the emitting region.

## 2.1.2 Macroscopic Characteristics of Radiation

The main macroscopic characteristics of the radiation field are as follows.

### 2.1.2.1 Energy Flux of Radiation $F$

The energy flux is defined as the amount of energy $dE$, passing through a unit cross-sectional area $dA$ in a unit time $dt$ from all directions.

$$dE = F dA dt.$$

The dimensionality of the flux is [W/m²] (SI) or [erg/cm²/s] (CGS).

From the law of conservation of energy for an isotropic source, we immediately obtain: 

$$F(R_1)4\pi R_1^2 = F(R)4\pi R^2,$$

which gives us 

$$F(R) = \frac{const}{R^2}.$$

### 2.1.2.2 Specific Intensity (or Brightness)

The flux depends on the orientation of the area in space $\vec{\Omega}$ and thus is not a function solely of the observer's coordinates $\vec{r}$ in the radiation field. More fundamentally, the description of the radiation field in terms of the photon distribution function 

$$f(\nu, \vec{r}, \vec{\Omega}, t)$$ 

is essential, which indicates the number of light quanta in the spectral interval from $\nu$ to $\nu + d\nu$, located at time $t$ within a volume element $d{\mathbf{r}}$ at point $\vec{r}$ and moving in a solid angle element $d\Omega$ around the unit vector $\vec{\bar{n}}$.

Each quantum has energy $h\nu$ and travels at speed $c$, so the specific intensity is given by:

$$dE = I_{\nu} dA \Omega dt d\nu.$$

The energy flux through a solid angle from direction $\vec{\Omega}$ is expressed as 

$$dF_{\nu} = I_{\nu} \cos \theta \, d\Omega.$$

If we integrate over all directions, we get an expression for the total flux through the intensity:

$$F_{\nu} = \int I_{\nu}(\theta) \cos \theta \, d\Omega.$$ 

### 2.1.2.3 Total Radiation Flux and Momentum Flux through the Area

Considering a radiation field (rays coming from all directions), the total energy flux through an area from a solid angle element $d\Omega$ (often called the specific radiation flux) is given by 

$$F = \int I_{\nu} dA \, d\Omega.$$ 

Integrating over all directions yields: 

$$F = \int dF_{\nu} = \frac{1}{c} \int I_{\nu} \cos^{2} \theta \, d\Omega.$$

If the radiation field is isotropic, then $I_{\nu}$ does not depend on the direction, and the total flux through an area from all directions equals zero. This situation occurs in the case of thermal equilibrium radiation (with high accuracy inside stars). Conversely, the more anisotropic the radiation field, the further it is from an equilibrium state (for example, near the boundary of a star's photosphere).

The momentum flux through a unit area per unit time (which defines the pressure exerted on that area) is calculated as follows. Each photon has a momentum 

$$\vec{p} = \frac{E}{c} = \frac{h \nu}{c}.$$ 

From this, we can express the momentum flux through a surface from direction $\vec{\Omega}$ as:

$$p_{\nu} \left( \text{dyn/cm}^2/\text{Hz} \right) = \frac{1}{c} \int I_{\nu} \cos^{2} \theta \, d\Omega$$

This is a useful relationship when discussing radiation pressure in astrophysical contexts.

### 2.1.2.4 Energy Density of Radiation

Recalling the connection between specific intensity $I_\nu$ and the photon distribution function $f_\nu$,

$$u_{\nu} = h\nu \int f d\Omega = \frac{1}{c} \int I_{\nu} d\Omega = \frac{4\pi}{c} J_{\nu},$$ 

where 

$$J_{\nu} = \frac{1}{4\pi} \int I_{\nu} d\Omega$$ 

is the mean specific intensity. 

For monochromatic radiation fields, we find the relation 

$$p = \int p_{\nu} \, d\nu = \frac{2}{c} \int J_{\nu} \, d\nu \int \cos^{2} \theta \, d\Omega = \frac{u}{3}.$$ 

This expression emphasizes how energy density relates to pressure in radiation fields.

## 2.1.3 Constancy of Specific Intensity Along the Line of Sight in a Vacuum

If the radiation flux diminishes with distance from the source, the intensity remains constant along the line of sight. This critical property follows from the law of conservation of energy. 

Let's consider two points along the line of sight. If there are no sources or sinks of energy in between (i.e., the medium neither absorbs nor emits), then 

$$I_1 = I_2.$$

This property of the specific intensity can be rephrased: 

$$I = \text{const}$$ along the path, provided there are no additional sources of radiation or absorption.## 2.2 Radiation Transfer Equation

Let us proceed to describe the propagation of radiation in a medium with which the radiation interacts. The interaction between radiation and matter can be considered on various physical levels. For our purposes, it is sufficient to introduce macroscopic coefficients of emission and absorption of light, although the calculation of these coefficients as functions of photon frequency and the physical characteristics of the medium is conducted using classical electrodynamic and quantum methods.

## 2.2.1 Emission Coefficient

The emission coefficient is defined as the energy emitted per unit volume per unit time in the frequency interval $\nu, \nu + d\nu$ in the direction $d\Omega$:
$$dE_{\nu} = j_{\nu} dV d\Omega dt.$$

In an emitting medium without absorption, over time $dt$, photons travel a distance $ds$ and the contribution to the intensity from the elementary volume $dV$ will be:
$$dI_{\nu} = j_{\nu} ds.$$ 
Thus, the radiation transfer equation takes the form:
$$\frac{dI_{\nu}}{ds} = j_{\nu}$$.

## 2.2.2 Absorption Coefficient

When traveling a distance $ds$ in an absorbing medium, a portion of the photons diminishes from the beam (is absorbed), allowing us to phenomenologically write:
$$I_{\nu}(s + ds) = I_{\nu}(s) e^{-\alpha_{\nu} ds},$$ 
where $\alpha_{\nu}$ is the absorption coefficient, dependent on the physical parameters of the medium. The intensity of the beam decreases after traveling a distance $x$ from point $s$ to point $s + ds$ according to an exponential law:
$$\frac{dI_{\nu}}{ds} = -\alpha_{\nu} I_{\nu}$$.

Sometimes, the absorption coefficient per gram of material traversed, $k_{\nu}$, is introduced. In this case, the coefficient $\kappa_{\nu}$ in cm$^{-1}$/g is referred to as the **opacity coefficient**. The physical meaning of the opacity coefficient is straightforward: when referred to a single atom, this coefficient depends only on the properties of the atom itself. This quantity $\sigma_{\nu}$ has the dimension cm$^{-1}$ and is called the **effective cross-section of absorption**. 

Assuming a parallel beam of light with frequency $\nu$ and a cross-section of 1 cm$^{2}$ passes through an absorbing gas, absorption can be visualized as if each atom is replaced by a small opaque disk, perpendicular to the beam direction, where a quantum gets trapped (absorbed). If the area of each disk is $\sigma_{\nu}$ and the concentration $n$ in cm$^{-3}$, the total area of all disks in a layer of gas with an area of 1 cm$^{2}$ and thickness $ds$ equals $n \sigma_{\nu} ds$, from which we directly obtain:
$$\alpha_{\nu} = n \sigma_{\nu}.$$

**Note:** The absorption coefficient may be either positive (genuine absorption) or negative, since in elementary processes of emission and absorption of light by atoms, there is always stimulated (induced) emission, proportional to the incident intensity, just like absorption. A well-known example from optics is the quantum radiation generator (laser). In cosmic conditions, population inversion levels (cosmic masers) are also possible. This topic will be discussed in detail in a lecture dedicated to the interstellar medium.

## 2.2.3 Transfer Equation

If the medium is capable of both emitting and absorbing light, assuming the emission coefficients $j_{\nu}$ and absorption coefficients $\alpha_{\nu}$ are known functions of coordinates and time, depending on the physical state of the substance (temperature, density, chemical composition, etc.), we can write in a stationary case:

$$\frac{dI_{\nu}}{ds} = -\alpha_{\nu} I_{\nu} + j_{\nu}$$.

### Remarks on the Transfer Equation

1. Photons from the beam can disappear not only due to genuine absorption but also due to scattering (in many real situations, for example, in the solar corona, scattering by free electrons predominates). Thus, the situation becomes significantly more complicated because scattering alters the trajectories of photons, and the transfer equation turns into an integro-differential equation, which is usually solved numerically.

2. The simplest particular cases of the transfer equation:

- Let the medium only emit, $\alpha_{\nu} = 0$: 
$$I_{\nu}(s) = I_{\nu}(0) + \int_{s_{0}}^{s} j_{\nu}(s') ds'.$$

- Let the medium only absorb, $j_{\nu} = 0$:
$$L_{\nu}(s) = I_\nu(s_0) e^{-\int_{s_0}^{s} \alpha_\nu(s') ds'}.$$

## 2.2.4 Optical Thickness and Connection with Mean Free Path

Next, we introduce a dimensionless characteristic along the beam of light's propagation—**the optical thickness** of the medium:
$$\tau_{\nu} = \int_{s_0}^{s} \alpha(s') ds'.$$

If $\tau_{\nu} \gg 1$, then we have the optically thick case (the medium is opaque to radiation); if $\tau_{\nu} \ll 1$, it is the optically thin case (the medium is transparent to radiation).

The importance of the concept of optical thickness comes from its connection with the mean free path of the photon. In a homogeneous medium without radiation, the transfer equation can be rewritten in the form:

$$\frac{dI_{\nu}}{ds} = -\alpha_{\nu} I_{\nu},$$
leading to the probability of the photon passing a distance corresponding to $ds$ being $e^{-x}$, where the average optical thickness satisfies 
$$\langle \tau_\nu \rangle = \alpha_\nu l_\nu = 1,$$
with $l_{\nu} = \frac{1}{\alpha_{\nu}} = \frac{1}{n \sigma_{\nu}}$ being the mean free path expression.

## 2.2.5 Source Function

The transfer equation is now expressed as:
$$\frac{dI_{\nu}}{d\tau_{\nu}} = -I_{\nu} + S_{\nu},$$
where $S_{\nu} \equiv \frac{j_{\nu}}{\alpha_{\nu}}$. 

This function is particularly useful because it is often easier to find or calculate than microscopic emission or absorption coefficients. We will see below that for thermal radiation, the source function represents Planck's function for thermal radiation equilibrium.

## 2.2.6 Formal Solution to the Transfer Equation

Multiplying equation ($2.22$) by an integrating factor, we obtain the solution:
$$I_{\nu}(\tau_{\nu}) = I_{\nu}(0)e^{-\tau_{\nu}} + S_{\nu}(1-e^{-\tau_{\nu}}) = S_{\nu} + e^{-\tau_{\nu}}(I_{\nu}(0) - S_{\nu}).$$ 

As $\tau_{\nu} \rightarrow \infty$, we find that $I_\nu \rightarrow S_\nu$, indicating that if $I_\nu > S_\nu$, then $\frac{dI}{d\tau} < 0$, meaning the intensity decreases as it travels through the medium. Conversely, if $I_{\nu} < S_{\nu}$, then $\frac{dI}{d\tau} > 0$, indicating that the intensity increases.

## Example: Formation of Spectral Lines

Spectral lines (of emission or absorption) form when there are discrete frequencies at which the microscopic coefficients of emission and absorption exhibit extrema. For instance, let’s say the absorption coefficient has a sharp maximum at frequency $\nu_0$. If the source function does not vary with depth, several scenarios for the observed radiation can occur depending on the optical thickness of the medium.

**Illustration of Spectral Line Formation**:
![Figure 2.1 Formation of spectral lines in homogeneous clouds. Lines do not form when the cloud is optically thick (top left). In an optically thin cloud, lines form only if it is illuminated (top right), or when it is illuminated and observed under specific conditions (bottom). Absorption lines only form in optically thin objects under certain illumination conditions (bottom center-right).](https://images.astronet.ru/pubd/2002/05/14/0001176797/img235.gif)## 2.3 Thermal Radiation

Thermal radiation is generated by matter that is in thermal equilibrium.

### 2.3.1 Blackbody Radiation

A fundamental example of thermal radiation is the radiation of a black body. The radiation of a black body is in *complete thermodynamic equilibrium*. Let's briefly remind ourselves of the main properties of blackbody radiation.

1. The spectrum of a black body (Planck's spectrum: 

![Planck's law](https://images.astronet.ru/pubd/2002/05/14/0001176797/img236.gif) - Planck's function) 

depends solely on the temperature $T$. The field of equilibrium radiation is strictly isotropic (i.e., the net flux through any arbitrarily oriented surface is exactly zero), and it is unpolarized.

2. Kirchhoff's law (valid for any *thermal* radiation) states that:

$$I_{\nu} = B_{\nu}(T)$$

is the intensity of emission for a given source function, where $j_\nu = \alpha_\nu \times B_\nu(T)$

Radiation for which the source function differs from Planck's function is termed *non-thermal* (examples of non-thermal radiation include synchrotron radiation of relativistic electrons in a magnetic field, inverse Compton scattering, Cherenkov radiation, etc.).

An important conclusion that follows from the transfer equation is that any thermal radiation becomes blackbody radiation in the limit of large optical depths.

### 2.3.2 Planck's Law for Black Bodies

The Planck function for equilibrium radiation can be expressed as the specific intensity in a unit frequency interval ([erg/cm²/c/Hz/sr]):

$$B_{\nu}(T) = \frac{2h\nu^{3}}{c^{2}} \cdot \frac{1}{e^{\frac{h\nu}{kT}} - 1}.$$

To transition to the specific intensity in a unit wavelength interval, we can use the energy conservation law:

$$B_{\nu} d\nu = B_{\lambda} d\lambda.$$

The expression for the Planck function in terms of wavelength is:

$$B_{\lambda}(T) = \frac{2hc^{2}}{\lambda^{5}} \cdot \frac{1}{\frac{hc}{e^{\frac{hc}{\lambda k T}} - 1}}.$$

The behavior of the Planck function is depicted in Figure 2.1:

![Blackbody Spectrum](https://images.astronet.ru/pubd/2002/05/14/0001176797/img242.gif)

### 2.3.2.1 Limits and Properties of the Planck Function

1. The Rayleigh-Jeans Law, 

$$I_{\nu}^{RJ}(T) = \frac{2\nu^{2}}{c^{2}} k T,$$

is observed in the limit where $hv \ll kT$. 

We note that the expression for intensity in this case does not include Planck's constant, indicating that this limit describes purely classical radiation. Attempts to extrapolate the Rayleigh-Jeans Law into higher-frequency ranges lead to divergence:

$$\int I_{\nu}^{R,J} d\nu \sim \int v^{2} d\nu \rightarrow \infty$$

(infamous "ultraviolet catastrophe"). 

2. Wien's Law,

$$I_{ \nu }^{ W } = \frac{ 2 h \nu^{ 3 } }{ c^{ 2 } } e^{ - \frac{ h \nu }{ k T }},$$

is applicable in the opposite limit when $h\nu \gg kT$.

3. The Planck function monotonically increases with temperature:

$$\frac{\partial B_{\nu}}{\partial T} > 0;$$

for $T_2 > T_1$, $B_{\nu}(T_2) > B_{\nu}(T_1)$.

4. The maximum of the Planck function occurs at approximately:

$$h\nu_{\text{max}} \approx 2.82 k T.$$

5. Wien's Displacement Law gives:

$$\lambda_{\text{max}} = 0.29 \, \text{cm}/T.$$ 

It is important to note that 

$$\lambda_{\text{max}}\nu_{\text{max}} \neq c.$$

6. The total energy flux emitted from a surface radiating as a black body is given by:

$$F = \int \int B_{\nu} \cos \theta d\Omega d\nu = \pi \int_{0}^{\infty} B_{\nu} d\nu = \sigma_{B} T^{4},$$

where 

$$\sigma_B = \frac{2 \pi^6 k^4}{15 c^5 h^3} \approx 5.67 \times 10^{-5}.$$

The energy density for blackbody radiation is given by:

$$u_{bb} = \frac{1}{c} \int_{0}^{\infty} B_{\nu}(T) d\nu d\Omega = \frac{4\pi}{c} \int_{0}^{\infty} B_{\nu} d\nu,$$

which can also be expressed as 

$$u_{bb} = \frac{4\sigma_B}{c}T^{4} = a_{r}T^{4},$$ 

with 

$$a_{r} \equiv \frac{4 \sigma_{B}}{c} \approx 7.565 \times 10^{-15}.$$ 

7. The pressure of blackbody radiation is given by 

$$p_{bb} = \frac{a T^{4}}{3}.$$

8. The average energy of a photon in blackbody radiation is given by:

$$\langle \epsilon_\gamma \rangle = \frac{u}{\langle n_\gamma \rangle},$$

where $u$ is the energy density and $\langle n_{\gamma} \rangle$ is the average number of photons:

$$\langle n_{\gamma} \rangle = \frac{4\pi}{c} \int_{0}^{\infty} \frac{B_{\nu}(T)}{h\nu} B_{\nu} d\nu \propto T^{3}.$$

9. The average energy can be computed as follows:

$$\langle \epsilon_{\gamma} \rangle = kT \frac{\int_{0}^{\infty} \frac{x^{3}}{e^{x}-1} dx}{\int_{0}^{\infty} \frac{x^{2}}{e^{x}-1} dx} \simeq 2.7 kT,$$

with 

$$\frac{\zeta(3)}{\zeta(2)} \approx 2.7,$$ 

indicating the ratio of the Riemann zeta function values.

Thus, knowing the maximum wavelength,

$$n_{\gamma} \simeq \frac{1}{2} \frac{1}{\lambda_{\text{max}}^3}.$$ 

Finally, we can conclude that as the temperature approaches about $T \approx 2.7$ K, 

$$\lambda_{\text{max}} \simeq 0.1 \text{cm},$$ 

which yields a typical value of 

$$n_{\gamma} \sim 500.$$## 2.4 Characteristic Temperatures of Astrophysical Sources

For thermal radiation, the temperature of the body serves as the sole parameter that determines the emission spectrum. In astrophysics, we generally deal with observations of sources across a limited range of frequencies (or wavelengths). The estimate of the temperature of the emitting body can be made in various ways; however, the resulting temperature value does not always correspond to the physical temperature of the emitting medium. From the perspective of radiative transfer theory, temperature is merely one of the parameters that define the source function.

The following definitions of temperature are commonly encountered:

### A) *Brightness Temperature* $T_b$

The brightness temperature $T_b$ corresponds to the temperature of a black body that has an intensity equal to that of the observed source at a given frequency, $I_{\nu}$.

In the case of radio waves (RJ-region), the radiative transfer equation for thermal radiation can be rewritten in terms of the brightness temperature:

$$
\frac{dT_b}{d\tau_\nu} = -T_b + T
$$

With the solution being:

$$
T_b = T_b(0)e^{-\tau_\nu} + T(1 - e^{-\tau_\nu}),
$$

where $\tau_\nu \to \infty$ implies $T_b \rightarrow T$. For the optically thin gas ($\tau_{\nu} \ll 1$), we find that:

$$
T_b \approx T_{\nu} \ll T.
$$

These considerations lead to the following conclusions:

1. The brightness temperature $T_b$ is a function of frequency!
2. The intensity of thermal radiation at temperature $T$ is the *maximum achievable* for any body at that temperature (which defines, for instance, the average energy of chaotic motion of particles in gas).
3. For a wide class of non-thermal spectra, the brightness temperature has no relation to the thermodynamic characteristics of the medium (e.g., in the case of synchrotron radiation with a power-law spectrum).

### B) *Color Temperature* $T_c$

The color temperature $T_c$ is defined as the temperature of a black body whose spectrum best approximates the observed spectrum in a given frequency range. The color temperature accurately reflects the temperature of a black body with unknown dimensions. 

### C) *Effective Temperature* $T_{eff}$

The effective temperature $T_{eff}$ is defined as the temperature of a black body that radiates the same energy per unit time per unit area across all frequency ranges as a specified body. The relationship is given by:

$$
F = \int \int I_\nu \cos \theta \, d\Omega \, d\nu \equiv \sigma_B T_{\text{eff}}^4,
$$

and for the luminosity, we have:

$$
L = 4 \pi R^2 \sigma_B T_{eff}^4.
$$

For example, the effective temperature of the Sun can be approximated as $T_{eff,\odot} \approx 5600$ K. Effective temperatures for stars range from 2000 K to 50000 K. Hot white dwarfs can reach effective temperatures around $T_{eff} \sim 100000 K$. Additionally, effective temperatures for neutron stars are even higher, ranging from about $10^5$ to $10^6$ K.## 3. Features and Physical Limitations of Astrophysical Observations

In the field of astrophysics, understanding the features and constraints of observational techniques is crucial. This section delves into the fundamental challenges faced by astronomers when gathering data from celestial objects and phenomena.

### 3.1 The Main Task of Observational Astronomy

Astrophysical observations rely on converting light and other electromagnetic radiation from celestial bodies into meaningful data. This task encompasses identifying, measuring, and analyzing light from stars, galaxies, and other astronomical entities.

### 3.2 Telescopes and Radiation Receivers

Telescopes serve as primary instruments for capturing light from astronomical sources. Their design and functionality can greatly influence the quality and breadth of data obtained. Key types of telescopes include optical, radio, and space telescopes, each suited to specific wavelengths of light.

### 3.3 Astronomical Intermezzo: Stellar Magnitudes

Stellar magnitudes provide a measure of the brightness of stars as perceived from Earth. This logarithmic scale is fundamental to astrophysics, helping scientists categorize stars and understand their properties.

### 3.4 Physical Limitations on the Accuracy of Astronomical Observations

Several factors impede the accuracy of observations in astrophysics, including atmospheric disturbances (for ground-based telescopes), instrument sensitivity, and the inherent variability of celestial objects.

### 3.5 On the Accuracy of Light Flux Measurements

Accurate measurement of light flux is paramount in astrophysics as it relates directly to the energy output of stars and other celestial bodies. Meticulous calibration and advanced techniques are employed to enhance the precision of these measurements.

---

### Figure Captions

- **Figure**: Illustration of a telescope capturing light from a distant star.
- **Figure**: Graph showing the relationship between distance and luminosity of stars.

By studying these topics, we can appreciate the intricate dance of light and matter that underpins our understanding of the universe. Astrophysics continually evolves, driven by advancements in technology and observational techniques, further unraveling the mysteries of the cosmos.## 3.1 The Main Task of Observational Astronomy

The primary distinguishing characteristic of information reception in astronomy is the impossibility of conducting an "experiment" in the conventional sense used in physics. We cannot specifically "prepare" the object of study or influence it in any way. Due to the finite speed of light, when examining the signal from a certain source, we are actually studying physical processes that occurred many hundreds, thousands, or even billions of years ago. For this reason, astronomers refer to their work as astronomical *observations*, emphasizing the passive reception of information from sources. Thus, the reception and analysis of temporal and spectral characteristics of signals from astronomical sources become the main method for investigating their physical state and evolution. 

To obtain a clear physical understanding of the class of objects under investigation (such as stars or galaxies), it is essential to conduct observations on the largest possible number of them at various stages of their evolution.

The primary channel of information in astronomy is still linked to the study of electromagnetic radiation. The entire space is permeated by the radiation of stars, interstellar gas and dust, intergalactic hot gas, and relic microwave radiation. Therefore, the challenge arises to (A) separate the positions of sources on the celestial sphere from each other and (B) extract the *signal* from a particular source amidst the natural *noise*.

## 3.1.1 Transmission of Light through the Earth's Atmosphere

The strong interaction of electromagnetic radiation with the matter in Earth's atmosphere makes ground-based astronomical observations possible only in narrow "windows of transparency" in the optical, infrared, and radio ranges (see Figure 3.56). The absorption of infrared photons occurs primarily with water, oxygen, and carbon dioxide molecules in the troposphere. Ultraviolet and harder radiation is absorbed by molecular and atomic oxygen and nitrogen, while absorption in the near ultraviolet mainly occurs due to ozone at altitudes of 20-30 km above the surface of the Earth (the ozone layer). Starting from altitudes of 20-30 km, the atmosphere becomes practically transparent to photons with energies above 20 keV. The opacity of the atmosphere in the decameter radio range is due to reflection from the ionosphere, which is located at altitudes of 90 km and above.

From the figure, it is evident that almost the entire infrared range of the spectrum, along with hard X-ray and gamma radiation, can be observed with equipment lifted on balloons and airplanes above 20-30 km. Observations of ultraviolet and X-ray photons are only possible from high altitudes or near outer space.

<div align="CENTER"><a name="atm0"></a>
<table align="center" width="50%">
<tr><td>![Figure 3.56: The height to which radiation of a given wavelength penetrates, ranging from long radio waves to gamma radiation. Curves are provided for heights where 50%, 10%, and 1% of the incoming radiation reaches.](https://images.astronet.ru/pubd/2002/05/14/0001176797/3lec/img8.gif)</td></tr>
</table>
</div>

## 3.1.2 Transmission of Light through Interstellar Medium

The interstellar medium is filled with sparse ionized and neutral hydrogen, dust, and molecular clouds. Electromagnetic radiation propagating through such a medium undergoes absorption and scattering, which significantly affects the observational capabilities of distant astronomical sources.

In the radio wave region, absorption is practically absent, while the ionized component of the interstellar medium is responsible for radio signal dispersion. The main absorption in the infrared, optical, and ultraviolet ranges (0.1-20 µm) is due to interstellar dust. The dust particles absorb ultraviolet and visible radiation from stars, converting it into lower-energy photons. A characteristic feature of interstellar absorption in this area is its *selectivity*, meaning a strong dependence on wavelength. This dependence is non-monotonic, exhibiting various features, but on average, absorption in the blue part of the spectrum is stronger than in the red, leading to *reddening* of light sources.

In the visible range, the absorption curve approximately follows the law $A \propto \lambda^{-n}$. The amount of interstellar absorption calculated per unit distance varies widely and depends on direction. The maximum absorption occurs in the galactic plane, where most of the gas-dust complexes are concentrated. In the vicinity of the Sun in the galactic plane, the optical thickness is about 2 for 1 kpc, with the highest contribution from clouds (6-10 clouds per 1 kpc). In some directions, the optical thickness can reach several tens (the so-called "coal sacks"). Absorption decreases with distance from the galactic plane according to a cosecant law, reaching a roughly constant level for galactic latitudes $|b| > 20^\circ$. A connection has been established between the optical thickness for absorption in the optical range (V band) and the number of neutral hydrogen atoms $N_H$ along the line of sight in a column with a cross-section of 1 cm$^2$:

$$
\tau = 0.1 N_H \text{ [g/cm]}^{-2}
$$

In shorter wavelengths, the main absorption is associated with neutral gas (mainly hydrogen) and other chemical elements. The primary reason for the absorption of high-energy photons is the photoelectric effect (photoelectrons being ejected from the various shells of chemical elements). If the energy of the incoming photon is equal to $E_{p} > \phi$, it can eject an electron from the atom with a binding energy $\phi$, and the remaining energy converts into the kinetic energy of the emitted electron. Energies at which $E_{p} < \phi$ are called *absorption thresholds*, since the ejection of electrons from these levels by lower energy photons is impossible. At higher energies, the photoabsorption cross-section for that level rapidly decreases as $E_{p} \rightarrow 0$. For example, the ionization threshold for hydrogen at 13.6 eV corresponds to a photon wavelength of 912 Å, so radiation with a wavelength shorter than 912 Å is heavily absorbed in the interstellar medium. The effective photoionization cross-section for atoms in the interstellar medium is shown in Figure 3.57. For a given element, the photoionization cross-section is zero for photon energies below the ionization threshold from the innermost shell. The graph shows jumps in absorption at the ionization levels of various elements up to iron. 

In observations within the X-ray range (0.1-100 keV) with low spectral resolution, these jumps are not resolvable, therefore the relationship between optical thickness in this range and the number of hydrogen atoms along the line of sight is given by:

$$
\tau_X = 0.1N_H \text{ [g/cm]}^{-2}
$$

When free electrons are present in the medium for hard X-ray photons with an energy of 10 keV, Compton scattering on free electrons becomes predominant. The cross-section for Compton scattering does not significantly depend on photon energy up to energies of approximately $E_{0}$, where $m_{e}$ is the electron rest mass, and it equals the Thomson cross-section for scattering on free electrons, $\sigma_T \approx 6.65 \times 10^{-25} \text{ cm}^2$. For higher energy photons, the scattering cross-section decreases rapidly.

For gamma photons with an energy of $E_{\gamma} = 0.1$ MeV, the dominant process may turn out to be the production of electron-positron pairs. However, the pair creation due to the conservation of momentum is impossible in a vacuum; it occurs either in a nuclear field or in a magnetic field. The passage of hard quanta and energetic particles through a substance is often characterized by a permeability value, which is the reciprocal of opacity $\kappa$ [g/cm$^2$] (effectively this is the mean free path length multiplied by the density). For high-energy gamma photons ($E_{\gamma} > 100$ MeV), the permeability of matter is approximately equal to that for charged particles with the same energy and numerically equals $\kappa \approx 0.1$ g/cm$^2$. From the figure, it is clear that the entire Galaxy is "transparent" to photons starting from the soft X-ray range (100 Å).

## 3.1.3 "Point" and "Extended" Sources

Due to diffraction of light on the telescope's objective, the image of any object in the focal plane has a finite size given by the relationship:

$$
\Theta = \frac{1.22 \lambda}{D},
$$ 

where $\lambda$ is the wavelength of radiation and $D$ is the diameter of the objective. The *resolution* of an astronomical telescope is defined as the minimum angular size of the image that the telescope can construct. As shown below, for large ground-based telescopes, the resolution is limited by the effects of turbulence in the atmosphere through which the light travels before reaching the telescope.

Based on their angular sizes, astronomical sources can be divided into two broad classes: point sources and extended sources. A point source (extended source) has angular sizes smaller (larger) than the telescope resolution. Clearly, in the limit of infinitely high angular resolution, any source ceases to be a point source.

First, we will demonstrate that from a "point" source of radiation, the telescope can only record the flux of radiation (not the intensity). Consider a spherical radiator (star) with a radius $R$ at a distance $d$ from the observer. We introduce a coordinate system with the axis z directed towards the observer. Let $R$ be the distance perpendicular to this axis. The circular ring on the surface of the star, visible from the center of the star at an angle $\theta$ with respect to the line of sight, has an area in projection normal to the line of sight

$$
A = \pi R_\text{star}^2 (1 - \cos{\theta}).
$$

The observer sees this area under a solid angle $\Omega$. The intensity from the area of the star in the direction of the observer is $I$. The energy received per unit time by a unit area (detector) perpendicular to the line of sight (actually the flux), from an infinitesimal area on the surface of the star is 

$$
dF = I \cdot dA \sin{\theta} \; dt$$

Integrating over the disk of the star, we obtain:

$$
F = R^2 \int dA \cdot I \cdot \sin{\theta}.
$$

Thus, if the source is "point-like" for the given telescope, only the *flux of radiation* is registered, not the intensity. However, if the angular diameter of the star is known, observed as a "point" source, the captured flux can be recalculated using formula (3.3) to the flux emitted near the surface of the star.

If the radiation field near the star's surface is isotropic (i.e., the intensity of the radiation emitted from the star's photosphere does not depend on angle, which is practically never the case in stars), then the direct study of the intensity of outgoing radiation carries maximum information about the emitting matter.

For an "extended" source, on the contrary, one can directly observe the intensity of outgoing radiation (the term *brightness* is often used), averaged within the limits of the telescope's resolution. The highest angular resolution is achieved in the radio range, therefore, for radio sources with known angular sizes, the concept of *brightness temperature* is often used to characterize their radiation, as in this frequency range (Rayleigh-Jeans region) it is proportional to the intensity of the outgoing radiation $ I $.## 3.2 Telescopes and Radiation Receivers

### 3.2.1 Optical Telescopes

To isolate individual sources in the sky, it is necessary to enhance the resolving power of the receiving device and increase the incoming flux of radiation from the source. These goals are achieved through the use of a telescope—a specialized device where collected electromagnetic energy is focused into individual images. The first optical telescope was invented by Galileo Galilei in 1610 and consisted of two converging lenses with varying diameters and focal lengths, namely the objective lens and the eyepiece. Subsequently, parabolic mirrors (reflecting telescopes) began to replace lenses for the objective, as they exhibit fewer aberrations than lenses and are easier to manufacture technologically.

The objective lens is designed with the largest possible diameter to collect the maximum amount of energy and provide good angular resolution. The *resolving power* of the telescope is determined solely by the diameter of the objective lens and is limited by the diffraction of light at the entrance pupil ![](https://images.astronet.ru/pubd/2002/05/14/0001176797/3lec/img40.gif) as well as by the influence of atmospheric turbulence for ground-based optical telescopes (see below).

Images are formed in the focal plane of the objective. If the goal is to study the images of all objects that fall within the field of view of the objective, a panoramic receiver (such as a photographic plate or CCD matrix) is placed in the focal plane. This setup does not require additional optics (eyepiece). If the task is to measure the flux of radiation from a specific source, the receiver is placed at the *exit pupil* of the telescope. The exit pupil is the image of the objective lens projected by the eyepiece. Since the exit pupil contains images of all stars within the objective's field of view, a diaphragm is installed in the focal plane to isolate light coming solely from that specific source.

---

<div align="CENTER">
![](https://images.astronet.ru/pubd/2002/05/14/0001176797/3lec/img56.gif)
**Fig. 3.58**  
Schematic representation of one of the four 8.2-meter telescopes of the VLT project at the Southern European Observatory on the Paranal plateau in the Chilean Andes.
</div>

---

The largest modern optical telescopes have primary mirror diameters of: 6 m (Special Astrophysical Observatory of the Russian Academy of Sciences, Northern Caucasus), 8 m (Very Large Telescope, Southern European Observatory, Chile), and 10 m (composite mirror, adaptive optics; Keck Observatory, Hawaiian Islands, USA). The VLT project comprises four independent telescopes with primary mirror diameters of 8.2 m (see Fig. 3.3). Each mirror can mechanically adjust its shape to correct for atmospheric image blurring (adaptive optics). It can serve as both an independent telescope and a component of an optical interferometer with an effective diameter of 16 m. By the year 2000, two out of the four telescopes were operational. The observation range spans from 25 microns to 3000 Å.

### 3.2.2 Receivers

The main task of a *receiver* is to convert electromagnetic energy from light into other forms (e.g., mechanical, electrical, or thermal), the measurement of which through laboratory physical methods allows conclusions to be drawn about the characteristics of the light signal received by the telescope. At the microscopic level, the light-sensitive element of any receiver consists of a material in which the energy of photons converts into the kinetic energy of free electrons (internal or external photoeffect) or into the vibrations of ions within the nodes of a crystal lattice, which are subsequently registered by various means. Simple examples include silicon photodiodes or photokathodes in photomultiplier tubes. The threshold of the photoeffect in a specific substance defines the *sensitivity range* of the detector. The intrinsic sensitivity of various receivers is determined differently, but fundamentally, it is the minimum amount of electromagnetic energy within the detector's sensitivity range that, upon interaction with the detector material, produces a physical effect comparable to the internal noises of the detector (thermal noise, etc.).

Another characteristic is the response time, the minimum time required for the detector to react to a received portion of electromagnetic radiation. The response time limits the temporal resolution of the detector.

To describe the sensitivity of light detectors quantitatively, the concept of *quantum efficiency* $\eta$ is often used. For instance, for the human eye, $\eta \approx 10\%$, for photographic emulsion it is 1-5%, while for photomultiplier tubes (PMTs), the quantum efficiency can reach 50-70%, and for charge-coupled devices (CCDs), it can exceed 50-70%.

This characteristic is also applied for quantitatively describing the overall efficiency of the instrument, i.e., the entire path from telescope to detector to amplifier, or individual components within this path since additional noise can arise in each element of the receiving channel, degrading overall reception efficiency (for example, light scattering in optics and telescope structures or parasitic couplings in signal amplifiers). Thus, the *overall quantum efficiency* is simply defined as the ratio of the signal-to-noise ratio at the input of the receiving channel to the signal-to-noise ratio at its output.

Different ranges of the electromagnetic spectrum have their peculiarities in the principles of radiation detection and the construction of images from sources.

### 3.2.3 Radio Telescopes

Radio telescopes are used to receive cosmic radiation within the window of transparency of the Earth's atmosphere for radio waves, ranging from millimeters to decameters. They consist of an antenna and a radiometer. The most commonly used are *parabolic antennas*, which collect parallel radio waves at their focus. Fully steerable antennas can reach diameters of 100 m (Bonn, Germany). The largest fixed antenna is the 300-meter radio telescope in Arecibo, Puerto Rico, USA. Also employed are *synthesized antennas*, individual elements of which may include elementary feeds (half-wave dipoles, spiral antennas) or small-diameter parabolic reflectors. The signal from each elementary feed is transmitted via waveguides to the receiver, with the delay in the waveguides calculated so that signals arrive at the receiver in phase (coherently).

The resolving power of a radio telescope is determined by the width of the main lobe of the antenna's radiation pattern and is defined similarly as for optical telescopes: 

$$ \Delta \theta = \frac{\lambda}{D} $$ 

where $\lambda$ is the wavelength of the received radiation. The sensitivity of the radio telescope is defined by the effective area of the antenna $A_{eff}$, which is associated with the shape of the radiation pattern $g(\theta, \phi)$ (a dimensionless function indicating how much more or less power is received from a real antenna in the direction $(\theta, \phi)$ compared to that received by an idealized antenna with an isotropic radiation pattern; the main lobe reaches a maximum value of $g(0, 0)$). Therefore, the effective area is:

$$ g(\theta, \phi) = \frac{4\pi A_{eff}}{\lambda^2}. $$ 

The effective area is always less than the geometric area of the antenna due to the presence of side lobes in the radiation pattern.

#### 3.2.3.1 Noise and Antenna Temperature

To characterize the sensitivity of antennas, the concept of *noise temperature* $T_n$ is employed. The noise temperature of an antenna characterizes the total power of radiation $W_{n,a}$ received by the antenna through all lobes of the radiation pattern from the Earth’s surface, atmosphere, ionosphere, and outer space in a frequency band $\Delta \nu$:

$$ W_{n,a} = k_B T_{n,a} \Delta \nu $$ 

where $k_B$ is Boltzmann's constant and $\delta T_{n,a} \ll T_{n,a}$ signifies a small change in antenna temperature. The passage of a cosmic source through the main lobe of the antenna's radiation pattern causes slight variations in antenna temperature $T_a$, and the task boils down to isolating a weak signal from the noise. When the receiver bandwidth $\Delta \nu$ (determined by the bandwidth of the radiometer amplifier) and the signal integration time $\tau$ are considered, the minimal detectable signal amplitude is given by 

$$ \Delta T_{n,a} \sim \frac{T_n}{\sqrt{\Delta \nu \tau}}. $$ 

For broader signals, extending the receiver bandwidth and increasing the observation time can enhance the sensitivity of the radio telescope to broadband signals. For narrowband signals (e.g., quasi-monochromatic) or pulsed signals, the sensitivity formula changes accordingly. For optimal reception of pulsed signals with characteristic time $T_k$, the receiver's bandwidth should be:

$$ \Delta \nu \sim \frac{1}{T_k}. $$

#### 3.2.3.2 Aperture Synthesis Method

Due to the large wavelengths of radio waves, even radio telescopes with very large antenna diameters display poor resolving power, typically a few angular minutes at best. To enhance this resolving power, it’s necessary to increase the signal reception baseline. This is achieved using radio interferometry, where signals from two or more radio telescopes dispersed over a distance $D$ are recorded by devices at each telescope and subsequently processed together. The effective resolving power can achieve values on the order of 

$$ \Delta \theta \sim \frac{\lambda}{D}. $$ 

In very long baseline interferometry, telescopes located at different points on Earth (for example, in Europe and Australia) are utilized, achieving resolving powers better than 100 microseconds of arc.

Unlike a single radio telescope, a radio interferometer does not capture the entire image but only one of the spatial Fourier harmonics of the brightness distribution of sources across the sky. To construct an image, as many harmonics as possible with varying phases are required (via the aperture synthesis method). This is accomplished by simultaneously observing the source with numerous antennas of different baselines and orientations. For instance, the Very Large Array (VLA) in New Mexico, USA, consists of 27 antennas, each 25 m in diameter, arranged in a Y-shaped configuration. The resolution of the VLA reaches up to 1 angular second at a wavelength of 10 cm.

Even greater resolution can be achieved by placing one of the radio telescopes in space (a space radio interferometer). Several such projects, including ones in Russia, are currently under consideration.

### 3.2.4 X-ray Telescopes and Detectors

To register high-energy photons, their specific interactions with matter are utilized. For detecting photons with energies less than 20-30 keV, detectors that utilize the photoelectric effect in gas or on solid surfaces are applied. These include *proportional gas-filled counters*, the amplitude of the electrical impulse at the output of which is proportional to a certain spectral range of the photon energy. The effectiveness of such detectors is determined by the photoionization cross-section of the gas fill (typically inert gases such as Ar or Xe) and the transmission coefficient of the counter's window (commonly thin foils of light metals like Be or Al with thicknesses of 10-100 microns, or organic films with thicknesses of 1-10 microns or less). To stop the electrical discharge in the inert gas caused by the arrival of a high-energy photon, an electronegative gas (such as methane or CO) is added. In proportional mode, the gain coefficient can reach values of $\eta \approx 10\%$. Spectral resolution of these counters is not very great (often around 5 keV) and is inversely proportional to the square root of the photon energy. The area of individual gas-filled proportional counters can reach approximately 300 cm².

For detecting photons with energies from 30 keV to 10 MeV, *scintillation detectors* are used, with crystals of NaI or CsI doped with Tl or scintillating organic plastics as the sensing material. The incident photon causes a flash of UV or visible light in the scintillating material, the amplitude of which is proportional to the energy of the absorbed quantum within a certain spectral range. The impulses of visible light are registered by photomultiplier tubes. The size of scintillation detectors is limited by the technology for growing single crystals of CsI or NaI and typically does not exceed 100-300 cm². To determine the coordinates of X-ray photons, they are first converted into a beam of electrons and then into visible light. Various devices, such as multi-wire two-coordinate proportional gas-filled counters, diode matrices, or CCD matrices are utilized for this purpose.

In the soft X-ray range, reflective focusing telescopes (oblique-incidence X-ray telescopes) are employed to construct X-ray images. These telescopes operate because the reflection coefficient for metals increases with the wavelength of the incoming X-ray radiation and as the angle of incidence approaches 90 degrees. A high reflection coefficient (over 50%) for Au and Pt is achieved at incidence angles greater than 87 degrees. A two-mirror system consisting of a paraboloid and a hyperboloid of revolution (the Walter-type oblique-incidence X-ray telescope) provides good quality X-ray imaging, with angular resolution reaching 1" (arcsecond). The effective area of such telescopes, depending on photon energy, can achieve 20 cm² in the energy range of 0.5-1 keV.## 3.3 Astronomical *intermezzo*: Stellar Magnitudes

Since the primary information about celestial bodies is obtained in the optical and near-optical ranges (IR, UV), we will focus on the specific units of measurement for radiation fluxes at these wavelengths ($A$), which are widely used in astrophysics.

Let us make simple estimates of the characteristic radiation fluxes that we encounter in astrophysics.

a) The energy flux from the Sun. The bolometric luminosity of the Sun is given by

$$L_{\odot} = 4 \times 10^{33} \, \text{erg/s},$$ 

and the distance to Earth is 

$$R \approx 3 \times 10^{18} \, \text{cm},$$ 

from which the total flux of electromagnetic energy from the Sun at Earth is 

$$\frac{L_{\odot}}{4 \pi R^2} \sim 10^6 \, \text{erg/cm}^2/\text{s}.$$

b) A star of solar type located at the center of the Galaxy ($1 \, \text{kpc} \approx 206265 \, \text{AE}$). Due to the decrease in the received flux from the source being inversely proportional to the square of the distance to it, the flux at Earth from a solar-type star at 10 kpc is

$$\frac{F(1\,\text{kpp})}{F_{\odot}(1\,\text{AE})} = \left(\frac{1\,\text{AE}}{1\,\text{kpp}}\right)^{2} \sim \left(2 \times 10^{5} \times 10^{4}\right)^{-2},$$ 

which is nearly 19 orders of magnitude weaker!

Therefore, for convenience in astronomy, logarithmic scales of flux are used (similar to decibels in acoustics). This is closely related to the biological characteristics of human senses. Human perception (vision, hearing) responds to signals in a logarithmic relation (the so-called Weber-Fechner psychophysical law: if stimulation increases in geometric progression, sensation increases in arithmetic progression).

### 3.3.1 Definition

Historically, the following units of exposure (energy reaching the detector during the exposure time) have been adopted in astronomy.

*Stellar magnitudes* – a measure of the relative brightness of stars – were introduced by Hipparchus of Rhodes in the 2nd century BC, as five degrees of brightness of stars. Mathematically, the definition of stellar magnitudes was formulated by the British astronomer Pogson in 1859 for the difference between two stellar magnitudes $m_1$ and $m_2$:

$$m_{2} - m_{1} = -2.5 \log \left( \frac{E_{2}}{E_{1}} \right).$$

The zero point of the magnitude scale is taken to be the A0 spectral class star (currently known as $\alpha$ Lyr Vega). The “color” of the star is defined by the difference in stellar magnitudes at different wavelengths:

$$m(\lambda_1) - m(\lambda_2) = -2.51g \left( \frac{F(\lambda_1)}{F(\lambda_2)} \right) + C.$$

It is worth noting an important approximate relationship: the zero point (i.e., the star of zero magnitude) corresponds to a specific flux of photons with a wavelength $\lambda = 5500 A$.

### 3.3.2 Absolute Stellar Magnitude

By definition, this is the stellar magnitude that a source (star, galaxy, etc.) would have at a distance of 10 parsecs. Let’s suppose the star is located at a distance of $d$ and has an apparent stellar magnitude $m$. Considering the dependence of the change in the received radiation flux from the source with distance $R$, we directly obtain from Pogson's formula:

$$M - M_{\odot} = -2.5 \log\left(\frac{L}{L_{\odot}}\right),$$ 

which leads us to 

$$\frac{L}{L_{\odot}} = 10^{-0.4(M - M_{\odot})}.$$

### Example

1. First, let’s determine the visible stellar magnitude (by comparing the flux from the Sun, say with Vega):

$$F(\lambda) \text{ comparison to } m = 0^{m} \rightarrow 10^{3} \, \text{quanta}/\text{cm}^2/\text{s/Å}.$$

2. From the formula derived earlier, we calculate: 

$$\Delta \lambda \approx 700 \, \text{Å} \text{ for } \lambda_U = 3650 \, \text{Å},$$ 

$$\Delta \lambda \approx 1000 \, \text{Å} \text{ for } \lambda_{B} = 4400 \, \text{Å},$$ 

$$\Delta \lambda \approx 900\, \text{Å} \text{ for } \lambda_{V} = 5550 \, \text{Å}.$$

Thus, we bridge our understanding of stellar magnitudes, relative brightness, and the underlying physics that governs them.## 3.4 Physical Limitations on the Accuracy of Astronomical Observations

### 3.4.1 Coherence of Light
Stars are not mere points with infinitely small angular sizes; they possess a finite (albeit very small) angular size. For instance, the disc of the Sun, with a radius of the visible photosphere approximately $R_\odot = 7 \times 10^{10}$ cm at a distance of 10 parsecs, is observed at an angle of 

$$\theta \approx 6 \times 10^{-4}''.$$

Since observations are conducted using telescopes (receivers) with finite apertures (diameters) $D$, one must consider Fresnel diffraction: for a monochromatic source with a wavelength $\lambda$, the size of the diffraction disc image is 

$$\beta_d \simeq 1.22 \frac{\lambda}{D}.$$

**Note**: Atmospheric turbulence distorts the wavefront, blurring the point image to sizes on the order of 1", which is much larger than the diameter of the diffraction disc. It is relatively rare to achieve "image quality" $\theta = 0{''}.003$ at high-altitude observatories (for instance, at the Mauna Kea Observatory, which is located 4000 m above sea level in the Hawaiian Islands, at the European Southern Observatory in Chile, and at the Maidanak Observatory in Uzbekistan). Space telescopes, of course, are free from atmospheric influences and achieve the diffraction limit of angular resolution.

If a source is not point-like and has a finite angular size $\theta_0$, then for 

$$D \leq 1.22 \frac{\lambda}{\theta_0},$$ 

the source should be treated as coherent because the path length difference of rays from different "edges" of the source is less than half the wavelength (an example is the star Vega: $\theta_0 \sim 0{''}.001$, with $D \approx \lambda = 5500$ A). Thus, any deviation of the wavefront within an angle 

$$\theta \sim \frac{\lambda}{D}$$ 

keeps the image coherent (the phase difference does not exceed $\beta_d$). Therefore, due to random distortions of the wavefront from a source with an angular size $\theta_0$, an interference pattern will be observed as long as 

$$\beta_d \approx 0.12'' \gg \theta.$$ 

This principle is the foundation of Michelson star interferometers, which were used to measure the diameters of some nearby giant stars back in the 1920s. The main issue with this method is the blurring of the interference pattern caused by atmospheric turbulence.

Real sources are typically not monochromatic. For them, the concept of coherence length (or area) becomes important. From optics, we know that as the path length difference increases, the contrast of the interference fringes decreases. The path length difference can be expressed as 

$$\Delta l = c \Delta t,$$

where $\Delta t$ is the coherence time, and for a source with a bandwidth $\Delta \nu$, the coherence time can be expressed as 

$$\Delta t = \frac{1}{\Delta \nu} = \frac{1}{c \lambda^2} \frac{1}{\Delta \lambda}.$$

The physical meaning of coherence length is straightforward. It indicates the maximum allowable path length difference for visibility of interference fringes. Depending on the aperture-coherence length ratio, in various ranges there are distinctions made between coherent and incoherent signal reception.

Considering, for example, the optical range, $\lambda = 5000$ A, we find 

$$l_{coh} \simeq 2.5 \times 10^{-3}$$ 

cm, which is several wavelengths long. Conversely, in the radio range, where narrow-band detectors are used (e.g., $\lambda \sim 1$ cm at $\Delta \nu = 100$ MHz), the coherence length can be 

$$l_{coh} \simeq 300$$ 

cm, being several hundred wavelengths. Thus, in the long-wavelength range, coherent signal reception can be performed, yielding very high angular resolutions (radio interferometry). In optics and at higher frequencies, reception is almost always incoherent. Nevertheless, optical interferometry can be executed using the aperture synthesis method (as mentioned earlier). This requires at least two telescopes positioned a distance $D \geq 1$ apart from each other with short exposures (to prevent atmospheric turbulence from blurring the interference pattern) at various orientations of the telescope-telescope axis relative to the source (this is facilitated by Earth's daily rotation). The resulting interference pattern can potentially achieve an angular resolution 

$$\beta \approx \frac{\lambda}{r_0} \gg \frac{\lambda}{D_2}$$ 

for this to occur, the light paths from both telescopes must converge at a common focus with a path difference that does not exceed the coherence length. This technically challenging task will be realized at the four-telescope Very Large Telescope (VLT) of the European Southern Observatory, where the effective diameter of the VLT interferometer will equal 16 m, with an angular resolution of $0.006''$ at a wavelength of 5000 A. In 2000, the second of the four 8.2 m telescopes of the VLT became operational. By the end of 2001, the first interferometric observations were made using two VLT telescopes operating in interferometer mode with a baseline of 102 m. Angular sizes of several stars were measured at the level of one millisecond of arc (a record for ground-based observations). By 2010, the launch of the Terrestrial Planet Finder (TPF), a space interferometer consisting of four 3.5 m telescopes with a maximum baseline of 1 km, is planned. The angular resolution will reach $0.001''$ at a wavelength of 3 μm, with the main scientific goal of this interferometer being the search for Earth-like planets around nearby stars.

### 3.4.2 Speckle Interferometry
As previously mentioned, atmospheric turbulence distorts the wavefront and "blurs" the image of the star. Figure 3.59 schematically illustrates the passage of the wavefront through a turbulent atmosphere. To quantitatively characterize the scale of turbulence in the atmosphere, the Fried parameter $r_0$ (the so-called Fried parameter) is introduced. Its physical meaning is equivalent to the diameter of a telescope that achieves the diffraction-limited half-width of the image $D_{diff}$, producing an image created by the atmosphere when observing a point source with an ideal telescope with an infinite mirror size. The Fried parameter varies with the wavelength of the source $\lambda$ and in the optical range fluctuates between 5-20 cm. The larger the Fried parameter, the more suitable the site is for astronomical observations.

A small telescope with an aperture $D_1$ produces a diffraction image of its aperture $D_{diff}$ and is relatively unaffected by atmospheric blurring (left side of the image). In contrast, a large telescope with diameter $D_2$ (right side of the image) simultaneously creates a large number of separate diffraction images of the source, which are "blurred" by turbulence in areas with angular sizes $\theta \sim \frac{\lambda}{r_0}$. Thus, with sufficiently long exposures, the angular resolution of a large telescope is *completely* determined by the size of the image created by the atmosphere.

![Figure 3.59](https://images.astronet.ru/pubd/2002/05/14/0001176797/3lec/img155.gif)  
**Figure 3.59** Passage of light through a turbulent atmosphere. Left - detection by a small aperture telescope $D_1$; right - detection by a large aperture telescope $D_2$. $r_0$ - Fried parameter characterizing the scale of turbulence.

Of course, positioning the telescope above the atmosphere (for example, the Hubble Space Telescope) eliminates the issue of atmospheric interference, but this is a very costly way to improve image quality. In the 1970s, French astronomer A. Labeyrie proposed the method of speckle interferometry to enhance angular resolution of large ground-based telescopes, which gained prominence. This method involves statistically processing very short exposures ($\tau \sim 0.01$ sec, where $\sigma_{v}$ is the dispersion of turbulent speeds), during which the diffraction image does not "smear" due to the atmosphere (compare to the twinkling of stars!) (See Figure 3.60). In a single speckle image (upper panel of the illustration), distinct images of a binary star ("speckles") are clearly visible. Their count can be approximated by $\langle N \rangle$. If successive speckle images are summed (in the middle of the figure, 128 speckle images are combined), increasing the exposure time, the random phase variations of individual diffraction images will result in the destructive interference blurring the image (middle of the illustration). However, simple mathematical processing of a single speckle image allows for the reconstruction of the original picture (lower part of the illustration). For instance, the lower part of the illustration shows the autocorrelation function from the upper speckle image, clearly exhibiting the main star (a large peak) with diffraction resolution $\theta$ and a companion star of lesser intensity (a small peak on either side of the larger one; edge peaks are artifacts from the processing procedure).

![Figure 3.60](https://images.astronet.ru/pubd/2002/05/14/0001176797/3lec/img160.gif)  
**Figure 3.60** A speckle image of a binary star (top), the sum of 128 speckle images (middle), and the autocorrelation function of a single speckle image, where the duality of the source is clearly visible.

Successful speckle interferometry depends on two conditions: 1) short exposures ($\tau \ll \tau_0$, where $\tau_0$ is the characteristic time of turbulent fluctuations) and 2) a narrow enough bandwidth from the receiver to remain within the zone of coherence. The interference pattern from sources with finite angular sizes will be observable if the angular diameter of its image is less than the ratio of coherence length to the telescope diameter.

**Example**: For a star with an angular diameter $\theta_{0} \sim 0{''}.001$, at a wavelength $\lambda \approx 5000$ A, using a telescope with diameter of $D = 1$ m, speckle interferometry can be applied (for instance, measuring the angular diameter of this star or the angular distance between two closely spaced stars) already with a receiver bandwidth of $\Delta \lambda \approx 100$ A.

### 3.4.3 Adaptive Optics
Another method to counteract atmospheric turbulence is through the use of *adaptive optics*. Adaptive optics refers to optical devices that mechanically adjust their parameters to compensate for wavefront distortions caused by atmospheric turbulence and other factors. In astronomical instruments, special deformable mirrors approximately 20 cm in diameter are employed, with the surface shape changing during exposure. The number of feedback sensors deforming the mirror (referred to as "activators") is approximately determined by the requirement 

$$D \leq \frac{\lambda}{r_0},$$

and for controlling the wavefront shape, either a bright reference star is used or (in the absence of bright stars near the observed object) an "artificial star" is created, i.e., by illuminating a section of the sky with a powerful laser pulse tuned to resonate with the transition frequency of sodium atoms. The glow occurs at altitudes of around 90 km.

### 3.4.4 Photon Statistics. Shot Noise and Wave Noise
Consider a stationary light source detected by a detector with an average flow rate of 

$$\langle N \rangle = 1 \text{phot/sec},$$ 

accounting for the detector's area. In optical and shorter wavelength ranges, the probability of registering $\Delta N$ quanta over a time $\Delta t$ conforms closely to the Poisson statistic.

$$(3.12) \quad p(n, t) = \frac{(\langle N \rangle t)^{n}}{n!} e^{-\langle N \rangle t}$$

For photonic detectors experiencing shot noise, the variance is given by 

$$(3.13) \quad \sigma_{n}^{2} = \langle N \rangle t,$$

where $\alpha \ll 1$. In addition to shot noise, we can also have wave noise, which may represent another source of fluctuation:

$$(3.14) \quad \sigma_n \propto \sqrt{\langle N \rangle} t.$$

Thus, photon statistics, including effects of shot noise and wave noise, are essential considerations in precision measurements in astrophysics.## 3.5 About the Accuracy of Light Flux Measurements

The primary task of any astronomical observation is not only to *detect* a source but also to *measure* the flux of radiation. To register a source, it is sufficient to differentiate it from the background noise, taking a predetermined signal-to-noise ratio as a quantitative criterion. Measuring any physical quantity (such as flux or intensity) requires the specification of the accuracy with which we want to measure that quantity. Naturally, the higher the measurement accuracy, the better it is. In astronomical observations, the energy of photons collected by the telescope over the exposure time is converted by the detector into other forms of energy and ultimately output as digital data (for example, as the number of photoelectrons per second in a photomultiplier tube). These counts are then calibrated, establishing a definitive correspondence between the detector’s counting rate and the incoming photon flux in a specific energy range.

The importance of increasing the accuracy of light flux measurements from astronomical sources is illustrated by the following example. There exists a numerous class of astrophysical objects that are intensively studied—close binary stars, where one of the stars approaches the tidal stability limit due to its proximity to the other (it is said to be close to filling the Roche lobe). Under the influence of tidal forces, matter from this star can flow onto the other one. The shape of the star, distorted by these tidal forces, differs from a spherical form, gravitational forces on different parts of the surface vary, and the outgoing radiation flux fluctuates depending on the angle from which we observe this star (the so-called ellipsoidal effect). Thus, as the star orbits around the common center of mass, the observed flux will be modulated at a level of about $\sim 2\%$ due to this effect. To detect this modulation (and consequently measure the orbital period and other physical characteristics of the system), observations must be made with an accuracy better than $2\%$. By the end of 1999, high-precision photometry methods had already detected planets around nearby stars.

During the exposure time, the telescope collects photons from both the source and background photons (such as light scattering in the atmosphere, atmospheric glow, photons from the interstellar medium, etc.). The background sky during the exposure can be considered constant; we will characterize its intensity with the value $B$ [quanta/cm$^2$/s/ster]. A typical value in the blue-green (B) region is 21.5 magnitudes per square arcsecond, which corresponds to 

$$B \approx 2.5 \times 10^{-6} \text{ quanta/cm}^2/\text{s/\AA/arcsec}.$$

The background light increases in the red region due to the glow of atmospheric molecules.

Let’s consider an ideal ($\eta = 1$) receiver. Let $t$ be the exposure time, $\theta$ be the angular size of the image (usually atmospheric), $D$ be the aperture of the telescope, $B$ be the brightness of the night sky [quanta/cm$^2$/s/ster], and $S$ be the flux from the source [quanta/cm$^2$/s].

The number of background quanta hitting the detector during the exposure is:

$$N \approx D^{2} B t.$$

### Case A: Bright Star, $S \gg B$

Then 

$$N_{*+} = D^{2}t(n_{*} + \beta^{2} S) .$$ 

**Example**: What is the maximum stellar magnitude observable with a photometer (quantum efficiency $Q$) on a 6m telescope with an exposure time $t = 10$ sec and an accuracy of $1\sigma$? 

To find this, we can derive that:

$$m_{lim} \approx 2.51 \, g \frac{10^{6}}{1.5 \times 10^{-3}} \approx 21 \, m.$$

### Case B: Faint Object, $n_{*} < n_{\phi}$

We have:

$$\epsilon_{f} = \frac{\sqrt{2N}}{N^{*}} = \frac{\sqrt{2D^{2}\beta^{2}St}}{D^{2}n_{*}t} = \frac{\beta}{D n_{*}} \sqrt{\frac{2S}{t}}.$$

**Example**: Determine the limiting stellar magnitude in Moscow when observing with a 1m telescope. For limiting visibility, assume relative accuracy $\epsilon = 0.1$. The background sky brightness on the best nights is 19 quanta/sq. sec due to significant light pollution. 

Notice that the limiting stellar magnitude is significantly different (about ten times lower in flux) from that of the night sky background!

The information provided here will help us understand whether stars can be observed with the naked eye during the day from the bottom of a deep well. For the answer, it is sufficient to realize that the background sky brightness per unit area and the resolving power of the eye do not depend on where we conduct the observations. Would the answer change if we take a telescope instead?### 3.5 On the Accuracy of Measurements

1. Physics of the Cosmos, Little Encyclopedia, ed. R.A. Sunyaev, Moscow: Soviet Encyclopedia, 1986.

2. M. Longair. High-Energy Astrophysics. Chapters 6-7. Moscow: Mir, 1984.

---

**Publications with Keywords:**  
[Stars](http://db/search.html?kw=13809) - [Interstellar Medium](http://db/search.html?kw=14142) - [Cosmology](http://db/search.html?kw=15891) - [Theoretical Astrophysics](http://db/search.html?kw=10526) - [Astrophysics](http://db/search.html?kw=16508)  

**Publications with Words:**  
[Stars](http://db/search.html?words=%E7%E2%E5%E7%E4%FB) - [Interstellar Medium](http://db/search.html?words=%CC%E5%E6%E7%E2%E5%E7%E4%ED%E0%FF%20%F1%F0%E5%E4%E0) - [Cosmology](http://db/search.html?words=%CA%EE%F1%EC%EE%EB%EE%E3%E8%FF) - [Theoretical Astrophysics](http://db/search.html?words=%F2%E5%EE%F0%E5%F2%E8%F7%E5%F1%EA%E0%FF%20%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0) - [Astrophysics](http://db/search.html?words=%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0)  

---

**See also:**

- ![APOD](http://images.astronet.ru/si/apod.gif) [Black Hole Destroys Star: Animation](http://db/msg/1931410)  
- ![APOD](http://images.astronet.ru/si/apod.gif) [Stars, Dust, and Nebula in NGC 6559](http://db/msg/1904844)  
- ![APOD](http://images.astronet.ru/si/apod.gif) [25 Brightest Stars in the Night Sky](http://db/msg/1863796)  
- ![APOD](http://images.astronet.ru/si/apod.gif) [Animation: Black Hole Destroys Star](http://db/msg/1736616)  
- ![APOD](http://images.astronet.ru/si/apod.gif) [Decomposition of Distant Light](http://db/msg/1696356)  
- ![APOD](http://images.astronet.ru/si/apod.gif) [Comparison of Star Sizes](http://db/msg/1415428)  
- ![APOD](http://images.astronet.ru/si/apod.gif) [The Farthest Known Star?](http://db/msg/1406555)  

[All publications on the same topic >>](http://db/search.html?kw=13809&kw=14142&kw=15891&kw=10526&kw=16508)  

---

**Reader Opinions** [70]

**Rating:** 3.1 [votes: 182]  
Rating: 
- [Excellent]
- [Good]
- [Average]
- [Poor]
- [Unsatisfactory]

---

[Print Version](http://db/print/msg/1170612/3lec/node7.html)  

**Categories:**  
- **[Astrometry](http://db/sect/300000007)**  
- **[Astronomical Instruments](http://db/sect/300000010)**  
- **[Astronomical Education](http://db/sect/1168516)**  
- **[Astrophysics](http://db/sect/300000003)**  
- **[History of Astronomy](http://db/sect/300000016)**  
- **[Space Exploration](http://db/sect/300000012)**  
- **[Amateur Astronomy](http://db/sect/300000013)**  
- **[Planets and Solar System](http://db/sect/300000005)**  
- **[The Sun](http://db/sect/300000004)**  ## 4. Interstellar Medium

The interstellar medium (ISM) is a crucial component of the Galaxy, second only to stars. The interstellar gas, primarily consisting of hydrogen, makes up slightly less than $10\%$ of the mass of the Galaxy, yet its role is immensely significant. The percentage of gas in the total mass of the galaxy is one of its key characteristics and determines the rate of star formation. Most gas is found in irregular and spiral galaxies, where new stars are constantly being born. For instance, the average star formation rate in our Galaxy is about 1 solar mass per year. There are galaxies with high star formation rates, several times above this average. In contrast, elliptical galaxies contain the least gas. They are mainly populated by low-mass, slowly evolving main-sequence stars of spectral classes G, K, and M, with almost no gas present (except in the central regions), resulting in very few new stars being formed.

In spiral and irregular galaxies, cold massive gas-dust complexes create suitable conditions for the development of Jeans instability, leading to star formation. As stars evolve, they lose mass through stellar winds, primarily due to radiation pressure on the rarefied plasma in the atmospheres of stars, mainly in lines of heavy elements, and by heating the corona to high temperatures via shock waves. Ultimately, during the formation of compact remnants (when the star sheds its outer layers as a planetary nebula for stars of moderate mass and as a supernova explosion for stars more massive than 10 solar masses), a constant cycle of gas-stars-gas occurs. In this process, the total mass of gas gradually decreases, as some baryons remain in the form of compact remnants (white dwarfs, neutron stars, black holes), while others are expelled into intergalactic space.

Components of the interstellar medium also include interstellar dust (about $1\%$ by mass), interstellar magnetic fields, cosmic rays, and electromagnetic radiation from stars.

### Main Observational Manifestations of the Interstellar Medium:

1. Presence of luminous nebulae of ionized hydrogen (HII) surrounding hot stars and reflective gas-dust nebulae.

2. Weakening of starlight (interstellar absorption) in continuous spectra and individual lines, as well as reddening of light (selective absorption by dust).

3. Polarization of light due to scattering on electrons and dust particles in the interstellar medium, aligned along the large-scale magnetic field of the Galaxy.

4. Radio emission from neutral hydrogen (HI) at a wavelength of 21 cm.

5. Cosmic masers, arising from molecules such as H$_2$O, OH, methanol, etc., in dense cold star-forming regions.

6. Synchrotron radiation from relativistic electrons in interstellar magnetic fields (the electron component of cosmic rays, which are accelerated at shock fronts arising in the interstellar medium during supernova explosions).

7. Infrared radiation from interstellar dust.

8. Soft X-ray emission from hot regions heated by shock waves during supernova explosions and from the outflow of powerful stellar winds from young massive O and B stars (coronal gas).

The interstellar medium was discovered in 1904 by Hartmann, who observed stationary absorption lines in the spectra of binary stars to check the Doppler effect. Knowing the orbital period, one can determine the speed of the components and thus pre-calculate the amplitude of the displacement of absorption lines in the atmospheres of moving stars. By 1938, absorption lines from many interstellar molecules (CH, CH$_2$, CN, C$_2$, NH) had been identified. However, the presence of these molecules does not accurately reflect the true chemical composition of the interstellar medium—heavy elements (Fe, etc.) constitute solid interstellar dust grains, while the most abundant elements, neutral and molecular hydrogen and helium, are not observed in the optical range. The first cosmic maser was discovered in 1965 in the OH molecule (at 18 cm). In 1973, a specialized UV satellite, "Copernicus", discovered a large number of lines from various interstellar molecules, among which the line H$_2$ 1108 Å is of particular importance.

The interstellar medium exhibits a complex structure, comprising separate compact formations, cold and warm clouds surrounded by hot gas. The main components of the interstellar medium in the spiral arms of the Galaxy and their physical states are summarized in the Table 1.

---

### Table 1. Main Components of the Interstellar Medium

| Phase                      | T (K)    | n (cm$^{-3}$)  | Mass (M$_\odot$) | Size (pc) | Volume Fraction |
|---------------------------|----------|----------------|------------------|-----------|------------------|
| Coronal Gas               | $10^6$  | $-3$           | -                | -         | $\sim 0.003$     |
| Low Density HII Regions   | $10^4$  | $-3$           | -                | -         | $\sim 0.5$       |
| Intercloud Medium         | $10^4$  | $-3$           | -                | -         | $\sim 0.3$       |
| Warm HI Regions           | $10^4$  | $-3$           | -                | -         | $\sim 0.1$       |
| HI Clouds                 | $10^4$  | $-3$           | $\approx 10^3$   | $\sim 10$ | $\geq 100$       |
| Dark Clouds                | $10^4$  | $-3$           | -                | -         | $\sim 10^{10}$   |
| Globules                  | $10^4$  | $-3$           | -                | $\sim 30$ | $\sim 3 \cdot 10^{-9}$ |
| HII Regions               | $10^4$  | $-3$           | $\approx 10$     | $\sim 300$ | $\sim 10^{-5}$   |
| Giant Molecular Clouds     | $10^4$  | $-3$           | $\sim 3 \cdot 10^{5}$ | -     | $\sim 20$       |
| Maser Condensations       | $10^4$  | $-3$           | -                | -         | -                |

--- 

This gives a comprehensive overview of the interstellar medium, its components, properties, and observational manifestations relevant to the study of astrophysics.## 4.1 Physical Characteristics of Cosmic Plasma

The primary feature of the physical state of the interstellar medium (ISM) is its extremely low density. Typical values are between 0.1 and 1000 atoms per cubic centimeter, and with characteristic molecular speeds around 10 km/s, the collision time between individual particles can reach tens or even thousands of years. This timescale far exceeds the characteristic lifetimes of atoms in excited states (on allowed levels, around $10^{-8}$ seconds). Consequently, a photon absorbed by an atom has sufficient time to be re-emitted from the excited level, and the probability of true absorption of non-ionizing quanta by ISM atoms (where the energy of the absorbed photon converts into kinetic energy of random particle motion) is extremely low.

The absorption line becomes distinguishable against the background of the continuous spectrum (the continuum) at optical thicknesses in the center of the line of the order of $\tau_{\nu_0} \sim 0.1 - 1$. The absorption cross-section $\sigma(\nu)$ is related to the optical thickness by the relation 
$$\tau_\nu = \int \sigma(\nu) n \, ds$$ 
where $N = \int n \, ds$ is the number of atoms along the line of sight. Since the absorbing atom in the line can be modeled as a damped harmonic oscillator, both classical and quantum mechanical calculations yield the profile of the absorption cross-section:

$$\sigma(\omega) = \sigma_{\text{max}} \frac{(W/2)^{2}}{(\omega - \omega_{0})^{2} + (W/2)^{2}}$$

where $$\sigma_{\text{max}} = \frac{\lambda^2}{\pi}$$ and $$\lambda = \frac{2\pi c}{\omega_0}$$. Under typical conditions, $\lambda \sim 3000 - 7000$, leading to estimates of $\sigma(\nu_0) \sim 10^{-12} - 10^{-13}$.

## 4.1.1 Absence of Local Thermodynamic Equilibrium

The transparency of the ISM for radiation is determined by a crucial physical property of interstellar plasma — the absence of **Local Thermodynamic Equilibrium (LTE)**. Recall that under conditions of **complete thermodynamic equilibrium**, all forward and reverse processes occur at the same rates (the so-called principle of detailed balance), and there exists only one temperature value that defines the physical state of the medium (local TDE means that detailed balance exists and maintains TDE at every point, but the temperature is a function of spatial coordinates and time).

The LTE approximation works well in cases of high optical thickness (for example, in the interiors of stars), where non-LTE effects become significant only for $N_e \sim 10^{19}$ particles per cubic centimeter (for example, in the photospheres of stars, from which photons escape freely into space).

In the interstellar medium, the concentration of atoms is low, with $n \sim 10^{-6}$ particles per cubic centimeter; thus, the optical thickness is small, and LTE is not satisfied. This is because (a) the radiation temperature in the ISM (primarily from starlight) is high, around $T \sim 5000$ K, while the electron and ion temperatures of the plasma are determined by particle collisions and can differ significantly from the radiation temperature. The distribution of atoms and ions among energy levels is determined by the balance of ionization and recombination processes; however, unlike in LTE, the principle of detailed balance does not hold. For instance, in the **coronal approximation** (the limit of low particle density, a term derived from the physical state of plasma in the solar corona), atom ionization occurs via electron collisions, while energy de-excitation occurs through spontaneous radiative transitions. In HII regions and quasars, gas is ionized by the hard UV radiation from the central source, and the populating of levels is determined by radiative recombination processes. In these examples, direct and reverse elementary processes have different natures, making conditions far from equilibrium. However, even in very rarefied cosmic plasma, the Maxwellian distribution of electron velocities establishes (with their temperature) in a timescale much shorter than the characteristic time between particle collisions, owing to the long-range nature of Coulomb forces; thus, for the distribution of particles by energy, one can use the Boltzmann formula.

## 4.1.2 Frozen-in Magnetic Field

A crucial component of the ISM that largely determines its dynamics is the large-scale magnetic field of the galaxy. The average magnetic field strength in the Galaxy is about $B \sim 10^{-8}$ G. In conditions of cosmic plasma, the magnetic field is overwhelmingly often **frozen into** the medium. The frozen-in condition means the magnetic flux through a closed conducting contour remains constant during its deformation:

$$\int_{S} B \, dS = \text{const}$$
In laboratory conditions, the preservation of magnetic flux occurs in media with high conductivity $\sigma$. However, in cosmic plasma conditions, the larger characteristic sizes of the contours considered and, consequently, the longer timescales for magnetic field decay compared to the studied process timescale become significant. To demonstrate this, consider a volume of plasma $V$, where currents with a density $j$ flow. According to Maxwell's equations, these currents generate a magnetic field:

$$\text{rot} \mathbf{B} = \frac{4 \pi}{c} \mathbf{j}$$
Current in the plasma with finite conductivity decays due to Joule losses associated with collisions between electrons and ions. The heat generated in a unit of time in a unit volume of plasma is given by $q = j^{2}/\sigma$. The magnetic energy per unit volume is given by $\frac{B^2}{8\pi}$. Therefore, the characteristic time for the dissipation of magnetic energy into heat (and the corresponding decay of the field) in a volume with a characteristic size $L$ is defined as:

$$t_d = \frac{E}{\frac{dE}{dt}} \sim \frac{B^2/8\pi}{j^2/\sigma} \sim \frac{2\pi\sigma}{c^2}R^2$$

This frozen-in condition is a good approximation in virtually all astrophysical situations (even during the dynamic processes of stellar core collapse due to short characteristic times). However, on small scales, this approximation may not hold, especially in regions of sharp field variations, characterized by sudden turns of magnetic field lines.

## 4.1.3 Forbidden Lines

A distinctive feature of radiation arising in an optically thin sparse medium is the emission of radiation in **forbidden lines** of atoms. Forbidden spectral lines are those that occur during transitions in atoms from metastable levels (i.e., forbidden by selection rules for electric dipole transitions). The characteristic lifetime of an atom in a metastable state ranges from $10^{-5}$ seconds to several days or longer. High particle concentrations (e.g., $N_e \sim 10^{9}$ in Earth's atmosphere, or $\sim 10^{16}$ cm in the solar photosphere) lead to collisions that depopulate the excited states of atoms, causing forbidden lines not to be observed.

To illustrate, consider a line resulting from a transition from level $N_1$ to level $N_2$ with a transition probability $A_{kk'}$ (the number of transitions per unit time) emanating from a volume $V$ of optically thin plasma. The luminosity in the line is given by:

$$L_{kk^*} = N_k V A_{kk} E_{kk^*} = V N_H n_2 \alpha(X) A_{kk} E_{kk^*}$$ 

where $E_{kk'} = h \nu_{kk'} = E_{k} - E'_{k}$. The relative concentrations can be expressed as:

$$n_z = \frac{N(X, z)}{N(X)} \quad \text{and} \quad n_k = \frac{N_k(X, z)}{N(X, z)}$$

where $\hat{z}$ is taken along the line of sight. The relative abundance of species $X$ can then be expressed as $\alpha(X) = \frac{N(X)}{N_H}$, leading to:

$$L_{kk'} = V N_H N_e \alpha(X) n_{z} q_{0} \left( \frac{A^{kk'}}{A_k} \right) E_{kk'} \exp\left(-\frac{E_{0k'}}{k T}\right)$$

The condition $L \sim N_H N_e \sim N_e^2$ and 

$$\left( \frac{A_{k} k'}{A_{k}} \right)$$ 

is an important aspect of this process.

In regions of low density, the situation changes. Consider the **coronal approximation** again, where atom ionization occurs solely through electron collisions. Under a Maxwellian distribution of velocities, the fraction of electrons with sufficient energy to excite level $N_1$ of the atom is significant. The rate of collision leading to excitation is given by

$$\Gamma = C_n [\text{cm}^{-3}/c]$$ 

where $C$ is a coefficient dependent on the temperature and density of electrons.

The total probability of radiative decay from this level to others can be expressed as:

$$\Gamma_{\text{decay}} = \sum_i A_{ki}$$ 

Considering the balance between excitation and decay gives us the relative population:

$$n_k = \frac{N_k}{N_e}$$ 

This relative population ultimately influences the line strengths observed in various astrophysical contexts. For instance, the most prominent forbidden lines occurring in planetary nebulae and HII regions around hot stars include the doublet of doubly ionized oxygen [OIII] at $4959$ A and $5007$ A, as well as UV lines of singly ionized oxygen [OII] and ions like SII, NII, among others. By comparing the intensities of these lines, one can determine the electron temperature of the gas in planetary nebulae, as the relative population of these levels is temperature-dependent.

The emission lines in the spectrum of the solar corona were interpreted as forbidden emissions from atoms of Fe, Ni, and Ca that had been ionized multiple times (12 to 15 times) only in 1942. The temperature of the corona is several million degrees Kelvin, resulting in a very high ionization level among heavy ions, with hydrogen-like and helium-like iron atoms present. The most characteristic forbidden line in the optical spectrum of the solar corona is the green line of [FeXIV] at $5302.86$ A. In the X-ray spectrum of the corona, one can observe both forbidden and resonance lines, the latter showing similar intensity, even though the degree of forbiddenness can increase significantly with the charge state of the ion.## 4.2 The 21 cm Neutral Hydrogen Radio Line

The most significant forbidden line in the Cosmic Microwave Background (CMB) is the 21 cm radio line of neutral hydrogen. This line arises from transitions within the hyperfine structure of the hydrogen atom, which is associated with the spins of the electron and proton. The upper sublevel corresponds to the parallel spins of the electron and proton, while the lower sublevel corresponds to their antiparallel spins, with the transition frequency being $\nu = 1420.40$ MHz. It was theoretically predicted by van den Hulst (Netherlands) in 1944 and independently calculated by I.S. Shklovsky in 1949. The line was detected in 1951 and remains one of the primary radio lines for studying neutral hydrogen in our galaxy and others.

The transition is magnetically dipole allowed with a probability of $A_{10} = 2.9 \times 10^{-15}$, occurring approximately once every 11 million years. The excitation temperature of this transition is given by 

$$ T_{10} \approx 0.068 \, K. $$ 

Excitation occurs through collisions between neutral hydrogen atoms at a kinetic temperature $T \gg T_{10}$. Calculating the level populations gives:

$$ n_{1} = \frac{n_{H}}{4}, \quad n_{2} = \frac{3n_{H}}{4}, $$ 

where $n_{H}$ is the density of hydrogen atoms.

Let's calculate the intensity of the neutral hydrogen emission line in the case of small optical thickness. For the emission in this line, induced emission is crucial. The transfer equation accounting for induced emission is given by

$$\frac{dI_{\nu}}{ds} = \epsilon_{\nu} + \epsilon_{\nu}^{ind} I_{\nu} - a_{\nu} I_{\nu,$$

where $\epsilon_\nu$ is the emission coefficient and $a_{\nu}$ is the absorption coefficient.

The solution for a homogeneous cloud leads to the equation 

$$\frac{dI_{\nu}}{d\tau_{\nu}} = S_{\nu} - I_{\nu}, $$ 

with 

$$d\tau_{\nu} = \tilde{a}_{\nu} ds, \quad \tilde{a}_{\nu} = a_{\nu} \left(1 - \frac{\epsilon^{ind}_{\nu}}{a_{\nu}} \right).$$ 

Hence, the source function is expressed as 

$$S_{\nu} = B_{\nu}(T_{s}), $$ 

where $B_{\nu}$ is the Planck function.

For thermal radiation, we can describe the intensity as 

$$I_{\nu} = B_{\nu}(T)(1 - e^{-\tau_{\nu}})$$ 

or in the case of optically thick conditions (large $\tau_\nu$):

$$I_{\nu} = B_{\nu}(T_{b}) \simeq \frac{2k T_{b}}{\lambda^{2}}. $$ 

For an optically thick neutral hydrogen cloud, where $\tau_\nu \gg 1$, one derives 

$$T_b(\nu) = T_s(1 - e^{-\tau_\nu}) = T_s(\tau_\nu \gg 1); \quad \approx T_s \tau_\nu (\tau_\nu \ll 1). $$ 

Under the condition of weak absorption, we find that 

$$\tilde{a_{\nu}} = a_{\nu} \left(1 - e^{-h \nu_{10}/k T_{s}} \right) \simeq a_{\nu} \frac{h \nu_{10}}{k T_{s}}.$$

Considering the escape of radiation through the medium, we rewrite the optical depth as 

$$\tau_{\nu} = \int \bar{a}_{\nu} dl = \int a_{\nu} \frac{h\nu_{0}}{kT_{s}} dl = \int \frac{\sigma(\nu) n_{H}}{4} \frac{h\nu_{0}}{kT_{s}} dl.$$

In terms of the brightness temperature, we have 

$$kT_b = kT_s \tau_\nu = \int \frac{\sigma(\nu)n_H}{4} h\nu_{10} dl \propto \int \epsilon_\nu dl,$$ 

yielding an approximate temperature of 

$$\approx 220 \, K.$$

Research on the 21 cm line has established that neutral hydrogen in the galaxy is primarily confined within a very thin ($< 1 \, pc$) and uniform layer near the Galactic plane. At the periphery (10-12 kpc) from the center, this layer bends, and its thickness increases to about 1 kpc. The distribution of HI distinctly marks the spiral arms of the galaxy. Inside these arms, hydrogen is unevenly distributed, forming extended complexes with scales on the order of 20-80 pc. The Zeeman splitting of the absorption components of the 21 cm line in the presence of strong radio sources is utilized to estimate the magnetic field within the clouds.

Additionally, HI emission is observed from many other galaxies, and its shine is used to determine the mass ratio of neutral hydrogen to the total mass of a galaxy while its rotation helps estimate the mass of the galaxy itself.

It’s important to note that other chemical elements also exhibit hyperfine splitting of their ground state; however, attempts to detect corresponding (weak) lines so far have not been successful.### 4.3 Clouds of Neutral Hydrogen (H I) and Thermal Instability of the Interstellar Medium

Observations show that neutral hydrogen does not uniformly fill the interstellar medium (ISM) but primarily exists in two phases: relatively dense clouds of cold neutral hydrogen at temperatures around $T \sim 100$ K and a more diffuse inter-cloud medium at temperatures around $T \sim 10^4$ K. This distribution is a consequence of the thermal instability of the ISM caused by a non-monotonic relationship between pressure and matter density $P = n k T$ in the context of the ISM.

<center>
![](./imgs/019b98cac56947f4976742fde70126e3_img174.png)

**Figure 4.3**: Thermal instability of the ISM. The section of the curve with a negative derivative corresponds to an unstable state.
</center>

Qualitatively, the effect manifests as follows. The ISM behaves like an ideal dilute gas with a pressure proportional to density. The temperature of the medium is determined from the solution of the thermal and ionization balance equations. Consequently, the pressure-density dependency in the ISM is non-monotonic, with portions where pressure increases with density and regions where it decreases. This results in a pressure range where a single pressure value corresponds to three solutions of the thermal, ionization, and hydrostatic equilibrium equations with different densities $n$ and temperature $T$. Solution 2, existing in the section where pressure decreases with increasing density, is unstable to small perturbations. A fluctuation with density below the equilibrium will exhibit higher pressure and thus will expand until it reaches the equilibrium state (Solution 1). Conversely, a fluctuation with a density above the equilibrium will have lower pressure than the equilibrium and will compress until it attains the equilibrium at higher density (Solution 3).

### 4.3.1 Volumetric Heating and Cooling of the ISM

The transparency of the ISM to electromagnetic radiation and high-energy charged particles (cosmic rays) defines the specifics of gas heating and cooling. Energy released in any region of space is carried away by electromagnetic quanta, leading to a cooling effect throughout the volume. For characterizing cooling, we use the volumetric cooling coefficient $\Lambda$ [erg/cm$^3$s]. Thermal conductivity is ineffective in transferring heat from distant energy sources; thus, heating is determined by processes that warm the medium over larger areas. The volumetric heating coefficient $\Gamma$ [erg/cm$^3$s] characterizes heating, and we have, in thermal equilibrium:

$$\Lambda = \Gamma.$$

**Main Heating Mechanisms:**
1. **Ultraviolet Radiation from Stars (Photoionization)**: A photon with energy $E = h\nu$ ionizes an electron from an energy level, imparting kinetic energy, which transforms into the chaotic motion energy of particles, thereby heating the gas.

2. **Heating via Shock Waves**: Shock waves occur during various processes at supersonic speeds (about 1 km/s in the ISM), such as during shell ejections from stars in supernova explosions or cloud collisions. Behind a shock front, kinetic energy of directed motion converts into chaotic energy, achieving extremely high temperatures (up to billions of K in remnants of supernovae).

3. **Volumetric Heating by Penetrating Radiation and Cosmic Rays**: Heating occurs during Coulomb interactions of charged particles with the medium, including secondary free electrons formed by ionization.

4. **Volumetric Heating by Hard Electromagnetic Radiation (X-rays and Gamma Quanta)**: This occurs mainly through secondary electrons during photoionization and Compton scattering.

<center>
![](./imgs/019b98cac56947f4976742fde70126e3_img174.png)
</center>

**Note**: The processes of volumetric heating are proportional to particle density and the flux of ionizing radiation, which means the total volumetric heating rate can be expressed as:

$$\Gamma(n, T) = n G(T),$$

where $G(T)$ depends solely on temperature and chemical composition and is calculated through elementary interaction processes of radiation and matter.

**Key Cooling Mechanisms:**
Almost invariably, volumetric cooling of the ISM occurs via photons, for which the medium is transparent. Thermal conductivity is ineffective due to small temperature gradients over large volumes, except at shock wave fronts or phase boundaries with sharply differing temperatures. Photon emission is associated with binary collision processes among particles, proportional to the square of density.

1. **Free-Free (Bremsstrahlung) Radiation**: This arises when an electron moves within the field of an ion, resulting in continuous spectra.

2. **Recombination Radiation**: During radiative recombination, the kinetic energy of a recombining electron is low, thus the emitted photon carries energy predominantly corresponding to internal energy of the ion formed without affecting the thermal energy of the surrounding medium.

3. **Other Continuous Spectra Radiation Processes**: 
   a) **Two-Photon Emission**: This occurs during the radiative decay of metastable levels in hydrogen and hydrogen-like ions, producing a continuous spectrum with wavelengths longer than the Lyman-alpha line.
   
   b) **Inverse Compton Scattering**: This can increase the energy of low-frequency photons when they scatter off high-energy electrons, converting them to higher-energy quanta.

This framework helps explain the observed stratification of H I regions into cold clouds and a warmer intercloud medium, highlighting the interplay between heating and cooling mechanisms in astrophysical contexts. To find the equilibrium temperature of the medium, it is necessary to jointly solve the equations of ionization balance, considering the population levels of atomic and ionic species within the ISM.## 4.4 Ionized Hydrogen and HII Regions

Hydrogen is the most abundant element in the Universe. The ionization potential of hydrogen from its ground state is approximately $13.6$ eV, which means that hydrogen can be ionized by photons with energies greater than this threshold. This corresponds to radiation wavelengths shorter than the Lyman limit of $\lambda(L_{yc}) = 912$ Å, or about $\nu_c \approx 3.29 \times 10^{15}$ Hz. 

In addition to ionization by photons, there is also the possibility of ionization through electron collision. Formally, the "ionization temperature" corresponding to the energy $13.6$ eV is very high—around $158,000$ K. However, hydrogen becomes fully ionized at significantly lower temperatures, starting around $3000$ K, with complete ionization occurring by about $10,000$ K. This is due to the fact that the relative concentration of ions is determined by the ionization equilibrium in plasma, which reflects a dynamic balance between ionization and recombination processes. 

It is important to note that during collisions between an electron and an ion, the probability of ionization is substantially higher than the probability of recombination. As a result, the maximum of the function $n_z(T)$ is reached at a temperature where the fraction of electrons with sufficient energy to ionize an atom is relatively low. As the charge of the ion $Z$ increases, the ratio $\chi_z / k T$ decreases. The excitation and ionization of atoms necessary to maintain the ionization equilibrium occur via electrons with energies $\epsilon \gg kT$, implying an exponentially small fraction of high-energy electrons from the "tail" of the Maxwellian distribution. Under local thermodynamic equilibrium conditions (for instance, in stellar atmospheres), the equilibrium degree of ionization of ions is determined using the Saha formula.

HII regions are very common types of emission nebulae surrounding hot stars, characterized by complete ionization of hydrogen due to UV radiation with wavelengths shorter than $912$ Å. Bright giant HII regions, which are clearly visible in other galaxies, serve as indicators of zones of active star formation, where many young, hot stars of early spectral classes exist. There may be so many UV photons that all the surrounding hydrogen in the star-forming region becomes ionized, leading to boundaries of HII regions that are diffuse and patchy, following the distribution of atomic hydrogen density. In many cases, however, the boundary of an HII region is sharply defined by the strength of the UV radiation from the central source.

The thickness of the transition zone is on the order of $0.1/N_e$ parsecs, which is hundreds of times smaller than the characteristic sizes of the nebula itself. This is due to the avalanche-like nature of the increase in optical thickness for photons with energies $h \nu < 912$ Å in the transition region.

The physical conditions in HII regions are far from thermodynamic equilibrium, and the ionization of elements is calculated based on the conditions of ionization equilibrium, mainly balancing photoionization and radiative recombination processes. The temperature of HII regions is determined by balancing heating from UV radiation (where part of the energy of the photon $E = h \nu - \chi$ is converted into kinetic energy of the electron freed during photoionization, which subsequently imparts this energy to other particles during further collisions) and cooling through forbidden lines of heavy elements like OII, OIII, and NII (where electrons expend thermal energy exciting metastable levels, and the emitted photon escapes the nebula, resulting in cooling).

Depending on the temperature of the central star, the temperature in HII regions is approximately $6000 - 10,000$ K.

The radius of a stationary HII region, bounded by radiation, is determined by equating the number of $L_{yc}$ photons per unit time emitted by the central star(s) with the number of recombinations of hydrogen per unit time across all levels above the first within the entire volume of the nebula:

$$
\frac{4}{3}R^3(\alpha_t - \alpha_1)N_e N_p = N_{Lyc}
$$

Next, we can make a numerical estimate of the number of $Lyc$ photons emitted by a star per unit time:

$$
N_{Ly\ c} = 4\pi R_{*}^2 \int_{3.3 \times 10^{15}}^{\infty} \pi F_{\nu} \frac{d\nu}{h\nu}
$$

Photons with wavelengths $\lambda < 504$ Å are capable of ionizing helium, so zones of HeII are observed around the hottest stars.## 4.5 Molecular Clouds, Star Formation Regions, and Cosmic Masers

Within the extensive regions of neutral hydrogen (HI), which have a characteristic density of $n_{HI} \simeq 10 \, \text{cm}^{-3}$ and a complex structure, there exist dense cold clouds of molecular hydrogen, referred to as giant molecular clouds with masses around $10^{5} M_{\odot}$ and characteristic sizes of 40 parsecs. All molecular gas is concentrated within these clouds, with a total mass in the Galaxy estimated at about $2 \times 10^{9} M_{\odot}$. These clouds represent the most abundant massive gravitationally bound objects in our Galaxy. Most of them are found in a ring at distances of 4 to 8 kpc from the Galactic center, appearing both in spiral arms and in between them. The clouds are inhomogeneous, containing cold condensations ($n \sim 100 - 1000 \, \text{cm}^{-3}$, $T \approx 10 \, \text{K}$, $l \sim 0.3 - 1 \, \text{pc}$), and even denser giant globules (Bok globules), which are visible as dark spots against the background of the Milky Way (for example, the Horsehead Nebula or Barnard 68), with masses reaching up to 100 $M_{\odot}$. Active star formation occurs within these dense regions.

In addition to the molecules $H_{2}$, over 100 different molecules can be found in molecular clouds. The most abundant molecule is carbon monoxide (CO). Its concentration is proportional to the amount of $H_{2}$ molecules: 

$$
\frac{n_{CO}}{g_{CO}} > \frac{n_{H2}}{g_{H2}}.
$$ 

Observing the $H_{2}$ molecule is challenging; however, other molecules can be detected through their infrared and radio emissions, which allow molecular clouds to remain transparent to these types of radiation.

**Cosmic masers (CM)** are non-thermal sources of radio emission, where the thermal emission of gas in the spectral lines of molecules is amplified due to the dominance of stimulated emission over absorption (analogous to laboratory lasers). They are characterized by high brightness temperatures and a high degree of polarization in their lines. The most well-known masers are observed in hydroxyl (OH) lines ($\lambda = 18 \, \text{cm}$, $T_b \sim 10^{13} \, \text{K}$), water (H$_2$O) ($\lambda = 1.35 \, \text{cm}$, $T_b \sim 10^{15} - 10^{16} \, \text{K}$), silicon monoxide (SiO) (2-7 mm, $T_b \sim 10^{10} \, \text{K}$), and methanol (CH$_3$OH) (1.2 cm). Maser sources are usually associated with star formation regions and consist of clusters of small (1-10 AU) components in nests with sizes around $10^{16} \, \text{cm}$. The total luminosity in a maser condensation can reach $10^{44} - 10^{51} \, \text{erg/s}$, and in the case of mega-masers (near active galactic nuclei), it can reach up to $10^{36} \, \text{erg/s}$. This implies that cosmic masers emit $10^{35}$ radio photons per second in a narrow spectral range. The concentration of gas particles in cosmic masers can reach $n = 10^{7} - 10^{11} \, \text{cm}^{-3}$, with masses roughly comparable to that of planets at about $10^{27} - 10^{30} \, \text{g}$, possibly representing protoplanetary condensations. Weaker cosmic masers are also found in areas where supernova shells interact with molecular clouds, as well as in circumstellar envelopes around old stars of late spectral classes (K, M) with strong mass outflows.

For cosmic masers to operate, similar to laboratory lasers, an inverted population of atomic levels (negative absorption coefficient) is necessary: 

$$
\eta < 1,
$$ 

where $g_{1,2}$ are the statistical weights of the transitioning levels. The high power of the emitted radiation arises from induced transitions from the upper signal level "2" to the lower one "1," stimulated by photons that are generated in the medium due to thermal energy (atom collisions, recombination). Induced emission occurs at the same frequency, with the same phase, and propagates in the same direction as the photon that caused it. Figuratively, continuous operation cosmic masers can be thought of as thermal machines that convert pumping energy from an external source into maser emission energy, with an efficiency coefficient.

The pumping and energy extraction in cosmic masers occurs either through radiative (R) or collisional (C) processes, or via chemical processes. In the latter case, a molecule is formed in an excited state, or a molecule in the lower signal level is destroyed during a chemical reaction. A laboratory example is the excimer lasers based on unstable compounds of noble gases such as He or Xe.

In R-extraction, it is crucial that the extracted photons exit freely from the maser source; otherwise, thermalization of the levels (Boltzmann occupancy) may occur. For collisional masers, energy pumping and extraction should take place with particles at different temperatures. Such out-of-equilibrium conditions are feasible in shock waves, where the temperatures of electrons and atoms (molecules) can significantly differ.## 4.6 Cosmic Rays and Synchrotron Radiation

Cosmic rays (CR) are high-energy charged particles (up to $10^{20}$ eV) that originate from interstellar space. They were discovered by the Austrian physicist Victor Hess in 1912. Cosmic rays resemble a highly rarefied relativistic gas where particles do not interact with each other but occasionally collide with particles of the interstellar medium (ISM) and interact with the interstellar magnetic field. Protons dominate the composition of cosmic rays, though electrons, helium nuclei, and heavier elements up to $Z \sim 30$ are also present. The flux near Earth is relatively low, about 1 particle/(cm²·s), yet the energy density $U_{cr} \sim 1$ eV/cm³ is comparable to the density of the total electromagnetic radiation from stars in the Galaxy, the thermal motion energy of the interstellar gas, and the kinetic energy of its turbulent motions, as well as the energy density of the Galactic magnetic field (known as the equipartition theorem, due to global stationarity). The CR spectrum follows a power law that is non-thermal, with a few characteristic breaks, and averages around an index of about 3 ($I(E) \sim E^{-3}$). CRs with energies less than $10^{19}$ eV arrive isotropically from all directions in the sky. This fact is interpreted as evidence of their galactic origin and their confinement by the magnetic field of the Galaxy. The flux of ultra-high-energy cosmic rays (above $10^{20}$ eV) is extremely low (about 1 particle/km per 100 years), yet these ultra-high-energy cosmic rays represent one of the mysteries of modern astrophysics and particle physics.

Cosmic rays interact when colliding with protons and nuclei of interstellar matter, with large-scale magnetic fields, and also with radiation.

1. **Relativistic Protons and Gamma Radiation**. Interaction with matter occurs through the strong interaction when a proton collides with a nucleus, as each nucleon is treated independently, because the de Broglie wavelength of the relativistic proton with energy $E \sim \gamma m_p c^2$ is much smaller than the size of the nucleus. During scattering on nucleons, secondary nucleons and charged pions are produced until the energy per particle falls below the threshold energy for multiple pion production (around 1 GeV). Thus, the initial energy of the cosmic ray particle is converted into the energy of pions, strange particles, and antinucleons (the so-called pionization process). Secondary protons then lose energy due to ionization and are decelerated to a complete stop. Neutral pions decay into 2 gamma quanta in a time $\tau_{\pi^{0}} \approx 8.4 \times 10^{-17}$ seconds. Charged pions decay into muons and muon neutrinos; the neutrinos escape, and the charged muons further decay into electrons, positrons, and neutrinos.

   The average energy of gamma quanta during the decay is about $E_{\gamma} \sim 70$ MeV. The total cross-section for the photoproduction process is on the order of the geometric cross-section of the proton or nucleus, on average $$\sigma_{\gamma} \approx 10^{-26} \text{ cm}^2$$. This process provides the main contribution to the gamma radiation of the Galaxy at energies above 100 MeV. At these energies, gamma radiation directly reflects the distribution of protons and cosmic rays in the Galaxy. Radiation is concentrated towards the Galactic disk and towards its center, predominantly associated with the photoproduction of pions during the interaction of cosmic ray protons with the nuclei of molecular hydrogen in giant molecular clouds.

2. A charged particle moving in a magnetic field experiences the Lorentz force; thus, in general, for an arbitrary direction of the particle's velocity vector concerning the magnetic field lines, the particle will move along a helical trajectory. In a uniform magnetic field with intensity $B$, its radius (the gyro-radius or Larmor radius) is determined by the field intensity and the particle's momentum $p$. For relativistic particles, energy and momentum are related by the equation $E = \gamma m c^2$, and the gyro-radius for a particle with charge $e$ can be expressed as:
   $$ r_g = \frac{E}{Z e B} \approx 3 \times 10^{13} \, \text{cm}^{-1} \left( \frac{E}{10^{3} \text{ eV}} \right) \left( \frac{B}{10^{-6} \text{ G}} \right)^{-1} $$

   The presence of a magnetic field has a significant effect on the electron component of cosmic rays. When a relativistic electron moves through a magnetic field, it produces **synchrotron radiation**. Unlike a non-relativistic electron (which shows magneto-drag radiation at the gyrofrequency $\omega_{g} = \frac{eB}{m_e c}$), a relativistic electron with energy $E \sim \gamma m_e c^2$ emits radiation across many frequencies (resulting in a continuous spectrum), with a peak near the frequency $$\nu_{max} \approx \frac{3}{2} \frac{eB}{2\pi m_e c} = \frac{eB}{m_e c} \sqrt{\frac{E}{m_e c^2}}$$.

   It is important to note that the curvature radius of the trajectory can be considered instantaneous, and for a relativistic electron with a large Lorentz factor $\gamma = 3 \times 10^{11}$, moving nearly along the magnetic field lines at light speed, what arises is called **curvature radiation**, connected to the intrinsic large-scale curvature of the magnetic field line. This radiation is particularly important in the magnetospheres of pulsars—neutron stars with a strong magnetic field of approximately $10^{12}$ G near the surface.

   For power-law distributions of relativistic electrons in energy ($N(E) \sim E^{-\beta}$), which are common in astrophysical conditions, the summed synchrotron spectrum has a power-law form $$I(\nu) \propto \nu^{-\frac{(\beta - 1)}{2}}$$. Another characteristic feature of synchrotron radiation is the high degree of linear polarization, which in a uniform magnetic field can reach up to $\Pi = \frac{(\beta + 1)}{(\beta + \frac{7}{3})}$. The direction of polarization is perpendicular to the projection of the magnetic field vector $B$ onto the image plane.

   The energy losses of relativistic electrons due to synchrotron radiation are proportional to the square of the particle's energy (Lorentz factor) and the energy density of the magnetic field $$ U_m = \frac{B^2}{8\pi} $$, as shown in the following equation:
   $$ - \left( \frac{dE}{dt} \right)_{s} = \frac{4}{3} \sigma T c \gamma^{2} U_{m} $$

   The time for an electron to decelerate in a magnetic field due to synchrotron losses can be expressed as:
   $$ \tau_s \equiv \frac{E}{(dE/dt)_s} \approx 3 \times 10^{12} \, [\text{eV}] \, \gamma^{-1} \left( \frac{B}{10^{-6} \, \text{G}} \right)^{-2} $$
   
3. **Interaction of Relativistic Charged Particles with Radiation** occurs through inverse Compton scattering and photoproduction of pions and electron-positron pairs. The universe is filled with cosmic microwave background (CMB) radiation with a temperature of $T \approx 2.72$ K and an energy density of $u_{\gamma} \approx 0.26$ eV/cm³. As a relativistic charged particle (a proton) moves, the energy of a photon in the proton's rest frame is $E'_{ph} = \gamma E_\gamma$. The threshold energy for pion production by photons is around 200 MeV, meaning that relic photons with energy $E_\gamma \sim 10$ eV can produce pions for particles with $E_p > 10^{10}$ eV. In practice, integration over the Planck function and the angles lowers this threshold energy to around $E_\gamma \sim 2.5$ eV. The cross-section of the reaction is $$\sigma_{p\pi} \approx 2.5 \times 10^{-28} \text{ cm}^2$$; thus, in the field of relic photons with a particle density of $n_{\gamma} \approx 400 \text{ cm}^{-3}$, the mean free path for scattering can be expressed:
   $$ l = \frac{1}{N_\gamma \sigma_{pn}} \approx 10^{25}$$ 
   or equivalently, the interaction time is given by:
   $$ \frac{l}{c} = 10^{7} \text{ years}.$$

   Since a pion is produced with an energy $E_{\pi} \sim \gamma m_{\pi} c^2$, the energy loss in a single collision with a relic photon corresponds to a fraction $$ \Delta E / E \approx P = \frac{E_{\pi}}{2 E} \sim 6 \times 10^{-4}$$. Consequently, within $10^{10}$ years, the proton will lose all its energy and fall below the reaction threshold. Hence, protons of ultra-high energy cannot originate from distances greater than 30-50 Mpc (the local supercluster of galaxies). The production of electron-positron pairs has a cross-section two orders of magnitude larger, but the energy carried away in this case is $1/6$ of that for pion photoproduction. As a result, the rate of slowing for a fast proton due to pair photoproduction is six times less effective than for pion photoproduction. The effect of spectral cutoff for ultra-high-energy cosmic rays in the field of relic photons is known as the **Greiner-Zatsepin-Kuzmin effect**, named after the authors who pointed out its importance in the mid-1960s.

## 4.6.1 The Problem of the Origin and Acceleration of Ultra-High Energy Cosmic Rays

Cosmic rays must be accelerated, evidently, by some non-thermal mechanism, as the temperature even at the centers of stars does not exceed a few keV. According to current understanding, the most likely mechanism for accelerating the electron and proton components of cosmic rays to high energies is the statistical acceleration of particles at the shock fronts created by supernova explosions. The essence of this mechanism (proposed by E. Fermi) is that during multiple collisions of particles in a moving medium with a speed $v \sim 0.1 c$, the energy of a particle on average increases by a magnitude $ \Delta E \sim 0.1 E$, ultimately resulting in a power law spectrum of distribution of particles in energy. In cases of head-on collisions, such a scenario can be realized at the front of a strong shock wave during a supernova explosion or in the vicinity of active galactic nuclei and quasars.

Another acceleration mechanism is electromagnetic, where a charged particle is accelerated in an electric field. Static electric fields are not possible in plasma due to high conductivity—the slightest deviation from charge neutrality in plasma creates a current that screens the field. However, under non-stationary electromagnetic fields, particle acceleration can be achieved up to very high energies. For example, in the magnetospheres of pulsars, the magnetic fields attain $B \sim 10^{12}$ G at the surface. Even at the minimally possible rotation periods of neutron stars, about $10^{-3}$ seconds, the size of the wave zone where charged particle acceleration can occur is on the order of $\sim 10^9$ km. At the base of the wave zone, the electric field induced by the rapidly changing magnetic field is given by Maxwell's equations and reaches values on the order of the magnetic field intensity: $$E \sim B$$. A charged particle can gain energy on the order of $$E_{max} \approx eBL \sim 3 \times 10^{19}$$ eV in a typical value of the field at the surface of a rapidly rotating neutron star $B = 10^{12}$ G. Thus, in principle, there are no issues with accelerating particles to very high energies. However, as experiments show, the spectrum of ultra-high-energy cosmic rays does not experience the expected cutoff at energies $E \sim 10^{20}$ eV (thus limiting their origin to the local supercluster size) and the observed cosmic rays at these energies arrive isotropically from all directions (there is no concentration towards the Galactic plane or its center), and they are not associated with any known astronomical objects in this well-studied region. Therefore, the problem of the origin of cosmic rays with energy above $E \approx 10^{20}$ eV remains one of the unresolved issues in modern astrophysics of cosmic rays.## 4.7 Other Methods for Diagnosing Cosmic Plasma

### 4.7.1 Dispersion Measure

The density of the electron component in the ionized interstellar medium can be determined by the delay of radio pulses from pulsars at different frequencies (the dispersion measure). The refractive index for radio waves with frequency $\omega$ in plasma with electron concentration $n_e$ is given by 

$$ n^{2} = \epsilon(\omega) = 1 - \frac{\omega_{p}^{2}}{\omega^{2}} < 1, $$

where $\omega_p$ is the plasma frequency defined as 

$$ \omega_{p} = \sqrt{\frac{4\pi e^{2} n_{e}}{m_{e}}} \approx 5.64 \times 10^{4} \sqrt{n_{e}}. $$

The time delay is expressed as 

$$ t = \frac{l}{v_g} = \frac{l}{cn} \simeq \frac{l}{c} \left( 1 + \frac{1}{2} \left( \frac{\omega_p}{\omega} \right)^2 \right) $$

Thus, the delay in time for a given frequency $\omega$ is given by 

$$ \Delta t(\omega) = \frac{1}{2 c \omega^2} l \omega_p^2 = \frac{2 \pi e^2 n_e l}{m_e c \omega^2}. $$

The dispersion measure $DM$ is defined as 

$$ DM = \int n_e \, dl, $$ 

with typical values indicating 

$$ 10 < DM < 500. $$

The time delay between two frequencies can be approximated as 

$$ \Delta t_{1,2} = \int \left( \frac{dl}{v_g(\omega_1)} - \frac{dl}{v_g(\omega_2)} \right) \approx 4.6 \, [\text{mks}] \, (\lambda_1^2 - \lambda_2^2) \times DM. $$

The refractive indices for the medium are given by 

$$ n_{\pm}^2 = 1 - \frac{\omega_p^2}{\omega(\omega \pm \omega_H \cos \theta)}, $$ 

where $\omega_H = \frac{eH}{m_ec}$ denotes the cyclotron frequency and $H$ is the magnetic field strength.

The phase velocity is expressed as 

$$ v_{\phi \pm} = \frac{c}{n_{\pm}} $$

The phase is given by 

$$ \phi_{\pm} = \frac{l \omega}{v_{\phi_{\pm}}} = \frac{l \omega n_{\pm}}{c}. $$

The rotation measure $\psi$ is defined as 

$$ \psi = \frac{\Delta \phi}{2}. $$

The indices can be approximated as 

$$ n_{\pm} \simeq 1 - \frac{1}{2} \frac{\omega_{p}^{2}}{\omega^{2}} \left( 1 \pm \frac{\omega_{H}}{\omega} \cos \theta \right) $$

Thus, the difference between the indices is 

$$ \Delta n = n_+ - n_- = \frac{\omega_p^2 \omega_H \cos \theta}{\omega^3}. $$

Finally, we can express the rotation measure as 

$$ \psi = \frac{1}{2} \frac{\omega_{p}^2 \omega_{H} l \cos \theta}{c \omega^2} = \lambda^{2} R M, $$

where 

$$ RM = \frac{e^2}{2\pi(m_e c)^2} \int_{0}^{L} n_e B_{\parallel} \, dl \approx 0.81 \, [\text{pa} \cdot \text{d}/\text{M}^2] \left( \frac{n_e}{\text{cm}^{-3}} \right)^{2} \left( \frac{B_{\parallel}}{10^{-6} \, \text{G}} \right) \left( \frac{L}{\pi k} \right) $$

This provides a deeper understanding of the effects of magnetic fields in plasma and the methodologies to measure them through astrophysical observations.## 4.8 Literature

1. **Cosmic Physics: A Small Encyclopedia**, Edited by R.A. Sunyaev. 2nd ed., Moscow: Soviet Encyclopedia, 1986.

2. **N.G. Bochkarev. Principles of Interstellar Medium Physics**. Moscow, Moscow State University Press, 1992.

3. **L. Spitzer Jr. Physical Processes in the Interstellar Medium**. Translated from English. Moscow: Mir, 1981.

4. **M. Longair. High Energy Astrophysics**. Translated from English. Moscow: Mir, 1984. 

---

### Additional Resources

- **Publications with Key Words**: [Stars](http://db/search.html?kw=13809) - [Interstellar Medium](http://db/search.html?kw=14142) - [Cosmology](http://db/search.html?kw=15891) - [Theoretical Astrophysics](http://db/search.html?kw=10526) - [Astrophysics](http://db/search.html?kw=16508)
  
- **Publications with Terms**: [Stars](http://db/search.html?words=%E7%E2%E5%E7%E4%FB) - [Interstellar Medium](http://db/search.html?words=%CC%E5%E6%E7%E2%E5%E7%E4%ED%E0%FF%20%F1%F0%E5%E4%E0) - [Cosmology](http://db/search.html?words=%CA%EE%F1%EC%EE%EB%EE%E3%E8%FF) - [Theoretical Astrophysics](http://db/search.html?words=%F2%E5%EE%F0%E5%F2%E8%F7%E5%F1%EA%E0%FF%20%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0) - [Astrophysics](http://db/search.html?words=%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0)

#### See also:
- ![APOD](http://images.astronet.ru/si/apod.gif) [Black Hole Disrupts Star: Animation](http://db/msg/1931410)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Stars, Dust, and Nebula in NGC 6559](http://db/msg/1904844)
- ![APOD](http://images.astronet.ru/si/apod.gif) [25 Brightest Stars in the Night Sky](http://db/msg/1863796)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Animation: Black Hole Disrupts Star](http://db/msg/1736616)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Decomposition of Distant Light](http://db/msg/1696356)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Comparison of Star Sizes](http://db/msg/1415428)
- ![APOD](http://images.astronet.ru/si/apod.gif) [The Most Distant of All Known Stars?](http://db/msg/1406555)

[All publications on the same topic >>](http://db/search.html?kw=13809&kw=14142&kw=15891&kw=10526&kw=16508)## 5. Stars

---

### Sections
- **5.1 General Information**
- **5.2 Star Formation**
- **5.3 Protostars**
- **5.4 Stationary Stars**

---

**Publications with keywords:** [stars](http://db/search.html?kw=13809) - [Interstellar Medium](http://db/search.html?kw=14142) - [Cosmology](http://db/search.html?kw=15891) - [Theoretical Astrophysics](http://db/search.html?kw=10526) - [Astrophysics](http://db/search.html?kw=16508)  
**Publications with phrases:** [stars](http://db/search.html?words=%E7%E2%E5%E7%E4%FB) - [Interstellar Medium](http://db/search.html?words=%CC%E5%E6%E7%E2%E5%E7%E4%ED%E0%FF%20%F1%F0%E5%E4%E0) - [Cosmology](http://db/search.html?words=%CA%EE%F1%EC%EE%EB%EE%E3%E8%FF) - [Theoretical Astrophysics](http://db/search.html?words=%F2%E5%EE%F0%E5%F2%E8%F7%E5%F1%EA%E0%FF%20%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0) - [Astrophysics](http://db/search.html?words=%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0)

---

**Also see:**
- ![APOD](http://images.astronet.ru/si/apod.gif) [Black Hole Destroying a Star: Animation](http://db/msg/1931410)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Stars, Dust, and Nebula in NGC 6559](http://db/msg/1904844)
- ![APOD](http://images.astronet.ru/si/apod.gif) [25 Brightest Stars in the Night Sky](http://db/msg/1863796)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Animation: Black Hole Destroying a Star](http://db/msg/1736616)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Decomposition of Distant Light](http://db/msg/1696356)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Comparison of Star Sizes](http://db/msg/1415428)
- ![APOD](http://images.astronet.ru/si/apod.gif) [The Most Distant of All Known Stars?](http://db/msg/1406555)

[All publications on the same topic >>](http://db/search.html?kw=13809&kw=14142&kw=15891&kw=10526&kw=16508)

---

**Reader Opinions** [70]

**Rating:** 3.1 [votes: 182]

**Rate it:** 
<select name="vote">
  <option selected="" value="0">--Rate--
  <option value="5">Excellent
  <option value="4">Good
  <option value="3">Average
  <option value="2">Poor
  <option value="1">Unsuitable
</select>
<input type="submit" value="Rate"/>

---

**Print Version**  
[![Print](http://images.astronet.ru/img/print.gif)](http://db/print/msg/1170612/5lec/node1.html)

---

**Related Topics**  
- [Astrometry](http://db/sect/300000007)
- [Astronomical Instruments](http://db/sect/300000010)
- [Astronomical Education](http://db/sect/1168516)
- [Astrophysics](http://db/sect/300000003)
- [History of Astronomy](http://db/sect/300000016)
- [Cosmonautics, Space Exploration](http://db/sect/300000012)
- [Amateur Astronomy](http://db/sect/300000013)
- [Planets and the Solar System](http://db/sect/300000005)
- [The Sun](http://db/sect/300000004)

---## 5.1 General Information

Stars can be classified based on their physical states into *normal* stars, which consist of non-degenerate matter (ideal gas) where thermonuclear fusion reactions occur in their cores, and *degenerate* stars (white dwarfs, neutron stars), whose equilibrium is maintained by the pressure of quantum-mechanically degenerate fermions (electrons in the case of white dwarfs or neutrons in the case of neutron stars). A special class includes black holes, which are not defined as stars in the conventional sense. White dwarfs, neutron stars, and black holes are collectively referred to as "compact remnants" as they are the final products of the evolution of ordinary stars. The total number of stars and their remnants in our Galaxy is estimated to be $\sim 2 \times 10^{11}$.

Let us begin with normal stars. The diversity of normal stars is comparable to that of galaxies; however, the key characteristics that determine their structure and evolution are their initial mass $M$ and chemical composition (the ratio of helium and heavier elements to hydrogen). The masses of stars range from $\sim 0.08 M_{\odot}$ to $\sim 100 M_{\odot}$. The lower limit is associated with the inability for nuclear fusion reactions to occur at smaller masses, while the upper limit is defined by the critical role of radiation pressure in massive stars. In high-mass stars, luminosity exceeds the Eddington limit:

$$
L_{\text{Edd}} \sim 10^{38} \left(\frac{M}{M_{\odot}}\right) \text{ erg/s}
$$

and therefore, there are no stable stars.

<div align="CENTER">
![Figure 5.3: Hertzsprung-Russell diagram](https://images.astronet.ru/pubd/2002/05/14/0001176797/5lec/img7.gif)  
**Figure 5.3**: Hertzsprung-Russell diagram (spectral class (effective temperature) - luminosity) for stars in the vicinity of the Sun (individual points are not shown). Luminosity is expressed in solar units ($L_{\odot}$ erg/s).
</div>

The evolution of stars with masses $M < 10 M_{\odot}$ culminates in the formation of white dwarfs with masses below the so-called *Chandrasekhar limit* ($M_{ch} \approx 1.4 M_{\odot}$). In more massive stars, nuclear fusion reactions continue until an iron core forms in the center of a star around 2 solar masses, which becomes unstable against gravitational collapse. During the collapse, binding energy is released:

$$
\sim 0.15 M_\odot c^2 \approx 10^{53} \text{ erg}
$$

(mainly in the form of neutrinos), while the remaining envelope is expelled, resulting in a *supernova* event. The remnants of supernovae eject a significant portion of the star's mass into the interstellar medium, enriching it with heavy elements—products of nuclear fusion. During supernova explosions, heavier chemical elements than iron are formed through neutron capture by the nuclei. The remnants of gravitational collapse may result in a neutron star with a mass of about 1.5 solar masses, or in the case of very massive stars, a black hole.

The chemical composition of stars (primarily, the content of heavy elements) determines the opacity of the star's envelope to radiation, which affects all star parameters (radius, central temperature, and rate of nuclear reactions). Chemically, stars are categorized into two major populations. *Population I* stars are poor in heavy elements (the mass fraction of elements heavier than helium is less than a fraction of a percent). These are old, low-mass dwarf stars found in the spherical components of disk galaxies, forming part of the ancient *globular clusters* and elliptical galaxies, i.e., where there is no active star formation in the present epoch. *Population II* stars are young, massive stars in the disk component of spiral galaxies, stars in irregular galaxies, and those in young *open clusters*, located in areas of intense star formation. The gas from which Population II stars form is the product of the evolution of Population I stars. It has undergone at least one cycle in stars and is therefore enriched with heavy chemical elements—the products of stellar nuclear evolution and supernova explosions. Our Sun belongs to Population II. Occasionally, hypothetical Population III stars are mentioned, which would be formed from primordial material (composed of hydrogen and helium with minor traces of lithium, deuterium, and beryllium) even before galaxies formed. The existence of such stars is not ruled out, but no observational evidence has yet been obtained.

The spectra of stars are extremely diverse. As we noted in Lecture 2, the spectrum of radiation emitted from a star's atmosphere is determined by the physical condition of its plasma and its chemical composition (the coefficients of emission and absorption). Based on spectral properties, stars are divided into spectral classes indicated by the letters O, B, A, F, G, K, M (the main spectral classes) in order of decreasing effective temperature from $\sim 20000$ K to $\sim 3000$ K. Stars of different radii may correspond to the same spectral class. A convenient graphical representation of a star's state was introduced in the early 20th century: the color-luminosity diagram (or luminosity - effective temperature), known as the *Hertzsprung-Russell diagram*. On this diagram, the *main sequence*, the branch of giants and supergiants, as well as the branch of subdwarfs and white dwarfs, can be clearly traced. Main sequence stars are the most numerous, as they burn hydrogen into helium in their cores. This is the longest stage of a star's evolution. Subsequent evolutionary stages leading to the formation of a compact remnant last about 10% of the main sequence lifetime.

After hydrogen is depleted, the star moves off the main sequence towards the red giants. In this process, the star's radius increases rapidly while its effective temperature decreases. The energy source for red giants is the burning of hydrogen in the shell surrounding the helium core. In later stages of evolution, helium burns into carbon, carbon into oxygen, and so forth, progressing through the elements up to the iron peak at an ever-increasing rate. For stars with initial masses $M < 10 M_\odot$, the formation of a white dwarf occurs at the top of the giant branch and is accompanied by a relatively slow shedding of the envelope, resulting in a *planetary nebula*. More massive stars explode as supernovae at the red supergiant stage, and depending on chemical composition, a supernova explosion may occur even at the blue supergiant stage, as was the case with supernova 1987A in the Large Magellanic Cloud.## 5.2 Star Formation

Stars are formed as a result of gravitational (Jeans) instability in cold dense molecular clouds. Let's consider a defined spherical volume in a uniform medium. The gravitational force, which tends to compress this volume, depends only on the mass of the gas contained within it:

$$F_g \propto \frac{M}{R^2} \propto R,$$

while the force opposing gravitational collapse is caused by the pressure gradient:

$$F_{p} \sim \frac{P}{R} \propto \frac{1}{R}.$$

It is evident that starting from a certain radius $\mathbb{R}$, equilibrium becomes impossible, and the volume will begin to collapse. By analyzing the linearized system of equations from gas dynamics for an ideal gas regarding the growth of small perturbations of the form:

$$\rho(t) = A \exp\{i(\omega t + \kappa r)\},$$ 

Jeans (1902) first showed that a initially homogeneous gravitational medium with density $\rho_0$ is unstable with respect to small sinusoidal density perturbations with characteristic scales exceeding:

$$\lambda_J = \frac{c_s}{\sqrt{\frac{\pi}{G \rho_0}}}$$.

Here, $c_s$ is the sound speed in the medium with molecular weight $\mu$, temperature $T$, and adiabatic index $\gamma$. At scales smaller than the Jeans wavelength, the perturbations become acoustic oscillations. The growth of density perturbations is determined solely by the initial density of the medium and does not depend on the scale of the perturbation:

$$\frac{\delta \rho}{\rho_0} \sim e^{i \omega t},$$

where 

$$\omega \simeq \sqrt{G \rho}.$$

For a cold dense interstellar medium with 

$$n \sim 100 \, \text{particles/cm}^3,$$ 

and 

$$\rho \sim 10^{-22} \, \text{g/cm}^3,$$ 

the collapse time is given by:

$$t_{ff} \sim \frac{1}{\sqrt{G \rho}} \sim 10^{7} \, \text{years},$$ 

and the sound speed $c_s \sim 10 \, \text{km/s}$. The characteristic mass of a giant molecular cloud is approximately:

$$M_J \sim 10^{38} \, g \sim 5 \times 10^{4} M_{\odot}.$$

This estimation indicates that the entire cloud can begin to collapse due to gravitational instability.

As the cloud compresses, density increases, the Jeans wavelength decreases, and fragmentation into smaller scale formations becomes possible. Therefore, stars are always born in groups (clusters, complexes). Young massive hot stars are nearly exclusively observed in OB associations.

*Example*: Let's examine the condition for fragmentation within a collapsing cloud. Suppose an ideal gas is compressing adiabatically. The specific heat ratio is given by:

$$\gamma = \frac{C_p}{C_v}.$$

The equation of state can be expressed as:

$$P = K \rho^{\gamma}.$$ 

The Jeans mass is:

$$M_J = \rho \lambda_J^3 \sim T^{3/2} \rho^{-1/2}.$$

From the state equation, we find:

$$M_J \sim \rho^{3/2} \gamma^{-2}.$$

The condition for stability with respect to fragmentation during density growth is:

$$\frac{dM_J}{d\rho} > 0,$$ 

which implies $\gamma > \frac{4}{3}$. For a monatomic ideal gas, we have $\gamma = \frac{5}{3}$, which shows stability against Jeans fragmentation upon adiabatic compression.

As long as the central temperature and density are insufficient to initiate thermonuclear fusion reactions, gravitational energy is released during compression, half of which, according to the virial theorem, goes into increasing thermal energy, while the other half escapes as radiation. This phase of evolution is termed the protostar stage.

*Example*: We can show that during the fragmentation of the protostellar cloud into individual stars, the masses of the resulting stars cannot fall below a certain fundamental limit, which depends only on the characteristic mass of a star, $M_{\text{min}} \sim 0.05 M_{\odot}$ (M.J.Rees, 1976).

A cloud with Jeans mass collapses over the free-fall time, during which the increase in density and temperature leads to a decrease in the Jeans mass, making it possible to fragment into smaller masses that begin collapsing on their own free-fall times.

The fragmentation process ceases before the onset of hydrogen ignition in the star's core, when the density increase renders the collapsing protostar optically opaque. This indicates that the gravitational binding energy $E_g \sim \frac{GM^2}{R}$ during times comparable to the free-fall time:

$$t_{ff} \sim \frac{1}{\sqrt{G \rho}}$$ 

becomes comparable to the radiation emitted from the surface of the star with a temperature $T \sim 10^{4} \, K$, hence:

$$L \sim \sigma_B T^{4} R^{2},$$ 

leading to the relation:

$$GM^2 \sqrt{\frac{G\rho}{R}} < L \sim x \sigma_B T^4 R^2.$$

Considering that the mass of fragments cannot be less than the Jeans mass, the relation:

$$M > M_{Ch} x^{-1/2} \left( \frac{k T}{m_{p} c^{2}} \right)^{1/4}$$

comes into play, yielding a lower limit for star formation rates. If giant molecular clouds in the Galaxy (numbering in the thousands) freely collapsed due to gravitational instability, stars would form within a timescale of:

$$\sim 10^{8} \, \text{years}.$$

The total mass of molecular hydrogen in the Galaxy is:

$$M_{\text{H}_2} \sim 10^{10} M_{\odot},$$ 

indicating that the star formation rate would be:

$$\sim 10^{3} \, M_{\odot} \, \text{per year}.$$

However, the observed star formation rate in the Galaxy is around 1 $M_{\odot}$ per year. This slowdown in the star formation rate is attributed to rotation and magnetic fields (due to the embedding of the fields within cosmic plasma). On the other hand, the compression is aided by shock waves from supernova remnants, spiral density waves, and stellar winds from hot OB stars.## 5.3 Protostars

Let's qualitatively follow the process of the collapse of a molecular cloud that meets the Jeans instability criterion. We will consider a spherical cloud of an ideal gas with mass $M$. It will start collapsing under its own gravity if its radius satisfies the inequality:

$$R < \frac{4 \mu G M}{R T} \simeq \frac{0.2 \pi k M}{T} \frac{M}{M_{\odot}}.$$

The cloud begins to contract on a free-fall time scale $t_f \sim \frac{1}{\sqrt{G\rho}}$, as the high transparency of the neutral material for photons allows the contraction to occur nearly isothermally. By substituting the radius from (5.1), we find the free-fall time as a function of temperature:

$$t_f \simeq \left( \frac{\mu}{RT} \right)^{3/2} GM \sim 6 \times 10^{7} \text{ years } \left( \frac{\mu}{T} \right)^{3/2} \frac{M}{M_{\odot}}.$$

The energy released during gravitational compression leads to an increase in temperature. While the matter is not yet plasma, its opacity is low, and the newly created low-energy photons freely escape from the cloud, carrying away some of the released energy. As the density rises, the free-fall time shortens, but the increase in density leads to increased opacity (primarily due to the absorption of infrared photons by dust and molecules). Therefore, isothermal compression gradually turns into adiabatic compression.

It is straightforward to estimate the radius to which a cloud of a given mass can compress based on the energy needed to dissociate molecules and ionize the material. Suppose the material initially consists of molecular hydrogen. The dissociation of one $H_2$ molecule requires approximately $4.6 \times 10^{-12}$ ergs, and the ionization of each hydrogen atom requires another 13.6 eV (or about $22 \times 10^{-12}$ ergs). Thus, to transform 1 gram of matter into plasma, approximately $I \approx 1.5 \times 10^{13}$ ergs are needed. The presence of helium molecules raises this estimate almost twofold. From the condition 

$$R \sim \frac{GM}{I} \simeq 80 R_{\odot} \frac{M}{M_{\odot}},$$ 

we can find the radius of an “opaque” protostar.

We can also estimate the luminosity of the protostar during the compression phase in free-fall:

$$L \sim \frac{GM^{2}}{Rt_{f}}.$$

Since the energy source is the gravitational energy of the collapsing cloud, this leads us to the conclusion that:

$$L \sim \frac{I}{G} \left( \frac{RT}{\mu} \right)^{3/2} \approx 2 \times 10^{-3} \left( \frac{T}{\mu} \right)^{3/2} L_{\infty}.$$

The luminosity is related to the effective temperature of the protostar via the Stefan-Boltzmann law:

$$L = 4\pi R^{2} \sigma_{B} T_{eff}^{4},$$ 

where $T_{eff}$ is the effective temperature.

On the Hertzsprung-Russell diagram, the star evolves along what is known as the Hayashi track, named after the scientist who quantitatively calculated this process. The actual compressing protostar stage is called the *Hayashi stage*.

The luminosity of the protostar during the Hayashi stage is simply 

$$\frac{L}{L_{\odot}} = \left( \frac{T_{eff}}{T_{\odot}} \right)^{4} \left( \frac{R}{R_{\odot}} \right)^{2} \simeq 400 \left( \frac{M}{M_{\odot}} \right)^{2}.$$

Evidently, the real picture of protostar compression is considerably more complex. In particular, we have ignored the effects of magnetic fields and rotation, which are inevitably present in astrophysical conditions. Both effects hinder the compression of protostars.

The role of rotation is quite evident. Using the conservation of angular momentum, for a cloud of a given mass $M$, during compression we have:

$$J = I \Omega_0 \propto M R^2 \Omega = \text{const}.$$

It follows that the rotational energy during compression increases as 

$$E_{rot} = \frac{1}{2} I \Omega^{2} \propto \frac{1}{R^{2}}.$$ 

The gravitational energy increases more slowly:

$$E_g \simeq \frac{GM^2}{R} \propto \frac{1}{R},$$ 

implying that at some radius, centrifugal forces will halt the collapse.

The less obvious influence comes from magnetic fields. In cold molecular clouds, the field interacts with neutral particles via a physical process analogous to *ambipolar diffusion* in laboratory plasmas. In contrast to the latter case (where the diffusion of light electrons leads to the diffusion of heavy ions due to Coulomb interaction), in the interstellar medium, heavy ions interact with the magnetic field, while the connection with neutral atoms occurs through collisions with ions. The characteristic time for the diffusion of a non-uniform magnetic field from an interstellar cloud due to this process is approximately

$$t_d \approx 5 \times 10^{13} \text{ years} \frac{n_i}{n_H},$$ 

where $n_i$ is the density of ions and $n_H$ is the density of neutral hydrogen.

In summary, the dynamics of protostars involves complex interplay between gravitational, thermal, magnetic, and rotational forces, influencing their evolution and formation processes.## 5.4 Stationary Stars

The physical state of stationary stars is determined by the conditions of hydrostatic equilibrium (when macroscopic parameters—mass, radius—change over long timescales $t_{ff} \sim \frac{1}{\sqrt{G \rho}}$, where $\rho$ is the mass density) and thermal equilibrium (despite the intense energy release at the core, stars do not explode, and their luminosity varies smoothly).

### 5.4.1 Hydrostatic Equilibrium

Consider a volume of matter $dV$ with pressure $P$. The force attempting to expand the volume is expressed as:

$$\vec{F} = -\int P \, d\vec{S},$$

where $d\vec{S}$ is the surface element. It is clear that if there is no pressure gradient ($\frac{\partial P}{\partial r} = 0$), then $\vec{F} = 0$. In general, we have:

$$P = P_{0} + \bar{r}^{n} \frac{\partial P}{\partial \bar{r}} + \ldots$$ 

Thus, the force acting on the volume element $dV$ is

$$\vec{F} = -\int P_0 d\vec{S} - \int \vec{r} \frac{\partial P}{\partial r} d\vec{S} + \ldots$$

Given 

$$dV = \vec{r} \cdot d\vec{S},$$

the corresponding forces can be expressed as:

$$d\vec{F}_{p} = -\nabla P \, dV,$$

and for gravitational force:

$$d\vec{F}_g = -\nabla \phi \, dm$$ 

where 

$$\phi(r) = -\int_{r}^{\infty} \frac{G m(x)}{x^2} \, dx.$$

The total force acting on the volume element in a star can therefore be summarized as:

$$d\vec{F} = -\nabla \phi \, dm - \nabla P \, dV.$$

Using the equilibrium condition, we derive:

$$\frac{1}{\rho}\nabla P + \nabla \phi = 0,$$

where $\phi = -\frac{GM(r)}{r}$, and 

$$M(r) = \int_{0}^{r} 4\pi x^{2} \rho(x) \, dx.$$

This leads us to the hydrostatic equilibrium equation:

$$\frac{1}{\rho} \frac{dP}{dr} + \frac{GM(r)}{r^2} = 0.$$

As a rough estimate, we can express the relationship:

$$\frac{P}{\rho} \sim \frac{GM}{R}.$$

For further analysis of potential energy, one can use:

$$U = -\int \frac{GM(r)dm}{r} = -3\int PdV,$$

with the condition $P \mid_{M(R)} = 0$. The pressure-volume relationship is typically modeled as:

$$P = K \rho^{\gamma},$$

where the specific internal energy can be calculated as:

$$\varepsilon = \frac{1}{(\gamma - 1)} \frac{P}{\rho}.$$

Consequently, we arrive at 

$$U = -3(\gamma - 1)Q,$$

where 

$$Q = \int \epsilon \rho \, dV.$$

### Example 1

Let's estimate the temperature at the center of the Sun. Assuming the entire star consists of an ideal monatomic gas, we can derive a center temperature of 

$$\langle T \rangle = \mu \frac{GM}{(RR)} \sim 3 \times 10^{7} K.$$

The exact value is around 14 million degrees.

### Example 2

Physically significant cases include:

1) For $\gamma = \frac{5}{3}$, corresponding to an ideal monatomic gas and non-relativistic degenerate Fermi gas, we obtain a familiar form of the virial theorem for motion in the potential $\phi$.

2) For $\gamma = \frac{4}{3}$, characteristic of gases composed of relativistic particles (such as photons or massless neutrinos), the virial theorem for a self-gravitating configuration yields a unique equilibrium state.

The total energy is related to the contributions of both kinetic and potential energies, summarized descriptively within the framework of energy conservation.

### 5.4.3 Thermal Stability of Stars. Negative Heat Capacity.

Considering the virial theorem for an ideal monatomic gas which approximates the material in normal stars:

$$P = \epsilon / 3,$$

results indicate an energy transfer to the star ($\Delta E$) leads to cooling, while energy radiation results in heating. This implies stars maintain a unique negative heat capacity, understood within the context of hydrostatic equilibrium.

Overall, it’s notable that the virial theorem remains applicable beyond thermodynamic considerations, spanning classical and quantum dynamics, and is critical for understanding both stable macroscopic systems and quantum systems like charged particles in a Coulomb field.## 6. Stars. Structure and Evolution (Continued)

### 6.1 Nuclear Reactions in Stars

### 6.2 Features of Nuclear Reactions in Stars

### 6.3 Relationships between $M - L$ and $M - R$ for Main Sequence Stars

---

In this section, we will explore the characteristics and the relationships between the key parameters of stars, specifically looking at main sequence stars, their luminosity, and radius as a function of their mass.

### Figure captions:

- **Figure 1:** Relationship between Mass and Luminosity ($M - L$)
- **Figure 2:** Relationship between Mass and Radius ($M - R$)

---

In the domain of stellar astrophysics, it is important to understand how these relationships inform our knowledge of stellar evolution and the lifecycle of stars. The mass of a star fundamentally influences its structure, energy production, and ultimately, its fate. 

Specifically, main sequence stars follow a defined set of relationships where luminosity increases with mass. Additionally, the radius also scales with mass, and these fundamental correlations are central to our understanding of stellar physics.

Understanding these core concepts will provide a strong foundation for further studies in stellar dynamics and evolutionary processes that govern the behavior of stars over cosmic timescales.## 6.1 Nuclear Reactions in Stars

The reserves of nuclear energy in stars far exceed their thermal energy reserves. If a star (for example, the Sun) were to shine solely through gravitational contraction, according to the virial theorem, the timescale for radiating thermal energy (the Kelvin-Helmholtz timescale) can be expressed as:

$$t_{KH} = \frac{GM^{2}}{RL} \sim 3 \times 10^{7} \left( \frac{M}{M_{\odot}} \right)^{-2} \text{years} .$$

![Equation (6.1)](https://images.astronet.ru/pubd/2002/05/14/0001176797/6lec/img6.gif)

When considering the energy available from nuclear processes, we can denote the nuclear energy change as:

$$\Delta E_n = \eta_n M_c c^2,$$

where $M_c \sim 0.1M$ signifies the mass converted in the reactions. The efficiency $\eta_n$ represents the fraction of mass converted into energy during the nuclear fusion process. 

Consider the fusion reaction:

$$4p \rightarrow He e^{4}_{2}$$ 

resulting in a net energy release calculated using the mass difference:

$$\delta \mathcal{E} = (4m_{p} - m_{He})c^{2} = 27.3 \, \text{MeV} .$$ 

This indicates that approximately $ \eta_{n} \approx 0.007 $, illustrating the limited efficiency of energy production during the nuclear fusion processes.

As we analyze hydrogen-burning processes, we find that the duration of hydrogen fusion in the core of a star - the longest-lasting phase - is significantly influenced by the mass of the star. Specifically, the timescale for hydrogen burning can be approximated as:

$$t_n = \frac{\eta_m M c^2}{L} \sim 10^{10} \, \text{yr} \left( \frac{M}{M_{\odot}} \right)^{-2},$$ 

highlighting that a star with a mass ten times that of the Sun evolves approximately 100 times faster than the Sun itself.

### Observations:

1. The timescale of thermonuclear burning of hydrogen is highly dependent on the star's mass, roughly as $M^{-2}$; for instance, a star with 10 solar masses evolves 100 times quicker than the Sun.

2. The hydrogen fusion stage in a star's core is the most prolonged phase. All subsequent stages (such as helium burning into carbon, etc.) contribute only about $10\%$ of the duration of the initial hydrogen-burning phase, which is attributed to the high sensitivity of nuclear reaction rates to temperature. In fusion reactions for heavier elements, the central temperature needs to exceed certain thresholds, overcoming higher Coulomb barriers, approximately represented as $\sim \mathbb{Z}^{2}$.## 6.2 Features of Nuclear Reactions in Stars

Using the virial theorem, the central temperature in a star can be estimated as:

$$T_c \sim \frac{\mu GM}{RR} \sim 10^{7} \, \text{K} \approx 1 \, \text{k}_{\text{B}}^{1}$$

In the center of the Sun, the gas is nearly ideal, and particles (protons) move with velocities consistent with Maxwell's distribution:

$$f(v) dv \propto v^{2} e^{-v^{2}/kT}$$

Thus, the fraction of protons with energy $E \sim 1$ is calculated, leading to an exceedingly small probability of interaction, even considering the solar mass:

$$\alpha \exp\left[-\left(\frac{1 \kappa B}{1 \text{ M} B}\right)^{2}\right] \sim e^{-1000} \sim 10^{-430}$$

However, as demonstrated by G. A. Gamov, nuclear reactions in the center of the Sun are still feasible due to the effect of **quantum mechanical tunneling** that allows the wave function to penetrate the Coulomb barrier. The momentum of a particle in quantum mechanics, as described by de Broglie, is given by:

$$\vec{p} = \hbar \vec{k}$$

where $\vec{k} = \frac{2\pi}{\lambda}$. The motion of a charged particle with momentum is represented by the wave function:

$$\psi \sim e^{ikx} \sim e^{i(p/\hbar)x} \sim e^{i/\hbar} \int p \, dx$$

The kinetic energy of the particle is:

$$\frac{p^2}{2m} = E_{\text{kin}} = E_{\text{pot}} - U = E_0 - U$$

The potential energy in the Coulomb field is expressed as:

$$U = Z_{1} Z_{2} e^{2}/r$$

In classical mechanics, if $E_0 \leq U$, the particle is reflected by the barrier, meaning it cannot penetrate the area with $r < r_1 = \frac{Z_1 Z_2 e^2}{E_0}$. In quantum mechanics, if $E > E_0$, we find that:

$$\psi \sim \exp\left[-\frac{1}{\hbar} \int_{r_1}^{r} \sqrt{2m(U - E_0)} \, dx\right]$$

This indicates that there is always a non-zero probability of tunneling through the barrier.

Now, knowing the reaction rate allows us to easily calculate the change in concentration of interacting elements over time:

$$\frac{dn_i}{dt} = \frac{dn_k}{dt} = -n_i n_k \langle \sigma v \rangle_{ik}$$

At this juncture, we should examine some specific features of the main thermonuclear reactions occurring in main-sequence stars.

### 6.2.1 pp-Cycle (G. Bethe, 1939)

This cycle occurs in stars of small masses (M < 1.3 $M_{\odot}$).

1. $\mathrm{pp\ cycle:}$
   - $$p + p \rightarrow D^2 + e^+ + \nu_e(E_{\nu,pp} < 0.42 \text{MeV}) \quad \tau \sim 10^{10} \text{ years}$$

   - $$D + p \rightarrow He^{3} + \gamma \quad \tau \sim 1.5 \text{ сек}$$

   - $$He^3 + He^3 \rightarrow He^4 + 2p \quad \tau \sim 10^6 \text{ лет}$$

2. With a probability of 65%:
   - $$He^{3} + He^{4} \rightarrow Be^{7} + \gamma$$

   - $$Be^{7} + e^{-} \rightarrow Li^{7} + \nu_{e}; \langle E_{\nu, Be} \rangle = 0.81 \text{ MeV}$$

   - $$Be^{7} + p \rightarrow Be^{8} + \gamma; \quad Be^{8} \rightarrow Be^{8} + e^{+} + \nu_{e}; \quad \left< E_{\nu,B} \right> \sim 8 - 14 \, M_{\odot}$$

   - $$Li^{7} + p \rightarrow 2 He^{4}$$

**Notes:**
1. The first reaction is the slowest, as it proceeds through the weak interaction, characterized by the Fermi constant $G_F \sim 1.4 \times 10^{-49} \ \text{erg} \ \text{cm}^3$. This reaction dictates the rate of energy release per gram of matter and the lifespan of a star on the main sequence.
   
2. Deuterium (in the second reaction) quickly reacts to form helium-3, and its equilibrium concentration is determined by the ratio of reaction times.

3. The energy release efficiency per unit mass depends highly on temperature:

   $$\epsilon_n \left| \frac{\partial p}{\partial r} \Big/ \frac{r}{c} \right| \propto \rho T^4 \ldots 8$$

4. Neutrinos typically carry off approximately 0.6 MeV of energy. The number of neutrinos produced by the Sun per second is given by:

   $$N_{\nu} = \frac{2L_{\odot}}{26.7 \, \text{MeV}} \simeq 1.8 \times 10^{38}$$

   The flux of $pp$ neutrinos on Earth is given by:

   $$F_{\nu} = \frac{N_{\nu}}{4\pi (1AE)^{2}}$$ 

5. Observations also indicate a significant difference between the numbers of solar neutrinos detected and the theoretically predicted values, leading to various implications about neutrino oscillation and properties. For instance, the observed electron neutrinos appear to be fewer than expected based on standard solar models.

[Insert Figure 6.2 - Calculated spectrum of the solar neutrino flux on Earth]

Probing the structure of the Sun via the observation of solar neutrinos using ground-based neutrino detectors provides essential insights into stellar nuclear processes.

### 6.2.2 CNO Cycle

The CNO cycle is implemented in stars more massive than the Sun. In this sequence of reactions, carbon acts as a catalyst—this means that, ultimately, in the CNO cycle, 

**Notes:**
1. The energy release per unit mass depends highly on temperature:
   
   $$L_{\odot}/M_{\odot} = 2$$

2. The total energy release in both the pp-cycle and CNO cycle is approximately the same, yet neutrinos carry away slightly more energy in the CNO cycle due to higher reaction temperatures.

### 6.2.3 Remarks on the Photon Luminosity of the Sun

Photons are generated in the nuclear reaction zone at the core of the Sun. The density of matter at the Sun's center is around 150 g/cm³, with a temperature near 1 keV. Conditions here closely adhere to a complete thermodynamic equilibrium, thus the energy of generated photons is distributed according to the Planck law for black bodies at a temperature of roughly 1 keV (in the X-ray range). 

Neutrinos, having an extremely small cross-section for interactions with matter, can freely escape the Sun, while photons are repeatedly absorbed and scattered until they reach the outer, more transparent layers of the solar atmosphere. The apparent "surface" of the Sun is regarded as the optical thickness level, which defines the photosphere, with an effective temperature dictated by the relationship:

$$T \sim \frac{Photometry \ energy}{density \times volume}$$ 

When considering small deviations from thermodynamic equilibrium, the transfer of radiant energy can be effectively described through the *diffusion approximation*.

The understanding of diffusion timescales in the Sun indicates that the time for thermal energy to emerge from the center is on the order of millions of years, dominated by radiation and convection processes. 

Thus, the interaction of solar magnetic fields also plays a significant role, as they can suppress convection and affect heat transfer, resulting in observable cooler areas known as sunspots with temperatures around 2000 K. These aspects are just parts of the greater context of stellar astrophysics that students are encouraged to explore further.## 6.3 Relationships between Mass and Luminosity for Main Sequence Stars

The masses of binary star components can be determined from observations, leading to the possibility of establishing an empirical mass-luminosity relation. It has been found that for main sequence stars, 

$$L \propto M^3$$ 

for stars with solar mass and  

$$L \propto M^{4.5}, \quad M < M_{\odot}.$$ 

These relationships were theoretically explained by the English astrophysicist A.S. Eddington in 1926.

The foundation of this analysis lies in the equation of radiative heat conduction (Equations (6.9) and (6.14)), which indicates that the photon luminosity of a star is regulated by the opacity of its outer layers. For rough estimations, we can replace derivatives with respect to radius with division by radius: 

$$\frac{d}{dr} \sim \frac{1}{R},$$ 

and substitute the star's temperature with its central value, 

$$T \rightarrow \sim T_c,$$ 

where 

$$T_c \sim \mu \frac{GM}{R^2}$$ 

is taken from the virial theorem. Ignoring constants (except for the gravitational constant), we obtain:

$$L \propto \frac{\mu^4 G^4}{\kappa} M^3$$ 

where $\kappa_T \approx 0.4$.

Note the steep dependence in (6.15) on Newton's gravitational constant $G$; it can be used to impose constraints on some physical theories in which the gravitational constant changes over time. If $G$ were to change over time, the luminosity of the Sun would also change under the same conditions. The very existence of a world ocean on Earth for billions of years (a necessary condition for organic life) limits variations in Earth's average temperature to roughly $\Delta T/T_{3} \sim 0.1$, which translates into 

$$T_3 \propto L_{\odot}^{1/4}$$ 

and results in 

$$\Delta G / G \sim 0.1.$$

Since we observe life on Earth, we can immediately conclude that the lifetime of stars must be on the order of 

$$L \sim \epsilon \mathcal{M} \sim \rho T^{ze} \mathcal{M},$$ 

implying lifetimes on the order of 

$10^9$ years for mass-luminosity relationships.

Now let's consider the mass-radius relationship for main sequence stars. Using the derived relation (6.15), we acknowledge that the luminosity of a star is related to energy generation in nuclear reactions:

$$L \propto G^{4}$$ 

This highlights that the fundamental physical parameter of a stationary star is its mass. The mass determines the star's luminosity on the main sequence, its lifespan, radius, and effective temperature. The next most important factor is its chemical composition, which dictates the molecular weight of the substance, influences opacity, and, consequently, affects all other parameters. However, within the scope of this discussion, we will limit ourselves to this observation.# 7. Evolution of Stars After the Main Sequence

In this section, we will explore the evolution of stars following their main sequence phase. Understanding this evolution is crucial for grasping the life cycles of stars, their transformations, and the eventual fate they face.

## 7.1 Evolution of Stars After the Main Sequence

The evolution of stars after the main sequence is dictated by their mass. As stars exhaust their hydrogen fuel in the core, they begin to undergo several transformational stages, leading to different outcomes based on their initial mass.

For stars similar to the Sun, once the hydrogen is depleted, they expand into red giants. The outer layers are expelled, creating planetary nebulae, while the core contracts into a white dwarf.

In contrast, more massive stars continue to fuse heavier elements until they reach iron in their cores. This process leads to more dramatic events, such as supernova explosions, which can form neutron stars or black holes.

### Figure Captions

- **Figure 1**: The evolution pathways for low-mass and high-mass stars post-main sequence.
  
- **Figure 2**: The structure of a red giant star during its evolution.

- **Figure 3**: A schematic representation of a supernova explosion.

The fundamental relationships that define the structure of stars, such as the mass-luminosity (M-L) and mass-radius (M-R) relations, play critical roles in these evolutionary processes. 

**Mass-Luminosity Relation**: This relation indicates that a star's luminosity increases with its mass, demonstrating that more massive stars burn hotter and faster.

**Mass-Radius Relation**: This relationship expresses how the radius of a star scales with its mass, and is critical for understanding various stellar structures during evolution.

In summary, the life cycle of stars after the main sequence phase involves complex processes governed by their mass, which ultimately dictate their eventual fates as different astronomical objects.## 7.1 Evolution of Stars After the Main Sequence

Hydrogen burning is the longest phase in the life of a star, primarily due to the initial abundance of hydrogen (about 70% by mass) and the considerable energy yield (about 70 MeV per nucleon) from the fusion of hydrogen into helium. During this process, the photonic luminosity of stars on the main sequence is generally less than during subsequent evolutionary phases, and their neutrino luminosity is significantly lower, with central temperatures not exceeding approximately $T_c \sim 2 - 3 \times 10^{7}$ K. Consequently, the majority of stars in the Galaxy and the Universe are main-sequence stars.

After hydrogen burning ceases in the core, the star moves to the right of the main sequence on the Hertzsprung-Russell diagram, with its effective temperature decreasing and the star entering the red giant phase. This shift is due to convective energy transport from the shell of hydrogen burning located just outside the helium core. In the core itself, temperature increases due to gravitational compression, and at temperatures around $T \sim 5 \times 10^{7}$ K and densities $\rho_{c} \sim 10^{3} - 10^{4}$ g/cm³, helium burning begins. 

*Note*: Since there are no stable elements with atomic numbers 5 and 8 in nature, reactions like $4He + 4He \iff Be^{8}$ are impossible, as $Be^{8}$ decays into 2 alpha particles.

The energy released per gram during helium burning is roughly an order of magnitude lower than during hydrogen burning. Therefore, the lifetime and the number of stars in this evolutionary stage are significantly less than that of main-sequence stars. However, due to their high luminosity (in the red giant or supergiant phase), these stars are well studied.

The most crucial reaction is the triple-alpha process: 

$$3\alpha \rightarrow C^{12}$$

The combined energy of three alpha particles exceeds the rest mass energy of a carbon-12 nucleus by about 7.28 MeV. To facilitate this reaction efficiently, a "resonant" energy level in the carbon-12 nucleus (with an energy of 7.656 MeV) is necessary. Thus, the $3\alpha$ reaction in stars is resonant and occurs at a sufficient rate. Two alpha particles form the short-lived nucleus $Be^{8}$:

$$He^{4} + He^{4} \iff Be^{8}$$

The lifetime of $Be^{8}$ is approximately $10^{-16}$ s, but there is a probability of it capturing another alpha particle to form the excited $C^{12}$ nucleus:

$$Be^{8} + He^{4} \iff C^{12}^*$$

The excitation is released by producing a pair, rather than by photon emission, because photon transitions from this level are forbidden by selection rules:

$$C^{12}_{*} \rightarrow C^{12} + e^{+} + e^{-}$$

It's noteworthy that the resulting atom $C^{12}$ mostly "breaks apart" into $Be^{8}$ and $He^{4}$ and ultimately into three alpha particles. Only in one case out of 2500 does it transition to the ground state with the release of 7.65 MeV of energy, taken away by the $e^{+} e^{-}$ pair.

On subsequent stages of evolution in massive stars, direct fusion reactions of heavier nuclei occur at high temperatures in the central regions of stars. The energy release in burning reactions related to $F e^{56}_{26}$ is comparable to that in the triple-alpha process; however, intense neutrino emission due to the high temperature ($\sim 10^{8}$ K) shortens the star's lifetime during these phases significantly compared to helium burning. The chance of discovering such stars is exceedingly small, and currently, there is no confirmed identification of a star in a stable state that produces energy through the burning of $C^{12}$ or heavier elements.

![Figure 7.1](https://images.astronet.ru/pubd/2002/05/14/0001176797/7lec/img28.gif)  
**Figure 7.1** Calculation of the evolution of a star with an initial mass of $22 M_{\odot}$ as a function of time from the onset of hydrogen burning in the core to the beginning of collapse. Time (in a logarithmic scale) is measured from the moment of collapse initiation. The vertical axis shows mass in solar units measured from the center. Stages of nuclear burning of various elements (including shell sources) are marked. Heating intensity is shown in color (blue for heating and purple for neutrino cooling). The hatched areas indicate convectively unstable regions of the star. Calculations by Heger A., Woosley S. (Figure from the review by Langanke K., Martinez-Pinedo G., 2002, nucl-th/0203071).

## 7.1.1 Processes of Heavy Element Formation

Nucleosynthesis in the early Universe halts at Helium ($\sim 2 \times 10^{-9}$), Deuterium, and traces of heavier elements, as there are no stable elements with atomic numbers 5 and 8, and reactions forming elements with $Z > 2$ involving charged particles require overcoming a significant Coulomb barrier. All chemical elements from carbon onwards are produced through thermonuclear burning in stars and during supernova explosions via the capture of protons and, primarily, neutrons by atomic nuclei. Elements like $Kr$, $Xe$, and heavier ones are not produced in stellar thermonuclear burning, and their observed concentrations are associated with spallation reactions during interactions of high-energy cosmic ray particles with heavy elements on the surfaces of stars and in supernova shells. 

During supernova explosions, temperatures can reach up to around 100 MeV in the center, establishing thermodynamic equilibrium based on nuclear reactions with kinetics governed by beta processes, resulting in the formation of elements in the iron group, which consist of equal even numbers of protons and neutrons.

The primary mechanism for forming elements heavier than iron is through neutron capture – the $s$- and $r$-processes. These processes differ regarding the ratio of the characteristic neutron capture time $\tau_n$ and beta decay time $\tau_\beta$ in a neutron-rich nucleus. In $s$-processes (slow capture), nucleosynthesis occurs through nuclei that fall in the "valley of stability" on the nuclear chart. Rapid neutron capture with $\tau_n \ll \tau_\beta$ (the $r$-process) occurs in environments significantly enriched with neutrons, leading to the formation of very unstable neutron-rich nuclei.

There is considerable uncertainty in calculations of the $r$-process, which likely occurs under conditions of intense neutrino irradiation. Synthesis of heavy nuclei occurs during helium flashes in moderate-mass stars, in the asymptotic giant branch phase, during nova explosions, and most actively during supernovae (primarily type Ia, which are thermonuclear explosions of white dwarfs near the Chandrasekhar mass, see below). 

Again, it's emphasized that the astrophysical phenomena involving $r$-processes are not definitively established; for instance, it is possible that heavy $r$-elements form during the merger of two neutron stars in relativistic binary systems.

Notably, the relative abundance of heavy $r$-elements can be used to estimate the age of a star. This typically involves long-lived radioactive isotopes, such as $^{232}Th(\tau_{1/2} = 1.4 \times 10^9 \text{ years})$ and $^{238}U(\tau_{1/2} = 4.5 \times 10^{9} \text{ years})$. 

By examining absorption lines in stellar spectra, the ratio of radioactive thorium (which can only be formed under $r$-process conditions) to the stable europium (Eu) element is determined. This ratio decreases over time (as thorium decays), allowing the star's age to be estimated by knowing the theoretical initial value of the abundance ratio, which is determined solely by the kinetics of the $r$-process. The ratio of third peak elements (Os, Ir, Pt, Au) to thorium and the ratio $U/Th$ are also considered, yielding a lower limit for the star's age. This method has been used to determine the ages of the oldest stars with low metallicity (halo stars of the Galaxy and those in globular clusters), estimated to be over 13 billion years old. This provides a crucial constraint on the lifetime of the Universe itself. For further details, refer to the collection "Nuclear Astrophysics," edited by Fowler, Moscow: Mir, 1986.## 7.2 Degeneracy of Matter

During the evolutionary process, both the density and temperature in the center of a star increase. As the density rises, the physical state of the matter begins to change—first due to Coulomb interactions (as seen in ordinary solid bodies) and later due to quantum mechanical effects (the degeneracy of the electron gas). Indeed, astronomical observations show that compact white dwarfs have a radius of about $0.01$ solar radii at a mass approximately equal to that of the Sun, which means their average density is $\sim 10^4$ g/cm³. At such densities, interatomic distances are smaller than the sizes of electron orbits in atoms, leading to electrons becoming free even at zero temperature ($T = 0$) and behaving like a gas.

A gas can be treated as ideal as long as the interaction energy between its particles is negligible compared to the thermal energy. The approximation of an ideal monatomic gas, where the energy per particle is given by $E = \frac{3}{2}kT$, effectively describes the behavior of the plasma at the center of the Sun. Quantum mechanical interactions can be neglected as long as the characteristic distances between particles are smaller than the de Broglie wavelength: $$\lambda_B = \frac{h}{p}$$ (where $n$ is the particle concentration). At small distances, the Pauli exclusion principle must be taken into account for fermions (particles with half-integer spin—such as electrons, neutrons, and protons): no more than one particle of a given type can occupy the same quantum state. In contrast, for bosons (particles with integer spin, such as photons), the more particles occupying a state, the more tend to occupy it—a phenomenon that explains wave noise in radio astronomy, for instance.

When the fermionic gas is degenerate, the particles fill all available states in phase space up to the state with the limiting momentum (known as the *Fermi momentum*), which depends on their concentration: 
$$p_F = \left( \frac{3}{8\pi} \right)^{1/3} h N^{1/3}.$$

Next, we estimate the pressure of a non-relativistic electron Fermi gas. The relationship between the kinetic energy of a non-relativistic electron and its mass $m_e$ through momentum is described by:
$$E_F \sim \frac{p_F^2}{2m_e}.$$

With a factor on the order of unity, the pressure is given by:
$$P \sim K \rho^{5/3},$$ 
where $K$ is a constant depending on fundamental constants and the chemical composition of the matter. In the relativistic case, the expressions change to reflect the higher energy state of particles. Thus, a critical property of the degenerate Fermi gas is that its pressure depends on the density of the matter, and it is almost **independent of temperature**, unlike an ideal gas, where pressure is proportional to the product of density and temperature: $$P \sim \rho T.$$

Let us demonstrate that a star, whose pressure is dictated by a non-relativistic degenerate electron gas (a white dwarf), follows the inverse mass-radius relationship. From the equation of hydrostatic equilibrium, we have:

$$\frac{P}{\rho R} \sim \frac{GM^2}{R}.$$

From this, it can be derived that:
$$R \propto M^{-\alpha},$$
where specifically for a non-relativistic electron degeneracy:
$$\alpha \approx \frac{1}{3}$$ 

This shows that as the mass of a white dwarf increases, its radius decreases, a demonstration of the intricate balance of forces at play in these stellar remnants.## 7.3 Chandrasekhar Limit and Fundamental Mass of a Star

As the density of matter increases ($\rho > 10^{6}$ g/cm³), electrons become relativistic, and their pressure can be expressed as $P \rightarrow K \rho^{4/3}$. From the equation of hydrostatic equilibrium, it follows that equilibrium is possible only for a specific mass, known as the Chandrasekhar limit:

$$M_{Ch} \approx \left( \frac{K_{rel}}{G} \right)^{\frac{3}{2}}$$

Specifically,

$$M_{Ch} = \frac{5.83 M_{\odot}}{\mu_{e}^{2}} \approx 1.46 M_{\odot} \left( \frac{\mu_{e}}{2} \right)^{-2}$$

where $ \mu_e$ represents the number of electrons per nucleon and $\mu_e \geq 2$. 

### Example
Here, it is crucial to observe that we deduced the fundamental number of baryons in a typical star to be $N_b$. The total number of baryons within the current event horizon $N_{tot}$, which encompasses all baryonic objects of stellar mass within the Hubble radius, can be estimated as:

$$N_{tot} \sim \left(\frac{c}{H_{0}}\right)^{3} \Omega_{b} \times \left(\frac{\rho_{cr}}{m_{p}}\right) \sim N N_{*}$$

Here, $N_{*}$ denotes how many stars exist within this framework.

If we consider the mass of a typical galaxy to be $M_g \sim 10^{11} M_{\odot}$, then we can say:

$$M_{g} \sim 10^{11} N m_{p}$$

where $N_g \sim 10^9 \Omega_b$. 

When the gravitational force of a star is countered by the pressure exerted by degenerate neutrons (as seen in a neutron star), a similar limiting mass can be obtained for the neutron star. This limit is sometimes referred to as the Oppenheimer-Volkoff limit, named after the physicists who in 1939 explored the structure of the simplest neutron star, composed solely of degenerate neutrons.

Unlike the Chandrasekhar limit, which is influenced solely by the chemical composition of the matter (defining the number of electrons per nucleon), the Oppenheimer-Volkoff limit depends on the yet-unknown equation of state for matter at nuclear densities (estimated at $\rho > 10^{14}$ g/cm³). Modern calculations indicate that this limit typically ranges from $\sim 1.4 - 3 M_{\odot}$, making its determination one of the fundamental challenges in the physics of neutron stars.## 7.4 Neutronization of Matter and Loss of Star Stability

The combustion of silicon leading to the formation of nuclei such as $^{32}Si$, $^{56}Fe$, $^{58}Fe$, and $^{60}Fe$ marks the culmination of thermonuclear reactions in the non-degenerate core of a massive star. At this stage, the density reaches about $3 \, \text{g/cm}^3$, and the temperature is approximately $8 \times 10^{9} \, K$ with a core mass of $1.5-2 \, M_{\odot}$. 

At high temperatures and densities, the direct and inverse nuclear reactions, facilitated through the electromagnetic channel (with photon emission or absorption), reach equilibrium, meaning that the number of direct reactions per unit time equals the number of inverse reactions. If the star's core were surrounded by an adiabatic shell and not undergoing compression, nuclear statistical equilibrium would establish itself at these equilibrium parameters, resulting in a mixture of photons, neutrons, alpha particles, and atomic nuclei, the concentrations of which could be calculated using statistical physics principles. 

However, this does not occur because the energy required to dissociate the nuclei is drawn from the negative gravitational potential energy. In this situation, compression does not result in an increase in pressure as would be expected in a stable star since nuclear dissociation represents a first-order phase transition—energy is consumed to alter the internal degrees of freedom of the particles rather than to boost their translational motion energy, which defines the pressure of a non-degenerate gas. Therefore, due to nuclear dissociation, the increase in pressure with rising density is insufficient to counteract gravitational forces. 

As the density increases, other physical processes commence, including the neutronization of matter, where free electrons are captured by protons within the nuclei, as explained below. In this process, neutrinos carry energy away from the star, further accelerating its collapse.

Nuclear evolution in the cores of stars is accompanied by an increasing relative abundance of neutrons: at the beginning of evolution, in matter consisting of 75% hydrogen and 25% helium, there are 6 protons for every neutron. However, after the formation of helium, this ratio decreases to 1:1. As the density rises and degeneracy begins, electrons attain relativistic speeds due to the Pauli exclusion principle (already at densities greater than $3 \, \text{g/cm}^3$). 

Once a certain threshold energy (the Fermi energy) is reached, processes of matter *neutronization* become possible:

$
H\textsuperscript{3} + e^{-} \rightarrow H\textsuperscript{3} + \nu_{e}, \, \varepsilon_{F} = 18 \kappa B, \, \rho > 10^{6}
$

$
He^{4} + e^{-} \rightarrow H^{4} + n + \nu_{e}, \, E_{F} = 20 \, \text{MeV}, \, \rho > 10^{11}
$

$
Fe^{56} + e^{-} \rightarrow Mn^{56} + \nu_{e}, \, \epsilon_{F} = 4M \rho B, \, \rho > 10^{11}
$

The average energy of neutrinos in this context can be approximated as:

$
\langle E_{\nu} \rangle \sim \langle E_{e^{-}} \rangle \sim E_{F} \approx 51.6 \left( Y_{e} \rho_{12} \right)^{1/3} M \Theta B
$

where $Y_{e} = \frac{n_{e}}{n_{b}}$ and $\rho_{12} = \frac{\rho}{(10^{12})}$.

When matter undergoes neutronization, the stiffness of the degenerate matter decreases, as the concentration of electrons decreases while keeping baryonic density constant (the lepton parameter $Y_{e}$ remains fixed). Thus, the effective adiabatic index of the matter, 

$
\Gamma = \frac{d \log P}{d \log \rho},
$

drops from $ \frac{5}{3} $ to $ \frac{4}{3} $. According to the virial theorem (or the conditions of hydrostatic equilibrium in a star), such a change in the adiabatic index leads to a loss of mechanical stability for the star. Therefore, the neutronization of matter is one of the key physical processes enforcing the core collapse of massive stars in the later stages of their evolution.

Another reason for the loss of hydrostatic stability in stars is the effects of General Relativity: in GR, the pressure of matter contributes to the gravitational force (figuratively speaking, pressure "weighs" something), and thus at high densities and pressures of degenerate gas, relativistic effects generate additional forces that tend to compress the stellar material.

During neutronization, the star rapidly loses stability: the loss of stiffness leads to compression and heating, but the negative heat capacity typical of ordinary stars ceases to operate. In this regime, the gas pressure opposing compression becomes nearly independent of temperature. Most of the energy from gravitational compression is carried away by neutrinos produced during neutronization. 

Even if the temperature rise during the collapse alleviates the degeneracy of the electron gas, energy continues to be lost via antineutrinos produced during the beta decay processes in neutron-rich nuclei. These irreversible energy losses due to direct and reverse beta decays are referred to as *URCA processes*, which were first examined by Gamow and Shenberg. The volumetric energy losses during URCA processes heavily depend on temperature and can be expressed as:

$
Q_{urca} \approx 8 \times 10^{11} \rho \left( \frac{T}{10^{9} \text{K}} \right)^{6} \text{erg}/\text{cm}^{3}/\text{s}.
$

$
Q_\textrm{urca} \sim 4 \times 10^{15} \rho \left( \frac{T}{10^9} \right)^9 \frac{\mathrm{erg}}{\mathrm{cm}^3 \, \mathrm{s}^{-1}}.
$ 

In summary, the processes involved in neutronization and the associated energy losses play crucial roles in the dynamics of stellar evolution and the eventual collapse of massive stars.## 7.5 Supernova Explosions

Supernova explosions (SN) represent one of the most powerful catastrophic processes in nature. These explosions are associated either with the collapse of the cores of massive stars (known as type II and Ibc supernovae), or with thermonuclear explosions of white dwarfs (type Ia SN). According to current understanding, in stars with a mass greater than approximately $10 M_{\odot}$ during their main sequence phase, the thermonuclear evolution proceeds under non-degenerate conditions until the formation of the most stable elements of the iron group (Fe, Ni, Co).

The mass of the evolving core of a star weakly depends on the total mass of the star, averaging around $2 - 2.5 M_{\odot}$ even for the most massive main sequence stars. The collapse of the core is initiated by the neutrinization of matter. In more massive stars, additional causes of instability arise - at temperatures reaching about $5 - 10 \times 10^9$ K, photodisintegration of iron nuclei starts occurring.

![Photodisintegration of iron nuclei](https://images.astronet.ru/pubd/2002/05/14/0001176797/7lec/img133.gif)

The total energy released during the collapse of the core of a massive star can be calculated. If, at the end of the process, a neutron star with a mass $M_{\text{NS}}$ and radius $R_{\text{NS}}$ is formed, then the energy released is equivalent to the binding energy of the neutron star:

$$\Delta E \simeq -\frac{GM^2_{\text{NS}}}{R_{\text{NS}}}.$$

This binding energy is approximately $M_{NS} = 1.35 \pm 0.1 M_{\odot}$. Hence, the released energy can be expressed as:

$$\Delta E \simeq 0.15 M_{NS} c^2 \simeq 5 \times 10^{53} \text{ erg}.$$

The onset of collapse may be halted by the stiffness of matter that has reached nuclear density, approximately $\rho_{\text{nuc}} \approx 2.8 \times 10^{14} \, \text{g/cm}^3$, and predominantly consists of degenerate neutrons (neutron fluid). At this point, a neutron star is formed. The star's envelope gains tremendous momentum (potentially being transferred by neutrinos or the magnetic field of the rotating collapsing core) and is ejected into interstellar space at speeds around $10,000 \, \text{km/s}$. The remnants of supernova explosions, upon expansion, interact with the interstellar medium, generating shock waves and emitting light for approximately $10^{4}$ years. In some types of remnants, called pulsars, the main energy source in the envelope comes from relativistic particles produced by a rapidly rotating neutron star with a strong magnetic field formed during the collapse. A well-known example of a young supernova remnant is the Crab Nebula, the remnant of the SN explosion of 1054 in the constellation Taurus.

During the formation of the neutron star, neutrinos, due to elastic scattering on electrons and nuclei, do not escape the volume of the collapsing matter in time (despite the negligible cross-section of weak interactions $\sigma_\nu \sim 10^{-44} \left( \frac{E_\nu}{m_e c^2} \right)^2$). For a while, on the order of $10$ seconds, an "optically thick" shell for neutrinos called the **neutrinosphere** is formed with a temperature around $10$ MeV and a spectrum close to equilibrium. As a consequence, all types of neutrinos and anti-neutrinos are present in equal concentrations in the neutrino emission from the surface of the neutrinosphere. The diffusion time of neutrinos through the neutrinosphere determines the characteristic duration of the neutrino pulse:

$$t_{\nu} \sim \frac{R_{NS}^{2}}{D} \sim M_{NS} \sigma_{\nu} / \left( R_{NS} c m_{p} \right) \sim 10 \text{ s},$$

where $D = \frac{cl}{3}$ and $l = \frac{1}{n \sigma_{\nu}}$.

The neutrino pulse was detected from supernova 1987A in the Large Magellanic Cloud across several neutrino observatories (Mont Blanc, Kamiokande, IMB, Baksan), in good agreement with theoretical calculations of the core collapse of a massive star.

In the collapse of the cores of the most massive stars (with a mass on the main sequence greater than $40 M_{\odot}$), the implosion of the core likely leads to the formation of a black hole. Observations of double X-ray systems with black holes indicate that their masses range broadly from $4$ to $20$ solar masses.

Current views suggest that type Ia supernovae are caused by thermonuclear explosions of a white dwarf in a binary star system, when it reaches a mass close to the Chandrasekhar limit of approximately $1.2 M_{\odot}$, during the process of mass transfer from the expanding companion star. The loss of stability in the white dwarf occurs due to the neutrinization of matter and effects from general relativity. A simple estimate shows that the energy released during thermonuclear burning is sufficient to disperse the star's material: the binding energy of the white dwarf $E_b \sim 3 \times 10^{51} \text{ erg}$, and the energy of the burning is expected to exceed this threshold comfortably.

It is important to note that the light curve of a supernova, which is what we actually observe, is associated with the brightness of the shell expanding at speeds of tens of thousands of kilometers per second. The luminosity over several months is related to the radioactive decay of iron group nuclei (primarily $^{56}Ni$ and $^{56}Co$) that are produced during the thermonuclear burning of the white dwarf.

A distinctive feature of type Ia supernovae is the weak dependency of the explosion's power on initial conditions, due to the universality of the upper mass limit for white dwarfs. Consequently, type Ia supernovae are currently used as "standard candles" for determining distances to distant galaxies. The record farthest galaxy where type Ia SN has been registered (April 2000) has a redshift of $z > 1.7$, indicating it is located at an astonishing distance of over a gigaparsec from Earth. The relationship between apparent flux and distance for objects with standard energy output is used to test cosmological models. Observations of distant type Ia supernovae in 1998 made it clear that the best cosmological model must include a significant cosmological constant, which effectively acts as anti-gravity on large scales, causing the expansion of the Universe to accelerate! If recent observations confirm this fundamental discovery, our understanding of the Universe's evolution will undergo significant changes. More detailed discussions can be found in the chapters on cosmology.# 8. Stellar Evolution Remnants

As discussed in previous lectures, the evolution of ordinary stars can be described by their nuclear fusion processes, primarily involving hydrogen in the main sequence and heavier elements in post-main sequence stages within the star's core. Hydrogen burning occurs at a slower rate, and the lifetime of a star after the main sequence does not exceed $10\%$ of its hydrogen-burning phase.

The final stages of stellar evolution are accompanied by significant mass loss from the star’s envelope in the form of stellar winds, especially during the red giant and supergiant phases, reaching rates of $\sim 10^{-5} M_{\odot}$ per year. The final products of stellar evolution are determined by the physical conditions at the star's center at the end of nuclear reactions. These conditions are entirely dependent on the star's initial mass on the main sequence and its original chemical composition.

Depending on the initial mass of Solar-composition stars (typical for stars in the disk of the Galaxy), there are three types of compact remnants that may arise in the stellar cores after the completion of nuclear evolution:

1. **Planetary Nebulae and White Dwarfs**  
   ![Planetary nebula, white dwarfs](https://images.astronet.ru/pubd/2002/05/14/0001176797/8lec/img3.gif) 

2. **Supernovae Type II and Ibc and Neutron Stars**  
   ![Supernovae and neutron stars](https://images.astronet.ru/pubd/2002/05/14/0001176797/8lec/img4.gif)  
   ![Neutron stars](https://images.astronet.ru/pubd/2002/05/14/0001176797/8lec/img5.gif)

3. **Supernovae and Black Holes**  
   ![Supernovae and black holes](https://images.astronet.ru/pubd/2002/05/14/0001176797/8lec/img6.gif)  
   Conditions leading to this final type are less certain, given the unclear details regarding the mechanism of envelope ejection during supernova explosions.

It should be noted that there is uncertainty regarding the precise boundaries that differentiate these cases, as the details of the envelope shedding mechanism during a supernova are still not fully understood.## 8.1 White Dwarfs

The primary reason for the formation of various types of stellar remnants is the difference in physical conditions at the center of stars. In stars with masses up to 10 times that of the Sun, thermonuclear evolution completes before the formation of an iron core, which has a mass lower than the Chandrasekhar limit. Depending on the initial mass, this occurs during the helium or carbon-oxygen core stages of the degenerate core. The thermonuclear burning in degenerate material is explosive in nature (due to the high thermal conductivity of degenerate electrons—think of a hot frying pan!), and the increased temperature can partially relieve the degeneration, making the burning less intense. 

Therefore, at the staged shell source near the degenerate CO core, the envelope of the star—a red (super)giant—can be expelled due to thermal instabilities at the boundary of the shell source and the degenerate core (at this point, the star is on the asymptotic giant branch in the upper right part of the Hertzsprung-Russell diagram). As a result of the envelope expulsion, a planetary nebula forms around the degenerate core, "illuminated" by a very hot proto-white dwarf (with an effective temperature of around $T_{eff} \sim 10^5$ K). The energy radiated by the white dwarf is thermal energy stored in the oscillations of ions. By emitting photons from its surface, the white dwarf gradually cools down (its effective temperature decreases), and since the radius of a white dwarf is about 10,000 km, the characteristic cooling time can reach 10 billion years. The oldest and coldest white dwarfs have an effective temperature of about 2000 K. In such cold "brown" dwarfs, positively charged ions form a crystalline lattice (crystallization begins at temperatures around 10000 K).

From the perspective of mechanical equilibrium, the force of gravity in white dwarfs is counterbalanced by the pressure gradient of the degenerate electron gas. It is essential to emphasize the role of Coulomb forces: gravity acts on the "heavy" protons, and due to the Pauli exclusion principle, immense pressure from degenerate electrons is created, which is transmitted to protons through electrostatic forces.

Stars on the main sequence with masses less than $0.5 M_{\odot}$ are fully convective, which prevents the ignition of the shell source after the hydrogen is exhausted. Such stars do not become red giants and move rightward on the Hertzsprung-Russell diagram, contracting and heating up. The temperature in the helium core is below the temperature necessary to relieve electron degeneration; therefore, eventually, such stars will evolve into born white dwarfs with masses of approximately $< 0.5 M_{\odot}$. For stars with masses between $0.5 M_{\odot}$ and $3 M_{\odot}$ (including the Sun), the helium core becomes degenerate. Thus, the onset of helium burning into carbon during the red giant stage is accompanied by a sharp, transient energy release, known as a helium flash. 

For stars with masses from $3 M_{\odot}$ to $8 M_{\odot}$, the evolution in the core occurs in non-degenerate conditions until a carbon-oxygen core is formed. After shedding their hydrogen envelopes on the asymptotic giant branch, they leave behind a white dwarf with a mass of up to $\sim 1.2 M_{\odot}$. Stars of $8 M_{\odot}$ to $10 M_{\odot}$ become carbon-oxygen white dwarfs with masses close to the Chandrasekhar limit of $M_{\odot}$.

A qualitatively new situation can arise if a white dwarf is part of a close binary system—under the influence of tidal forces, material transfer from the neighboring star to the white dwarf is possible, which can lead to an increase in its mass. As the white dwarf approaches the Chandrasekhar limit, thermonuclear burning begins in its center, leading to an explosion (this is the type Ia supernova model). The collapse of the white dwarf into a neutron star is also a possibility.## 8.2 Neutron Stars

In most cases, neutron stars are formed as a result of the collapse of the cores of massive stars (on the main sequence), which is accompanied by a Type II or Type Ib/c supernova explosion. The energy released during the collapse is roughly equivalent to the gravitational binding energy of the neutron star.

![Neutron Star Formation](https://images.astronet.ru/pubd/2002/05/14/0001176797/8lec/img18.gif)

The hallmark feature of neutron stars is their extraordinarily high density, on the order of nuclear density (about $\sim 10^{14} \, \text{g/cm}^3$). However, unlike a giant nucleus where nucleons are bound together by strong interactions between quarks, the degenerate neutrons in the star's matter do not decay: due to the high density, neutron decay is forbidden, as there is no "space" for the electron to form due to the strong degeneracy. The radius of neutron stars is weakly dependent on the poorly known equation of state at nuclear densities (protons and neutrons inside a neutron star behave as a superconducting, superfluid liquid) and is approximately 10 km. Such compactness combined with a mass on the order of the solar mass necessitates considering general relativistic effects when examining both the internal structure of neutron stars and the processes occurring in their vicinity. Like white dwarfs, neutron stars have a maximum mass known as the Oppenheimer-Volkoff limit, beyond which the star loses mechanical stability due to the combined effects of the relativistic degenerate neutron gas and general relativity. This limit is poorly defined due to the uncertainties surrounding the exact equation of state, but it is estimated to be around $1.5 - 3 \, M_{\odot}$. Rapid rotation (centrifugal forces) can enhance this limit by approximately 25%. Moreover, in close binary systems where mass is transferred from a normal (non-degenerate) star, exceeding the Oppenheimer-Volkoff limit will lead to collapse, forming a black hole.

In addition, neutron stars possess extraordinarily strong magnetic fields. Due to the frozen-in magnetic field within the cosmic plasma, during the compression of matter, the magnetic flux through a designated contour is conserved:

$$ \Phi \sim BR^{2} = \text{const}. $$

Thus, when a solar-type star with an average surface magnetic field strength of $B_0 \sim 1 \, \text{G}$ is compressed to the size of a neutron star of radius $R_{NS} = 10 \, \text{km}$, we obtain:

$$ B_{ns} = B_0 \left( \frac{R_\odot}{10} \right)^{2} \sim 5 \times 10^{11} \, \text{G}, $$

which is also observed in typical neutron stars known as pulsars.

The formation of superdense neutron stars during the collapse of massive star cores accompanying supernova explosions was proposed by astronomers Walter Baade and Fritz Zwicky in 1934, soon after the discovery of the neutron. Single neutron stars have been observed since 1967 as pulsars, with over 1500 known as of January 2001. The total number of neutron stars in the Galaxy is estimated at $\sim 10^{8} - 10^{9}$, with approximately $10^{5}$ of those being pulsars. Some neutron stars are part of binary systems. When material flows onto a neutron star with a strong magnetic field ($B \sim 10^{10} \, \text{G}$), the phenomenon of an *X-ray pulsar* is observed. If the magnetic field of the neutron star is not as strong, material accumulates on the surface of the neutron star (noting that it exists in a degenerate state). When a certain critical density and temperature threshold is exceeded on the surface of the neutron star, a thermonuclear explosion occurs. These explosions are observed as *X-ray bursters* (or bursting X-ray sources). For more detailed information, see the monographs by S. Shapiro and S. Teukolsky "Black Holes, White Dwarfs and Neutron Stars", Moscow: Mir, 1985, Vol. 2; V. M. Lipunov, "Astrophysics of Neutron Stars", Moscow: Nauka, 1987.## 8.3 Black Holes

Black holes (BH) of stellar mass can form either from the accretion-induced collapse of neutron stars in binary systems or from the collapse of the cores of massive single stars. This process is not well understood, even at a qualitative level. It remains unclear whether the formation of a black hole is accompanied by the shedding of a shell (i.e., the phenomenon of a supernova). The total number of black holes in the Milky Way may account for several percent of the number of neutron stars.

Physically, a black hole represents a peculiarity of spacetime associated with the existence of an *event horizon*—a light-like surface located at a specific distance from the center of the black hole, beyond which no information can escape outward. Figuratively speaking, the event horizon is akin to a one-way membrane that allows everything to enter in one direction while preventing anything from coming back out. A black hole can be characterized solely by its mass, angular momentum, and electric charge (i.e., all the possible conserved physical quantities). In the framework of General Relativity, the spacetime outside the event horizon of spherically symmetric black holes is described by the Schwarzschild solution (K. Schwarzschild, 1916). If a black hole has a non-zero angular momentum, the spacetime is described by the Kerr solution (W. Kerr, 1963), and if there is an electric charge, it is described by the Kerr-Newman solution. Black holes cannot possess a magnetic field. In this sense, a black hole is fundamentally simpler than a typical non-degenerate or degenerate star.

The event horizon of a non-rotating (Schwarzschild) black hole is located at the so-called gravitational radius:

$$ R_g = \frac{2GM}{c^2} \approx 3 \, \text{km} \left( \frac{M}{M_{\odot}} \right) $$

Finding a black hole from astronomical observations is challenging: a solitary black hole does not emit energy (the rate of quantum evaporation of a black hole, as proposed by S. Hawking in 1970, is inversely proportional to the square of its mass and is negligibly small for stellar-mass black holes). The efficiency of energy release during the free fall of matter onto a black hole from interstellar space is also low, and thus far, all attempts to identify such solitary black holes have been unsuccessful.

However, if a black hole is part of a close binary system, an *accretion disk* forms as matter flows from a neighboring star toward the black hole. This matter heats up to high temperatures, resulting in a bright X-ray source that can be observed. Modern observational methods have identified over 10 candidate black holes—undetected components of X-ray binary systems—whose masses exceed $20 - 40 M_{\odot}$, which are not X-ray pulsars or bursters (i.e., the infalling matter is neither directed by a magnetic field nor halted by a solid surface). For further details, refer to the review by A.M. Cherepashchuk, UFN Vol. 166, p. 809 (1996), and a more recent version by the same author (UFN 2002, in press).

The energy source for disk accretion is gravitational energy released as particles spiral inward within the accretion disk. Angular momentum from a particle can be removed by viscous forces (possibly related to the turbulence of magnetized plasma) or through oblique shock waves generated within the disk due to interactions between the outflowing matter jet from the neighboring star and the disk. Most of the energy and primary luminosity of the accretion disk is emitted near its inner boundary, which, in the case of neutron stars, is determined either by the radius of the magnetosphere of the rotating neutron star interacting with the disk plasma or by the neutron star surface if the pressure of its magnetic field cannot halt the infalling plasma. In the case of a black hole, the inner radius of the disk is defined by the last stable circular orbit of a test particle in the gravitational field of the black hole. For a non-rotating black hole, this radius is:

$$ R_{in} = 3R_{g} $$

For an extremally rotating Kerr black hole, it is given by:

$$ R_{in} = \frac{3}{2} R_{g} $$

The total energy emitted by a gas element falling from infinity must equal the binding energy of that element on the last stable circular orbit. This energy per gram of matter is:

$$ E_{bind} \approx 0.057c^{2} \text{ for non-rotating BH} $$

$$ E_{\text{bind}} \approx 0.42c^2 \text{ for maximally rotating BH} $$

The luminosity of the accretion disk around a black hole can be expressed as:

$$ L_d = E_{\text{bind}} \frac{dM}{dt} $$

This estimate indicates that accretion onto black holes has the highest known efficiency for converting rest mass into energy in nature. The luminosity of the accretion disk surrounding a black hole is remarkably significant.## 8.4 Pulsars

Let's take a closer look at solitary rotating neutron stars with strong magnetic fields. This is the best-studied class of neutron stars, comprising around 2000 objects (as of 2002).

Pulsating radio sources, known as pulsars, were discovered in 1967 (for which E. Hewish received the Nobel Prize in Physics in 1974). The main "unusual" properties of these objects are:

1. Short pulsation periods on the order of $0.0015 \, s$ - $0.01 \, s$. From this, we can immediately estimate the characteristic density of neutron star matter. Indeed, the limiting period of rotation for a star with mass $M$ and radius $R$ can be derived from the condition of balance between centrifugal force at the equator and gravitational force, given by:

   $$ P_{lim} = 2 \pi \sqrt{\frac{R^3}{GM}}. $$

   Therefore, the density estimate based on the observed rotation period yields:

   $$ \rho > \frac{12 \pi}{P^2 G} \sim 6 \times 10^{12} \left( \frac{P}{0.01 \, c} \right)^{-2} \frac{g}{cm^3}. $$

2. A slowdown of the pulsation period $\dot{P} \sim 10^{-15}$. This property is interpreted as the deceleration of the neutron star's rotation. Thus, the total rate of rotational energy loss from the neutron star is given by:

   $$ \frac{dE}{dt} = I\omega \dot{\approx} 4 \times 10^{37} \, [s \, p \, r / c] \left( \frac{I}{10^{45} \, \text{g} \, \text{cm}^{-2}} \right) \left( \frac{\dot{P}}{10^{-15} \, c/c} \right) \left( P \, 0.01 \right)^{-3} $$

   yielding $\approx 4 \times 10^{33}$.

3. Time delays in the arrival of pulses at different frequencies. This is related to the propagation of radiation in ionized cosmic plasma. Indeed, the group velocity of electromagnetic wave propagation in plasma is frequency-dependent:

   $$ v^{2}(\nu) = c^{2}\left(1 - \left(\frac{\nu_{0}}{\nu}\right)^{2}\right),$$

   where:

   $$ \nu_0^2 = \frac{4 \pi n e^2}{m_e}. $$

   The dispersion measure is defined as:

   $$ DM = \int n_e \, dl $$

   with $n_e = 0.03 \, \text{cm}^{-3}$.

4. An extraordinarily high brightness temperature of radiation. If the angular size of the radio source is $\theta$, the flux from it at a frequency $\nu$ is:

   $$ F_{\nu} \propto \frac{2kT_b \left( \frac{\nu}{c} \right)^{2}}{\Omega}, $$

   where 

   $$ \Omega \approx \pi \left( \frac{R_*}{r} \right)^{2}. $$

   It can be shown that the brightness temperature in the Rayleigh-Jeans limit is given by:

   $$ 2kTb \left( \frac{\nu}{c} \right)^{2} = F_{\nu} \Omega. $$

The main idea explaining the pulsar phenomenon (Pachining, Salvati; Ostriker, Gunn 1967) is the loss of rotational energy from a magnetized neutron star. The reservoir of rotational energy in a neutron star is considerable:

$$ E_r \sim 10^{49} \, erg $$ 

(order of the thermal energy of the Sun $\sim 3 \times 10^{48} \, erg$). In the simplest model, a rotating magnetic dipole in a vacuum is considered where the energy losses from magnetodipole radiation in vacuum can be expressed as:

$$ Q\vert pr/c\vert = \frac{2}{3} \frac{\mu^{2}}{c^{3}} = \frac{2}{3} \omega^{4} \frac{\mu_{0}^{2}}{c^{3}} $$.

Yet this is the complete rate of rotational energy loss of the neutron star. Low-frequency magnetodipole radiation cannot propagate in interstellar plasma.

An important quantity characterizing the pulsar is the concept of the light cylinder - the surface at which the solid body rotation speed, $\omega R$, reaches the speed of light:

$$ H(r < R_l) = H_s\left(\frac{r}{R}\right)^{3}. $$

From the expression for $\mu$, the law for the decay of pulsar rotation frequency with time can be derived:

$$ \dot{P}P = (2\pi)^{2}B_{s}^{2}R^{6}\Gamma^{-1}c^{-3}. $$

The characteristic deceleration time scale is crucial for understanding the age of pulsars. The differential equation governing the slowdown of the pulsar can be solved with the initial condition based on the observed period and its first derivative:

$$ \dot{P} = \frac{dP}{dt}. $$

The estimated pulsar age is sometimes referred to as its dynamic age.

### 8.4.1 Electrodynamics of Pulsars

Let's consider a simplified case where the magnetic dipole axis is parallel to the rotation axis (the Goldreich-Julian model). Formally, in this case, there is no pulsar effect (the flow of relativistic particles is directed along the rotation axis and does not pulse for the observer); however, this example allows us to demonstrate how the rotation of a neutron star decelerates.

In a spherical coordinate system with the axis along the rotation, the components of the dipole magnetic field's intensity are given as:

$$ E_{\theta} = \frac{B_s}{2} \left( \frac{R}{r} \right)^{3}, $$

and in this case, only the tangential component of speed differs from zero.

Assuming the neutron star is an ideal conductor. The points on the surface of the sphere move with speed:

$$ v = \omega R $$

, and in our case, only the tangential component of speed is relevant.

The Lorentz force acts on electric charges $F = q(\vec{E} + \vec{v} \times \vec{B})$ leading to charge separation and the appearance of an external electric field:

$$ E_r = \frac{B_s^2 R^2}{2}. $$

Charges cease to move when, in the rotating reference frame, the electromotive force equals zero:

$$ E_{\theta} = - \frac{d\Phi}{dt}. $$

Expressions demonstrate that in the regions of magnetic poles, the radial component of the electric field is parallel to the lines of magnetic force. Thus, in these areas, charge separation from the surface and acceleration can occur. 

By evaluating the dipole magnetic moment for a typical field at the surface of a neutron star, the implications of relativistic particles moving along open magnetic field lines with relativistic velocities result in the generation of electromagnetic radio waves directed in a narrow beam. This high-frequency non-thermal radio emission is what we detect from pulsars.

Approximately 100 radio pulsars are observed in binary systems, typically accompanying white dwarfs. There are some double pulsars with a neutron star as the secondary component. Pulsars paired with black holes have not yet been discovered. Notably, binary pulsars consisting of two neutron stars present significant interest from a fundamental physics standpoint. When the orbital period is sufficiently short (less than 15 hours), notable effects from general relativity must be considered — such as alterations in the physical parameters of the orbit due to the loss of orbital energy and angular momentum via gravitational waves.

The first binary pulsar of this kind, PSR 1913+16, has been studied for over 20 years, with general relativistic effects validated with an accuracy greater than $10^{-5}$. A centennial reduction in the period of this pulsar due to gravitational wave radiation has been reliably established. The American astrophysicists J. Taylor and R. Hulse received the Nobel Prize in Physics in 1993 for their discovery and high-precision long-term observations of this pulsar, which contributed significantly to fundamental physics.## 8.4 Pulsars

### Literature
1. S. Shapiro, S. Tykhonov, "Black Holes, White Dwarfs, and Neutron Stars," Moscow: Mir, 1985, Vol. 2;
2. V.M. Lipunov, "Astrophysics of Neutron Stars," Moscow: Nauka, 1987;
3. V.S. Beskin, "Radio Pulsars," Uspekhi Fizicheskikh Nauk 169, No. 11 (1999), p. 1169.

---

**Publications with keywords:**  
- [Stars](http://db/search.html?kw=13809)  
- [Interstellar Medium](http://db/search.html?kw=14142)  
- [Cosmology](http://db/search.html?kw=15891)  
- [Theoretical Astrophysics](http://db/search.html?kw=10526)  
- [Astrophysics](http://db/search.html?kw=16508)

**Publications with terms:**  
- [Stars](http://db/search.html?words=%E7%E2%E5%E7%E4%FB)  
- [Interstellar Medium](http://db/search.html?words=%CC%E5%E6%E7%E2%E5%E7%E4%ED%E0%FF%20%F1%F0%E5%E4%E0)  
- [Cosmology](http://db/search.html?words=%CA%EE%F1%EC%EE%EB%EE%E3%E8%FF)  
- [Theoretical Astrophysics](http://db/search.html?words=%F2%E5%EE%F0%E5%F2%E8%F7%E5%F1%EA%E0%FF%20%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0)  
- [Astrophysics](http://db/search.html?words=%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0)

### See also:
- ![APOD](http://images.astronet.ru/si/apod.gif) [A black hole destroys a star: animation](http://db/msg/1931410)  
- ![APOD](http://images.astronet.ru/si/apod.gif) [Stars, dust, and nebula in NGC 6559](http://db/msg/1904844)  
- ![APOD](http://images.astronet.ru/si/apod.gif) [25 brightest stars in the night sky](http://db/msg/1863796)  
- ![APOD](http://images.astronet.ru/si/apod.gif) [Animation: a black hole destroys a star](http://db/msg/1736616)  
- ![APOD](http://images.astronet.ru/si/apod.gif) [Decomposition of distant light](http://db/msg/1696356)  
- ![APOD](http://images.astronet.ru/si/apod.gif) [Comparison of star sizes](http://db/msg/1415428)  
- ![APOD](http://images.astronet.ru/si/apod.gif) [The most distant of all known stars?](http://db/msg/1406555)  

[All publications on the same topic >>](http://db/search.html?kw=13809&kw=14142&kw=15891&kw=10526&kw=16508)  

---

Readers' opinions: [70](http://db/forums/1170612)  

Rating: 3.1 [votes: 182] 

**Rate this:**  
- --Rate--  
- Excellent  
- Good  
- Average  
- Poor  
- Unsatisfactory  

---

[Print Version](http://db/print/msg/1170612/8lec/node6.html)

---

**Astrometry** - **Astronomical Instruments** - **Astronomical Education** - **Astrophysics** - **History of Astronomy** - **Cosmonautics, Space Exploration** - **Amateur Astronomy** - **Planets and the Solar System** - **The Sun**  ## 9. Galaxies and Quasars

### Sections
- [9.1 Galaxies. General Information.](https://db/msg/1170612/9lec/node2.html)
- [9.2 Quasars and Active Galactic Nuclei.](https://db/msg/1170612/9lec/node3.html)
- [9.3 The Eddington Limit of Luminosity During Accretion on Compact Relativistic Objects](https://db/msg/1170612/9lec/node4.html)
- [9.4 Black Holes in the Centers of Normal Galaxies and the Relation Between Black Hole Mass and Bulge Mass](https://db/msg/1170612/9lec/node5.html)

---

### Publications with Keywords:
- [stars](http://search.html?kw=13809) - [Interstellar Medium](http://search.html?kw=14142) - [Cosmology](http://search.html?kw=15891) - [Theoretical Astrophysics](http://search.html?kw=10526) - [Astrophysics](http://search.html?kw=16508)

### Publications with Words:
- [stars](http://search.html?words=%E7%E2%E5%E7%E4%FB) - [Interstellar Medium](http://search.html?words=%CC%E5%E6%E7%E2%E5%E7%E4%ED%E0%FF%20%F1%F0%E5%E4%E0) - [Cosmology](http://search.html?words=%CA%EE%F1%EC%EE%EB%EE%E3%E8%FF) - [Theoretical Astrophysics](http://search.html?words=%F2%E5%EE%F0%E5%F2%E8%F7%E5%F1%EA%E0%FF%20%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0) - [Astrophysics](http://search.html?words=%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0)

### See also:
- [Black Hole Destroying a Star: Animation](https://db/msg/1931410)
- [Stars, Dust, and Nebula in NGC 6559](https://db/msg/1904844)
- [25 Brightest Stars in the Night Sky](https://db/msg/1863796)
- [Animation: Black Hole Destroying a Star](https://db/msg/1736616)
- [Decomposition of Distant Light](https://db/msg/1696356)
- [Comparison of Star Sizes](https://db/msg/1415428)
- [Farthest Star Known?](https://db/msg/1406555)

[All Publications on the Same Topic >>](http://search.html?kw=13809&kw=14142&kw=15891&kw=10526&kw=16508)

---

### Reader Feedback
*Rating: 3.1 [Votes: 182]*

---

### Print Version
[Printable Version](https://db/print/msg/1170612/9lec/node1.html)

---

### Topics of Interest
- **[Astrometry](https://db/sect/300000007)** 
- **[Astronomical Instruments](https://db/sect/300000010)** 
- **[Astronomical Education](https://db/sect/1168516)** 
- **[Astrophysics](https://db/sect/300000003)** 
- **[History of Astronomy](https://db/sect/300000016)** 
- **[Cosmonautics, Space Exploration](https://db/sect/300000012)** 
- **[Amateur Astronomy](https://db/sect/300000013)** 
- **[Planets and the Solar System](https://db/sect/300000005)** 
- **[The Sun](https://db/sect/300000004)** 

---## 9.1 Galaxies. General Information.

The formation of large-scale structures is a consequence of the growth of small density perturbations due to gravitational instability. As will be demonstrated in Lecture 12, the characteristic Jeans masses immediately after the recombination epoch lie in the range of $10^{6} - 10^{12} M_{\odot}$, extending from the scale of globular star clusters to galaxy clusters. We have also noted that the structure of the Universe could not have formed without the presence of dark matter. According to current understanding, the formation of observable galaxies and stars began at redshifts $z < 10$. Recent observations (1996-1997) from the Hubble Space Telescope and other studies suggest that the peak rate of star formation may have occurred at redshifts $z_{max} \sim 1.5 - 2$, reaching about $\sim 10M_\odot$ per year in a typical galaxy with a mass on the order of $10^{11} M_{\odot}$. The total number of galaxies in the Universe is no less than $10^{10}$ (assuming that visible matter is concentrated in "typical" galaxies of a mass around $10^{11} M_{\odot}$). There exists a large number of faint dwarf galaxies that are difficult to detect. However, the mass fraction contained in them apparently does not exceed that concentrated in giant star systems.

The process of galaxy formation in response to perturbations is quite complex, and there is still no definitive understanding of this issue. However, it is crucial that the type of galaxy that forms (spiral or elliptical) is primarily determined by the angular momentum of the gas that is collapsing under gravitational instability. The total angular momentum of the Universe is zero (at least, there is no indication to the contrary, as far as we can assert isotropy). It is evident that local gravitational interactions of density perturbations lead to the emergence of angular momentum in a gravitationally bound system. The presence of significant angular momentum results in gravitational collapse primarily occurring along the vector of angular momentum (the axis of rotation). This leads to the formation of disk-like systems—spiral galaxies.

A distinctive feature of spiral galaxies is the presence of a well-defined disk where gas and dust reside (up to 10% of the disk's mass). The main process of star formation occurs in the disks of spiral galaxies from gas. It can be shown that differentially rotating self-gravitating disks are unstable to the formation of spiral density waves (spiral arms), which generally rotate as a coherent whole in the direction of galaxy rotation. As a spiral arm traverses the gaseous disk, a shock wave forms, compressing the gas, which triggers star formation processes. Between spiral arms, the star formation process is significantly suppressed. The characteristic radius of galaxy disks is around 10-15 kpc, with the thickness of the stellar disk being about 1-2 kpc, while the gas disk is considerably thinner, around 200 pc.

In addition to the thin disk containing gas, dust, and massive young stars (the so-called population I), spiral galaxies possess a spherical subsystem of stars (the so-called bulge) whose total angular momentum is close to zero. The bulge contains low-mass (less than or around the mass of the Sun) old stars (the so-called population II), which move in elongated orbits around the galactic center; essentially, the bulge resembles an elliptical galaxy. It is possible that the bulge subsystem in spiral galaxies (including our own) formed as a result of the collision of primordial spiral and irregular galaxies.

In another extreme case, where the angular momentum is initially low, quasi-spherical (ellipsoidal) gravitationally-bound systems—elliptical galaxies—are formed. Elliptical galaxies are characterized by an almost complete absence of gas, which results in a low rate of star formation in the modern epoch. Elliptical galaxies can also arise from the interaction (collision) of several spiral galaxies with differently directed angular momentum. Stars in elliptical galaxies move in elongated orbits within a common gravitational potential. A characteristic feature of elliptical galaxies and the population II (bulge) in spiral galaxies is the metal-poor chemical composition compared to the younger population in the disks of galaxies. This is associated with the older age of population II stars and the enrichment of interstellar gas by products of nuclear evolution of stars and supernova explosions occurring in the galaxy disks.

In addition to spiral and elliptical galaxies, there exists a relatively small class of irregular (or, as they are also called, irregular) galaxies with an indistinct shape, comprising no more than 10% of all galaxies. Typically, the masses of irregular galaxies are less than $10^{10} M_{\odot}$. These galaxies contain a significant amount of gas (up to 50% of their mass) and engage in active star formation, even though their chemical composition is poor in metals. This indicates their relative youth. An example of irregular galaxies includes the Magellanic Clouds—companions of our Galaxy—located about 60 kpc away.

Due to the great complexity of examining the structure and evolution of galaxies composed of billions of objects, it is challenging to provide a detailed description of all the physical processes occurring within these stellar systems. Therefore, in this area of astrophysics, phenomenological relationships and dependencies—albeit with deep physical content—are frequently employed.## 9.2 Quasars and Active Galactic Nuclei

Galaxies exhibit great diversity. Among them are galaxies with active nuclei, where there is immense energy release. The class of active galactic nuclei includes quasars, Seyfert galaxies, radio galaxies, and BL Lacertae objects.

### 9.2.1 Main Observable Properties

In 1960, radio sources with small angular sizes (less than 10 arc seconds) were discovered, which were subsequently identified with star-like objects in the optical range. (Quasar is an abbreviation for "QUASi-stellAR Radio source.") In 1963, Martin Schmidt obtained the spectrum of the source 3C 273. The spectrum displayed broad emission lines from the Balmer series of hydrogen and singly ionized magnesium (Mg II), and the redshift was found to be $z = 0.158$ (which corresponds to a distance of $d \simeq \frac{zc}{H_0} = 630$ Mpc). Currently, around 10,000 quasars are known, with the maximum redshift from which quasars are observed exceeding $z_{\text{max}} \sim 6$!

The main phenomenological properties of quasars are as follows:

1. **Large Redshift** (distant objects), $z \sim 1.5 - 2$.
2. **Non-thermal (power-law) continuous spectrum** of electromagnetic radiation across the entire range of wavelengths: $F(\nu) \propto \nu^{-\alpha}$.
3. **Broad emission lines** in allowed transitions (widths up to 2000 km/s) and narrow forbidden emission lines (similar to those in gas nebulae).
4. **Variability of radiation** $\Delta t$ over timescales from several days to several months, which provides an estimate of the characteristic size of the emitting region: 
   $$R = c \Delta t = 3 \times 10^{16} - 3 \times 10^{17} \text{ cm} \quad ( < 1 \text{ pc})$$
5. **Immense luminosity**, $L \approx 10^{46} - 10^{47} \text{ erg/s}$ (for comparison, the total luminosity of a giant spiral galaxy like our own is $\sim 10^{45} \text{ erg/s}$).
6. **Often, a "host" galaxy** with various morphologies (either elliptical or spiral) is visible around the quasar. Frequently, active nuclei are observed in interacting (merging) galaxies.
7. **Relativistic jets** of particles at speeds up to 0.99c are often observed, visible in the radio band at distances of several megaparsecs.

Similar properties (though somewhat on a smaller scale) are observed from active galactic nuclei (radio galaxies, Seyfert galaxies, and BL Lacertae objects). The high luminosity and compactness of the emitting region determine the physical conditions of the matter near the center of quasars.

*Example*: Let's estimate the radiation density at a characteristic distance of $R \sim 10^{15} \text{ cm}$ from the center of a quasar with luminosity $L \sim 10^{47} \text{ erg/s}$:
$$\rho_r = \frac{L}{4 \pi r^2} \frac{1}{c} \approx 2 \times 10^5 \text{ erg/cm}^3$$
This value is several orders of magnitude greater than the energy density of the relic radiation (about $10^{-12} \text{ erg/cm}^3$) or UV radiation from stars in our Galaxy (approximately $10^{-2} \text{ erg/cm}^3$).

Active galaxies and quasars constitute a relatively small subclass of objects (in other words, the phase of quasar or galactic nucleus activity is much shorter than the Hubble time, which is around $10^{10}$ years). Their spatial density is as follows:
- Ordinary galaxies: $ \sim 10^3$ per cubic Mpc
- Seyfert galaxies: $ \sim 10^2$ per cubic Mpc
- Radio galaxies: $ \sim 10$ per cubic Mpc
- Quasars: $ \sim 1$ per cubic Mpc

According to modern understanding, the phenomenon of active galactic nuclei is related to a specific phase in the evolution of galaxies, during which supermassive black holes formed at their centers. The peak of such galaxies' formation occurred during an epoch characterized by a redshift of $z \sim 2$. It seems that it was at these redshifts that the most active interactions between galaxies took place, initiating active star formation and enriching the central regions of galaxies with gas, which "feeds" the supermassive black hole at the center.

### 9.2.2 Mechanisms of Galactic Nuclei Activity

Historically, three main mechanisms for energy generation in a compact region at the center of galaxies have been proposed:

1. **Supernova Outbursts** in a compact stellar cluster at the center of the galaxy. This model was quickly dismissed after the variability of nuclear emissions was observed.

2. **Supermassive Star**, whose equilibrium is maintained by rotation and magnetic fields (L. M. Ozernoy). This predicts periodic emissions (which are not observed) and has problems with the stability of such a configuration.

3. **Accretion** (from the Latin "accretio," meaning "to grow together") of matter onto a supermassive black hole.

The last model is the most developed, and it explains many observational properties (high luminosity, compactness, spectra). We will examine it in more detail, as it illustrates the crucial role of accretion in astrophysics in general.

### 9.2.3 Accretion Model on a Supermassive Black Hole

The existence of massive black holes in the centers of galaxies arises from general evolutionary considerations, which we do not discuss here due to space constraints. By 1997, supermassive black holes had been detected in approximately 10 galaxies based on the motion of stars and gas.

M87 - $M_{bh} \approx 6.4 \times 10^9 M_{\odot}$

NGC 3115 - $M_{bh} \approx 1.5 \times 10^8 M_{\odot}$

NGC 4486 - $M_{bh} \approx 3.0 \times 10^9 M_{\odot}$

NGC 4594 (Sombrero) - $M_{bh} \approx 1.0 \times 10^9 M_{\odot}$

NGC 3377 - $M_{bh} \approx 1.5 \times 10^8 M_{\odot}$

NGC 3379 - $M_{bh} \approx 1.4 \times 10^8 M_{\odot}$

NGC 4258 - $M_{bh} \approx 3.6 \times 10^7 M_{\odot}$

M31 (Andromeda) - $M_{bh} \approx 1.0 \times 10^8 M_{\odot}$

M32 - $M_{bh} \approx 2.5 \times 10^7 M_{\odot}$

This list is constantly being updated, and by 2002 the number of galaxies with measured central black hole masses exceed 50 (see also the last paragraph of this lecture).

The masses of the black holes are determined from observations of the movement of stars and gas in the centers of galaxies using the Hubble Space Telescope. Indeed, established (steady-state) motions of stars near a black hole must adhere to the virial theorem:
$$\frac{1}{2} \langle v^2 \rangle = - \langle U \rangle$$ 
Where:
$$U = -\frac{GM_{bh}}{r}$$
Thus, the velocity dispersion of stars or the circular velocity of gas at a distance $r$ from the center of the galaxy can be expressed as:
$$v^2 \sim \frac{GM_{bh}}{r}$$
By measuring the Doppler effect to determine speeds at angular distances from the center of the galaxy and knowing the distance to the galaxy, estimates can be made for the mass of the central black hole.

The mass of the black hole at the center of our Galaxy is on the order of $M_{bh} \approx 4.1 \times 10^6 M_{\odot}$ and also has been defined through precise measurements of the proper motion of individual stars (since the center of the Galaxy is opaque to optical rays, measurements were conducted in the infrared range).

### 9.2.4 Efficiency of Accretion onto Black Holes

As is well known, a black hole is described by three parameters: mass $M$ (Schwarzschild black hole), angular momentum $J$ (Kerr black hole), and electric charge $Q$ (Kerr-Newman black hole). The event horizon of a Schwarzschild black hole (the so-called gravitational or Schwarzschild radius) is defined by the equation:
$$R_g = \frac{2GM_{bh}}{c^2} \approx 3 \, \text{KM} \left( \frac{M_{bh}}{M_{\odot}} \right)$$

In Newtonian approximation, when matter falls onto a gravitating body of mass $M$ with a radius $R$, the gravitational energy released per gram of matter upon falling is given by:
$$E = -\frac{GM \Delta m}{R}$$

If the object has a surface (for example, a star), gravitational energy is released in the form of heat upon impact with the surface. However, since a black hole does not have a surface, specific modes of fall are required for gravitational energy to be released. 

For instance, in a strictly spherically symmetric mode of infall onto a black hole, the efficiency of energy release is fully determined by the physical conditions in the falling plasma (density, temperature, magnetic field) and is usually very low, $\eta < 1$. 

Under realistic astrophysical conditions, plasma generally possesses a non-zero angular momentum $L$, which leads to the emergence of a centrifugal barrier when falling into the gravitational field of a body:
$$U_{eff}(r) = -\frac{GM}{r} + \frac{L^2}{2mr^2}$$ 

For a particle moving in a circular Keplerian orbit with radius $r$:
$$v_{\phi} = \sqrt{\frac{GM}{r}}$$
$$\omega(r) = \sqrt{\frac{GM}{r^3}}$$ 

Thus, distinct from zero shear stresses appear in the rotating gas disk, represented as:
$$\sigma_{r\phi} = r\left(\frac{\partial \omega}{\partial r}\right) = -\frac{3}{2}\omega$$

In the presence of viscosity, the shear stress (which is the frictional force acting per unit area) is given by:
$$W_{r\phi} = \eta \sigma_{r\phi}$$ 

If the coefficient of dynamic viscosity $\eta$ is non-zero, viscous forces acting on an annulus of radius $R_i$ lead to changes in its angular momentum. The viscosity mechanism in accretion disks is not entirely understood; however, it is widely believed that viscosity is linked to turbulent motions in the differentially rotating gas disk. Possibly, magnetic fields frozen into cosmic plasma play an important role in the turbulence of the disk.

Thus, when viscosity is present, angular momentum is transferred through viscous stresses radially outward along the disk, leading the matter to gradually approach the central body. This process is diffusion-like. As a result of frictional forces, the gas heats up to high temperatures, and the released gravitational energy is converted into electromagnetic radiation. Such disks (with viscosity, unlike Saturn’s rings) are called *accretion disks*. They arise in binary star systems during mass transfer from one star to another (such phenomena are possible during the evolutionary expansion of one of the stars). Accretion disks can also form near supermassive black holes at the centers of active galaxies or quasars. The matter for the disk is supplied by stars that are torn apart by tidal forces when they fly near the black hole. Since the stars' angular momentum relative to the black hole is non-zero (especially in spiral galaxies), matter forms a disk. Currently, gaseous-dust disks of small sizes in the nuclei of galaxies are directly observed in the optical and infrared ranges, both from the Hubble Space Telescope and by large ground-based telescopes.

Accretion disks around black holes as energy sources for active galactic nuclei and quasars were quantitatively investigated by D. Lynden-Bell and J. Pringle in 1969. The theory of stationary accretion disks onto compact objects in binary systems was developed in works by Soviet astrophysicists N. I. Shakura (1972) and N. I. Shakura and R. A. Sunyaev (1973). 

Analysis shows that the total luminosity of an accretion disk does not depend on the mechanism of viscosity and is defined by boundary conditions—the rate of inflow of matter into the disk, $\dot{M}$, the radius of the inner edge of the disk $R_{in}$, and the specific angular momentum at the inner boundary. If the matter in the disk moves along Keplerian orbits down to the very inner boundary, its total luminosity is given by:
$$L_d = \frac{1}{2} \frac{GM \dot{M}}{R_i}$$

The energy release in the disk is often written as:
$$\frac{dE}{dt} = G \frac{\dot{M} M}{R} = \eta \dot{M} c^2$$

Where $\eta \approx \frac{1}{2}\left(\frac{R_g}{R}\right)$. In cases where $\eta$ is very small, the overall efficiency of energy release is considerably reduced, often resulting in $\eta \ll 1$.

### 9.2.5 Tidal Disruption of Stars Near a Supermassive Black Hole

Gas can enter the accretion disk via various pathways: from the interstellar gas in the galaxy disk, diffusing due to dynamical frictions, or from stars that are torn apart by the tidal forces of the black hole. We will consider the latter process (Hills, 1975). Assume there is a star with a mass $M_* = 10^{*/} M_{\odot}$ and a radius comparable to $R_*$. The average density of the star can be given as $\rho_* = \frac{M_*}{R_*^3}$. A star gets disrupted by tidal forces when the gravitational acceleration at its surface becomes less than the tidal acceleration from the black hole’s gravitational field of mass $M_{bh}$:

$$g = \frac{GM_{bh}}{d^2}$$

The disruption occurs at a critical distance (known as the tidal radius): 

$$r_t \sim \left( \frac{M_{bh}}{M_{*}} \right)^{1/3} R_{*} \sim \left( \frac{M_{bh}}{\rho_{*}} \right)^{1/3}$$

It is evident that the event horizon (gravitational radius) of the black hole varies linearly with mass:

$$r_g \sim M_{bh}$$ 

The tidal radius increases with black hole mass while remaining less than the event horizon. For a supermassive black hole, we can expect considerable stellar destruction leading to variable accretion rates, which contributes to the overall energetics and output observed in active galactic nuclei and quasars.## 9.3 Eddington Limit of Luminosity During Accretion onto Compact Relativistic Objects

Let us consider a plasma at a distance $r$ from a star with luminosity $\mathcal{L}$. Suppose the radiation source is isotropic. Then, at a distance $r$, the radiation flux is given by:

$$F = \frac{L}{4\pi r^{2}}.$$

Photons interact with the electrons in the plasma (Thomson scattering) and exert pressure with a force 

$$F_r = \frac{F}{c \sigma_T},$$

where 

$$\sigma_T = \left( \frac{8\pi}{3} \right) \left( \frac{e^2}{m_e c^2} \right)^2 \sim 6.71 \times 10^{-25} \, \text{cm}^2$$ 

is the Thomson scattering cross-section for a photon on an electron (in the non-relativistic approximation). The gravitational force from the central body of mass $M$ acting on protons is given by $F_g = F_r$. 

Due to Coulomb forces, the light pressure on the electrons is transmitted throughout the plasma element, and equilibrium 

$$F_g = F_r$$ 

is maintained at a critical luminosity value (the so-called *Eddington limit*).

![Eddington limit equation](https://images.astronet.ru/pubd/2002/05/14/0001176797/9lec/img98.gif)  
*Figure 9.7: Eddington limit equation*

Let us apply this reasoning to accretion onto compact objects. The luminosity released is 

$$L_a = \left( \frac{1}{2} \right) \frac{GM \dot{M}}{R_{in}} = \eta \dot{M}c^2,$$ 

where $R_{in}$ is the inner radius of the accretion disk (approximately $3R_{g}$ for a Schwarzschild black hole). The maximum accretion rate, at which it can still occur (i.e., without being halted by radiation pressure), is given by 

$$\dot{M}_{cr} = \frac{L_{Edd}}{\eta c^2} \simeq 10^{-8} M_{\odot} / \text{year} \left( \frac{M}{M_{\odot}} \right).$$

The critical mass accretion rate is approximately $\dot{M}_{cr} \sim 1 M_{\odot}$.

A classical example of a binary system in which super-critical accretion onto a compact object occurs is SS433, a massive binary star from which tightly collimated jets of matter are observed, moving at speeds greater than $0.26c$. Binary systems with relativistic jets are referred to as *galactic microquasars*. The compact stars in most of them have masses greater than $3M_{\odot}$ and are reliable candidates for black holes. It seems that super-critical accretion onto a black hole is always accompanied by the formation of relativistic jets; however, the mechanism for their formation is not yet fully understood.

It is also noteworthy that for accretion rates onto a black hole that are much smaller than $\dot{M}_{cr}$, a mode of matter falling can be established such that the heat generated by friction does not manage to escape from the disk as radiation and is dragged along with the matter under the event horizon of the black hole (the so-called *advection-dominated accretion flow*). This specific mode, associated with the presence of a horizon in a black hole, leads to the emission from the accretion disk being significantly less than what is predicted by the standard formula (refer to equation (9.4)). This phenomenon may explain the anomalously low emission from the vicinity of the black hole at the center of our Galaxy and in several other cases.## 9.4 Black Holes in the Centers of Normal Galaxies and the Black Hole - Bulge Mass Relationship

Observations of the central regions of galaxies and quasars from 1995 to 2001, conducted using the Hubble Space Telescope, revealed an important correlation between the dynamically determined mass of the central black hole and the mass of the spheroidal component of the galaxy (in the case of elliptical galaxies, this corresponds simply to the mass of the galaxy itself), as defined by the mass-luminosity relationship:

$$
\log\left(\frac{M_{\mathrm{bulge}}}{M_{\odot}}\right) \simeq 1.18\log\left(\frac{L}{L_{\odot}}\right) - 1.11.
$$

For both normal galaxies and active galactic nuclei, the mass of the central black hole is proportional to the mass of the bulge over a wide range of bulge masses from $10^{9}$ to $10^{12}M_{\odot}$.

This proportionality indicates a genetic link between the central black hole and the spheroidal subsystem of stars in the galaxy. It is believed that the growth of the black hole's mass may be associated with gas accretion processes directed toward the center, ejected during the evolution of stars within the bulge. The bulge itself may either result from the merger of spiral galaxies or arise due to instabilities in the central regions of galaxy discs, leading to the ejection of low-mass stars from the disc into the bulge.

![Black Hole Mass and Bulge Mass Correlation](https://images.astronet.ru/pubd/2002/05/14/0001176797/9lec/img113.gif)

**Figure 1:** Correlation between black hole mass and bulge mass in galaxies.## 10. Cosmology

Cosmology studies the physical structure and evolution of the observable part of the Universe (sometimes referred to as the Metagalaxy) on large scales (tens and hundreds of megaparsecs or more) and additionally examines the evolution of our Universe as a whole. Data is collected using standard astrophysical methods by observing the distribution of galaxies and clusters of galaxies (large-scale structure of the Universe) in various wavelength ranges, and separately, the properties (temperature and its spatial fluctuations) of the cosmic microwave background radiation. Moreover, cosmological models are constructed for the Universe as a whole—logically consistent frameworks based on current theoretical understandings of spacetime (theory of gravity) and elementary particles, describing the entire set of known observational facts about the Universe with minimal arbitrary assumptions. 

In our general overview, we will employ the most developed cosmological models based on Albert Einstein's General Theory of Relativity (GTR) or its extension by introducing a cosmological constant (Einstein, 1916). We will also utilize the "standard model" of particle physics and its extensions (scalar field in the inflationary model), which have been well-validated in experiments up to energy scales of about 1 TeV. This implies that we will describe modern cosmology from contemporary perspectives, omitting details of historically important but now outdated or incomplete models. Cosmology seems to be the most dynamically evolving area of modern astrophysics. Its importance to physics as a whole is determined by its ability to indirectly test fundamental physical laws at energy levels up to Planck values (approximately $10^{19}$ GeV) by comparing observed data with theoretical predictions. It is widely recognized that any serious physical theory of fundamental interactions should provide predictions that can be experimentally verified in the laboratory and, in cases of very high energies, should not conflict with contemporary cosmological data. 

![Cosmological Diagram](https://images.astronet.ru/pubd/2002/05/14/0001176797/10lec/img7.gif) 

**Figure: Energy Levels in Cosmology**## 10. Friedmann Cosmology

In this section, we will examine homogenous and isotropic cosmological models of the universe, first considered by A.A. Friedmann in 1922, which bear his name.

### 10.1.1 The Cosmological Principle

Similar to the principle of the constancy of the speed of light or the principle of equivalence (which underpins general relativity), modern cosmological models are based on the **cosmological principle**, which posits that there should be no privileged observers in the universe. This principle is sometimes referred to as the "Copernican principle," as Copernicus was the first in modern history to abandon the geocentric model of the universe. This principle implies that the global characteristics of the universe are the same for any observer located at any point on a hypersurface of constant time.

This principle has been confirmed with great precision by astronomical observations of the uniformity of matter distribution in the universe on large scales (about $> 100 \, \text{Mpc}$) and isotropy (the absence of a preferred direction at the level of fluctuations in the temperature of the cosmic microwave background). Even this evidence is sufficient to narrow down the multitude of possible mathematical models describing the universe as a whole to a quite narrow class of homogeneous and isotropic spaces (the so-called Friedmann-Robertson-Walker models). For more detailed information, see the unparalleled monograph by S. Weinberg "Gravitation and Cosmology," Moscow: Mir, 1975, Chapter 13 and beyond.

### 10.1.2 "A Brief Course" in the History of 20th Century Cosmology

A very schematic outline of the recent history of modern cosmology can be traced through the dates of the most important observational and theoretical discoveries:

- **1910-1922**: V. Slipher, redshifts in galaxy spectra  
    ![](https://images.astronet.ru/pubd/2002/05/14/0001176797/10lec/img10.gif)
  
- **1916**: A. Einstein, General Theory of Relativity

- **1922-24**: A. Friedmann, non-stationary solutions to Einstein's equations (Friedmann cosmological models)

- **1929**: E. Hubble, the law $v = Hr$ for receding galaxies. The recession velocity of a galaxy is determined by its redshift, interpreting it through the Doppler effect for small $v$.  
    ![](https://images.astronet.ru/pubd/2002/05/14/0001176797/10lec/img15.gif)  
    **Figure 10.1**: Hubble diagram (the dependence of recession velocity (in km/s), measured by redshift, on distance (in Mpc)) for type Ia supernovae. The tangent of the angle of the slope of the line approximating this dependence gives the current value of the Hubble constant $H \sim 70 \, \text{km/s/Mpc}$.

- **1933**: F. Zwicky, hidden mass in galaxy clusters

- **1949**: Alpher, Bethe, Gamow - the "hot universe" hypothesis ("Big Bang") and the prediction of isotropic relic radiation with an equilibrium spectrum at a temperature of about $T \sim 5 \, \text{K}$.

- **1965**: A. Penzius, R. Wilson - the discovery of isotropic cosmic microwave background radiation with a temperature of about 3 K.  
    ![](https://images.astronet.ru/pubd/2002/05/14/0001176797/10lec/img17.gif)  
    **Figure 10.2**: Spectrum of cosmic microwave (relic) radiation. The solid curve is the Planck function for a black body with a temperature $T = 2.728 \, \text{K}$.

- **1979-80**: A. Guss, A.A. Starobinsky, A.D. Linde, D.A. Kirzhnits - the "inflationary" universe hypothesis

- **1992-1993**: In the cosmic experiments "Relikt" (Russia), "COBE" (USA) fluctuations of the relic radiation were discovered at a level $\sim 10^{-5}$ on scales of around 10 degrees.

- **1998**: Hubble diagrams (the dependence of apparent magnitude at peak brightness - redshift) for Type Ia supernovae (thermonuclear explosions of white dwarfs near the Chandrasekhar limit) show that at large distances, the expansion of the universe occurs with acceleration. This indicates the necessity of introducing a positive cosmological constant (Einstein, 1917) or a more complex form of matter (so-called "dark energy" or "quintessence") with an equation of state $P = -w \epsilon \; (w < 1)$, which makes the dominant contribution today to the energy density of the universe ($\sim 80\%$) and effectively creates anti-gravity on large scales.

- **2000**: Measurement of the angular spectrum of fluctuations of the relic microwave radiation in the BOOMERanG and MAXIMA experiments. Discovery of the first Doppler peak in the angular spectrum of fluctuations on scales of about 1 degree, predicted by A.D. Sakharov in 1967 (the so-called "Sakharov oscillations"). Evidence of flat (Euclidean) geometry of the spatial sections of the observable universe with an accuracy of about 10% up to redshifts $z \sim 1000$ (the era of recombination).  
    ![](https://images.astronet.ru/pubd/2002/05/14/0001176797/10lec/img23.gif)  
    **Figure 10.3**: Map of fluctuations in cosmic microwave radiation on scales from 5 arcminutes to several degrees based on data from the BOOMERanG experiment (left map) and MAXIMA (right map).

    ![](https://images.astronet.ru/pubd/2002/05/14/0001176797/10lec/img24.gif)  
    **Figure 10.4**: The angular spectrum of fluctuations in relic radiation based on BOOMERanG, MAXIMA, and QMASK experiments. The position of the first peak at $l_{first} \sim 200$ corresponds to the flat geometry of the spatial sections of the universe ($\Omega_k = 0$).

Despite the enormous progress in modern cosmology, many important questions remain unresolved:

1. The problem of non-baryonic dark matter (observed matter accounts for only a few percent of the total gravitational mass).

2. The problem of the cosmological constant (or why the enormous energy of zero-point fluctuations of the vacuum is not visible?) and the closely related problem of "quintessence" (a substance of unknown nature that does not show gravitational clustering and has an equation of state $P = -\epsilon$), which currently promotes anti-gravity on large scales and makes the universe practically flat ($\Omega_{\Lambda} + \Omega_m = 1 \pm 0.1$).

3. The nature of the earliest universe (quantum birth, the arrow of time, cosmology on a 3-dimensional brane in a multidimensional space, etc.).

### 10.1.3 Hubble's Law

First, let's consider the simplest homogeneous and isotropic cosmological models without a cosmological constant. Due to homogeneity, we can take a limited spherical region in space and track its evolution. External regions are insignificant because the gravitational field created by matter outside the sphere (assuming strict spherical symmetry) is identically zero (Tolman 1934, proof within general relativity).

**Note**: In Newtonian gravity, the force is described by the equation $$F = -\frac{GMm}{r^2}$$, and within a hollow sphere, $F=0$. In the Newtonian theory, locally the theory is exact: for weak gravitational fields or in any sufficiently small neighborhood of an "arbitrarily strong" gravitational field, spacetime can be treated as flat, with a metric $g_{ik}=\eta_{ik} + h_{ik}$, where $\eta_{ik}$ is the Minkowski spacetime metric, $h_{ik}$ are small metric perturbations. 

From astronomical observations of galaxy spectra, the recession velocity of galaxies from the observer is directly proportional to the distance:

$$v = H r \tag{10.1}$$

Let's consider the mass contained within a designated sphere of radius $R$:

$$M = \frac{4}{3}\pi R^3 \rho$$. 

The change in density during expansion is given by

$$\frac{d\rho}{dt} = -\frac{3M}{4/3\pi R^{4}} \frac{dR}{dt} = -3H\rho \tag{10.2}$$

### 10.1.4 The Evolution Law. Critical Density

Let's consider a point on the boundary of a region expanding according to the law (10.1). The equation of motion is given by

$$\frac{d^2 R}{dt^2} = -\frac{GM}{R^2}. \tag{10.3}$$

Multiplying (10.3) by $R$, we get:

$$\frac{dH}{dt} + H^2 = -\frac{4\pi}{3} G \rho \\ \frac{d\rho}{dt} = -3H \rho$$

This leads us to the energy conservation law:

$$\frac{1}{2} \left( \frac{dR}{dt} \right)^{2} - \frac{GM}{R} = const$$

The critical density is defined by

$$\rho_{cr} = \frac{3H_{0}^{2}}{8\pi G} \approx 2 \times 10^{-29} \, \text{g/cm}^{3} h_{100}^{2}$$

### 10.1.5 Influence of Pressure

Until now, we have considered dust or low-density gas with pressure $P = 0$ (a good approximation for the current stage of expansion). For ordinary matter (where $\epsilon$ is the energy density), for relativistic particles (photons, neutrinos), whose energy is proportional to momentum, we see that energy decreases during expansion:

$$P = -w \epsilon \; w < 1$$

These simple reasoning illustrate that as we move into the past, we must eventually start taking the influence of pressure into account. As shown by Tolman, considering pressure is equivalent to replacing the density with the sum of energy density and three times the pressure:

$$\rho' = \rho + 3P$$

Then the equation of motion is modified to account for this additional pressure influence, affecting the dynamics and evolution of the universe's structure. 

This concludes our examination of these crucial concepts in Friedmann cosmology, establishing the foundation for understanding the grand scale dynamics of our universe.## 10.2 Models of Friedmann with Cosmological Constant

As previously noted, current data convincingly suggest that a significant portion of the total energy in the Universe exists in the form of a cosmological constant (with an effective equation of state $P = -\epsilon$) or hypothetical quintessence, represented by $$- \frac{1}{3} \epsilon > P > - \epsilon$$. Therefore, below we present the main formulas of the homogeneous and isotropic Universe model (the Friedmann-Robertson-Walker model) with a cosmological constant for reference.

The homogeneous and isotropic Universe can be described by a non-stationary (i.e., time-dependent) metric of a special form (the so-called Friedmann-Robertson-Walker metric):

$$ds^{2} = c^{2}dt^{2} - a^{2}(t)\left(\frac{dr^{2}}{1 - \kappa r^{2}} + r^{2}d\theta^{2} + r^{2}\sin^{2}\theta d\phi^{2}\right) \quad \kappa = 0, \pm 1$$

From the form of the interval $$ds^{2} = c^{2} dt^{2} - a(t)^{2} dx^{2}$$, where $dl^2 = a(t)^2 \, dx^2$, we automatically derive the Hubble law. Indeed, as follows from the expression for the interval, the physical distance is given by $dl = a(t)dx$. The rate of change of the physical distance, however, is not zero:

$$dv = \frac{dl}{dt} = \frac{da}{dt}dx = \frac{(da/dt)}{a(t)}(a(t)dx) = \dot{a}/a \, dl$$

Integrating along the geodesic (i.e., along the light beam), we obtain the Hubble law: 

$$\left(\frac{\dot{a}}{a}\right)^{2} = \frac{8\pi G\rho}{3} - \left(\frac{\kappa c^{2}}{a^{2}}\right) + \frac{\Lambda c^{2}}{3},$$ 

where $\dot{a}$ denotes the derivative of the scale factor with respect to time, and $\Lambda$ is the cosmological constant.

Substituting this interval into Einstein's General Relativity equations yields the Friedmann equations for the evolution of the scale factor. Here we provide them without derivation, immediately for non-zero cosmological constant $\Lambda$ (which, generally speaking, can be a function of time).

Energy Equation:

$$\left(\frac{\dot{a}}{a}\right)^{2} = \frac{8\pi G\rho}{3} - \left(\frac{\kappa c^{2}}{a^{2}}\right) + \frac{\Lambda c^{2}}{3}.$$ 

Equation of Motion:

$$\ddot{a} = -\frac{4\pi G}{3} \left( \rho + \frac{3P}{c^2} \right) + \frac{\Lambda c^2}{3}.$$

Continuity Equation:

$$\frac{d\rho}{dt} = -3H\left(\rho + \frac{3P}{c^2}\right).$$

**Remarks:**

1. In these equations, there are no arbitrary constants, i.e., given the topology ($\kappa$) and $\Lambda$, the evolution proceeds according to a specific law depending on the relationship between pressure and density ($P = w \rho$) (equation of state). 

2. Let us denote $H = \frac{\dot{a}}{a}$ as the Hubble parameter, and divide both sides of the energy equation by $\Lambda$:

$$1 = \Omega_m + \Omega_c + \Omega_\Lambda$$ 

with $\Omega_{\Lambda} \approx 0.7$.

3. The cosmological constant $\Lambda$ has units of $[\text{L}^{-2}]$ cm$^{-1}$. In dimensionless form, current observations suggest a value of $\Omega_{\Lambda} \approx 0.7$, from which it follows that in the current epoch, the "vacuum energy density" can indeed play the role of a positive cosmological constant with $\Lambda$.

![Difference in Distance Moduli of known Type Ia Supernovae in various cosmological models relative to a linearly expanding Universe model ("empty Universe" with $\kappa=0$) (horizontal line). For redshifts $z < 1$, individual supernovae are averaged. Each model is marked at the point (black square) where acceleration changes to deceleration. Light from the farthest SN1997ff was emitted at a moment when the Universe was expanding with deceleration. [From A. Riess et al. 2001, astro-ph/0104455].](https://images.astronet.ru/pubd/2002/05/14/0001176797/10lec/sn97ff.gif)

4. The equation can be rewritten in the form of the motion of a point on the surface of a sphere of radius $R(t)$ with mass $M$: 

$$\ddot{a} = -\frac{4\pi G}{3} \left( \rho + \frac{3P}{c^2} \right) + \frac{\Lambda c^2}{3} .$$ 

5. The sign of the spatial curvature (i.e., the Gaussian curvature of the 3-dimensional hypersurface of constant time) remains unchanged during the evolution of the Universe, although its magnitude, of course, depends on time. It is important to emphasize that the topology is determined by the total energy density, which includes the density of all types of matter (visible (baryonic) and invisible (non-baryonic)), which have positive pressure and act as sources of gravity, and the density of "invisible energy" (known as "dark energy" - cosmological constant or quintessence) that creates anti-gravity on large scales.

6. In our case for dust-like matter (with zero pressure, $P=0$), there is an analytical solution for the growth of the scale factor:

$$a(t) = a_0 t^{\frac{2}{3}}$$

as can be derived under considerations of our cosmological model. 

This lecture lays the groundwork for understanding the dynamics of cosmic expansion under the influence of a cosmological constant or other forms of energy density, which is crucial in our exploration of the Universe's past and future trajectories.### Literature

1. Ya.B. Zel'dovich, I.D. Novikov, *Structure and Evolution of the Universe*. Moscow: Nauka, 1975.

2. S. Weinberg. *Gravitation and Cosmology*. Moscow: Mir, 1975.

3. A.D. Chernin. *Cosmic Vacuum*. 2001, Uspekhi Fizicheskikh Nauk, Vol. 171, p. 1153.

---

### Figure Captions

<div align="center">
![Black hole destroys star: animation](http://images.astronet.ru/si/apod.gif)  
[Black hole destroys star: animation](http://images.astronet.ru/msg/1931410)  
</div>

<div align="center">
![Stars, dust, and nebula in NGC 6559](http://images.astronet.ru/si/apod.gif)  
[Stars, dust, and nebula in NGC 6559](http://images.astronet.ru/msg/1904844)  
</div>

<div align="center">
![25 brightest stars in the night sky](http://images.astronet.ru/si/apod.gif)  
[25 brightest stars in the night sky](http://images.astronet.ru/msg/1863796)  
</div>

<div align="center">
![Animation: Black hole destroys star](http://images.astronet.ru/si/apod.gif)  
[Animation: Black hole destroys star](http://images.astronet.ru/msg/1736616)  
</div>

<div align="center">
![Decomposition of distant light](http://images.astronet.ru/si/apod.gif)  
[Decomposition of distant light](http://images.astronet.ru/msg/1696356)  
</div>

<div align="center">
![Comparison of star sizes](http://images.astronet.ru/si/apod.gif)  
[Comparison of star sizes](http://images.astronet.ru/msg/1415428)  
</div>

<div align="center">
![The farthest known star?](http://images.astronet.ru/si/apod.gif)  
[The farthest known star?](http://images.astronet.ru/msg/1406555)  
</div>## 11. Cosmology (continued)

---

### Sections

- 11.1 Light Propagation. Redshift
- 11.2 The Hot Universe
- 11.3 Primordial Nucleosynthesis ("the first three minutes")
- 11.4 Cosmic Microwave Background Radiation and the Era of Recombination
- 11.5 Fluctuations in the Cosmic Microwave Background Radiation

---

**Publications with keywords:**  
- [Stars](https://example.com/db/search.html?kw=13809)  
- [Interstellar Medium](https://example.com/db/search.html?kw=14142)  
- [Cosmology](https://example.com/db/search.html?kw=15891)  
- [Theoretical Astrophysics](https://example.com/db/search.html?kw=10526)  
- [Astrophysics](https://example.com/db/search.html?kw=16508)  

**Publications with phrases:**  
- [Stars](https://example.com/db/search.html?words=%E7%E2%E5%E7%D4%FB)  
- [Interstellar Medium](https://example.com/db/search.html?words=%CC%E5%E6%E7%E2%E5%E7%D0%ED%D0%D0%D0%20%F1%F0%E5%E4%D0)  
- [Cosmology](https://example.com/db/search.html?words=%CA%EE%F1%EC%EE%EB%EE%E3%E8%FF)  
- [Theoretical Astrophysics](https://example.com/db/search.html?words=%F2%E5%EE%F0%E5%F2%E8%F7%E5%F1%EA%D0%20%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%D0)  
- [Astrophysics](https://example.com/db/search.html?words=%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%D0)  

### See also:
- ![APOD](http://images.astronet.ru/si/apod.gif) [Black Hole Destroys Star: Animation](https://example.com/db/msg/1931410)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Stars, Dust, and Nebula in NGC 6559](https://example.com/db/msg/1904844)
- ![APOD](http://images.astronet.ru/si/apod.gif) [25 Brightest Stars in the Night Sky](https://example.com/db/msg/1863796)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Animation: Black Hole Destroys Star](https://example.com/db/msg/1736616)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Decomposition of Distant Light](https://example.com/db/msg/1696356)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Comparison of Star Sizes](https://example.com/db/msg/1415428)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Farthest Known Star?](https://example.com/db/msg/1406555)

[All publications on this topic >>](https://example.com/db/search.html?kw=13809&kw=14142&kw=15891&kw=10526&kw=16508)

---## 11.1 Light Propagation. Redshift

Let's move from discussing mathematical models to actual observed quantities. The primary information from cosmic objects is obtained from the observation of electromagnetic waves (light). 

Consider a photon with frequency $\nu$, emitted from a point with coordinate $r_1$ against the backdrop of an expanding Universe. Let the receiver be located at a point with coordinate $r_2$. The velocity of point 2 relative to point 1 is evidently given by:

$$u_{21} = \frac{dl_{21}}{dt} = r_{21} \dot{a}(t) = dt = \frac{l_{21} \dot{a}}{a} = H l_{21}$$

Using the non-relativistic Doppler effect (i.e., considering points that are not too far apart), we find the difference between the received and emitted frequencies of the photon:

$$\omega_{2} - \omega_{1} = \omega_{1}\left(\frac{u_{21}}{c}\right) = \omega_{1}H\left(\frac{l_{21}}{c}\right).$$

As $l_{21} \rightarrow 0$, we can express the relationship as:

$$dw = -\frac{1}{c} H \omega dr$$

where $H = \frac{d \ln a}{dt}$. 

The observed quantity is the redshift $z$, which relates the wavelengths of the received $\lambda_{\text{obs}}$ and emitted $\lambda_{\text{em}}$ photons:

$$z \equiv \frac{\lambda_{\text{obs}} - \lambda_{\text{em}}}{\lambda_{\text{em}}}.$$

For non-relativistic cases and when the velocity $v \ll c$, we have:

$$z \simeq H_0 d/c,$$

where $d$ is the proper distance. 

From this, we can establish that:

$$\frac{a(z=0)}{a(z)} = (1 + z).$$

It is important to note that the scale factor is related to the redshift according to:

$$\frac{dt(z)}{dt_{0}} = \frac{a(z)}{a_{0}} = \frac{1}{1+z}.$$

### 11.1.1 Horizon

Now, let's address the question of how far we can receive information in the expanding Universe – in other words, what is the size of the causally connected region in the Universe? The event horizon is defined as the surface of the sphere formed by the collection of particles that emitted light at the moment $t = 0$, which is received by an observer at time $t$. The equation for the propagation of light in the Friedmann-Robertson-Walker metric takes the form:

$$ds^{2} = c^{2} dt^{2} - a(t)^{2} dr^{2} = 0,$$

which leads us to:

$$a(t)dr = -cdt,$$

yielding the comoving distance.

### 11.1.2 Angular and Photometric Distances

In an expanding Universe described by the Friedmann-Robertson-Walker metric, the concept of distance requires clarification. It can be defined by the angular size of a source with standard sizes (angular distance), by the flux received from a standard luminous source (photometric distance), or by the proper motion of a source with a standard speed (metric distance). In flat spacetime, all three methods yield the same result. However, since the Universe is described by a curved spacetime with a changing scale factor, these methods produce significantly different values once the distance becomes high.

#### 11.1.2.1 Angular Distance

In Euclidean geometry, we define angular distance as the distance calculated from the apparent angular size of an object $\theta$: 

$$D = \frac{D}{\theta},$$ 

where $D$ is the physical size at the source.

#### 11.1.2.2 Photometric Distance

We can also define the distance to an object differently: let the object have a constant intrinsic luminosity $L$, and the received flux from it be $F$. By definition, the photometric distance to an object is given by:

$$d_l = \left( \frac{L}{4 \pi F} \right)^{1/2}.$$

The significance of this relationship lies in its practical application in addressing the famous Olbers' paradox, which posits that in an infinite Universe filled with stars, at some point, the whole sky should be obscured by the disks of stars, contradicting the fact that the night sky is dark. The resolution to this paradox within the expanding Universe model is straightforward: the brightness of the sky does not occur due to the significant attenuation of intensity with redshift, and also because stars and galaxies did not exist at high redshifts (the first stars formed due to gravitational instability at $z \sim 10$). 

Through these discussions, we can robustly understand key astronomical distances and their implications on our view of the Universe. 

---

This concludes our discussion on light propagation, redshift, and the associated principles in cosmology. Further exploration into the expanding Universe will help us uncover the underlying structures and behaviors in our cosmic landscape.## 11.2 Hot Universe

The solution of Friedman yields 
$$\rho \rightarrow \infty$$ 
as 
$$z \to +\infty$$ 
(we recall that in the early stages 
$$\rho \sim \frac{1}{(t_{\infty} - t)^{2}}$$ 
regardless of the presence of pressure, cosmological constant, and the value of total density $\rho$!). From a physical standpoint, a density approaching infinity is unacceptable, and an adequate description of matter at very high densities is necessary.

The consideration of the state of matter at high densities must meet the following requirements:

1. The fundamental physical principles remain valid: conservation of baryon and lepton number, electric charge, and the first and second laws of thermodynamics.

2. The rate of establishment of equilibrium between particles must be much greater than the rate of expansion, ensuring that the expansion occurs adiabatically, 
$$TdS = 0,$$ 
with entropy remaining unchanged.

3. The state of equilibrium is determined by entropy and other conserved quantities and does *not depend* on the paths taken to equilibrium.

The theory of the hot universe (English: *Big Bang*) was developed in the works of Alpher, Bethe, and Gamow (1948), who examined a state of matter in which the radiation density vastly exceeds the matter density. Their idea was to derive the observed chemical composition of matter through nuclear reactions. 
In fact, they predicted the existence of relic microwave radiation with a temperature of 
$$T \sim 5$$ K, 
left over from the era when hot matter (plasma) was opaque to radiation, and matter was in a state of thermodynamic equilibrium with the radiation. The discovery of microwave background (relic) radiation in 1967 left no doubt about the validity of the hot universe concept.

As derived earlier, in an expanding universe the temperature of radiation changes as 
$$T \sim \frac{1}{a} \sim (1 + z),$$ 
and the matter density evolves as 
$$\rho_b \sim \frac{1}{a^3} \sim (1 + z)^3$$ 
so that the ratio 
$$\frac{T^3}{\rho_b} = \text{const}$$ 
during expansion. This is a fundamental conserved quantity in an expanding universe as, up to a numerical coefficient, this ratio corresponds to the entropy of radiation per baryon: 
$$\frac{S_{\gamma}}{n_{b}} = \left(\frac{4}{3}\right)a_{r}T^{3}/n_{b}$$
where 
$$a_r = \frac{\pi^2 k^4}{15(hc)^3} \approx 7.56 \times 10^{-15}$$
is the radiation constant. The total entropy of radiation can be expressed as 
$$S_{\gamma} = \frac{2\pi^{4}}{45}\zeta(3) k_{\gamma} \approx 3.6 k_{\gamma}$$ 
and the number density of photons as 
$$n_{\gamma} = \frac{2\zeta(3)}{\pi^{2}}\left(\frac{kT}{\hbar c}\right)^{3}.$$ 

Thus, the dimensionless entropy (in units of the Boltzmann constant $k$) can be written as 
$$\eta_b = \frac{\rho_{cr}}{m_p} = 1.124 \times 10^{-5} \Omega_b h^2 \text{ cm}^{-3},$$ 

where 
$$h \equiv H_0/(100 \, \text{km}/s/\text{Mpc}).$$ 

For the current temperature of the universe, we have $T = 2.726$ K. The number density of photons can be approximated as 
$$n_{\gamma} \approx 420(1 + z)^{3} \text{ cm}^{-3},$$ 
indicating that 
$$\frac{1}{\eta} \sim 10^{9}$$ 
and that the density of baryons is significantly lower than the density of radiation, as expressed by 
$$\rho_b \ll \rho_{\gamma,\nu,\mu,\ldots}.$$

The energy density evolves as 
$$\epsilon(t) \sim \frac{1}{t^2}$$ with the definition of total energy density given by 
$$\epsilon_{r} = a_{r} T^{4}$$ 
and 
$$\epsilon = \xi a_r T^4$$ 
where $\xi > 1$. The approximate relationship between temperature and time since the onset of expansion can be expressed as 
$$T \sim \frac{1}{\sqrt{t}}.$$ 

In numerical terms, we can say that 
$$T \approx \frac{1.3 \, \text{MeV}}{\sqrt{t \xi^{1/4}}}$$ 
and approximately 
$$t \approx \frac{1.7 c}{\left( \frac{T}{1 \, \text{MeV}} \right)^{2} \xi^{1/2}}.$$ 

In terms of the later universe, we have $T \sim 10^{12}$, with time being 
$$t = 1$$ 
which states that $T \sim 1$ when 
$$n = \frac{\epsilon}{4kT} \sim 10^{31}(T/1 \text{MeV})^{3},$$ 
which gives rise to the electron and positron number densities approximately as 
$$n_e^+ \sim n_e^- \sim 10^{31}$$ under the assumption that the interaction cross-section $\sigma \sim \lambda_c^2$, with 
$$\lambda_c = \frac{\hbar}{m_e c} \sim 10^{-12}$$ cm 

yielding a rough estimate of the interaction cross-section 
$$\sigma \sim 10^{-24}$$ cm$^2$. The speed of relativistic particles approaches the speed of light, $v \sim c$, while the characteristic interaction time can be estimated by 
$$\tau \sim \frac{1}{n \sigma v} \sim 10^{-17} c \ll t = 1 c.$$ 

Annihilation reactions like 
$$e^+ + e^- \leftrightarrow 2 \gamma$$ 
are quite frequent during such high-energy environments. 

In summary, the evolution of the universe from a hot, dense state involves complicated interactions and changes in density and temperature, governed by both particle physics and cosmological principles.## 11.3 Primordial Nucleosynthesis ("The First Three Minutes")

At temperatures greater than $1 \text{ MeV}$, atomic nuclei could not exist, as they were effectively destroyed in collisions with photons, electrons, and positrons. Only protons and neutrons were present. As the Universe expanded and cooled ($T \sim t^{-1/2}$), the concentration of neutrons decreased according to the Boltzmann distribution in an equilibrium gas:

$$\frac{N_n}{N_p} \sim \exp\left(-\frac{\Delta mc^2}{kT}\right)$$

where $\Delta mc^{2} = (m_{n} - m_{p})c^{2} = 1.38 \text{ MeV}$.

The reactions proceeded as follows:

1. $n + p \rightarrow D + \gamma$
2. $D + D \to T + p$; $D + D \to ^3He + n$
3. $3He + n \leftrightarrow T + p$; $T + D \rightarrow 4He + n$
4. $3He + 4He \rightarrow 7Be$

This leads to the creation of helium and other light elements. 

Interestingly, observational data related to the primordial chemical composition (especially primordial deuterium through the UV line at $\lambda = 972.272 \text{ nm}$, as it is most sensitive to the density: the higher the density, the faster deuterium participates in subsequent reactions, thus reducing its relative abundance) impose independent constraints on the baryonic matter density in the Universe:

$$\rho_b = \Omega_b \rho_{cr} \propto \Omega_b h^2$$

The abundances of primordial light elements are estimated as follows:
- $Y = ^4He \sim 0.244 \pm 0.002$
- $D\left(3 \times 10^{-5}\right)$
- $3He\left(2 \times 10^{-5}\right)$
- $^{7}Li\left(10^{-9}\right)$

![](https://images.astronet.ru/pubd/2002/05/14/0001176797/img1620.gif)

**Figure 11.1:** Calculation of the chemical content of light elements during the epoch of primordial nucleosynthesis (number of atoms relative to hydrogen) as a function of specific entropy per baryon or baryon density (upper scale). The vertical strip corresponds to observations of the contents of light elements from distant quasar spectra.

### 11.3.1 Constraints on the Number of Neutrino Types from Primordial Nucleosynthesis

During the radiation-dominated phase, the relationship between the temperature of the primordial matter and time $t$ from the beginning of expansion is derived from the formula for the density of all matter:

$$\rho_{\Sigma} = \xi \frac{a_r T^4}{c^2} = \frac{3}{32 \pi G t^2}$$

According to modern particle physics theories, neutrinos can have a rest mass. Recent data (from 1998) from the Super-Kamiokande neutrino detector in Japan suggests atmospheric oscillations of different neutrino types, which can only occur with non-zero rest mass. The measured value of the squared mass difference is:

$$\Delta m^{2} \sim 2.2 \times 10^{-3} \text{ eV}^2$$

Interestingly, with a rest mass of around $m_{\nu} \sim 0.1 \text{ eV}$, the contribution of neutrinos to the total density in the Universe becomes comparable to the contribution of baryons in luminous matter in stars!## 11.4 Cosmic Microwave Background and the Era of Recombination

A significant triumph of Gamow's hot universe theory came with the discovery in 1967 of an isotropic background of microwave cosmic (relic) radiation, characterized by a Planck spectrum with a temperature of approximately $T_0 \approx 2.73$ K. As the universe expands, the density of non-relativistic particles changes as 

$$\rho_m \sim a(t)^{-3} \sim (1+z)^{3},$$ 

while the density of radiation evolves as 

$$\rho_r \sim a(t)^{-4} \sim (1 + z)^{4}.$$ 

Thus, after a certain period, denoted by 

$$t_{eq}$$ 

(or equivalently, at some redshift 

$$z_{eq}$$), the radiation-dominated phase (with an equation of state given by $P = \epsilon/3$ and a scale factor dependency $a(t) \sim t^{1/2}$) transitions to a phase dominated by ordinary matter (with an equation of state $\rho_m = \rho_r$ and a scale factor 

$$a(t)$$). This epoch is clearly defined by the relationship 

$$1 + z_{eq} = \frac{a(0)}{a(t_{eq})} = \frac{\rho_{m}(0)}{\rho_{r}(0)} \simeq 2.3 \times 10^{4} \Omega_{0} h_{100}^{2},$$ 

indicating a phase when radiation's influence on expansion dynamics becomes negligible.

The expansion time to the recombination epoch is given by 

$$t_{r} \simeq 3 \times 10^{5}$$ years.

During the radiation-dominated era under conditions of complete thermodynamic equilibrium, the spectrum of the radiation corresponds to that of a black body, with a temperature decreasing inversely with the scale factor: 

$$T(z) \sim T_0(1 + z).$$ 

As the universe cools and the temperature of the plasma decreases to about $T_r \approx 3000$ K, recombination occurs as electrons combine with protons to form neutral hydrogen atoms (helium recombines slightly earlier). Ultimately, free electrons disappear, allowing the universe to become transparent to radiation.

Thus, the recombination epoch occurs at 

$$z \approx 1.8,$$ 

formally established during the matter-dominated stage, where radiation plays an insignificant role in the dynamics of expansion. Observational evidence supporting the relationship between the growth of the temperature of the relic radiation and redshift has been confirmed through the observation of the fine-structure lines of neutral carbon in the spectra of distant quasars, with 

$$z \sim 1.8,$$ 

validating that relic background photons with a temperature 

$$T_r \approx 3000 \text{ K}$$ 

act as a pump for the corresponding energy levels.## 11.5 Fluctuations of the Cosmic Microwave Background Radiation

An important result obtained in recent years pertains to the measurements of temperature fluctuations in the cosmic microwave background (CMB) radiation at various angular scales. The existence of fluctuations in temperature (and thus intensity) of the CMB is inevitable in the hot Big Bang model, as density fluctuations were also inevitable, which subsequently formed all the observed large-scale structure due to gravitational instability. Due to the conservation of specific entropy, we have:

$$3\delta T/T = \delta \rho_b/\rho_b$$

In 1969, the dipole anisotropy of the cosmic background radiation was measured, which is related to the motion of the Earth relative to the isotropic CMB. The measured value of the dipole anisotropy is 

$$\delta T_d \approx 3 \, \text{mK}$$ 

corresponding to the speed of motion of the barycenter of the Solar System at 

$$v \approx 370 \pm 0.5 \, \text{km/s}$$. 

Taking into account the movement of the Solar System relative to the center of the Galaxy, the speed of the Local Group of galaxies with respect to the CMB background is determined to be 

$$v \approx 620 \pm 20 \, \text{km/s}.$$ 

After 30 years of studying the anisotropy of the CMB in experiments "Relikt" (Russia) and COBE (USA), the amplitudes of temperature fluctuations in the CMB have been measured in angular scales of several degrees at a level of 

$$\frac{\delta T}{T} \sim 5 \times 10^{-6}.$$

In 2000-2001, fluctuations of the microwave background on small angular scales were measured and the results confirmed the theoretically expected behavior predicted by A.D. Sakharov, particularly the presence of so-called "Sakharov oscillations." Physically, these phenomena are caused by the Doppler effect due to the motion of plasma at the time of recombination:

$$\theta_r \approx \frac{ct_{r}}{(\sqrt{3}ct_{0})(1 + z_{r})} \approx 1^{\circ}.$$

The maximum amplitude of oscillations corresponds to the size of the entire causally connected region, specifically the acoustic horizon. In smaller scales, oscillations are significantly weaker due to photon viscosity (J. Silk). Therefore, the expected maximum of fluctuations observed in the present era should occur at the angular scale under which the sound horizon was observed at the time of recombination:

$$\sim \frac{c}{\sqrt{3 t_r}} \text{, where } t_r \text{ is the time of recombination.}$$

The exact value depends on the geometry of the universe (i.e., the total density relative to the critical density). The magnitude of the first peak in fluctuations occurs at an angular scale with a harmonic 

$$l = 200$$ 

which corresponds with high accuracy to 

$$\Omega_{0} = 1 \text{ and } \Omega = 1 \pm 0.1.$$ 

This indicates that the spatial curvature of the universe is equal to zero, implying that the geometry of the spatial sections of the universe is Euclidean.

### Figure Captions
![](https://images.astronet.ru/pubd/2002/05/14/0001176797/img1357.gif)

**Figure 11.2**: The angular spectrum of fluctuations in the cosmic microwave background radiation based on the data from the BOOMERanG, MAXIMA, and QMASK experiments. The position of the first peak at 

$$l$$ 

corresponds to a flat geometry of the universe (parameter 

$$\Omega_{0}$$).

Lastly, we note the significance of the second and subsequent peaks in the angular spectrum of fluctuations. The very existence of these peaks reflects the correlation of acoustic oscillations in the plasma during the era of recombination, caused by "phased" primary fluctuations. If there were no such connections, enhanced oscillations at specific harmonics would not be observed, the fluctuations would be equal in probability across all scales. However, causal connections between fluctuations at different scales could only exist if those fluctuations were once inside the causal horizon. This situation arises within the inflationary model of the universe. Thus, confident detection of the second and subsequent peaks in the angular spectrum of fluctuations of the cosmic microwave background will provide unambiguous confirmation of the existence of an inflationary period in the early universe.

### References
1. Ya.B. Zel'dovich, I.D. Novikov. **Structure and Evolution of the Universe.** Moscow, Nauka, 1975.
2. S. Weinberg. **Gravitation and Cosmology.** Moscow, Mir, 1973.
3. S. Weinberg. **The First Three Minutes.** Moscow, Atomizdat, 1983.
4. Peebles, P. J. E. **Principles of Physical Cosmology.** Princeton Series in Physics, Princeton, NJ: Princeton University Press.## 12. Cosmology (Continuation II)

### 12.1 Difficulties of Classical Cosmology
### 12.2 Model of the Inflationary Universe
### 12.3 Growth of Small Perturbations
### 12.4 Formation of Large-Scale Structure in the Universe

---

### 11.5 Fluctuations of the Cosmic Microwave Background Radiation

---

#### Publications with Keywords:
- [Stars](https://example.com) - [Interstellar Medium](https://example.com) - [Cosmology](https://example.com) - [Theoretical Astrophysics](https://example.com) - [Astrophysics](https://example.com)

#### Publications with Terms:
- [Stars](https://example.com) - [Interstellar Medium](https://example.com) - [Cosmology](https://example.com) - [Theoretical Astrophysics](https://example.com) - [Astrophysics](https://example.com)

#### Also See:
- ![APOD](http://images.astronet.ru/si/apod.gif) [Black Hole Destroys Star: Animation](https://example.com)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Stars, Dust, and Nebula in NGC 6559](https://example.com)
- ![APOD](http://images.astronet.ru/si/apod.gif) [25 Brightest Stars in the Night Sky](https://example.com)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Animation: Black Hole Destroys Star](https://example.com)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Decomposition of Distant Light](https://example.com)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Comparison of Stellar Sizes](https://example.com)
- ![APOD](http://images.astronet.ru/si/apod.gif) [The Most Distant Star Known?](https://example.com)

### All publications on this topic >> 

---

**Reader Opinions** [70]

### Rating: 3.1 [votes: 182]
- Rate: 
  - [Excellent](https://example.com)
  - [Good](https://example.com)
  - [Average](https://example.com)
  - [Poor](https://example.com)
  - [Unsuitable](https://example.com)

---

[Print Version](http://images.astronet.ru/img/print.gif)

---

**Astrometry** - **Astronomical Tools** - **Astronomical Education** - **Astrophysics** - **History of Astronomy** - **Space Exploration** - **Amateur Astronomy** - **Planets and the Solar System** - **The Sun**## 12.1 Difficulties of Classical Cosmology

The coherent theory of Friedmann cosmology, which includes the Robertson-Walker metric and non-stationary solutions to Einstein's equations, models a hot Universe characterized by primordial nucleosynthesis and explanations for the cosmic microwave background radiation, has been substantiated by extensive astronomical observations. However, it quickly encountered several difficulties. In brief, these issues arise from the fact that the scale factor of the Universe $a(t)$ increases too slowly over time (as $\sqrt{t}$ or $t^{\frac{2}{3}}$ in a flat model), which leads to significantly large scale factors $a(t)$ corresponding to small times in the past. The paradoxes of classical cosmology are resolved in the inflationary Universe model, which posits that during the earliest stages of evolution, the scale factor increased exponentially:

$$
a(t) = a_0 e^{Ht}
$$

## 12.1.1 Horizon Problem (Causality Issue)

The cosmic microwave background radiation is observed isotropically from all directions in the sky. After the moment of recombination ($z_r \approx 1000$, $t_r \sim 10^{12} - 10^{13}$ s), it interacts minimally with matter in the expanding Universe. The physical size of the horizon at the time of recombination is approximately $l_h \approx c t_r$. Consequently, regions of the sky with angular sizes $\theta \sim (1 + z_r)\left(\frac{t_r}{t_0}\right) \approx 2^\circ$ turn out to be causally disconnected from each other. Then why do we observe such an isotropic distribution of matter and cosmic microwave background radiation? In Friedmann models, the horizon grows proportionally to the time elapsed since the beginning of the expansion, thus in the future, any regions will inevitably "come under the horizon."

Reformulating the horizon problem in terms of the Universe's entropy reveals that the contemporary entropy is concentrated in relativistic particles (photons, neutrinos). The dimensionless entropy (i.e., in units of Boltzmann's constant $k_B$) in one volume unit for relativistic particles (whether bosons or fermions) is given by

$$
s \approx 4(n_{\gamma} + n_{\nu} + n_{\bar{\nu}} + \ldots)
$$

For photons and neutrinos, we have $n_{\gamma} + \sum_{\nu} n_{\nu} \approx 500 + 400 = 900$. Hence, the entropy of the Universe within today's horizon is:

$$
S_U \sim \left( \frac{c}{H_0} \right)^{3}s \sim 10^{90}
$$

Furthermore, the number density of relativistic particles is given by $n \sim T^3$. This leads us to the estimate for the entropy within the horizon

$$
S_{HQR} \sim \left( \frac{c}{H} \right)^{3} T^3.
$$

Using the relation $\varepsilon = \alpha_{r} T^{4}$ and the assumptions about the expansion rate, it follows that 

$$
\frac{H^2}{G} \sim \frac{H^2 m_{Pl}^2}{T^4} \rightarrow H \sim \frac{T^2}{m_{Pl}}.
$$

This implies the Planck mass

$$
m_{pl} = \sqrt{\frac{hc}{G}} \approx 10^{-5}.
$$

If we consider the entropy in terms of the Planck length, we find 

$$
S_{HQR} \sim \left( \frac{m_{pl}}{T} \right)^{3} \sim 1.
$$

If there was an epoch of exponential growth of the scale factor, any initially causally connected regions would quickly "spread out" to distances greater than $ \frac{c}{H}$, leading to a situation where these areas appear causally disconnected during later stages of slower growth.

## 12.1.2 The Flatness Problem

This problem revolves around the extraordinary closeness of the density to the critical density ($\Omega_{0} = 1$) at the early stages of evolution. Consider this straightforward reasoning: if we assume that the quantum "birth" of the Universe occurred at 

$$
t \sim 10^{-43} \text{ s},
$$ 

then the natural curvature radius of the Universe at birth is 

$$
R \sim 10^{-33} \text{ cm}.
$$ 

If we estimate the Universe's expansion occurring according to a power law 

$$
a(t) \sim t^{\alpha}, \; \alpha < 1,
$$ 

then by the present moment ($t \sim 10^{10}$ years), the curvature radius would have grown to sizes significantly larger than expected.

Similar backward estimations reveal that currently, the curvature radius is $R \sim 10^{-2}$ cm, and earlier any evolutionary state leads to the curvature radius being on the order of the horizon size $l_H$, which implies that at that epoch, the Universe behaves flat with a precision of about $10^{-60}$.

Ultimately, applying more precise quantitative analysis leads to the Friedmann equation for the scale factor written in terms of the density parameter:

$$
\left| \Omega - 1 \right| \sim t^{2(1-\alpha)} \rightarrow +\infty \text{ as } t \to \infty.
$$

Consequently, the Universe's density appears to converge towards a critical density, implying 

$$ 
\Omega = \mathcal{O}(1).
$$## 12.2 The Inflating Universe Model

The main idea of the inflating universe model (A.D. Linde, A. Gus, A.A. Starobinsky) is that in the very early universe, there existed an unusual form of matter that created "antigravity," causing the universe to expand at an accelerated rate. Antigravity itself should not be perceived as something miraculous; we must recall that, within the framework of General Relativity (GR), the source of the gravitational field is not only matter but also pressure (momentum flux). There is no physical law that forbids having negative pressure. Moreover, modern elementary particle physics suggests the existence of scalar fields, one of the properties of which is the realization, under certain conditions, of an equation of state $p = -\epsilon$ (where pressure is negative!).

If such a field arises in an arbitrarily small region of the universe during its early stages, this results in an equation of state such that the scale factor of that region grows exponentially over time:

$$a(t) \sim e^{Ht},$$ 

where $H = \dot{a}/a$ is the Hubble constant. The solution of the type (12.1) with $\epsilon$ constant was obtained by the Dutch physicist Willem de Sitter in 1917 from Einstein's equations with a cosmological constant, and it bears his name. 

Negative pressure effectively acts as "antigravity," causing the universe to expand very rapidly. We will clarify this point in more detail. From the Friedmann equations (see Lecture 10), we have:

$$\frac{d^2 a}{dt^2} = -\frac{4 \pi G}{3} \left( \rho + \frac{3p}{c^2} \right) a,$$

and 

$$\frac{d\rho}{dt} = -3H\left(\rho + \frac{P}{c^2}\right).$$

The exponential growth of the size of a region with constant density means an increase in mass (energy) within that region "from nothing," which at first glance might seem strange. However, there is no violation of the law of conservation of energy here—the increase in positive energy is precisely compensated by the negative energy of the gravitational field created by the "emerging" positive energy within the expanding region. Thus, during inflationary expansion, total energy is conserved.

More formally, we can consider the thermodynamic relationship (the first law of thermodynamics, the law of conservation of energy). Since entropy must be conserved during expansion $dS = 0$, the change in energy in a volume element is compensated by the work of pressure forces:

$$d(\varepsilon V) + pdV = 0,$$

leading to

$$deV + \epsilon dV - \epsilon dV = 0.$$

The antigravitating state is fundamentally unstable; it "decays" exponentially, like the radioactive decay of nuclei, into ordinary gravitational matter. The characteristic decay time of this unstable state is defined as the Hubble time $\frac{1}{H}$. Upon decay, relativistic particles of ordinary matter (leptons, quarks, and their supersymmetric partners) are produced. Collisions and interactions among them quickly lead to the establishment of thermodynamic equilibrium with the equation of state for relativistic matter $p = +\frac{\epsilon}{3}$. 

To resolve the paradoxes of Friedman cosmology mentioned earlier, it is sufficient for inflation to continue for about 70 Hubble times. During this period, the scale factor increases by approximately $e^{70} \approx 10^{30}$, and by the beginning of the Friedmann stage, the scale factor is about $10^{-33} \times 10^{30} = 10^{-3}$ cm, which is necessary to solve the horizon problem. The initial density, with a required accuracy of $\Omega_{\text{tot}} \rightarrow 1$, naturally turns out to equal 1 (resolving the flatness problem). Due to the exponential growth of the scale factor, initial quantum fluctuations leave the horizon (which grows slower than the exponential) and later (when the scale factor grows as a power of $t$) re-enter beneath the horizon (which grows proportionally to time since the beginning of Friedmann expansion), now amplified by the expansion. This generates the initial spectrum of perturbations necessary for structure formation in the universe.

Thus, the inflation stage within the time $T \sim 10^{16}$ prepares the initially very hot matter in regions about 0.01 cm in size, which expands in an inertial manner with a scale factor growing like $a(t) = a_0 \exp\left( \sqrt{\frac{8\pi G \rho}{3}} t \right)$. This is nothing other than the hot universe model ("Big Bang"). Now it is clear that the role of the "explosion" was played by the inflation stage.

To summarize, here are the arguments supporting the reality of the inflationary expansion stage before the Friedmann stage in the early universe:

1. High entropy of the universe ($S \sim 10^{16}$). In the inflationary model, such a high number arises "at the cost" of the 70-fold exponential growth of the scale factor. A number on the order of 100 is easier to explain in the future based on a more fundamental theory.

2. The presence of homogeneous and isotropic Hubble expansion arises naturally as a consequence of the action of antigravity in the early universe.

3. The homogeneity and isotropy of the universe on large scales (the horizon problem) are explained by the causal connection of all fluctuations during the pre-inflationary period.

4. The closeness (exact equality?) of the total density to the critical density (the flatness problem). Regardless of the initial value $\rho$, during the inflation stage $\rho = \epsilon = \text{const}$ with the required accuracy.

5. The absence of magnetic monopoles (particles with masses on the order of $10^{16}$ GeV, predicted by Dirac). In the standard Big Bang model, such monopoles would have been produced at about $10^{16}$ GeV, and would currently dominate the universe with an absurd density excess of $10^{-34}$. In the inflationary model, monopoles formed during the pre-inflationary epoch are "spread out" during the exponential expansion over vast distances, making their number "safely small" within the modern horizon.

6. Phase oscillations of perturbations in the relic radiation at different angular scales (Sakharov oscillations). This is a direct indication of the origin of primary fluctuations within causally linked areas in the pre-inflationary period.

In conclusion, let us briefly touch on the widely discussed model of eternal inflation. Its essence lies in the fact that once initiated in some place in the universe, inflation cannot cease. Indeed, unlike radioactive decay, the decay of the antigravitating substance into ordinary matter during inflation leads to exponential growth of the region occupied by inflation, in which the area occupied by ordinary matter is exponentially small (since ordinary matter expands increasingly slowly or even enters a phase of dynamic dominance of the cosmological constant with acceleration, but lesser than the initial). Thus, it appears that the entire universe is filled with a decaying inflationary phase, within which there exists an infinite number of causally disconnected "islands" of ordinary matter ("our universe" is just one of these islands).## 12.3 Growth of Small Perturbations

The growth of small initial density perturbations and metric fluctuations (gravitational waves) in an expanding Universe is determined by the dynamic interaction of perturbations with the changing scale factor (parametric resonance). All wavelengths change proportionally to the scale factor $\lambda(t) = l_h(t)$. In the radiation-dominated phase of expansion (where the pressure $P = \frac{1}{3} \rho$), density perturbations with wavelengths shorter than the horizon do not grow—they manifest as acoustic oscillations whose amplitude does not increase due to dissipative processes. The amplitude of density fluctuations with wavelengths longer than the horizon $\lambda_h$ grows proportionally to the square of the scale factor,

$$\delta \rho \sim \rho_0\, a^2(t).$$ 

In the matter-dominated stage (non-interacting particles), the amplitude of perturbations increases like the scale factor:

$$\delta \rho \sim \rho_0\, a(t).$$ 

Metric fluctuations (gravitational waves) with scales larger than the horizon do not grow, maintaining a constant amplitude (E.M. Lifshitz, 1946).

**Figure 12.1**: The growth of the scale factor $a(t)$ and the Hubble length $l_H$ as a function of time during the de Sitter (inflation) and Friedman expansion phases. The upper graph is in terms of physical length, while the lower one is in comoving coordinates. The comoving Hubble coordinate corresponds to a particle whose recession speed equals the speed of light during expansion. During inflation, the comoving Hubble length exponentially decreases with time, while in the Friedman phase, it increases as a power of time. This indicates that arbitrary wavelengths during the inflation phase exponentially exceed the horizon before eventually "returning" beneath it in the Friedman phase.

The growth of perturbations presented a problem in classical Friedman cosmology. Indeed, due to the slow growth of the scale factor, perturbations with wavelength $\lambda_{cut}$ enter the horizon at any given moment. In the radiation phase, their growth ceases due to dissipative processes. At the moment of recombination, there should exist a spectrum of density fluctuations linked to the spectrum of temperature fluctuations of the cosmic background radiation (since specific entropy $s \sim \frac{T^3}{\rho} = \text{const}$). After recombination, density fluctuations grow as the scale factor while temperature fluctuations remain unchanged. Therefore, from today's measurements of $\frac{\delta T}{T}$, one can infer about the density fluctuations at the moment of recombination. The fact that fluctuations in the relic radiation are isotropic (even though the angular scale of the horizon at the moment of recombination was approximately 2 degrees) is naturally explained in the model of the inflationary Universe, since in the past (before the inflation period), these regions were causally connected. Exponentially small fluctuations grow and drift far beyond the horizon during inflation, thereby explaining Figure 12.1.

### 12.3.1 Gravitational (Jeans) Instability

The origin of structures in the Universe can be traced back to the development of gravitational instability from small perturbations. Gravitational instability was quantitatively analyzed by Jeans in 1902. The physical cause of this instability is gravitational attraction. If a small fluctuation $\delta \rho$ with characteristic size $R$ arises in the background of uniform density $\rho$, it will grow if the gravitational attraction $F_{gravity}$ exceeds the pressure gradient $F_{pressure}$. Roughly speaking, equilibrium is disrupted when the characteristic time $\tau_{instability}$ for the development of instability (the free-fall time) is less than the time taken for perturbations to propagate through the medium, $\tau_{sound}$, where $c_s$ is the sound speed. In simpler terms, if the scale of the perturbations (the characteristic length) is larger than the critical (Jeans) value,

$$\lambda_J \sim \frac{c_s}{\sqrt{G \rho}},$$

the growth of density begins. The precise value of the critical wavelength, derived by Jeans, is greater than this simple estimate by a factor of order $2\pi$.

For an ideal gas $\rho$, we have:

$$s \sim \frac{T^3}{\rho}.$$

There is often talk of the Jeans mass—the amount of matter contained in a volume with characteristic size $R$:

$$M_J = \rho V \sim \rho R^3.$$

Any arbitrary small density perturbation can always be expressed as a Fourier series, allowing us to track the behavior of individual harmonics. If at least one harmonic grows with time, it will indicate instability. The exact solution (Jeans) gives for the harmonics with wave vectors $k = \frac{2\pi}{\lambda}$ the relation:

$$\frac{\delta \rho_k}{\rho_0} = A_k e^{\gamma t + i k x}$$

where 

$$\gamma = \pm \sqrt{4\pi G \rho_0 - k^2 c_s^2}.$$

These solutions tell us that the perturbations' growth resembles the form 

$$\delta \rho \approx \rho_0 e^{\gamma t} \int d^3 k A_k e^{i k \cdot x} = \rho_0 e^{\gamma t} f(x),$$ 

indicating that 

$$\frac{\delta \rho}{\rho} \sim e^{\gamma t}.$$

In a radiation-dominated plasma, the situation is notably different. If we consider the usual density $\rho \sim \frac{1}{(1+z)^3}$ at the time of recombination, the corresponding sound speed $c_s$ and the perturbation's scale leads to the case where the perturbations with wavelengths $\lambda < \lambda_J \sim h$ become relevant.

At larger scales ($\lambda > h \sim ct$), we find that the density perturbations $\frac{\delta \rho}{\rho} \sim a^2(t)$, and when $\lambda \sim h$, they behave like $\delta \rho / \rho \sim a(t) \sim t^{2/3}$. 

With the understanding of sound speed and mass of hydrogen:

$$v \sim \sqrt{\frac{k_B T}{m_H}}$$,

and the determination of conditions during the era after recombination, we find that fluctuations above a critical scale must have been in a rapid growth phase. However, due to the dissipation of short-wavelength perturbations in the plasma at the moment of recombination, only those fluctuations larger than a characteristic mass scale survive, thus enabling the development of structures like galaxy clusters.## 12.4 Formation of Large-Scale Structure in the Universe

The large-scale structure of the Universe (including galaxies, galaxy clusters, and voids with sizes of approximately 100 Mpc) arises from small density perturbations. When the contrast in density approaches 

$$\frac{\delta \rho}{\rho} \sim 1$$ 

the perturbation ceases to participate in the cosmological expansion and can form a gravitationally bound system. It is crucial to note that the nonlinear stage of growth of these perturbations leads to preferential compression along one direction, resulting in the formation of flattened structures, known as the "Zel'dovich pancakes." When these pancakes cross each other, they create a cellular structure. In areas of highest density, galaxy clusters are formed. Evidently, the observed large-scale structure could not have developed without the involvement of dark matter — an invisible substance that manifests only through its gravitational interactions. Indeed, from the fluctuations in the temperature of the cosmic microwave background radiation, we know that the density fluctuations at the time of recombination were 

$$\left( \frac{\delta \rho}{\rho} \right)_{r} \sim 10^{-5}.$$ 

After recombination, these fluctuations grow proportional to the scale factor. Thus, by the time 

$$z \approx 1,$$ 

they can have increased by a factor of $\sim 1000$, reaching a level of 

$$10^{-2}.$$ 

This is entirely insufficient (by two orders of magnitude!) to initiate gravitational instability and the formation of structures! This fact strongly supports the existence of dark matter, which interacts with normal matter solely through gravity. It is the density fluctuations of dark matter (which were two orders of magnitude larger at the time of recombination) that created potential wells into which normal matter "flowed," leading to the formation of galaxies and galaxy clusters. The observed large-scale structure is presented in Figure 12.2. The results of numerical simulations of large-scale structure in the cold dark matter model are shown in Figure 12.3.

According to contemporary views, the preferred model for structure formation is that of so-called cold dark matter (CDM) (including axions and neutralinos). It is also possible that a non-zero cosmological constant plays a significant role. For more details, see A. Dolgov, Ya.B. Zel'dovich, M.V. Sazhin, "Cosmology of the Early Universe," Moscow State University Press, 1988.

<div align="CENTER"><a name="lss_obs"></a><a name="9297"></a>
<table align="center" width="50%">
<tr><td>![](./imgs/404c8d05c2064a07acc9634894914b57_img1805.png)</td></tr>
<tr><td>Figure 12.2
The observed large-scale structure of the Universe in terms of a "slice" of the galaxy distribution by redshift (in units of speed of recession). The lower scale presents a one-dimensional "slice" of the structure by redshift (distance to galaxies). Distinct galaxy clusters, filamentary structures, and voids with sizes of $\sim 100$ Mpc are clearly visible.</td></tr>
</table>
</div>

<div align="CENTER"><a name="lss_calc"></a><a name="9291"></a>
<table align="center" width="50%">
<tr><td>![](./imgs/e79887aba5344a46a05a8f53f7231beb_img1806.png)</td></tr>
<tr><td>Figure 12.3
Result of three-dimensional modeling of the large-scale structure of the Universe in the cold dark matter model, projected onto a portion of the celestial sphere. The points represent individual galaxies.</td></tr>
</table>
</div>## 13. Dark Matter and Gravitational Lenses

This lecture is still under preparation. 

---

### Publications with Keywords:
- [Stars](http://db/search.html?kw=13809) - 
- [Interstellar Medium](http://db/search.html?kw=14142) - 
- [Cosmology](http://db/search.html?kw=15891) - 
- [Theoretical Astrophysics](http://db/search.html?kw=10526) - 
- [Astrophysics](http://db/search.html?kw=16508)

### Publications with Words:
- [Stars](http://db/search.html?words=%E7%E2%E5%E7%E4%FB) - 
- [Interstellar Medium](http://db/search.html?words=%CC%E5%E6%E7%E2%E5%E7%E4%ED%E0%FF%20%F1%F0%E5%E4%E0) - 
- [Cosmology](http://db/search.html?words=%CA%EE%F1%EC%EE%EB%EE%E3%E8%FF) - 
- [Theoretical Astrophysics](http://db/search.html?words=%F2%E5%EE%F0%E5%F2%E8%F7%E5%F1%EA%E0%FF%20%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0) - 
- [Astrophysics](http://db/search.html?words=%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0)

---

### See Also:
- ![APOD](http://images.astronet.ru/si/apod.gif) [Black Hole Destroys Star: Animation](http://db/msg/1931410)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Stars, Dust, and Nebula in NGC 6559](http://db/msg/1904844)
- ![APOD](http://images.astronet.ru/si/apod.gif) [25 Brightest Stars in the Night Sky](http://db/msg/1863796)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Animation: Black Hole Destroys Star](http://db/msg/1736616)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Decomposition of Distant Light](http://db/msg/1696356)
- ![APOD](http://images.astronet.ru/si/apod.gif) [Comparison of Star Sizes](http://db/msg/1415428)
- ![APOD](http://images.astronet.ru/si/apod.gif) [The Farthest Known Star?](http://db/msg/1406555)

[All publications on this topic >>](http://db/search.html?kw=13809&kw=14142&kw=15891&kw=10526&kw=16508)

---

### Reader Feedback
- Evaluation: 3.1 [Votes: 182]

[Rate this lecture](http://doc/publication_rating.html)

---

### Additional Links
- [Print Version](http://db/print/msg/1170612/node67.html)

---

**[Astrometry](http://db/sect/300000007)** - 
**[Astronomical Instruments](http://db/sect/300000010)** - 
**[Astronomical Education](http://db/sect/1168516)** - 
**[Astrophysics](http://db/sect/300000003)** - 
**[History of Astronomy](http://db/sect/300000016)** - 
**[Space Exploration and Astronomy](http://db/sect/300000012)** - 
**[Amateur Astronomy](http://db/sect/300000013)** - 
**[Planets and the Solar System](http://db/sect/300000005)** - 
**[The Sun](http://db/sect/300000004)**## 14. Gravitational Wave Astronomy

Up to now, we have primarily examined electromagnetic radiation from cosmic sources. This is the most well-studied form of radiation. As mentioned earlier, neutrino radiation only plays a significant role in the later stages of stellar evolution, right before and during the collapse of a star's core, and immediately after the formation of a neutron star.

In addition to electromagnetic and neutrino radiation associated with the electroweak interaction, there exists another form of energy radiation in nature—gravitational waves. Unlike electromagnetic (EM) radiation, which (except for the maser mechanism) is generated by a large number of incoherent emitters (atoms, electrons, etc.), gravitational radiation is significant during non-spherical, symmetric movements of large masses of matter (individual objects) overall. The weakness of gravitational radiation is linked to the weakness of gravitational interaction in nature. The electromagnetic coupling constant (the fine-structure constant) is given by 

$$\alpha = \frac{e^2}{\hbar c} \approx \frac{1}{137},$$ 

while the dimensionless coupling constant of gravitational interaction is 

$$\alpha_G = \frac{G m_p^2}{\hbar c} = \left( \frac{m_p}{m_{PL}} \right)^2 \sim 10^{-38}.$$

The enormous difference between gravitational wave radiation and electromagnetic radiation can be illustrated by the following distinctive features of gravitational waves:

1. EM radiation consists of oscillations of the electromagnetic field that propagate through spacetime at the speed of light. Gravitational waves are oscillations of physical parameters that describe the properties of spacetime itself, propagating at the speed of light.

2. EM radiation from astronomical sources is almost always a superposition of incoherent waves emitted by individual electrons, atoms, or molecules. Gravitational waves from astrophysical sources are generated by coherent movements in space of vast amounts of mass-energy—whether massive bodies (stars) or energy of oscillating spacetime curvature (in the early stages of the evolution of the Universe).

3. The wavelength of EM radiation is typically much smaller than the macroscopic sizes of the emitting objects (stars, interstellar gas clouds, accretion disks, etc.), which allows us to study the structure of the respective emitting body through EM radiation. In contrast, the wavelength of gravitational waves is comparable to or larger than the macroscopic sizes of their sources. In this sense, gravitational waves are similar to sound waves—by studying them, we obtain information about the global properties of their sources.

4. EM waves are easily absorbed, scattered, and refracted by matter (as covered in classical astrophysics). Gravitational waves, however, are virtually unaffected by absorption or scattering, even by massive bodies.

These properties of gravitational waves enable the observation of processes that cannot be studied using electromagnetic radiation—specifically, the state of matter in strong gravitational fields and the properties of the strongest gravitational fields, of which we currently have primarily theoretical understandings.

1. The information obtained from gravitational waves about the source will be fundamentally different from that carried by electromagnetic waves. Gravitational waves provide insights into the global movements of mass and energy in the source, while the properties of electromagnetic radiation reflect the thermodynamic state of the emitting optically thin layers of matter.

2. Most (though not all) gravitational wave sources detectable by modern detectors are not visible in electromagnetic waves, and vice versa, most light-emitting sources do not produce significant gravitational radiation. Typical light sources include stellar atmospheres, accretion disks, interstellar gas and dust, while typical sources of detectable gravitational waves are collapsing stellar cores surrounded by opaque shells and merging binary black holes, which do not emit electromagnetic waves at all.

3. Gravitational waves are sure to present unexpected surprises. As the history of science has shown, any new "window into nature" has a revolutionary impact on our understanding of the Universe. This was the case with radio astronomy, which led to the discovery of quasars, pulsars, and cosmic microwave background radiation. These discoveries provided the first observational evidence of neutron stars and black holes and confirmed the "hot Universe" hypothesis.

Thus, the newly emerging field of gravitational wave astronomy is poised to become one of the priority directions in astrophysics in the 21st century.## 14.1 Description

According to A. Einstein's theory of gravity (the general theory of relativity, GTR), any energy density can be described in terms of a gravitational field, and the gravitational field itself is intuitively represented as the curvature of the spacetime in which matter exists. This curvature means that the square of the interval between two events in the presence of matter differs from the square of the interval in special relativity. Specifically, coefficients that depend on coordinates and time appear before the square of the time and length elements.

In general, one can express this as 

$$ds^{2} = -g_{00}c^{2}dt^{2} + \sum_{\alpha,\beta=1}^{3}g_{\alpha\beta}dx^{\alpha}dx^{\beta} = g_{ik}dx^{i}dx^{k}, \, i, k = 0, 1, 2, 3$$ 

(where summation over repeated indices is implied, and time is treated as a coordinate with an index of zero). The square symmetric matrix $g_{ik}$ is called the *metric* of spacetime. Thus, in general, there are 10 independent quantities $g_{ik}$ that characterize the gravitational field. It is worth noting that in Newtonian gravity, a single scalar gravitational potential $\phi$ is sufficient, which is computed from the spatial distribution of density using Poisson's equation 

$$\Delta \phi = 4 \pi G \rho(\vec{r}).$$ 

The physical meaning of the metric coefficients is clear from their form in the weak field approximation: for a spherically symmetric non-rotating body, 

$$g_{00} = -\left(1 + \frac{2\varphi}{c^{2}}\right), \, g_{0i} \equiv 0.$$ 

The force acting on test bodies (the gravitational field strength) is defined as the gradient of potential in Newtonian theory and, in general, by the derivatives of the metric with respect to coordinates and time.

Under normal Earth conditions, the metric differs very little from that of empty space (the so-called Minkowski metric):

$$ds^{2} = -c^{2}dt^{2} + dl^{2}.$$ 

For a weak gravitational field, the metric can be linearized by writing 

$$g_{ik} = \eta_{ik} + h_{ik}$$ 

where $\eta_{ik} = \text{diag}(-1, 1, 1, 1)$ is the Minkowski metric, and $h_{ik}$ represents a small perturbation. Linearization of the GTR equations without a source term leads to the wave equation 

$$\Box h_{ik} = 0$$ 

(where $\Box$ is the D'Alembert operator), which describes the propagation of waves at the speed of light in a vacuum.

Up to the mid-1960s, theoretical debates ensued regarding whether gravitational waves represented a physical reality or were a mathematical fiction. However, it is now proven that gravitational waves carry energy and momentum that can be transmitted to macroscopic bodies. One can metaphorically visualize a gravitational wave as a rippling effect on the surface of an ocean, where the large radius of curvature of the ocean represents the background curvature of spacetime upon which waves propagate, and interaction with macroscopic bodies is akin to the "rocking of a boat" on this ripple.

Typically, flat waves are considered (which is quite justified for distant sources), and for describing their interaction with macroscopic bodies, a special coordinate system is chosen that simplifies this interaction's description (it is evident that the choice of coordinate system should not affect the physical effects). Fixing a coordinate system in the four-dimensional spacetime imposes 8 additional conditions, leaving only two of the 10 independent quantities $h_{ik}$ as actually independent, known as $h_{+}$ and $h_{\times}$ polarizations. This labeling corresponds to how these waves affect test bodies (see Figure 14.1). 

![Figure 14.1: Field of relative accelerations (force lines) generated by a flat gravitational wave with different polarizations $h_{+}, h_{\times}$. The force lines exhibit a quadrupole pattern. The distance between the lines decreases as one moves away from the coordinate origin.](./imgs/dc6d9f6ee739495b84341be6b6f27a43_img1825.png)

Similar to how a charged particle oscillates in the field of a flat electromagnetic wave, the interaction of a gravitational wave with macroscopic bodies leads to the emergence of relative accelerations and to changes in physical distance $l$ between them. For example, the relative change in distance between two test bodies in the field of a flat gravitational wave is described by 

$$\Delta l \propto h,$$ 

where $l$ is the length of interest, and $h$ is the amplitude of the gravitational wave perturbation.## 14.2 Detection of Gravitational Waves

As we will see below, the characteristic dimensionless amplitudes of gravitational waves (GWs) from astrophysical sources (such as asymmetric supernova explosions, mergers of binary neutron stars, etc.) are of the order of $h \sim 10^{-21}$. This means that as such a wave passes by, a meter stick changes its length by only $\Delta l \simeq 10^{-19}$ cm, which is many orders of magnitude smaller than the Compton wavelength of a proton!

In a few years, experimental technology will allow us to measure such subtle effects.

The principle of gravitational wave detection is based on the physical impact of GWs on test masses—transferring momentum and energy to them (in solid-state detectors) and changing the relative positions of free masses (in GW interferometers). Solid-state detectors have been developed since the mid-1960s (Weber, USA), and by the end of 1999, the best of them had sensitivities of $h \sim 10^{-19}$ in a narrow frequency band around 1 kHz. These detectors (often referred to as GW antennas) typically consist of cylinders made from materials with high quality factors $\mathbb{Q}$ (such as aluminum, sapphire, niobium), isolated from all possible terrestrial disturbances, and cooled to cryogenic temperatures to suppress thermal noise. 

The incoming GW excites the fundamental mode of oscillation in the cylinder at its resonance frequency, and the displacement of the cylinder is recorded by a sensitive sensor. To date, no credible GW signals have been detected by these antennas.

GW interferometers are Michelson two-arm interferometers (see Figure 14.2), where mirrors act as the free masses. The mirrors are specially suspended to isolate them from external terrestrial noise (such as seismic ground vibrations, anthropogenic noise, etc.). A powerful continuous-wave laser serves as the radiation source. GWs with frequencies greater than the pendulum frequency of the suspended mirrors $f_M$ displace the mirrors relative to each other as if they were free masses, leading to a change in the difference of lengths of the interferometer arms $\Delta L = L_1 - L_2$. The output signal measured by a photodiode is directly proportional to $h(t)$.

Currently, several large GW interferometers of this type are under construction: two LIGO detectors in the USA (arm length 4.5 km), the VIRGO detector in Italy (4 km), the GEO-600 detector in Germany (600 m), and the TAMA-300 detector in Japan (300 m). The commissioning of the first phase of these unique instruments is expected in 2001-2002.

<div align="CENTER">
![Figure 14.2: Diagram of a Michelson GW interferometer. The suspended mirrors act as free masses. A GW modifies the distances between the mirrors in the interferometer arms, which causes a change in the interference pattern.](./imgs/98439b9930f3420ea79d12b31971ea3b_img1831.png)
</div>

Compared to resonance antennas, interferometers have a significant advantage because they record the complete signal $h(t)$ across a wide frequency range (from 10 to 1000 Hz), whereas the resonance system effectively only measures the Fourier component of the signal at the corresponding resonance frequency ($f_M \sim 1$ kHz). The expected sensitivity of the first interferometers $h \sim 10^{-21}$ around the frequency of 100 Hz, and the second phase of these receivers, which will be commissioned in a few years, will be able to register GWs with amplitudes at the level of $h \sim 10^{-4} - 10^{-1}$.

<div align="CENTER">
![Figure 14.3: The orbit of the LISA space interferometer, consisting of 6 satellites. The satellites themselves act as free masses.](./imgs/7900e2be72fb43fc9d067e2d54beffe5_img1835.png)
</div>

The sensitivity of ground-based interferometers deteriorates sharply at frequencies below 1 Hz (primarily due to the inability to filter out seismic noise). Thus, for the detection of low-frequency GWs (typically $f \sim 0.001 - 1$ Hz), which are emitted by tightly bound binary stars in our Galaxy or during catastrophic events in the cores of galaxies containing supermassive black holes, the creation of a space interferometer LISA (a joint project of the European Space Agency and NASA, $> 2010$) is planned. The role of free masses will be played by six satellites positioned on a special orbit around Earth. The distance between each pair of satellites is 5 million km.

The expected sensitivity of planned or under-construction GW interferometers is illustrated in Figure 14.4. To characterize the sensitivity of a detector, we use the spectral noise density in units of $S_h [\text{Hz}]$, so that in the frequency band $f$, which is defined by the type of source, the minimum detectable signal magnitude (for a signal-to-noise ratio of 1) is given by:
$$h_{min} \approx h_f \sqrt{\Delta f}.$$

For strictly periodic sources, the frequency band is determined by the uninterrupted observation time $T$; thus, $h_{min} = \frac{h_f}{\sqrt{T}}$. The smaller the amplitude of the signal we want to detect, the longer we must observe. For a rough estimate of sensitivity in detecting broad-band signals, we can assume $\Delta f \sim f$. The same figure shows some typical astrophysical GW sources (see section 14.4).

<div align="CENTER">
![Figure 14.4: Spectral noise density of ground and space GW interferometers under construction or planned across a wide frequency range. Expected signal amplitudes from various astrophysical sources are also shown. Figure from B. Schutz, Classical and Quantum Gravity, 1999, in press.](./imgs/4f3cf04a15164fda97579f51d7daad49_img1845.png)
</div>## 14.3 Radiation of Gravitational Waves

Let us consider how and under what conditions gravitational radiation occurs. By analogy with electromagnetism, one might suppose that energy radiation (i.e., the field's amplitude diminishing in space as $\frac{1}{r}$) arises from the change of the "gravitational" dipole moment 

$$d_G = \sum M_i r_i,$$ 

where $M_i$ represents the masses of the particles involved in the emitting system. However, due to the conservation of total momentum within a closed system, $\dot{g} \equiv 0$, dipole radiation does not occur. For non-relativistic motion of charges, a magnetic dipole radiation is generated, which is also absent in gravity due to the conservation of total angular momentum in a closed system. Indeed, the gravitational analogue of the magnetic dipole moment 

$$\mu_{G} = \frac{1}{c} \sum_{i} \vec{r}_{i} \times (M_{i} \vec{r}_{i})$$ 

does not exist. Therefore, the lowest possible mode of gravitational wave (GW) emission is the **quadrupole mode.**

If the radiation is caused by macroscopic motion of masses moving with speeds much smaller than the speed of light, then the dimensionless amplitude of the gravitational field, at a distance $r$ from the source in the quadrupole approximation, is roughly given by 

$$h \sim \frac{G \dot{Q}}{c^{4} r} ,$$ 

where 

$$Q_{ij} \sim \int \rho x_{i} x_{j} d^{3}x$$ 

represents the quadrupole moment.

As in electromagnetism, the energy flux carried by the wave (the Poynting vector) should be proportional to the square of the field strength, i.e., the square of the derivative of the wave's variable amplitude:

$$\frac{dE}{dt} \approx \frac{G}{c^5} \left( \frac{d^3Q}{dt^3} \right)^{2} .$$ 

The energy radiated is thus proportional to the square of the **third** time derivative of the quadrupole moment. Not detailing the numerical coefficient (which depends on the precise definition of the quadrupole moment), we write the energy loss due to GW emission as:

$$dE dt \sim L_0 \left( \frac{E_{kin}}{T} \right)^{2} \sim L_{0} \left( \frac{R_{g}}{R} \right)^{2} \left( \frac{v}{c} \right)^{4} ,$$ 

where $L_0 \equiv \frac{c^5}{G}$ and $L_0 \approx 10^{59}$. 

It is noteworthy that the magnitude 

$$\frac{R_g}{c}$$ 

has dimensions of luminosity and is numerically equal to 

$$L_{pl} \sim m_{Pl}c^{2} $$ 

[erg/s]. This fundamental quantity is sometimes referred to as the "Planck luminosity" and is obtained by dividing the Planck energy by the Planck time or, for any body of mass $M$, by dividing its rest energy by the minimum characteristic time. By writing as before, up to an order of magnitude, and differentiating, one obtains a useful estimate:

$$h_{max} \sim \frac{r_g}{r}$$ 

for the gravitational wave amplitude, suggesting it is on the order of 

$$h_{max} \sim 3 \times 10^{-23}$$ 

when evaluating near compact structures like black holes. Here, $r_g = \frac{2GM_q}{c^2}$ and we find $\sim 10^{28}$ as the effective radius for our estimations. 

This behavior captures the essence of gravitational wave production in astrophysical scenarios, which is vital for comprehending phenomena such as colliding black holes or neutron stars.## 14.4 Astrophysical Sources of Gravitational Waves

As we have seen, in astrophysics, the characteristic mass of a star is defined by fundamental constants of nature and is typically on the order of about one solar mass. Besides mass, another crucial parameter of a self-gravitating configuration is size or average density $\rho$. The latter determines the characteristic dynamical time—the free-fall time, given by 

$$t_{ff} \sim \frac{1}{\sqrt{G \rho}}.$$ 

The masses of stars are confined within relatively narrow limits, approximately between $0.1 - 100 M_\odot$, whereas densities occupy a much broader range—from less than $1 \text{ g/cm}^3$ to nuclear densities $\sim 10^{15} \text{ g/cm}^3$. 

This implies that the characteristic frequencies of gravitational waves (GWs) emitted by gravitationally bound objects of stellar mass span a range of 7 orders of magnitude, from $\sim 10^{-9} \text{ Hz}$ to several kHz. 

## 14.4.1 Supernova Explosions

As previously discussed when referring to equations (14.4) and (14.6), the most promising sources of GWs must possess small sizes ($R = \mathcal{O}(R_g)$) and high velocities ($v = \mathcal{O}(c)$) of masses contributing to a non-zero quadrupole moment. Such extreme physical conditions may accompany the births of neutron stars or black holes during the collapse of the cores of massive stars at the end of their evolution. 

Although reliable theoretical calculations of this process are likely not feasible, one can expect significant non-sphericity in the collapse process, potentially leading to the emission of a GW impulse during the collapse time frame. Current estimates suggest that the emitted fraction of energy could be 

$$\Delta E_{\nu} \sim 0.15 M_{\odot} c^2.$$ 

This is significantly less than the energy carried away by neutrinos ($\sim 10^{10} \text{ erg/s}$). Nonetheless, the GW impulse from a supernova in the Milky Way (i.e., at a distance of about 10 kpc) could be detected at a level of $h \sim 10^{-21}$. Supernova explosions in the Milky Way occur on average once every 30-50 years, thus the "hunt" for such events can be extended over a considerable period. 

As the sensitivity of detectors increases, the observable region of space expands as $h^{-3}$, allowing for the inclusion of other galaxies and a heightened event registration rate. However, the extensive uncertainty in the energy released during the collapse in the form of GWs makes supernovae less than optimal sources for detection in the near future.

## 14.4.2 Rapidly Rotating Neutron Stars

The simplest example of a body emitting GWs is a non-spherically symmetric rotating star. If the fraction of rotational energy associated with the non-spherical mass distribution is denoted as 

$$\varepsilon = 10^{-6},$$ 

where $I \sim MR^2$ is the moment of inertia of the rotating star and $\omega$ is the rotation frequency, then from (14.6) we find

$$E_{\text{kin}} = \varepsilon I \omega^2.$$ 

For a rapidly rotating neutron star (pulsar) with a characteristic value of $\rho \sim 10^{13} \text{ g/cm}^3$ at a frequency of 100 Hz, we obtain 

$$\frac{dE}{dt} \sim 10^{35} \text{ erg/s},$$ 

which is comparable to the energy carried away by relativistic particles from an actively working pulsar. The parameter of non-sphericity $\varepsilon$ is poorly known, and thus, despite pulsars having an undeniable advantage as sources with a known rotation frequency and position in the sky, the amplitude of the expected GW signal from pulsars is defined very unreliably. The situation is slightly better, as the signal-to-noise ratio in the detector increases as $\sqrt{T}$ with the continuous accumulation of a periodic signal over time $T$. This situation is expected to be exploited when searching for GW signals in the continuous data stream from laser interferometers.

Another opportunity for observing GWs from rapidly rotating compact stars is related to the occurrence of specific instabilities in rotating bodies, which either lead to the emergence of a variable quadrupole moment or the development of cyclonic layered flows (in a rotating reference frame) at zero quadrupole moment. In the first case, quadrupole radiation is generated, as described above; in the second, magneto-quadrupole GW radiation arises due to asymmetric mass currents. Although the magneto-quadrupole approximation has a higher order of smallness compared to the quadrupole one, it has been shown that in rapidly rotating young neutron stars, it can play a determining role and carry away a significant portion of the initial angular momentum of a young neutron star. Such instabilities are expected to accompany the formation of a young hot rotating neutron star, though uncertainties remain—related, for example, to the viscosity of the neutron star material.

## 14.4.3 Double Stars

A classic example of a system with a large quadrupole moment is two bodies with masses $M_1$ and $M_2$, rotating in orbit around a common center of mass (a binary star). For this setup, let $\mu \equiv \frac{M_{1} M_{2}}{M}$ denote the reduced mass, where $M = M_1 + M_2$, and $a$ is the semi-major axis of the orbit. It is estimated that double stars account for at least half of all stars in the galaxy ($\sim 10^{11}$), making them the most reliable sources of gravitational waves. The main question is about the frequency and amplitude of the GWs they emit.

For circular orbits, the radiation occurs precisely at the **double** orbital frequency, since the quadrupole moment takes on the same value twice per period (symmetry with respect to $M_1$ and $M_2$ in the reduced mass!). The semi-major axis $a$ is related to the orbital frequency $\omega_{\text{orb}} = \frac{2\pi}{P}$, where $P$ is the orbital period, by Kepler's third law, as follows:

$$\frac{dE}{dt} \sim \left( \frac{G^4}{c^5} \right) \left( \frac{\mu^2 M^3}{a^5} \right).$$ 

Constant energy loss from the binary system $dE/dt$ due to gravitational radiation leads to a decrease in the semi-major axis $a$ and the orbital period $P$ of the binary system. This effect was observed during prolonged precise observations of the pulsar PSR 1213+16, which is part of a binary system where the second component is another neutron star not observable as a pulsar. High-precision timing of radio pulses from the pulsar, which moves around the common center of mass of the binary system, indicates a consistent decrease in the orbital period of the system. In a binary system consisting of two neutron stars, there are no other physical mechanisms for reducing the orbital energy except through gravitational wave emission. Moreover, the rate of period decrease has been measured with an accuracy better than 0.5%, matching the value obtained from the quadrupole formula to within this precision.

For this discovery and research of this double pulsar, American astrophysicists J. Taylor and R. Hulse were awarded the Nobel Prize in Physics in 1992. Thus, astronomical observations currently provide indirect evidence supporting the reality of GW emission from binary stars, confirming Einstein's general relativity predictions with an accuracy better than 0.5%. 

![](./imgs/3fa8eb6fd9c24912b8d95fab289ab1d9_img1904.png)

**Figure 14.5:** Dependence of GW amplitude on time for a merging double system consisting of two point masses. On the right, the change in shape is shown in the presence of a non-zero eccentricity of the orbit. The formula illustrates the dependence of the amplitude $h$ of the GW polarizations on the angle of inclination $\theta$ of the orbital plane of the binary system to the line of sight.

The strong dependence of the rate of decrease of the orbital period on the period itself ($dP/dt \propto P^{-8/3}$) causes the orbit to shrink at an accelerating pace, suggesting that within a finite time, two stars should come close and merge into one. For two compact neutron stars or black holes, this time is less than the Hubble time; for instance, for the double pulsar PSR 1913+16, it is approximately 100 million years. During the merger process of two compact bodies, the semi-major axis of the orbit is about the size of a star, i.e., several gravitational radii, and the amplitude of the generated gravitational waves is nearly at its maximum possible level.

Thus, merging double neutron stars and black holes are the most promising sources for detection in the next generation of GW detectors. The pressing question is how frequently such catastrophic events occur in the Milky Way. Observationally, there is credible evidence for the existence of several tight pairs of neutron stars, with estimates for the merger rate suggesting on the order of $10^{-6}$ years in the galaxy. However, stellar evolution theory implies that the merger rate for such double systems in the galaxy could be up to one to two orders of magnitude higher, about once every 10–30 thousand years. Therefore, first-generation GW interferometers with sensitivities of $h \sim 10^{-21}$ at a frequency of 100 Hz would be able to detect several such systems operating continuously for one year. An example of the GW amplitude from a merging double system is shown in Figure 14.5.## 14.4 Astrophysical Sources of Gravitational Waves

### Literature

1. C. Shapiro, S. Tykulsky. *Black Holes, White Dwarfs, and Neutron Stars*. In 2 parts. Vol. 2, Ch. 16. Moscow: Mir, 1985.

2. L. P. Grishchuk. *Successes in Physics of Sciences*, Vol. 156, Issue 2, p. 297 (1988).

3. B. Schutz, *Classical and Quantum Gravity*, 1999, in press.

---

### Key Words in Publications:
- [Stars](http://db/search.html?kw=13809) 
- [Interstellar Medium](http://db/search.html?kw=14142) 
- [Cosmology](http://db/search.html?kw=15891) 
- [Theoretical Astrophysics](http://db/search.html?kw=10526) 
- [Astrophysics](http://db/search.html?kw=16508)

### Related Publications:
- [Stars](http://db/search.html?words=%E7%E2%E5%E7%E4%FB)
- [Interstellar Medium](http://db/search.html?words=%CC%E5%E6%E7%E2%E5%E7%E4%ED%E0%FF%20%F1%F0%E5%E4%E0)
- [Cosmology](http://db/search.html?words=%CA%EE%F1%EC%EE%EB%EE%E3%E8%FF)
- [Theoretical Astrophysics](http://db/search.html?words=%F2%E5%EE%F0%E5%F2%E8%F7%E5%F1%EA%E0%FF%20%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0)
- [Astrophysics](http://db/search.html?words=%E0%F1%F2%F0%EE%F4%E8%E7%E8%EA%E0)

### Related Topics:
- [Black Hole Destroying a Star: Animation](http://db/msg/1931410)
- [Stars, Dust, and Nebula in NGC 6559](http://db/msg/1904844)
- [25 Brightest Stars in the Night Sky](http://db/msg/1863796)
- [Animation: Black Hole Destroying a Star](http://db/msg/1736616)
- [Decomposition of Distant Light](http://db/msg/1696356)
- [Comparison of Star Sizes](http://db/msg/1415428)
- [Farthest of All Known Stars?](http://db/msg/1406555)

### Reader Opinions
[70 Comments](http://db/forums/1170612)

### Rating
<b>Rating:</b> 3.1 [Votes: 182]

---

For further reading, you may refer to sections on [Astrometry](http://db/sect/300000007), [Astronomical Instruments](http://db/sect/300000010), [Astronomical Education](http://db/sect/1168516), [Astrophysics](http://db/sect/300000003), [History of Astronomy](http://db/sect/300000016), [Space Exploration](http://db/sect/300000012), [Amateur Astronomy](http://db/sect/300000013), [Planets and the Solar System](http://db/sect/300000005), and [The Sun](http://db/sect/300000004).## Table of Contents

- [Table of Contents](#)
- [1. Introduction: Spacetime Scales in Astrophysics](#)
  - [1.1 Angular and Photometric Distances](#)
  - [1.2 Times](#)
  - [1.3 Masses](#)
  - [1.4 Solar Units](#)
  - [1.5 Planck Units](#)
  - [1.6 Dimensionless Numbers](#)
- [2. Radiation: Fundamentals of Radiation Transfer Theory](#)
  - [2.1 Radiation Transfer Equation](#)
    - [2.1.1 Basic Definitions](#)
    - [2.1.2 Macroscopic Characteristics of Radiation](#)
    - [2.1.3 Constancy of Specific Intensity along a Ray in Empty Space](#)
  - [2.2 Transfer Equations](#)
    - [2.2.1 Emission Coefficient](#)
    - [2.2.2 Absorption Coefficient](#)
    - [2.2.3 Radiation Transfer Equation](#)
    - [2.2.4 Optical Thickness: Connection to Mean Free Path](#)
    - [2.2.5 Source Function](#)
    - [2.2.6 Formal Solution of the Transfer Equation](#)
  - [2.3 Thermal Radiation](#)
    - [2.3.1 Perfect Black Body](#)
    - [2.3.2 Planck’s Law for Perfect Black Bodies](#)
  - [2.4 Characteristic Temperatures of Astrophysical Sources](#)
- [3. Features and Physical Limitations of Astrophysical Observations](#)
  - [3.1 Main Task of Observational Astronomy](#)
  - [3.2 Telescopes and Radiation Receivers](#)
  - [3.3 Astronomical Intermezzo: Stellar Magnitudes](#)
  - [3.4 Physical Limitations on the Accuracy of Astronomical Observations](#)
  - [3.5 On the Accuracy of Light Flux Measurements](#)
  - [3.6 Literature](#)
- [4. Interstellar Medium](#)
  - [4.1 Physical Features of Cosmic Plasma State](#)
  - [4.2 21 cm Neutral Hydrogen Radio Line](#)
  - [4.3 Clouds of Neutral Hydrogen HI and Thermal Instability of the Interstellar Medium](#)
  - [4.4 Ionized Hydrogen and HII Regions](#)
  - [4.5 Molecular Clouds, Star-Forming Regions, and Cosmic Masers](#)
  - [4.6 Cosmic Rays and Synchrotron Radiation](#)
  - [4.7 Other Methods of Cosmic Plasma Diagnostics](#)
  - [4.8 Literature](#)
- [5. Stars](#)
  - [5.1 General Information](#)
  - [5.2 Star Formation](#)
  - [5.3 Protostars](#)
  - [5.4 Stationary Stars](#)
- [6. Stars (Continued)](#)
  - [6.1 Nuclear Reactions in Stars](#)
  - [6.2 Features of Nuclear Reactions in Stars](#)
  - [6.3 M-L and M-R Relations for Main Sequence Stars](#)
- [7. Evolution of Stars](#)
  - [7.1 Evolution of Stars after the Main Sequence](#)
  - [7.2 Degeneracy of Matter](#)
  - [7.3 Chandrasekhar Limit and Fundamental Mass of a Star](#)
  - [7.4 Neutronization of Matter and Loss of Stability of a Star](#)
  - [7.5 Supernova Explosions](#)
- [8. Stellar Evolution Remnants](#)
  - [8.1 White Dwarfs](#)
  - [8.2 Neutron Stars](#)
  - [8.3 Black Holes](#)
  - [8.4 Pulsars](#)
  - [8.5 Literature](#)
- [9. Galaxies: General Information and Quasars](#)
  - [9.1 Galaxies: General Information](#)
  - [9.2 Quasars and Active Galactic Nuclei](#)
  - [9.3 Eddington Limit of Luminosity When Accreting onto Compact Relativistic Objects](#)
  - [9.4 Black Holes in the Centers of Normal Galaxies and the Mass Ratio of the Black Hole to the Bulge](#)
- [10. Cosmology](#)
  - [10.1 Friedmann Cosmology](#)
  - [10.2 Friedmann Models with Cosmological Constant](#)
  - [10.3 Literature](#)
- [11. Cosmology (Continued)](#)
  - [11.1 Light Propagation: Redshift](#)
    - [11.1.1 Horizon](#)
    - [11.1.2 Distances](#)
    - [11.1.3 Surface Brightness and Olbers' Paradox](#)
  - [11.2 Hot Universe](#)
  - [11.3 Primordial Nucleosynthesis ("The First Three Minutes")](#)
    - [11.3.1 Constraints on the Number of Neutrino Types from Primordial Nucleosynthesis](#)
  - [11.4 Relic Radiation and the Era of Recombination](#)
  - [11.5 Fluctuations of Relic Radiation](#)
- [12. Cosmology (Continued II)](#)
  - [12.1 Challenges of Classical Cosmology](#)
    - [12.1.1 Horizon Problem (Causality Problem)](#)
    - [12.1.2 Flat Universe Problem](#)
  - [12.2 Inflationary Universe Model](#)
  - [12.3 Growth of Small Perturbations](#)
    - [12.3.1 Gravitational (Jeans) Instability](#)
  - [12.4 Formation of Large-Scale Structure of the Universe](#)
- [13. Dark Matter and Gravitational Lenses](#)
- [14. Gravitational-Wave Astronomy](#)
  - [14.1 Description](#)
  - [14.2 Detection of Gravitational Waves](#)
  - [14.3 Emission of Gravitational Waves](#)
  - [14.4 Astrophysical Sources of Gravitational Waves](#)
    - [14.4.1 Supernova Explosions](#)
    - [14.4.2 Rapidly Rotating Neutron Stars](#)
    - [14.4.3 Binary Stars](#)
  - [14.5 Literature](#)

---

### Publications with Keywords:
- [Stars](#) - [Interstellar Medium](#) - [Cosmology](#) - [Theoretical Astrophysics](#) - [Astrophysics](#)

### Publications by Terms:
- [Stars](#) - [Interstellar Medium](#) - [Cosmology](#) - [Theoretical Astrophysics](#) - [Astrophysics](#)## 1. Introduction: Spacetime Scales in Astrophysics

The range of temporal and spatial scales that we encounter in astrophysics is quite broad. Due to the finiteness of the speed of light $c$, there exists a fundamental relationship between the characteristic scales $l$ of the phenomenon under consideration and the characteristic minimal time $t_{\text{min}}$ at which one might expect variations in the electromagnetic radiation generated at that scale:

$$t_{\text{min}} = \frac{l}{c}$$

Another crucial characteristic of any astrophysical object is its mass $M$. In each specific case (e.g., a star, a planet, a galaxy), the mass $M$ can be associated with a characteristic scale $l$. The minimal size $l_{\text{min}}$, corresponding to a macroscopic mass $M$, is determined by gravitational interactions and is approximately equal to the gravitational radius:

$$l_{min} \sim R_{g} = \frac{2GM}{c^{2}} \approx (3 \, \text{km}) \left( \frac{M}{M_{\odot}} \right)$$

where $G \approx 6.67 \times 10^{-8}$. 

As long as the size of the object being studied is large compared to its gravitational radius $R_g$, it is sufficient to describe the physical processes using Newtonian physics. Otherwise, relativistic effects (General Relativity) become significant and even dominant.

### Examples
- The Sun has a radius of $R_{\odot} \simeq 700,000$ km; 
- A planet like Jupiter has a mass $M_{Jp} \sim 10^{-3} M_{\odot}$ and radius $R_{Jp} \sim 10$ times its gravitational radius $R_g(M_{p}) \sim 3$ km. 
- A neutron star, with a radius of about 10 km, has important relativistic corrections; 
- A non-rotating black hole has an event horizon radius equal to its gravitational radius, making it a fully relativistic object; 
- The universe as a whole has a gravitational radius $R_g \sim \frac{c}{H_0}$, where $H_0$ is the current value of the Hubble constant, indicating that it should also be considered within the framework of relativistic theory (General Relativity). 

In summary, understanding the various scales at play in astrophysics not only aids in the comprehension of specific celestial objects and their behaviors but also underscores the need to utilize appropriate theoretical frameworks, especially when the sizes and masses involved approach the relativistic regime.## Table of Contents

- **Table of Contents**
- **1. Introduction: Space-Time Scales in Astrophysics**
  - 1.1 Angular and Photometric Distances
  - 1.2 Times
  - 1.3 Masses
  - 1.4 Solar Units
  - 1.5 Planck Units
  - 1.6 Dimensionless Numbers
- **2. Radiation: Basics of Radiation Transfer Theory**
  - 2.1 Radiation Transfer Equation
    - 2.1.1 Basic Definitions
    - 2.1.2 Macroscopic Characteristics of Radiation
    - 2.1.3 Constancy of Specific Intensity Along a Ray in Empty Space
  - 2.2 Transfer Equation
    - 2.2.1 Emission Coefficient
    - 2.2.2 Absorption Coefficient
    - 2.2.3 Transfer Equation
    - 2.2.4 Optical Thickness: Connection to Mean Free Path
    - 2.2.5 Source Function
    - 2.2.6 Formal Solution of the Transfer Equation
  - 2.3 Thermal Radiation
    - 2.3.1 Perfect Black Body
    - 2.3.2 Planck’s Law for Perfect Black Bodies
  - 2.4 Characteristic Temperatures of Astrophysical Sources
- **3. Features and Physical Constraints of Astrophysical Observations**
  - 3.1 Main Task of Observational Astronomy
  - 3.2 Telescopes and Radiation Receivers
  - 3.3 Astronomical *Intermezzo*: Stellar Magnitudes
  - 3.4 Physical Limitations on the Accuracy of Astronomical Observations
  - 3.5 On the Accuracy of Light Flux Measurements
- **4. Interstellar Medium**
  - 4.1 Physical Characteristics of Cosmic Plasma
  - 4.2 Radio Line of Neutral Hydrogen at 21 cm
  - 4.3 Clouds of Neutral Hydrogen (HI) and Thermal Instability of the Interstellar Medium
  - 4.4 Ionized Hydrogen and H II Regions
  - 4.5 Molecular Clouds, Star Formation Regions, and Cosmic Masers
  - 4.6 Cosmic Rays and Synchrotron Radiation
  - 4.7 Other Methods for Diagnosing Cosmic Plasma
- **5. Stars**
  - 5.1 General Information
  - 5.2 Star Formation
  - 5.3 Protostars
  - 5.4 Stationary Stars
- **6. Stars (Continued)**
  - 6.1 Nuclear Reactions in Stars
  - 6.2 Features of Nuclear Reactions in Stars
  - 6.3 M-L and M-R Relations for Main Sequence Stars
- **7. Star Evolution**
  - 7.1 Evolution of Stars After the Main Sequence
  - 7.2 Degeneracy of Matter
  - 7.3 Chandrasekhar Limit and Fundamental Mass of a Star
  - 7.4 Neutronization of Matter and Loss of Star Stability
  - 7.5 Supernova Explosions
- **8. Remnants of Stellar Evolution**
  - 8.1 White Dwarfs
  - 8.2 Neutron Stars
  - 8.3 Black Holes
  - 8.4 Pulsars
- **9. Galaxies: General Information and Quasars**
  - 9.1 Galaxies: General Overview
  - 9.2 Quasars and Active Galactic Nuclei
  - 9.3 Eddington Limit of Luminosity During Accretion onto Compact Relativistic Objects
  - 9.4 Black Holes at the Centers of Normal Galaxies and the Black Hole-Bulge Mass Relation
- **10. Cosmology**
  - 10.1 Friedmann Cosmology
  - 10.2 Friedmann Models with Cosmological Constant
- **11. Cosmology (Continued)**
  - 11.1 Propagation of Light: Redshift
    - 11.1.1 Horizon
    - 11.1.2 Distances
    - 11.1.3 Surface Brightness and Olbers' Paradox
  - 11.2 Hot Universe
  - 11.3 Primordial Nucleosynthesis ("The First Three Minutes")
    - 11.3.1 Constraints on the Number of Neutrino Types from Primordial Nucleosynthesis
  - 11.4 Cosmic Microwave Background Radiation and the Recombination Era
  - 11.5 Fluctuations in Cosmic Microwave Background Radiation
- **12. Cosmology (Continued II)**
  - 12.1 Challenges of Classical Cosmology
    - 12.1.1 Horizon Problem (Causality Problem)
    - 12.1.2 Flatness Problem
  - 12.2 Inflationary Universe Model
  - 12.3 Growth of Small Perturbations
    - 12.3.1 Gravitational (Jean's) Instability
  - 12.4 Formation of Large-Scale Structure in the Universe
- **13. Dark Matter and Gravitational Lensing**
- **14. Gravitational Wave Astronomy**
  - 14.1 Overview
  - 14.2 Detection of Gravitational Waves
  - 14.3 Emission of Gravitational Waves
  - 14.4 Astrophysical Sources of Gravitational Waves
    - 14.4.1 Supernova Explosions
    - 14.4.2 Rapidly Rotating Neutron Stars
    - 14.4.3 Binary Stars