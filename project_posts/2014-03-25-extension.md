The simulation is run using the Grey Scott model.  A simple formula of two equations, applied repeatedly.  It simulates the interaction of two chemicals that diffuse, react, and are replenished at specific rates given by primarily two numerical quantities.  The amount that the active chemical decays, and an amount of the food chemical that is added to the system.

![Grey Scott Formulation](http://mrob.com/pub/comp/xmorphia/gray-scott-formula.jpg?raw=true "Grey Scott Formulation")

This simulation is performed in the GPU, with a chemical concentration in the red, and green channel.

An extra shader program has been used to prepare the state for display.

![Reaction Diffusion Detail](../project_images/rd_b_w_detail.jpg?raw=true "Reaction Diffusion Detail")

The organic growth contains some geometric and apparently random elements.  This complexity is emergent in the formulation itself.  Complex large-scale structure arises from simple, local rules.

![Reaction Diffusion](../project_images/rd_b_w.jpg?raw=true "Reaction Diffusion")

At full scale the pattern becomes uniform.

The following link runs the simulation inside the browser.

[Experiment 4](https://dl.dropboxusercontent.com/u/263160/Web/WebGl/Experiment4.html)
