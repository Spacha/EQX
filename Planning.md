# Design
Que pasa?

# Elements
* **Configurability and updatability**
  * Powerful back-end and DB structure with Laravel
* **Searchability**
  * Everything must be easily found. There should be multiple ways to find what one is looking for (powerful search tool, book-like contents, graphic maps, ...)
* **Localization**
  * English as primary language, Finnish as secondary

# Hierarchy
* **Fields**
  * Mathematics, Physics, Chemistry, Astronomy, Mechanical engineering / Strength of materials, Biology, Computer Science
* **Areas**
  * Logics, Geometry, Algebra, Trigonometry, Statistics, Calculus, Linear algebra
  * Classical mechanics, Fluids, Thermodynamics, Wave optics (wave theory), Acoustics, Optics, Material physics, Quantum mechanics, Nuclear physics, Electromagnetism, Electrics
  * Fluid dynamics, Signal analysis, Digital filters, Wireless communications
* **Subjects**
  * Series expansions, trigonometric functions, complex numbers, exponents, logarithms, matrices, ...
* **Equations**
  * Product of roots, Euler's identity, normal distribution, frequency, two-ray model, ...

## Equation
```json
{
	"latex": "\\sqrt{a}\\sqrt{b} = \\sqrt{ab}",
	"name": "product of roots",
	"aliases": [],
	"short_description": "Product of roots is the root of products",
	"tags": ["root", "product", "multiplication"],
}
```

# General considerations

* One key are to focus on is the rendering of the equations. There needs to be caching of some sort, in order to have fast enough rendering of equations, especially on pages where there is a lot of equations.
The equations must still be "alive" (i.e. not images).