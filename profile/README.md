<div align="center">

<img src="https://raw.githubusercontent.com/DevFourYou/.github/main/assets/header.svg" width="100%" alt="Dev4You: equipo de estudio en Lima, Perú"/>

<br/>

<a href="https://github.com/DevFourYou"><img src="https://img.shields.io/badge/📍_Lima,_Perú-161B22?style=for-the-badge&labelColor=161B22" alt="Lima, Perú"/></a>
<img src="https://img.shields.io/badge/estudiantes-4-00F0FF?style=for-the-badge&labelColor=161B22" alt="4 estudiantes"/>
<img src="https://img.shields.io/badge/proyectos-VR_·_Web_·_IA-9B5CFF?style=for-the-badge&labelColor=161B22" alt="VR, Web e IA"/>

</div>

<img src="https://raw.githubusercontent.com/DevFourYou/.github/main/assets/divider.svg" width="100%"/>

## 👋 Quiénes somos

Somos **cuatro estudiantes de carrera** en Lima, Perú. Usamos esta organización como **equipo de estudio** para juntar
los proyectos que desarrollamos en los cursos de la universidad y probar ideas que mezclen realidad virtual,
desarrollo web e inteligencia artificial.

<table>
  <tr>
    <td align="center" width="33%">
      <h3>🥽</h3>
      <b>Realidad virtual</b><br/>
      <sub>Escenas 3D, física, háptica y audio espacial en Unity para Meta Quest 3.</sub>
    </td>
    <td align="center" width="33%">
      <h3>🌐</h3>
      <b>Desarrollo web</b><br/>
      <sub>Interfaces y APIs con Next.js, TypeScript y Bun para conectar todo desde el navegador.</sub>
    </td>
    <td align="center" width="33%">
      <h3>🤖</h3>
      <b>IA aplicada</b><br/>
      <sub>Integración de modelos de lenguaje y voz para acompañar cada proyecto de estudio.</sub>
    </td>
  </tr>
</table>

<img src="https://raw.githubusercontent.com/DevFourYou/.github/main/assets/divider.svg" width="100%"/>

## 🚀 Proyecto de curso: Xplica

<table>
  <tr>
    <td width="52%" valign="middle">
      <img src="https://raw.githubusercontent.com/DevFourYou/.github/main/assets/xplica-room.png" width="100%" alt="Consultorio virtual de Xplica"/>
    </td>
    <td width="48%" valign="middle">
      <h3>🦴 Espejo anatómico en VR</h3>
      <p>Proyecto para el curso <b>Desarrollo de Videojuegos con Realidad Aumentada y Virtual</b>. El usuario entra a un consultorio virtual, ve una pierna en 3D a escala real, separa sus capas anatómicas y escucha a una guía explicar el caso cargado con un PIN desde el portal web.</p>
      <p>
        <img src="https://img.shields.io/badge/181-estructuras-00F0FF?style=flat-square&labelColor=161B22"/>
        <img src="https://img.shields.io/badge/7-capas_anatómicas-4EA8FF?style=flat-square&labelColor=161B22"/>
        <img src="https://img.shields.io/badge/PIN-4_dígitos-9B5CFF?style=flat-square&labelColor=161B22"/>
      </p>
      <p>
        <a href="https://github.com/DevFourYou/Xplica"><b>🥽 Visor VR</b></a> ·
        <a href="https://github.com/DevFourYou/xplica-web"><b>🩺 Portal web</b></a> ·
        <a href="https://github.com/DevFourYou/Xplica/releases"><b>📦 Releases</b></a>
      </p>
    </td>
  </tr>
</table>

> [!NOTE]
> **Trabajo académico:** todos los casos e informes usados en las pruebas son ficticios (Ley 29733), la guía no
> diagnostica y los repositorios de código del proyecto son privados mientras dura el curso.

<details>
<summary><b>🏗️ Cómo se conecta todo</b></summary>
<br/>

```mermaid
flowchart LR
    A["📄 Informe PDF"] --> B["🩺 Portal web<br/>Next 16 + Bun"]
    B -- "ficha con citas verificadas" --> C["🔐 PIN de 4 dígitos"]
    C --> D["🥽 Visor VR<br/>Unity 6.6 + OpenXR"]
    D --> E["🦴 Pierna por capas<br/>181 estructuras"]
    D --> F["🔊 Guía con voz<br/>guionizada + IA"]
```

</details>

<details>
<summary><b>📊 Optimización del visor (Unity Profiler)</b></summary>
<br/>

Comparación desde la vista del usuario antes y después de optimizar la escena para Quest 3:

| Métrica (peor cuadro) | Antes | Después | Mejora |
| :--- | :---: | :---: | :---: |
| Objetos que proyectan sombra | 437 | 76 | **−83 %** |
| Triángulos | 4.032.075 | 2.260.730 | **−44 %** |
| Draw calls | 926 | 556 | **−40 %** |
| Memoria de texturas | 419,8 MB | 285,2 MB | **−32 %** |
| GC Alloc por cuadro | 1,3 KB | 0,3 KB | **−77 %** |

</details>

<img src="https://raw.githubusercontent.com/DevFourYou/.github/main/assets/divider.svg" width="100%"/>

## 🛠️ Con qué trabajamos

<div align="center">

<img src="https://skillicons.dev/icons?i=unity,cs,nextjs,ts,bun,git,github&perline=7" alt="Unity, C#, Next.js, TypeScript, Bun, Git, GitHub"/>

<br/><br/>

<img src="https://img.shields.io/badge/Meta_Quest_3-0467DF?style=for-the-badge&logo=meta&logoColor=white" alt="Meta Quest 3"/>
<img src="https://img.shields.io/badge/OpenXR-1F2937?style=for-the-badge&logo=khronosgroup&logoColor=white" alt="OpenXR"/>
<img src="https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge&logoColor=white" alt="DeepSeek"/>
<img src="https://img.shields.io/badge/ElevenLabs-1F2937?style=for-the-badge&logo=elevenlabs&logoColor=white" alt="ElevenLabs"/>

</div>

<img src="https://raw.githubusercontent.com/DevFourYou/.github/main/assets/divider.svg" width="100%"/>

## 👥 El equipo

<div align="center">
<table>
  <tr>
    <td align="center" width="25%">
      <a href="https://github.com/IvyedSG"><img src="https://github.com/IvyedSG.png?size=200" width="96" alt="IvyedSG"/></a><br/>
      <b>Deyvi</b><br/>
      <sub>Sánchez</sub><br/>
      <a href="https://github.com/IvyedSG"><sub>@IvyedSG</sub></a>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/ander0code"><img src="https://github.com/ander0code.png?size=200" width="96" alt="ander0code"/></a><br/>
      <b>Max</b><br/>
      <sub>Ttito</sub><br/>
      <a href="https://github.com/ander0code"><sub>@ander0code</sub></a>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/DiegoInga"><img src="https://github.com/DiegoInga.png?size=200" width="96" alt="DiegoInga"/></a><br/>
      <b>Felipe</b><br/>
      <sub>Inga</sub><br/>
      <a href="https://github.com/DiegoInga"><sub>@DiegoInga</sub></a>
    </td>
    <td align="center" width="25%">
      <a href="https://github.com/AngelCh0"><img src="https://github.com/AngelCh0.png?size=200" width="96" alt="AngelCh0"/></a><br/>
      <b>Angel</b><br/>
      <sub>Choquehuanca</sub><br/>
      <a href="https://github.com/AngelCh0"><sub>@AngelCh0</sub></a>
    </td>
  </tr>
</table>
</div>

<img src="https://raw.githubusercontent.com/DevFourYou/.github/main/assets/footer.svg" width="100%"/>
