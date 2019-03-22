# 2Layer-Diffusion-Leachate-Analytical
2 Layer Diffusion Equation of Leachate, Analytical Fourier solution of Li & Cleall 2010

    <br />leachate diffusion in two-layer media
    <br />landfill on top, layer of impermeable clay of thickness h1 below landfill
    <br />normal soil stratum of thickness h2 below clay layer
    
    <br />reference: Li, Y. C., & Cleall, P. J. (2010).
    <br />Analytical solutions for contaminant diffusion in double-layered porous media.
    <br />Journal of Geotechnical and Geoenvironmental Engineering (ASCE)
    <br />Volume 136, No. 11, pages 1542-1554.
    
    <br />diffusion equation in each layare:
    <br />(1/Rd1)* dc_1/dt = Ds1 * d^2c_1/dz^2,    0<z<h1
    <br />(1/Rd2)* dc_2/dt = Ds2 * d^2c_2/dz^2,    h1<z<H
    
    <br />boundary condition:
    <br />c_1=c0 @ z=0
    <br />c_2=0 @ z=H
    
    <br />initial condition
    <br />c_1=c_2=0 at t=0
    
    <br />interface boundary condition
    <br />n1*Ds1*dc_1/dz=n2*Ds2*dc_2/dz  @ z=h1
    <br />c_1=c_2 @ z=h1
    
    <br />H=h1+h2 : overal thickness
    <br />Ds1 & Ds2 : diffusion coefficient
    <br />n1 & n2: porosities
    <br />Rd1 & Rd2: retardation factors
<br /> c1 & c2 : concentration in each layer
  
