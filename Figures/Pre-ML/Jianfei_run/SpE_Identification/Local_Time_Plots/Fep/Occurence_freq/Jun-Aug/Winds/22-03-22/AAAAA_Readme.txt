Calculating dUdz by calculating a logP pressure at the level interfaces, and using these to calculate dz

dU was calculated using midpoints giving final array length one shorter than usual sliced lev array

dz should have been shifted into local time but was mistakenly left on lon grid (whereas Uwinds & therefore dU were calculated in local time)