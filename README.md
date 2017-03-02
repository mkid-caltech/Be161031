Be161031: Jack's Be161031 1 micron no BCB device
==========================================

*Niobium device with some parallel plate resonators and some kids(?). Could
show resonators at 1.0, 1.8, or 2.8 GHz.

Cooldowns:
-----------

170216Be161031.h5 -
    >freqsweep.save_scatter("170216Be161031.h5",fwinsize=0.005,fwinstart=0.1,fwinend=4,plotting=False)
    >4.610K
    >Taken on 02/16/2017 9:14-10:24 AM

Opening h5 on Matlab:
>documentation for hdf5 files is available on the Matlab website
>EX: use "data=h5read('170216Be161031.h5','/S21/f')" to take the f data for channel S21
>use "data=h5read('170216Be161031.h5','/S22/z')" to take the z data for channel S22 and so on...
