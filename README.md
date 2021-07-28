# Ocean-Nav
This repository contains the development of two acoustic variables 
- *Potential Sub Surface Channel* which conveys the existence of a subsurface channel from a given sound speed profile.
- [WIP] *Slope of Something (Slope of Sound Profile)* that will indicate the amount of sound wave that is trapped inside a sound channel.

## Notes
### Potential Sub-Surface Channel
- ~~Create the 1D sub-surface channel detection routine~~
- ~~Integrate frequency cutoff variable and ΔC calculation~~
    - ~~Write a function to calculate ΔC from a given sound speed profile and fixed frequency cutoff~~
    - ~~Write two versions of the ΔC calculation routine, with given frequency cutoff and a fixed frequency cutoff~~
    - ~~Get feedback from DND~~

- Prepare the routine to integrate with ONAV
    - Transform the routine to a n-dimensional form to be able to used as derived variable in ONAV
        - ~~Prepare the delC calculation routine to return _ndarray_ instead of a single value~~
        - ~~Prepare the sub-surface chanel detection routine to return an _ndrray_ of boolean which will indicate the existence of sub-surface channel~~
