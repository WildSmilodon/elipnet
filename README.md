# Elpinet

 
Raw data to train a neural network for evaluating the resulting force dyad exerted on a soft ellipsoidal particle 

Data is generated using the Roscoe traction model, see:
R. Roscoe, On the rheology of a suspension of viscoelastic spheres in a viscous liquid, Journal of Fluid
Mechanics 28 (2) (1967) 273–293.

which is an extension to the work of Jeffery 1922, see
G. Jeffery, The motion of ellipsoidal particles immersed in a viscous fluid, Proceedings of the Royal Society
of London. Series A, Containing Papers of a Mathematical and Physical Character 102 (715) (1922)
161–179.

## Authors

Jana Wedel<sup>1</sup>, Paul Steinmann<sup>1</sup>, Matjaž Hriberšek<sup>2</sup>, Jure Ravnik<sup>2</sup>

<sup>1</sup>University of Nuremberg, Germany

<sup>2</sup>University of Maribor, Slovenia

## Contact

Please direct your inquiries to jana.wedel@fau.de.

## Details

The data presents the force dyad m in a non-dimensional form (mu=1,deq=1)

The data set includes ellipsoidal particles in 9 flow configurations with the following non-dimensional velocity gradients:

```
exp1   = [1.0 0.0 0.0;    0.0 -0.5 0.0;   0.0 0.0 -0.5]; 
exp2   = [-0.5 0.0 0.0;   0.0 1.0 0.0;    0.0 0.0 -0.5]; 
exp3   = [-0.5 0.0 0.0;   0.0 -0.5 0.0;   0.0 0.0 1.0]; 

omega1 = [0 -1 0;         1 0 0;          0 0 0]; 
omega2 = [0.0 0.0 -1.0;   0.0 0.0 0.0;    1.0 0.0 0.0];
omega3 = [0.0 0.0 0.0;    0.0 0.0 -1.0;   0.0 1.0 0.0]; 

shear1 = [0 1 0;          1 0 0;          0 0 0]; 
shear2 = [0.0 0.0 1.0;    0.0 0.0 0.0;    1.0 0.0 0.0];
shear3 = [0.0 0.0 0.0;    0.0 0.0 1.0;    0.0 1.0 0.0]; 
```

The frame of reference is such that the particle long axis is aligned with the x-direction.
The particle half axis are denoted as a,b,c with a>=b>=c.
Consequently, the particle aspect ratios are defined as lambda1 = a/c, lambda2 = b/c.
Results for lambda1 = [1,10] are presented.

