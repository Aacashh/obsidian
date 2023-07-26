### Conservation of charge
- Continuity Equation
$$ \frac{\partial \rho}{\partial t} + \nabla \cdot (\rho \mathbf{v}) = 0 $$

where: 
- $\rho$ is the density of the fluid, 
- $t$ is the time
- $\mathbf{v}$ is the velocity vector field of the fluid,
- $\nabla \cdot (\rho \mathbf{v})$ is the divergence of the mass flux (the product of density and velocity).

The continuity equation in terms of the rate of change of a quantity can be written as:

$$
\frac{dQ}{dt} = \text{input} - \text{output} + \text{generation} - \text{consumption}
$$

where:
- $\frac{dQ}{dt}$ is the rate of change of the quantity `Q` with respect to time `t`,
- $\text{input}$ is the rate at which the quantity `Q` is added to the system,
- $\text{output}$ is the rate at which the quantity `Q` leaves the system,
- $\text{generation}$ is the rate at which the quantity `Q` is produced within the system,
- $\text{consumption}$ is the rate at which the quantity `Q` is used up within the system.


### Conservation of Energy

For a some charge distribution in a volume, the infinitesimal charge $dq$ in an infinitesimal volume $d\tau$ can be represented as:

$$
dq = \rho \, d\tau
$$

where:
- $\rho$ is the charge density,
- $d\tau$ is the infinitesimal volume.

The work $dW$ done by the electromagnetic field on this infinitesimal charge is the product of the charge and the electric potential $V$:

$$
dW = dq \, V = \rho \, V \, d\tau
$$

where:
- $V$ is the electric potential or voltage.

The total work $W$ done on the whole charge distribution in the volume $V$ is then the integral of this over the volume:

$$
W = \int_V \rho \, V \, d\tau
$$


The rate of work done, or power $P$, is the work done per unit time. If $dW$ is the infinitesimal work done in time $dt$, the power $P$ is $dW/dt$:

$$
P = \frac{dW}{dt}
$$

The rate of work done on the infinitesimal charge $dq$ is then:

$$
\frac{dW}{dt} = V \, \frac{dq}{dt}
$$

Here, $\frac{dq}{dt}$ is the current $I$, so:

$$
\frac{dW}{dt} = V \, I
$$

This is the standard relationship for power in electrical systems, with power being the product of voltage and current.
