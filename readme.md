# Vampire

Originally developed by Richard Evans

Modified by LeBert Sam Billgates

Vampire is a high performance general purpose code for the atomistic simulation of magnetic materials. Using a variety of common simulation methods it can calculate the equilibrium and dynamic magnetic properties of a wide variety of magnetic materials and phenomena, including ferro, ferri and antiferromagnets, core-shell nanoparticles, ultrafast spin dynamics, magnetic recording media, heat assisted magnetic recording, exchange bias, magnetic multilayer films and complete devices.

## Capabilities
The original capabilities of Vampire include a variety of simulation methods, standard calculations, structural properties, magnetic properties, and code features. For a complete list of these features, please refer to the [original Vampire repository](https://github.com/richard-evans/vampire).

## New Feature: Vacancy Introduction Function
This modified version of Vampire includes a new feature to introduce defects in magnetic materials. The function can create **mono**, **di**, and **cluster vacancies**, allowing for more accurate simulations of defected materials.

### **Usage**
To include vacancies in your simulations, add the following parameters to your `.mat` file:

```
material[1]:cluster-vacancy-percentage=8
material[1]:num-vacancy-per-cluster=11
```
- **cluster-vacancy-percentage**: Specifies the percentage of vacancies to be introduced.
- **num-vacancy-per-cluster**: Defines the number of vacancies per site (mono, di, or cluster vacancies).

This feature enhances the capability of Vampire to simulate realistic defect structures in materials.

## Attribution
This code is a modified version of the original Vampire code developed by Richard Evans. The new features were introduced by **LeBert Sam Billgates**.

If you use this code in your research, please cite the following paper:
> LeBert Sam Billgates, "Introduction of Defects in Magnetic Materials using Vampire," *Physica Scripta*, DOI: [10.1088/1402-4896/ad3505](https://doi.org/10.1088/1402-4896/ad3505).

## License
See the license file.

