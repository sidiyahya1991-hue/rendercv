# RenderCV

<div align="center" markdown>
*CV/resume generator for academics and engineers*

[![test](https://github.com/rendercv/rendercv/actions/workflows/test.yaml/badge.svg?branch=main)](https://github.com/rendercv/rendercv/actions/workflows/test.yaml)
[![coverage](https://coverage-badge.samuelcolvin.workers.dev/rendercv/rendercv.svg)](https://coverage-badge.samuelcolvin.workers.dev/redirect/rendercv/rendercv)
[![docs](https://img.shields.io/badge/docs-mkdocs-rgb(0%2C79%2C144))](https://docs.rendercv.com)
[![pypi-version](https://img.shields.io/pypi/v/rendercv?label=PyPI%20version&color=rgb(0%2C79%2C144))](https://pypi.python.org/pypi/rendercv)
[![pypi-downloads](https://img.shields.io/pepy/dt/rendercv?label=PyPI%20downloads&color=rgb(0%2C%2079%2C%20144))](https://pypistats.org/packages/rendercv)
</div>

Write your CV or resume as YAML, then run RenderCV,

```bash
rendercv render John_Doe_CV.yaml
```

and get a PDF with perfect typography. No template wrestling. No broken layouts. Consistent spacing, every time.

With RenderCV, you can:

- Version-control your CV — it's just text.
- Focus on content — don't worry about the formatting.
- Get perfect typography — pixel-perfect alignment and spacing, handled for you.

A YAML file like this:

```yaml
cv:
  name: reda sbait
  location: madrid.calle pozas 04
  email: sidiyahya1991@gmail.com
  website: https://rendercv.com/
  social_networks:
    
  sections:
    Welcome to RenderCV:
      - RenderCV reads a CV written in a YAML file, and generates a PDF with professional typography.
      - See the [documentation](https://docs.rendercv.com) for more details.
    education:
      - institution: Instituto de Educación Secundaria Zainab Al-Nafzawiya
        area:Ciencias de la Vida y la Tierra – Trimestre
        degree: 
        date:2011
        start_date: 2010-09
        end_date: 2011-05
        location: oujda ciudad marruecos.
         Datos personales
Nombre: Reda Sbeit
Fecha y lugar de nacimiento: Rabat, Marruecos – 08/05/1991
Teléfono: +34 617 629 523
Correo electrónico: sidiyahya1991@gmail.com
Formación académica
Carné de conducir (turismo)
Certificado de Educación Secundaria (año 2010)
Experiencia laboral
Agricultura
Venta de ropa
Carpintería
Habilidades personales
Ganas de aprender
Paciencia
Capacidad de escucha
Objetivo profesional
Persona responsable y preparada para incorporarse al trabajo de inmediato.
Formación actual
Actualmente realizando un curso de carretilla elevadora
En proceso de homologación del título de Educación Secundaria y del carné de conducir
Inicio previsto de un curso profesional en almacén a finales de abril
Situación legal
Permiso de estancia por estudios con autorización de trabajo hasta 30 horas semanales

