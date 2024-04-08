---
title: "The 2D Time Dependent Schrödinger Equation"
excerpt: "This PHYS 410 project delves into the computational exploration of quantum phenomena, focusing on solving the one-dimensional and two-dimensional time-dependent Schrödinger equations. In the one-dimensional case, the implementation involves discretization and the Crank-Nicolson method, with convergence testing and numerical experiments revealing the behavior of quantum particles interacting with barriers and wells. The two-dimensional extension utilizes the Alternating Direction Implicit (ADI) technique, offering a nuanced perspective on quantum dynamics in a broader spatial context. Numerical experiments, including scattering off various potentials and through double slits, illuminate complex phenomena such as self-interference. The project not only underscores the intricacies of quantum mechanics but also showcases the robustness of computational methods in simulating and visualizing these phenomena.
<br/><img src='/images/DoubleSlit_RectanglesSchematic.png'>
"
collection: portfolio
---

A full description for this project is to come!

![Double Slit Example!](/images/DoubleSlit_RectanglesSchematic.png)


# Introduction

The following report will closely follow some of Dr. Choptuik's Class Notes, as well as the Project 2 Notes.

## One Dimensional Case

I start the project by solving the one-dimensional time-dependent Schr\"odinger equation (SE) using the Crank-Nicolson (CN) method. The (continuum) 1D SE is

\begin{equation}
    i \\hbar \\frac{ \\partial \\psi(x, t)}{\\partial t} = - \\frac{\\hbar^2}{2m} \\frac{\\partial^2 \\psi(x,t)}{\\partial x^2} + V(x, t)\\psi(x,t)
\end{equation}

## Two Dimensional Case

In the second part of this project, I solve the two-dimensional SE using the ADI (Alternating-direction implicit) method. The (continuum) 2D SE is

\begin{equation}
    i \\hbar \\frac{ \\partial \\psi(x, y, t)}{\\partial t} = - \\frac{\\hbar^2}{2m} \\left( \\frac{\\partial^2 \\psi(x,y,t)}{\\partial x^2} + \\frac{\\partial^2 \\psi(x,y,t)}{\\partial y^2} \\right) + V(x, y)\\psi(x,y,t)
\end{equation}
