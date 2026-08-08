---
title: "Research"
---

<style>
.container, main.content {
    max-width: none !important; 
    width: auto !important;     
}

/* LARGURA GERAL  */
.research-container {
    width: 100%; 
    max-width: 1600px; 
    margin: 0 auto;    
    padding: 0 3px;
    margin-top: 0px; 
    box-sizing: border-box;
}

@media (max-width: 960px) {
    .research-container { padding: 20px; }
    .reverse-layout { flex-direction: row; }
}

/*  DISTÂNCIA ENTRE AS COISAS */
.research-row {
    display: flex;
    flex-wrap: wrap; 
    align-items: center; 
    gap: 50px; 
    margin-bottom: 10px; 
    border-bottom: 1px solid #eee;
    padding-bottom: 40px;
}
.research-row:last-child { border-bottom: none; }

.research-text { 
    flex: 0.8; 
    min-width: 300px; 
    max-width: 800px; 
    text-align: justify; 
    font-size: 1.1rem; 
    line-height: 1.7; 
}

/*  COLUNA DA IMAGEM */
.research-image { 
    flex: 1.1; 
    min-width: 350px; 
}

.image-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    width: 100%;
    justify-content: center;
    flex-direction: column; 
}


/* Regra Geral para TODAS as imagens dentro do grid */
.image-grid img {
    width: 100%;       
    height: auto;      
    object-fit: contain;
    border-radius: 8px; 
    
    transition: transform 0.3s ease; 
    cursor: pointer;
}

.image-grid img:hover { 
    transform: scale(1.01); 
    z-index: 2; 
    box-shadow: 0 10px 20px rgba(0,0,0,0.1); 
}

/* Ajustes Específicos */
.image-grid img.small-grid {
    flex: 1 1 45%;
    min-width: 140px;
    height: 250px; 
    object-fit: cover; 
}

.image-grid .full-width {
    width: 100%;       
    height: auto;      
    max-height: none;  
    object-fit: contain;
}

/* TEXTOS */
.research-name { 
    font-size: 1.5rem; 
    color: #2c3e50; 
    font-weight: 800; 
    margin-bottom: 5px; 
}

.researcher { 
    font-size: 1.0rem; 
    color: #e67e22; 
    font-weight: 700; 
    text-transform: uppercase; 
    margin-bottom: 20px; 
    display: block; 
    letter-spacing: 1px; 
    margin-top: 0px;
}

.plot-caption { 
    margin-top: 8px; 
    font-style: italic; 
    color: #555; 
    
    text-align: justify; 


    font-size: 0.75rem;
    line-height: 1.4;
}

.reverse-layout { flex-direction: row-reverse; }

.post > h1 { display: none !important; }
</style>

<div class="research-container">
<h1 style="text-align: center; margin-top: 40px; margin-bottom: 50px; font-size: 2.2rem; color: #2c3e50; border-bottom: 1px solid #eee; padding-bottom: 20px; width: 100%;">
    Research Lines
</h1>


/* MARCO

<div class="research-row" style="margin-top: 50px;">
    <div class="research-text">
        <div class="research-name">The MaLHUCOS Survey</div>
        <span class="researcher">Marco Grossi</span>
        <p>
            We conducted a James Clerk Maxwell Telescope (JCMT) survey of molecular gas in low-mass disk galaxies selected from the MaNGA survey.
            Our sample includes 42 late-type galaxies with stellar masses between 10<sup>8</sup> and 10<sup>10</sup> M<sub>⊙</sub>, of which 55% are detected at 230 GHz through the CO(J=2–1) emission line.
        </p>
        <p>
            By combining IFU observations with the JCMT CO data, we investigate the processes that regulate the abundance of molecular gas and its conversion into stars in low-mass disk galaxies,
            as well as how it correlates with other galaxy properties such as stellar mass, star formation rate, and metallicity.
        </p>
    </div>

<div class="research-image">
    <div class="image-grid" style="flex-direction: row;">
        <img class="full-width" src="/blocks-teste/images/rect2.png" alt="JCMT Spectra">
    </div>
    <div class="plot-caption">Combined gri SDSS images of a subset of the MaLHUCOS sample with the MaNGA hexagonal field of view overlaid (32″ diameter, top row). Example of the JCMT spectra showing the detected CO(J=2-1) emission line (bottom row).
    </div>
</div>
</div>


/* CECILIA


<div class="research-row reverse-layout">
    <div class="research-text">
        <div class="research-name">Searching for metal-poor dwarf galaxies in the DR4 of the S-PLUS</div>
        <span class="researcher">Cecília Pereira Coutinho</span>
        <p>
            We use the DR4 of the S-PLUS to select low-metallicity dwarf galaxy candidates based on a color selection criteria for metal-poor, low-mass and star-forming galaxies.
        </p>
        <p>
            Our sample of 308 galaxies is being studied in terms of SEDs, with CIGALE, and our aim is to build a sample of metal-poor dwarf galaxy candidates to investigate galaxy chemical evolution at low stellar masses.
        </p>
    </div>

<div class="research-image">
    <div class="image-grid" style="flex-direction: row;">
        <img class="full-width" src="/blocks-teste/images/splus.png" alt="S-PLUS Analysis">
    </div>
    <div class="plot-caption">Left: S-PLUS multiband images of 2 low-metallicity dwarf galaxy candidates from this work, each covering 67"✕67". Right: examples of SED fitting with CIGALE. The pink circles represent the modeled flux and the white circle the photometric fluxes, obtained from the 12 S-PLUS magnitudes.
    </div>
</div>
</div>



/* LUCAS

<div class="research-row">
    <div class="research-text">
        <div class="research-name">AGN Feedback in Low-Mass Galaxies</div>
        <span class="researcher">Lucas Ribeiro</span>
        <p>
            In this work, we used spatially resolved Integral Field Unit (IFU) observations from the MaNGA survey to study a sample of dwarf and low-mass galaxies (M<sub>⋆</sub> < 5 × 10<sup>9</sup> M<sub>⊙</sub>) in all environments.
        </p>
        <p>
            Our main objectives are to detect AGN signatures, estimate virial Black Hole masses, and investigate the impact of AGN feedback on the global properties of these galaxies.
        </p>
    </div>

<div class="research-image">
    <div class="image-grid">
        <div>
            <img class="full-width" src="/blocks-teste/images/agn.png" alt="Spectral decomposition">
            <div class="plot-caption">
                Left: Spectral decomposition of the Hα region for object 9190-1901, showing the broad (green) and narrow (cyan) components.
                Right: The M<sub>BH</sub> - M<sub>*</sub> scaling relation. Our broad-line AGN candidates are compared to the DESI low-mass AGN sample.
            </div>
        </div>
    </div>
</div>
</div>





/* RAIMUNDO


<div class="research-row reverse-layout">
    <div class="research-text">
        <div class="research-name">Investigating globular clusters in dwarf irregular galaxies </div>
        <span class="researcher">Raimundo José Ferreira Filho</span>
        <p>
         We use the DELVE survey to search for globular clusters (GCs) in dwarf irregular galaxies outside the Local Group. Our sample includes 20 galaxies spanning a stellar mass range of approximately 10<sup>7.5</sup>- 10<sup>9.5</sup> M⊙. We also have Gemini/GMOS follow-up for some of the galaxies.
        </p>
        <p>
        We measure the properties of the GC systems and investigate scaling relations between the GC population and host galaxy properties, which are linked to the dark matter content, star formation history, mass assembly, and merger processes.
    </p>
    </div>

<div class="research-image">
    <div class="image-grid" style="flex-direction: row;">
        <img class="full-width" src="/blocks-teste/images/GC.png" alt="Descrição da Imagem">
    </div>
    <div class="plot-caption">The dashboard shows 10 dwarf irregular galaxies, with small circles representing the dispersion of the GCs around each galaxy. The color bar indicates the colors of the GC candidates, different colors within the same galaxy may suggest the presence of subpopulations. The red circle indicates a region corresponding to five effective radii around the galaxy.</div>
</div>
</div>

</div>