---
title: "Contact"
---

<style>
/* --- 0. CONFIGURAÇÃO BASE --- */
.container, main.content {
    max-width: none !important; 
    width: auto !important;     
}

/* --- 1. LARGURA GERAL E CONTAINERS --- */
.contact-container {
    width: 100%; 
    max-width: 1600px; /* Padronizado com as outras páginas */
    margin: 0 auto;    
    padding: 0 20px 50px 20px;
    box-sizing: border-box;
}

/* --- 2. PADRÃO DO TÍTULO PRINCIPAL --- */
.contact-container h1 {
    text-align: center;
    margin-top: 40px;
    margin-bottom: 50px;
    font-size: 2.2rem; 
    color: #2c3e50;
    border-bottom: 1px solid #eee; 
    padding-bottom: 20px;
}

/* --- 3. LAYOUT EM DUAS COLUNAS --- */
.contact-content {
    display: flex;
    flex-wrap: wrap;
    gap: 50px;
}

.contact-info {
    flex: 1;
    min-width: 300px;
    font-size: 1.1rem;
    line-height: 1.6;
    color: #333;
}

.contact-info h3 {
    color: #2c3e50;
    margin-top: 0;
    margin-bottom: 15px;
    font-size: 1.4rem;
}

/* --- 4. COLUNA DO MAPA E BOTÃO --- */
.contact-map {
    flex: 1.5; /* O mapa ocupa um espaço levemente maior */
    min-width: 300px;
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.contact-map iframe {
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    width: 100%;
    height: 350px;
}

.route-button {
    display: inline-block;
    background-color: #f8f9fa;
    color: #2c3e50;
    border: 1px solid #dcdcdc;
    padding: 10px 20px;
    border-radius: 20px;
    font-weight: 600;
    text-decoration: none;
    transition: all 0.2s ease;
    align-self: flex-start; /* Alinha o botão à esquerda sob o mapa */
}

.route-button:hover {
    background-color: #2c3e50;
    color: #fff;
    border-color: #2c3e50;
}

.post > h1 { display: none !important; }
</style>

<div class="contact-container">

<h1>Contact</h1>

<div class="contact-content">
    
<!-- COLUNA DA ESQUERDA: TEXTO E ENDEREÇO -->
<div class="contact-info">
    <h3>Where to find us</h3>
    <p>You can visit us at the Valongo Observatory, part of the Federal University of Rio de Janeiro (UFRJ).</p>
    
<h3 style="margin-top: 40px;">Address</h3>
<p>
    <strong>Valongo Observatory - UFRJ</strong><br>
    Ladeira Pedro Antônio, 43 - Saúde<br>
    Rio de Janeiro - RJ<br>
    ZIP: 20080-090
</p>

<p style="margin-top: 20px;">
    <strong>Phone:</strong> +55 (21) 2263-0685<br>
    <strong>Email:</strong> marco@astro.ufrj.br
</p>
</div>

<!-- COLUNA DA DIREITA: MAPA E BOTÃO -->
<div class="contact-map">
    <iframe 
        src="https://maps.google.com/maps?q=Observatório%20do%20Valongo&t=&z=15&ie=UTF8&iwloc=&output=embed" 
        style="border:0;" 
        allowfullscreen="" 
        loading="lazy">
    </iframe>

<a href="https://www.google.com/maps/search/?api=1&query=Observatório+do+Valongo" target="_blank" class="route-button">
View on Google Maps</a>
</div>

</div>
</div>