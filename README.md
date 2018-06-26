# design-system-generator-proposal

## Goals 

The motivation behind this project is to help educate the community about the importance / principles of building atomic design systems for their products, at the same time help them keep their peace of mind by helping with bootstrapping and keeping assets in sync. 

## Pros of doing so

* Promotes consistency and cohesion
* Allows for a more collaborative team effort ( designers and engineers together )
* Creating a shared vocabulary for the org
* Better reasoning about testing and documentation
* This such as cross browser compatibility, perf monitoring and accessibility can be baked and provided for free
* Faster and collaborative iteration ( A/B testing becomes trivial )

## Aim 

* World class cli tool to bootstrap a design system.
* Provide state-of-the-art tooling for handling opinionated workflows
* *Framework agnostic* ( may it be React, Vue, Angular, Web Components, or even plain old HTML and CSS ).

## Project Outline 

*Step 1* - The project envisions a cli tool which takes user input on things like babel presets, lint config, browser compatibility goals, bundling strategies, package manager, styling system and so on, and bootstrap a boilerplate project for them. Also there should be meaning defaults available. 

*Step 2* - The generated project then guides / educates the user about the process of building their design systems. This means introducing them to the core concepts such as tokens, atoms, and so on. At this point we might also provide some meaningful defaults to choose from and also the ability to export these units from PS or Sketch files.

*Step 3* - The project can optionally also target on providing a DSL to build and sync all design assets, something similar to lona. 


## Further Readings / Projects

1. Atomic Design by Brad Frost [http://atomicdesign.bradfrost.com/]
2. Material UI [https://material-ui.com/]
3. airbnb/lona [https://github.com/airbnb/Lona]
4. airbnb/react-sketchapp [https://github.com/airbnb/react-sketchapp]
