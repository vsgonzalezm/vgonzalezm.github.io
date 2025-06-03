---
title: "About / Sobre mí"
---

<div class="language-tabs">
  <button class="tab-button active" onclick="showTab('spanish')">Español</button>
  <button class="tab-button" onclick="showTab('english')">English</button>
</div>

<div id="spanish" class="tab-content active">

# Valentina González

Soy candidata a Doctora en Sociología por la Pontificia Universidad Católica de Chile, con una formación interdisciplinar que combina filosofía y sociología. Mi investigación se centra en el estudio de desigualdades sociales de género y estratificación social.

## Formación Académica

* **Doctorado en Sociología** (2020-Presente)  
  Pontificia Universidad Católica de Chile

* **Magíster en Sociología** (2020-2022)  
  Pontificia Universidad Católica de Chile

* **Magíster en Ciencias Sociales** (2015-2017)  
  Universidad de Chile

* **Licenciatura en Filosofía** (2010-2014)  
  Universidad de Chile

## Áreas de Especialización

* Métodos cuantitativos y cualitativos
* Estudios de género y cuidados
* Desigualdad y estratificación social

</div>

<div id="english" class="tab-content">

# Valentina González

I am a PhD candidate in Sociology at Pontificia Universidad Católica de Chile, with an interdisciplinary background combining philosophy and sociology. My research focuses on the study of gender social inequalities and social stratification.

## Academic Background

* **PhD in Sociology** (2020-Present)  
  Pontificia Universidad Católica de Chile

* **Master's in Sociology** (2020-2022)  
  Pontificia Universidad Católica de Chile

* **Master's in Social Sciences** (2015-2017)  
  Universidad de Chile

* **Bachelor's in Philosophy** (2010-2014)  
  Universidad de Chile

## Areas of Specialization

* Quantitative and qualitative methods
* Gender and care studies
* Inequality and social stratification

</div>

<style>
.language-tabs {
  display: flex;
  margin-bottom: 20px;
  border-bottom: 2px solid #e1e5e9;
}

.tab-button {
  background: none;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
  font-size: 16px;
  font-weight: 500;
  color: #6c757d;
  border-bottom: 2px solid transparent;
  transition: all 0.3s ease;
}

.tab-button.active {
  color: #007bff;
  border-bottom-color: #007bff;
}

.tab-button:hover {
  color: #007bff;
}

.tab-content {
  display: none;
}

.tab-content.active {
  display: block;
}
</style>

<script>
function showTab(language) {
  // Hide all tabs
  document.querySelectorAll('.tab-content').forEach(tab => {
    tab.classList.remove('active');
  });
  
  // Remove active class from all buttons
  document.querySelectorAll('.tab-button').forEach(button => {
    button.classList.remove('active');
  });
  
  // Show selected tab
  document.getElementById(language).classList.add('active');
  
  // Activate clicked button
  event.target.classList.add('active');
}
</script>
