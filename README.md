# Brand Material Skill

Claude Code Skill for creating professional marketing materials based on an existing website.

## What it does

The skill analyzes the existing website and project assets and uses them as the brand's source of truth.

It can create materials such as:

* Flyers
* Business cards
* Brochures
* Posters
* Postcards
* Social media graphics
* Advertisements
* Other branded marketing materials

The goal is that every new material feels like a natural extension of the existing website.

## Design philosophy

The skill focuses on:

* Premium visual design
* Strong typography
* Clear hierarchy
* Consistent branding
* Intentional whitespace
* Professional composition
* Realistic and believable visuals
* Print-ready output
* Human-designed aesthetics

It is specifically designed to work together with an **Anti-AI-Slop** skill.

The result should never look like generic AI-generated marketing material.

## Website as source of truth

Before creating anything, Claude Code analyzes:

* Colors
* Typography
* Logo
* Layout system
* Spacing
* Images
* Icons
* Visual motifs
* Content
* Tone of voice
* Calls to action
* Existing design tokens and assets

The marketing material is then designed from this existing identity instead of inventing a completely new style.

## Example

Inside an existing website project:

```text
"Mach mir einen doppelseitigen Flyer passend zur Website."
```

The skill automatically analyzes the project and creates a flyer that visually belongs to the same brand.

Likewise:

```text
"Erstelle passende Visitenkarten."
```

or:

```text
"Mach eine Broschüre aus der Website."
```

## Installation

Copy the `brand-material` folder into your Claude Code skills directory.

The structure should look like:

```text
.claude/
└── skills/
    └── brand-material/
        └── SKILL.md
```

The skill can then be used automatically by Claude Code when the task matches its description.

## Recommended combination

For the best results, use this skill together with:

* Anti-AI-Slop
* Cinematic Web Motion
* UI/UX design skills
* Any existing project-specific brand or design skills

The **website remains the source of truth**. Other skills should enhance the result without overriding the existing brand identity.
