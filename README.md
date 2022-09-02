These are the data products associated with arXiv:2208.14002
Please contact Jack Runburg at runburg [at] hawaii [dot] edu if you have any questions

Each directory corresponds to a different NFW dark matter distribution rho(r) where the directory name indicates the slope (i.e. nfw0-8 corresponds to an NFW distribution with gamma=0.8). Note that we use scale-free quantities throughout. This is for convenience. Units are determined by dimensional analysis.

To restore units, multiply the data products here by the appropriate dimensionful factor(s) listed below (fiducial values used in the paper are listed in parentheses):
- distance/radius: r_s (21 kpc)
- density: \rho_s (8e6 M_\odot kpc^{-3}) (directory names specify value of \rho_s)
- velocity: sqrt{4\pi G_N \rho_s r_s^2} (4.4e2 km s^{-1})
- energy/phi: velocity^2 (1.9e5 (km s^{-1})^2)
- velocity distribution, f(E): velocity^{3/2}\rho_s^{-1} (1.1e-3 (km s^{-1})^{3/2}M_\odot^{-1} kpc^3)
- J_factor: 2\rho_s^2 r_s (velocity / c)^{n} (2.7e15 (1.5e-3)^n/2 M_\odot^2 kpc^{-5})

In each directory, there are four files:

phi.txt: contains the scale-free gravitational potential Phi(r) where the first column of the data are the r values and the second column are the Phi values.
f.txt: contains the scale-free velocity distribution f(E) where the first column of the data are E values and the second column are the f values.
p2.txt: contains scale-free P2 (which is the analog of the square of the DM profile rho^2) where the first column are the r values, the second column are P2 for s-wave DM, the third column are P2 for p-wave DM, the third column are P2 for d-wave DM and the fourth column are P2 for Sommerfeld DM
j.txt: contains the scale-free J-factor, J(theta), where the first column are the theta values, the second column are J for s-wave DM, the third column are J for p-wave DM, the third column are J for d-wave DM and the fourth column are J for Sommerfeld DM. Note that these values are unnormalized. To get the same values as those seen in Figs. 1-4 of the paper, divide by J^{tot} (see Eq. 6 of the paper).

