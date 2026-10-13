<h1 align="center">Hi, I'm Kim Josell</h1>

<p align="center">
  <b>Computer Science Engineering student · Game Developer</b><br/>
  Building toward a career as an <b>AI Programmer</b> or <b>Gameplay Programmer</b>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/Godot_4-478CBF?style=for-the-badge&logo=godotengine&logoColor=white" alt="Godot 4"/>
  <img src="https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code"/>
</p>

---

## About me

I'm a CS engineering student focused on **game development**. I like designing systems that are **formally specified before they are implemented**: defining entities, relations, invariants and transformations first, then turning them into code.

- Building a portfolio through **Stardew Valley mods** and an **original game**
- Studying **discrete mathematics** to apply it directly to game design
- Interested in **game AI**: state machines, behavior trees and A* pathfinding
- Passionate about **cozy games** and what makes them work
- Fluent in **Spanish and English**

---

## Projects

### Potion Crafting Engine *(original project, in development)*
An engine-agnostic C++ library with a C interface for building potion-crafting systems in any game engine. Instead of hard-coded recipes, every potion is a point in a 3D space, so developers can define their own ingredients, domains, and effects and let players discover potions from scratch. The core is built on discrete and Euclidean geometry:

- **Potions as points in a 3D cube:** each ingredient is a 3D vector over **Z₁₁**
- **Mixing via modular arithmetic:** combining two ingredients applies an operator (addition, subtraction, multiplication, or exponentiation) to their vectors, then reduces the result modulo 11, so every outcome stays bounded
- **Effect detection with Euclidean geometry:** a recipe triggers an effect when its resulting point falls within the effect's range
- **Effect strength via normalized distance:** the closer the point is to the effect's center, the stronger the result
- **Developer-defined domains** to organize ingredients and effects
- Five formal entities with five invariants, documented in a formal design document
- **Data-driven architecture** with JSON

**Stack:** `C++` · `C API` · `JSON`
**Links:** [Repository](#) · [Design document](#)

---

### Stardew Valley Mod: Dynamic Spouses *(in development)*
A mod that makes spouses more dynamic in the base game.

**Stack:** `C#` · `SMAPI`
**Links:** [Repository](https://github.com/kimjosell/helpfulSpouses) · [Nexus Mods](#)

<!--
===========================================
 PROJECT TEMPLATE
 Copy this block, paste it above this comment,
 and replace the placeholders.
===========================================

### Project Name *(status: in development / completed / prototype)*
One or two sentences: what it is and what problem or idea it explores.

- Key feature or technical decision #1
- Key feature or technical decision #2
- Key feature or technical decision #3

**Stack:** `Tech 1` · `Tech 2` · `Tech 3`
**Links:** [Repository](URL) · [Demo](URL) · [Video](URL)

![Screenshot or GIF](path/to/image.gif)

---
-->

## Tech & tools

| Area | Tools |
|------|-------|
| **Languages** | C# · C++ · GDScript / GDExtension |
| **Engines & frameworks** | Godot 4 · SMAPI (Stardew Valley modding) |
| **Tools** | Visual Studio Code · dnSpy · Git |
| **Foundations** | Discrete mathematics · Game AI (FSM, behavior trees, A*) |

---

## Currently learning

- Discrete mathematics applied to game systems
- Game AI: state machines, behavior trees and A* pathfinding
- Modeling problems mathematically *before* writing code

---

## Let's connect

<p>
  <a href="https://www.linkedin.com/in/kimjosell"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:kimjosellag@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://LugiaLink.itch.io"><img src="https://img.shields.io/badge/itch.io-FA5C5C?style=for-the-badge&logo=itchdotio&logoColor=white" alt="itch.io"/></a>
</p>

<p align="center"><i>Always happy to talk about game dev, modding and cozy game design.</i></p>
