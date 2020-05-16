
<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml" lang="" xml:lang="">
<head>
  <meta charset="utf-8" />
  <meta name="generator" content="pandoc" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes" />
  <title>chapter_1</title>
  <style>
    code{white-space: pre-wrap;}
    span.smallcaps{font-variant: small-caps;}
    span.underline{text-decoration: underline;}
    div.column{display: inline-block; vertical-align: top; width: 50%;}
    div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
    ul.task-list{list-style: none;}
  </style>
  <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
  <!--[if lt IE 9]>
    <script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv-printshiv.min.js"></script>
  <![endif]-->
</head>
<body>
<h1 id="antenna-fundamentals">Antenna Fundamentals</h1>
<h2 id="introduction">INTRODUCTION</h2>
<p>Wireless communication became a reality after the invention of the antenna. Antenna is an integral part of any Wireless Communication system; whether it is fixed communication or Mobile communication. The invention of Radio in 1895 gave birth to Wireless Communications. The initial experimental contributions of Hertz (1857-1894) of Germany helped in understanding the generation and transmission of Electromagnetic wave. However, the great genius Guglielmo Marconi (1874-1937) was responsible for realizing practical, reliable radio communications through his far reaching inventions. Thus he is regarded as ‘Father of Radio’. Marconi’s relentless efforts made it possible for long distance communication using Radio waves. The advances in long distance communication in Radio, Radio broadcasting, Television, Radar, Satellite Communications, Mobile Communication, and Information Superhighways had their beginnings in Marconi’s experiments on wireless. Wireless Communication has made great impact on the living standards of the human society from time to time. Today if we are able to connect and communicate globally in a short time to any part of the world, it is due to these advances in Radio Communications. Antenna is one of the very important devices in Radio Communications. There are a large variety of antennas which are used in different applications. However, all these antennas operate according to the fundamental Principles of Electromagnetic theory.</p>
<p>The discovery of Electromagnetic induction by Michael Faraday (1791-1867) in 1831 demonstrated that a changing magnetic field can produce electric current. Further, the discovery of Electromagnetic theory of light, and the field and wave equations of Electromagnetic field by James Clark Maxwell (1831-1979) formed the major basis for the Electromagnetic waves. It was Maxwell who gave the theoretical foundations for a unified theory of Electricity and Magnetism and propounded the Electromagnetic theory. It was a decade later, Heinrich Hertz (1857-1894), a German Scientist, who experimentally demonstrated the generation of Electromagnetic waves and their propagation in free space. His concept of Hertzian doublet antenna is the basis for many antennas. However, the discoveries of Hertz were confined to the laboratory. Many scientists including Jagadeesh Chandra Bose (JC Bose 1858-1937) in India conducted investigations on the findings of Hertz. J.C.Bose built a Microwave spectrometer, which has now become an essential part of microwave communication link. Popov (1859-1905) of Russia devised a radio antenna to detect electromagnetic radiation from lightning. Also Oliver Lodge (8151-1940) of England and Augusto Righi (1858-1937) in Italy also had continued their studies on Electromagnetic waves. Lodge gave a lecture-cum-demonstration on the transmission and reception of Electromagnetic waves in 1894. Righi had given lectures on Hertzian waves at the University of Bologna in 1894.</p>
<p>Marconi, in 1894 read the experimental findings of Hertz in 1894 and repeated Hertz’s experiments. He used Hertzian waves to send messages. He was able to transmit telegraph signals over a distance of 10 meters. Later he improvised the system for long distance communication. He used 130m long copper wire antenna. In 1932, he demonstrated Microwave communication at 50cm between Rome and Sardinia, distance of 270km. However, after Marconi’s wireless, the Modern Communications has seen several advances. There are several kinds of antennas and several structures which are used in variety of applications. With the activities of the mankind expanding into space, the need for antennas also has grown enormously. Therefore antenna will provide link to outer space and from there to any other point. The usage of antennas in normal Communication will be extended to reach the Stars. In the era of Internet and Mobile Cellular Communications, newer antenna systems also have been developed to be more miniaturized.</p>
<h2 id="antenna-types">Antenna Types</h2>
<p>Antennas have different configurations and types. However, we can broadly classify antennas into four major types as follows.</p>
<h3 id="wire-antennas">WIRE ANTENNAS</h3>
<p>It can also be a loop antenna as shown in fig <a href="#fig:fig1" data-reference-type="ref" data-reference="fig:fig1">1.1</a>(b) or it can be a long wire antenna as in fig <a href="#fig:fig1" data-reference-type="ref" data-reference="fig:fig1">1.1</a>(c) whose length will be <span class="math inline">\(l = 4\lambda \; to \; 8\lambda\)</span>. It can be a helical wire antenna as shown in fig <a href="#fig:fig1" data-reference-type="ref" data-reference="fig:fig1">1.1</a>(d).</p>
<figure>
<img src="assets/figures/ch1/fig1.png" id="fig:fig1" alt="" /><figcaption>(a) Dipole with <span class="math inline">\(l=\lambda/2\)</span>, (b) loop antenna, (c) long wire antenna (Rhombic antenna), (d) Helical antenna</figcaption>
</figure>
<p>They are the most commonly used antennas. They are found on automobiles, buildings, and spacecrafts.</p>
<p>They are of various shapes: -</p>
<p>Straight wire dipole fig <a href="#fig:fig1" data-reference-type="ref" data-reference="fig:fig1">1.1</a>(a), loop antennas fig <a href="#fig:fig1" data-reference-type="ref" data-reference="fig:fig1">1.1</a>(b), helical antennas fig <a href="#fig:fig1" data-reference-type="ref" data-reference="fig:fig1">1.1</a>(c) and long wire non-resonant antennas fig <a href="#fig:fig1" data-reference-type="ref" data-reference="fig:fig1">1.1</a>(d). Wire antennas are derived from transmission line.</p>
<h3 id="aperture-antennas">APERTURE ANTENNAS</h3>
<figure>
<img src="assets/figures/ch1/fig2.png" id="fig:fig2" alt="" /><figcaption>(a) Conical Horn, (b) Rectangular Horn</figcaption>
</figure>
<p>These are high frequency antennas and are derived from wave guides. These antennas have their shapes of horn: either square or circular aperture. They can be mounted conveniently on aircrafts and spacecrafts. The structure of horn antennas are shown in fig <a href="#fig:fig2" data-reference-type="ref" data-reference="fig:fig2">1.2</a>(a) and fig <a href="#fig:fig2" data-reference-type="ref" data-reference="fig:fig2">1.2</a>(b). These antennas are extensively used as primary feed antennas to excite UHF and Microwave antennas. In particular, they are used as primary feeds for parabolic reflector antennas.</p>
<h3 id="microwave-antennas"> MICROWAVE ANTENNAS</h3>
<p>The antennas used at Microwave frequency will have to work in the frequency range of several GHz. At such high frequencies the wavelength will be in mm. Therefore it is possible to have antenna dimensions of several orders of magnitude greater than the wavelength. The EM waves at microwaves can be treated in terms of rays. We apply principles of geometrical optics to analyze them. The principles of focusing and collimation can be applied to microwave antennas. Therefore several physical shapes and structures are possible at microwaves. A few of the microwave antennas are</p>
<ul>
<li><p>Parabolic reflector antennas as shown in fig <a href="#fig:fig3" data-reference-type="ref" data-reference="fig:fig3">1.3</a>(a),</p></li>
<li><p>Lens antennas shown in fig <a href="#fig:fig3" data-reference-type="ref" data-reference="fig:fig3">1.3</a>(b)</p></li>
<li><p>Micro strip antennas</p></li>
</ul>
<figure>
<img src="assets/figures/ch1/fig3.png" id="fig:fig3" alt="" /><figcaption>(a) Parabolic Reflector, (b) Lens antenna</figcaption>
</figure>
<h3 id="array-antennas">ARRAY ANTENNAS</h3>
<p>Single antenna may not provide the necessary directivity and other characteristics. Then, two or more antenna elements laid out in parallel or in line with each other form an array. These provide very high directivity and the desired pattern. Arrays of dipoles as well as arrays of parabolic reflectors are used in Radio Telescopes to receive signals from astronomical objects. The array of dipoles is shown in Fig <a href="#fig:fig4" data-reference-type="ref" data-reference="fig:fig4">1.4</a>(a)</p>
<figure>
<img src="assets/figures/ch1/fig4.png" id="fig:fig4" alt="" /><figcaption>(a) Array of dipoles, (b) Array of parabolic antennas</figcaption>
</figure>
<p>Microwave antenna Arrays are used in RADAR, Satellite communications, Radio astronomy, Radio telescope, etc. The Radio Telescope at Ootacamand (Ooty) is around 1.6 km long consisting of array of parabolic reflector antennas, whereas an antenna array of dipoles in two dimensions at Gowribidnur Radio telescope is several thousand square meters in area.</p>
<h2 id="definition-of-an-antenna-and-principles-of-radiation">DEFINITION OF AN ANTENNA AND PRINCIPLES OF RADIATION</h2>
<p>Antenna is a device used for radiating or receiving Electromagnetic waves. It can be defined as a transitional structure between the free space and a guiding device or vice-versa.</p>
<p>The guiding structure can be a transmission line or a co-axial cable or a wave guide. These are used to transport electromagnetic energy from the transmitter to the antenna or from antenna to the receiver as shown in fig <a href="#fig:fig5" data-reference-type="ref" data-reference="fig:fig5">1.5</a>.A transmission line guides the EM energy from the transmitter to the antenna. The antenna radiates the EM waves. The antenna used to radiate electromagnetic energy at the transmitter is called the Transmitting antenna, while the antenna which receives the</p>
<figure>
<img src="assets/figures/ch1/fig5.png" id="fig:fig5" alt="" /><figcaption>Communication system</figcaption>
</figure>
<p>EM energy that is traversing from transmitter to receiver is called the Receiving antenna. Antenna is a reciprocal device. In addition to radiating or receiving EM waves, an antenna is required to radiate energy in some chosen directions and suppress it in the other directions. Therefore an antenna has to act as a directional device in addition to be a probing device. Antenna is an interface between a circuit and free space. The circuit can be a transmitter or a receiver.</p>
<p>The radiation of electromagnetic energy takes place due to accelerated charge. This can be expressed by the relation</p>
<p><span class="math display">\[\frac{dI}{dt}l \; = \; Q\frac{dv}{dt}\]</span> where <span class="math inline">\(\frac{dI}{dt}\)</span> is the time changing current in ampere/second, <span class="math inline">\(l\)</span> is the length of the current element in meter, <span class="math inline">\(Q\)</span> is the charge in coulomb, <span class="math inline">\(\frac{dv}{dt}\)</span> is the rate of change of velocity (the acceleration of charge in <span class="math inline">\(m/s^2\)</span>).</p>
<p>Thus there will be radiation of energy either due to time changing current or due to accelerated change. For sinusoidal inputs, it is due to current and for pulses it is due to charge. The power is proportional to <span class="math display">\[\left( \frac{dI}{dt} \right)^2 or \left( Q\frac{dv}{dt}\right)^2\]</span></p>
<p>We know that a transmission line guides the electromagnetic energy bounded by the region within the conductors. It travels as transverse electromagnetic waves.</p>
<p>However, an antenna is required to radiate energy rather than guiding the energy. A transmission line can be made to radiate EM energy by flaring it out at the ends. An opened out transmission line converts plane wave to spherical waves and the field associated with them will move forward. Thus an electromagnetic energy is launched into free space by an opened out transmission line. Thus this device is called an antenna or an aerial. The term Antenna is used in the United States and the term aerial is used in the UK and Europe. A transmitting antenna launches a free space wave. This wave can travel over the upper atmosphere above the earth’s surface over longer distances. These traversing EM waves can be intercepted by an antenna at the receiver point and produce a voltage at its terminals which allows flow of current through the receiving apparatus. In summary, an antenna has the function of accepting the energy from the guiding structure (a transmission line) and then radiating the energy into free space in desired directions. This function is done at the transmitting end. However, the same antenna may be used at the Receiver to intercept the EM waves and obtain a power corresponding to the incoming electromagnetic energy. Thus an antenna is a reciprocal device. The process of radiation is illustrated in fig. An antenna is analogous to an eye.</p>
<p>Fig 1.3.2</p>
<p>Antenna interfaces electrons on conductors and photons in space. We know that a field is a region where electric or magnetic forces act. The electric and magnetic fields in free space wave traveling outward at a large distance from an antenna convey energy called Radiation.</p>
<h2 id="near-field-and-far-fields-of-an-antenna">NEAR FIELD AND FAR FIELDS OF AN ANTENNA</h2>
<p>Radio waves are usually referred to as Electromagnetic waves which consist of electric and magnetic fields. Whenever a voltage is applied to an antenna, an electric field will be setup. The voltage causes a current to flow. This in turn produces a magnetic field. The electric and magnetic fields will be at right angles to each other. These fields are emitted from an antenna and travel through the space over very long distances. The direction of propagation is perpendicular to both electric and magnetic fields.</p>
<p>The field due to an antenna responsible for propagation in space over long distance is called the radiation field or far field. There is another field called near field or induction field very close to the antenna element. This is due to the field produced because of the current flowing through the element. This produces a magnetic field in the vicinity of the conductor. This field is stronger near the antenna and hence it is called near field or induction field. The boundary between the near field and the far field is given in terms of the dimensions of the antenna and the wave length of the EM wave. The sketch shown in fig5 indicates the regions of near field and far field of an antenna</p>
<figure>
<img src="assets/figures/ch1/fig7.png" id="fig:fig7" alt="" /><figcaption>Near &amp; Far field of an antenna</figcaption>
</figure>
<p>The space surrounding the antenna is subdivided into three regions as shown in fig <a href="#fig:fig7" data-reference-type="ref" data-reference="fig:fig7">1.6</a> as</p>
<ol>
<li><p>Reactive near field region</p></li>
<li><p>Radiating near field region (Fresnel Zone)</p></li>
<li><p>Far field region (Fraunhoffer Zone)</p></li>
</ol>
<p>There are empirical relations to find the near field and far field regions of an antenna. The boundary between near field and far field is <span class="math display">\[R \; = \; \frac{2D^2}{\lambda}\]</span> where <span class="math inline">\(D\)</span> is the length of the antennas and <span class="math inline">\(\lambda\)</span> is the wave length of the Em wave <span class="math display">\[\lambda \: = \: \frac{c}{f} \:=\: \frac{velocity \: of \: light}{frequency}\]</span></p>
<p>When the point of determination of the field emitted by the antenna is greater than <span class="math inline">\(R\)</span>, i.e., <span class="math inline">\(\left(R\:&gt;\:\frac{2D^2}{\lambda}\right)\)</span> , then that point will be in the far field zone. Hence for radiation field to be present, the distance from the antenna should be greater than <span class="math inline">\(R\:=\:\frac{2D^2}{\lambda} \:metres\)</span>. The field components in the far field region are transverse. For an Antenna the far field is the one that determines the Radiation field.</p>
<p>However the near field region is further subdivided into two as</p>
<ol>
<li><p><em>Reactive near field zone</em> - This is defined as that region of the field immediately surrounding the aerial.</p></li>
<li><p><em>Radiation near field</em> is the region between the far field region and reactive near field region.</p></li>
</ol>
<p>The boundary between the two near field regions is given by</p>
<p><span class="math inline">\(R_1\;=\;0.62\sqrt{\frac{D^3}{\lambda}}\)</span></p>
<p>For an antenna, both the fields exist.</p>
<p><strong>Illustration 1:</strong> Field measurements were made on an antenna of size 50m at a distance of 1km from the antenna. The frequency of the wave is 100MHz. Find whether the point is in the far field region or near field region.</p>
<p><strong>Solution</strong></p>
<p><img src="assets/figures/ch1/fig8.png" alt="image" /> <span id="fig:fig8" label="fig:fig8">[fig:fig8]</span></p>
<p><span class="math display">\[R\;=\;\frac{2D^2}{\lambda}\]</span> <span class="math display">\[D\;\rightarrow\; Size \:of\: the\: antenna\]</span> <span class="math display">\[D\;=\;50m\]</span></p>
<p><span class="math display">\[\lambda\:=\:\frac{c}{f}\:=\:\frac{3\times10^8}{100\times10^6}\;=\;3m\]</span></p>
<p><span class="math display">\[\therefore R\;=\;\frac{2\times50\times50}{3}\;=\;\frac{5000}{3}\;=\;\frac{5}{3}\;=\;1.67km\]</span></p>
<p>The point of measurement is at 1km from the antenna. This is less than R. <span class="math inline">\(\therefore\)</span> The point of determination of field is in the near field zone. Further we can examine whether this point is in the Reactive Near field or Radiating Near field <span class="math display">\[R_1\;=\;0.62\sqrt{\frac{D^3}{\lambda}}\;=\;0.62\sqrt{\frac{50\times50\times50}{3}}\;=\;0.62\sqrt{\frac{125\times10^3}{3}}\]</span> <span class="math display">\[R_1\;=\;0.124km\]</span> <span class="math inline">\(\therefore\)</span> The point is in Radiating near field region.</p>
<p><strong>Illustration 2:</strong> At a distance of <span class="math inline">\(r = 1m\)</span> from a particular short dipole, the induction field component of the total field is equal in strength to the far field. At <span class="math inline">\(r = 10m\)</span> in the same direction which of these is stronger? How much stronger?</p>
<p><strong>Solution:</strong> At the boundary between the near field and the far field of an antenna the two fields are equal i.e., at <span class="math inline">\(R\;=\;\frac{2D^2}{\lambda}\)</span> the two fields are equal at point A. <span> <img src="assets/figures/ch1/fig9.png" alt="image" /> <span id="fig:fig9" label="fig:fig9">[fig:fig9]</span> </span></p>
<p>At <span class="math inline">\(r = 10m\)</span> (point B), this is in the radiation field zone. In the far field zone, the far field component is stronger as it is proportional to <span class="math inline">\(\frac{1}{r}\)</span>, while near field is weaker as it is proportional to <span class="math inline">\(\frac{1}{r^2}\)</span> <span class="math display">\[\frac{E_{far\;field}}{E_{near\;field}}\;=\;\frac{E_0\left(\frac{1}{r}\right)}{E_0\left(\frac{1}{r^2}\right)}\;=\;r\;=\;10\]</span></p>
<p>The far field is ten times stronger.</p>
<h2 id="isotropic-radiator">ISOTROPIC RADIATOR</h2>
<p>An <em>isotropic radiator</em> is a point source of radiation which radiates EM energy equally in all directions. It is something similar to a point source of light which gives out light energy uniformly in all directions as indicated in fig <a href="#fig:fig10" data-reference-type="ref" data-reference="fig:fig10">1.7</a></p>
<figure>
<img src="assets/figures/ch1/fig10.png" id="fig:fig10" alt="" /><figcaption>(a) Point source or isotropic radiator, (b) Point source of light</figcaption>
</figure>
<p>An isotropic radiator is a hypothetical antenna of theoretical interest. It cannot be produced in practice but the concept of isotropic radiator is useful because it provides a theoretical standard to which other practical antennas can be compared. Since an isotropic radiator radiates equally well in all directions, the trace of the electromagnetic field radiated in 3-dimensions will be a spherical pattern. An isotropic antenna is omni-directional. It provides a directivity of unity and is used as reference antenna to specify the directional properly of other practical antennas.</p>
<p>To analyze the field radiated by an antenna we use spherical co-ordinate systems because the radiated field is in 3-dimensions in the space and this system of coordinates is best suited in analyzing the radiation fields due to an antenna. To find the field radiated by an isotropic radiator we use this co-ordinate system and is as shown in fig <a href="#fig:fig10" data-reference-type="ref" data-reference="fig:fig10">1.7</a>. The point source of radiator is located at the origin of spherical co-ordinate system. The XY co-ordinate represents the <span class="math inline">\(\phi\)</span>-plane which is called Azimuth plane and <span class="math inline">\(\phi\)</span> is called the azimuth angle. YZ plane encompasses <span class="math inline">\(\theta\)</span> co-ordinate and it is called elevation plane. The radial distance represents the r co-ordinate</p>
<p>The elemental area <span class="math inline">\(da = r^2\;\sin\theta\;d\theta\; d\phi\)</span></p>
<p>Fig 1.5.2</p>
<p>Fig 1.5.3</p>
<p><strong>To find the power radiated by an isotrope</strong></p>
<p>We use the Poynting theorem to find the power radiated by a source. The Poynting vector represents the power per unit cross-sectional area, and is given by</p>
<p><span class="math inline">\(\vec{P}\;=\;\vec{E}\times\;\vec{H}\)</span></p>
<p><span class="math inline">\(E\)</span> is the electric field in <span class="math inline">\(V/m\)</span> and</p>
<p><span class="math inline">\(H\)</span> is magnetic field intensity in <span class="math inline">\(A/m\)</span>.</p>
<p>The direction of power flow will be in perpendicular plane containing both E &amp; H vectors. Since E is in V/m and H is in A/m, the magnitude of the Poynting vector <span class="math inline">\(|P| = P_r = |E| |H| \sin\theta = EH\)</span> will be in W/m2. The total power radiated by the isotropic radiator through a spherical surface of radius ‘r’ is evaluated using the surface Integral <span class="math display">\[W = \iint P_r\; da\]</span> where W is the total power radiated in watt</p>
<p><span class="math inline">\(P_r\)</span> is the power density in <span class="math inline">\(W/m^2\)</span></p>
<p><span class="math inline">\(da\)</span> is the elemental area <span class="math inline">\(= r^2 \sin\theta d\theta d\phi\)</span></p>
<p>For an isotropic source, the power density at any fixed radius r is constant</p>
<p><span class="math inline">\(\therefore P_r \left(\theta,\phi\right)= constant\)</span></p>
<p>This is because the isotropic radiator radiates energy equally well in all directions.</p>
<p>Power radiated, <span class="math inline">\(W =  \iint P_r da\)</span> <span class="math display">\[= P_r \iint da\]</span> <span class="math display">\[W = P_r \int_{\phi=0}^{2\pi} \int_{\theta=0}^{\pi} r^2 \sin\theta \; d\theta \; d\phi\]</span> <span class="math display">\[= \;P_r\:r^2\:\left(2\pi\right)\int_{\theta=0}^{\pi}\sin\theta\:d\theta\]</span> <span class="math display">\[W\;=\;2\pi P_r r^2 \left[ - \cos\theta\right]^\pi \sigma = 4\pi r^2 P_r\]</span> <span class="math display">\[\therefore P_r = \frac{W}{4\pi r^2}\]</span></p>
<p><span class="math inline">\(4\pi r^2\)</span> is the area of the sphere of radius r</p>
<p>Also <span class="math inline">\(P_r = EH\)</span> and <span class="math inline">\(\frac{E}{H} = \sqrt{\frac{\mu}{\epsilon}} = \sqrt{\frac{\mu_0}{\epsilon_0}} \left(3\right)\)</span></p>
<p>The ratio, <span class="math inline">\(\frac{E}{H}\)</span> has the dimensions of impedance and is the impedance offered to the passing electromagnetic wave in free space denoted by <span class="math inline">\(Z_0\)</span>. This is called intrinsic impedance of free space.</p>
<p><span class="math display">\[Z_0 = \sqrt{\frac{\mu_0}{\epsilon_0}} = 120\pi = 377\Omega\]</span> <span class="math display">\[Z_0 = \frac{E}{H} = 120\pi \quad or \quad H = \frac{E}{120\pi} \left(3\right)\]</span> <span class="math display">\[\therefore P_r = EH = E \cdot \frac{E}{120\pi} = \frac{E^2}{120\pi} \left(4\right)\]</span></p>
<p>Since <span class="math inline">\(\left(3\right) and \left(4\right)\)</span> are identical</p>
<p><span class="math display">\[\frac{W}{4\pi r^2} = \frac{E^2}{120\pi} \quad \left(5\right)\]</span> <span class="math display">\[E^2 = \frac{W\times 120\pi}{4\pi r^2} = \frac{30W}{r^2}\]</span> <span class="math display">\[E = \frac{\sqrt{30W}}{r} \quad  \left(6\right)\]</span></p>
<p>The radiation pattern of an isotropic antenna is a plot of the far field Electric field strength or power density as a function of spatial co-ordinates. This is a spherical pattern in 3-dimensions for an isotropic radiator. In any of the planes; XY or YZ planes - the pattern is a circular one. <span class="math inline">\(E\left(r,\theta,\phi\right)\)</span> or <span class="math inline">\(P_r\left(\theta,\phi,\phi\right)\)</span> is a sphere of radius r and at a given radius <span class="math inline">\(E\left(\theta,\phi\right)\)</span> or <span class="math inline">\(P_r\left(\theta,\phi\right)\)</span> is a constant with respect to either <span class="math inline">\(\theta or \phi\)</span>.</p>
<figure>
<img src="assets/figures/ch1/fig11.png" id="fig:fig11" alt="" /><figcaption>(a) Radiation pattern in 3-D for an istrope, (b) Radiation Pattern in 2-D for istrope.</figcaption>
</figure>
<p>Because an isotropic radiator is omni directional, we take the directivity as unity. But all practical antennas are directional antennas. They radiate more energy in some directions and very little energy in other directions. They are called anisotropic antennas.</p>
<p><strong>Illustration 3:</strong> An isotropic antenna radiates equally in all directions. Total power delivered to an antenna is 100kW. Calculate the power density at 100m, 1km, 100km and 1000km and plot the power density as a function of distance.</p>
<p><strong>Solution:</strong> W= 100kW <span class="math inline">\(r_1 = 100m, r_2 = 1km, r_3 = 100km, r_4 = 103km\)</span></p>
<p>Power density, <span class="math inline">\(P_r\)</span></p>
<p><span class="math display">\[P_r = \frac{W}{4\pi r^2}\]</span> <span class="math display">\[P_{r_1} = \frac{100 \times 10^3}{4\pi \times \left(100\right)^2} = \frac{10}{4\pi} = 0.8\frac{W}{m^2} = 800m \frac{W}{m^2}\]</span></p>
<p><span> <img src="assets/figures/ch1/fig12.png" alt="image" /> <span id="fig:fig12" label="fig:fig12">[fig:fig12]</span> </span></p>
<p><span class="math display">\[P_{r_2} = \frac{100 \times 10^3}{4\pi \times \left(10^3\right)^2} = 0.08 \frac{W}{m^2} = 80m \frac{W}{m^2}\]</span> <span class="math display">\[P_{r_3} = \frac{100 \times 10^3}{4\pi \times \left(100 \times 10^3\right)^2} = 0.8m \frac{W}{m^2}\]</span> <span class="math display">\[P_{r_4} = \frac{100 \times 10^3}{4\pi \times \left(10^3 \times 10^3\right)^2} = 0.008m \frac{W}{m^2}\]</span></p>
<p><strong>Illustration 4:</strong></p>
<p>A wave propagating in free space is at point 20km from its source (assumed to be point source) and the power density is 5 W/m2. What is the power density at 30km distance? Also find electric field at this distance.</p>
<p><strong>Solution:</strong></p>
<p><span class="math display">\[P_{r_1} = \frac{W}{4 \pi r^2} or W = P_{r_1} 4 \pi r_1^2\]</span></p>
<p><span> <img src="assets/figures/ch1/fig13.png" alt="image" /> <span id="fig:fig13" label="fig:fig13">[fig:fig13]</span> </span></p>
<p><span class="math display">\[W = 2 \times 10^-5 \times 4 \pi \times \left(20 \times 10^3\right)^2\]</span> <span class="math display">\[W = 1009.8 watt = 1.0098 kW\]</span> <span class="math display">\[P_{r_2} = \frac{W}{4\pi r_2^2} = \frac{1.0098 \times 10^3}{4\pi \times \left(30 \times 10^3\right)^2}\]</span> <span class="math display">\[= \frac{1}{3600\pi \times 10^3}\]</span> <span class="math display">\[P_{r_2} = 8.846 \times 10^-5 m\frac{W}{m^2}\]</span> <span class="math display">\[E = \frac{\sqrt{30W}}{r_2} = \frac{\sqrt{30 \times 1 \times 10^3}}{30 \times 10^3} = 0.57 \times 10^-3 \frac{V}{m}\]</span> W = 1009.8 watt = 1.0098 kW</p>
<p><strong>Illustration 5:</strong> An isotropic radiator radiates 1kW. Find the electric field intensity at a distance of 20km from the isotropic radiator. Find also the power density at this point</p>
<p><span class="math display">\[E = \frac{\sqrt{30W}}{r} = \frac{\sqrt{30 \times 1 \times 10^3}}{20 \times 10^3} = 8.66m \frac{V}{m}\]</span> <span class="math display">\[P_r = \frac{W}{4 \pi r^2} = \frac{10^3}{4 \pi \times \left(20 \times 10^3\right)^2}\]</span></p>
<h2 id="retarded-potentials">Retarded Potentials</h2>
<p>Consider a radiator located at a point with a current <span class="math inline">\(I = I_0 \cos\omega t\)</span></p>
<figure>
<img src="assets/figures/ch1/fig14.png" id="fig:fig14" alt="" /><figcaption>Retarded current</figcaption>
</figure>
<p>If the velocity of propagation of EM energy is infinite, we would experience the current at a distance r at the point P instantaneously. Due to the finite velocity of the EM waves, the effect of current is not felt instantaneously at point P, but only after a time delay <span class="math inline">\(\tau = \frac{r}{C}\)</span> where r is the distance from origin to point P and C is the velocity of light. Thus, if the time of propagation <span class="math inline">\(\tau = \frac{r}{C}\)</span> , then the current at point P at a distance of r is <span class="math display">\[I = I_0 \cos \omega\left(t - \frac{r}{c}\right)\]</span> <span class="math display">\[I = I_0 \cos \left(\omega t - \beta r\right) \quad \left(2\right)\]</span> <span class="math display">\[where \beta = \frac{\omega}{c} = \frac{2 \pi f}{c} = \frac{2\pi}{\left(\frac{c}{f}\right)} = \frac{2\pi}{\lambda}\]</span> and is called phase shift constant.</p>
<p>The retarded current <span class="math inline">\(I = I_0 \cos\left(\omega t - \beta r\right)\)</span> shows that the phase of the wave is retarded at point P. This represents a spherical wave traveling in the radial direction. The spherical wave suffers larger attenuation because it expands over a larger region as it propagates. Similarly the retarded current density is given by <span class="math inline">\(J = J_0 e^{j\left(\omega t - \beta r\right)}j\)</span>. The corresponding retarded vector magnetic potential is given by <span class="math display">\[A = \frac{\mu_0}{4\pi}\iiint\frac{J}{v}dv \quad \left(3\right)\]</span> <span class="math display">\[A = \frac{\mu_0}{4\pi}\iiint\frac{J_0 e^{j\left(\omega t - \beta r\right)}}{r} dv \frac{Wb}{m} \quad \left(4\right)\]</span></p>
<p>In the same way the retarded scalar potential is given by <span class="math display">\[V = \frac{1}{4\pi\epsilon_0}\iiint\frac{\rho_0 e^{j\left(\omega t - \beta r\right)}}{r}\]</span></p>
<p>where <span class="math inline">\(\rho\)</span> is the charge density in <span class="math inline">\(\frac{C}{m^3}\)</span> and <span class="math inline">\(\rho = \rho_0 e^{j\left(\omega t - \beta r\right)}\)</span></p>
<h2 id="hertzian-dipoles">Hertzian Dipoles</h2>
<p>Another simple antenna is a Hertzian dipole or a Doublet or an elementary dipole. It is a very short length of wire in which the current, I, is uniform over the entire length of the element. An alternating current element of infinitesimally small length, l, and carrying a uniform current I = I0 ejt is one of the basic antennas. An isolated current element is shown in fig <a href="#fig:fig15" data-reference-type="ref" data-reference="fig:fig15">1.10</a></p>
<figure>
<img src="assets/figures/ch1/fig15.png" id="fig:fig15" alt="" /><figcaption>Current element or a doublet</figcaption>
</figure>
<p>The alternating charges of opposite polarity +q and -q are separated by distance l and hence it is called a dipole. The accumulated charges at the ends of the dipole produce fields - both near &amp; far. We use Maxwell’s equations to obtain the field due to a Hertzian dipole. In analyzing the fields due to an antenna operating at high frequencies, we have to consider two important modifications:</p>
<ol>
<li><p>Firstly, the alternating currents of such fields produce electric fields and Displacement currents that in turn will produce magnetic fields.</p></li>
<li><p>Secondly, Due to finite velocity of EM waves, the charges occurring very close to the dipole are observed at a distance ‘r’ after a time delay of <span class="math inline">\(\frac{r}{c}\)</span> but not instantaneously. That is, we have to take the retarded potentials into account.</p></li>
</ol>
<p>Though the Hertzian dipole is a conceptual antenna, the practical wire radiators can be analyzed easily treating them as consisting of several Hertzian dipoles connected in series.</p>
<h2 id="field-due-to-a-hertzian-dipole-or-short-dipole">FIELD DUE TO A HERTZIAN DIPOLE (OR SHORT DIPOLE)</h2>
<p>Let the dipole be a thin conductor of length l <span class="math inline">\(\left(l &lt;&lt; \lambda\right)\)</span> and carrying a uniform alternating current <span class="math inline">\(l = l_0 e^{j\omega t}\)</span> we use spherical co-ordinate system <span class="math inline">\(\left(r,\theta,\phi\right)\)</span>. The dipole is located at the origin of the co-ordinate system oriented along the z-direction as shown in fig1-9.</p>
<p>Fig 1.8.1</p>
<p>We are determining the Electric field at a point P. The electric and magnetic fields are produced when alternating current is fed to a dipole. These disturbances travel away from it in free space. Since it is 3-dimensions, there will be three field components at point P:</p>
<ol>
<li><p>The radial component <span class="math inline">\(E_r\)</span></p></li>
<li><p>The <span class="math inline">\(\theta\)</span> component <span class="math inline">\(E_\theta\)</span></p></li>
<li><p>The <span class="math inline">\(\phi\)</span> component <span class="math inline">\(E_\phi\)</span></p></li>
</ol>
<p>The total field at a point P is given by <span class="math display">\[E = -\left(\nabla V + \frac{\partial A}{\partial t}\right) \quad \left(1\right)\]</span></p>
<p>where V is the scalar potential and A is the vector magnetic potential.</p>
<p>We have to first find V &amp; A for a dipole and use them in equation(1) to evaluate the total field. The magnetic field H at point P is given by <span class="math display">\[H = \frac{1}{\mu_0}\nabla \times A \quad \left(2\right)\]</span></p>
<p><strong>Calculation of Scalar potential V:</strong></p>
<p>Two equal and opposite charges q &amp; -q are separated by a small distance l in free space. <span class="math display">\[V = \frac{q}{4\pi \epsilon_0 s_1} - \frac{q}{4 \pi \epsilon_0 s_2} \quad \left(3\right)\]</span> <span class="math display">\[V = \frac{q_0 e^{j\left(\omega t - \beta r_1\right)}}{4\pi \epsilon_0 s_1} - \frac{q_0 e^{j\left(\omega t - \beta r_2\right)} }{s_2} \quad \left(4\right)\]</span></p>
<p>where <span class="math inline">\(q_0 \rightarrow\)</span> peak value of the charge at ends of dipole <span class="math inline">\(s_1  \rightarrow\)</span> is the distance from upper end of dipole <span class="math inline">\(s_2 \rightarrow\)</span> is the distance from lower end of dipole.</p>
<p>We also know that rate of change of charge is the current, i.e., <span class="math inline">\(\frac{dq}{dt} = I\)</span> <span class="math display">\[or q = \int Idt = \int I_0 e^{j \omega t} dt\]</span> <span class="math display">\[= \frac{I_0 e^{j \omega t}  }{j\omega} = \frac{I}{j\omega} \quad \left(5\right)\]</span> <span class="math display">\[V = \frac{I_0}{4\pi \epsilon_0 j \omega} \left[\frac{e^{j\left(\omega t - \beta r_1\right)}}{s_1} - \frac{e^{j\left(\omega t - \beta r_2\right)}}{s_2}\right] \quad \left(6\right)\]</span></p>
<p>Next step is to express <span class="math inline">\(s_1\)</span> &amp; <span class="math inline">\(s_2\)</span> interns of r and l. From fig 1-9-1 we have <span class="math display">\[\begin{rcases*}
 s_1 = r - \frac{1}{2} \cos \theta \;\;and \\
 s_2 = r + \frac{1}{2}\cos\theta
 \end{rcases*} \quad \left(7\right)\]</span></p>
<p>Fig 1.8.2 Relation between <span class="math inline">\(r, s_1 and s_2\)</span></p>
<p>Substituting for <span class="math inline">\(s_1\)</span> &amp; <span class="math inline">\(s_2\)</span> in (6) we get, <span class="math display">\[V = \frac{I_0}{4\pi \epsilon_0 j \omega} \Bigg\{\frac{e^{j\left[\omega t - \beta\left(r - \frac{l}{2}\cos\theta\right)\right] } }{r - \frac{l}{2}\cos\theta} - \frac{e^{j\left[\omega t - \beta\left(r + \frac{l}{2}\cos\theta\right)\right] }}{r + \frac{l}{2}\cos\theta}\Bigg \}\]</span> <span class="math display">\[V = \frac{I_0}{4\pi \epsilon_0 j \omega}e^{j\left(\omega t - \beta r\right)}\Bigg\{ \frac{e^{j\beta\frac{l}{2}\cos\theta}}{r - \frac{l}{2}\cos\theta} - \frac{e^{-j\beta\frac{l}{2}\cos\theta} }{r + \frac{l}{2}\cos\theta}\Bigg\}\]</span> <span class="math display">\[V = \frac{I_0}{4\pi \epsilon_0 j \omega}e^{j\left(\omega t - \beta r\right)}\Bigg\{\frac{\left(r + \frac{l}{2}\cos\theta\right)e^{j\beta\frac{l}{2}\cos\theta} - \left(r - \frac{l}{2}\cos\theta\right)e^{-j\beta\frac{l}{2}\cos\theta}}{r^2 - \left(\frac{l}{2}\right)^2\cos^2\theta}\Bigg\}\]</span> <span class="math display">\[\begin{split}
  V = \frac{I_0}{4\pi \epsilon_0 j \omega}e^{j\left(\omega t - \beta r\right)}\Bigg\{\left(r + \frac{l}{2}\cos\theta\right)\cos\left[\frac{\beta l}{2}\cos\theta\right] + j\sin\left[\frac{\beta l}{2}\cos\theta\right] \\
 - \left(r - \frac{l}{2}\cos\theta\right)\cos\left[\frac{\beta l}{2}\cos\theta\right] - j\sin\left[\frac{\beta l}{2}\cos\theta\right]\Bigg\}
 \end{split}\]</span></p>
<p>Since <span class="math inline">\(l&lt;&lt; \lambda\)</span> and <span class="math inline">\(r&gt;&gt;l\)</span> <span class="math display">\[r^2 - \frac{1}{2}^2\cos^2\theta = r^2\]</span> <span class="math display">\[\cos\left(\frac{\beta l}{2}\cos\theta\right) = 1\]</span> <span class="math display">\[\sin\left(\frac{\beta l}{2}\cos\theta\right) = \frac{\beta l}{2}\cos\theta\]</span></p>
<p>Thus</p>
<p><span class="math display">\[\begin{split}
V = \frac{I_0 e^{j\left(\omega t - \beta r\right)}}{4\pi \epsilon_0 j\omega r^2}\left[\left(r+\frac{l}{2}\cos\theta\right)\Bigg\{1+j\frac{\beta l}{2}\cos\theta\Bigg\}  \right. \\
\left. - \left(r = \frac{l}{2}\cos\theta\right)\Bigg\{1 - j\frac{\beta l}{2}\cos\theta \Bigg\}\right]
\end{split}\]</span></p>
<p><span class="math display">\[\begin{split}
 V = \frac{I_0 e^{j\left(\omega t - \beta r\right)}}{4\pi \epsilon_0 j\omega r^2}\left[ r + \frac{l}{2}\cos\theta + jr\frac{\beta l}{2} \cos\theta + \frac{l}{2}\cos\theta + j\frac{\beta l}{2}\cos\theta \right. \\
\left. -r + rj\frac{\beta l}{2}\cos\theta + \frac{l}{2}\cos\theta - j\frac{\beta l}{2}\cos\theta - \frac{l}{2}\cos\theta\right]
 \end{split}\]</span> <span class="math display">\[V = \frac{I_0}{4\pi\epsilon_0j\omega r^2}\left[l\cos\theta + rj\beta l\cos\theta\right]e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[= \frac{I_0 l\cos\theta}{4\pi\epsilon_0} \left[ \frac{1}{j\omega r^2} + \frac{\beta}{\omega r}\right] e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[V = \frac{I_0}{4\pi \epsilon_0} l\cos\theta \left[\frac{1}{j\omega r^2} + \frac{1}{rc} \right] e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[V = \frac{I_0 l \cos\theta}{4\pi \epsilon_0 c}\left[\frac{1}{r | \frac{c}{j\omega} \cdot \frac{1}{r^2}}\right]\]</span></p>
<p>we know</p>
<p><span class="math display">\[E = - \nabla V - \frac{\partial A}{\partial t}\]</span> <span class="math display">\[E = \hat{r} E_r + \hat{\theta} E_\theta + \hat{\phi} E_\phi\]</span></p>
<p>Also</p>
<p><span class="math display">\[\begin{rcases}
   E_r = \frac{\partial v}{\partial r} \\
   E_\theta = \frac{1}{r} \frac{\partial v}{\partial \theta} \\
   E_\phi = \frac{1}{r\sin\theta} \frac{\partial v}{\partial \phi}
   \end{rcases}\]</span></p>
<p><span class="math display">\[\therefore \nabla V = \hat{r} \; \frac{\partial v}{\partial r} + \hat{\theta} \frac{1}{r} \frac{\partial v}{\partial \theta} + \hat{\phi} \frac{1}{r\sin\theta} \frac{\partial v}{\partial \phi}\]</span> Since V is a function of only <span class="math inline">\(\theta\)</span> &amp; r and is independent of <span class="math inline">\(\phi\)</span>,</p>
<p><span class="math display">\[\therefore E_\phi = 0\]</span></p>
<p>We have,</p>
<p><span class="math display">\[A = \hat{r} A_r + \hat{\theta} A_\theta + \hat{\phi} A_\phi\]</span></p>
<p>Since the current is along the z-direction Az component is present and therefore <span class="math inline">\(A_\phi = 0\)</span> <span class="math display">\[\therefore A_r = A_Z \cos \theta and A_\theta = - A_Z \sin \theta\]</span></p>
<p><span class="math inline">\(\therefore\)</span> Total radial component,</p>
<p><span class="math display">\[E_{rt} = -j\omega A_r - \frac{\partial v}{\partial r} = -j \omega A_Z \cos\theta - \frac{\partial v}{\partial r}\]</span></p>
<p>Total <span class="math inline">\(\theta\)</span> component,</p>
<p><span class="math display">\[E_{\theta t} = - j \omega A \theta - \frac{1}{r} \frac{\partial v}{\partial \theta} = j\omega A_Z \sin \theta - \frac{1}{r} \frac{\partial v}{\partial \theta}\]</span></p>
<p>Total <span class="math inline">\(\phi\)</span> component,</p>
<p><span class="math display">\[E_{\phi t} = -j\omega A_\phi - \frac{1}{r\sin\theta} \frac{\partial v}{\partial \theta} = 0\]</span></p>
<p><span class="math display">\[E_{rt} = -j\omega A_Z \cos\theta - \frac{\partial v}{\partial r}\]</span></p>
<p><span class="math display">\[\begin{split}
 But \quad \frac{\partial v}{\partial r} = \frac{I_0 l \cos\theta}{4\pi\epsilon_0 c} \left[ \frac{1}{r} + \frac{1}{r^2} \frac{c}{j\omega} \left(-\frac{j\omega}{c}\right)e^{j\omega \left( \frac{t-r}{c}\right)} \right. \\
 \left. + e^{j\omega \left(\frac{t-r}{c}\right)} \left( - \frac{1}{r^2} - \frac{2c}{j\omega r^3}\right) \right]
 \end{split}\]</span></p>
<p><span class="math display">\[\frac{\partial v}{\partial r} = \frac{I_0 l \cos \theta}{4\pi\epsilon_0 } \left[ - \frac{j\omega}{c^2 r} - \frac{1}{cr^2} - \frac{1}{cr^2} - \frac{2}{j\omega r^3}\right] e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[\frac{\partial v}{\partial r} = \frac{I_0 l \cos \theta }{4 \pi \epsilon_0} \left[ - \frac{j\omega}{c^2 r} - \frac{2}{c r^2} - \frac{2}{j\omega r^3}  \right] e^{j\left(\omega t - \beta r\right)}\]</span></p>
<p>The vector magnetic potential, is <span class="math display">\[A = \frac{\mu_0}{4\pi} \iiint\frac{J_0}{r} e^{j\left(\omega t - \beta r\right)} dv\]</span></p>
<p>The double integration of the current density <span class="math inline">\(J_0\)</span> over the surface gives the total current <span class="math inline">\(I_0\)</span>. Then, the <span class="math inline">\(A_Z\)</span> component of vector potential</p>
<p><span class="math display">\[A_Z = \frac{\mu_0 I_0}{4\pi} \int_{-\frac{l}{2}}^{\frac{1}{2}} \frac{e^{j\left(\omega t - \beta r\right)}}{r} dZ\]</span> <span class="math display">\[A_Z = \frac{\mu_0 I_0 l}{4\pi r} e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[A_Z = \frac{\mu_0 C I_0 l}{4\pi cr} e^{j\left(\omega t - \beta r\right)}\]</span></p>
<p>But, <span class="math display">\[\mu_0 c = \frac{1}{\epsilon_0 c}\]</span> <span class="math display">\[\therefore A_Z = \frac{I_0 l}{4\pi \epsilon_0 c \cdot cr} e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[A_Z = \frac{I_0 l}{4\pi \epsilon_0} \cdot \frac{1}{c^2 r} \cos \theta e^{j\left(\omega t - \beta r\right)} - \frac{\partial v}{\partial r}\]</span> <span class="math display">\[\therefore E_{rt} = -j \omega \frac{I_0 l}{4\pi \epsilon_0} \cdot \frac{1}{c^2 r} \cos \theta e^{j\left(\omega t - \beta r \right)} - \frac{\partial v }{\partial r}\]</span> <span class="math display">\[\begin{split}
 E_{rt} = - \frac{j\omega I_0 l}{e\pi \epsilon_0} \cdot \frac{1}{c^2 r} \cos \theta e^{j\left(\omega t - \beta r\right)} \\
  + \frac{I_0 l \cos \theta}{4 \pi \epsilon_0} \left[\frac{j\omega }{c^2 r} + \frac{2}{cr^2} + \frac{2}{j\omega r^3}\right]e^{j\left(\omega t - \beta r\right)}
 \end{split}\]</span> <span class="math display">\[E_{rt} = \frac{I_0 l \cos \theta}{4\pi \epsilon_0}\left[\frac{2}{cr^2} + \frac{2}{j\omega r^3}\right]e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[E_{rt} = \frac{I_0 l \cos \theta}{2\pi \epsilon_0}\left[\frac{1}{cr^2} + \frac{1}{j\omega r^3}\right]e^{j\left(\omega t - \beta r\right)}\]</span></p>
<p>The radial component of the electric field has components proportional to <span class="math inline">\(\frac{1}{r^2} , \frac{1}{r^3}\)</span> . Since the distance r from the antenna is much large and it is in radiation field zone, radiation or field contribution due to the radial component is negligible. However, close to the antenna this field is predominant which is the near field of the antenna.</p>
<p>To find the <span class="math inline">\(\theta\)</span>-component of the field: <span class="math display">\[E_{\theta t} = +j\omega A_Z \sin \theta - \frac{1}{r} \frac{\partial v}{\partial \theta}\]</span> <span class="math display">\[E_{\theta t} = \frac{j\omega l I_0 \sin \theta}{4\pi \epsilon_0 c^2 r}e^{j\left(\omega t - \beta r\right)} - \frac{1}{r} \frac{\partial v}{\partial \theta}\]</span> But, <span class="math display">\[\frac{\partial v}{\partial \theta} = - \frac{I_0 l \sin \theta}{4\pi \epsilon_0 c}\left[\frac{1}{r} + \frac{1}{r^2} \frac{C}{j\omega}\right]e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[\therefore  E_{\theta t} = \frac{j\omega l I_0 \sin \theta}{4\pi \epsilon_0 c^2 r}e^{j\left(\omega t - \beta r\right)} + \frac{1}{r} \cdot  \frac{I_0 l \sin \theta}{4\pi \epsilon_0 c}\left[\frac{1}{r} + \frac{1}{r^2} \frac{C}{j\omega}\right]e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[E_{\theta t} = \frac{I_0 l \sin \theta}{4\pi \epsilon_0}\left[\frac{1}{r} \left(\frac{j\omega}{c^2}\right) + \frac{1}{r^2}\left(\frac{1}{c}\right) + \frac{1}{r^3} \cdot \frac{c}{j\omega}\right]e^{j\left(\omega t - \beta r\right)}\]</span></p>
<p>If we examine the above equation, it has terms <span class="math inline">\(\frac{1}{r}, \frac{1}{r^2}, \frac{1}{r^3}\)</span>. The terms containing <span class="math inline">\(\frac{1}{r^2} , \frac{1}{r^3}\)</span> are near field components of the dipole which are negligible. As far as Radiation field or far field is concerned the term containing <span class="math inline">\(\frac{1}{r}\)</span> is significant. This is the one which contributes to the far field of a dipole. In the far field <span class="math inline">\(E_\theta = 0, \quad E_r\)</span> is negligible. Therefore it is the <span class="math inline">\(\theta\)</span> component which is significant and the far field of a Hertzian dipole is given by</p>
<p><span class="math display">\[E_\theta = \frac{j\omega l I_0 \sin \theta}{4\pi \epsilon_0 c^2 r}e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[= \frac{j I_0 \frac{\omega}{c} l  \sin \theta}{4\pi \epsilon_0 c r}e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[= \frac{j I_0 \beta l \sin\theta}{4\pi \left(\frac{1}{120\pi}\right)r}e^{j\left(\omega t - \beta r\right)} \left[\because \frac{1}{\epsilon_0 c} = \sqrt{\frac{\mu_0}{\epsilon_0}} = 120\pi \right]\]</span> <span class="math display">\[= j\frac{120\pi}{4\pi} I_0 \left(\frac{2\pi}{\lambda}  \right) \frac{1}{r} l \sin \theta e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[E_\theta = j\frac{60\pi}{\lambda} I_0 \frac{1}{r} l \sin\theta e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[E_\theta = 60\pi I_0 \frac{l}{\lambda} \frac{1}{r} \sin\theta j e^{j\left(\omega t - \beta r\right)}\]</span> <span class="math display">\[E_\theta = 60\pi \cdot I_0 \cdot \frac{l}{\lambda} \cdot \frac{1}{r} \sin\theta j e^{j\left(\omega t - \beta r\right)} \\
\Bigg\downarrow  \quad \Bigg\downarrow  \quad \Bigg\downarrow  \quad \Bigg\downarrow  \quad \Bigg\downarrow  \quad \Bigg\downarrow  \quad  \\
Constant \quad Current \quad Relative Length \quad Distance \quad Pattern \quad Phase\]</span></p>
<p>The last term in the above equation is phase term. Therefore the far field of the Hertzian or short dipole is given by</p>
<p><span class="math display">\[E_\theta = 60\pi I_0 \frac{l}{\lambda} \frac{1}{r} \sin\theta\]</span></p>
<p>The radiation pattern in the elevation plane is proportional to <span class="math inline">\(\sin\theta\)</span> Therefore the Field pattern in vertical plane will be a inverted figure of eight as shown in fig 1-9-2. It has the maxima, at <span class="math inline">\(\theta = 90^0\)</span>, <span class="math inline">\(E_{\theta max} = 60\pi I_0 \frac{l}{\lambda r} V/m\)</span> and has the minima at <span class="math inline">\(\theta = 0\)</span>.</p>
<figure>
<img src="assets/figures/ch1/fig16.png" id="fig:fig16" alt="" /><figcaption>(a) Pattern in YZ Plane, (b) Pattern in horizontal or azimuth plane</figcaption>
</figure>
<p>The radiation pattern in Azimuth plane (<span class="math inline">\(\phi\)</span>-plane; XY plane) or Horizontal plane is circle as shown in fig 1-9-2(b). However, in 3-dimensions it is a doughnut shaped pattern as shown in fig 1-9-3</p>
<figure>
<img src="assets/figures/ch1/fig17.png" id="fig:fig17" alt="" /><figcaption>3-D Radiation pattern of a dipole</figcaption>
</figure>
<p>The electric &amp; magnetic fields corresponding to a dipole have 3 components <span class="math inline">\(E_r, E_\theta and \phi\)</span>. The field components <span class="math inline">\(E\phi, H_r, H_\theta\)</span> are zero everywhere. Among the three components <span class="math inline">\(E_r\)</span> has only near field, <span class="math inline">\(E_\theta\)</span> &amp; <span class="math inline">\(H_\phi\)</span> have both near field and far field components. At greater distances from the dipole only <span class="math inline">\(E_\theta and H_\phi\)</span> components are present.</p>
<p><span class="math display">\[E_\theta = 60\pi I_0 \frac{l}{\lambda} \cdot \frac{1}{r} \sin \theta j e^{j\left(\omega t - \beta r\right)} and\]</span> <span class="math display">\[H_\phi  = \frac{E_\theta}{120\pi} = \frac{1}{2\pi r} I_0 l \sin\theta j e^{j\left(\omega t - \beta r\right)}\]</span></p>
<p>A dipole is a directional antenna. It radiates maximum amount of energy perpendicular to the antenna axis. Along the dipole, the energy radiated is minimum. In the vertical plane it is a directional one whereas in azimuth it radiates equally in all directions as already pointed out. Hence for broadcast applications, the dipole antenna is well suited.</p>
<p><strong>Illustration 6:</strong></p>
<p>An Elementary dipole has an electrical length of 0.0625 <span class="math inline">\(\lambda\)</span> and carries a current of 2.5A rms. Calculate the field intensity at 50km from the doublet and at an angle of <span class="math inline">\(25_0\)</span> from the main lobe of radiation. <span> <img src="assets/figures/ch1/fig18.png" alt="image" /> <span id="fig:fig18" label="fig:fig18">[fig:fig18]</span> </span> Fig 1.8.5</p>
<p>The Electric field strength in the far field,</p>
<p><span class="math display">\[E_\theta = 60\pi I_0 \frac{l}{\lambda} \cdot \frac{1}{r} \cdot \sin\theta\]</span> <span class="math display">\[I_0 = 2.5 \sqrt{2} = 3.535A\]</span> <span class="math display">\[l = 0.0.625\lambda\]</span> <span class="math display">\[r = 50 \times 10^3 m\]</span> <span class="math display">\[\theta = 90 - 25 = 65^0\]</span> <span class="math display">\[\therefore E_\theta = 60\pi \times 3.535 \times 0.0625 \frac{1}{\lambda} \times \frac{1}{50 \times 10^3} \times \sin 65^0\]</span> <span class="math display">\[E_\theta = 0.755 mV/m\]</span></p>
<p><strong>Illustration 7:</strong></p>
<p>A vertical wire 1m long carries a current of 5A of frequency 3MHZ. Assuming that wire is in free space calculate the strength of the radiated field at a distance of 100km in a direction at right angles to the axis of the wire.</p>
<p><span class="math display">\[f = 3MHz\]</span> <span class="math display">\[\lambda = \frac{c}{f} = \frac{3 \times 10^8 m/s}{3 \times 10^6 Hz} = 100m\]</span></p>
<p>The length of the wire <span class="math inline">\(l = 1m\)</span></p>
<p><span class="math display">\[\frac{1}{\lambda}  = \frac{1}{100} ; \therefore l &lt;&lt; \lambda\]</span></p>
<p><span> <img src="assets/figures/ch1/fig19.png" alt="image" /> <span id="fig:fig19" label="fig:fig19">[fig:fig19]</span> </span></p>
<p>This can be treated as a short dipole antenna and the radiation field is given by,</p>
<p><span class="math display">\[\therefore E_\theta = 60\pi I_0 \frac{l}{\lambda} \frac{1}{r} \sin\theta\]</span> <span class="math display">\[E_\theta = 60\pi \times 5 \times \frac{1}{100} \times \frac{1}{100 \times 10^3} \sin 90^0\]</span> <span class="math display">\[E_\theta = 300 \times \pi \times \frac{1}{100} \times \frac{1}{100 \times 10^3 \times 1}\]</span> <span class="math display">\[E_\theta = 3.14 \times 3 \times 10^{-3} V/m\]</span> <span class="math display">\[E_\theta = 9.42 mV/m\]</span></p>
<p><strong>Illustration 8:</strong> A 10cm long dipole antenna carries a current of 1A at a frequency of 108Hz. It radiates into free space. Find the electric field intensity at a distance of 50km from the antenna in the direction of maximum radiation. Also calculate the power density at this point.</p>
<p>l = 10cm f = 100MHZ r = 50x103 m I = 1 Amp. <span class="math inline">\(E_\theta = ?\)</span> <span class="math inline">\(P_r = ?\)</span></p>
<p><span> <img src="assets/figures/ch1/fig20.png" alt="image" /> <span id="fig:fig20" label="fig:fig20">[fig:fig20]</span> </span></p>
<p><span class="math display">\[\lambda = \frac{c}{f} = \frac{3 \times 10^8}{100 \times 10^6} = 3m\]</span> <span class="math display">\[l &lt;&lt; \lambda\]</span> <span class="math inline">\(\therefore\)</span> It can be approximated to a Hertzian dipole <span class="math display">\[\therefore E_\theta = 60\pi I_0 \frac{l}{\lambda} \frac{1}{r} \sin\theta\]</span></p>
<p>In the direction of Maximum radiation <span class="math inline">\(\theta\)</span> = 900, <span class="math inline">\(\sin90\)</span> = 1</p>
<p><span class="math display">\[E_\theta = 60\pi \times 1 \times \frac{10 \times 10^{-2}}{3} \times \frac{1}{50 \times 10^3} \times 1 V/m\]</span> <span class="math display">\[= \frac{6\pi}{3} \times \frac{1}{50} \times 10^{-3} = \frac{6.28}{5} \times 10^{-4}\]</span> <span class="math display">\[E_\theta = 1.256 \times 10^{-4} v/m\]</span> <span class="math display">\[Power \; density \quad P_r = \frac{E^2_\theta}{120\pi} = \frac{\left(1.256 \times 10^{-4}\right)^2}{120\pi}\]</span> <span class="math display">\[\quad = 4.2 \times 10^{-11} watts/m^2\]</span> <span class="math display">\[\quad = 42 pW\]</span></p>
<h2 id="antenna-properties">ANTENNA PROPERTIES</h2>
<p>We have discussed two conceptual antenna types: the isotropic radiator and the Hertzian dipole and evaluated the field due to them. Before discussing some of the important properties of the antenna, two types of antennas are analyzed. An isotropic antenna radiates equally in all directions giving rise to omni-directional radiation pattern in all the principal planes. However, a Hertzian dipole gives a directional pattern in the vertical plane and omni-directional pattern in the horizontal plane. After having learnt about the two basic antennas, it is felt proper to discuss some of the important parameters that describe the general characteristics of an antenna. In this section we will examine these parameters so as to appreciate the importance of them. The important parameters are</p>
<ol>
<li><p>Polarization</p></li>
<li><p>Radiation pattern</p></li>
<li><p>Directive gain</p></li>
<li><p>Directivity</p></li>
<li><p>Power gain</p></li>
<li><p>Radiation Resistance</p></li>
<li><p>Bean width</p></li>
<li><p>Band width</p></li>
<li><p>Effective Aperture etc.</p></li>
</ol>
<h3 id="polarization">POLARIZATION</h3>
<p>The orientation of the electric and magnetic fields radiated by an antenna with respect to the Earth is called polarization of EM waves. The direction of the electric field specifies the polarization of the antenna. An electromagnetic wave originating from an antenna can be either vertically polarized or horizontally polarized. We know that the electric and magnetic vectors are perpendicular to each other and the direction of propagation is perpendicular to both electric &amp; magnetic vectors.</p>
<p>In vertical polarization, E vector is vertical and this needs vertical antenna to launch it. A vertical dipole can produce this kind of polarization. In horizontal polarization, a horizontal antenna is required to produce horizontally polarized wave. When the electric field radiated is parallel to the earth it gives horizontal polarization. On the other hand, electric field is perpendicular to the earth it gives vertically polarized wave. Some antennas like helical antennas produce circular or elliptical polarization.</p>
<p>It is important to note that, for proper transmission and reception of radio waves, both the transmitting and receiving antennas should be of same type of polarization. Most of the antennas are vertical and they support vertical polarization. However, in Mobile communications where same frequency is used for different cells, two orthogonal polarizations are used. In deep space communication, where the EM wave arriving at the receiver might have changed from one polarization state to the other, it is advisable to use circularly polarized antenna system like a helical antenna.</p>
<h3 id="radiation-pattern">RADIATION PATTERN</h3>
<p>The radiation pattern of an antenna is defined as the graphical representation of the field strength or power density as a function of spatial co-ordinates. The radiation pattern is a 3-dimensional quantity. It is determined in the far field region and is represented as a function of directional co-ordinates. In 3-dimensions, it represents a solid cone of radiation. If the electric field strength is plotted as function of co-ordinate systems, it is called field pattern. While the power density is plotted as function of co-ordinates it is called the Power pattern. As examples: for an isotropic antenna (which radiates power or field equally in all directions), the three dimensional pattern is a sphere at a constant radius. Pr(</p>
<p>For a Hertzian dipole, the 3-dimentional Power pattern is a doughnut shaped pattern</p>
<figure>
<img src="assets/figures/ch1/fig21.png" id="fig:fig21" alt="" /><figcaption>Power pattern for isotropic antenna, (a) 3-D Pattern (b) Power pattern in vertical plane(- plane), (c) Horizontal plane(-plane</figcaption>
</figure>
<p>The power pattern is normally specified in two principal plans. In elevation plane or vertical plane (YZ plane or plane) and Horizontal or Azimuth plane (XY plane or plane). Fig1-10-1 shows the power pattern for an isotropic antenna. The 3-D pattern is a sphere and the pattern in two-principal planes is a circle. Fig 1-10-2 shows the power pattern for a dipole in 3-D and the two principal planes. In 3-D it is doughnut shaped pattern as in Fig 1-10-2(a) and an inverted figure of eight for vertical plane as in fig 1-10-2(b) and a circular or omni-directional pattern in Horizontal plane as in fig 1-10-2(c).</p>
<p>In most of the cases, if we have the patterns in the two principal planes, it is sufficient enough to understand the directional properties of the antenna. The pattern may be omni-directional as in the case of an isotropic antenna and it may be a bi-directional pattern as in the case of a dipole. It can also be a pencil beam having concentration of the radiated energy in one cone of radiation and very little radiation in the other directions as shown in fig 1-10-3. This is for a highly directional antenna.</p>
<figure>
<img src="assets/figures/ch1/fig22.png" id="fig:fig22" alt="" /><figcaption>Power pattern of a dipole, (a) 3-D Pattern, (b) Vertical plane(-plane), (c) Horizontal plane(-plane)</figcaption>
</figure>
<p>Fig(a) shows the 3-dimensional solid cones of radiation for an antenna. This consists of a main lobe and several side lobes. The main lobe of radiation is defined as the radiation lobe containing the direction of maximum radiation. Most of the energy is concentrated in this major lobe for an antenna. This is a solid cone of radiation which accounts for the radiated power in these directions.</p>
<p>A minor lobe or a side lobe is a radiation lobe in any direction other than the main lobe of radiation. A back lobe is a side lobe which is opposite direction to that of the main lobe of radiation. The side lobes represent energy spillover in unwanted directions in the case of transmitting antenna. For a receiving antenna, they may receive unwanted signals from these directions which may cause interference if the level of these is considerable. Therefore, side lobe levels have to be minimized so as to avoid noise and interference from unwanted signals at the receiver. Since the radiation pattern is a solid cone of radiation we use solid angle rather than plane angle. To plot the power pattern we can use power density Pr in W/m2 or Radiation intensity U which represents the power per unit solid angle or W/steradian.</p>
<h3 id="radiation-intensity">RADIATION INTENSITY</h3>
<p>The power per unit solid angle is called Radiation Intensity. It is the power density multiplied by square of the radius and denoted by U. This is a 3-dimentional quantity. <span class="math inline">\(U\left(\theta, \phi\right) = P_r\left(\theta, \phi\right) r^2\)</span> watt/steradian [ Note: watt/steradian = Square radian denoted by <span class="math inline">\(S_r\)</span>] The radiation Intensity is independent of radius. From power theorem, the radiated power, <span class="math display">\[W = \iint P_r \cdot da\]</span> <span class="math display">\[W = \iint P_r \cdot r^2 \sin\theta d\theta d\phi\]</span> <span class="math display">\[W = \iint U \cdot \sin\theta d\theta d\phi\]</span> <span class="math display">\[W = \iint U \cdot d\Omega\]</span></p>
<p>where <span class="math inline">\(d\Omega = \sin\theta d\theta d\phi\)</span> steradian <span class="math inline">\(d\Omega\)</span> is called solid angle. Thus the total power radiated is given by the double integral of the radiation Intensity U over the solid angle <span class="math inline">\(d\Omega\)</span>. For an isotropic antenna, the total power radiated <span class="math display">\[W = \int_{\theta =0}^{\pi} \int_{\phi =0}^{2\pi} P_r \left(\theta, \phi\right) r^2 \sin\theta d\theta d\phi\]</span></p>
<p><img src="assets/figures/ch1/fig23.png" id="fig:fig23" alt="image" /> <span id="fig:fig23" label="fig:fig23">[fig:fig23]</span></p>
<p>For and isotrope <span class="math inline">\(P_r\left(\theta, \phi\right)\)</span> is a constant at a radius r <span class="math inline">\(\therefore P_r\left(\theta, \phi\right)r^2 = U = U_0\)</span> constant</p>
<p><span class="math display">\[\therefore W = \int_{\theta =0}^{\pi} \int_{\phi =0}^{2\pi} U_0 d\Omega = U_0 \iint d\Omega\]</span> <span class="math display">\[\quad = U_0 \int_{\theta =0}^{\pi} \int_{\phi =0}^{2\pi} \sin\theta d\theta d\phi = 2\pi U_0 \int_{\theta =0}^{\pi} \sin\theta d\theta d\phi\]</span> <span class="math display">\[\quad = 2\pi U_0 \left[- \cos\theta\right]^\pi_0 = 2\pi U_0 \cdot 2\]</span> <span class="math display">\[W = 4\pi U_0 watts\]</span></p>
<h3 id="beam-width">BEAM WIDTH</h3>
<figure>
<img src="assets/figures/ch1/fig24.png" id="fig:fig24" alt="" /><figcaption>Beam width of a pattern</figcaption>
</figure>
<p>When the radiated power of an antenna is concentrated in a single major lobe, the angular width of this lobe is the Beam width. We define half power beam width as the angle subtended by the points in the main cone of radiation at which the radiation power has fallen to half its maximum value OR the field strength has fallen to <span class="math inline">\(\frac{1}{\sqrt{2}}\)</span> of its maximum value. This is called Beam width between half power points denoted as BWHP. This is shown in fig 1-10-4 as <span class="math inline">\(\theta_{HP}\)</span>. Another way in which the beam width is specified is in terms of the angle subtended by the main lobe of radiation between the first nulls of the main lobe. Nulls are nothing but the directions of zero radiation - these are the directions of minima. The first nulls occur on either side of the main lobe. The angle subtended by main lobe between the first nulls is called Beam width between First nulls, denoted as BWFN. This is shown in the fig 1-10-4 as <span class="math inline">\(\theta_{FN}\)</span>. If we know the pattern, we can determine easily the first nulls and then the Half Power Beam Width can be found by using an approximate relation. <span class="math display">\[\theta_{HP} = \frac{1}{2} \theta_{FN}\]</span> The beam width of an antenna is another important specification which will indicate how directive the given antenna is. Smaller the beam width larger will be the Directivity.</p>
<p>If an antenna has a narrow beam and it is used for reception, it can be used to determine the direction of signal arrival. For direction finding, narrow beam antennas are used whereas in broadcast applications, wider beam antennas are used.</p>
<p><img src="assets/figures/ch1/fig25.png" id="fig:fig25" alt="image" /> <span id="fig:fig25" label="fig:fig25">[fig:fig25]</span></p>
<p>Consider a dipole antenna whose radiation field, <span class="math inline">\(E_\theta\)</span> <span class="math display">\[E_\theta = 60\pi I_0 \frac{l}{\lambda} \cdot \frac{1}{r} \sin\theta\]</span> Its field pattern is shown below <span class="math display">\[E_{\theta max} = 60\pi I_0 \frac{l}{\lambda r}\]</span> At half power points, <span class="math display">\[E_\theta = \frac{E_{\theta max}}{\sqrt{2}}\]</span> <span class="math display">\[\frac{E_\theta}{E_{\theta max}} = \frac{\left(\frac{60\pi I l}{\lamba r}\sin\theta\right)}{\frac{60\pi I l}{\lambda r}}\]</span> <span class="math display">\[\frac{\frac{E_{\theta max}}{\sqrt{2}}}{E_{\theta max}} = \sin\theta \quad or \quad \sin\theta = \frac{1}{\sqrt{2}}\]</span> <span class="math display">\[\theta = 45_0\]</span></p>
<p>BWHP = 2 (90-45) = 2X45 = <span class="math inline">\(90_0\)</span>. Beam width between First nulls <span class="math inline">\(\theta\)</span> = 0 and <span class="math inline">\(\theta\)</span> = <span class="math inline">\(180_0\)</span> are the nulls of the Pattern. <span class="math inline">\(\therefore  BWFN = 180_0\)</span>.</p>
<h3 id="directivity">DIRECTIVITY</h3>
<p>The directional property of an antenna is expressed by another important characteristic referred to as Directivity. Before giving the definition of Directivity, we would like to define the term Directive gain.</p>
<p>Directive gain of an antenna is defined as the ratio of the power density due to the test antenna in any arbitrary direction to the power density that would be radiated by an isotropic antenna, with both the test antenna and the isotropic antenna radiating the same amount of power. Or alternatively, it can be defined as the ratio of the power radiated by an isotropic antenna to the power that would by radiated by the test antenna so as to keep the power density at the point away from the antenna which is in the far field region. <span class="math display">\[Directive gain =  \frac{Power density of the test antennas}{Power density of the isotropic antenna}\]</span></p>
<p>With same powers being radiated by both. A much more useful quantity, which has a unique value for a given antenna, is called the Directivity. Directivity is determined in the direction of maximum radiation direction. Therefore this is the maximum directive gain.</p>
<p>It can be defined as the ratio of the power density of the test antenna oriented in a direction to get maximum response to the power density due to the isotropic antenna when both antennas are radiating the same amount of power. It is to be noted that we are defining the directivity taking the reference antenna to be isotropic radiator which is an omni-directional antenna having the Directivity to be unity. Since the isotropic antenna radiates EM energy in all directions equally (non-directional), the power density <span class="math inline">\(P_{ri} = \frac{W}{4\pi r^2}\)</span> will be always smaller compared to the actual test antenna which is a directional antenna. For the same power radiated, the power density due to a test antenna <span class="math inline">\(P_{ra} = \frac{E^2_\theta}{120\pi}\)</span> where <span class="math inline">\(E_\theta\)</span> is the electric field intensity due to the actual antenna at the point in free space with antenna oriented for maximum response.</p>
<p>Since the actual test antenna is oriented in the direction of maximum radiation, the power density, <span class="math inline">\(P_ra\)</span>, will be maximum.</p>
<p>The power density due to the isotropic radiator, <span class="math inline">\(P_ri\)</span>, will be the average power density. Therefore we can also define the directivity as the ratio of Maximum power density to the average power density. Since the radiation intensity <span class="math inline">\(U = P_r r^2\)</span>, we can write the <span class="math display">\[Directivity, \quad D = \frac{P_{rm} r62}{P_{ri} r^2} = \frac{U_m}{U_0}\]</span> <span class="math display">\[D = \frac{Maximum Radiation Intensity}{Average Radiation Intensity}\]</span></p>
<p>The Directivity of a source can be evaluated if we know the radiation power pattern.</p>
<p><span class="math display">\[D = \frac{U_m \left(\theta, \phi\right)}{U_{av}} = \frac{U_m \left(\theta, \phi\right)}{U_0}\]</span> <span class="math display">\[D = \frac{U_m \left(\theta, \phi\right)}{\frac{1}{4\pi} \iint U d\Omega} = \frac{1}{\frac{1}{4\pi}\iint\frac{U}{U_m \left(\theta, \phi\right)}d\Omega}\]</span></p>
<p><img src="assets/figures/ch1/fig26.png" id="fig:fig26" alt="image" /> <span id="fig:fig26" label="fig:fig26">[fig:fig26]</span></p>
<p>Fig 1.9.5</p>
<p><span class="math display">\[\Omega_A = \iint \frac{U}{U_m\left(\theta, \phi\right) d\Omega}\]</span></p>
<p>is called the beam area or beam solid angle <span class="math display">\[D = \frac{4\pi}{\Omega_A}\]</span></p>
<p><span class="math inline">\(\Omega_A\)</span> can be expressed in terms of the Half Power Beam Widths in two Principal planes. If <span class="math inline">\(\theta_{HP}\)</span> is the half power beam width in vertical plane and <span class="math inline">\(\phi_{HP}\)</span> is the half power beam width in Horizontal plane, then,</p>
<p><span class="math display">\[\Omega_A \approx \theta_{HP} \phi_{HP}\]</span> <span class="math display">\[\therefore D = \frac{4\pi}{\theta_{HP} \phi_{HP}}\]</span> <span class="math display">\[\Omega_A = \int_{\theta = 0}^{\pi} \int_{\phi = 0}^{2\pi} \frac{U_0}{U_m\left(\theta, \phi\right)} d\Omega\]</span></p>
<p>for an isotropic radiator</p>
<p><span class="math display">\[U_0 = U_m \left(\theta, \phi\right)\]</span> <span class="math display">\[\therefore \Omega_A = \int_{\theta = 0}^{\pi} \int_{\phi = 0}^{2\pi} \sin\theta d\theta d\phi\]</span> <span class="math display">\[\quad = 2\pi \int_{\theta=0}^{2\pi} \sin\theta d\theta\]</span> <span class="math display">\[\Omega_A = 4\pi\]</span></p>
<p><span class="math inline">\(\therefore\)</span> Directivity for an isotropic radiator, <span class="math display">\[D = \frac{4\pi}{\Omega_A} = \frac{4\pi}{4\pi} = 1\]</span> Thus directivity of an isotrope is equal to unity. An approximate method of finding the Directivity.</p>
<p>But, 4 Steradian = 4 1 rad2 But 1800 = radian 1 radian =</p>
<p>This is the solid angle for sphere. are in degrees.</p>
<h4 id="determination-of-directivity-from-radiation-pattern">DETERMINATION OF DIRECTIVITY FROM RADIATION PATTERN</h4>
<p>We have already shown that the Directivity D is given by . The above relation is obtained when the actual antenna and the reference antenna (isotrope) are radiating the same power. By knowing the radiation pattern of an antenna, we can determine the power radiated by that source using power theorem. Then equate this to the power radiated by the isotropic antenna. Take the ratio of the maximum radiation intensity to average radiation Intensity to get the directivity. The given pattern can be modeled into an expression and then use this to find the power radiated using power theorem. In this section, for a few standard patterns, Directivity will be evaluated and others will be given as exercises.</p>
<p>1.9.5.2 HEMISPHERIC POWER PATTERN</p>
<p>A source radiating over the hemisphere gives a hemispheric pattern shown in fig (a) and (b)</p>
<figure>
<img src="assets/figures/ch1/fig27.png" id="fig:fig27" alt="" /><figcaption>(a) pattern in vertical plane(0 &lt; &lt; /2) (b) comparison with spherical pattern of isotropic antenna ( 0 &lt; &lt; 2 )</figcaption>
</figure>
<p>0</p>
<p>By power theorem, the total power radiated is</p>
<p>Power radiated by isotropic Antenna is W= 4U0 (2) Equating 1 and 2, we get 2Um = 4U0 or . It is an obvious result. The Directivity of hemispheric source is twice that of isotrope.</p>
<h4 id="bidirectional-cosine-power-pattern">BIDIRECTIONAL COSINE POWER PATTERN</h4>
<p>The pattern is given by U = Um cos The bounds for a 0 and 0 =</p>
<figure>
<img src="assets/figures/ch1/fig28.png" id="fig:fig28" alt="" /><figcaption>Near &amp; Far field of an antenna</figcaption>
</figure>
<p>Power radiated by isotropic antenna is 4U0</p>
<p>For a unidirectional cosine power pattern, the Directivity will be 4, as the entire power is concentrated in one side.</p>
<h4 id="sine-power-pattern">SINE POWER PATTERN</h4>
<p>The pattern is given by U = Um Sin</p>
<p><img src="assets/figures/ch1/fig29.png" id="fig:fig29" alt="image" /> <span id="fig:fig29" label="fig:fig29">[fig:fig29]</span></p>
<h4 id="sine-squared-pattern">SINE SQUARED PATTERN</h4>
<p>For sin squared radiation pattern, U = Um Sin2</p>
<p>Fig 1.9.5.4</p>
<p>This pattern is identical to the power pattern of a short dipole. It has already been shown that the Directivity of a short dipole as 1.5 which can be verified once again. Power radiated by this source,</p>
<p>Power radiated by isotrope is, W= 4U0 (2)</p>
<h4 id="unidirectional-cosine-squared-pattern">UNIDIRECTIONAL COSINE SQUARED PATTERN</h4>
<p>U = Um Cos2 ; 0 /2 and 0 Since it is a unidirectional pattern, it exists over the upper hemisphere</p>
<p>Fig 1.9.5.4</p>
<p>Power radiated by isotrope W = U0 (2)</p>
<p>We can extend this result to show that Directivity for a source with a power pattern defined by U = Um cosn to be equal to i.e. D = 2(n+1).</p>
<p>Problem:</p>
<p>Show that the Directivity for a source with a unidirectional power pattern given by U = Um cosn can be expressed as D = 2(n+1). U has a value only for and is zero elsewhere. Power radiated by isotropic source W = 4U0 (2)</p>
<p><img src="assets/figures/ch1/fig30.png" id="fig:fig30" alt="image" /> <span id="fig:fig30" label="fig:fig30">[fig:fig30]</span></p>
<p>Fig 1.9.5.5</p>
<p>Fig 1.9.5.6</p>
<h4 id="power-pattern-of-asymmetrical-antenna">POWER PATTERN OF ASYMMETRICAL ANTENNA</h4>
<p>We have determined the Directivity of an antenna pattern which are symmetrical about the polar axis. However there are antennas which do not produce a pattern which is not symmetrical.</p>
<p>Consider a source with field pattern given by E = sinsi The limits for and may be specified as 0 and 0 The pattern is shown in fig. The pattern for such an antenna will have = 900 plane coinciding with XY plane = 900 plane with YZ plane The power pattern for the above radiator is given by U= Umsin2.cos2 The figure shows the power pattern</p>
<p><img src="assets/figures/ch1/fig31.png" id="fig:fig31" alt="image" /> <span id="fig:fig31" label="fig:fig31">[fig:fig31]</span></p>
<p>E(, ) = Sin Sin Power density Radiation Intensity U = Pr.r2 = U =</p>
<p>Power radiated by isotrope is W = 0 (2)</p>
<h3 id="power-gain">POWER GAIN</h3>
<p>Power gain, denoted by G, is another important parameter with reference to an antenna. In the definition of Directivity we considered both antennas being radiating the same amount of power. The definition of Directivity does not take into account losses in the antenna. Power gain takes into account losses in the antenna.</p>
<p>Power gain is defined as the ratio of the power density of the actual test antenna to that of the power density due to a lossless isotropic source for the same total input power in the direction of Maximum radiation. Thus, Since the power gain is defined on the basis of same input power, the power density calculated for the actual test antenna takes into account the losses in the antenna. The power gain is related to the Directivity by the relation G = D, where is the efficiency of the antenna.</p>
<p>The Power density or the field strength at the receiving point can be increased by using a transmitting antenna having high power gain without increasing the transmitter power. Hence this relationship has much economic significance.</p>
<h3 id="radiation-resistance">RADIATION RESISTANCE</h3>
<p>Another important property of an antenna is its Radiation resistance which accounts for the power radiated by an antenna. The ratio of the total power radiated to the square of the rms current has the dimensions of resistance and is denoted by Rr and is called Radiation resistance. ohm. where W is the power radiated by an antenna and I0 is the peak current fed to the antenna.</p>
<p>This is not the ohmic resistance of the antenna but an equivalent fictitious resistance used to represent the radiated power. Therefore, Radiation resistance is that value of resistance of an antenna which if replaced by the radiation mechanism would dissipate exactly the same amount of power that the antenna radiated when both are fed with same current. If the radiation resistance is larger, the power radiated also will be larger by a transmitting antenna. On the other hand for a receiving antenna the radiation resistance acts as the terminal impedance and the powered delivered to the load will depend on the radiation resistance and the current produced. Short dipoles have very small radiation resistance while a half-wave dipole has a radiation resistance of 75.</p>
<h3 id="radiation-resistance-of-hertzian-dipole">RADIATION RESISTANCE OF HERTZIAN DIPOLE</h3>
<p>For a Hertzian dipole we can evaluate the Radiation resistance.</p>
<p><img src="assets/figures/ch1/fig32.png" id="fig:fig32" alt="image" /> <span id="fig:fig32" label="fig:fig32">[fig:fig32]</span></p>
<p>The far field of Hz dipole is The peak power radiated by the dipole is</p>
<p>For a short dipole the radiation resistance is proportional to since . The radiation resistance of Hz dipole is very small.</p>
<p><strong>Illustration 9:</strong> As an example find the Radiation Resistance of dipole antenna with l = 0.0625 Since l&lt;&lt;, it is a short dipole.</p>
<p><strong>Illustration 10:</strong> Find the radiation resistance of a short dipole antenna with its length to be l = 10cm operating at 100 MHz fed with a peak current of 2A. Find the radiation resistance and the power radiated. l = 10 cm</p>
<h3 id="antenna-efficiency">ANTENNA EFFICIENCY</h3>
<p>Antenna is made up of metallic structure usually a wire of certain length and diameter. This will have an ohmic resistance, which depends directly on length, and inversely on cross-section. The power input an antenna through a feeder cable will be sum of the power dissipated due to ohmic and other losses and the power radiated. Power input an antenna = Power loss + Power radiated. If Rr is the radiation resistance and Rloss is the loss resistance then the terminal resistance of the antenna of the antenna Rt = Rr + Rloss.</p>
<p><img src="assets/figures/ch1/fig33.png" id="fig:fig33" alt="image" /> <span id="fig:fig33" label="fig:fig33">[fig:fig33]</span></p>
<p>The loss resistance has two components - one is the ohmic resistance of the antenna and the second is the equivalent resistance, which accounts for loss of radiated energy being eaten away be near by conduction structures. Longer the antenna, higher the loss resistance. Therefore low frequency antennas will have more loss resistance. The efficiency of the antenna is defined as the ratio of the power radiated to the input power fed to the antenna i.e.,</p>
<p>If the antenna current is I0 ampere and the antenna radiation Resistance is Rr, then Power radiated , Power input</p>
<p>As already pointed out, Rloss is more for low frequency antennas and hence low frequency antennas will be less efficient compared to high frequency antennas. The efficiency of low frequency antennas ranges from 60 to 90% and for high frequency antennas it approaches 100%. It is to be noted that most of the dipole antennas have resonant length and the impedance at resonance will be resistive and slightly off resonance impedance will have reactance component also. Xa 0 for Resonance Za = Ra j Xa Ra = Rr + Rloss. Where Ra is the antenna resistance consisting of radiation resistance and loss resistance.</p>
<p><strong>Illustration 11:</strong> Find the radiation resistance of short dipole of length . Also calculate the efficiency of the dipole antenna if the loss resistance is 1. Find the power radiated if antenna current is 10A rms. l = Rloss = 1 Rr = ? = ?</p>
<p>Power radiated Wr = I2rms Rr Wr = 102.8 = 800 watts.</p>
<p><strong>Illustration 12:</strong> Estimate the radiation Resistance of a short dipole whose overall length is 0.2m at a frequency of 25 MHz. Derive the formula you would use. l = 0.2 m f = 25 MHz Rr = ?</p>
<p><strong>Illustration 13:</strong> A short dipole was observed to have a radiation resistance of 2at a frequency of 1MHz. Find its length. Given Rr = 2 f = 1MHZ</p>
<p>For a dipole,</p>
<p><strong>Illustration 14:</strong> An antenna radiates isotropically over half a space above a perfectly conducting earth. If E = 50 mV/m (rms) at a distance of 1km, find the (i) Power radiated and (ii) radiation resistance if the antenna current is 3.5A rms.</p>
<p><strong>Solution:</strong> Antenna has hemispheric pattern</p>
<p><span> <img src="assets/figures/ch1/fig34.png" alt="image" /> <span id="fig:fig34" label="fig:fig34">[fig:fig34]</span> </span></p>
<p>(i) Power radiated r = PrArea (Area of half sphere)</p>
<p>(ii) To find radiation resistance Rr</p>
<p>I2 Rr = r</p>
<p><strong>Illustration 15:</strong> An omni-directional (isotropic) antenna has a field pattern given by where I is the current in ampere and r is the distance in m. Find radiation resistance.</p>
<p><strong>Solution:</strong></p>
<p>Power radiated by isotropic Antenna is</p>
<h3 id="effective-length">EFFECTIVE LENGTH</h3>
<p>For a Hertzian dipole, the current distribution is uniform over the entire length of the dipole.</p>
<p>But, antennas of physical length comparable to wavelength of the radiated field are used, the current distribution is no longer uniform. It is observed that for dipoles of length or greater, the current varies linearly from the centre fed point to zero at the ends of the dipole. This has a triangular distribution as shown in fig 1-10. The current distribution for half wave dipole is sinusoidal as shown in fig 1-10-(b). Due to the non-uniform current distribution, the effective length and actual</p>
<figure>
<img src="assets/figures/ch1/fig35.png" id="fig:fig35" alt="" /><figcaption>Current distributions for dipoles (a) Short Dipole (b) /2 dipole</figcaption>
</figure>
<p>Fig 1.9.10.1</p>
<p>length are going to be different.</p>
<p>The effective height is that length over which uniform current produces the same effect as that of a non-uniform field over the actual element. To find the effective height, we find the area under the actual distribution (A) and equate it to the area under the uniform distribution, i.e., A = leff.Io or leff = Area under non-uniform current distribution curve is</p>
<p>Therefore effective length (height) is always smaller than the actual height of the antenna i.e., leff&lt;l. For a triangular distribution,</p>
<p>It is half the physical length for triangular distribution of fig 1-10-(a) For the sinusoidal distribution, area under the actual distribution,</p>
<p>The effect of the effective length being smaller is that the amount of voltage induced in a receiving antenna which is equal to V = E.leff will be reduced slightly. Whereas for a receiving aerial, the radiation resistance will be reduced.</p>
<h3 id="bandwidth">BANDWIDTH</h3>
<p>The bandwidth of an antenna is defined as the range of frequencies over which the antenna characteristics such as the radiation pattern, the input impedance, Directivity, beamwidth, etc. do not vary appreciably but within acceptable limits of those at centre frequency. Usually resonant antenna like dipoles of length have narrow bandwidth. For such antennas, the bandwidth is expressed as a small percentage of the centre frequency about 5% of centre frequency. If the frequency varies beyond this, the input impedance Za = Ra j Xa will change resulting in change of radiation pattern and hence Directivity also changes. Therefore for resonant antennas the bandwidth is narrow.</p>
<p>Whereas non-resonant antennas are usually broad band. The broad band antennas can operate over a wide range of frequencies 2:1 frequency range like Rhombic antenna. There are frequency independent antennas like log periodic aerials which work over a range of 10:1 in frequency range. Therefore there is no unique definition for bandwidth of an antenna. The specifications are set in each case to meet the particular application.</p>
<p><strong>Illustration 16:</strong></p>
<p>Prove that the free space field strength at a distance r metre from the radiating antenna is given by</p>
<p>where w power radiated watts G Gain of the antenna</p>
<p>Solution: Consider an isotropic antenna radiating a total power of W watt in free space. This radiates equally in all directions. But the antenna given has a Power gain of G. The total power radiated Wt = GW watts Power density at a distance r will be due to isotropic antenna will be</p>
<p>But for an antenna with gain of G</p>
<p>Power density evaluated from the Poynting vector. andare identical</p>
<p>(2) For a short dipole show that the Directivity is . The field radiated by dipole is</p>
<p>Power radiated</p>
<p>The power radiated by the isotropic antenna is W = 4U0 (2) Power radiated by test antenna = Power radiated by isotrope</p>
<p>Directivity for a short dipole = 1.5 The Directivity of dipole is 1.5 times that of isotropic antenna.</p>
<p><strong>Illustration 17:</strong> Show that the maximum field strength due to an elementary dipole at a distance from it is given by where W is the power radiated.</p>
<p>Solution:</p>
<p>The field due to an antenna with a power gain G and radiating watts is shown to be (see illustration 1) The Directivity of the Elementary dipole as evaluated in illustration 2 is assuming efficiency of the antenna to be 100</p>
<p><strong>Illustration 18:</strong> An antenna radiates a total power of 100 watt. In the direction of maximum radiation, field strength at a distance of 10km is found to be E = 12mV/m (i) What is the directivity of the antenna assuming free space propagation? (ii) If the efficiency of the antenna is 90</p>
<p>Solution:</p>
<p>Given W = 100 watt. r = 10km = 1103m E=12mV/m = 1210-3 v/m D = ? G = ?</p>
<p>(i) Finding Directivity:</p>
<p>Power density due to the isotropic antenna at point P will be</p>
<p>The power density due to the actual antenna at the point P is</p>
<p>Directivity, for same radiated power when test antenna is oriented for maximum response</p>
<p>(ii) Power gain G = D =</p>
<p><strong>Illustration 19:</strong> A low frequency transmitting antenna has a radiation resistance of 0.5and total loss resistance 2.5. The current fed to the antenna is 100A. Find the radiated power, input power and efficiency.</p>
<p>Solution: Rr = 0.5 Radiated power, Rloss = 2.5 Wr = I2 Rr = (100)2 0.5 I = 100 Amps. = 5000 watt r = ? Wr = 5kw i = ? Power input, = ? Wi = I2 (Rr + Rloss) = 1002 (0.5 + 2.5) = 3 1002 Wi = 30kw</p>
<p><strong>Illustration 20:</strong> An aerial has an effective height of 100m and the current at the base is 450A (rms) at 40 kHz. What is the power radiated? If the total resistance of the antenna is 1.12 , find the efficiency. leff = 100m I = 450 A f = 40KHZ Rin = Rr + Rloss = 1.12 Wr = ? Rr = ? = ?</p>
<h3 id="receiving-aerial-and-reciprocity-theorem">RECEIVING AERIAL AND RECIPROCITY THEOREM</h3>
<p>So far we have devoted more attention to an antenna as a transmitting device. But it is equally important as receiving device. When antenna is used as a receiving device, the incident EM energy induces a voltage at its terminals. The magnitude of the voltage induced depends on the electric field strength and the dimensions of the antenna. When a load is connected, the power is delivered.</p>
<p>The properties of receiving antenna are very much similar to those of transmitting antenna. This is because an antenna is a reciprocal device and follows Reciprocity theorem. The Reciprocity theorem is stated as follows: If an emf is applied to the terminals of an Antenna A, and the current measured at the terminals of another antenna B, then an equal current (in both amplitude and phase) will be obtained at the terminals of antenna A if the same emf is applied to the terminals of antenna B.</p>
<p>The result of this theorem is that the radiation pattern of the antenna is identical when it is used as receiving as well as transmitting antenna. Hence the power gain, impedance are the same whether used as a transmitting or receiving antenna.</p>
<figure>
<img src="assets/figures/ch1/fig36.png" id="fig:fig36" alt="" /><figcaption>Illustration of Reciprocity Theorem</figcaption>
</figure>
<p>using Reciprocity theorem we have Zab = Zba. As already pointed out a plane wave incident on an antenna induces a current in antenna element. The antenna re-radiates EM energy acting as transmitter.</p>
<h3 id="effective-aperture-of-an-antenna">EFFECTIVE APERTURE OF AN ANTENNA</h3>
<p>Power gain is one of the important properties of an antenna. Another property which is very important for receiving antenna is its capture area which is also referred to as Receiving cross section or effective aperture.</p>
<p>Consider a receiving antenna shown in fig 1-10-12(a). The field from a transmitter arrives at the receiver (Receiving antenna) with a Power density Pr W/m2. The receiving antenna exposed to this field will induce currents and voltages in it. At the antenna terminals this represents an RF power that can be delivered to the load. Let the power delivered to the load be W watt. Let the surface area over which the power collected by the antenna to deliver a power of W watt be A m2. The power delivered W = Pr A watt. The equivalent area over which the RF energy is captured by the receiving antenna is called effective area denoted by the letter Ae and defined as the ratio of power delivered by the antenna to the incident power density of the incoming EM wave with the antenna oriented for maximum response i.e. Effective aperture . This relation has the dimensions of area and hence this is called effective aperture. The</p>
<figure>
<img src="assets/figures/ch1/fig37.png" id="fig:fig37" alt="" /><figcaption>Receiving antenna terminated with load ZR (a) Receiving antenna (b) Equivalent Circuit of antenna</figcaption>
</figure>
<p>value of the capture area obtained for matched condition is maximum. It is called maximum effective aperture or simply effective aperture.</p>
<p>Effective aperture can be thought of as a fictitious cross-sectional area such that the power absorbed by this area is equal to that actually absorbed by the antenna under matched conditions. This has a unique value for a given antenna. Consider the fig 1-10-12(b) in which the antenna is represented by its equivalent circuit consisting of a alternating voltage source U and an impedance ZA in series with it. The open circuit voltage V induced across its terminals is due to the incident field. This produces a current I through the antenna. ZA is the antenna impedance ZT is the load impedance. Then ZA = RA j XA ———- ZT = RT j XT ———— The antenna impedance has the real part RA which consists of two parts, radiation resistance Rr and loss resistance Rloss. RA = Rr + Rloss Assuming a loss less antenna Rloss = 0.</p>
<p><img src="assets/figures/ch1/fig38.png" id="fig:fig38" alt="image" /> <span id="fig:fig38" label="fig:fig38">[fig:fig38]</span></p>
<p>RA = Rr ; ZA = Rr j XA The power delivered to the load by the antenna is W = I2 Rr</p>
<p><img src="assets/figures/ch1/fig39.png" id="fig:fig39" alt="image" /> <span id="fig:fig39" label="fig:fig39">[fig:fig39]</span></p>
<p>Under matched condition, Rr = RT and XA = - XT</p>
<p>By definition, the effective aperture is the ratio of power delivered to the load to the power density of the incident EM wave.</p>
<p>The above equation forms the basis for determining the effective aperture of any antenna. The power dissipated in the antenna resistance is re-radiated or scattered. This re-radiated power is delivered to the load. Under matched condition all these are equal.</p>
<h3 id="physical-aperture">PHYSICAL APERTURE</h3>
<p>The physical aperture of an antenna is defined as the physical area of cross-section perpendicular to the incident electromagnetic wave with the antenna oriented for maximum response. This is denoted by AP. Consider a horn antenna shown in fig. For a horn antenna the area of cross section of the mouth of the horn.</p>
<p>Fig 1.9.14</p>
<p>On the other hand, consider a cylindrical dipole of length, l, and diameter, d, the physical aperture AP is the area given by AP = ld m2.</p>
<p>Therefore, the physical aperture AP depends on the type of antenna and its structure where as the effective aperture is a unique quantity. The physical and effective apertures need not be equal. Some antennas like half-wave antenna have larger effective aperture compared to physical aperture. However, for high gain antennas the physical aperture and effective aperture are nearly equal.</p>
<p><img src="assets/figures/ch1/fig40.png" id="fig:fig40" alt="image" /> <span id="fig:fig40" label="fig:fig40">[fig:fig40]</span></p>
<p>Fig 1.9.14.1</p>
<h3 id="effective-aperture-of-a-short-dipole"> EFFECTIVE APERTURE OF A SHORT DIPOLE</h3>
<p>The short dipole has its length l&lt;&lt; and the current distribution is uniform. Let the dipole be subjected to an incident EM field with field strength E V/m which produces a voltage Vat its terminals.</p>
<p>The voltage induced V = E l volts. The power density of the incoming EM wave at the dipole,</p>
<h3 id="relation-between-directivity-and-effective-aperture">RELATION BETWEEN DIRECTIVITY AND EFFECTIVE APERTURE</h3>
<p>Consider an antenna with aperture Ae and with a uniform field Ea over the aperture as shown in fig 1-10-16. The power radiated</p>
<p>Fig 1.9.16</p>
<p>Let the field at a distance r along the maximum radiation direction be Er. The power radiated at a distance r is given by</p>
<p>Equation (1) and (2) are identical 2 = Ae A (4) Where is the wave length = Ae is the effective Aperture m2 A is the beam solid angle in steradian We know that Directivity,</p>
<p>The beam solid angle or beam area is related to directivity by the relation</p>
<p>For an isotropic antenna the 3 - D pattern is spherical. A = 4 SV D = 1.</p>
<p>For any other directional pattern, the beam area A is not equal to Sr. It is less than 4 Sr. For E.g.: Consider a dipole whose directivity is , we have</p>
<p>Thus the dipole radiation pattern will fill of the sphere. For antennas with large directivity, the smaller will be the fraction of the sphere filled by its radiation pattern.</p>
<p><img src="assets/figures/ch1/fig41.png" id="fig:fig41" alt="image" /> <span id="fig:fig41" label="fig:fig41">[fig:fig41]</span></p>
<p>Fig 1.9.16.1</p>
<h3 id="friis-transmission-formula">FRII’s TRANSMISSION FORMULA</h3>
<p>Using the concept of effective aperture Harard T-FRII’s derived a formula for received power. This is an important relation useful in finding the received power in a communication system. Consider the fig 1-10-17 depicting a communication system in which the transmitted EM waves traverse over a distance r and reach a receiving antenna by a direct path.</p>
<p><img src="assets/figures/ch1/fig42.png" id="fig:fig42" alt="image" /> <span id="fig:fig42" label="fig:fig42">[fig:fig42]</span></p>
<p>Fig 1.9.17</p>
<p>Let the power radiated by the transmitting antenna be Wr watt. Initially assuming the transmitting antenna to be an isotrope, the power density at the receiving antenna site is</p>
<p>If the transmitting antenna is a directive antenna with Directivity Dt, we get the power density The receiving antenna has an effective Aperture Aer and the Directivity Dr. Then the Power received</p>
<p>Also Substituting for Gt in we get,</p>
<p>The above relation is called FRIIS transmission formula which is the power transfer ratio</p>
<p><strong>Illustration 21:</strong> What is the maximum effective aperture of a Microwave antenna with a directivity of 900? Assume the frequency of operation to be 300MHz. D = 900 Ae = ? f = 900 MHZ</p>
<p>= 1m</p>
<p><strong>Illustration 22:</strong> What is the maximum effective aperture for a beam antenna having half power beam widths of 300 and 350 in two principal planes? Minor lobes may be neglected HP = 300 Hp = 350 D = ? Ae = ?</p>
<p>If is in m, then the maximum effective Aperture</p>
<p><strong>Illustration 23:</strong> What is the maximum power received at a distance of 0.5km over a free space 1GHz circuit consisting of a transmitting antenna with a 25dB gain and a receiving antenna with a gain of 20dB? The gain is w.r.t. a lossless isotropic source. The transmitting antenna input is 150W.</p>
<p><span> <img src="assets/figures/ch1/fig43.png" alt="image" /> <span id="fig:fig43" label="fig:fig43">[fig:fig43]</span> </span></p>
<p>Using FRII’S Transmission formula, the received power</p>
<h2 id="half-wave-dipole">HALF-WAVE DIPOLE</h2>
<p>The half-wave dipole antenna is one of the most popularly used antenna elements in many types of antenna systems. This has length of (half-wave length) and is centre fed. It is necessary to have full knowledge of the properties of this antenna both at resonant frequency as well as off the resonant point. The half-wave dipole antenna is a very commonly used antenna in the VHF and UHF applications because of its convenient dimensions in these ranges of frequencies.</p>
<p>The current distribution along the dipole is not uniform. This is approximated to be sinusoidal. An insight into the current distribution can be understood by an analogy with transmission line theory. There will be standing waves on an open circuited transmission line as shown in fig 1-10-18(a). Similar standing waves occur if the two conductors are separated at the open ends. The situation is shown in fig 1-10-18(b) for a quarter-wave line open and then turned through a right angle. The resulting current distribution over a dipole is sinusoidal.</p>
<p>Fig 1.10</p>
<p>The process of opening out a transmission line at its has the effect of making the capacitance per unit length will be non uniform which results in a change in current distribution. The process of opening out also may cause change in current distribution. However, it has been observed that the current distribution over a dipole is sinusoidal.</p>
<figure>
<img src="assets/figures/ch1/fig44.png" id="fig:fig44" alt="" /><figcaption>Current distribution along a half wave dipole</figcaption>
</figure>
<p>Fig 1.10.1</p>
<h3 id="field-due-to-half-wave-dipole">FIELD DUE TO HALF-WAVE DIPOLE</h3>
<p>To find the field due to a half wave dipole it is considered as consisting of a chain Hertzian dipoles connected back to back. The fig 1-10-19 shows the dipole antenna which is centre fed with a current distribution . Consider two elementary dipoles A and B of length dz each and spaced at distance z apart. The radiation from doublet A lags that from doublet B by zcos. Hence, the electric field due to doublet A at the point P in the far field zone r metre from the doublet is given by</p>
<p>The total electric field at the point P is</p>
<p>Where</p>
<figure>
<img src="assets/figures/ch1/fig45.png" id="fig:fig45" alt="" /><figcaption>Determination of field due to a half wave dipole</figcaption>
</figure>
<p>Fig 1.10.1.1</p>
<p>using relations (4),(5),(6) and putting them in (3) we have,</p>
<p>But Therefore,</p>
<p>we have,</p>
<h3 id="field-pattern-of-hal-wave-dipole-and-beam-width">FIELD PATTERN OF HAL-WAVE DIPOLE AND BEAM WIDTH</h3>
<p>The pattern of dipole is determined by the factor . The Radiation pattern in the two Principal planes is shown in fig.</p>
<p>The pattern of a dipole is similar to the pattern of a short dipole. It is a doughnut shaped pattern in 3-D and an inverted figure of eight in Y-Z plane and circular pattern in X-Y plane. However, the pattern is more directive compared to a short dipole.</p>
<p>Fig 1.10.2.1 Field pattern of a half wave dipole</p>
<p>Finding beam width of dipole: We have the field due to a dipole</p>
<p>E will be maximum</p>
<p>At the half power points</p>
<p>Beamwidth between half-power points HPBW = 2(90-51) = 2(39) HPBW = 780 or HPBW = 129-51 = 780</p>
<p>Fig 1.10.2.2</p>
<p>Therefore, the pattern of dipole is more directive as the HPBW is less than that of a short dipole. A comparison of the pattern of short dipole, dipole and isotrope is shown in fig</p>
<p>Fig 1.10.2.3 Comparison of radiation pattern of half wave dipole, short dipole, and isotropic antenna</p>
<p>1.10.3 DIRECTIVITY OF HALF-WAVE DIPOLE</p>
<p>For a dipole, the maximum field strength in a direction = 900</p>
<p>The power density due to the dipole at a distance r in the direction of maximum radiation</p>
<p>The Maximum field due to an isotrope radiating the same power</p>
<p>The corresponding power density at r for an isotropic antenna</p>
<p>The power radiated by the dipole</p>
<p>The above is a peak power, However the rms power</p>
<p>The integral is an implicit function, it can be evaluated by Numerical integration</p>
<p>D = 10log (1.64) = 2.14dB.</p>
<h3 id="radiation-resistance-of-half-wave-dipole">RADIATION RESISTANCE OF HALF-WAVE DIPOLE</h3>
<p>Mean Power radiated by the dipole</p>
<p>If Rr is the radiation resistance and I0 is the peak current fed to the dipole, then the power radiated is given by</p>
<p>Equating (1) and (2), we get</p>
<p>The radiation resistance of a dipole is 73 which is a value convenient for matching 75 line co-axial cable. Hence the dipole is a practically important a antenna.</p>
<h3 id="effective-length-of-half-wave-dipole">EFFECTIVE LENGTH OF HALF-WAVE DIPOLE</h3>
<p>The current distribution over a half-wave dipole is sinusoidal. Hence the effective</p>
<p><img src="assets/figures/ch1/fig46.png" id="fig:fig46" alt="image" /> <span id="fig:fig46" label="fig:fig46">[fig:fig46]</span></p>
<p>height is less than the physical length of the dipole. If I0 is the current at the input terminals of the antenna, then the effective length is defined as that length which if it carried a uniform current I0, would result in the same radiated power. Area under the Rectangle distribution = actual area under the current length curve.</p>
<p>For vertical antennas effective length is referred to as effective height.</p>
<h3 id="effective-aperture-of-half-wave-dipole">EFFECTIVE APERTURE OF HALF-WAVE DIPOLE</h3>
<p><img src="assets/figures/ch1/fig47.png" id="fig:fig47" alt="image" /> <span id="fig:fig47" label="fig:fig47">[fig:fig47]</span></p>
<p>Fig 1.10.6.1</p>
<p>The effective aperture in general is given by the relation For a half wave dipole and Radiation resistance Rr = 73 Power density</p>
<p>The effective aperture of dipole is approximately same as</p>
<p>The physical aperture for the same dipole with l = and thickness of dipole to be then, Ap = l thickness = m2 The effective aperture is independent of dimensions of antenna. But physical aperture is dependent on dimensions.</p>
<p><img src="assets/figures/ch1/fig48.png" id="fig:fig48" alt="image" /> <span id="fig:fig48" label="fig:fig48">[fig:fig48]</span></p>
<p>Fig 1.10.6.2</p>
<p>A comparison of Ae and Ap shown in fig 1-10-19</p>
<p>Shaded area is Ae and the unshaded area is Ap It is clear from the above discussion that for a half-wave dipole, the effective area (Ae) is much more compared to physical area of cross section (Ap). This is a very important property which will account for an area larger than physical area.</p>
<h3 id="reactance-and-resistance-curves-of-dipole-antenna">REACTANCE AND RESISTANCE CURVES OF DIPOLE ANTENNA</h3>
<p>The curves in fig(a) and fig(b) show how the reactance and resistance of dipoles antenna vary with length . Also the impedance is dependent on thickness of the dipole or the diameter of the wire used for dipole. The importance regions of the curves are those corresponding to the length of approximately , which represents dipole.</p>
<p>Fig 1.10.7.1 (a) Reactance curve (b) Resistance curve</p>
<p>It is to be noted that the resonance occurs for length slightly less than . If the length is exactly , there will be a Resistive component with inductance. If we choose the length slightly less than , the input impedance will be a pure resistance equal to 73 (the radiation resistance of dipole). For a half-wave dipole antenna, the impedance Za = Rr j XA. Normally XA is negligible. The radiation resistance is 73 which will match with the feeder line input impedance. Since this antenna has to operate over a band of frequencies, the input impedance must be constant. The band width over which a antenna can operate is around +5</p>
<p>If we closely examine the resistance curves of antenna, we see that the resistance for lengths around remains constant at 75. It does not depend very much on the diameter of the dipole for lengths around . However, the diameter of wire will reduce the rate of change of reactance considerably with frequency. Thus a thicker dipole will work over a wide band and hence preferable in applications where the antenna is to be used over a wideband. The analysis of the impedance-frequency characteristics of a dipole is quite complex and the important characteristics are given here for the better understanding of dipole antenna. A dipole operated at a length closer to will have the impedance purely resistive and equal to the radiation resistance Rr = 73. A thicker dipole will have wide bandwidth compared to thinner dipoles. Hence a dipole has applications not only in the lower RF range but at VHF and UHF range of frequencies.</p>
<h2 id="dipole-antennas-near-the-surface-of-the-ground">DIPOLE ANTENNAS NEAR THE SURFACE OF THE GROUND</h2>
<p>We have analyzed antennas much above the ground and located well above the ground in free space. However, when the antenna is close to the surface of the earth, the directional characteristics are changed. Such antennas are analyzed on the principle of images. If an antenna is located at a height h from the ground, energy radiated towards the earth is reflected from an image exactly. The total field at a distant point is the sum of the direct radiation and the reflected energy from the image antenna. Therefore, the field at the distant point produced by this monopole is equivalent to that of a dipole of length 2h when both antennas are fed with the same current. The earth is assumed to have reflection co-efficient of unity. The combination of half dipole with its image in the reflecting surface is called a monopole. The radiation pattern for monopoles will be only half the free space pattern because the other half is short circuited by the earth. That is the other half is cut-off.</p>
<figure>
<img src="assets/figures/ch1/fig49.png" id="fig:fig49" alt="" /><figcaption>Principle of image antenna</figcaption>
</figure>
<p>Fig 1.11</p>
<p>The effect of this is that the radiated power is reduced by half and the radiation resistance also is reduced by half compared to free space values. However the pattern becomes twice as directive compared to a dipole in free space. However in azimuth plane, the pattern is omni-directional. A monopole is grounded at one end. For a short monopole whose length is less than the Radiation resistance . The Directivity of this antenna will be 3(twice that of the free space dipole). Fig (2) shows a monopole with its pattern.</p>
<figure>
<img src="assets/figures/ch1/fig50.png" id="fig:fig50" alt="" /><figcaption>Monopole</figcaption>
</figure>
<p>Fig 1.11.1 (a)</p>
<figure>
<img src="assets/figures/ch1/fig51.png" id="fig:fig51" alt="" /><figcaption>Pattern of a monopole</figcaption>
</figure>
<p>Fig 1.11.1 (b)</p>
<p>It is to be observed that the pattern exists over half the sphere. Therefore the Half power beam width will be 450. Hence the directivity is twice the short dipole i.e., it is equal to 3 as already stated.</p>
<h2 id="quarter-wave-monopole">QUARTER WAVE MONOPOLE</h2>
<p>Similar to a short monopole, we have monopole. In this, the lower end is grounded. Its length will be . But in free space, the far field is due to the monopole of length and a field due to reflected ray because of image antenna. The fig3 shows a Quarter wave monopole and its radiation pattern.</p>
<figure>
<img src="assets/figures/ch1/fig52.png" id="fig:fig52" alt="" /><figcaption>Quarter Wave Monopole</figcaption>
</figure>
<p>Fig 1.12</p>
<figure>
<img src="assets/figures/ch1/fig53.png" id="fig:fig53" alt="" /><figcaption>Radiation Pattern</figcaption>
</figure>
<p>Fig 1.12 (b)</p>
<p>The quarter-wave monopole is erected with its base at ground as shown in fig 3(a). This is fed with a current I0 and the current distribution along the element also is shown. We assume that we have perfect reflecting surface. The actual monopole along with its image produces the same field as that of a dipole. The radiation resistance is half that of dipole for a monopole i.e., it has a value of 36.5. The pattern of the monopole in vertical plane is shown in fig 3(b). As in a short monopole, the radiation pattern is over half the free space pattern of dipole. The other half is cut-off by the earth. The beam width is 78/2 = 390. This results in a directivity which is twice that of dipole in free space. That is the Directivity of monopole will be 1.642 = 3.28. This produces a vertically polarized wave. monopole radiators are used for broadcasting and other applications in medium frequency range of about 500 kHz to 3 MHz. The field due to a monopole</p>
<h2 id="comparison-of-basic-radiators">COMPARISON OF BASIC RADIATORS</h2>
<p>Comparison of basic radiators discussed so far is given below in the form of Table (for a few important parameters) 1(3) 2(4) 3(5) 4(2) Type of Antenna Directivity (D) Effective aperture (Ae) Radiation resistance Rr Beam width (HPBW) 1 Isotropic antennas 1 - 3600 2 Hertzian dipole 1.5 0.122 900 3 dipole 1.64 0.132 73 780 4 3.28 0.262 36.5 390</p>
<p><img src="assets/figures/ch1/fig54.png" id="fig:fig54" alt="image" /> <span id="fig:fig54" label="fig:fig54">[fig:fig54]</span></p>
<h2 id="babinets-principle">BABINET’S PRINCIPLE</h2>
<p>A narrow rectangular slot cut in an infinite conducting sheet when properly connected to a source of RF power between opposite sides of the slot will radiate EM energy like an antenna. This antenna is called a slot antenna. If the slot cut in an infinite conducting plane is exactly the same as a flat dipole whose thickness is same as that of slot width and the length of the dipole is same as that of the slot, then the radiation pattern is exactly same as that of the dipole. The only difference is that the electric and magnetic fields are reversed in a slot antenna though the impedance properties of the slot are different compared to the dipole. The principle used to explain this complementary property of antennas is called Babinet’s principle.</p>
<p>In optics, the Babinet principle is stated as follows: The field at any point behind a plane having a screen, if added to the field at the same point when the complimentary screen is substituted, is equal to the field at that point when the screen is removed.</p>
<p>The above principle is illustrated in Fig 1-12</p>
<p>Fig 1.14 A source and two imaginary planes are shown. In the first case, a perfectly absorbing screen is placed in plane A. The shadow region is represented by plane B. Let the field behind this screen be Fs.</p>
<p>In the second case, the screen is replaced by its complementary screen and let the field behind this be Fcs. With no screen present, let the field be F0. By Babinet’s principle Fs + Fcs = F0. The Babinet’s principle has been generalized and extended to take into account the vectorial nature of the EM waves. One screen is taken to be conducting with conductivity tending to infinity and the complementary screen is taken to be having infinite permeability. One screen is a conductor of electricity and the complementary screen is conductor of magnetism.</p>
<p>This principle can be extended to the slot antenna for explaining its radiation properties. Consider the source to be a dipole and the screen to be a conducting surface with a slot.</p>
<p>Fig 1.14.1 Fig 1-12-1 Babinet principle applied to a slot in a infinite metal sheet and a complimentary metal strip.</p>
<p>Field distribution around the slot and the radiation from the slot is the same as that of a dipole antenna. This is illustrated in fig 22(a) and (b)</p>
<p>Fig 1.14.2</p>
<p>The electric field from the slot is related to the magnetic field from the dipole by the relations Eslot = Hdipole and Hslot = Edipole/ where is the intrinsic impedance of free space. . The E and H vectors in a slot are interchanged. Therefore, the state of polarization is opposite to that of a corresponding dipole. Hence the pattern is unaffected. The input impedance of the slot is given by . For a dipole, the input impedance is ZA = 73 + j 42 and hence the impedance of Zslot = 363 - j 2. However for a resonant half wave dipole, the length is slightly less than i.e. l = 0.475. For this length antenna impedance is purely resistive ZA = 67. Therefore impedance of slot is resistive and</p>
<p><img src="assets/figures/ch1/fig55.png" id="fig:fig55" alt="image" /> <span id="fig:fig55" label="fig:fig55">[fig:fig55]</span></p>
<p>Fig 1.14.3</p>
</body>
</html>
