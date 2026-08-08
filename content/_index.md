---
title: "Building bLocks: explOring Chemistry and Kinematics of Small galaxies (BLOCKS)"
---

<style>
/* --- 1. OVERRIDE DO TEMA --- */
.container, main.content {
    max-width: none !important; 
    width: auto !important;     
}

/* --- 2. CONTAINER DA HOME --- */
.home-container {
    width: 100%; 
    max-width: 1600px; /* Igual à página de Research */
    margin: 0 auto;    
    padding: 0 20px;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: center; 
}

/* --- 3. TEXTO INTRODUTÓRIO --- */
.home-text {
    width: 100%; /* Permite que o texto vá de uma ponta à outra */
    text-align: justify; 
    font-size: 1.1rem; 
    line-height: 1.6; 
    color: #333; 
    margin: 0 auto 50px auto; 
}

/* --- 4. ALINHAMENTO DOS TÍTULOS --- */
.home-container h1 {
    text-align: center;
    margin-top: 40px;
    margin-bottom: 50px;
    font-size: 2.2rem; 
    width: 100%;
    line-height: 1.3;
    color: #2c3e50;
    border-bottom: 1px solid #eee; 
    padding-bottom: 20px;
}

.home-container h2 {
    text-align: center;
    margin-bottom: 30px;
    width: 100%;
    border-bottom: 1px solid #eee; 
    padding-bottom: 10px;
    color: #2c3e50;
}
/* --- 5. GRADE DE PERFIS E AJUSTE DE ESCALA --- */
.profiles-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center; 
    gap: 40px; /* Aumenta o espaço entre os pesquisadores */
    width: 100%;
    margin-bottom: 50px;
}

/* Ajusta a largura dos cartões para não espremer o texto */
.profiles-grid > div {
    width: 280px !important; 
    max-width: 100% !important; 
    padding: 20px !important;
    box-sizing: border-box;
}

/* Tamanho das fotos um pouco maior para acompanhar o cartão */
.profiles-grid img {
    width: 130px !important;
    height: 130px !important;
    max-width: 100% !important;
    margin-bottom: 15px !important;
}

/* Ajusta a fonte dos nomes */
.profiles-grid h3,
.profiles-grid h4,
.profiles-grid strong {
    font-size: 1.1rem !important;
    margin-bottom: 8px !important;
}

/* Ajusta a fonte das descrições */
.profiles-grid p, 
.profiles-grid span,
.profiles-grid a {
    font-size: 0.9rem !important;
    line-height: 1.4 !important;
}


</style>


<div class="home-container">

<h1>Building bLocks: explOring Chemistry and Kinematics of Small galaxies <br> (BLOCKS)</h1>

<div class="home-text">
Due to their low metallicities and angular momentum, high turbulence and bursty star formation history, nearby gas-rich dwarf galaxies with a low metals content are expected to be analogues of primeval galaxies. Interactions with more massive galaxies can drive the late (irregular) to early (spheroidal) type dwarf transformation. However, the lack of metallicity-gradient variations in the late-type, contrary to this gradient decrease in dwarf spheroidals and spiral disks, requires dedicated modelling and observational efforts. We aim at study local Universe dwarfs' chemical and dynamical properties to answer their open questions through different projects, this way placing these galaxies in the correct cosmological context.
</div>

<h2>Faculty</h2>
<div class="profiles-grid">
{{< profile 
    image="https://servicosweb.cnpq.br/wspessoa/servletrecuperafoto?tipo=1&id=K8060167Y0" 
    name="Marco Grossi" 
    description="(description)" 
    orcid="https://orcid.org/" 
    lattes="https://lattes.cnpq.br/" 
>}}
{{< profile 
    image="http://servicosweb.cnpq.br/wspessoa/servletrecuperafoto?tipo=1&id=K4728416A1" 
    name="Denise R Gonçalves" 
    description="(description)" 
    orcid="https://orcid.org/" 
    lattes="https://lattes.cnpq.br/" 
>}}
</div>

<h2>Students</h2>
<div class="profiles-grid">
  {{< profile 
      image="http://servicosweb.cnpq.br/wspessoa/servletrecuperafoto?tipo=1&id=K8144975Z3" 
      name="Rayssa Guimarães Silva" 
      position="PhD Student" 
      description="Evolution of dwarf galaxies in low-density environments." 
      orcid="https://orcid.org/" 
      lattes="https://lattes.cnpq.br/" 
      website="https://rayssags.github.io" 
  >}}
  {{< profile 
      image="http://servicosweb.cnpq.br/wspessoa/servletrecuperafoto?tipo=1&id=K1181249E7" 
      name="Raimundo José Ferreira Filho" 
      position="PhD Student"
      description="The relation between globular clusters and the dark matter halo of dwarf galaxies." 
      lattes="https://lattes.cnpq.br/3768018041447676"
  >}}
</div>

<div class="profiles-grid">
  {{< profile 
      image="http://servicosweb.cnpq.br/wspessoa/servletrecuperafoto?tipo=1&id=K1131515Z8" 
      name="Lucas Ribeiro da Silva" 
      position="BSc Student" 
      description="Intermediate black holes in low-mass galaxies of the MaNGA survey." 
      lattes="https://lattes.cnpq.br/0601908903616454" 
  >}}
  {{< profile 
      image="http://servicosweb.cnpq.br/wspessoa/servletrecuperafoto?tipo=1&id=K1193019T3" 
      name="Cecília Pereira Coutinho" 
      position="BSc Student"
      description="Searching for low-metallicity dwarf galaxies in the S-PLUS survey." 
  >}}
  {{< profile 
      image="" 
      name="Lucas Silva de Souza" 
      position="BSc Student"
      description="Star formation activity of dwarf galaxies with the ASKAP telescope." 
  >}}
</div>

</div>