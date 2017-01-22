.. currentmodule:: prodyn

.. _prodyn:

Prodyn
============
**Prodyn** is an autonomous file, which is written in python and can be used with every example. This is the core and driving force of every dynamic programming implementation. Three main functions of it are described below in details.       

prepare_DP 
^^^^^^^^
The goal of this function is a creation of several arrays, which will be used subsequently. The simplified procedure of this creation for 1 and 2 states random examples is presented in the Figure 6.

.. figure:: img/prepare_dp.png
   :width: 70%
   :align: center
   
   Figure 6: Working principle of prepare_DP function
   
The table with states of the system, which is stored in **DP-States**, plays a role of input for the **prepare_DP**. Three new arrays are the main returns of the function. **X** is an array containing every possible condition of the system. It's size depends from the number of system's states. For example, any  condition of the system with 2 states is always characterized by two variables and **X** is, consequently, 2d. In addition, every system's condition corresponds to the specific number. These numbers are stored in an array **Xidx**, which is always 1-d. The third return **XX** is an array of arrays, from which **X** is built. In other words, **X** is the cartesian product of **XX**.       


DP_forward
^^^^^^^^
bla-bla

DP_backward
^^^^^^^^