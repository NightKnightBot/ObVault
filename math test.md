The given equation id easy to solve and has the form
$$N\left( t \right) = C{e^{ - \lambda t}}$$
To determine the constant $C$, it is necessary to indicate an initial value. If the amount of the material at the moment $t=0$ was $N_{0}$, then the radioactive decay law is written as
$$N\left( t \right) = {N_0}{e^{ - \lambda t}}$$
Further, we introduce two useful parameters that follow from the given law.
The half life or half life period $T$ of a radioactive material is the time required to decay to one-half of the initial value of the material. Hence, at the moment $T$:
$$N\left( T \right) = \frac{{{N_0}}}{2} = {N_0}{e^{ - \lambda T}}$$
The formula for the half life follows from here:
$${e^{ - \lambda T}} = \frac{1}{2},\;\; \Rightarrow - \lambda T = \ln \frac{1}{2} =  - \ln 2,\;\; \Rightarrow T = \frac{1}{\lambda }\ln 2$$
The average lifetime $\tau$ of a radioactive atom is given by
$$\tau  = \frac{1}{\lambda }$$
As it can be seen, the half life $T$ and the average lifetime $\tau$ are related to each other by the formula:
$$T = \tau \ln 2 \approx 0.693\,\tau$$
These 2 parameters vary widely for different substances. For example, the half life of Polonium-212 is less than 1 microseconds, but the half life of Thorium-232 is more than 1 billion years.

$\frac{dN}{dt}\propto N$
*Where N is number of nuclei*
*This can further be expressed as*  $\frac{dN}{dt}=- \lambda N$ 
where $\lambda$ is the proportionality constant

#### Given
Number of nuclei present initially is $N_0$.
Number of nuclei present at time $t$ is $N$.

#### Formula Used
$\log_ea-\log_eb=\log_e(\frac{a}{b})$ , where $a$ and $b$ are constants

#### Solution
$$\begin{array}{l}\partial N\partial t=-\lambda N\end{array}$$
After rearranging this,
$$
\begin{array}{l}\partial NN=-\lambda \partial t\end{array}$$


Integrating both sides will result in,
$$
\begin{array}{l}\int NN_{0}\partial NN=-\lambda \int tt_{0}\partial t\end{array}
$$
$$\begin{array}{l}InN-InN_{0}=-\lambda \left ( t-t_{0} \right )\end{array}$$
Here, $N_0$ represents the original number of nuclei in the sample at a time $t_0$, i.e. t=0.
Applying that in the equation results in;
$$\begin{array}{l}InNN_{0}=-\lambda t\end{array}$$
This further leads to,
$$\begin{array}{l}N_{t}=N_{0}^{e-\lambda t}\end{array}$$
This type of decay is exponential.