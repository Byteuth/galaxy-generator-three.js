# Three.js Galaxy Generator

This project showcases a dynamic galaxy generator using **Three.js**, with a focus on particle-based rendering and user interactivity. The scene allows users to explore and customize a procedurally generated galaxy through a GUI interface, emphasizing the use of particle systems and real-time adjustments.

**DEMO:** [galaxy-generator-three-js-mauve.vercel.app](https://galaxy-generator-three-js-mauve.vercel.app/)

## Particle System and Geometry

The galaxy is generated using a particle system that creates thousands of stars arranged in a spiral pattern. 

- **Particle Count:** Determines the total number of stars in the galaxy.
- **Star Size:** Controls the size of each individual star.
- **Galaxy Radius:** Adjusts the overall size of the galaxy.
- **Branches:** Sets the number of spiral arms extending from the galaxy's center.
- **Spin:** Adds rotational force to the galaxy, creating a spiral effect.
- **Randomness:** Introduces variations in star positions for a more natural look.
- **Randomness Power:** Controls the intensity of the randomness effect.
- **Inside Color:** The color of stars near the center of the galaxy.
- **Outside Color:** The color of stars at the galaxy's outer edges.

### Buffer Geometry and Points

The galaxy's stars are represented using **BufferGeometry** and **Points**, which efficiently handle large numbers of particles:

- **Positions:** 3D coordinates for each star are calculated based on the galaxy parameters.
- **Colors:** Vertex colors are used to create a gradient effect from the inside to the outside of the galaxy.

## Customization and GUI

A **GUI** is provided for real-time customization of the galaxy. Users can adjust various parameters to instantly see the changes in the galaxy:

![Screenshot from 2024-08-28 13-51-12](https://github.com/user-attachments/assets/990c3b2f-bad0-4b75-b647-c39fa9b2dccd)
![Screenshot from 2024-08-28 13-52-30](https://github.com/user-attachments/assets/611e532e-5334-45c8-9d7d-5a9b2bbfde44)
![Screenshot from 2024-08-28 13-54-06](https://github.com/user-attachments/assets/88b1032b-da25-487d-be77-4ded56bb955f)
![Screenshot from 2024-08-28 13-53-43](https://github.com/user-attachments/assets/17cfa849-1597-4a63-b404-0c2cdd84a9be)


