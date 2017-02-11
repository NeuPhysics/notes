---
layout: single
title: "Gauge Symmetries and Lagrangian"
date: 2016-08-25
author: Lei Ma
summary: Lagrangian
---

Random notes for Section 14.1 of Halzen & Martin.
{: .notice}

## Conserved Quantities

**Conserved quantities are conserved locally in space, not just globally.**

In classical mechanics

1. Lagrangian is
   \begin{equation}
   L = T-V.
   \end{equation} 
2. Lagrange's equation

   \begin{equation}
   \frac{d}{dt}\left(  \frac{\partial L}{\partial \dot q_i} \right) - \frac{\partial L}{\partial q_i} = 0,
   \end{equation}

   where $q_i$ are the generalized coordinates and $\dot q_i \equiv \frac{d q_i}{dt}$.


To generalize to quantum fields, we generalize the generalized coordinates to fields, so that descretized coordinates $q_i$ becomes fields $\phi(x,t)$.

1. Lagrangian density is
	\begin{equation}
	\mathcal L (\phi,\partial \phi/\partial x_\mu, x_\mu).
	\end{equation}
2. Lagrangian is
	\begin{equation}
	L = \int \mathcal L d^3 x.
	\end{equation}
3. The equation of dynamics is Euler-Lagrangian equation
	\begin{equation}
	\frac{\partial }{\partial x_\mu} \left( \frac{ \partial \mathcal L }{ \partial ( \phi_{,\mu} ) } \right)  - \frac{\partial \mathcal L}{\partial \phi} = 0,
	\end{equation}
	where we denoted $\partial \phi/\partial x_\mu$ as $\phi_{,\mu}$.

**By convention, Lagrangian density is usually called Lagrangian in QFT.**

1. Klein-Gordon equation $(\Box^2 + m^2)\phi = 0$: Lagrangian is $\mathcal L = \frac{1}{2} \partial_\mu \phi \partial^\mu \phi - \frac{1}{2} m^2 \phi^2$.
2. Dirac equation: Lagrangian is $\mathcal L = i \bar \psi \gamma_\mu \partial^\mu \psi - m \bar \psi \psi$.
3. Maxwell equation $\partial_\mu F^{\mu\nu} = j^\nu$ ($F^{\mu\nu} = \partial^\mu A^\nu - \partial^\nu A^\mu$): Lagrangian is $\mathcal L = - \frac{1}{4} F_{\mu\nu} F^{\mu\nu} - j^\mu A_\mu $.
4. Massive photons $(\Box^2 + m^2)A^\mu= j^\mu$: Lagrangian is $\mathcal L = - \frac{1}{4} F_{\mu\nu} F^{\mu\nu} - j^\mu A_\mu + \frac{1}{2}m^2 A_\mu A^\mu$.


**One should connect Feynmann rules with Lagrangians.**

