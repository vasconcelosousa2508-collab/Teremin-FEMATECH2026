# Teremin-FEMATECH2026
Projeto que relaciona matemática e música via física ondulatória e acústica e trigonometria na construção de um instrumento musical digital. Sendo o Teremin ideal pois permite a observação clara de fenômenos físicos e matemáticos adaptado com Arduino, sensores ultrassônicos e bibliotecas de interface gráfica e áudio em Python.

Desenvolvido para a estande Matemática e Música da FEMATECH III - 2026 no IFCE Campus Fortaleza.


## Demonstração do Projeto
<table>
  <tr>
    <td align="center" colspan="2"><b>Circuito Físico</b></td>
  </tr>
  <tr>
    <td>
      <img height="805" alt="IMG_20260521_181443927_MP-EDIT" src="https://github.com/user-attachments/assets/203160da-56b9-4426-a93f-79ee0f71f093" />
    </td>
    <td>
      <img height="400" alt="IMG_20260521_183645091-EDIT" src="https://github.com/user-attachments/assets/d9176010-e2d0-4b1e-9a0d-94a0a097f20c" /><br>
      <img height="408" alt="IMG_20260521_183653178-EDIT" src="https://github.com/user-attachments/assets/674681af-8c71-4de6-ba69-a584c963a213" />
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center"><b>Interface </b></td>
  </tr>
  <tr>
    <td><img width="1920" height="1080" alt="Vol" src="https://github.com/user-attachments/assets/af2ad65b-bff0-4c42-82f7-e536c5025e66" />
</td>
  </tr>
</table>

#### Vídeo
[![Assista ao Vídeo Demonstrativo](imagens/miniatura_video.jpg)](PROLINK_DO_YOUTUBE_OU_DRIVE_AQUI)

---

## O Instrumento

Um Teremin é um instrumento que originalmente funciona com capacitancia eletrônica e permite que seja tocado sem contato direto com seu material, apenas partindo de pertubações em dois campos eletromagnéticos. 

---

## Sistema e Funcionamento

Para esta adaptação foi utilizado um micro-controlador Arduino Mega e dois sensores ultrassônicos, que enviam as distancias registradas para a porta USB de uma máquina. Nela está rodando um programa em python que recebe informações da porta USB e fornece um sintetizador de áudio unido a uma interface que reflete o gráfico de onda e processos feitos pelo sistema para cálculo de distancia e de onda senoidal.

### Modelagem
O circuito e o comportamento dos componentes foram planejados e simulados previamente:

![Modelo no Tinkercad](imagens/modelo_tinkercad.png)

---

## Teoria

Na apresentação deste repositório e durante a exposição na feira, são detalhados e demonstrados os seguintes tópicos científicos que conectam os dois temas:

* **Física Ondulatória e Acústica:** Como as ondas mecânicas se propagam no ar e de que forma a frequência define o comprimento de onda das notas musicais.
* **Trigonometria e Funções:** A aplicação prática da função seno na modelagem matemática e geração de áudio digital (onda senoidal).
* **Distância Acústica:** O cálculo do tempo de retorno do som feito pelos sensores ultrassônicos para rastrear as mãos do voluntário sem contato físico.

---

## Fotos do Evento

*Registros da nossa equipe durante a apresentação na FEMATECH III - 2026 no IFCE:*

<p align="center">
  <img src="imagens/foto_evento1.jpg" width="45%" />
  <img src="imagens/foto_evento2.jpg" width="45%" />
</p>
