# Electric field line simulation
Display electric field lines for point charges. Application of the definition of electric field (force exerted per unit charge) and Coulomb's law.

# Preview

<img src="https://raw.githubusercontent.com/callummarshall9/ElectricFieldLineSimulation/master/preview.png" width="250" height="250">

# Usage

Simply open index.html.

Functions that can be called in JS console during runtime:

add_charge(charge_magnitude,x_coordinate,y_coordinate) - Function to add a charge at a specified coordinate with the magnitude specified. Be sure to redraw canvas to see changes in the electric field, alternatively calculate the electric field at a point using the command below.


calculate_net_electric_field(x_pos,y_pos) - Calculates electric field at a specific point.


draw() - Performs drawing commands.

Note: When adding charges, draw() will overlay the current field drawn so clear canvas using get_context().fillRect(0,0,800,800) in JS console.

# Todo

- Make interactive.
- Possibly make charges move based on accelerations then simulate how
the electric field changes with respect to changes in position of the charges.
